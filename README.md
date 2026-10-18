# Repolex Knowledge Graph of jazzband/django-authority

RDF knowledge graph data for [jazzband/django-authority](https://github.com/jazzband/django-authority), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-authority
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f58bbef27eca18a818fce6f5c25e651c552386c1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f58bbef27eca18a818fce6f5c25e651c552386c1
│           └── chunk-001.nq.gz
├── blob
│   ├── 05a66fd215fbd7ca900c9d5bdd047992776dbc90.nq.gz
│   ├── 0976504290ed0f554c5f17e6d8f67a4d87140a30.nq.gz
│   ├── 0a6acb8991f4d40a58e00aca8c3cea55dbaa7966.nq.gz
│   ├── 0ed662b83325b06f464aaafe9d7706fd387ab661.nq.gz
│   ├── 0f6c570f7492edf448a39e08518a5c0ca5572a22.nq.gz
│   ├── 10cca7310569b9ff0fb937fa5a4aa2fe94a09b9d.nq.gz
│   ├── 1cc40044646bb73870088ddc88543c58a3ca083e.nq.gz
│   ├── 1f5873cea382f5078e3c2a4b96064ef8ac930223.nq.gz
│   ├── 27964bd6f79f15fd6fc5ad386e7566f723e58396.nq.gz
│   ├── 2e81bb442a980b149e296ae09a773aeb5d505930.nq.gz
│   ├── 3284d6debed4df49e6103496c051381e4c88cd8c.nq.gz
│   ├── 33ea6bebc2d05af44cca8f445681908a205292d7.nq.gz
│   ├── 3718fdb00e1162f0f3d984108fceaf765310d414.nq.gz
│   ├── 3891187a14c2bc2f1aac1da4f97e5ccf4a9c618e.nq.gz
│   ├── 38993b7e598385cee2d0b8b8a824e496319c268d.nq.gz
│   ├── 38d976bef367ef6c93a777fa4af3eef1fb701126.nq.gz
│   ├── 3be9d7d5c82ae6228af5d0c89aa2f91002fffbdf.nq.gz
│   ├── 3c9c05ea0648036f1349e0e1a48237c17f7f5fb0.nq.gz
│   ├── 3d203654d8e07e5811bcd06d78870e66c34840bf.nq.gz
│   ├── 3d845821c55c0172f3ceaf280dc39c2addbb88de.nq.gz
│   ├── 427bc60b2029e609f7efc5f81d01581741be71d8.nq.gz
│   ├── 444a7379be5eaa1463affdf025c717f9bfb8589d.nq.gz
│   ├── 45da3d2d83adb87b07157201b6aada5ebd175b1a.nq.gz
│   ├── 46a3858b7fc771fc5bf2562efdf22cbc3a0b7352.nq.gz
│   ├── 4a5b3a178e79fb4165489bfd5b5b1fb8e91f7e5e.nq.gz
│   ├── 50ef06fc8bde277ddea43ce30e0de7d87c12f5c8.nq.gz
│   ├── 5304c0b7b2e0e7481fe5b9c9fe32f15ef5473c66.nq.gz
│   ├── 5cd95919c215f77be4e2ecdb3e4155b0d607b17a.nq.gz
│   ├── 61674a531f8581cca8eb50efd4034ab96dd302c1.nq.gz
│   ├── 652b76128b6a174f3407a50fff8735896f47d863.nq.gz
│   ├── 6bc863d90485837bedd026ec879d4747e07a162e.nq.gz
│   ├── 71a836239075aa6e6e4ecb700e9c42c95c022d91.nq.gz
│   ├── 7683b809df06ee3e7562987aec22c9aa6822abc8.nq.gz
│   ├── 78d90a9ff0b6be8b07c96babdb20908280a3b307.nq.gz
│   ├── 800a32f5ba0064c5df9309dd856399c0f834e07c.nq.gz
│   ├── 8596cf9a84e611ff21327218538e03a40a5db2eb.nq.gz
│   ├── 89b35e7b1aa4eb5fe937e1750a7638905530e012.nq.gz
│   ├── 8f5e0d8a567547c9c19e7ed92b1f51af1e4b5959.nq.gz
│   ├── 978ceb531ca74febc3bd3f763642b9d7f90aa47c.nq.gz
│   ├── a11568cd154855063a4ed9098dab3007371a09e8.nq.gz
│   ├── a4d660359cc639fe0bb13beb19646ad7cba67014.nq.gz
│   ├── a7ec19ee1bc452bcfb4625c6c454573070b7e438.nq.gz
│   ├── b0f74cd98d98a65f96903728bb418c21e69d8876.nq.gz
│   ├── b43bf1aec49f227461a92b8eeaa1447d9ea55b1b.nq.gz
│   ├── baa244cd6ca28c08583d958f0ccf6671d4495e4c.nq.gz
│   ├── bd2c0b488a9472693e09522b4a28d3e0faec62fa.nq.gz
│   ├── bf167ef0b061dcc2429fea7c968731695d4aafbc.nq.gz
│   ├── c0aa19ffa3267c0a008846c9a6c5b8c0a551f3d7.nq.gz
│   ├── c94d8bef31c02d0ad8043eaf96216a46e6304a0f.nq.gz
│   ├── cacbb238632c7efdc8492eb865f6cabfe9f37513.nq.gz
│   ├── cd35f36282793637a15ebbb61e47f220722985bc.nq.gz
│   ├── cd5a5d7e00b1d62338b7a50c13a977cac7005a7f.nq.gz
│   ├── cffbb6ddabac1bd05e929dc928ea4ebe9758f7ff.nq.gz
│   ├── d5a962e38f59cd936b6ddd67f9ac6321636c8aa5.nq.gz
│   ├── dbe2730b4af88fc9ee6a5be60621cb20f1912b14.nq.gz
│   ├── dcca399ea0030ba150dbf9d443fb13395ee51609.nq.gz
│   ├── dde6d0b9be0ab713be14bf6228c04c2bc2e39dd1.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e51b8e6fe0d58bc0ba01ce150d5cd762bb8639ba.nq.gz
│   ├── e5ea6765bf8b149284db205967f9fe230f3c2367.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78b8970997c93d3f390c657821d699d108378b5.nq.gz
│   ├── e799d9bb7fabfde1ff425c337fa84c45dcf4ed92.nq.gz
│   ├── e890d3335dee4b7957e6aabfc6dea40837326703.nq.gz
│   ├── f124c2af2fdf32af396ecb8dd3eb5c9415951347.nq.gz
│   ├── f2b82bee599346c7c2517511a774fcdcf055eee5.nq.gz
│   ├── f77924f54ec95608487195123003ea91abe6dcc7.nq.gz
│   ├── f7a42745be16b9d75d6786baaef7d293e32f4c8a.nq.gz
│   ├── f85bac45168c9f9171b84a48eabcdcf287aa4c69.nq.gz
│   ├── fb5821b0a39e7bfd8616d437cf0e333b969332e2.nq.gz
│   └── fc8d6dbbac6aa4b44def5f5e80a4ad1adecd4ac7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f58bbef27eca18a818fce6f5c25e651c552386c1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 79 files
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

[jazzband/django-authority](https://github.com/jazzband/django-authority)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
