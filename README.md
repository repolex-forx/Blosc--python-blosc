# Repolex Knowledge Graph of Blosc/python-blosc

RDF knowledge graph data for [Blosc/python-blosc](https://github.com/Blosc/python-blosc), parsed by [repolex](https://repolex.ai).

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
rlex download Blosc/python-blosc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d80d533dab65f7e64868afb2746afa3453d6cd04
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d80d533dab65f7e64868afb2746afa3453d6cd04
│           └── chunk-001.nq.gz
├── blob
│   ├── 09d16fe020be1b7c999ddb5f2edbccc64217a19e.nq.gz
│   ├── 1145f485b47f09a79e177ac21551eaada6a7fa2b.nq.gz
│   ├── 17edd0305c0297321206c38d57bae81318bb42d9.nq.gz
│   ├── 1ea7877eacf678c62262224ce88d915074ffcd7f.nq.gz
│   ├── 22a9a30d78d172b873a8720ee465a75f358b3a6a.nq.gz
│   ├── 22ff26cb9179be8224001e0408dead03d9ded674.nq.gz
│   ├── 24a4d9c134d2d00f56d19850434717bfd4dc115f.nq.gz
│   ├── 34a9eb21ee7aab10a36516b738abef8415d25c67.nq.gz
│   ├── 3550926e518136616a94a11eac08acf8cc292c5b.nq.gz
│   ├── 3dfe6ceef8cfe38957cb546013e6e07dc7cd5a34.nq.gz
│   ├── 3ef23276181ee1b423279fb9d835978a27dea342.nq.gz
│   ├── 52a96e0b76f8d0888fd6f2588ae5c9d8238285f3.nq.gz
│   ├── 56637cb810d61b8f3f796c519cda83b2320475fd.nq.gz
│   ├── 59262dd81bbaf810a632c38c0866d128c3fed868.nq.gz
│   ├── 5f26923d63c48c2e935fd796e20aa29902a91cdd.nq.gz
│   ├── 627ac55c3fa7037f4387bb07250d1b6b0d9ef3d2.nq.gz
│   ├── 6915fc37a15546955c9a4fb90679ce066b75dec9.nq.gz
│   ├── 6c76fa4e5ac05007ae7c0070873eae06cf80ce8e.nq.gz
│   ├── 7bb4cf765de7c2dfd9f034e75ca6f36acd448148.nq.gz
│   ├── 7dc7614e4aa8b1f566668dbaeac4b10981deadcd.nq.gz
│   ├── 821e319cce810684b25bd96564bc4136da3be056.nq.gz
│   ├── 84c472caf5c8441e5583fb279e8a2294c86317ac.nq.gz
│   ├── 8c95854df0224b0c5349518022a5bf2f1d0dca58.nq.gz
│   ├── 8f1748d545c6e9de3b3b60a44514fa94c77fe63b.nq.gz
│   ├── 95230d92da046bfe14651315a4f3b7972bc87e77.nq.gz
│   ├── 9ce6196db00af3c3c4c9dad458aa2efea3ff69cf.nq.gz
│   ├── 9da8f67d15d58ce54e7196e00e73bb32c9ca6aa0.nq.gz
│   ├── a4d92cc08db6a0d8bfedbbbd620d1fb11f84677b.nq.gz
│   ├── a4f0eadc21a5a74779e1099153fb4ce45a89c95c.nq.gz
│   ├── aaa818849d147817d32215a13addcb5ac2ec2d64.nq.gz
│   ├── ade1731dfbd50814291fab5167096c7656719fe6.nq.gz
│   ├── b7a05362b510b7afed2b5d3847cbb526b9919489.nq.gz
│   ├── bdced8e5f6cd4d8d33f7fc8c765aa42f51e5c7ed.nq.gz
│   ├── c1dd275982242f38e4102a4a0996bce1d4ff3a57.nq.gz
│   ├── caed766941faed521d44d59b1f8880385a65c418.nq.gz
│   ├── dd5e07d20d7a7a1e64b4b8362fc40279c13a10d6.nq.gz
│   ├── dea291bb2e38601fc67782f458924e35e0e58e99.nq.gz
│   ├── e05848ed60ba27146c6098f4f86804f9d9df8a24.nq.gz
│   ├── e7d25eacee19eb53b3830a79aa2972bb57956bbd.nq.gz
│   ├── ed8d9053639086efe477f7ccc8dba7ebc4a29697.nq.gz
│   ├── f0338036bfca315376b0b7f4b3d0e1af66bfd97b.nq.gz
│   ├── f05640cbd463133380ebf9848d09c065d4eeba74.nq.gz
│   └── f0dee713c6a238eac4652bda1fafeba8791abb90.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d80d533dab65f7e64868afb2746afa3453d6cd04.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[Blosc/python-blosc](https://github.com/Blosc/python-blosc)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
