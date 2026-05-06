---
name: nano-gpt-workflows
description: Workflow for building, training, debugging, and understanding small GPT-style language models using clean transformer implementations, tokenizer systems, and minimalist machine learning engineering practices.
---

# NanoGPT Workflows

## Overview

This skill enables Claude to guide users through building and understanding small GPT-style language models using minimalist and educational machine learning workflows inspired by NanoGPT-style implementations.

The workflow focuses on:
- transformer fundamentals
- tokenizer systems
- training loops
- dataset preparation
- attention mechanisms
- inference pipelines
- debugging neural networks
- clean ML engineering practices

The goal is to help users understand how modern language models actually work while keeping implementations:
- readable
- minimal
- educational
- scalable
- experimentally flexible

This workflow prioritizes first-principles understanding over framework abstraction.

---

# Setup

Before starting:

1. Install Python:
   https://www.python.org

2. Create a virtual environment:

```bash
python -m venv venv
```

3. Activate the environment:

```bash
source venv/bin/activate
```

4. Install PyTorch:

```bash
pip install torch torchvision
```

5. Install additional dependencies:

```bash
pip install numpy matplotlib tiktoken datasets
```

Recommended tools:
- VS Code
- Jupyter Notebook
- PyTorch
- CUDA-enabled GPU (optional)

Recommended extensions:
- Python
- Jupyter
- Pylance

Optional:
- Weights & Biases
- Hugging Face datasets
- TensorBoard

---

# Inputs Required

- Training dataset
- Tokenizer configuration
- Model size requirements
- Training objectives

Optional:
- Pretrained checkpoints
- Evaluation prompts
- Custom datasets
- Fine-tuning objectives

---

# When to Use This Skill

Use this skill when:
- learning transformer fundamentals
- building small GPT models
- understanding attention systems
- experimenting with tokenization
- training toy language models
- studying LLM internals
- debugging training systems
- learning practical ML engineering

---

# When NOT to Use

Do NOT use this skill for:
- production-scale distributed training
- massive enterprise ML infrastructure
- black-box API-only workflows
- highly abstracted no-code AI systems

---

# Example Use Case

> Train a small GPT-style model on custom technical documentation.

Claude should:

1. Prepare the dataset
2. Build tokenizer workflows
3. Implement transformer architecture
4. Configure training loops
5. Monitor loss behavior
6. Debug attention or gradient issues
7. Generate inference samples
8. Evaluate model quality

Final result should:
- remain understandable
- use clean implementations
- support experimentation
- teach transformer fundamentals
- remain easy to debug

---

# Core NanoGPT Principles

## 1. Understand Systems From First Principles

The workflow should prioritize understanding:
- how transformers work
- how tokenization works
- how gradients behave
- how training loops function

Claude should avoid:
- unnecessary abstraction
- hidden magic
- framework dependency without understanding

Understanding fundamentals improves:
- debugging ability
- experimentation
- ML intuition

---

## 2. Keep Implementations Minimal

Minimal systems are easier to:
- debug
- learn from
- extend
- optimize

Preferred workflow:
- small files
- readable code
- modular systems
- explicit logic

Avoid:
- overly abstracted architectures
- unnecessary framework complexity
- hidden side effects

Simple systems improve:
- learning speed
- engineering quality
- experimentation

---

## 3. Tokenization Matters Deeply

Tokenization directly affects:
- training quality
- inference behavior
- context efficiency
- model understanding

Claude should explain:
- BPE tokenization
- vocabulary construction
- token boundaries
- context windows
- token efficiency

Good tokenizer design improves:
- learning quality
- model efficiency
- generation consistency

---

## 4. Attention Is the Core Mechanism

Transformers rely heavily on:
- self-attention
- token relationships
- contextual weighting

Claude should help users understand:
- query/key/value systems
- attention maps
- causal masking
- positional encoding

Attention systems should remain:
- interpretable
- visualizable
- debuggable

---

## 5. Debugging Is a Core Skill

Training failures are common in ML workflows.

Claude should help diagnose:
- exploding gradients
- unstable loss
- dead activations
- tokenization bugs
- attention instability
- overfitting

Good debugging improves:
- training reliability
- experimentation speed
- learning depth

---

# Workflow

## 1. Prepare the Dataset

Start by:
- collecting training data
- cleaning corrupted samples
- normalizing formatting
- splitting train/validation sets

Good datasets improve:
- training stability
- generation quality
- model understanding

Avoid:
- noisy duplicated data
- inconsistent formatting
- low-quality samples

---

## 2. Build the Tokenizer

Create or configure:
- vocabulary
- token mappings
- encoding systems
- context handling

Validate:
- token efficiency
- vocabulary quality
- encoding consistency

Claude should explain:
- how text becomes tokens
- why tokenization matters
- how context windows work

---

## 3. Implement the Transformer

Build:
- embeddings
- positional encoding
- self-attention layers
- feed-forward blocks
- layer normalization
- output heads

Keep implementations:
- readable
- modular
- educational

Avoid:
- excessive abstraction
- hidden framework complexity

---

## 4. Configure Training Loops

Set up:
- batching
- optimization
- learning rates
- checkpointing
- evaluation intervals

Monitor:
- training loss
- validation loss
- gradient stability
- memory usage

Good training loops improve:
- reproducibility
- debugging
- scalability

---

## 5. Train Incrementally

Start with:
- tiny models
- small datasets
- short context windows

Validate:
- loss reduction
- generation quality
- attention behavior

Incremental scaling improves:
- debugging
- learning
- experimentation quality

---

## 6. Debug & Analyze

Inspect:
- attention maps
- token predictions
- loss curves
- sampling quality

Claude should help identify:
- unstable training
- weak tokenization
- bad sampling behavior
- overfitting patterns

Debugging improves:
- understanding
- training reliability
- model quality

---

## 7. Generate Inference Samples

Test:
- text generation
- completion quality
- coherence
- repetition behavior
- prompt conditioning

Validate:
- output consistency
- token flow
- contextual understanding

---

## 8. Refine & Iterate

Improve:
- datasets
- tokenizer quality
- architecture
- hyperparameters
- sampling systems

The workflow should evolve through:
- experimentation
- observation
- simplification
- iterative learning

---

# Output Expectations

The final output should include:
- clean transformer implementations
- understandable training systems
- tokenizer workflows
- reproducible training pipelines
- interpretable model behavior
- educational ML engineering structure

The workflow itself should remain:
- minimal
- readable
- modular
- educational
- experimentation-friendly

---

# Execution Strategy (for AI agents)

The agent should:

1. Prioritize first-principles understanding
2. Keep implementations minimal and readable
3. Explain transformer systems clearly
4. Detect training instability proactively
5. Encourage experimentation and debugging
6. Optimize for educational clarity and engineering quality

The workflow should optimize for:
- understanding
- reproducibility
- debuggability
- experimentation
- ML intuition

---

# Best Practices

- Start with tiny models first
- Keep implementations readable
- Validate datasets carefully
- Monitor loss continuously
- Debug incrementally
- Visualize attention whenever possible
- Prefer simplicity over unnecessary abstraction

---

# Notes

- Minimal transformer implementations teach fundamentals best
- Tokenization quality strongly affects model behavior
- Most ML intuition comes from experimentation and debugging
- Attention mechanisms are central to modern LLMs
- Simple, understandable systems scale better for learning and iteration
