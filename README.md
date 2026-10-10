# Repolex Knowledge Graph of marshmallow-code/apispec

RDF knowledge graph data for [marshmallow-code/apispec](https://github.com/marshmallow-code/apispec), parsed by [repolex](https://repolex.ai).

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
rlex download marshmallow-code/apispec
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b66a26b865772f5f461f97f99c5957790a3a8d7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b66a26b865772f5f461f97f99c5957790a3a8d7
│           └── chunk-001.nq.gz
├── blob
│   ├── 0798ecb7b6998b1a6e06e96c5d2a257e3b03bf96.nq.gz
│   ├── 0e35bee91470117571d29550419477dba7f42c93.nq.gz
│   ├── 19cfacbf70676b064f66b348b0af4e0cb6b48626.nq.gz
│   ├── 1d872d37e9c4bcb0beb0fbb0e2f70e4a8cdeebff.nq.gz
│   ├── 2df9a8cbbb680a1e83d41f835efafaefffc4888b.nq.gz
│   ├── 3663fce6955ee379bfc44a3ae2d35fefc159f279.nq.gz
│   ├── 391528f8068f0c965fdc848a7b3672d77090ea80.nq.gz
│   ├── 3a62a98a2f54d62003c8d3a8fd948816ed5e965a.nq.gz
│   ├── 439826031bcac775f3e4c6813e102b0aced5320e.nq.gz
│   ├── 485b4c5568f91b724e292e4c993e57a285136911.nq.gz
│   ├── 563db130f26e1b392dced7329e42227d42ba33a9.nq.gz
│   ├── 568c6b17b5a209216fd41bf75aa1ddf08bfd61c1.nq.gz
│   ├── 5710c535d7410a4a2390b5049e904b9b84355a8b.nq.gz
│   ├── 5b89ed2d0f72a31d5a31a523350271fc12813588.nq.gz
│   ├── 66ba1f8abc345dc735e046ae7f76a2ae4b70f459.nq.gz
│   ├── 6a6d4957b5b9875eaacd6738c6a48731917c6bb6.nq.gz
│   ├── 6bc4c94be1b52a5ce1f397656a5e344ba7404fb5.nq.gz
│   ├── 6c0058da70a328d718b3f17d1066309991cc669a.nq.gz
│   ├── 6fd76a63e6cb218a844fc4b3a6d8ff8b7b32036b.nq.gz
│   ├── 758ab1634cb8275863f6f7a5289fa0293182bf09.nq.gz
│   ├── 7c045e4674dc0af636a9bd21741953eb948894b4.nq.gz
│   ├── 825c8aa2a601eb6d19cefc4e403111f987cdf357.nq.gz
│   ├── 879e66024409ed5d58ab53a0b9ac20db46fe3786.nq.gz
│   ├── 8a9f4362456ebe877fe513d1d353d045eb66627e.nq.gz
│   ├── 8ba96d314340316d618d015c059519af28c9e90a.nq.gz
│   ├── 92ec2bb600a1e1f3ad8666d355b485b696332790.nq.gz
│   ├── 9ae6383b6f6e642d43c827ee14e282d85ba2dc7c.nq.gz
│   ├── 9d832002bb9975c2f9febcb03c429c720025f14f.nq.gz
│   ├── addc383806e7e090072707a5653f4f1dfcdd01e5.nq.gz
│   ├── afa27ed9e204da7621f4bfc70bc019530667e942.nq.gz
│   ├── b10bdef0e5ca933b192f7f36fba45b3d4fe4ac3c.nq.gz
│   ├── b3fe148b815c1641821844009a8fac7594ff0219.nq.gz
│   ├── bcf0e63e92029beb092da6322c33f3de6a6988f3.nq.gz
│   ├── c0379a715b05db2170f646bb70de3a6f23b937ce.nq.gz
│   ├── cb862e53a0899de09cab3267f5246a2bbcecc337.nq.gz
│   ├── cbea21233d83edeac885896ea966dbb6f775e59a.nq.gz
│   ├── ccd0731266a0125cd9fe7b1b1357b0e57682f837.nq.gz
│   ├── d07ca99f4d7a1ad9b04c721ba16e66c4057c649c.nq.gz
│   ├── d4722bdf28a00536bd3b52fb15b6c34a3338a36b.nq.gz
│   ├── d4f1a542ec37bccf16807a60468aaa8b82f69e56.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e128b255854b2e24c7eb6769e6a332e5d7983b8b.nq.gz
│   ├── e21a84937c4bdcccbc3af1e3c9450cdd402abf33.nq.gz
│   ├── e51d9cf0738e5a742e229ba708f8f78ff146f711.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7d9c4b3d04825d08f3de8cb22d79451394d8840.nq.gz
│   ├── ea9ea55259de7928f0e63ca338d6fdf0652b0d6e.nq.gz
│   ├── ec9ad7558964881f5655ebe3aa00a376670eab6a.nq.gz
│   ├── eddb89e9c0caf1bac4439935b2fff9830f58afbe.nq.gz
│   ├── ef7dcdc472cd7996bf3ee9acd91c4e4ab1b6c1a1.nq.gz
│   ├── f40ce91be5fa3ae6afbf5457462f0d87000e4f1b.nq.gz
│   ├── f8751b3a51f1ebf4c2b0b722bc02db35322991c6.nq.gz
│   ├── fa07e9e9a0a642238290e1e531c015e7134401fa.nq.gz
│   ├── fb4819c65f475bd20b677419822633f5f020e3a2.nq.gz
│   └── fc40046eb55bf9cc135e2da5a796ccb63ea42f83.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0b66a26b865772f5f461f97f99c5957790a3a8d7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[marshmallow-code/apispec](https://github.com/marshmallow-code/apispec)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
