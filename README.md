# LLM Engineering Study Repository

This is a personal study repository for mastering **Large Language Model (LLM) Engineering and Research Foundations**. 

I've transitioned this project from a professional certification (CFP) prep to a technical learning environment for AI engineering, using the same successful **AI-powered guided learning** methodology.

## How This Works

This repository uses Claude Code as an interactive LLM engineering tutor that:
- Teaches using the **Socratic method** (asking what you know first)
- Provides concise (~200 word) technical explanations
- Verifies understanding with follow-up questions
- Adapts teaching style based on your responses
- **Tracks every learning session to personalize your study journey**

## Learning Curriculum

The study is organized into 7 principal knowledge domains:
1. **Foundations & Architecture** (Transformers, Attention, Tokenization)
2. **Pre-training & Data** (Scaling laws, Data pipelines, Distributed training)
3. **Fine-tuning & Alignment** (SFT, RLHF, DPO, LoRA)
4. **Engineering: RAG & Prompting** (Vector DBs, RAG pipelines, Prompt engineering)
5. **Evaluation & Benchmarking** (MMLU, LLM-as-a-judge, Hallucinations)
6. **Inference & Deployment** (Quantization, vLLM, Speculative decoding)
7. **Agents & Multi-modality** (Tool use, VLM, Planning)

## Repository Structure

```
/sessions/                    # Daily learning sessions documented
  /YYYY-MM-DD/               # One folder per study day
    session-notes.md         # Detailed notes and progress for each session

/progress/                    # Single source of truth for learning progress
  llm-study-tracker.md       # Comprehensive tracker with:
                             # - All knowledge domains mapped
                             # - Topics mastered
                             # - Knowledge gaps identified
                             # - Dynamic study plan

CLAUDE.md                     # AI tutor instructions (Socratic method)
README.md                     # This file
```

## How to Use

### Daily Study Sessions

1. Open Claude Code in this repository
2. Ask questions about LLM topics naturally (e.g., "How does RoPE work?")
3. Answer the comprehension check questions Claude asks
4. After each session, Claude will automatically document your progress in `/sessions/` and update `/progress/llm-study-tracker.md`

### Track Your Progress

View your comprehensive study tracker at `/progress/llm-study-tracker.md` to see your mastery across different domains and identify what to focus on next.

## Study Philosophy

**Guided Learning Approach:**
- **Conversational & Non-judgmental**: A "study buddy" rather than a lecturer.
- **Active Recall**: Built-in verification steps to ensure concept retention.
- **Adaptability**: Explanations pivot based on your current understanding.
- **Evidence-Based**: Technical details are verified against original research papers (Vaswani et al., etc.).

---

## About the Author

This repository was originally created to help me pass the CFP exam (which it did!). Now, I'm repurposing the methodology to dive deep into the world of Large Language Models.

**Connect with me**: [linkedin.com/in/chenran818](https://linkedin.com/in/chenran818)
