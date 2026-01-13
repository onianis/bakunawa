# Bakunawa

_The submarine named after the dragon._

_Because Bakuwana dives **deep**._

---

Bakunawa is a tool that analyzes AI models and validates integrity, audits structure, and detects security threats such
as pickle bombs and corruption.

Bakunawa is a zero-copy tool which means that it has (will have) the ability to efficiently analyze massive files
without loading them into memory. The goal is to make it significantly faster than PyTorch for this specific purpose.

Bakunawa is entirely written in Rust and serves three main purposes beyond its real-world utility:

- Being an academic exercise and an excellent opportunity for me to learn Rust;
- Helping me familiarize myself with the inner workings and structure of AI models and byte-level file analysis;
- Being a cornerstone CV project.

