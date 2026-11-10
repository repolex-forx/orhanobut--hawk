# Repolex Knowledge Graph of orhanobut/hawk

RDF knowledge graph data for [orhanobut/hawk](https://github.com/orhanobut/hawk), parsed by [repolex](https://repolex.ai).

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
rlex download orhanobut/hawk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0b20db65d5a984bf8597915cafeb1276e5169e15
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0b20db65d5a984bf8597915cafeb1276e5169e15
│           └── chunk-001.nq.gz
├── blob
│   ├── 094aa070f179116f9a7fa8171496824768c68127.nq.gz
│   ├── 1eca32e7b4b33bc173e6b75ef5871dfd705b190e.nq.gz
│   ├── 20924c04893778747d9081cfc56b82f317b25c85.nq.gz
│   ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
│   ├── 24ecd487093da7ecf9c3b253b6f0a87cac50a655.nq.gz
│   ├── 27181b9fb771fc13bfb4be414406caf94ddec850.nq.gz
│   ├── 2821ed432fe8be6883a7119f3b3fc2d0febffec7.nq.gz
│   ├── 2da3cf51f053191486ffb142ab6e0645177606fe.nq.gz
│   ├── 2f46a2a4f4cf3a4c6b4b16ec58fb1c05877c3cef.nq.gz
│   ├── 3185a43f78fabec15ca99b0ca6bf1e666218d5ca.nq.gz
│   ├── 34cb99e3d466cc6273a71555e15ac48b8fcb37ca.nq.gz
│   ├── 35eb1ddfbbc029bcab630581847471d7f238ec53.nq.gz
│   ├── 3c126d3f0269b9330d3249f6fbaa39333b4b0fa4.nq.gz
│   ├── 463781ebf6ee8905ab27f5dc363fb4272faea706.nq.gz
│   ├── 49dbc1f975cee27c82584728d870c75087891c6e.nq.gz
│   ├── 4b149bd858b8de11e32f6a3748b2dcce85dbee59.nq.gz
│   ├── 5097068a8d375f5bf0d15693fb5b3615c972a801.nq.gz
│   ├── 57538bab8b1bb3e817242ed3cc660e2aeda3b2fb.nq.gz
│   ├── 585f41c9c34a4c1b0e68be41a4a55e5e9313078c.nq.gz
│   ├── 59e3b9497a36722327f7535c2aecf99415cb4a5f.nq.gz
│   ├── 5d725c8daf70c3d2714e2ec02aeece9fb3810cc4.nq.gz
│   ├── 6babe8470162cbe4ad5fa0da9e0df38f887b6255.nq.gz
│   ├── 7884de37113135ba2eea1833c0f047d8ac606b22.nq.gz
│   ├── 79ee123c2b23e069e35ed634d687e17f731cc702.nq.gz
│   ├── 8c95146ffa91c4e32384d0b7acb373917c717d63.nq.gz
│   ├── 904cfda3aabc55aea58f83d34f4c79ef3f562756.nq.gz
│   ├── 91b45bbcefc944f1ef66cde61a6b68e1360e4961.nq.gz
│   ├── 95b524db8dc0a1c4cde7ae11ffb8c9324851404a.nq.gz
│   ├── 961402ac3ac1645fa95f373bed1ed9702d57f8d6.nq.gz
│   ├── 988bdf5502ac0592352f6bf059c246e5a9389fdd.nq.gz
│   ├── a1a4b9829907b47dde165733c696478609a48ec4.nq.gz
│   ├── a3a4685da22e262036c33a721d261c9cde7b1770.nq.gz
│   ├── acf94cc67b3ce250848c9f601eac7596c15e9ed8.nq.gz
│   ├── aef44d8382a9cbd166a2b72e02416b46aecd3a55.nq.gz
│   ├── c3764a08ec1cd432ef47bebfdc2c8b22a2b72fce.nq.gz
│   ├── cc7c812dd334f4f2eea63ce49e916266a6d1b76b.nq.gz
│   ├── cc947c56799598205b8fb518f3ba95843c1bab71.nq.gz
│   ├── cde69bcccec65160d92116f20ffce4fce0b5245c.nq.gz
│   ├── d2c88dc0bfe0c4f10e40a744036143e20c5d9c7e.nq.gz
│   ├── d2f9a6320d8119e617a5dc92c7f95a97c7c3cfa9.nq.gz
│   ├── d6a6c4dec8cdc0dd566ae7e7547ba2f83223d372.nq.gz
│   ├── d73221d888cf5455c23b87e3abc22c7c151a81ad.nq.gz
│   ├── db9081ba1f3cbe01abbce102bf14699f7d933836.nq.gz
│   ├── e00eb9e59f14a9bd52ef561331fda7dc8fa0ee4f.nq.gz
│   ├── e05637495a5855fd3b9f340cfccc090a1266bf94.nq.gz
│   ├── e06d2081865a766a8668acc12878f98b27fc9ea0.nq.gz
│   ├── e1b3690efc1b666515a145ef2c23d1a6a38c7209.nq.gz
│   ├── e68fd4401228b24a4448bfb82851bbe94691e3af.nq.gz
│   ├── e6b9cd7a28b6d20f51249562a4b2a5c6d32c4c29.nq.gz
│   ├── e91207994ca698118208d4194e612cb40615545c.nq.gz
│   ├── f01e0801943b64ccf2bc7cf33b50c44119c0436e.nq.gz
│   ├── f14f6a40e23e8758136bed1bd93f1915ab3a6189.nq.gz
│   ├── f9252f555d751f8d5cd8bdd038a7993726ea5251.nq.gz
│   ├── f95fc98ec604e2ba2633293f476eadf4ddcb6776.nq.gz
│   ├── fc09d703756e3bfc39bf676cdb29d437c2cdf6b9.nq.gz
│   └── fe0f8e15aad063186b985b7e236b44244e21d0b2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0b20db65d5a984bf8597915cafeb1276e5169e15.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[orhanobut/hawk](https://github.com/orhanobut/hawk)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
