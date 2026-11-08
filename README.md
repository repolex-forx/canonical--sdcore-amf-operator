# Repolex Knowledge Graph of canonical/sdcore-amf-operator

RDF knowledge graph data for [canonical/sdcore-amf-operator](https://github.com/canonical/sdcore-amf-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/sdcore-amf-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3646c47b581262ae0b0e1146b50b21ed121cf58c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3646c47b581262ae0b0e1146b50b21ed121cf58c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0305460f4ef8e59ca8439ce619a6e025d97f1f94.nq.gz
│   ├── 07e10a08514124ce2ce63de2bd3fccecb89797e1.nq.gz
│   ├── 087ab559848c0f694f55f7573394f5952253231f.nq.gz
│   ├── 0abdc5ccf0e8d19ec6d8185c690b63ad0a667ddd.nq.gz
│   ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
│   ├── 0ff992b299b3f0224c0a4575fb68ea04de62af99.nq.gz
│   ├── 13af703428e23ce7d56cf7a1bc7061b64a8f6a18.nq.gz
│   ├── 1a4debf8c7a0541cdf8481c9c535feb2903b040a.nq.gz
│   ├── 1aa4fc5595613e3383b9a447df058e1595ac34aa.nq.gz
│   ├── 1e70173599b6a62d6dd2f688a00500df407b532c.nq.gz
│   ├── 249228f6f5d0ad8531ffc9f353c55771ca967996.nq.gz
│   ├── 3bcd8a9f726c1e7ff32172d0ed5d95ab6436a34c.nq.gz
│   ├── 3bdee5a25c8ec75e6ced5cbbad0df249fd255ea5.nq.gz
│   ├── 3be9075f2bdf1fcdb230cbf35126f8dbf3213ea1.nq.gz
│   ├── 4c5f50bb380603c5e36198cbf7aafb8633453d2a.nq.gz
│   ├── 4d394c33b8ea132a10ef09db97c9509d10e14fd1.nq.gz
│   ├── 5411236d6b63bc4bd54f36ff39cc6f7912a44507.nq.gz
│   ├── 54f132d0cf5e7c8b9291927b1aca022634f0b87e.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 592917c1faf09d824880438d553cabdf97ef219c.nq.gz
│   ├── 6063f72f417271a6cba967b4e767ccd955d209b3.nq.gz
│   ├── 6e7930eadaf58b4c73b4fcffacc2f4579df851ed.nq.gz
│   ├── 70220e03fa32832a398116cb279773dd8124b95c.nq.gz
│   ├── 73d0b9bf6d1367b7bbe18a08083808c7d038267c.nq.gz
│   ├── 7dc4b175e472384f15e5d4aa28ae247f539d3794.nq.gz
│   ├── 844576d41d6ec200a28e4917bf3b567e689b1468.nq.gz
│   ├── 8abc134df4036620fd3ad008fe64d2054d38454d.nq.gz
│   ├── 8d771e187ba4b2ced1b643c804548e5c014bab70.nq.gz
│   ├── 8f54340743d7c5b1b55cd095156e063baf0ead5d.nq.gz
│   ├── 9ca56a8830a92c94a3be6a6aeb3dfe77d9cd869b.nq.gz
│   ├── a293bf7ba87a1d8d662e157dd743b07990a56d52.nq.gz
│   ├── a81c4625c094f11963e67c498ab3809ecb84c1f2.nq.gz
│   ├── aebd04db82731a91a7fa398f79db46d0c8dee348.nq.gz
│   ├── af4b1c516d6177355e517177dda1f31c94b277dc.nq.gz
│   ├── b5bda54a84709163d94a47d08e5fdc24a4a74b80.nq.gz
│   ├── b9b351359a24633e1f323831ba3381156c1d9585.nq.gz
│   ├── bbe77cb69558e274639017d0079c3ebd6bc948a5.nq.gz
│   ├── bd418d4c38a2ac7224a9d96b73029764359b499a.nq.gz
│   ├── bee179737880f282783d4b4b8349adacb5552c6a.nq.gz
│   ├── c042c07dd245bf66c26e9379871f6dfb5165f5e4.nq.gz
│   ├── c05e4074c7759738817ddf7a5f388bee49eb852f.nq.gz
│   ├── c478e75dc4b9bde4be71ec07a34ad57b42bc0c0b.nq.gz
│   ├── c60179725b19fdc005bcb4f53ea78078f16ba8b5.nq.gz
│   ├── caa276d7ce09ce17c677682ece0cf30ff11ba2e8.nq.gz
│   ├── cf92dc55617db94e956f4d89963a0049b0fe5a14.nq.gz
│   ├── d01d3ec218c3341b0efcc04120cea0290c5f3ca3.nq.gz
│   ├── d54e174965cd46628cb383227260a3687f776d53.nq.gz
│   ├── d618a8be2fc5a354288e523cdba2cfdc6a003c46.nq.gz
│   ├── e72f54e6eaa4ed0e2e7674d455c782943265b518.nq.gz
│   ├── eb5fc80ea619aa1cc08bc11bbbb6915c78421967.nq.gz
│   ├── f8f9dcd8802cae704f06aa3e24b4f291f7f01915.nq.gz
│   └── fbb584450f83cf32150ffffcba26dfdd2d8ef3f4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3646c47b581262ae0b0e1146b50b21ed121cf58c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[canonical/sdcore-amf-operator](https://github.com/canonical/sdcore-amf-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
