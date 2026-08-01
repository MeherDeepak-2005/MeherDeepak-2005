# Singireddy Meher Deepak

Computer Science undergrad in Hyderabad. I build small, efficient machine learning —
models that have to run on the device, inside a real memory budget, not in a notebook.

Most of what I do ends up being the full path: training the model, shrinking it,
converting it, and shipping the thing it runs inside.

---

### On-device language models — KeyPoint Technologies (Xploree)

Sole developer of the language model and the iOS keyboard extension around it.
Researched and trained a family of **4M to 11M parameter** models as a drop-in
replacement for the product's existing autocorrect and next-word suggestion engine,
then took them end to end — data preparation, training, Core ML conversion with int8
quantization, on-device benchmarking.

The accuracy was not the hard part. iOS gives a keyboard extension **66MB of memory,
total**, for everything. Got the working baseline down to **15MB** by memory-mapping
the 60k-word dictionary trie and the n-gram tables into clean, evictable pages, which
left enough headroom for the model and a trie-constrained beam search on top.

### Graph neural networks for intraday options

A GNN that jointly embeds multiple stocks and learns the relations between them,
applied in real time to intraday options trading through the Zerodha Kite API.
Running on a live portfolio. Peak single-day return of 220%, against a 60% max
drawdown — the drawdown is the honest half of that number.

### Triver

A travel recommender built around user preference rather than popularity — SVD++,
Seq2Seq, and graph neural networks, deployed to the web with an automated
training-to-deployment workflow, inference optimization, and production monitoring.
Ongoing since 2021, and the project where I learned most of what I know about MLOps.

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

Two concurrent degrees, permitted under UGC's 2022 dual-degree policy — one online,
one on campus.

---

### Tools

**Languages** Python · Java · Swift · Kotlin · Go · JavaScript / TypeScript · PHP · MATLAB
**ML** PyTorch · scikit-learn · Core ML · on-device deployment · quantization
**Web & Mobile** React · React Native · Next.js · SwiftUI · Firebase · Vercel
**Data & Infra** PostgreSQL · MongoDB · Elasticsearch · Kafka · NATS · Docker · Kubernetes

---

Hyderabad, India · [meherdeepakpc@gmail.com](mailto:meherdeepakpc@gmail.com)
