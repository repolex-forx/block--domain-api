# Repolex Knowledge Graph of block/domain-api

RDF knowledge graph data for [block/domain-api](https://github.com/block/domain-api), parsed by [repolex](https://repolex.ai).

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
rlex download block/domain-api
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07397bafbfb974bca508472708de0e1bed23ce1e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07397bafbfb974bca508472708de0e1bed23ce1e
│           └── chunk-001.nq.gz
├── blob
│   ├── 004e88f5e2276d28aa540a5ea290e772d5408f00.nq.gz
│   ├── 03199e3f1fac0795dda8ffaf191f78a47ae2898f.nq.gz
│   ├── 0736355870bf24d8314bd04b05adc1e07ff49506.nq.gz
│   ├── 0dcbf5c5431311f4ec620c2030662894711b6d03.nq.gz
│   ├── 0f24cc3c70d9d403664a8da37ac8eb43899c4645.nq.gz
│   ├── 10e474993355bac386639209f04c2450e9aaf436.nq.gz
│   ├── 119fca14eeb6f6568a0d5902baf0798876b2ad8c.nq.gz
│   ├── 13dbf554d0d5150cacb41c2f4449089735e0b6b6.nq.gz
│   ├── 1d0dcc92dc66f3e7f05292e9514a1f086f794baa.nq.gz
│   ├── 20dea1de6d0f86257478a3dad6128e19a55b9c9e.nq.gz
│   ├── 24a4b5305b0c5e177218d93b43e5d67e1d71a0d4.nq.gz
│   ├── 2a03fd2b7b418f098509bdcb51b7c51bf2f4f7ff.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 444770ed2cb51a50f92f1868afea05bd9ead750b.nq.gz
│   ├── 47d018322d0ddc170aad3e8c04f4673cb5736921.nq.gz
│   ├── 486f2d822a61c0b2cd6e762ec2ac318b86ac2143.nq.gz
│   ├── 4ba6e9a4f7a38b881d18e7d4794e022ef3d6e603.nq.gz
│   ├── 4eb5d56e621c40a95373201957b100a5669e952a.nq.gz
│   ├── 6568a0cfa6e85ddb6df253a4af700f5f8d9a4b71.nq.gz
│   ├── 67404fecbe66f4291a2549882f4b7e175427511d.nq.gz
│   ├── 6b3f7c4bd666ba5f5971e6c249dc7a2ed913d681.nq.gz
│   ├── 6e7baa43ed766267e499d403ba428aee1baf968d.nq.gz
│   ├── 6e9c9aed2df9985d4163182cb96857ca77c9994f.nq.gz
│   ├── 74e02da5316e063e9f3160401e22e6ae5d85a28e.nq.gz
│   ├── 7fef769248e85eab6c828b9f2f7b802296cddadc.nq.gz
│   ├── 88f20d830664c475707f86ed2babf515b64b1832.nq.gz
│   ├── 90f40ed15dafb47e938b14fdef0f3218aa70b060.nq.gz
│   ├── 9e8f739dce2437a8cddc77148f63946f25dae29e.nq.gz
│   ├── a126b7e96d5c81627a63af0e259ba602d7884a0f.nq.gz
│   ├── a4a00765f5ce361f2316e6b21aafa4035b6f9f73.nq.gz
│   ├── a7011ca9874f85fe84f90b344e92aa9d96e32eb5.nq.gz
│   ├── a7e188dcaf47d1b184da213d419d5c36a8e6de68.nq.gz
│   ├── acda9c42421a41c0de10fb49beed42e0a4742aef.nq.gz
│   ├── af3670362e54e76530903d7eeced36cfc835e78d.nq.gz
│   ├── b01ac3f067bd6307b0486cdfbf97972730151a45.nq.gz
│   ├── b9b66e3359c51c1538438d979fe007bd30c96936.nq.gz
│   ├── bd13c859ba57eb398bd853c1e09b38c6159f9d41.nq.gz
│   ├── bdf9c79a1d5c458d3ae83f7f9c3afec119271fac.nq.gz
│   ├── bf635457cb0dfb7347a7ac06fa5c82a74f7caa0b.nq.gz
│   ├── bfea92d92242e9ca101f0fbc13428e13d93ac98c.nq.gz
│   ├── d6bdaa4479efb677890a847428f3d5cb3088b959.nq.gz
│   ├── e278c7d855c23e1cfbb15e6aff5b4bbb9a1ff682.nq.gz
│   ├── e2a76b48ee106b95a63975a450cab60f07ba10d7.nq.gz
│   ├── e4ef514523b1c4420747817415572013db3626f5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── ef0d430985a6d9859c6f9a337d9a97e3d3a22388.nq.gz
│   ├── f211ba61eee78ef7a4ea0fde47a36fe3e87612d6.nq.gz
│   ├── f54754452467a1d3f1ccde8d71e69611f9c2e9ef.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 07397bafbfb974bca508472708de0e1bed23ce1e.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 57 files
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

[block/domain-api](https://github.com/block/domain-api)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
