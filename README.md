# Repolex Knowledge Graph of python-trio/cookiecutter-trio

RDF knowledge graph data for [python-trio/cookiecutter-trio](https://github.com/python-trio/cookiecutter-trio), parsed by [repolex](https://repolex.ai).

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
rlex download python-trio/cookiecutter-trio
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 17f560a4aab0da9be009f1526ca5bcddc47a4c3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 17f560a4aab0da9be009f1526ca5bcddc47a4c3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 0782622e69cd01a7c167122d860f449af8f3963e.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 0e814ba376c2b7b551c4a6908ff2d1652dab2ebe.nq.gz
│   ├── 13f39c596b4fd1affbf199fdf4f41c37ef53d655.nq.gz
│   ├── 169cc0d8cbcbb7a86bf96b32713ef79aaceaf073.nq.gz
│   ├── 1dc1718d0808899a47bc2266cf11b3eb46dc0519.nq.gz
│   ├── 25b16b40d27bc82bdb5be4de028be5a212be296a.nq.gz
│   ├── 291bfeaa3b207e4173c50080f22cfb473363ee5a.nq.gz
│   ├── 2ad91e4ccae847753ca2307e22d8d84bb57bac6d.nq.gz
│   ├── 2b656e196b919e501c047ac5497dea25d8a92d1c.nq.gz
│   ├── 344678bcb9faed19cd32bfac63b307f652418a25.nq.gz
│   ├── 3615f9292aad1a1bfa832b186f6a9ca2151d0f18.nq.gz
│   ├── 3a0e6d1850d4211dc94a35bc42c31b3af91ab6a2.nq.gz
│   ├── 47ad4b1d6f68df976d9c63307c411ebab7daa205.nq.gz
│   ├── 490c03a02a385026c9d8b1f6856cd3845e7d99e2.nq.gz
│   ├── 5006947f93fdc1e31a1f45142736450fbb44f2e1.nq.gz
│   ├── 51cad4a9bd718a71fe4ef07a3525269575fc75da.nq.gz
│   ├── 51f3442917839f8e0f0cccb52b3c10968ad0779e.nq.gz
│   ├── 533dc2161fc607e429d3183c74fb4e3b41f6e160.nq.gz
│   ├── 57bc84e641ed50347debea9e4e06097691aea598.nq.gz
│   ├── 5fa2f81c34e093b7b461f6c88dc3ec49dcdd3970.nq.gz
│   ├── 6d5d3519981beec08d8045a82feda72fe9a0a88d.nq.gz
│   ├── 733d09f2b6859d20662b1b0e0beb2cd4d03a0090.nq.gz
│   ├── 7b3896a160b15b512699ab4d769bfa25d9c08fd2.nq.gz
│   ├── 8c300c830f007b55faaa4a8029a8b817b838b253.nq.gz
│   ├── 8d4c2ba943d86aae248753092f71ccdbd0afcbe3.nq.gz
│   ├── 909ccf1bb3f8612d8dcd2580f18bf118297aecad.nq.gz
│   ├── 92571c661290a7f44d45cc97606e58d3769558bf.nq.gz
│   ├── 9a0f21ba1761179e55d1712c5fa87ea2f0375703.nq.gz
│   ├── 9dbd45474f3da13e305ac51d5d5a1907a0167108.nq.gz
│   ├── afc90e2323a0bb08ef0c580ce3122ac6471578a9.nq.gz
│   ├── b38f1a56edac686f29b4e1c99c1fa8fe0f488f04.nq.gz
│   ├── b61c3bf22d28112ce036f2a57149e42b89f3e310.nq.gz
│   ├── b8bb97185926d7daed314609753173945ed4ff1a.nq.gz
│   ├── ce10f922ada48f5a4d6fa28ae44f7ea8468d4920.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d84880d1956234d57e3af0d1c63c6aa58e89350c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed6578ff512d2d3e39ce7fa8ab467f9704eb86a6.nq.gz
│   ├── f90461ad8758905ee043bd65ea79e1bbd376ad56.nq.gz
│   ├── f95854fd0849472a7a15d95b375bb8d93e411a24.nq.gz
│   └── fcb68d43894de013f886422e9bc64452a61fdb8d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 17f560a4aab0da9be009f1526ca5bcddc47a4c3d.nq.gz
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

[python-trio/cookiecutter-trio](https://github.com/python-trio/cookiecutter-trio)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
