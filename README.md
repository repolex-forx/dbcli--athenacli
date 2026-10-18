# Repolex Knowledge Graph of dbcli/athenacli

RDF knowledge graph data for [dbcli/athenacli](https://github.com/dbcli/athenacli), parsed by [repolex](https://repolex.ai).

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
rlex download dbcli/athenacli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b1b18c4f16521b61a4b02f32c88a656bf5797e84
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b1b18c4f16521b61a4b02f32c88a656bf5797e84
│           └── chunk-001.nq.gz
├── blob
│   ├── 031b444e3561d6f9e500665f31b56941fb0baa3f.nq.gz
│   ├── 07d893a512255067923cbf84dadb75a220293de3.nq.gz
│   ├── 084a3129673eba9b49f80f359f9e030ade4dff0e.nq.gz
│   ├── 09c91c62bb4f282e711212681324fa18cc16f482.nq.gz
│   ├── 0e1a38d3c2dcca22c1f67c1c79d862a0189959dd.nq.gz
│   ├── 105b1a9b18724880d2826b122b5fa92a2ccb5d60.nq.gz
│   ├── 10e016bea431bd36bf8281720e31e202bd4175a5.nq.gz
│   ├── 15db09e461e6fed93004e51cca7db51feeb4890c.nq.gz
│   ├── 1a34b74fcb6eb57591bb8e31f2209ee57c1cc8ae.nq.gz
│   ├── 1f6f02915723cec140201e28257c180021fdf733.nq.gz
│   ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
│   ├── 2b49fb1aa2573deeff165bf873c6c48f398b2d23.nq.gz
│   ├── 2fbbee6c120a9fbeba68971f8cb42efbccd76784.nq.gz
│   ├── 31707288c03d82f9317c9950cb3370dad4574b7b.nq.gz
│   ├── 35c7ed64bbb4241ff191f74f4eec8d9db8235232.nq.gz
│   ├── 3607732619ac824b7bb1a61d6102a75912b1dfa7.nq.gz
│   ├── 3976c06a50420abb5094fa73388af120b998d810.nq.gz
│   ├── 3a3c24a73da335a36da84dd7045e125e33ac80a3.nq.gz
│   ├── 3a5b549f6588650c5c567511f629f26a51b45091.nq.gz
│   ├── 3d8983ddf717511aaa61e11e529b81dcafe2efa2.nq.gz
│   ├── 41973158770bf9afeb8bdfe0f6e477b642bce8b8.nq.gz
│   ├── 480520d7a49f9e66527a6ce9a14b0eb27f6dcb30.nq.gz
│   ├── 4a5fb6d664065fcf1b8dfffff85a5b2015b04d75.nq.gz
│   ├── 4f205464fcec829f87731ba53ac504bdc56cf228.nq.gz
│   ├── 500676e292ef95756814ff73e4597ad4afefefde.nq.gz
│   ├── 5056e626849364dce51d4d8f5d9c521c928b0ad2.nq.gz
│   ├── 54e2757de37cc101b218d18b22ae430ba818937f.nq.gz
│   ├── 5957557575fa988caa4d6ea3abda6c95a6de83a0.nq.gz
│   ├── 5a7ff70f155fdd05c140c11b6412a2ddef06deb0.nq.gz
│   ├── 5d718e2cd65076c37b8bf05b37c5c8c1d399b1a8.nq.gz
│   ├── 6086a6bf1a1f8f34e3955b36485658acd36510fd.nq.gz
│   ├── 60dfcfdb017cc5f2f32fc7bcac1e99a09cc535a7.nq.gz
│   ├── 63fd918643c42be8fb92bb4de7c7f7f200e63d81.nq.gz
│   ├── 6773695f884872282f44e1e0f9bb9c9911dcbe56.nq.gz
│   ├── 6a4cee6dc694b5e142ae03b13bb1280e59677b29.nq.gz
│   ├── 6bdf624ae3beddb376318a4711e8e248fd17277f.nq.gz
│   ├── 70997fde254ab3f4653ba0f886f015e68bdb1492.nq.gz
│   ├── 776970fb97f553b2493550f5b06dcd2b3c25cdc1.nq.gz
│   ├── 79b1849e587cd8bee1f35281e9d8f70ca3d66508.nq.gz
│   ├── 7accb355bc175d0bb4150c773d972a8def71e49d.nq.gz
│   ├── 80e14590b50af6dd06f85c6e6dede04614d52923.nq.gz
│   ├── 8174bb8ffcf90113d097df44bccb3109ff9b179c.nq.gz
│   ├── 828ee8b721c48b3763384b3e8a3b5eda74aba26f.nq.gz
│   ├── 83226b7753e2ede193b15b3a47d6f6f0feb10b47.nq.gz
│   ├── 8565777ca027879b93c94987af5442e6ac307259.nq.gz
│   ├── 88f8ba5bf346199a0c9094cf366ad051c5d67434.nq.gz
│   ├── 895bb3ac065f39b76f5b8a674f5f8ef87f96106a.nq.gz
│   ├── 8bec488bb7f5932dc14b33d5aff8b1525f460f3e.nq.gz
│   ├── 8f9b02307cd4f4bb97b0ef6e302a067732a0f282.nq.gz
│   ├── 90db0108e55edae6cfbc1d97412bf44e45a3dbc8.nq.gz
│   ├── 96082bd5e4e949c32c781f58a3f3899ed6ebe16c.nq.gz
│   ├── 9d50420d015ee42677a2e3d4d3b2c0914519a592.nq.gz
│   ├── aaf276072343958fee1cf7eaae4284022a9cf85b.nq.gz
│   ├── afda5b92623ffde4fe89dd767b73cf5696f85418.nq.gz
│   ├── b8a1655fa4e9bd73e23cd69aea650086884098c5.nq.gz
│   ├── cac96ed393dfc8f16d97b7f4badbfbc7c233bed9.nq.gz
│   ├── d734086bbc9af07640662a20b1ea9bebb0eee925.nq.gz
│   ├── d8d394ee1a9fd7bb3d911f882191693cbd5e87b8.nq.gz
│   ├── e2186535a712e2cdbc9aa1af03c2ae8867750f78.nq.gz
│   ├── e548595929e7518edfabeb50ced1523b5de9984f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebb97a9d0768939a80e651ca65c2e4713a90c933.nq.gz
│   ├── ec4d9f1b0ef82899b1a94186e27049ceee059b77.nq.gz
│   ├── ecab57403f431962b042ce95510c80d043275741.nq.gz
│   ├── efc416fb7401743d8c9bc58bfdb7f640b27b0e17.nq.gz
│   ├── f9604177eeabe16804285da1d3fe32045a966de1.nq.gz
│   ├── fa5578f3e2e857783a23c6337ff91d47a7e13752.nq.gz
│   ├── fb261ffbeca4f5bfda56936516fa8d92f2043600.nq.gz
│   └── fd2edbdb4f1c352ec5f3c592f5f18f82a8212537.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b1b18c4f16521b61a4b02f32c88a656bf5797e84.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[dbcli/athenacli](https://github.com/dbcli/athenacli)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
