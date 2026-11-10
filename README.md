# Repolex Knowledge Graph of Xmarmalade/alisthelper

RDF knowledge graph data for [Xmarmalade/alisthelper](https://github.com/Xmarmalade/alisthelper), parsed by [repolex](https://repolex.ai).

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
rlex download Xmarmalade/alisthelper
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6d7e1acb86a5c67bcf86d99bc6034f130b1d04c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6d7e1acb86a5c67bcf86d99bc6034f130b1d04c2
│           └── chunk-001.nq.gz
├── blob
│   ├── 011e2cc87ec5c372ffbfa027d64ca5dc749681b9.nq.gz
│   ├── 02cb48d69178609951db3b01e52dc59dae69bfe3.nq.gz
│   ├── 054b5d276cd490037c000dc5355126dfd0ae69eb.nq.gz
│   ├── 0746842e0e8d84a27f545810fcca6f89b27d77a4.nq.gz
│   ├── 0930ce551ec7025e27399998a37763de7f0f2054.nq.gz
│   ├── 0f29e0c1f6f1a20d76bbff9b63fe9c4241f71a96.nq.gz
│   ├── 142f7df1d639dbd33b27038a86da1621ef2b2910.nq.gz
│   ├── 14ec01a9b1d93e54986efe6ca76342054eda8634.nq.gz
│   ├── 1628e9e1f405a95ac157b5611681320b98f749e5.nq.gz
│   ├── 16c27b05acd360e61ac200edbd243cbdf6937958.nq.gz
│   ├── 18c91471812cb6f4c4e8d0fc407f70c4612e1648.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1adf3a8f0172b0838c9adcbf580e5744d0ad86c9.nq.gz
│   ├── 1b1b337c0d92c553826a289367c898185559a1f1.nq.gz
│   ├── 1d526a16ed0f1cd0c2409d848bf489b93fefa3b2.nq.gz
│   ├── 1e384b93d85355950730e34a1c8b50df7dd93803.nq.gz
│   ├── 218f93e02373ede3d285c92733f9c3d2be9fb740.nq.gz
│   ├── 2425272e41625cca1a6f77f8449e9298b41aa5e8.nq.gz
│   ├── 294a87fe53d7f377e088359e0f01cb78f5f8efd9.nq.gz
│   ├── 2ac8555f0e5e692662856c9a88eea4c6e24cf89f.nq.gz
│   ├── 36b0fd9464f45b33f482e64bea579787e142affa.nq.gz
│   ├── 3879d54755798567f0f318d63340508d5668eb96.nq.gz
│   ├── 394917c053a04daa76d8b94f0a02db0bd99e1034.nq.gz
│   ├── 39a997267c2e5d3993ab95f3e5d6b01244303965.nq.gz
│   ├── 3b8d249203caba26f5dea2f743266b9de2b85a14.nq.gz
│   ├── 41a8762502b12087e2016674afd5e2b238d50cf7.nq.gz
│   ├── 42bcbf4780b187e80025b7917058bcb882012aa1.nq.gz
│   ├── 43366c2e278d1dfb79d9299d58c336f92a2676bb.nq.gz
│   ├── 44c36752b4dbcb67e35ec92e1b3b9d9734360b58.nq.gz
│   ├── 45e2e3b4e5510968bfb9bdf81c0d8df6e728496b.nq.gz
│   ├── 4789daa6a443eefa7f3f729164a18351e06e9800.nq.gz
│   ├── 48e78d1a1192cbf451a9c738f75eebeeed6b046c.nq.gz
│   ├── 4d70608fbfa6a25058769440adc61a674eabf852.nq.gz
│   ├── 5418c9f5395573cfd0fb8290b7ac946030f11ec6.nq.gz
│   ├── 59becffc3db9c4e1526db1f9e62cb57591965feb.nq.gz
│   ├── 5b9845a700f6eff0110b91d7695b93033b9c695e.nq.gz
│   ├── 5cc8b6cf1edb38139dc554b72fbea2347a2a61d6.nq.gz
│   ├── 6163e508fb5dcc7c0a5f703d4bc04ddefc6a17a0.nq.gz
│   ├── 61b6c4de17c96863d24279f06b85e01b6ebbdb34.nq.gz
│   ├── 639c3810723e856db9aaa8df4d899eaea70d6c97.nq.gz
│   ├── 65e30a629219fb9084ff873a45a0712abca29bd8.nq.gz
│   ├── 66a65d1e4a79f230031ec0e0959a721039e7282f.nq.gz
│   ├── 6da0652f05f28fc6950cec20ebdfbae89b665479.nq.gz
│   ├── 6ef5141c4ece03b070a07f542d1e169ce43614c4.nq.gz
│   ├── 702273a5eedc478620497a2916ef66d81aa40cdb.nq.gz
│   ├── 72271d5e41701cfbffad74d38640bf9cc7c1f7be.nq.gz
│   ├── 73a7c6975fac2028ae1f5c27fd4a6da0a87a2a44.nq.gz
│   ├── 743c7704eed0980724606d2757be92ee97c9a81d.nq.gz
│   ├── 746adbb6b9e14b7e685c91e280a4d37a672afbd8.nq.gz
│   ├── 7587487ad6a0d199ae4813708e3c1331999aa2a6.nq.gz
│   ├── 80e867a4e06b4dc26d0a2b327cbd54041addc50a.nq.gz
│   ├── 8277d091283538e2afd17c56a8487f78e94ede17.nq.gz
│   ├── 8285f28058e64282be7a6ee4b0c89f45d050b841.nq.gz
│   ├── 83d04673dee8bb1da165b2dd9110cda947b00b6f.nq.gz
│   ├── 869e2d8310cdd6a0422f3c03ed99aee7d78ec95b.nq.gz
│   ├── 88a36531ffedabeb0eabcfd36125eb46afc54827.nq.gz
│   ├── 8b584062eb81d16f9eae0c1f583d2ce134088d85.nq.gz
│   ├── 8b972eb3fd325b2c7bfbf928ab2071c7ff319396.nq.gz
│   ├── 903f4899d6fced0eb941e159f7322b21b320c40c.nq.gz
│   ├── 90818e421d5f6a90284e86bb42101e8752296cce.nq.gz
│   ├── 978c9b66010d0defa4a7f40d5b53afe50abe0916.nq.gz
│   ├── 98d988434dbcb8a9c9c1e6c963f3e523399881ee.nq.gz
│   ├── 9ae7902b8ffdc86ae343d244b2db30185eb38962.nq.gz
│   ├── a42ea7687cb67e55af955dc8874a072e087ce3ed.nq.gz
│   ├── a6a5cfb956b60183704d6b8b04651f2d7985e6b9.nq.gz
│   ├── a7757063a0c639d11a2676c80dec567416cb034c.nq.gz
│   ├── a993044429345bc853af23a5831a25b6af9d8e03.nq.gz
│   ├── abab92910ebf27c1a71e163a2befbc90ebc7073a.nq.gz
│   ├── af2a589ce4f41a3f34304d7f82baa0358e4969f1.nq.gz
│   ├── b16f0d070b186c359e01a9b862977a45eaaabee3.nq.gz
│   ├── b242bc58dcb4b22285b9c8e732b8d601f9c73bee.nq.gz
│   ├── b2b08734db2bf90568fb1980bf46e0f42aea5856.nq.gz
│   ├── b50b3e4fc175c0bbdc435a4940d9a93bc461e612.nq.gz
│   ├── b5dace5a625dafdc4759de68c54c99deedc4d4b2.nq.gz
│   ├── b6177be6dcc6d8b4f1e9c5199d08f2259a8ecedd.nq.gz
│   ├── b6807124ba841a55b0f31d27f5b48969082514a5.nq.gz
│   ├── b703464f326fcdefc2ffcf02a593c6a125d847ee.nq.gz
│   ├── baaa930de5cd0b406d5d038373b2bd7b341c8af5.nq.gz
│   ├── bc1d5d0d73b635e4dbf67a139fd0ea48b70fdee0.nq.gz
│   ├── bd4136a38fcce0f749fa247b2d7a2116890a9124.nq.gz
│   ├── be189b3fba7f82c8f9af0d064775663ee51dcf26.nq.gz
│   ├── be7975f53e774272869bb17c8af7098401db3922.nq.gz
│   ├── c296cd8fb62a774d11b8cb41dfb826060a1346b7.nq.gz
│   ├── c2efd0b608ba84712fb3e1d01122468a50c7fba1.nq.gz
│   ├── c3bc1db818355063ca23b47041ef4acb9e992bf7.nq.gz
│   ├── c4f7cf37b4ddcea9cf815923b21d6db9a1a40a77.nq.gz
│   ├── c7c18de05bd16c0a8c1a7ea696efeefc6b82d174.nq.gz
│   ├── ca5e115348ebb3990838bb2d4efdeb9d298d6efb.nq.gz
│   ├── ca88bc0e9625745eb62054eb02c3961e3a8a039d.nq.gz
│   ├── cd272a4544f14143c0c841ad50665433cff0e7b9.nq.gz
│   ├── cd86e942a43f619bcff21d3337cd08f3dc08540b.nq.gz
│   ├── cef64e78f92fcfa04f2132af9e812aed84a95ad2.nq.gz
│   ├── d3896c98444fbe7288d434169a28c532258a4466.nq.gz
│   ├── d492d0d98c8fdc9f93ad2543bb4f531803e9df72.nq.gz
│   ├── d4f708df52a8b3e2ecddc1f4f73c7394536b0500.nq.gz
│   ├── d5bd01648a96d50136b2a97c8bb9aa5b711f6c39.nq.gz
│   ├── d5fd7147b7781292ed9bd3a8460a59c6bd3fa059.nq.gz
│   ├── d8c3b4cb018dd82cebbcba7743094f9ec15f3a0e.nq.gz
│   ├── da1e10c4a51b91fc950def7950f8a1af010852a4.nq.gz
│   ├── dff4f49561c816f70eaea557d889d31cf63447ac.nq.gz
│   ├── e00acc763309cbd433514cf3925df45b53f66b96.nq.gz
│   ├── e1d2fd9d01f474d5bbfdc8f1bb82ffe9ae050524.nq.gz
│   ├── e1f2ea6312ccc59e99191acdb412f3ee7cea1dd1.nq.gz
│   ├── e5da614e96aec5954b04c934e1c3539af00e27a6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c5c54370372a4cdde7288a32733998d87bd767.nq.gz
│   ├── e901dde684ea8ba25c50ea5dc7d5900da31a30d4.nq.gz
│   ├── eaa29be0af4dafc38771de48f6b3b4a0a637c3e8.nq.gz
│   ├── eace8cca91a8314c079aea8090c2980bd2207ef7.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f48c2b32436e1f9253f5832599fac1e8a284f8a7.nq.gz
│   ├── f72e50fb931117cc27835a9078e90140b7b6ce1f.nq.gz
│   ├── fa0b357c4f4a29c3de7c5abfa47ba9ea8e52dd92.nq.gz
│   ├── fa22cd7cb54b850ff5f76f95003b7a98e2541fde.nq.gz
│   └── fe4200b30c8ac702113fa273e928a94b1bffe296.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6d7e1acb86a5c67bcf86d99bc6034f130b1d04c2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[Xmarmalade/alisthelper](https://github.com/Xmarmalade/alisthelper)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
