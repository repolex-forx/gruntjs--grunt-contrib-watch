# Repolex Knowledge Graph of gruntjs/grunt-contrib-watch

RDF knowledge graph data for [gruntjs/grunt-contrib-watch](https://github.com/gruntjs/grunt-contrib-watch), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download gruntjs/grunt-contrib-watch
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3b7ddf4453787979a22b83949b86106534c78d26
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 3b7ddf4453787979a22b83949b86106534c78d26.nq.gz
│   └── repolex
│       └── 3b7ddf4453787979a22b83949b86106534c78d26
│           └── chunk-001.nq.gz
├── blob
│   ├── 0826ff6107269cb0607324527dbbb27645765bdb.nq.gz
│   ├── 08ebe60cca20e7209b5a64dbf44d064ff7c6b26c.nq.gz
│   ├── 09b359f7a2e6fb7ab7ca831fb5beabee0999fdf8.nq.gz
│   ├── 0cdf587d995c43cf155f5ae1aaee4488525090e2.nq.gz
│   ├── 1994040bb15fe23c2c24823b2f8ace9645fb1cb3.nq.gz
│   ├── 1b3c0a21c9e57460283f124c8acb67a866d74282.nq.gz
│   ├── 2125666142eb661091cc5f32af2ed2f3fc65571d.nq.gz
│   ├── 24ad8a36f6f7dd5dea56ef67233cc7a9713c00c0.nq.gz
│   ├── 34d0672375527851cceaa6988c2ec74185cb50d6.nq.gz
│   ├── 38bd4458c15936279887adc5f83cdce41ffbce3a.nq.gz
│   ├── 397b8f41ca0c2b5874ffbc8de94019d417ec54a1.nq.gz
│   ├── 3b76c4710c65c4ed2f374e8a05bb752e13cd3ace.nq.gz
│   ├── 3d48656689e9f1efb832506107183d43b0486108.nq.gz
│   ├── 419366714f3cfde4f0adad50b33bc70312bb460c.nq.gz
│   ├── 4af1bce1b47280a36559d59c58c75c6e7a35d718.nq.gz
│   ├── 507f91281ddb349f4b46006c67c28165b7690cf6.nq.gz
│   ├── 50942b3912ec2ec7e6019252fe85fb916130901e.nq.gz
│   ├── 517f09feae22f65f6003368b6602d7317622deab.nq.gz
│   ├── 5482741819773d1133b52a05f00e5e06e935ec0a.nq.gz
│   ├── 55fc0981669c81e1a65b1e0fa8d59eb546e24639.nq.gz
│   ├── 5671f0754aa44b1da3e7f4f194d30ac5224b586f.nq.gz
│   ├── 5d08cc3879a0bcb62e516656f4b929150e4ec64c.nq.gz
│   ├── 5d754c7f9e49411016d6699e7880aee3d3ba0c1b.nq.gz
│   ├── 60a4d21893f4639e335aefe089528478a8b53175.nq.gz
│   ├── 6b207ebc1a92ff6edbe10eaa59c7904d6b00c1fb.nq.gz
│   ├── 6c5424edb8d8939b8b0eb507eff3587f1cd406dc.nq.gz
│   ├── 6e608f1637f2b604f555bcda16ebac90b5972e4c.nq.gz
│   ├── 73042623e86db5486629c2019a9ac6812d03f3d7.nq.gz
│   ├── 743a69359c8c122ea3aee2216cf460344f163753.nq.gz
│   ├── 7ee9a2363c49ccc1a624a9ebb0014ff939fc8623.nq.gz
│   ├── 80702d5d01e30d379ec67420c65da23e583f08fe.nq.gz
│   ├── 8353937798d8744744f076d44dad6ae6088ad634.nq.gz
│   ├── 882a27381516260dccb0197fea4d494521ccdfc0.nq.gz
│   ├── 8a8f8b337656c16e5ac2ff9981ddfe710f5ded0f.nq.gz
│   ├── 8a97a9d6ca5833b5bceacc705758664c906cafe2.nq.gz
│   ├── 9171d7449fbf2400436b24ab41775ada568c4e71.nq.gz
│   ├── a788db2d56cfb4b983f00eac8195a87984b6b364.nq.gz
│   ├── aa1b96c46090efd2ed55b6b3be03e85935f464a6.nq.gz
│   ├── b0654561b68ffd5456fa6d49ecf5d0edafe473f8.nq.gz
│   ├── b785247e588ed6ee0acdec5ae843ce8f69ff1005.nq.gz
│   ├── ba9bec95f66bae3ff8b466e68017a80432a5361f.nq.gz
│   ├── be50138d221ea18ab5e094eee93efa6b7bb3ed9c.nq.gz
│   ├── c4e04de18dfe197d56034c9df8065abaf8835851.nq.gz
│   ├── cc4f503bd7605d1684bac1882cf422042aebaad0.nq.gz
│   ├── db92b67fc17acff4e8f732aa2bec58ab3432a5e5.nq.gz
│   ├── e074095c751a3783079563d3502663f7f5501ded.nq.gz
│   ├── e35871cd20fc6b19e278472f140b85358b98d6b7.nq.gz
│   ├── eb8c2eb65a400801cfcaa1bb2676fc98d94137e4.nq.gz
│   ├── f93cfa802810730f64ce3143c7f41d825aa61b89.nq.gz
│   ├── fb8c1d600b84cf447d81f2578a5ec3da27a99330.nq.gz
│   └── fefeeeaa8f0283b00147525a6bb0ffd1b107e1db.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 3b7ddf4453787979a22b83949b86106534c78d26.nq.gz
├── filetree
│   └── 3b7ddf4453787979a22b83949b86106534c78d26.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 61 files
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

## Source repository

[gruntjs/grunt-contrib-watch](https://github.com/gruntjs/grunt-contrib-watch)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
