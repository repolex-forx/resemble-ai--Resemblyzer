# Repolex Knowledge Graph of resemble-ai/Resemblyzer

RDF knowledge graph data for [resemble-ai/Resemblyzer](https://github.com/resemble-ai/Resemblyzer), parsed by [repolex](https://repolex.ai).

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
rlex download resemble-ai/Resemblyzer
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 15d828edebe06bc72b9cabc8ef8ca5ab2cb457ce
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 15d828edebe06bc72b9cabc8ef8ca5ab2cb457ce
│           └── chunk-001.nq.gz
└── blob
    ├── 01f944853bf541cc2a344b75b3ef61da0c2705d3.nq.gz
    ├── 041b25508f8b42760eb62dbc4786be412aa38a10.nq.gz
    ├── 06fb09b7e80ef0b2d24db6a029220243a06df25a.nq.gz
    ├── 074ed4c3257f4fbf567841efe4b9c331fede63a5.nq.gz
    ├── 075763d79d07de3afd7f4d4de5631c7b92ad82f1.nq.gz
    ├── 077c9cba1fcd3a0e0d89170d0115390947ff3bdb.nq.gz
    ├── 0813ec7d7a0a587249a2d16e63bfa2fa648db1b3.nq.gz
    ├── 08141ba554508fbb98479483d755a06feffb3f5b.nq.gz
    ├── 0a1034b9fe7a71f2d4e02c4092da45153c2e6773.nq.gz
    ├── 0a417517c3df534d84214c98ac19cee523ffe307.nq.gz
    ├── 0a585b91fef334cc7f246b30da7a1cf3093d12ce.nq.gz
    ├── 0a7b1c14a0e45c971234656ba2b792383346a721.nq.gz
    ├── 0aff1956d700ee963df1a8b437dff478d2d4bf3e.nq.gz
    ├── 0b6ab7f6bf9c223f5f22c2e0d22197e9fe62ef53.nq.gz
    ├── 0c2511c35f37cf4071f944663aa7527fdac72185.nq.gz
    ├── 0cec6012dcebc43d0b9a7343326eab83e2e52448.nq.gz
    ├── 0d48c40ea017ccdd427299bd91588ee7ce8dc60e.nq.gz
    ├── 0e65d0044f27a805e7035929f17e765fabbc7fd8.nq.gz
    ├── 10261d11de25b790b5b448839ccd13e096c05f45.nq.gz
    ├── 1038d240d7b8f202d9d0f53eee5d2d72dde81b44.nq.gz
    ├── 105b1b1520548fedb37c47fb296b6136bdbbf8e3.nq.gz
    ├── 108a136a543407018c8cc5968f42fd6d7c2aaef5.nq.gz
    ├── 109e3b44c69c708b543124ffe0a8fcd80093f924.nq.gz
    ├── 1141589ce95d75d5c958445759b212f8084aba20.nq.gz
    ├── 11711d1feaaa4999b6c697924287868a675f1ab7.nq.gz
    ├── 12efe5cd22cbdab66252c58d90a73fada865157a.nq.gz
    ├── 145610fcf823f1821746dda7d4eca976894c0be8.nq.gz
    ├── 146a2587555d306429aafc63f6fa5a64b89d4ef9.nq.gz
    ├── 14b85f25c1cf4435148b9f76a1f6e9101d61ab9e.nq.gz
    ├── 164d62542f4351cc9eebfe1ac94934db6e74ac56.nq.gz
    ├── 166d4dc595f3c0a26d1657a4300b8560414680fe.nq.gz
    ├── 16a6c1fdbb4d3a1f7e2bf00b7c4f217c9237ce0d.nq.gz
    ├── 17018db1f8194ba3c7f2db1bdaab24cc5e3d65e8.nq.gz
    ├── 1719bcacb6479cb10f62ed5d344837e4aca682e4.nq.gz
    ├── 175fa7b5e4d7fe1c89dc618a6a6221e371ffa6d4.nq.gz
    ├── 17890c89e77cd83538099e845eec4a8ef4aab5ff.nq.gz
    ├── 17d937c17cb1c89b22c0fd0c2f3d4f2e68c777d9.nq.gz
    ├── 180b2e1a172ebcc4bb454158f9c707cbdc767557.nq.gz
    ├── 18955ca054bf79ffccd5ad78cf921da699fe9eb8.nq.gz
    ├── 18d3a3047eaffc4cb492c0bd35def013581977a0.nq.gz
    ├── 192c69ce7c5121e6f25bf1689a79babc8454589e.nq.gz
    ├── 193f789817cd79ff5289dc987862271629dea3ef.nq.gz
    ├── 19590df0d9dac4de5c8a829d15f56f38494dd536.nq.gz
    ├── 1a01155638da84f7c819af4d6928c0dbaf6771dd.nq.gz
    ├── 1a534018a9f64eb0aeea805c38fb935a4592d8fe.nq.gz
    ├── 1bccc5f7ce4bd98f24e60572b51a6947c12bb6bc.nq.gz
    ├── 1c07511b8ade4271be78fda2870f0e8878d85fd3.nq.gz
    ├── 1c24d32c779dd18e7cfc03151032f0eb34e82c5c.nq.gz
    ├── 1d3afcbc73b198bdbdad1bd6dd2c5dd98a02d3da.nq.gz
    ├── 1dadae2c08f98b95edc452173a07c0ad36d49346.nq.gz
    ├── 1dbe1cbcbc9049840962c70a6165a93cc3a87af7.nq.gz
    ├── 1fc7bba13dfa27dcc29ed153131ecc002be8cf00.nq.gz
    ├── 204519334b6995b6a4dc61672b1558493068e2c9.nq.gz
    ├── 210ecaddfdeb2d15fbcd9b0f644575254dbb2be0.nq.gz
    ├── 22db2d7fbfe3a343d6cae7d51ddbbd2f47ca9421.nq.gz
    ├── 22e32fa905b12a4f66ce413f82cbb961e81c319c.nq.gz
    ├── 2381739e3af6d68b98712b1e0c4ed73d9f8e7414.nq.gz
    ├── 23f6486ba781435c7234f5973e8ddd20689f915b.nq.gz
    ├── 24f75eb33dcc5ec0734d3b65830d9203b30ed400.nq.gz
    ├── 2518e91713d19d4da49a5a160d13d534f44291d7.nq.gz
    ├── 255bd3f03a917b2e69ce497eeab009600e4510b8.nq.gz
    ├── 2584f9ae4cd50c77608ee699f7d5c69b2e821950.nq.gz
    ├── 258dc8cd2654ac8c4b30376d2b22bffa7a332efa.nq.gz
    ├── 261d0dd93fc4013cd3931282d0d19e7fdaf3cb44.nq.gz
    ├── 262a4c8066150cb3f7308bfc292ca9529b207947.nq.gz
    ├── 26b3dcc1c6246c33dede5f595a92402b0e2476e9.nq.gz
    ├── 27749212ba6fa1a35f5653287bc4445634baf71f.nq.gz
    ├── 27846df2284704e61120e1aa37d5a725e5dd5669.nq.gz
    ├── 27be4cc80066e6243dd8b77f96f73a742e941121.nq.gz
    ├── 27bf3980276ca337b81c713407d72e74f4f7aac4.nq.gz
    ├── 27ea9041cb2d4fce25a1f67df4dd6513854a64f6.nq.gz
    ├── 27f80865922f4e260ad750c2d787262359691c7d.nq.gz
    ├── 2928f2940fd373919b5fee0361ccafdbeebacafa.nq.gz
    ├── 29ef97bfea1660639f63339c887640f4870544bb.nq.gz
    ├── 2a259efbe552b87ec7cc9396c393d777b495bbc8.nq.gz
    ├── 2a852f15c28d1defbf30bdc3ff71338c9063b147.nq.gz
    ├── 2b0167f22af91aa16da76d741025a336e66361be.nq.gz
    ├── 2b1804113359c24a2bcb77b8ab9971d98d61451d.nq.gz
    ├── 2b6f3cde18599f0f4eef34401c4533d7e9acdc81.nq.gz
    ├── 2bc674ab4434c3bd57aeed4ffe2b18113ab96c5d.nq.gz
    ├── 2c7cfe4a9bd69cbb5b72e53d39777ffaebc1cfdc.nq.gz
    ├── 2c8089813c96f2b2c41fb169e4f816c990740313.nq.gz
    ├── 2c9f27d3a60d48394dde76bb2c5db64d794af786.nq.gz
    ├── 2d64ca2dbaeb07f585d03cd043024864233e2ef3.nq.gz
    ├── 2e8820523d7c91c5f2a4b271c8bd07ffbef0bab6.nq.gz
    ├── 2ee62fc1681e1a7550e38f4a1ece4acc3d934506.nq.gz
    ├── 2eee448e2e03b66e273796ed9166512c91c0fd89.nq.gz
    ├── 2f6edb699d5edefd7598ff77a54390cc00bb0a4e.nq.gz
    ├── 3047b34486e5a0121c4046143d3623aa0dac7a06.nq.gz
    ├── 3055d0f8a26462b97f91444a3a060dce3271c21d.nq.gz
    ├── 307c6c13001530c338441978f431917a9b6c33e3.nq.gz
    ├── 3179853d09b1476c5c0ee2b36fc100b620bacf00.nq.gz
    ├── 3245e9bdd85288455c6dc8d8d91ec9863e0f486c.nq.gz
    ├── 3273917e3cd8edf5305d9eb3dadb6918fd0702fc.nq.gz
    ├── 3278e977fe3940d6a383de49a8d452f3e75236e6.nq.gz
    ├── 3431aad39b84d736075724b5448370b888ec648d.nq.gz
    ├── 345ef49686ec4bcf1adc28878cefbc33bd31d959.nq.gz
    ├── 345f2c1b6d1674f99f12c2fadcc70c56c2f35f32.nq.gz
    ├── 35ada57bf3cda26e17e96dbbe6c03335eb6bb837.nq.gz
    ├── 361889afbb450edfdc867b26cb3bbb9cbada88c7.nq.gz
    ├── 36eff57fb224709f0856bea415fd9a2e662422e1.nq.gz
    ├── 36fbff23a3e460b42cbd5f9af6925a11a1b51737.nq.gz
    ├── 37727842d063cae9beca96f809131e5347b5b201.nq.gz
    ├── 37f56ac0665bc34a634f4be288c09c4c4cfdfab7.nq.gz
    ├── 389d558da5f08dea9fec9f67e562a3919dcc0893.nq.gz
    ├── 38d29aa14a7d89e3467498f6f646c691a7f5bb6a.nq.gz
    ├── 397721a2ba92bcf9569364c0e54e0e288ae2ae9a.nq.gz
    ├── 39a27efe6cd7b4c3c52196aa598555f99ebff3e1.nq.gz
    ├── 3b646e1c92123f99c7eac6374ce404cc376a9827.nq.gz
    ├── 3cc93aa3b84f2a8f0cebe421f7c4c7200bb90b31.nq.gz
    ├── 3f7628974d16e7e79bc5f837306bc5291bd57715.nq.gz
    ├── 3fad5cbdda18b659c218e4cf144bcd169c1a3138.nq.gz
    ├── 4014cd33c114ce504c7887bf804badb330520075.nq.gz
    ├── 404ad3e5b982e76fc21063540b644437d95248b6.nq.gz
    ├── 40b7d50a3aeaa230276fe5b3006679fdaae853d4.nq.gz
    ├── 40be592de54fe94cce76a2145ff4ad6f153e447e.nq.gz
    ├── 40c9cd8579264e8ea4a1011d989bbc6f111034b2.nq.gz
    ├── 40e7ff5f0b810ba4bbf396d5fcfdac23b1e60292.nq.gz
    ├── 40fe44893bd62016441fb30dd4421c735e79caaf.nq.gz
    ├── 4170f1f2a7751ad65627d6547d551a3bf2612391.nq.gz
    ├── 418d815a09553762de46829b6765b6f813d79b3a.nq.gz
    ├── 43caf464c1ec8de94165be7a0d1fbd8926f71582.nq.gz
    ├── 4494d13992f3a28522516aa24c30c8a1f1cc94cb.nq.gz
    ├── 449ebc8292fb3568c8866c592652f8d1c01c6e41.nq.gz
    ├── 44c6ef4cedc49b5c83514ba630a53563018d2518.nq.gz
    ├── 45772ad4fe17fa4b8589bd16473d7edba50d519e.nq.gz
    ├── 45a0ea01f114c124a537b42cf98383b1a416b4a6.nq.gz
    ├── 4679225495adb6cf9ad97ade98bd70fa7e1e4dd9.nq.gz
    ├── 468341617f4e26c4016550e2d0c1ec22b70c593b.nq.gz
    ├── 4722db8ab325c76974d3f0798c0c1fe5ead88ecf.nq.gz
    ├── 47bd97553b64872d2b1bec9197221b200bb9c98e.nq.gz
    ├── 47c7f976a409a23f0af65d7c17b26903cedfd05b.nq.gz
    ├── 47e405a459e4b97a21325dc78ba6f8270498ac06.nq.gz
    ├── 47e810e585070a8e550b7c77ffb726cbbc4e07f8.nq.gz
    ├── 4880873b28b04d6130d6dc05fec23efd4c527b9f.nq.gz
    ├── 48a0fe334ba01a233a31c604347038a51f819d0e.nq.gz
    ├── 48dd96bafb6d81510b5ab25c8a56e5fc5e2de95b.nq.gz
    ├── 4969fd58d32acf1ced710c8fa60d4b836c719f23.nq.gz
    ├── 49701a409c9155631c6fd6a5ab4785ed5a7b1c33.nq.gz
    ├── 49dc71989ab1540249da1014560fffd1c3322b61.nq.gz
    ├── 49ff4fe29875d9ab9c5e86dad407529c951bfe25.nq.gz
    ├── 4b3c8d2cf02d5c1c92c6f02ace9ac645beb437d6.nq.gz
    ├── 4d72c6f4d40d0316056a3acd7f9a5e7fadea9360.nq.gz
    ├── 4d9347692d13bd89ee2bfb7518be7acfc42d9c2d.nq.gz
    ├── 4de4a323c54a3946fc5fe43143ccfa66ff5e1f11.nq.gz
    ├── 4e6ff0d903695fa40e1686982de0bf62fce6c114.nq.gz
    ├── 4ebfac34d4e625e8cb72ee8041c7c723a30b3dce.nq.gz
    ├── 4f4eee3bcea27361cad0e03bc3d8b7784b4bb010.nq.gz
    ├── 4fb4ab607ce97c88f5c8c42228909140e940a26d.nq.gz
    ├── 4fcbf1b49deb965eaf6c3be757113319f7dedf40.nq.gz
    ├── 4fe49ac8849259a4da383b14894e2b0534cf1554.nq.gz
    ├── 505e4e3a7b129745ca039c05cb9ad796c8b7213f.nq.gz
    ├── 51205acb7157d8d3d772b0dec78c7060e039fea9.nq.gz
    ├── 51b1847e8fe29c9ac9282b0dd2d59bfc1825f414.nq.gz
    ├── 51f479332597a8152f57935983f3718c1b152b3c.nq.gz
    ├── 52d838f7e30a666e27965d58834b5b35f8010e69.nq.gz
    ├── 533c2cacb066fb1ce8b7bfa000841bde6cd4bbbe.nq.gz
    ├── 53aa4530a2e15f89f8b8985cbf8a1d5fc6f4b13a.nq.gz
    ├── 548de720794354a50c4fe715889a12c715114006.nq.gz
    ├── 54a27993d66b595e6e54ff2513edbe3d0482374f.nq.gz
    ├── 552c0c8022204aa5a557d043efc17ab4da4a7b00.nq.gz
    ├── 553fcd15955a559dadbcd75646c5a89d4aaa55ca.nq.gz
    ├── 5558a0c1f9b858e3e5333ded7ff2655a1e7db32e.nq.gz
    ├── 559b6185bb9265e41a26da88b1130f6298a39148.nq.gz
    ├── 567f98f37773829c16e23ee047f2fc18a4f6e502.nq.gz
    ├── 578616202bb6125cf645040517cdef29c98ae812.nq.gz
    ├── 5795e173184f86bf8d82e0e835d00d052dc497f8.nq.gz
    ├── 5972adf08cf34d3fc838d6f9c77c31168828978a.nq.gz
    ├── 5a6356aac5c45a91c15990ab94ef9ba1d2863eb8.nq.gz
    ├── 5b78bf9037a4316e4b3614246b3ef81c724313e1.nq.gz
    ├── 5d845cb74ea7ea98fd4b90fdd485a21b613e3ec4.nq.gz
    ├── 5dd1a6a379725854490a50a390a7b483877ef700.nq.gz
    ├── 5dee5e92f9f0077a45bfd2d7b3076f05d9ecde7a.nq.gz
    ├── 5e0cb0756af56cc5c093e1dd63dca75aa06f6f2e.nq.gz
    ├── 5e47a84387f30a10bc5bf8edb6050d4e1dd15944.nq.gz
    ├── 5ee651a9934f37514d91e14577f82552d03f7cf0.nq.gz
    ├── 5f5bb39a14afb795d0e64024ec35d6b81a9c0fbc.nq.gz
    ├── 5fa339bd99d5e82d9816d3186f0087ab070f1491.nq.gz
    ├── 5faaf8b6c6b08d8938c576340276209ab83ee625.nq.gz
    ├── 6044a36ededfec1e0d8f63d2ea7949fd4cf8189b.nq.gz
    ├── 6093fdabd8fa012c070b034f222b031e7ae697c0.nq.gz
    ├── 627c7c29f0db5a0efcff2dedc3c509eec84f9a67.nq.gz
    ├── 6400b50553c8914a8d9aaf85c5ce09703e28f702.nq.gz
    ├── 64068321b0e292cc6a2c9b98cf764130d0cdb909.nq.gz
    ├── 64958358eccb2b2fdf6d39e21cf6bddb5f8d871e.nq.gz
    ├── 64ff75b5bacf40bf6a6db4af93fd9b49985f7118.nq.gz
    ├── 65ad4f9f6d0abed8c14cf8725d7706bf2210a510.nq.gz
    ├── 68198345607aebe3e4af82fb2d8c9428bb9ac44c.nq.gz
    ├── 686434f0f72e5a633359ea472b3645c3b50387df.nq.gz
    ├── 69ea946fe50a511035aaa2ca1d41c09a0a050b72.nq.gz
    ├── 6b4bf0ecd25ced22dd60adcb532bf09c5ca7d9f4.nq.gz
    ├── 6c3bb0fddb3035071f2a78168bda207a3e6d9ec1.nq.gz
    ├── 6cb64e8092aea1b76462e516841a17d6821c052c.nq.gz
    ├── 6cc33250621833c6043f50cc173257bb4edec84a.nq.gz
    ├── 6cf7fd83f4bff4b921aa0f3d7a87ebf75863e2f6.nq.gz
    ├── 6d2c6261d19519a333270a7bf03d09d2d7e3954e.nq.gz
    ├── 6db00a8713a18ebbe9d337f958eb702293f7ffe4.nq.gz
    └── 6df1fca8f4800bdb5b61075311d9e0a042734e5e.nq.gz

7 directories, 200 files
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

[resemble-ai/Resemblyzer](https://github.com/resemble-ai/Resemblyzer)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
