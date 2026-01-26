# Session Notes: January 26, 2026

## Overview
- **Topic**: BPE OOV Handling & Numerical Tokenization Analysis
- **Format**: Socratic Discussion + Comparative Research
- **Main Goal**: Understand how subword tokenization prevents OOV and how modern LLMs (GPT-4 vs Llama 3) optimize for mathematical reasoning.

## Initial Exploration
- **Student's Understanding**: Awaiting response to the baseline question regarding word-level vs subword-level OOV handling.

## Concepts Explained
- **BPE OOV Handling**: Explained the "safety net" of character/byte-level fallback. BPE removes the concept of "Unknown" tokens as long as the base character set is included.
- **Numerical Tokenization**:
    - **GPT-4 (cl100k_base)**: Uses regex `\p{N}{1,3}` to group digits into chunks of up to 3 (e.g., "123", "456").
    - **Llama 3**: Uses a specialized Tiktoken implementation that forces **individual digit tokenization** (e.g., "1", "2", "3", "4", "5", "6").
- **Mathematical Implications**: Discussed alignment, carry-over logic, and how individual digits act as a "positional scratchpad" for better arithmetic reasoning.

## Comprehension Checks
1. Why not just use character-level tokenization for everything?
2. How does a comma (e.g., "1,234") impact tokenization in these models?

## Topics Mastered
- BPE OOV fallback mechanism
- GPT-4 vs Llama 3 numerical regex patterns
- Tokenization impact on LLM arithmetic

## Knowledge Gaps Identified
- Specific merging logic differences between BPE (GPT) and WordPiece (BERT).
- Impact of multi-modal tokenization on numerical data (e.g., in VLMs).
