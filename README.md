# Repolex Knowledge Graph of cherrypy/python3statement.github.io

RDF knowledge graph data for [cherrypy/python3statement.github.io](https://github.com/cherrypy/python3statement.github.io), parsed by [repolex](https://repolex.ai).

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
rlex download cherrypy/python3statement.github.io
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ede803185d493b9181b438a5e73ed9c49951cc3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ede803185d493b9181b438a5e73ed9c49951cc3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e70a63c0dbd0492700842382b3e4d9de25361a.nq.gz
│   ├── 247305468392593ec3024e5e5a4563638b84288b.nq.gz
│   ├── 26ca83dcb46a6e9df444a10f07608f823d49c72b.nq.gz
│   ├── 2704f258934016176bd816e5b330d3c4550f7182.nq.gz
│   ├── 2912433c798f2343845739a8a41d16236689816a.nq.gz
│   ├── 2946f0c64e51d72c73058107d45328e38308c00c.nq.gz
│   ├── 2d630cf757cbeea1b26f73fea83b950873b552b4.nq.gz
│   ├── 2eea12916b7760365ecf1f13fac472f137bc1dd5.nq.gz
│   ├── 34467801696ebe310609387584dec92d32b2953d.nq.gz
│   ├── 39464952472173a1d4a88239dc41fd2b9b144052.nq.gz
│   ├── 3d648f683b9b0c857d2254f6e60366ea02fd597a.nq.gz
│   ├── 4260f2adae144e3d15fe1e6edcd3ceb91b4b6372.nq.gz
│   ├── 4413744d02bcbe9accff8b9831dfb89db54f1e3a.nq.gz
│   ├── 45699ce93abbf08f84533a24001b66095457fb7e.nq.gz
│   ├── 4602a51921e658c851ee634674629adf3e170e53.nq.gz
│   ├── 4730a29ba8e3c2892b3b262a0015665bc3ddd5b6.nq.gz
│   ├── 4901dcea4efa4997ee530f3e044ea3ef89d1aeb8.nq.gz
│   ├── 4fa7b5f42774929e52c2f7c2690d8dddb18ef4f3.nq.gz
│   ├── 5aa224426447a2627f967e7c99c9553c9f8a66b1.nq.gz
│   ├── 5cacd6b84a6138b1e3d6c3281fc4cc1bc89e06e5.nq.gz
│   ├── 5cc0f45b0b6e7f15982d495733f7b91af5268db7.nq.gz
│   ├── 6600daeaf308016fa26ff71c2f6cd9e18992ffcb.nq.gz
│   ├── 662e636286a3ea844f95d691ad236b1171002ce7.nq.gz
│   ├── 67a3e3b7a027af9e27cbea0c6836b6ede1687af4.nq.gz
│   ├── 7154327152cf05f997ad8a9a81804dc8c184fb39.nq.gz
│   ├── 732662fb116fc2e1b03b7abd13e5dfb20fe2738e.nq.gz
│   ├── 7a49710b4568e0aa4578567aed09c4dc7972d29f.nq.gz
│   ├── 82d950893fe36eef8e7a4e230a8a38eafeb25065.nq.gz
│   ├── 840a189a684534eb6d5d970a9f1cade1c3515f0c.nq.gz
│   ├── 8424c9719fb34d6e57d5129835d9b22bc8fe8f50.nq.gz
│   ├── 855006eafec7ca79546146623379c1a301ae9969.nq.gz
│   ├── 91e74a212d38551925711d9f811d0dbdfbf0b15f.nq.gz
│   ├── 925e28257cf33241f22a65d4b7b85e65a7a1ec2d.nq.gz
│   ├── 92a961823808f6722aa823ef78ac344f1c63c6d3.nq.gz
│   ├── 931234121303b1ce1f4f06984c72469745644463.nq.gz
│   ├── 9b93faad738eb84e46f355e7e8a54645afb25eaa.nq.gz
│   ├── 9be0e323478d0d6d57e6066ebf75c738dada95c7.nq.gz
│   ├── 9c2ad199df02c907b804e8ec9da281489fc7e3d3.nq.gz
│   ├── 9df4c879ee99d8f15f94223ae2970d31fc77854f.nq.gz
│   ├── a159a2ffebd707559c2b0c59517542f250ea9d1e.nq.gz
│   ├── a29c5d2ee992ea2b663efab010c15c6009738f7d.nq.gz
│   ├── a2c7b4fd3e3c334374a175c558405b759debd624.nq.gz
│   ├── a365dacd94120e4feee122c6edd9f633a08ec5b2.nq.gz
│   ├── a406e9302b1343df54b16fd128020f3af6ed59ba.nq.gz
│   ├── a4844b1d3ccc2232396a2bcb17d64a9cfda7fbc8.nq.gz
│   ├── a594ccb4d75b6129925f763b0724e5b4ff9f1785.nq.gz
│   ├── a61c2fb264da7707e9e369b3afd374bd627e9ebd.nq.gz
│   ├── b4e0a55841368e3275af7026e61fd7686dc72a67.nq.gz
│   ├── b875056cafc82367361e509705605710a1ec6036.nq.gz
│   ├── bc3d0abff11ba388bfd4dca1016a5456ca99e2ce.nq.gz
│   ├── c5310a017928202c0a6c4a6e4ac8bab93b4fc893.nq.gz
│   ├── cb3898aa73a9114a4723355804ca291138e0bd34.nq.gz
│   ├── cd13ae57fd8405d9a399c71ab66f899a72f6e173.nq.gz
│   ├── d8288d2f6a5e9526c77ef95fdc5a2dafcab519e8.nq.gz
│   ├── dab01949fa2b39deb431c02333957e8912000695.nq.gz
│   ├── dbc475d1e8e1b8ceee138e81f0c677b28c7d3a1c.nq.gz
│   ├── e401321ba5cd2b0980199db27759c7c414c13c62.nq.gz
│   ├── e6fe8ab4598c938ee57651f3253d2e313a7ca8b0.nq.gz
│   ├── f2c5184abd4027ea2a6ad2bb3f8f82fe0956bd7a.nq.gz
│   ├── f39a552b86027242a4dd97c399660da23028fa39.nq.gz
│   ├── fa3e07e47b04478caa421a7610fc67a0ff21d592.nq.gz
│   └── fa720bfc81417270b4b6125be545831e371e04d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ede803185d493b9181b438a5e73ed9c49951cc3d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 69 files
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

[cherrypy/python3statement.github.io](https://github.com/cherrypy/python3statement.github.io)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
