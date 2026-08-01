# Singireddy Meher Deepak

Computer Science undergrad in Hyderabad. I work on the whole stack of a machine
learning product, not one slice of it: the research and training, the services that
run inference, and the web or mobile front end sitting on top.

That has meant fairly different things at different times. Graph neural networks on
live market data. Recommender systems and the MLOps to keep them running. Language
models squeezed into an iOS keyboard extension. Next.js sites with Firebase behind
them. The common thread is that I'd rather own a thing end to end than hand it off
at the model boundary.

[Resume](resume.pdf)

---

### Graph neural networks for intraday options

A GNN that jointly embeds multiple stocks and learns the relations between them,
applied in real time to intraday options trading through the Zerodha Kite API.
Running on a live portfolio. Peak single-day return of 220%, against a 60% max
drawdown. The drawdown is the honest half of that number.

### Triver

A travel recommender built around user preference rather than popularity, using
SVD++, Seq2Seq, and graph neural networks. Deployed to the web with an automated
training-to-deployment workflow, inference optimization, and production monitoring.
Ongoing since 2021, and the project where I learned most of what I know about MLOps.

### Reinforcement learning

Implemented World Models (VAE, MDN-RNN, and an evolved controller) on CarRacing,
which is the one I'd point at first. Also worked through PPO, SAC, DDPG, and
curiosity-driven exploration from the original papers, and spent a while on GANs
before that. None of it is my own architecture. I wanted to know how the pieces
actually behave when you build them rather than read them.

### On-device language models, at KeyPoint Technologies (Xploree)

Sole developer of the language model and the iOS keyboard extension around it.
Trained a family of 4M to 11M parameter models as a drop-in replacement for the
product's existing autocorrect and next-word suggestion engine, then took them
through Core ML conversion, int8 quantization, and on-device benchmarking.

Accuracy was not the hard part. iOS gives a keyboard extension 66MB of memory for
everything it does. I got the working baseline down to 15MB by memory-mapping the
60k-word dictionary trie and the n-gram tables into evictable pages, which left
room for the model and a trie-constrained beam search on top.

---

### Competitions

| | |
|---|---|
| **Top 2%** | Stable Diffusion Image-to-Prompts (Kaggle, $50k) — fine-tuned a CLIP image encoder with an Efficient Channel Attention head to regress prompt embeddings on a cosine-similarity objective |
| **Top 10%** | BirdCLEF 2026 (Kaggle, $50k) — equiangular tight frame constrained embeddings to identify bird species with very few training recordings |
| **15th** | ConserVision — species classification robust to camera-trap noise: low light, occlusion, cropped frames |
| **All-India Top 5** | BlueLearn Designathon — a platform for restoring student interaction during remote learning |

---

### Education

**B.Sc. Computer Science** — Birla Institute of Technology and Science (BITS), Pilani · 2025–2028
Online Degree Programme.

**BBA, Artificial Intelligence and Data Science** — ICFAI, Hyderabad · 2024–2027
Full-time, on campus.

Two concurrent degrees, permitted under UGC's 2022 dual-degree policy: one online,
one on campus.

---

### Tools

**Languages** Python · Java · Swift · Kotlin · Go · JavaScript / TypeScript · PHP · MATLAB
**ML** PyTorch · scikit-learn · LLM training and fine-tuning · reinforcement learning · quantization · Core ML
**Web & Mobile** React · React Native · Next.js · SwiftUI · micro frontends · Firebase · Vercel
**Systems & Data** microservices · Kafka · NATS · Ejabberd · Docker · Kubernetes · PostgreSQL · MongoDB · Elasticsearch

---

Hyderabad, India · [meherdeepakpc@gmail.com](mailto:meherdeepakpc@gmail.com)
