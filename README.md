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
├── aggregate
│   ├── ast
│   │   ├── 1848718e1386ebeaec990ff34c20fb05ec3008d7.nq.gz
│   │   ├── 18c9844cdfa2727d5951e8627ab97b70186065a2.nq.gz
│   │   ├── 59f3bf7877e21af8e5571993edb6834744858583.nq.gz
│   │   ├── 847cbb85b1c4e2a431d8547759495bb56a2e6c83.nq.gz
│   │   └── b5352b34c57cd680aaef53d07238c41c021c2032.nq.gz
│   ├── lsp
│   │   ├── 1848718e1386ebeaec990ff34c20fb05ec3008d7.nq.gz
│   │   ├── 18c9844cdfa2727d5951e8627ab97b70186065a2.nq.gz
│   │   ├── 59f3bf7877e21af8e5571993edb6834744858583.nq.gz
│   │   ├── 847cbb85b1c4e2a431d8547759495bb56a2e6c83.nq.gz
│   │   └── b5352b34c57cd680aaef53d07238c41c021c2032.nq.gz
│   └── repolex
│       ├── 1848718e1386ebeaec990ff34c20fb05ec3008d7.nq.gz
│       ├── 18c9844cdfa2727d5951e8627ab97b70186065a2.nq.gz
│       ├── 59f3bf7877e21af8e5571993edb6834744858583.nq.gz
│       ├── 847cbb85b1c4e2a431d8547759495bb56a2e6c83.nq.gz
│       └── b5352b34c57cd680aaef53d07238c41c021c2032.nq.gz
├── blob
│   ├── 03b63601bd74cea8979032d6403adfafb64fb273.nq.gz
│   ├── 0c6a4b2e930a645ddddd54eaaef75b6ed1d165ed.nq.gz
│   ├── 11c0c4515fdf8fbb66dacd55ecd67a7ca23d042f.nq.gz
│   ├── 183d7f6df5d88e0e478f7687b0b0e78a0f6168a1.nq.gz
│   ├── 192e2a29ae817252b6c4ec58fce8a0fe3287b3c0.nq.gz
│   ├── 1e941d8ca3dfaa2522e04702ac10f2dd8c9cd9f7.nq.gz
│   ├── 2155a4407d429c2dfb3f722ff315fcd2e53174c0.nq.gz
│   ├── 25af6a7f2ae7d9fbb2e2ebea2a857e4ebd8b2192.nq.gz
│   ├── 33f47449c11d241e36c83d7f95d819bbe56e2c8f.nq.gz
│   ├── 35cd0012916cb2ba0c478e2fe850fc740d94d861.nq.gz
│   ├── 3879e8529a60d099ec588e785ad6fc5d39d2bc1a.nq.gz
│   ├── 3be72ad7522b2eacfbda6b077171bc4d0038ff85.nq.gz
│   ├── 3c7598b9f7a482da380ce28fd7d4c36d49674e48.nq.gz
│   ├── 4577a08ddd589d7dcbfceddd68d981291800c825.nq.gz
│   ├── 51ed3a4b9069e556bdeb86ee96817ec7d95799f1.nq.gz
│   ├── 640d2976666681f7922d3adf4513e6492d2e7f55.nq.gz
│   ├── 652c0500f752f4b3d0354230614066a56aa681f4.nq.gz
│   ├── 66b6e4c2f3b55b25afd9716f9d3c5afb47b15d4e.nq.gz
│   ├── 8cd4d41b8e735094d085da9ecce0e63004d0deb0.nq.gz
│   ├── 8daab7ee6efe3b6f3c2a2594b711e7a9026eb5e2.nq.gz
│   ├── 94aef0a0d527d9143e781d274935af79cbd9d2a9.nq.gz
│   ├── 995b94337260973d683b4252c944929af94de321.nq.gz
│   ├── 9aa6d7aeb9b737fb967ce8bcb2b158e75bb0a1f0.nq.gz
│   ├── 9b99664b655a51e888b28955b5ef9fd3b6dbb6aa.nq.gz
│   ├── 9bca27fe9bb3a87f575c2922da56ac7c0f5a9444.nq.gz
│   ├── af29ed9f0e0458b53c35ac4c69e7d81a02e127d1.nq.gz
│   ├── b3292bdff8ed5429eedd7f409839979d408beb6a.nq.gz
│   ├── b542371d5de49a382fc0b21e10ea5b19918822f2.nq.gz
│   ├── ba34fcd25e4dda256ed99e27f57d274a2327d517.nq.gz
│   ├── bd3b2b81c16a79617c00fed294f4361980428ee4.nq.gz
│   ├── c30d3a142f459ec8bd54482575542b5992b69ffd.nq.gz
│   ├── c3d3922246a8ff27ba28f3dd88c1b1e39e2a7425.nq.gz
│   ├── c3ee65f50e7af8da324985768663d4f63ff16b71.nq.gz
│   ├── cd14253a627a6a13e2adae4c3d0c730892c82dec.nq.gz
│   ├── cde4bfc6cc22d6d080cd484070ed4dd47d24e3eb.nq.gz
│   ├── d0a3da2b8a39b050099aff5a12f7486cba2b03c2.nq.gz
│   ├── d65f9bd5f31e10f8e9dab56e76cde02abe1e5cc1.nq.gz
│   ├── d68d1a21b046d8b389ba84a83f9c1f9eafc63d86.nq.gz
│   ├── de36a067b92702a59111e84edee1ecf305b21c17.nq.gz
│   ├── e9ac0b0569d2e5df7700246f079b0fad8cf398b7.nq.gz
│   ├── ea3e37030b13b989b49cf7dfbf5f43f1add32aaf.nq.gz
│   ├── ef72aa99092a70d46f0f7163e23fac12c6b9468d.nq.gz
│   ├── f31f46c1312f4b316c58f02c2e5e02d77a21bb73.nq.gz
│   ├── f8b0d2ef31df4b8609b3b26190c88db211966589.nq.gz
│   ├── fb4d282217d513573ed8ca77bf853ced3588ff32.nq.gz
│   └── fcb4730a15711bc1feaa5fd9a43d097da4399334.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 1848718e1386ebeaec990ff34c20fb05ec3008d7.nq.gz
│   ├── 18c9844cdfa2727d5951e8627ab97b70186065a2.nq.gz
│   ├── 59f3bf7877e21af8e5571993edb6834744858583.nq.gz
│   ├── 847cbb85b1c4e2a431d8547759495bb56a2e6c83.nq.gz
│   └── b5352b34c57cd680aaef53d07238c41c021c2032.nq.gz
├── filetree
│   ├── 1848718e1386ebeaec990ff34c20fb05ec3008d7.nq.gz
│   ├── 18c9844cdfa2727d5951e8627ab97b70186065a2.nq.gz
│   ├── 56ddae16b77ef23efc4ded9d3411c13ef9ce3cf2.nq.gz
│   ├── 59f3bf7877e21af8e5571993edb6834744858583.nq.gz
│   ├── 847cbb85b1c4e2a431d8547759495bb56a2e6c83.nq.gz
│   ├── b5352b34c57cd680aaef53d07238c41c021c2032.nq.gz
│   └── dfa3a8c7573836aa7cdbc57bf6a13c3780710b5a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
