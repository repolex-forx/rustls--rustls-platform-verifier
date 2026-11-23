# Repolex Knowledge Graph of rustls/rustls-platform-verifier

RDF knowledge graph data for [rustls/rustls-platform-verifier](https://github.com/rustls/rustls-platform-verifier), parsed by [repolex](https://repolex.ai).

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
rlex download rustls/rustls-platform-verifier
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 996b1c903491641b17b3c9afb65d1352f6fc6b76
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 996b1c903491641b17b3c9afb65d1352f6fc6b76.nq.gz
│   └── repolex
│       └── 996b1c903491641b17b3c9afb65d1352f6fc6b76
│           └── chunk-001.nq.gz
├── blob
│   ├── 024cab8ccb582694f2ec9fb7cb04207db072f9a0.nq.gz
│   ├── 028baa2a4e8988f649258403e1c0aabfc7366624.nq.gz
│   ├── 028e6f5c8c80d0b2c1bd3561f53dcbdcd5d7533f.nq.gz
│   ├── 0292e4c62afe1af5b7d3bd38fba0d4f72f7398fd.nq.gz
│   ├── 0968a956569cc4b3210e316b61f00faac30cd687.nq.gz
│   ├── 0c2364f41aa735320f80c580cb8722ac37551253.nq.gz
│   ├── 156afaa2dbe7547cd87449b77fff65d1e243c9b8.nq.gz
│   ├── 17bdbc054ec67b33e05551c3441b726d4db66ce7.nq.gz
│   ├── 1970f97d2f638669924c46260649a5b0eb562077.nq.gz
│   ├── 1ac3d71a3de74be3e1fca06db8c90aee1087b287.nq.gz
│   ├── 1bb20d546efe1ead38ffc040fdaab44b70314bfb.nq.gz
│   ├── 1dfb0e70faadbce1e2af09df6a528e061e25c471.nq.gz
│   ├── 1e36bedf7987f60a6e4118d340ad34913364bad1.nq.gz
│   ├── 238b636d8eea4c0d211042a1e5806ab37e67d180.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2bbb3309c8d0138fdf88e77f9f31fba87c37bf30.nq.gz
│   ├── 2e85965f40b337a5e5e11206bff79e8514a50482.nq.gz
│   ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
│   ├── 343badcb6dfe217780880adf1044a2d38c7fd575.nq.gz
│   ├── 38a2686b77405d2f0711ae847fe230eb3ff1f029.nq.gz
│   ├── 3b4aa06429d1961646893cda6ec27c682ba06277.nq.gz
│   ├── 3c1da291a7b5850e74e592cc9fbe433f35f597eb.nq.gz
│   ├── 3e6174d29f680a71a70ca0e1d2d6b909c5699bcd.nq.gz
│   ├── 42bbb13f7951584aeffbbe306552d63676b7c67c.nq.gz
│   ├── 46289c19da4673c0f13859e5253e7824f0a2acab.nq.gz
│   ├── 4d2bdceb7244e182257f0f52f2e07acda75c3c67.nq.gz
│   ├── 4f906e0c811fc9e230eb44819f509cd0627f2600.nq.gz
│   ├── 4fb03756cc21b644e9ea5978edb3691bde86c0f8.nq.gz
│   ├── 5186e3a558fc13be1f82523ff2a8773718c0e46f.nq.gz
│   ├── 5693ed6f8f9f87c29cac1ad9e4dde1b9f72c5ccf.nq.gz
│   ├── 59a931c82a9da8ecff7cdee191eac17dc2f9d604.nq.gz
│   ├── 63e7692a0e41ee8e87f554a4f03d14a5d4751bc3.nq.gz
│   ├── 666a1bd61f8380b107dfe5dd1df99cd8b34cb929.nq.gz
│   ├── 66e49a7e84864a5877ca34539018bd8c48d3e1c2.nq.gz
│   ├── 6b71c6f8fc83b02c5d6998b1b3226c2825bcadf3.nq.gz
│   ├── 6c9882421dff590f14b8aa4559b047df57bc08e8.nq.gz
│   ├── 6d52ea5e96ff705ea34495b67370725cbb141959.nq.gz
│   ├── 6dff38ec934b2e6a73ea618c78c7a42bfcd4ebd4.nq.gz
│   ├── 70b398f59511faea3af72c4188a6fa926695a812.nq.gz
│   ├── 71252b6207ce9da487615523cda2cbd70dd0efd1.nq.gz
│   ├── 715268a4ad941aa9391dfd61f98fcde3f409f719.nq.gz
│   ├── 744795f467224556696397cff052c754a3a250c9.nq.gz
│   ├── 75df0cc7c0be230aca9aec4f9d5e958ea3b268ac.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 7a687b716d2a68e6bd304804165a544521e70dbf.nq.gz
│   ├── 7c059e530c146f3b5e10d5b5439afe52e3f86913.nq.gz
│   ├── 8cf0eef4d564d6ebbc14cd213ff8c1c6b3e823fc.nq.gz
│   ├── 91b06eac5d67e45f81d5e0521902af99b86699fe.nq.gz
│   ├── 91d9d305175b69e674b7a4bbbbb4007a18b38084.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 97fb79ada326479f4311fb0b7663bb1a258c3977.nq.gz
│   ├── 9964122648c6348a3c8e61d6d46a87d5942d036c.nq.gz
│   ├── 9d7be827b197d2280c0373a66a66772117ae6f0b.nq.gz
│   ├── 9d947ff281feed2bd53a68793c89cbe5d5155a23.nq.gz
│   ├── abd0fa14ab485c63ec736a21437020d75fc28d8f.nq.gz
│   ├── ac1b06f93825db68fb0c0b5150917f340eaa5d02.nq.gz
│   ├── b187e36c701953011c794aac8f903d780efe9390.nq.gz
│   ├── b2233f389ac268310e48e0914e3f942642c07f7a.nq.gz
│   ├── b4f4012e2a97ca70286c0cda43e9f027b24911d8.nq.gz
│   ├── b547d64d693974d9644f5b652ac0ce0a6a1a05cb.nq.gz
│   ├── b7671fd5b9e6134181d72020025aaee59a1c9d91.nq.gz
│   ├── bbd64a3708ddf3d8243d62b0046e9c2a5fe9f5de.nq.gz
│   ├── bf6c751af9941b54757f510a9edf6afb4cff7016.nq.gz
│   ├── c35da3705adec34776a58cc9e3a7eff46de78dcc.nq.gz
│   ├── cbc86eb962ef6aaeedae7a649b20c47042510474.nq.gz
│   ├── cd0519bb2a9450033b80e5906f766b71d176014f.nq.gz
│   ├── d18515e88224c7cb36e38c67818c9316bb1ef46a.nq.gz
│   ├── ddbdfa3e4f2941d1c58d26b7a36e057e2f16bb07.nq.gz
│   ├── e00d83fe54605ea23cb46ae74edb75e66f20b3f1.nq.gz
│   ├── e311b4fa98c2bc937752ade4224b2a40179ebf75.nq.gz
│   ├── e4030665bea96f23f0d3c38400bc5d815655db15.nq.gz
│   ├── e5903e0b83dc737c6590aed92cc76b85b8613929.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e708b1c023ec8b20f512888fe07c5bd3ff77bb8f.nq.gz
│   ├── e920cd38e8d0e0f0b93341f825c8de77549b28bc.nq.gz
│   ├── ec3b4de1b435b91c6eeebe06727b86d99fbb1b20.nq.gz
│   ├── ed86475cced00eb85e8dfadf7dfe63d008f10971.nq.gz
│   ├── eeb3deb6940196950d1d4c4ad8aefd0a5c01b52d.nq.gz
│   ├── f50b23c02b566243df2e4485fce9a13306cde435.nq.gz
│   ├── fd0986f3333eac856994f4b9626dfdaaf1585146.nq.gz
│   ├── febbcfd2d803b09d2eec563279ce096e6e3bfa9d.nq.gz
│   └── ff02b2d3557bea2224249404e28227d84142fece.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 996b1c903491641b17b3c9afb65d1352f6fc6b76.nq.gz
├── filetree
│   └── 996b1c903491641b17b3c9afb65d1352f6fc6b76.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 92 files
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

[rustls/rustls-platform-verifier](https://github.com/rustls/rustls-platform-verifier)

---
*Parsed on 2026-11-23 by [repolex](https://repolex.ai)*
