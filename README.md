# Repolex Knowledge Graph of arrow-py/arrow

RDF knowledge graph data for [arrow-py/arrow](https://github.com/arrow-py/arrow), parsed by [repolex](https://repolex.ai).

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
rlex download arrow-py/arrow
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2224255c4acc594d734cef0bbc83360452a67983
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2224255c4acc594d734cef0bbc83360452a67983
│           └── chunk-001.nq.gz
├── blob
│   ├── 056cee41257bd872dd6c5531a9fa45c803bcc496.nq.gz
│   ├── 07cbd63a127b23f0ef3cb6f401286485b8156981.nq.gz
│   ├── 0913bfe1b49b95f1fa22be1dbcd6337791d142fe.nq.gz
│   ├── 0ad2fdba4dcd8ecca075ef9b53a0223a39b171fc.nq.gz
│   ├── 0e07c288af53cf260af2697636a92246b08bcdc5.nq.gz
│   ├── 11c4415587df064610e9d7ed0caf1a6c402ae9ed.nq.gz
│   ├── 1435ac21c242e473017b57bd5d5eac3507835b48.nq.gz
│   ├── 2454dac568c29f153494d87feacab2fbdd09c48c.nq.gz
│   ├── 35ca4ded43c03505ea80ecef2a6f1e90ce962717.nq.gz
│   ├── 3b9c38048d344f8e133529a62e7c22b5cf23d246.nq.gz
│   ├── 3cf4d394ac71de3b63c0e2426591338507d842dc.nq.gz
│   ├── 3d7120e368db4bcda94013d741ee760e8ededd27.nq.gz
│   ├── 3e8d9f94621c6b29efab723e119a73a0dbe15089.nq.gz
│   ├── 4324cdf1e22cf0df966256cac6a213f2eb808340.nq.gz
│   ├── 4c8153dfb90bc4160afe0604bae136dddacd856c.nq.gz
│   ├── 532e95969543728e575a1100b2491d97966fc323.nq.gz
│   ├── 5576aaf84a4e778750816d1032f24719ed84c0e5.nq.gz
│   ├── 57f8dd088508722b07d8924ec41a5ceb8bea1d90.nq.gz
│   ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
│   ├── 5e0e697a47211cb34f61fb8608cc7d0f2f68f63f.nq.gz
│   ├── 6c6a718c41d6cf5f98e2b83c6165bd30fe41c182.nq.gz
│   ├── 6ebd3346f1f3971af32aa5d8936074d732477c0d.nq.gz
│   ├── 6fd2640da5fd0e718e73aeba49ac52930c1204b7.nq.gz
│   ├── 7038d880faf7817f6800de08e815576a776e423a.nq.gz
│   ├── 7171d92ccb420865d115b5a2d4a01474eeefe262.nq.gz
│   ├── 753ed0c620a41b2d67d6e0a3db9e4a1081db2744.nq.gz
│   ├── 757df480dbe021fde1e82113f546794458124e0c.nq.gz
│   ├── 77f020525c9427bdfb5bf16553c9187e39fe580b.nq.gz
│   ├── 7c6bc4014fe982dccf9b1a03ff7ab0e814fe8018.nq.gz
│   ├── 834aee05ced1a79e5d640a92bfe19a9be46074db.nq.gz
│   ├── 916477e58bbf418b945fc7aff4d53297a623d1e7.nq.gz
│   ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
│   ├── 9232b379c6b322056e815a2c42969b85548b8e4d.nq.gz
│   ├── aa6fb4440d2a46dabc2e340d6ab0312a47581810.nq.gz
│   ├── b595e4e212189a0d1298d09e87b8ce136c9244bf.nq.gz
│   ├── b612707306097d7e27aedf230907cf24b1808cfe.nq.gz
│   ├── c3608357a438468c9ec6a4b3f6d2a2cfafbbf8f4.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d7d176a78feb6ab6be209ef382e618484e35d30b.nq.gz
│   ├── d9f660e3a283caabd28e25b462bb845857ff6fef.nq.gz
│   ├── e4e242ee42d05c3a815c81d412e27ce11aed5972.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed21b48794f28d5170eb4312e7d3e90c06a951ae.nq.gz
│   ├── eecf2326693ffa72e61f4a9251c5cfa8d0b6238f.nq.gz
│   ├── fa333102fcc06491af1cf72e0ab420223bc7dfcb.nq.gz
│   ├── fc3774b09a47deaef83473e16770f11efc4d7818.nq.gz
│   ├── fcab9213f593a68d7293baf26d8dd33557a1841a.nq.gz
│   ├── ff3fea28a56ef43e762b09a30f9c749f849c2c83.nq.gz
│   └── ff864f3ba15d69812f374f8cd53fa72c3435a4dd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2224255c4acc594d734cef0bbc83360452a67983.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[arrow-py/arrow](https://github.com/arrow-py/arrow)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
