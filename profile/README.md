<div align="center">
  <a href="https://github.com/imece-ai">
    <img alt="IMECE Logo" src="https://raw.githubusercontent.com/imece-ai/.github/main/profile/logo.svg" width="50%">
  </a>
</div>

<div align="center">
  <h3>Build AI agents that run entirely on your device.</h3>
  <p><em>Zero API dependency. Zero cloud lock-in. Full sovereignty.</em></p>
</div>

<div>
  <p align="center">
    <a href="https://x.com/imeceai"><img src="https://img.shields.io/badge/X/Twitter-000000?style=for-the-badge&logo=x&logoColor=white&logoSize=auto" /></a>
    <a href="https://www.linkedin.com/company/imece-ai"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&logoSize=auto" /></a>
    <a href="https://www.youtube.com/@imeceai"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white&logoSize=auto" /></a>
    <a href="https://github.com/imece-ai"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&logoSize=auto" /></a>
  </p>
</div>

---

IMECE is an open-source, local-first autonomous agent framework built in Rust. Every component, including LLM inference, embeddings, vector memory, and multi-agent orchestration, runs entirely on-device, with no cloud calls, no API keys, and no data leaving your machine.

## Core Library

- [`imece-core`](https://github.com/imece-ai/imece-core) — Rust-native autonomous agent framework: local LLM inference via llama.cpp FFI, KV-Cache "Time Travel" rollback, chain-of-memory (DMCE), an async actor swarm, and on-device embeddings via ONNX Runtime.

## Planned

- **`PyIMECE`** — Python bindings via PyO3/maturin, bringing imece-core's performance to the Python AI/ML ecosystem with a familiar API.

## Learn More

- [**imece-core Documentation**](https://github.com/imece-ai/imece-core#readme) — architecture, building, usage examples
- [**DMCE Algorithm**](https://arxiv.org/abs/2601.14287v1) — the chain-of-memory paper that inspired Module 1

## License

AGPL-3.0 — see individual repositories for details.
