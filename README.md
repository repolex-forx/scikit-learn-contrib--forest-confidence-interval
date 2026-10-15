# Repolex Knowledge Graph of scikit-learn-contrib/forest-confidence-interval

RDF knowledge graph data for [scikit-learn-contrib/forest-confidence-interval](https://github.com/scikit-learn-contrib/forest-confidence-interval), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download scikit-learn-contrib/forest-confidence-interval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 582058827ab735b3ffc1a18a07590ff977f7e99d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 582058827ab735b3ffc1a18a07590ff977f7e99d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0d7669290367e7ba6cfdc3d0b203243647e6e434.nq.gz
│   ├── 1120f4af87225d485fabac7ff238ea77a01bdcbd.nq.gz
│   ├── 1b517e7fa6a8886b82cfce580018379403a933a5.nq.gz
│   ├── 1b962e90c56a3070b22c914141a95457fe90cc14.nq.gz
│   ├── 23502ebdd5275faab820fefc18250af715152764.nq.gz
│   ├── 2c4ea31b69c7f83e68c639f6f2119b792ba7ebd3.nq.gz
│   ├── 3928c727ba28c7758cc44fdf10b75702ca389407.nq.gz
│   ├── 3adfb4cb45e5e29ecda70239f18cd6a6cdd59e47.nq.gz
│   ├── 3eef97467222900287d032493c53eae152d5d599.nq.gz
│   ├── 473253b41c15c7f2b755eada7961a1f6156fc3bf.nq.gz
│   ├── 4ba355d57c873dcd0f43e0471b0df1b8d2a98374.nq.gz
│   ├── 514ccc1ad05cc1e7284dfbf914447cd804b45831.nq.gz
│   ├── 51f62969773b912207b69eab6d8c48eb30b1520e.nq.gz
│   ├── 51f9fdc326b3f923fcc14d992198e9334f48c95a.nq.gz
│   ├── 53e99776aaf581e702e05d22688ea0b2a0e0139e.nq.gz
│   ├── 5428a3555f2061505475358789d145ae37a65687.nq.gz
│   ├── 55eae1341349fa4f26ddba5f92af50b1e68d8b3b.nq.gz
│   ├── 5a47b06c4970b35e961ee497ea8032d2e69f2ec4.nq.gz
│   ├── 664a9b0b379c8997ec5ec20a40d5116fee0cfed3.nq.gz
│   ├── 71400b3bed91872f52a0f4b108240c0e4b3c1a51.nq.gz
│   ├── 7542c2589123a879dfec10425244fa7167c954c7.nq.gz
│   ├── 76f8fd010fa8079b6646abcd0600795f433ec0d8.nq.gz
│   ├── 7ca5c54dfabfeaccb7da6d3dcac1279b9e9cd101.nq.gz
│   ├── 821f3d54af671ab5023c05c1b726eb0d2d12fde2.nq.gz
│   ├── 917dcd37e7eb5146b82f06113ef6161a3205cf8d.nq.gz
│   ├── 9803777f71b8be5c1ac78de17232a73e18d69c69.nq.gz
│   ├── 9a8f98d7f4a0a551c984d36ec0a4a0e03dd56522.nq.gz
│   ├── a402eda0142976cb7b8578933a908eabbcd80e62.nq.gz
│   ├── acdf57848a5ca2886681c5d4baa1cccdacd7280b.nq.gz
│   ├── af1794f7849a4fe270534694e7ffa7505b90f0a6.nq.gz
│   ├── c22b85505465245907abb56237aabc610f479d62.nq.gz
│   ├── c2fb2d88201275766a81cc9980e523909e5a4e8e.nq.gz
│   ├── cc3c808dc09e5c54f46fa23a8e8aced667d10f83.nq.gz
│   ├── cde07d5b231bd8d27f1e2df179a64eb70841f9a3.nq.gz
│   ├── d09aae311a744420380762bc3a9f0c19848ed27e.nq.gz
│   ├── d87f56998175b91b21e7ee53ea806064fe0f78e1.nq.gz
│   ├── f25afcb6c6d0e107781a793b50831fdb3b49393f.nq.gz
│   ├── f335977949d6d92f5f00a20069eb4f294c4f8959.nq.gz
│   ├── f6867f9cee21ba63456a9e773d7b2c9971198d38.nq.gz
│   ├── f6caff23ee5012614068f7bd3da241adecdc075e.nq.gz
│   ├── fc5cc3f68264c73b8c29efa74d31744bda02cfb9.nq.gz
│   ├── fc892f802d8112313a116c6d4a79cb80fb72e8ef.nq.gz
│   ├── fd6a35f7662b07dc9058a8ccc0a42e161ddbc6a8.nq.gz
│   └── fe8c051cf6ee8d51a70092b957ceab4e99104772.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 582058827ab735b3ffc1a18a07590ff977f7e99d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 52 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[scikit-learn-contrib/forest-confidence-interval](https://github.com/scikit-learn-contrib/forest-confidence-interval)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
