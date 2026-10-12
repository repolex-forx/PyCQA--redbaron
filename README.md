# Repolex Knowledge Graph of PyCQA/redbaron

RDF knowledge graph data for [PyCQA/redbaron](https://github.com/PyCQA/redbaron), parsed by [repolex](https://repolex.ai).

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
rlex download PyCQA/redbaron
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9b4a1825d160269815ca7bc90f55fff8a5e76e29
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9b4a1825d160269815ca7bc90f55fff8a5e76e29
│           └── chunk-001.nq.gz
├── blob
│   ├── 0326342068bfd4191ec8f0762bec8b799336ed06.nq.gz
│   ├── 03c64874aa570ed871aefb1b7e2f6e11c0aec853.nq.gz
│   ├── 04605396f004ba6476cf3094b8f3a31595d1a6d7.nq.gz
│   ├── 04d3ee2eb7c4a94947ab6b78bbb99f745f58466b.nq.gz
│   ├── 05d079bbc52a2379ad248ec337517e1c48e73b89.nq.gz
│   ├── 1064653c238e5222e2c4af6c965f2d4e12faa616.nq.gz
│   ├── 2356d392fcec61294b445c4d246cd02eee6ec082.nq.gz
│   ├── 28ff14ba5793ba36d859128f24e6bee077ca028c.nq.gz
│   ├── 2af248407972158327d5b01ecf93db24fc8adb86.nq.gz
│   ├── 3c4524c18fb5fdcc2e046e892c6f314d39d887bd.nq.gz
│   ├── 4241ced54f9187975a15943385879c68f3017e04.nq.gz
│   ├── 451675b5fd80599cee30c9919996f7e6360d921e.nq.gz
│   ├── 4c74883707bbfccc4635428b1ea3b1278d3c5de5.nq.gz
│   ├── 4ef7657b7d968a23d10832a3989eddec08587861.nq.gz
│   ├── 536c5fa2852e819e1a90c09fd56ef3f5507f5afe.nq.gz
│   ├── 56bc16381291bed8985e5f88b7df9ec2244a78bb.nq.gz
│   ├── 5b93bc4dc6aad23b5bb9ff28d6546868593091f5.nq.gz
│   ├── 5c6acf9c97758070c733bba5a9e24fb03e36ab23.nq.gz
│   ├── 5dda24bbc53e41c9b73b39a5b56bef50866b7cf5.nq.gz
│   ├── 5eaf3a9947ef960f564323f55acafe285d4b4019.nq.gz
│   ├── 640eb1fae2ed319c8c4be4d9b19aea4a3484e228.nq.gz
│   ├── 6855cca4d372b20e9d5249dc701da4081d1dcfba.nq.gz
│   ├── 6a7360970926c72ed8408ba1d2665d53194dad11.nq.gz
│   ├── 786032de6982bfc9aed7a98b02d7eae76ccd9ed6.nq.gz
│   ├── 7d2cdded413872f5a7b369ebcaca596e1254a481.nq.gz
│   ├── 7d93e7448f49f5b13e7c4731ef09383710174c47.nq.gz
│   ├── 7f7de71996ba222b36b30926b6969a46bfe0bb17.nq.gz
│   ├── 815c8d3a39851c2cce2b9f9f237dd7267542da4f.nq.gz
│   ├── 8951ea8e619d97d651aa55e8dee549b29b31a746.nq.gz
│   ├── 8a81f93177fc524e3c344fd522327495d2200fa8.nq.gz
│   ├── 8c403525647bcaad5cf1670bc6801163e32c551c.nq.gz
│   ├── 90c5165404a9ec66312d2eca70881c7a6445c7ec.nq.gz
│   ├── 99b5949f7b65cb85f1767062295d69d6daa43d1c.nq.gz
│   ├── a2fec271c7f9d883ac753b9a0b93d068796f9aed.nq.gz
│   ├── aaf02212a87e29e8da333d0d5242ded86f7145a7.nq.gz
│   ├── b587d1694daf86b50365869dc4fe918420d2ae76.nq.gz
│   ├── b92d21d097ee539c23f24e38711f99aa3f7b3679.nq.gz
│   ├── c171aab4eb9b5d533f05c6ef5c8aa90881891c08.nq.gz
│   ├── c30fb1876ff2313073482c3e73a6eaaa78517e9a.nq.gz
│   ├── c678cee61ea6f53542d8613f75ec5ad986c969bf.nq.gz
│   ├── cb412e5e547dc5986d05b4bfe697db72751969ab.nq.gz
│   ├── defef2c1b6085bb62f9ae7ce92d43db46677909e.nq.gz
│   ├── e5782f06dbcf5f3294c3c8f039e3cb503573c27f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea4b6af60e8e916745e57e652d818f897625e867.nq.gz
│   ├── eb05596f8498134e6e0de06a63478070e342c3e3.nq.gz
│   ├── ec5f1960a4fc797079d07f147c6bbcdc70eb0f1c.nq.gz
│   ├── ed5e5a29300ce9beb1117879a0f5b5e19cd36a67.nq.gz
│   ├── ee40f78adb9fa145a39e99df99f691b62d71b73e.nq.gz
│   ├── f04c6da20a3061dcfc6e312a2971f9e2a63a8ef8.nq.gz
│   ├── f2af8a32d813228603c80fafd2bc370d0fa135fe.nq.gz
│   ├── f355df3f60e819ff3d6a96668fe2533af722f270.nq.gz
│   ├── f681a9bc0719284058b9e3504dfad83ac08743ae.nq.gz
│   ├── fb17d4e16afe9ac7d5594b11eb7d2233f317c7f0.nq.gz
│   ├── fb382fe1e347b31efd43293bbabf07d6cd1cc7c9.nq.gz
│   ├── fe55b138812f7a7fb78dc33fdbdf2107e46612fe.nq.gz
│   └── ff22313ee8d6b4effb00130a3267973dd8f21acc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9b4a1825d160269815ca7bc90f55fff8a5e76e29.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
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

[PyCQA/redbaron](https://github.com/PyCQA/redbaron)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
