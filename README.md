# Repolex Knowledge Graph of tiangolo/typer-cli

RDF knowledge graph data for [tiangolo/typer-cli](https://github.com/tiangolo/typer-cli), parsed by [repolex](https://repolex.ai).

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
rlex download tiangolo/typer-cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36a49a4ec532bc3d6ad138aa46d7e6ac8c092940
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 36a49a4ec532bc3d6ad138aa46d7e6ac8c092940
│           └── chunk-001.nq.gz
├── blob
│   ├── 0045fb8182cf94a55db192aa3bc8c4c7e033da47.nq.gz
│   ├── 042da15f2f16bd90bd2e2ad423aa49a76c1ba6ab.nq.gz
│   ├── 05b61004bf37be2ff624020e60540f0a8879539d.nq.gz
│   ├── 0755309fee3022ec9c888594de3cacfabf3911ff.nq.gz
│   ├── 09794550a65e3c27999c1fcb8dc13830ac54e929.nq.gz
│   ├── 0a73c7ebc3121672d0d4ac2481792e09adf1c673.nq.gz
│   ├── 0b0c1e52c6651fcd64d316d1d6b4ce1ebc2018bf.nq.gz
│   ├── 0b36cbb588379c372889507db4010e1dc11c609a.nq.gz
│   ├── 0cabf52a9fdf21914814f854f6890bbed6f58c94.nq.gz
│   ├── 0ffc101a3f23548392499fe5104f3f8cf4d4e91b.nq.gz
│   ├── 1442aa24422c7877bf1e0d9eb1e73839927b9370.nq.gz
│   ├── 168f83b6c2f4c1e333e0d92a82c27c8870f942c9.nq.gz
│   ├── 1ac3556cccdaa77abf4d967f9371ddd75a37d56f.nq.gz
│   ├── 1ebd280a38086ed8ced87197ae71d733df7fc32c.nq.gz
│   ├── 21918a0f029e60aabf766d4695109a659efd61d5.nq.gz
│   ├── 27a13823ef43c119b7789bef12b5d5bd93744f13.nq.gz
│   ├── 2d74566de69c9e3cea2d23843932aae77a7cb2fe.nq.gz
│   ├── 35a79f6a2330ff345926736a9502acc024912287.nq.gz
│   ├── 38fd18d97ebc9c62999c82b84ab2c78b6f3d81c8.nq.gz
│   ├── 43c80516510413d43748d8cdddfb86220531926e.nq.gz
│   ├── 48d765edb993753e04169fa51b02258ca233fdeb.nq.gz
│   ├── 4ae81f3dec0f36bcb7c315430745c6f0d898f0d0.nq.gz
│   ├── 5d6a8109e6ce6ef4587c5fb02bb9d621aa3fa09b.nq.gz
│   ├── 5eb1a5ddd5cb03567f049816a28f1b18506bbcdf.nq.gz
│   ├── 5fb66a18db87c02ed8c26e9a58a34c783f8f75bd.nq.gz
│   ├── 65eba564bbe5369bab7e9480bb9ee48a444264aa.nq.gz
│   ├── 6cdbc90025f6c65c25f9f6c5f5c349e5ff154648.nq.gz
│   ├── 783ad34577b6edc2e1635cabaf2f93ca539c3136.nq.gz
│   ├── 78bb101a9037e73e997445885871f31214678bb2.nq.gz
│   ├── 7957277fc354fc6fb9c3dd27391971b18fe93c69.nq.gz
│   ├── 79ff29b5acad87155a04ed5cbd6bade028873dfb.nq.gz
│   ├── 89c3c40ba5bd5f7c1c3066349d6cd38b3d171dbc.nq.gz
│   ├── 90cdf7323f499afc0bba1ceea31fee0b6c523122.nq.gz
│   ├── 9bf3e45fa6ec969572d935d0104e45902f964909.nq.gz
│   ├── a91ba8ccc78beffe9e6adc42db2dcbba9015d76d.nq.gz
│   ├── af572545be0eb1618a1841311c9226aec681c5b0.nq.gz
│   ├── b88cb167e4798120fdaa2a7ed44fb83b71aca399.nq.gz
│   ├── beddc16ac094efb495d02c61a408cbd0376f9495.nq.gz
│   ├── c272ee2be1292c63f9ab99ead2490a4c5a369e08.nq.gz
│   ├── cd972a0ba47221bf96acedfaed8f3b5cba819849.nq.gz
│   ├── d6206d697b8bba681107e79978da0c013eb29d51.nq.gz
│   ├── de58d7d379682e2596b84617ca8575e4f8da7b0a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c1367441660c6492e5b255757ff07d7c51b101.nq.gz
│   ├── e6f3655221f3b4dc572d1964c4ac0ea66523e153.nq.gz
│   ├── e8b794d8b87a35ec6b040d97fd77dc1f9cdc77d0.nq.gz
│   ├── ed4592f5c8c44012740ead878ebe5c004dfab55f.nq.gz
│   ├── ef228cc5ca9b8a4b14276243afbccf75b87e99a8.nq.gz
│   ├── f22d33e1a08227d718abc102b028a9472679b565.nq.gz
│   ├── f7e126d821b5fdbbd2d9b4b16a78522db776ecc7.nq.gz
│   └── fe0d1cfae2eaeea92b00a1b8bfac5e52667a880d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 36a49a4ec532bc3d6ad138aa46d7e6ac8c092940.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[tiangolo/typer-cli](https://github.com/tiangolo/typer-cli)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
