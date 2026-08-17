### Hey, I'm 0xVanta. 👋

Static analysis is what I do. Reversing binaries, pulling protocol formats apart,
and building tooling that makes other people's code tell the truth about
itself. I run [Vanta Labs](https://vanta-labs.dev) out of Karlsruhe, where the
core rule is simple: **if you cannot point at the bytes, you do not have an
answer.**

---

### What I build

| Project | What it does |
|---|---|
| [**QuantumSeal**](https://github.com/mpaymenremora/QuantumSeal) | Post-quantum migration workbench. Inventories the crypto in a source tree — RSA, ECC, MD5, TLS, ML-KEM — and charts it as a scored CryptoBOM with migration priorities. Rust CLI, zero deps. |
| [**CacheCraft**](https://github.com/mpaymenremora/CacheCraft) | Semantic cache strategy bench. Replays recorded request traces through exact/prefix/overlap/route policies and measures which one actually pays off. Python + Go, dependency-free. |

Both are static-analysis instruments, not libraries that pretend to be secure.
A finding is a coordinate for human review, never a verdict.

---

### What I'm usually doing

- 🔍 Reversing binaries and mapping protocol formats (the `[static analysis]` part of the day job)
- 🧱 Building offline analysis tooling — no network calls, no hidden dependencies
- 📐 Reading RFCs, FIPS documents, and disassembly so the tooling has a spec to point at
- 🗄️ Occasionally looking at caches, latencies, and where the time actually goes

### Things I care about

- **Byte-level honesty** — if a tool cannot cite the source span of its claim, the claim is a guess
- **Deterministic output** — the same input must produce the same bytes, on every machine, forever
- **Dependency-free where it matters** — the smaller the surface, the easier it is to audit

---

### Contact

- 📫 [vanta-labs.dev](https://vanta-labs.dev)
- 💬 Low-level systems, static analysis, post-quantum migration — open to discussion