# prismarine-search

A curated knowledge dataset for Mineflayer and the PrismarineJS ecosystem, created as part of my journey to learn how to train and enhance LLMs using real-world codebases, API structure, and community discussions.

---

## 🧠 What is this?

This is a structured dataset of technical Q&A, metadata, and API insights.

It focuses on the [PrismarineJS](https://github.com/PrismarineJS) ecosystem — especially [`mineflayer`](https://github.com/PrismarineJS/mineflayer) — and aims to help LLMs answer questions more accurately across its projects.

---

## 🤔 Why?

Because I wanted to see what I could build in my spare time using real-world data — no formal education, just curiosity and commitment. This project might evolve, but the goal is to learn and experiment with AI in a niche that I care about.

---

## 📦 What’s Inside

- `data.jsonl` — A JSONL file of validated entries, each containing:
  - `type`: Entry classification
    - `QA`: Question + Answer
    - `CODE`: Code snippet (generated or requested)
    - `EXPLAIN`: Technical explanation
    - `DEBUG`: Error diagnosis or fix
    - `PLUGIN`: Plugin-specific guidance
    - `CONCEPT`: Goal translated to implementation idea

---

## 🛠️ Goals

This dataset is intended for use in:
- 🔍 Retrieval-augmented generation (RAG)
- 🧪 Fine-tuning lightweight LLMs
- 📚 Embedding-based search and smart autocompletion

---

## 🚧 Roadmap

- [x] Format and clean Q&A data
- [ ] Manual review of all entries for accuracy
- [ ] Link GitHub metadata (types, events, cross-repo structure)
- [ ] Improve dataset breadth and depth with smarter filtering
- [ ] Experiment with small model fine-tuning or playground UI

---

## 🙌 Contributing

Suggestions, corrections, or new entries are welcome!  
Open a PR, submit an issue, or DM me on Discord.
