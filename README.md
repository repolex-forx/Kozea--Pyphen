# Repolex Knowledge Graph of Kozea/Pyphen

RDF knowledge graph data for [Kozea/Pyphen](https://github.com/Kozea/Pyphen), parsed by [repolex](https://repolex.ai).

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
rlex download Kozea/Pyphen
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 708189702c917b95832b164bfd5fc6082f348d76
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 708189702c917b95832b164bfd5fc6082f348d76
│           └── chunk-001.nq.gz
├── blob
│   ├── 0317cc5af31bcdbd8d359d76496a749b333d2bcc.nq.gz
│   ├── 03ee5095f7f3f50e0c567b26f2906224f6255423.nq.gz
│   ├── 04880ea64249fcd2abfb86f38467c18802cc8cb6.nq.gz
│   ├── 06f965147a8c0e6d3fdd7054cb1099b30714e927.nq.gz
│   ├── 08eaf82c2c8ab8487860bdb7640e38393bedce01.nq.gz
│   ├── 097799942d36cc79dcc377f7b247c6aa191da4ab.nq.gz
│   ├── 0e6bb6b7953bcba0881c70c97f48869d21d2fdec.nq.gz
│   ├── 0f06722fd9a3692134109fe6d2245e6786c1b644.nq.gz
│   ├── 0f6ee66dcbe128301022fccbb7a8c07e258a8ebf.nq.gz
│   ├── 100dde01304ae8f071830dcdf352b6642fa92442.nq.gz
│   ├── 11129db34ec3908002e09d677106f65ef8fc4110.nq.gz
│   ├── 1368798874eeb0138831c09e3679bcf41a41267f.nq.gz
│   ├── 168de2386e5dd2a765e893585521a66afc26eb2e.nq.gz
│   ├── 1d82ffc3b4044e8d587751a368a4850c9cc6bad7.nq.gz
│   ├── 1d860cfc1023cc2f4d10121f8ee543b88225f6ea.nq.gz
│   ├── 2318f7439faac95bb5224fb55b19c31cb974ea88.nq.gz
│   ├── 24543dfa2383544fde7ed9de728824f895e414f9.nq.gz
│   ├── 278ce6dbbb17de5384a99a245ec19bcbf6122fa0.nq.gz
│   ├── 2c75d04e647142638797b9eb38221b7005565d54.nq.gz
│   ├── 2dfd0fb990e3d804aad20926afa72b359a2f018f.nq.gz
│   ├── 3010a9aa8f748f7fad9911fd51e64ca2c7945640.nq.gz
│   ├── 387bcae11df1d43038b315ac7f642eedc18b8d82.nq.gz
│   ├── 39639ad2b0531d4cbccefb2ad70cb1a5b45c795d.nq.gz
│   ├── 3a8cac98d4e3a07d78f16a0bfe914b42134301b7.nq.gz
│   ├── 3f35865c3e5aec34f354b3679a1c47e1dc14cfc9.nq.gz
│   ├── 41f37a1d3b508e2cafb93fd4df587ae1ec376d20.nq.gz
│   ├── 41f600bd0370df83bf6bf1d5f4bb1b4ecca8202c.nq.gz
│   ├── 4264a28b8541d8fb41a5c5da4f763fc7e65a211b.nq.gz
│   ├── 437d4a4fd5f5c0175fb148eef08dcec276a2e8e2.nq.gz
│   ├── 49dfa83f43c41979a8694097a30f36806e3bf6bd.nq.gz
│   ├── 4afac7b60bad9d8ba42b964706837834201ec321.nq.gz
│   ├── 4f1b826088fc2d5c6908d3d9cf7fd5adb066951b.nq.gz
│   ├── 507bf242221d66043daa5c8eee27d3f5db7d1a11.nq.gz
│   ├── 53b1ae1cbc7f5c671db37ea677b01d0d57075e0d.nq.gz
│   ├── 5476256e19f95d5a4ac9a0af613a8a2b1f4db889.nq.gz
│   ├── 547904baa07e4c0a5738aae44fb2d82dcb9fe4c2.nq.gz
│   ├── 5965123bc91905894f013323683adbb635f10ff9.nq.gz
│   ├── 5a00fd21e6b7ac3d5508378818bf2dfb249e3548.nq.gz
│   ├── 5b1f33efb67e1cd1ce0aebf121f0c46c03128f00.nq.gz
│   ├── 5c17d8504858520872920aca2b765bacbbb79b49.nq.gz
│   ├── 66af19ed919a08fd06b9e1981a928f6fec21b71a.nq.gz
│   ├── 68ae1626c467cff460e57317bcc3f294e176ba97.nq.gz
│   ├── 6c296dab316bd2bc18815ddfa86a573c323ae80e.nq.gz
│   ├── 6d5aeb5f071cc133b5675a1d972f357d8154d9ab.nq.gz
│   ├── 6e5f42417d729ac8c2427fdd4806cf9460acdffe.nq.gz
│   ├── 72a97b15b047646df951a30ac81254393fcdfd4b.nq.gz
│   ├── 761e8eb3d0c24784c8b023fa288912ad65ab6cef.nq.gz
│   ├── 76868d4d3ed736c0dc2a75ddff43e567bb4dfc4e.nq.gz
│   ├── 76e5873c4ff56c209a7cb7d535aa7b0601136f3b.nq.gz
│   ├── 78ecc4e0c5d7f52af56b502030f0fd563d07aa8a.nq.gz
│   ├── 7b4769b083e80499063883d5320801152dc99032.nq.gz
│   ├── 7e0f947a01c7bcbbf8b9612deed52250ed9a6343.nq.gz
│   ├── 7e7bb497a325cbf3f897d5f6b23b98bb1895b59b.nq.gz
│   ├── 7f478d02cfcf0f15b7313e37bbb040c32cb11117.nq.gz
│   ├── 8420172ba48044f75f8b85dc498657caba8abf95.nq.gz
│   ├── 854c053cad8cba6f44d234f1729182f1a1de0461.nq.gz
│   ├── 8557beeaaf6ea167a0b04d09ca896b5867692529.nq.gz
│   ├── 8921caef8669a6da5df523fa3491dde3624db5ea.nq.gz
│   ├── 8a506283f3fd8698d22def5b48dc0767a25418a9.nq.gz
│   ├── 8bb9db00a665568dbd8b428e92d6ad0070a383d5.nq.gz
│   ├── 8c3fd8ce4bd22faca900e25e9562d9472aeca9df.nq.gz
│   ├── 8c547f9868705713282a98c498073a3bb8e71adf.nq.gz
│   ├── 8dd2d4411744fc00c377343bc3dcfabc8ec1fed9.nq.gz
│   ├── 9ccdbbcd6da7bd0f45f1e1ea9cbe5ff784826306.nq.gz
│   ├── 9d28fed425503a7552a9dcf70c561e9bcc140b5e.nq.gz
│   ├── a19141a0359c9da1317b265181dab4dc408685b6.nq.gz
│   ├── a29688b89c3ee1715e43327cb68f58641140dabb.nq.gz
│   ├── a4448e284b874f80b96204ac3eda1e01acfebeda.nq.gz
│   ├── ab71357d43b411d3211f09f7803500a1c91e2e27.nq.gz
│   ├── aeaa0c99dcfd668b19a48eb38c862413efe00760.nq.gz
│   ├── b2b3ce20b7546ce7f9f2caa45fcbc06dc10d900a.nq.gz
│   ├── be7145ee77de9a80f45f9f46eedf2d0ee03fd213.nq.gz
│   ├── bfae83391fde20d0182c6f641476ef84c0f89181.nq.gz
│   ├── c4792dd27a32d2ce510ec3e6ea008d87a7bdbe9a.nq.gz
│   ├── c4dde678f1c5a2f468122232a9f78e12d639e7fe.nq.gz
│   ├── cc39080221c44fa7844a8bfca13a6f6470212346.nq.gz
│   ├── ccb9875d7da97313bceb49b65362724dfb9fbb0e.nq.gz
│   ├── d1106d665e35b485dbb25b977e98618fa947e36d.nq.gz
│   ├── d1f762980cdc663db905b878ea0aa730ba55d207.nq.gz
│   ├── d47216bba33f721cfb2ef2c4e228964c90e390e0.nq.gz
│   ├── d4cdcddfd1b71bf52a0aeb74f5fd811af1e22677.nq.gz
│   ├── d62e3db4af3b85666511513be0bffde12e29f1da.nq.gz
│   ├── d7dd292a7e5ca48221a893a7269e352152c65b4d.nq.gz
│   ├── d85271b0ac15805c8cffc78c16a63c32d36e8655.nq.gz
│   ├── d86e8a786a451882237aeaca153101dfc58062d9.nq.gz
│   ├── d8c36b5394437249d84c63d3d2959a6b91f7a8a2.nq.gz
│   ├── da9846dfe43be037ca88fd708d4afc6920b3daee.nq.gz
│   ├── e01b66cb31088cb51d1f63d5e8e47ea826cec839.nq.gz
│   ├── e0e28acf3e9dbd2749982f14f83037d9f7bc6db7.nq.gz
│   ├── e19d0ea7508c59d767933e954345534bd33aa163.nq.gz
│   ├── e33d8cdf18e2b2a579a0d37ddca37acb4ac766d1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7129dcff7cf4d91cc2b7071df4c806a699221ce.nq.gz
│   ├── e9c91be86fa8dc62c0d70176a8d4e111e0752d7b.nq.gz
│   ├── ea4299acdae80bb6601c0ae7bc43dc3bf3a2d1bc.nq.gz
│   ├── ee6c9c70ce5a325f2becc114fc60edbfce36b63e.nq.gz
│   ├── ef3ca2e9785f6050c1b7d081d70e68a669e4af7d.nq.gz
│   ├── efba420f80303e6d3d94040fcccb5c318791d0ba.nq.gz
│   ├── f0d80c214b4cf237857daba290b8f193a8a214f4.nq.gz
│   ├── f204481198e3733b26cb0f03891689852065a5c6.nq.gz
│   ├── f4350312b2838cfd53e8ad610f969d76f0b4560f.nq.gz
│   ├── f940350ae2d37ad79354f3514edbdac10aad94c5.nq.gz
│   ├── f9c5fda5a3bf0bafbd4084452f1bbea510e4307e.nq.gz
│   ├── fab225a00f71060cdd0b3ec4fde0c3978c7369f1.nq.gz
│   ├── fcf172198afa1fa586258cac4eae1cecb112e3aa.nq.gz
│   └── fd1c94ff5492afa0093814aa92df90a8c740553b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 708189702c917b95832b164bfd5fc6082f348d76.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[Kozea/Pyphen](https://github.com/Kozea/Pyphen)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
