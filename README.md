
# Nishant Tiwari

Second-year B.Tech CSE @ IIIT Sonepat · Building AI systems and LLM pipelines
· Graduating 2029 · CGPA 8.9/10

GSoC 2027 aspirant — AI/ML + LLM infrastructure. Interested in research
engineering, LLM infra, and AI/ML internships.

## What I build

### Crater.ai — industrial AI maintenance intelligence

My main project: turn technical manuals and schematics into a structured
machine knowledge model, then use it for grounded diagnosis — with a
simulation twin that verifies a repair before anyone touches the machine.
Ingestion → machine model → diagnosis → verified-repair loop, plus a visual
twin and hypothesis tournament. A prototype, built end to end in FastAPI.

`FastAPI` `RAG` `Qdrant` `LLM pipelines` `Python`

### ResearchOS-v2 — can hidden states replace textual RAG?

A research project asking whether transformer hidden states / intermediate
vectors can serve as the information source for retrieval instead of text.
Perceiver-style compressor, 256 → 128, on Flan-T5-base: decoder MSE 0.020,
cosine 0.929, top-5 agreement 81%.

`PyTorch` `Transformers` `Hugging Face` `Python`

### Transformer_model — transformer from scratch in NumPy

Encoder-only transformer built from scratch: attention, multi-head
attention, LayerNorm, masked-language modelling. No framework internals
borrowed — built to understand what's actually inside the black box.

`NumPy` `Python` `Transformers`

### ai-game-builder — LLM pipeline · self-correction · RAG

Converts natural language prompts into playable Phaser.js games using a
multi-stage pipeline — GDD generation, code synthesis, validation,
iterative LLM correction loops, and persistent failure memory. Built to
explore what makes AI code generation reliable, not just fast.

`FastAPI` `Ollama` `Phaser.js` `RAG` `Python`

### open-ppt — full-stack · local-first AI

Local-first AI presentation generator. A staged pipeline (outline → slide
plan → structured content) feeds a React viewer. Runs entirely on Ollama —
no hosted API needed. Explores structured JSON generation over free-form
LLM output.

`FastAPI` `React` `Vite` `Framer Motion` `Ollama`

### mini-dl-framework — ML fundamentals · from scratch

Full forward + backward propagation engine in pure NumPy. Modular layers,
Adam optimizer with bias correction, dropout, gradient checking. Achieves
94% on MNIST with no PyTorch or TensorFlow.

`NumPy` `Python` `backprop` `Adam`

## Stack

|  |  |
| --- | --- |
| **Languages** | Python · C++ |
| **AI / ML** | LLM pipelines · RAG · fine-tuning · NumPy ML · PyTorch |
| **Backend** | FastAPI · Ollama · Qdrant |
| **Frontend** | React · Vite |

Second-year CS student, IIIT Sonepat. Interested in ML infrastructure,
AI tooling, and research. Open to research internships and remote roles.
