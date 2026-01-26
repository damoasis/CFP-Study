# LLM Engineering Study Tracker

**Last Updated**: January 26, 2026
**Target Goal**: Master LLM Engineering & Research Foundations
**Current Focus**: Architecture & Foundations

This document tracks your progress through the LLM Engineering curriculum.

---

## Quick Stats

📊 **Overall Progress**: 7/30 core topics = **23%**
📅 **Study Start Date**: January 26, 2026
🎯 **Current Milestone**: Fine-tuning & Alignment

---

## Domain Progress Summary

| Domain | Weight | Topics Covered | Status | Priority |
|--------|--------|----------------|--------|----------|
| **A. Foundations & Architecture** | 15% | 5/6 | 🟢 Mastered | Medium |
| **B. Pre-training & Data** | 15% | 0/5 | ⚪ Not Started | Medium |
| **C. Fine-tuning & Alignment** | **18%** ⭐ | 2/5 | 🟡 In Progress | **CRITICAL** |
| **D. Engineering: RAG & Prompting** | 17% | 0/4 | ⚪ Not Started | **HIGH** |
| **E. Evaluation & Benchmarking** | 12% | 0/4 | ⚪ Not Started | Medium |
| **F. Inference & Deployment** | 10% | 0/4 | ⚪ Not Started | Medium |
| **G. Agents & Multi-modality** | 13% | 0/4 | ⚪ Not Started | Low |

---

## A. Foundations & Architecture (15%)

### Topics to Master
- [x] **A.1 Transformer Architecture** (Encoder, Decoder, Encoder-Decoder)
- [x] **A.2 Attention Mechanisms** (Self-attention, Multi-head, KV-Cache)
- [x] **A.3 Tokenization** (BPE, WordPiece, SentencePiece)
- [x] **A.4 Positional Encodings** (Sinusoidal, RoPE, ALiBi)
- [x] **A.5 Activation & Normalization** (GeLU, RMSNorm, LayerNorm)
- [ ] **A.6 Mixture-of-Experts (MoE)**

---

## C. Fine-tuning & Alignment (18%)

### Topics to Master
- [ ] **C.10 Supervised Fine-Tuning (SFT)** (Instruction tuning, Prompt masking)
- [ ] **C.11 Alignment via RLHF** (PPO, Reward Models)
- [ ] **C.12 Direct Preference Optimization (DPO)**
- [x] **C.13 Efficient Fine-tuning (LoRA, QLoRA)**
- [x] **C.13a Hyperparameter Optimization** (Rank, Alpha, Target modules selection)
- [ ] **C.14 Multi-turn instruction following**

---

## Topics Mastered

- **Transformer Architecture**: Deep understanding of Encoder/Decoder blocks and their specific use cases (GPT, BERT, T5).
- **Attention Mechanisms**: Mastered QKV mechanism, Multi-Head Attention dimensionality, and KV-Cache optimization for inference.
- **Tokenization**: Understanding of BPE/Byte-level BPE, OOV mitigation, and digit tokenization impact on math.
- **Positional Encodings**: Understanding of sinusoidal vs. learned vs. rotary (RoPE) encodings.
- **Activation & Normalization**: Deep intuition on LayerNorm vs. BatchNorm and modern RMSNorm/GeLU.
- **Efficient Fine-tuning**: Mastery of LoRA/QLoRA principles, Rank/Alpha selection, and re-parameterization.

---

## Study Plan

**Phase 1: Foundations (Week 1)** - [x] COMPLETED
1. Transformer Architecture deep dive
2. Attention mechanisms and KV-Cache
3. Tokenization and Positional Encoding

**Phase 2: Training & Fine-tuning (Week 2)** - [ ] IN PROGRESS
1. SFT and Instruction Tuning
2. LoRA/QLoRA hands-on
3. RLHF vs DPO


**Phase 3: RAG & Applications (Week 3)**
1. RAG pipeline implementation
2. Vector DB selection and optimization
3. Advanced Prompting techniques

**Phase 4: Optimization & Agents (Week 4)**
1. Quantization and efficient serving
2. Building Agentic workflows
3. Multimodal exploration
