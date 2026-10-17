# Repolex Knowledge Graph of jiaaro/pydub

RDF knowledge graph data for [jiaaro/pydub](https://github.com/jiaaro/pydub), parsed by [repolex](https://repolex.ai).

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
rlex download jiaaro/pydub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 103e339d3bc7a9a58a9f1de65f7d8074659b5f5a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 103e339d3bc7a9a58a9f1de65f7d8074659b5f5a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0210521a7126eb194e10c62fffbb8c6da61e888a.nq.gz
│   ├── 040c4a320102741ffdee080c979ba3edbd484799.nq.gz
│   ├── 06291aeeb1b4e4ca9a5e44e7dcfbf417ea4c05df.nq.gz
│   ├── 0ad149999d8fffc39d2bc1d0a3e2469daed0df78.nq.gz
│   ├── 0cb49b7455d113ec0d0a2347150243888cdb2d00.nq.gz
│   ├── 0df487e4f161dfe0924ca90fee3c2b98bb5d1bc8.nq.gz
│   ├── 144696e8a8eeb27c2e2f5eb65fca15d73eaae6d6.nq.gz
│   ├── 1965761fff1bfbf2c1173cfdacd26d743df211fb.nq.gz
│   ├── 19fa9de54f74d311b7e414f547224c9a287db05d.nq.gz
│   ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
│   ├── 2694f90a2eae5e69554377edfad700a3887a2cbc.nq.gz
│   ├── 2eacfd10971b05bfd20799e190b9d3345485e7f9.nq.gz
│   ├── 38850a953ec01df22a8ea047e59c65f5c214ea59.nq.gz
│   ├── 3a3918282b74005b11e492be75779150790347b6.nq.gz
│   ├── 3b9e2881230f861d29d8b904f9941388f29bca3b.nq.gz
│   ├── 3ced7c0d1f9cb69d7c5dfbe0c4f957dda07d63c8.nq.gz
│   ├── 40fb5c8c4c923c591d17e6671abe0870c901e243.nq.gz
│   ├── 46a6261f10b73c517db7bed858796b5ba6e7ae5b.nq.gz
│   ├── 47dc2b4292eedac52f53b36c743bde773a29aeba.nq.gz
│   ├── 50bd5a543181a385f29d2cb633ed9fb32f408fc5.nq.gz
│   ├── 57d2d4ac445e3378e85fa7e58d010f314eb4b255.nq.gz
│   ├── 5ff32361f647c9c3c3d126b96acc06be3561003d.nq.gz
│   ├── 61458fb21686fa4d5bf18070aa5e6ae29409f997.nq.gz
│   ├── 65e30b4eaaff401a23a5baf05735dd2f340ff1f9.nq.gz
│   ├── 72ce4a53aea729873e5230519cba2cce35903df2.nq.gz
│   ├── 7395af5d74c53f1d7a9d51398147cf82f9415180.nq.gz
│   ├── 79d0743601eb12a7914fb63d549aa618383e79c5.nq.gz
│   ├── 7a2fc152a61545647299851a97788b93e5d0b354.nq.gz
│   ├── 7ca32d0cb656c53ba4bd729e9176f79ff6bae899.nq.gz
│   ├── 8e536536dd52a8da9c12353282452530d9fa11f3.nq.gz
│   ├── 9b1e2fbf172884197ca1135a5e0a99cf5823c6f5.nq.gz
│   ├── 9cdc3ba76edeba0ca9e6989a62ce37d160741f01.nq.gz
│   ├── a312bd247535b08f1ac491a2063b7d789fe81f72.nq.gz
│   ├── abab2b4b568779f205a76d9acfb7026f878bf9d7.nq.gz
│   ├── ae29083b8d60b5c9c4ef17c7580324f79e154347.nq.gz
│   ├── aee37c959a7b8da71aeea1a52542e22291391c32.nq.gz
│   ├── b04cb4ce8102d3a48eb14803bc047c084a8a817b.nq.gz
│   ├── b14a1113a627e8105b7ea2a88a5c7e3927a16914.nq.gz
│   ├── b1cbc4b6ec2f5fe4d977798862bc9e210bdbc8b8.nq.gz
│   ├── b948138024362c5e5365ddab4e02a3e789f5e6f6.nq.gz
│   ├── cf3aad63b9ea02c350317a6f751fbf53df9a19c2.nq.gz
│   ├── d26b87bdbb5a1d3bd5a9b12a2e0b6a4107616f9d.nq.gz
│   ├── d4b999b374d511fe42b23f92535cac2e0ad435be.nq.gz
│   ├── dc75fb367dec356c1698d443e7f7193c55237fa3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6fe12cc814bee2123fb990173290209c364551b.nq.gz
│   ├── f4c4c1d821c04fa450dc14e6226ab96cb8e92fae.nq.gz
│   ├── f8016568f737fbca96176f09912a6217847054a0.nq.gz
│   ├── fe5465a47502588a3865b6ac452773bbc8dd5a26.nq.gz
│   └── ff399f32b118fce6072ec74815fc8d52db1652ba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 103e339d3bc7a9a58a9f1de65f7d8074659b5f5a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[jiaaro/pydub](https://github.com/jiaaro/pydub)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
