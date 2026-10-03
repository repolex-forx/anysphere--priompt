# Repolex Knowledge Graph of anysphere/priompt

RDF knowledge graph data for [anysphere/priompt](https://github.com/anysphere/priompt), parsed by [repolex](https://repolex.ai).

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
rlex download anysphere/priompt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 64321bead70ceaec3f1ab7aef28707c557c958fd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 64321bead70ceaec3f1ab7aef28707c557c958fd.nq.gz
│   └── repolex
│       └── 64321bead70ceaec3f1ab7aef28707c557c958fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 0317600427447f32bc3679b4b096de1473c548aa.nq.gz
│   ├── 04e711013d098bae6093d316c5e028b0eeb566ad.nq.gz
│   ├── 095a346666e8b5ac7229688bf5feb195edd9b129.nq.gz
│   ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
│   ├── 0f32c22f01eef51237730559c56ee056641a2751.nq.gz
│   ├── 10ee05ec295f1b99b59dbd6a6ec5c457022adcfb.nq.gz
│   ├── 11f02fe2a0061d6e6e1f271b21da95423b448b32.nq.gz
│   ├── 130aa7bde53179357e1739430ac2147b3189ea62.nq.gz
│   ├── 1379153fe55ff2dabb7b3d808a64da70f8d2969b.nq.gz
│   ├── 13cc0ae7bb99bc8c2443a097c261df07efb20eca.nq.gz
│   ├── 1646db5e5d8ae906e41084a42c011a130e7621a8.nq.gz
│   ├── 1a483ddefc62185166337a8193a9e433bc9e6ec8.nq.gz
│   ├── 1f866b6a3c3acf7987e5089874f2193d587427e3.nq.gz
│   ├── 22c2bb2b087b6dbedbf5af09c043075ace82ffb7.nq.gz
│   ├── 27203bf5b366cf6d2a7a0ea415cd46a336b115f4.nq.gz
│   ├── 27a982a7e1f1ea06e14e214a5e5ba0dd563ad7a6.nq.gz
│   ├── 2a602e2b822c3674e90036f097ad7c393be15330.nq.gz
│   ├── 2a92926208b5bb5539769186cd4bab1d21857983.nq.gz
│   ├── 2d46f48c8f8262fdc5841e26753306576893fa87.nq.gz
│   ├── 2dff8ba0027ebeefc84b67a6351900ccba8c1362.nq.gz
│   ├── 2e7af2b7f1a6f391da1631d93968a9d487ba977d.nq.gz
│   ├── 2e7bc75651b7c305acdc8fa3efe9cea238ecdc13.nq.gz
│   ├── 2efe3184758c17cb12be35671e5aa5cc7b6b7b32.nq.gz
│   ├── 3113800870c7086b9cc4b63483ff033e93f5d018.nq.gz
│   ├── 311e011965da5f9c2a59632be4fc2d3705b6a15d.nq.gz
│   ├── 340562aff103906b000e905d3c228c55c71decc9.nq.gz
│   ├── 3aadb577a92c00419c4501a3460d65ce63befb4f.nq.gz
│   ├── 40a7d00e774e0a0a0da9d71ec653d6b61789aef0.nq.gz
│   ├── 41841bb6596dbcae221c34cdc45a34191ec0b01c.nq.gz
│   ├── 41abcc90b10fcbe498829014bd68d33dbfd4cb17.nq.gz
│   ├── 423c32b5796572b0968f2b77e58b952bbad30b06.nq.gz
│   ├── 45b4346f63a1862ff47022cc8fa16815c2482159.nq.gz
│   ├── 4639ccc69f2f03b8e6635ca3aa3e35f8958afc18.nq.gz
│   ├── 4fd940ae04e17f3481e927cd097b9dd6f70d7e1a.nq.gz
│   ├── 573722aef369b999d91f3b4e4d47a404584e45ad.nq.gz
│   ├── 5802c69cb8fe90d642f290fe56554c2e047fd42f.nq.gz
│   ├── 59e1b183b48349b0cdbc0ac7cbf9b2187015c20f.nq.gz
│   ├── 5e2577b3576f01f2a88babccd2119a471854319d.nq.gz
│   ├── 5f534ea659d33fa5e937d6ca9c5f11e9d5e53739.nq.gz
│   ├── 61bf7abd2c364c05c7868423a04fe6d6b53a8e83.nq.gz
│   ├── 646b5e0069ab151bc6f012c057a5cf00f5c03233.nq.gz
│   ├── 71be22f0cde35aa72686f12b8d6dafa855bea729.nq.gz
│   ├── 76215d6fce77b4232156f560db0790c37a195196.nq.gz
│   ├── 7641e79adadfa557bd816a720e70e248f9d4c535.nq.gz
│   ├── 7a0970e91db0b6f0d9783b3afeab1e5c804803f1.nq.gz
│   ├── 7d2afe54cfbf935aff0a2dc79020cb3ec4f9f501.nq.gz
│   ├── 7e09b694ddceea80d7cf5207e6dd326ab8190991.nq.gz
│   ├── 7ea3673b65b3cf2d45a491a3b8c19e5afe757d11.nq.gz
│   ├── 7f8f3b1b3e0f28f3b251a95ace0d0b74deb0bdfe.nq.gz
│   ├── 8b3dad5da7fc614f658a050b8c48848723c41c92.nq.gz
│   ├── 8f434a08d7a3af1f237df5be6c9535e2709e1f03.nq.gz
│   ├── 957b143583afb739e462339c8240514425b5cc61.nq.gz
│   ├── 97bbe70b68eba032d1807c17c65d152736223b13.nq.gz
│   ├── 986614676253f97ae0d4dd4a1ad9f7f8f2ba49b5.nq.gz
│   ├── 98c6f07d571e117baaeda56aa74d41e8ca70073f.nq.gz
│   ├── a0200b77e48d776d3f940df881c992f0938923e9.nq.gz
│   ├── a3a37ef9d185fbac218b6e6c428db764f0794208.nq.gz
│   ├── a494ab16596e0bc5a1cfae953a6bb3fb38b8e871.nq.gz
│   ├── a547bf36d8d11a4f89c59c144f24795749086dd1.nq.gz
│   ├── a7d75a81e4b8414ea41318a613b22db22066ccd1.nq.gz
│   ├── a803ce76677987d62c11e6228e6c02006f097f98.nq.gz
│   ├── aa066506c054bd7ce13d608f6ce046c78c1d3a13.nq.gz
│   ├── aa709425bf759ae5c9f47c1f11f7ceb43e49f915.nq.gz
│   ├── aae0440fac20764c96e65670a69363f6c3119697.nq.gz
│   ├── af3ae48f9243ee5f553608a79dcebd0c30c54805.nq.gz
│   ├── b04bb3c844dd20f08fddd7425b68cea9647338c2.nq.gz
│   ├── b3028929504edb29d539b3216075df798a4c1e7a.nq.gz
│   ├── b3a2593ba47d71517fa7ba82348e80d35b369439.nq.gz
│   ├── b545d1d782da835bfcffcb3d21fe3f195b8a3dfe.nq.gz
│   ├── b587be8f03b7756860f30a499cf44a1a9d9d1dac.nq.gz
│   ├── b703ec74c314ceacd0532b064b116fc45acd06de.nq.gz
│   ├── bd6213e1dfe6b0a79ce7d8b37d0d2dc70f0250bb.nq.gz
│   ├── bf839c8958b6e0930dc35c02a019855247792f9c.nq.gz
│   ├── c09716f5c80a2069d69b5e25af5276fcf202e088.nq.gz
│   ├── c5c832c6a1791b73b3d39df1506ade11fe8076e3.nq.gz
│   ├── c8a409f19a58c15f80b017cd29e9be6bbfd26a60.nq.gz
│   ├── cfa1ab5b950b2860ff6138c37cc94915bdba27b2.nq.gz
│   ├── d2219f9a11e673b758d5ad9503c3942ee86d10a2.nq.gz
│   ├── d2baa0d14261639f234271c456f61818b5eb3f6b.nq.gz
│   ├── d2e342f58fab5171f4daec691e4023c8529c372a.nq.gz
│   ├── d691a337e887e49e433b5c4f80e2b6fd09876dc3.nq.gz
│   ├── da9326d744d31cd2359af18886eef6a55ca71c08.nq.gz
│   ├── daa0e2c42d0c01b1e535bbbd2fee82821e774814.nq.gz
│   ├── db4c6d9b6797601f6677263cb201a46743f9d545.nq.gz
│   ├── db84e9b049a71b798ad4a4f8e6e7f8ce0eaba6e8.nq.gz
│   ├── e02e3bb854336a4aa09e3d782318b6d0bd9097b5.nq.gz
│   ├── e2be72972064fa8504b1b3cd0c5caff3a7e7f173.nq.gz
│   ├── e605825f76784e832ba4c6e63576e3083179c9e6.nq.gz
│   ├── e82c117ac55928027012eba6554f9dc435c31b74.nq.gz
│   ├── e8a6b6d5acac8e36627ac5527caf9495eb8adb71.nq.gz
│   ├── ec79801fe9cdd7711f6dbef26678a134c634a8be.nq.gz
│   ├── ee081e3d8a8b790cd2c7cd19dfdb4e72f343e125.nq.gz
│   ├── f072654d0214f20b970d55b18764f5bbad2d52ff.nq.gz
│   ├── f200f4440d2f199c57bafaf0c1485f043d3dba7f.nq.gz
│   ├── fa4222de5160aa298d89cd230764088dbeeb7101.nq.gz
│   ├── fa9cebd3b54f3ac2fa2c48357831feedd0334749.nq.gz
│   └── fc3185e33c0c0bdd89a84d39719ce3e9ce93c57e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 64321bead70ceaec3f1ab7aef28707c557c958fd.nq.gz
├── filetree
│   └── 64321bead70ceaec3f1ab7aef28707c557c958fd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 107 files
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

[anysphere/priompt](https://github.com/anysphere/priompt)

---
*Parsed on 2026-10-03 by [repolex](https://repolex.ai)*
