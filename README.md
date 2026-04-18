# Repolex Knowledge Graph of bower/bower

RDF knowledge graph data for [bower/bower](https://github.com/bower/bower), parsed by [repolex](https://repolex.ai).

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
lexq download bower/bower
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f18330b248bb5b796fd9fdeba63f0afdb76e5b4b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f18330b248bb5b796fd9fdeba63f0afdb76e5b4b.nq.gz
│   └── repolex
│       └── f18330b248bb5b796fd9fdeba63f0afdb76e5b4b
│           └── chunk-001.nq.gz
└── blob
    ├── 00a15adeee7fa22976414ddb5059a1e69d455b5b.nq.gz
    ├── 0192a2c6656957468b6fd700404736ca66c401f5.nq.gz
    ├── 01bc18fb3b29d6cd737a66a5a9af485e25fde1d3.nq.gz
    ├── 01e1e9358cfe6db0ea5232f2e037baaa8f7962dc.nq.gz
    ├── 03912e5258b5570c8a0aeab54929a9fc54ee9650.nq.gz
    ├── 04bdb1fcd873893172f4d04ee76418835e415165.nq.gz
    ├── 04ccd7c23730bcef067cce6aac77f5abd3281cde.nq.gz
    ├── 06aadaa349a9336141f1784914578663dc5ac91a.nq.gz
    ├── 07dc1dcda88af9784e701119672df616cd6d851c.nq.gz
    ├── 08095e770ca6dd40f9056eabf52730783e479b38.nq.gz
    ├── 08f43eb9a11c47609890bbad58226efa081e4cbb.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 0a816d26cc5101752d3ec8a109c00daf42e8e13c.nq.gz
    ├── 0b9ff55d991f87e9da2299770fce3057bdce3483.nq.gz
    ├── 1011844aa7a9e1fb9fed153ed9b30c982fa8ba2f.nq.gz
    ├── 115121bdea33d90ab83fa7946fa5bc5497076f66.nq.gz
    ├── 1156ec8d5ed50de9dfdb48314895961861270d82.nq.gz
    ├── 1230165c4de1519583eb34d05fb3370cdbedc673.nq.gz
    ├── 137151dee1e6541ea761426a1b3ec01a8765008e.nq.gz
    ├── 13e8246fd6f1f7fb7a54e51c03f4f46d287dfe8b.nq.gz
    ├── 1719e4a86e55038c14394d10afb543341575c42e.nq.gz
    ├── 181c196316ccff411fbcf92075f143f9edb836f1.nq.gz
    ├── 186dbe5f59127312a8d9fd6ddb8dd12d4fbd97fd.nq.gz
    ├── 1958a73699e2f18dce230e8839a9d3e9b7cec6d1.nq.gz
    ├── 1b6c50d996ab9390484d22b55f1e616c58132bee.nq.gz
    ├── 1c3decbcf1e0642ea94d778c52f6c475fb66f477.nq.gz
    ├── 1d98f420c32f43cb5da2edf0d96cbe186f4f0a7f.nq.gz
    ├── 1dde1c1a5106d9a4e836aefd5a848036a74efce7.nq.gz
    ├── 21672491276af0d8186e2d3140c6c559bea36b63.nq.gz
    ├── 22b792c3774a6372bbb9a4e6cf0e1aa78faee7a6.nq.gz
    ├── 239318c84e843311fa348ae6f0178ed3eb61c2a0.nq.gz
    ├── 24141d1a7b06d8b773475e9c52cacba35a217064.nq.gz
    ├── 2623cc00746189371dc2cc55a061e646927ce240.nq.gz
    ├── 26d398590cfb6c416d00d8b69cc9c904c8c29051.nq.gz
    ├── 26ead5d3c3387f23120a325a4b02a68f5d37f868.nq.gz
    ├── 27407497d9929ef29a1222f339fd6e6c5c7733a6.nq.gz
    ├── 2784dc3d19f39b5e3507e5c89569a36205b30ff0.nq.gz
    ├── 283a6f067752306f5199f0541443667948c49144.nq.gz
    ├── 290d12931024564f3f87dd3cef5a630f6e1c87de.nq.gz
    ├── 2a5a7f0c95541037c4ff4f15127f003285786c1e.nq.gz
    ├── 2ab15f603b644469f81ad470cd9ddfea50fb31fd.nq.gz
    ├── 2beb7d4eeb975aa5cf77678785a65bb432a62e1e.nq.gz
    ├── 2bf577442b383009e32c248947a0d52bb271668f.nq.gz
    ├── 2cbebc9164e1fbdd72f70f40a98c7e929e29d9ce.nq.gz
    ├── 2df4993b77399d19814c6ff6d0887df325c6f4ac.nq.gz
    ├── 2e71be584c27b5bd1342b03412d259183f0d9861.nq.gz
    ├── 30f376589da543a87bbec5d68df26b1518467129.nq.gz
    ├── 31b157ca3f72f02704859d07da490f06af2d76c7.nq.gz
    ├── 333a58ced75d0e57869d97c835b3cf954e8abbb2.nq.gz
    ├── 339447ed973905ac1c12d254ca850eb029c73d2c.nq.gz
    ├── 397d5ee0d6ed9deb7fdb3ea55c6b1d933657f2cb.nq.gz
    ├── 39970805e43afcdc750ed9b3a71ca32abe4cb4a7.nq.gz
    ├── 3afa609a3514e098a79ddc9fa296363f0a8400b6.nq.gz
    ├── 3b10b3d6d0df354fa04285560721026d84d4677c.nq.gz
    ├── 3c0f70db53ca1cb88dbca5cbe932063ff79cf250.nq.gz
    ├── 40a034489db599e52fee5c22cf6bc897668997c3.nq.gz
    ├── 4257a9394822b1970547bf373c4eed1b7da05126.nq.gz
    ├── 42bcf25fc5fae9a87125f2e7d5ef94109a5b69f0.nq.gz
    ├── 42f6790579b26d91d6b2f272cb2dfdccd63b7651.nq.gz
    ├── 438d40cc67e8bea615ea5f9f8ac3b59dba23e7f4.nq.gz
    ├── 44148200e2e85db4b930b80bd337b7195ef33f04.nq.gz
    ├── 4545c0adb23fc91eab10a7b4b41c207dbfba482e.nq.gz
    ├── 45e665267f30a842a046297a9160c81670333369.nq.gz
    ├── 46d4bd0190bcc8da40e7b297b6c6cbd98aa12264.nq.gz
    ├── 47ba130b55ab23ee6991b0cb19e90a524226a73a.nq.gz
    ├── 49c0612f3ff9b14d513706cb2d585094598df3ea.nq.gz
    ├── 4b95ae5abaa9df47739617623ad0bf916a79dd63.nq.gz
    ├── 4bb98a4681c0f940f56f03c7b6715cbbf74e8407.nq.gz
    ├── 4d5332491ca6d1d90d288d317f86f4470e24c262.nq.gz
    ├── 4dfb929c2f236e283aaa418a48588ce12697db41.nq.gz
    ├── 4f3a640d94336393454bc99d53ea6651adcbb56c.nq.gz
    ├── 4f43807409a9bb3cd665b858b6536187e4eea3fa.nq.gz
    ├── 50a667ecb9bc2a3cbc03ffd13ec08a623be1ea63.nq.gz
    ├── 5158dfc4acf4abeb6b26d3ea642717a9447a242f.nq.gz
    ├── 519774b8a1a5595d27f12363360f79642c13b472.nq.gz
    ├── 51d54605942d994a6b9c4607dc115bb1f95a88d0.nq.gz
    ├── 547251e0bb9c0351f089b60e7ed20e957c87284f.nq.gz
    ├── 5534f6286af03a630f500ba96dcd0622c6e48bb6.nq.gz
    ├── 57aec33e0cc213a1f86654985f3377c5fdcf7d13.nq.gz
    ├── 5a4e539fc4931f3317ff454bc9699a020637e325.nq.gz
    ├── 5ac46e3fadc0188b46db20b515fe9155c5a76452.nq.gz
    ├── 5b4508300249329e3d962fa6240520c577bb18c6.nq.gz
    ├── 5bc17b8fdbe3db36e8f847229bd5b78e5b96603e.nq.gz
    ├── 5bcc67e4abb461b0b5f2a6478151b7ea8c5dc627.nq.gz
    ├── 5bf624628ab83e49bc68ceb6b8e3a4061460b3fa.nq.gz
    ├── 5c60cfbf8e40c420f5a559311b5a611c73a6c2e9.nq.gz
    ├── 5dece8e1070a1af0cf07480718c08c56dea03243.nq.gz
    ├── 5ef6ae306f5e60a41675c6427378dedb7bb58aac.nq.gz
    ├── 61c242c46b640babd699898bca80ed3bc214afc5.nq.gz
    ├── 62172636ce8aea870f34b7e98a13e8a101ff2555.nq.gz
    ├── 622e53a17fdb861871509e62528d0ba7b2a15b2e.nq.gz
    ├── 6350b6a5f3b3672a97992c48f0a64c6076dc7d97.nq.gz
    ├── 638af93e9e48e8343cb248a2f968e939d301fb3f.nq.gz
    ├── 6526821d3e60a2a0cf7f59a338c68d547ca00aad.nq.gz
    ├── 66bd4bababebdf6f95072e367304e1812a62c6e1.nq.gz
    ├── 66e91e3243ebed14ddf48cfa4fd514991180b46b.nq.gz
    ├── 676debc0574406934b527d2a96d243e2b72fb546.nq.gz
    ├── 67add744a975906fce86572ba7979329a64b16a6.nq.gz
    ├── 68129263966872fbf8934eb04957fa9aede4aec2.nq.gz
    ├── 6aef2f05ad2f7a543f854f2d3042c025e4fbc294.nq.gz
    ├── 6b120a4ca1773c576a13ebe252b0ef161f502a3a.nq.gz
    ├── 6e5762fca7b95d35de5b65b03f3e32f8a41d4dbf.nq.gz
    ├── 72c3c12f807c3cc98bb985a02e23f807c5cc6ee6.nq.gz
    ├── 731d027078246310a80d4e2db57601478c438529.nq.gz
    ├── 73f863dbe02cdd04ba3fe0e7c5da7c83a9231c00.nq.gz
    ├── 76a40e4723c0324989e387e177fb1e1467ae2c56.nq.gz
    ├── 774e0b438df8a2a6f8c76380356225688893cad0.nq.gz
    ├── 779f99a12b5c71692ad6d6908d6d2fc3bdba485d.nq.gz
    ├── 78431936c3e5fcd7235ba8728651ce10362ab564.nq.gz
    ├── 7ab40642e4ade00ade79bafd97112280259a2444.nq.gz
    ├── 7b4507e117da78506810c3a999b9678ec02d1d3f.nq.gz
    ├── 7bb6cee39af6156fd189744bb92befbfefcb8a1a.nq.gz
    ├── 7f42be2d98698893b1e5871465020d2fff9230ac.nq.gz
    ├── 80c4481148299426488787094665cb916add1092.nq.gz
    ├── 81330223f19bde77ddb7d61749cf98c1e0b78661.nq.gz
    ├── 82876e1931938d0c6ef549b9986a6a5cd8f9e37a.nq.gz
    ├── 845bd1554ac0ba42a3291f3bb518aa0988709897.nq.gz
    ├── 8559e410e102e3ada7c23553bcfa3dde3239de26.nq.gz
    ├── 8641806b8cabaebdeaac9d0abf1c76eddd06595a.nq.gz
    ├── 86671ba1b81abfbe17874b0ea6a3aa211f102bad.nq.gz
    ├── 88229b6af4db2e1f860bec61326a13bd26c2ffe2.nq.gz
    ├── 8935fb42291f9030d6e3a6ce900d4ee41e64cfbe.nq.gz
    ├── 8b69bf77d1f382a648cdb8d3e3420459315080a9.nq.gz
    ├── 8bed5ad479d79088d2c05b1736686bbd8ad175c6.nq.gz
    ├── 8ca7507d2a53bb7b466e1596db3679fd1299bacd.nq.gz
    ├── 8d00b85a95da224ecbe9f7f3134e5b16f52ad33b.nq.gz
    ├── 8d776deff846eb47640a9e8c39eba43ed517b7f8.nq.gz
    ├── 8e9a4168a7721247d6e8c2abe396afd53ce0b4e8.nq.gz
    ├── 91227c478716579d8e570f4ec5aadb52479940f2.nq.gz
    ├── 9219a2f4f93e7d81fae16583a3adff301bea8859.nq.gz
    ├── 929f933f3d10ca6fb3f145ba48a5a0b989fce9bf.nq.gz
    ├── 92a55e7b5177584affa5b8bf2c46b978becd382a.nq.gz
    ├── 936c1718ef484f8bbe0249834b53fa701f7be596.nq.gz
    ├── 93a0613e1b9f90741ee560031ff14326ce84f8a3.nq.gz
    ├── 9481f85795f53e4244e87898f3426cf624c22889.nq.gz
    ├── 94a87e158d4249a2117d8225502cf4f20dce7c84.nq.gz
    ├── 957ceb93a05e1fb1fa7aa6d31471904c9ad9b28a.nq.gz
    ├── 98232c64fce9360c79f119cf6de8f670f69f1c44.nq.gz
    ├── 99ca1f5780351b4f0a20034d2bf12ea6b92010d3.nq.gz
    ├── 9a15c49dc385357453810217500419bac3fa161e.nq.gz
    ├── 9ade305ea4120073ce8a591a2575bc493a2df77e.nq.gz
    ├── 9b234895dab6a8736d3507e3b3a2cc2434716eb7.nq.gz
    ├── 9cf47edb774176e6ac4afaa2da300cd7cc071b4a.nq.gz
    ├── 9d39a3c1ff39d9ff8d7f980b9c589df1c015e83c.nq.gz
    ├── 9ec5153c14ae8802dd054ec78d27893a7ca9a586.nq.gz
    ├── 9f3870786328b24fa044fe5456fe2bd3a8a21d69.nq.gz
    ├── a163667dc17c9697e02df879f185d3a8fa38c235.nq.gz
    ├── a17ba96c1f9ff97ebf959399aa17c8df5f4e6272.nq.gz
    ├── a183f5c39c6bb6deac9374d31d5826f1652a9b44.nq.gz
    ├── a2c3f76dec67c0efd73b15740056ad48422b1e1b.nq.gz
    ├── a470376d2b84199baea8a1423b3f6755bb2e36ea.nq.gz
    ├── a54b03adb87e9c7c73249e107edbe47eb416cfdb.nq.gz
    ├── a5a45d4533d330784b3b41cf559ae71fa72c2c2e.nq.gz
    ├── a5c6f200d747796717ac1a2fa4d22a80f212eee7.nq.gz
    ├── a79407e9e408860240603a593280f9f29b4d163c.nq.gz
    ├── a856392cb0dd09923a22ede7b39e98202904c100.nq.gz
    ├── a867cba2a68ab0c827ea02f84bf4b244b1b6db0a.nq.gz
    ├── a9c33bd8685b9c5e8d3c0d20bf7c8afd9eb5a136.nq.gz
    ├── ac04f062ccf0acc6500c38ecfdc250b1fdc2ccb2.nq.gz
    ├── ac4375bd78b630faeb2a63333cbfd22be1c61201.nq.gz
    ├── ae3c88adee2ec2035075e4d59edafb169a0e3156.nq.gz
    ├── b02fec2bb126eb893fe81c051dd8434de569d1c0.nq.gz
    ├── b1ca44ee7a672d65fc5d94b5c5130bd1ad46a81c.nq.gz
    ├── b316e8ae0a4e3baa6991b4b33ab350ab8fc19534.nq.gz
    ├── b3954f3719f3cbfb0fa7046c03d19bd8fdf0b16a.nq.gz
    ├── b4145fb6f3cc57e60fb78f76ee727297b2036b33.nq.gz
    ├── b4afe1749b74be8f3279f9979aefea794e7e07e9.nq.gz
    ├── b5406393421f1db9cca7005a0ebd17bbcf5d0654.nq.gz
    ├── b6c26732ff7bfb19f58ca48e192db0513158966e.nq.gz
    ├── b7d0c40ddf870fbec7bfcaa52ca5920fc1142321.nq.gz
    ├── b9b1598e8003b7b9dd9f7d901a8c2e7065608f65.nq.gz
    ├── bb1c9ff1610dac0094dd9c566dce8dfd6b073371.nq.gz
    ├── bb25acdca57087b0f709c42d9846f97a2a6bbc1e.nq.gz
    ├── bb4940e13f2ca24352dbb4505f4536ff75331571.nq.gz
    ├── bc2785c49ba72c1d7a555939dc972c481e6b9e04.nq.gz
    ├── be6c6e294d6cca6a75e7520a5f608d052a7600c0.nq.gz
    ├── be8cfb6681fecf91fcb53f47d5dadcf79df829be.nq.gz
    ├── bf3aa1f838e8290503cdd0764ddaed432de4b4d1.nq.gz
    ├── bf9669c26f42064c638e932d797c30518a3cf0a6.nq.gz
    ├── bfb3e22b0a0410c3cc9d7442656f0aa7ae51de22.nq.gz
    ├── c1a47b294ad23c5dac0a28906d5f8b8263147f6d.nq.gz
    ├── c1d624306df3b320fe378b28fd8d00e56e5c9277.nq.gz
    ├── c2d0364ec006777747adb73d15702e6ef0caa040.nq.gz
    ├── c32cd5786857874b41649aed6df442324239f15a.nq.gz
    ├── c5c28e12716d06c1eecb14d7b4a6a2dbf0464b10.nq.gz
    ├── c5f448feab0d749976226dc3d65c1dff00296145.nq.gz
    ├── c88c03440ad13b6fa8ef9d03f116c92ac9db9294.nq.gz
    ├── cad36863c12f60124f86b17b5afe85d09f2d9d05.nq.gz
    ├── cd17c7c9829297a9036be66ddfac541fed8c94f1.nq.gz
    ├── ce85f92a9852e3482a5f1e99c232844e5e48fae8.nq.gz
    ├── ceb396290d68ed5bee08a4fd22d054aa820813ab.nq.gz
    ├── ceef4868c806408abfa57439e58e8a63b3b11a54.nq.gz
    ├── d0178011824d432461450f66cfc5504a60329bf2.nq.gz
    ├── d197a382413470678cd3edbaca37eefaddef2ee0.nq.gz
    ├── d2da3b90b2716d041eb95a58d96942e32114994b.nq.gz
    ├── d455fd3c882d8d311ac14170aa75d04d14b22e04.nq.gz
    └── d475c459aa7ae5840032feb7ce27bb74bdf13ff7.nq.gz

8 directories, 200 files
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

[bower/bower](https://github.com/bower/bower)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
