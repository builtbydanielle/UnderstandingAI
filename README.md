# AI Quick Reference Guide

An interactive, single-page HTML reference guide covering artificial intelligence fundamentals — built for anyone who wants a practical, no-fluff introduction to how AI works and how to use it responsibly.

© 2026 Danielle D.

---

## Overview

This is a standalone `index.html` file. No build process, no dependencies, no server required. Open it in any modern browser and it works. Content is organized into six tabbed sections covering AI literacy from the ground up.

---

## Sections

**Basics** — Core vocabulary (model, training, parameters, inference, tokens, context window), a clear breakdown of what AI is and isn't, and expandable sections covering key technical concepts (hallucinations, bias, AGI, ASI, RAG, fine-tuning, LLMs, NLP, computer vision, few-shot learning) and the three AI learning methods: supervised, unsupervised, and reinforcement learning.

**AI Types** — Expandable entries for Generative AI, Machine Learning, Deep Learning, Predictive/Discriminative AI, Narrow AI, Multimodal AI, and Agentic AI. Each defines what it is, what it does, and gives real-world examples.

**Model Types** — Reference grid covering Language Models, Image Models, Audio Models, Video Models, Embedding Models, and APIs with representative tools for each. Expandable sections on open-source vs. closed-source models (trade-offs, when to use each, hybrid approaches) and a practical guide to running AI locally with Ollama, including hardware requirements, setup steps, and recommended starter models.

**Tools** — Overview of the current AI tool landscape: ChatGPT, Claude, Gemini, Midjourney, Stable Diffusion, GitHub Copilot, DALL-E, Perplexity, and ElevenLabs, each with a "best for" summary.

**Practical Use** — The most hands-on section. Covers common use cases, AI in marketing, prompt engineering basics, temperature and creativity settings, token limits and context windows, before/after prompt examples (vague vs. specific), a five-step workflow for any AI conversation, common mistakes to avoid, and a plain-language list of AI limitations.

**Ethics** — Eight warning-box entries covering privacy, copyright and ownership, job displacement, environmental impact, bias and fairness, transparency and accountability, misinformation, and the human-AI relationship. Closes with a best practices checklist for responsible AI use.

---

## Features

- Single file, zero dependencies — no npm, no build step, no server
- Tab-based navigation with fade transitions
- Expandable/collapsible accordion sections throughout
- Before/after prompt examples with visual red/green indicators
- Step-by-step instruction boxes
- Fully responsive — stacks cleanly on mobile
- Monospace typography (Space Mono / JetBrains Mono via Google Fonts)
- Minimal black-and-white design aesthetic

---

## Usage

```bash
open index.html
```

Or drag `index.html` into any browser. No installation required.

---

## Customization

All content and styles live in a single file. To update tool listings, add accordion sections, or adjust terminology, edit `index.html` directly. Styles are in a `<style>` block in the document `<head>`. The tab system and expandable sections are driven by a small vanilla JavaScript block at the bottom of the file.
