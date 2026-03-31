# Repolex Knowledge Graph of pallets/itsdangerous

RDF knowledge graph data for [pallets/itsdangerous](https://github.com/pallets/itsdangerous), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pallets/itsdangerous
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 0c6a4b2e930a645ddddd54eaaef75b6ed1d165ed.nq.gz
│   ├── 183d7f6df5d88e0e478f7687b0b0e78a0f6168a1.nq.gz
│   ├── 1e941d8ca3dfaa2522e04702ac10f2dd8c9cd9f7.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 3879e8529a60d099ec588e785ad6fc5d39d2bc1a.nq.gz
│   ├── 3c7598b9f7a482da380ce28fd7d4c36d49674e48.nq.gz
│   ├── 51ed3a4b9069e556bdeb86ee96817ec7d95799f1.nq.gz
│   ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 9aa6d7aeb9b737fb967ce8bcb2b158e75bb0a1f0.nq.gz
│   ├── 9b99664b655a51e888b28955b5ef9fd3b6dbb6aa.nq.gz
│   ├── 9bca27fe9bb3a87f575c2922da56ac7c0f5a9444.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── ba34fcd25e4dda256ed99e27f57d274a2327d517.nq.gz
│   ├── cde4bfc6cc22d6d080cd484070ed4dd47d24e3eb.nq.gz
│   ├── d0a3da2b8a39b050099aff5a12f7486cba2b03c2.nq.gz
│   ├── d68d1a21b046d8b389ba84a83f9c1f9eafc63d86.nq.gz
│   ├── ea3e37030b13b989b49cf7dfbf5f43f1add32aaf.nq.gz
│   ├── ef72aa99092a70d46f0f7163e23fac12c6b9468d.nq.gz
│   └── fb4d282217d513573ed8ca77bf853ced3588ff32.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 18c9844cdfa2727d5951e8627ab97b70186065a2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 26 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[pallets/itsdangerous](https://github.com/pallets/itsdangerous)

---
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
