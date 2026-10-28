# Repolex Knowledge Graph of mne-tools/mne-gui-addons

RDF knowledge graph data for [mne-tools/mne-gui-addons](https://github.com/mne-tools/mne-gui-addons), parsed by [repolex](https://repolex.ai).

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
rlex download mne-tools/mne-gui-addons
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3c78042bbfecee457f146dd667b3ee5e286adff4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3c78042bbfecee457f146dd667b3ee5e286adff4
│           └── chunk-001.nq.gz
├── blob
│   ├── 03bbada71ee1990d748a54b6494dbea249cecbc5.nq.gz
│   ├── 091e9b845b533964726f5bb4791923f4e6df36ed.nq.gz
│   ├── 0bd47e25883654b97c8141604eca4a2bbf4b2ef0.nq.gz
│   ├── 0bebe4c6996c43a9775df373cd74f4523300de21.nq.gz
│   ├── 0e95cfaac6fab6e99e4d02a8f03c351cbf6ded47.nq.gz
│   ├── 20bf1cab064d76f84356aef713b74600d6c626d1.nq.gz
│   ├── 386ce9819166884c2bf03539db86d59f3eec6618.nq.gz
│   ├── 3f43c980d0ab5dc695c975ea76c48c10703ebd27.nq.gz
│   ├── 4ef02be4a22cb0027b15932c0d255d5d389a8e20.nq.gz
│   ├── 4f9170288e41511e2a403b3681181a922a6ab7eb.nq.gz
│   ├── 5102cb990b77fee561c3335e8cb817487d69f656.nq.gz
│   ├── 5afb9168a2688e578c8185153dca1d78486065d9.nq.gz
│   ├── 669c8646ff2d70b3c61706a30c6b5b92bd95caba.nq.gz
│   ├── 6e493fae340fd2e5978b24bb7365a997b24504be.nq.gz
│   ├── 75daf9b7fe355b392f7847b4fae6e96b4035b81f.nq.gz
│   ├── 76acc8ed72cc13bc5a9a971a8026f509da556cf9.nq.gz
│   ├── 7771b9265446946fec0e0310e23e76c26eba9ca7.nq.gz
│   ├── 7cb9b6d73531e26136da340b5aa3eaba3f2366ee.nq.gz
│   ├── 84161e9c2da97df3c16ad58fbbe3cc7423a319e7.nq.gz
│   ├── 86650760e18881ddbd4fb37b00578bba33205903.nq.gz
│   ├── 8dde5403c074caf8099b292d2d91e0ebd25f51bb.nq.gz
│   ├── 91187c93c22879ed4359f6d1196304fea8d3ae3c.nq.gz
│   ├── 9193e70f22cbf03edaaa7e62d3c0832f8278da5c.nq.gz
│   ├── 9e40872353cd847b16180a1db9a4e3d89fe170e7.nq.gz
│   ├── a011f80f1c6e64f7c278c44dd26cdc9e98748291.nq.gz
│   ├── a3deed651f8d641ce0a108161f99447e8679ee11.nq.gz
│   ├── a46da673aa978d61ad6ddb90541b00ad04cdffb8.nq.gz
│   ├── adf1a0a5f248de3ef655ad70d52e83bc584e7879.nq.gz
│   ├── bc4ec2ed206aad15ed7fada220ccee914116e12f.nq.gz
│   ├── bd78b8e8e3aa72d04dc29b1acf87953dc3e45c6f.nq.gz
│   ├── cd5435fd95c748d91ce9336b1bb1768c7ec00daa.nq.gz
│   ├── cdb1b1a9bb566cdfeb4375d2e8b93546f6c45011.nq.gz
│   ├── d7abb8ee3cfd6afc39272953cf247a0cdf70622a.nq.gz
│   ├── db1a415b28123c7807a27751a70bddac18318947.nq.gz
│   ├── dbd7cfb43a4311124df2c5342fa4dcbed7ea80bc.nq.gz
│   ├── ddea4c2b4d205695f05c9fd9e947f4c0fc247473.nq.gz
│   ├── e04024235e2e81aa9b81a7863c6f66209335af9f.nq.gz
│   ├── e46a6f14546c93044a1c3c126acf811af94e3de0.nq.gz
│   ├── e4ae2f85ae6c090c177dba807cb7603e7c0f78a4.nq.gz
│   ├── ec9675cdbc14e8fe80944fbe757b54eed9336957.nq.gz
│   ├── f213cff071882755ba734ecb65ff0f3819e83929.nq.gz
│   └── fe4744011c02cb0a85197447c981233e9d6cbd0b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3c78042bbfecee457f146dd667b3ee5e286adff4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[mne-tools/mne-gui-addons](https://github.com/mne-tools/mne-gui-addons)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
