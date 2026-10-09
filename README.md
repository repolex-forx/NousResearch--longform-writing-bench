# Repolex Knowledge Graph of NousResearch/longform-writing-bench

RDF knowledge graph data for [NousResearch/longform-writing-bench](https://github.com/NousResearch/longform-writing-bench), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/longform-writing-bench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d1c625505b1cf8baf32a49c8e21a9cf93a254044
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d1c625505b1cf8baf32a49c8e21a9cf93a254044
│           └── chunk-001.nq.gz
└── blob
    ├── 00120fe72868f2245fe6a483796d64ed24a64208.nq.gz
    ├── 001ebe7e6351750e418dbc197de3eb455d63ae56.nq.gz
    ├── 02e81261eab03a941e79ba94fa477da68f43f80b.nq.gz
    ├── 035c1db3cae16ad0aaa96500f2cdb3a6e936f800.nq.gz
    ├── 0381198d346fb44a3dfa9c6c87a025a024e375c5.nq.gz
    ├── 039365088015c9aee7c784befc03f39a79a3a2f4.nq.gz
    ├── 053185e5d299739eee7218f2e93876f0c3a5463a.nq.gz
    ├── 05ad2076407cb3a322d68960f897ee2424700154.nq.gz
    ├── 0629c39f36f09e6e49766e8afcaaf49868f9145d.nq.gz
    ├── 075d1aefb5f2be373474f9686026ba855c19a9a4.nq.gz
    ├── 0c31e9f57cca4d7f0567aa0d39baba1f54c1d160.nq.gz
    ├── 0c93b7e680cbe40208f224ce5537da94d7cd9e16.nq.gz
    ├── 0d19c1aab1699be0998fb19fac09c682657cab95.nq.gz
    ├── 0dd0fff17c7dfc232b6e0fdb0e2cb9d627141998.nq.gz
    ├── 0e64ab96ea20d7849426e7a8894dcf9e0a8412e4.nq.gz
    ├── 0f6fe709cdd408727185b45cc8522e46a66f8060.nq.gz
    ├── 1048b07a1419df243b60971b59cbf813bde6d768.nq.gz
    ├── 1118631b688d1b89f5297e62ec9b0f916a5b9771.nq.gz
    ├── 111a131ed239c819c66114ba3e774f8ac4290d73.nq.gz
    ├── 113cd3b44a9fb2655f5182815e772fd71b8feb5f.nq.gz
    ├── 128d3e717ddbd8aa21b4b59dfeb82e8b9b70cde6.nq.gz
    ├── 132cca1602beabba6145d103cca0592c13f3a39c.nq.gz
    ├── 134e8372f4a8aeb117168da37c06c9a1e4abd503.nq.gz
    ├── 138ace200d848d9001a01ba902272c418beae0f7.nq.gz
    ├── 14d3595bc7260c30d8dcd777b1d7d5c2b9dfa241.nq.gz
    ├── 16a1560e8de30e53bed2b05f643b2e4a902a975f.nq.gz
    ├── 16ef7da7ec14d8e92c39607eb0a482c74986591d.nq.gz
    ├── 177b21bb0b4532c900a11de79e608d7d6feaf72b.nq.gz
    ├── 19a509641c5391eb277a09cc9583858a22758b66.nq.gz
    ├── 1a2a6f252d75104b822141ee84d2d7f89edd0944.nq.gz
    ├── 1a56735903475ae1011b66ab1d9fee7d7c0b3789.nq.gz
    ├── 1c49fb2401f8379507fc415850207268b130dd60.nq.gz
    ├── 1ccebccfea89f68f413274a8ec1c2a9bb2c3648d.nq.gz
    ├── 214c17f03fa551b821285a91fecf248e5d4eda3d.nq.gz
    ├── 22ee0e6ace52ad06e4ab89bc6e4f29e53e843f2d.nq.gz
    ├── 23454ff1d8263a83ded1adf367f473d7dc44e2c8.nq.gz
    ├── 2396b202efb5e40783416213c35359fe1352d900.nq.gz
    ├── 23dbbef7ad33589162417e100093cea56d8dab03.nq.gz
    ├── 25b1aadf0ef99ac11b2441400255517751cd49e9.nq.gz
    ├── 2643283f2a1da5becffcf5bf3356fe6c39785f2a.nq.gz
    ├── 275f305e27f250c77f0e30bd6eacd1d629e97958.nq.gz
    ├── 27d32ed961e7b7f72524b10d9fe8ab6afbe6b997.nq.gz
    ├── 286c38432de379c198b3c803f662b351ee085a50.nq.gz
    ├── 29ff69386f7b74fe24f0cc85dea86771f5b7dc47.nq.gz
    ├── 2d4e33122bb9aa2d71bc5c358889eebe5f5ff1ce.nq.gz
    ├── 2e22c5ac2155de62fef33769f8de55bddb808054.nq.gz
    ├── 2e8f777ded3bb74a45107f57a5921d464f17d321.nq.gz
    ├── 2ec6ca3fe4eb5e80faacbcd79c1632106fb94dad.nq.gz
    ├── 2f35bdf1cd4039d924d7a3b47b03f5b9405d83be.nq.gz
    ├── 2f7468b2b42b3ba4dc4d4f9460451918246c355c.nq.gz
    ├── 30380bad7811d297892d3bd295516856ec4c41a5.nq.gz
    ├── 305b0b8bad1c47b87f942d663bb9b3552bfc71b5.nq.gz
    ├── 30f6544c45295804d33b59c98a335c817795b5a1.nq.gz
    ├── 3138b9583fed9c3061c46ef647c07b8e08f1b599.nq.gz
    ├── 3461a928f439027a0971cfdf0a9bac6281510257.nq.gz
    ├── 3505b357ea8baf30989cc85a47db6150610d08a0.nq.gz
    ├── 35c41bfc6ec38b6d6a52258ac7b905848f2819a2.nq.gz
    ├── 36109bacf238cc97aa747ad4e8d0e27b51e56c30.nq.gz
    ├── 36423c33fbce703402a0e4c11ad763f4e4d13754.nq.gz
    ├── 36730e3e39b5034c058315cffde58a999c6b5156.nq.gz
    ├── 3874205d6dab7c437dd730a0e992b155ea7ed7b5.nq.gz
    ├── 3b387eb859cae066d971ec9fe1dcb9b0263eb6f7.nq.gz
    ├── 3c8fdf9686d1bd53177cf59a07637b69dd0fdafb.nq.gz
    ├── 3c967bfc30754afbb913e4c1d6fe97fbc81825ab.nq.gz
    ├── 3d6736bd470c054fb36f9acc0f4fcdd85584effe.nq.gz
    ├── 3e600b9ae9e877c0df3aeff6bd4e5ceaae9e6852.nq.gz
    ├── 3ea5768d3806f5cf21316c3d0b4aab8256e73bdc.nq.gz
    ├── 3f348341cb5b76e13dbed0555a58e964d71f8613.nq.gz
    ├── 415ab15470549a877bd9820b1d846fc4c4d648e3.nq.gz
    ├── 41ed05795e4fa1ea04e6fb09d89d26d1ee7c95ae.nq.gz
    ├── 4297f173868bae0333bd1089d73df42c5e7421c2.nq.gz
    ├── 42ccf67005aaa2b09ffba57ec9d9dad6f5efd5e2.nq.gz
    ├── 439a46dd4bbd0e8c8704c5b0b0df121c649cb4e5.nq.gz
    ├── 43af118064102e0fe085a006a4b8e27716b4da6e.nq.gz
    ├── 43ed4f5ee6cb01173b448af26edb9d7459f9d365.nq.gz
    ├── 4456828e07d6593090160f52ed1daf43e98a40ed.nq.gz
    ├── 459be7b425037e890ed948954cf8078263c04c21.nq.gz
    ├── 46b3583c5fd4c82cdd3d5ee7a4403cb4896bc1a6.nq.gz
    ├── 46be14d296830bddcf5ee7ad65f7cef516961666.nq.gz
    ├── 46f4121cc88d5e8c3e07cfac8960d3fe3b141ec2.nq.gz
    ├── 47ec38e4297b7a0303f8a1fb89f424b3a017c96a.nq.gz
    ├── 4b592f9647b59e5f055cbea7ce777974aad07e79.nq.gz
    ├── 4ddaeff3e7e7bcf748987db1a1ffa242c38cc584.nq.gz
    ├── 4eb3393528e2fa37ea5d59d9406f8717c808bd9c.nq.gz
    ├── 4fc617027ba0d5e3ec20d85e2480669d84b4b669.nq.gz
    ├── 514e3023f69a44707b537bc09ca9dbd7ccf93acc.nq.gz
    ├── 525397da6adfe9d97aac5370e505bc53d7a6dbc3.nq.gz
    ├── 5349b2e4af63a1cc91f209d95d355bb0800e94b8.nq.gz
    ├── 5483c18194f02eec7185450713b61d01f079c85d.nq.gz
    ├── 54bcacac7a8ec79b927d0f11ab9b4fe1eeccf480.nq.gz
    ├── 551f1251eac169583b46502dc5e61b55b2f5abbf.nq.gz
    ├── 5686b3db1075ffc7129434445c19fd0ce5d32eb8.nq.gz
    ├── 56b7dfd8ebc277c13a9b1a144787a0c88369365e.nq.gz
    ├── 56d212b34acc7774b1a6c6ac5c015606cf440d10.nq.gz
    ├── 58c0a44744a42629c71b33018ccd96410f1e4a1e.nq.gz
    ├── 5936496a3c0f1d93e94e499c064a088f1a287120.nq.gz
    ├── 5af42d473356441cc19d900ed5f8bc35d065edcb.nq.gz
    ├── 5b09b35bc1f088db879c950be995530db28b52cb.nq.gz
    ├── 5b7248b8c24c30a682b895493f73d1b135999ad5.nq.gz
    ├── 5c88739bdf1b4aec798fb58c873483a08a538b2a.nq.gz
    ├── 5c8c8b145f8a58aaa9529ba76e9cf4a74f78ba3e.nq.gz
    ├── 5cb2e9896f44d550d9d1f604801cb210c89df434.nq.gz
    ├── 5d78199d7e7175c90c8f9d04aeeb8075821797b0.nq.gz
    ├── 5e40d61ae9cddd809d97376bda2fd479e7cfb6d3.nq.gz
    ├── 5eeff3a594a7fea76b4affb88e5029670d61e98e.nq.gz
    ├── 5f05d08e4dbe5266f396c553493979efc5893755.nq.gz
    ├── 604f35aeae5c32b8e653af200d3ef98b06bd857f.nq.gz
    ├── 606a7986bc5982f16dbca8c1298ff967a7bdfaff.nq.gz
    ├── 61521b158fe70ed8d2e3c32addaa384787d1a679.nq.gz
    ├── 616dd8383765372cea327971b003de688e39bebe.nq.gz
    ├── 65a715ed0cb5291c523de8f4ba3b5d200175ad19.nq.gz
    ├── 663d1de5020e3136376176d106dcfae52c1a7ccf.nq.gz
    ├── 66a252f8f19c4a68df440de19e584e34ea83ea93.nq.gz
    ├── 67803bb642742643c9525b6d25b8ade89383232c.nq.gz
    ├── 6921df2260cef1362ad369beae3ab05c48be4fa8.nq.gz
    ├── 6b088a71193dc27290d27f910bc5d73214f3bbc1.nq.gz
    ├── 6b90b76687ff96a476491a01a971db30dc05998d.nq.gz
    ├── 6cb4656c66c4938d3620d3a4cac76395030d136e.nq.gz
    ├── 6d10b333a0e9162bbe0c4aeea1a3867a7a78809c.nq.gz
    ├── 6d1e09b240b04076a38937942d51b8f56f701958.nq.gz
    ├── 6d53d2387c970226bda906a86e6896eaaeb1663f.nq.gz
    ├── 6d5eda19d2ac913718520954a1c29056c3c7d6b3.nq.gz
    ├── 6d87caec3dff1001bea30c4fe462ceb7c72c8124.nq.gz
    ├── 6dbb73e30dd1919e5181709df75a3ffdc8af597b.nq.gz
    ├── 6ee97b889596da4b427f4230fe5ccf1b0a098de7.nq.gz
    ├── 6f46a5e692a820c3d2c616f5b5f50784befc5260.nq.gz
    ├── 6f806474948b2cfc5f8fb3fcea4b49e67c49031a.nq.gz
    ├── 6fcd5f964d3c54b1a94ed4ab2311fa3cc0d9f493.nq.gz
    ├── 6fce50a8415d1196c894f13bd9c3273f55d4ca51.nq.gz
    ├── 6fece4083da0cde5b517d9b5f1e8c4a74a83d8ee.nq.gz
    ├── 6feec410caa31215e40cacaf2e74f381a8fa8cbd.nq.gz
    ├── 70732702748cd3a231b5064f4e1d86422ef604c7.nq.gz
    ├── 7092a880bbdbb22299a7bff0f2fa7879a8f1ad2d.nq.gz
    ├── 719e3dd5c8b792dcae0c8d413de106bee157c5c0.nq.gz
    ├── 71a168bfa05d6ee7578eaf265f3ccf3296b2c441.nq.gz
    ├── 71d90172f10fab5ed0fd422a40cc09e7ef558072.nq.gz
    ├── 7214c6533aebc83fc277efc804202b733aa903a5.nq.gz
    ├── 7288b501f18cf7e4a0273a2f8f15b7eec00983ae.nq.gz
    ├── 7390e4558c6d7f79db856f5085c87a26abbd9193.nq.gz
    ├── 7481e7ba8a3b6fd261eb423fee4941ab65ed7a99.nq.gz
    ├── 7529d1b9051a6783bace1039d864d19bb8715a05.nq.gz
    ├── 75608c6642d677d8e05f46a3d3bd3669db806f53.nq.gz
    ├── 75789b42dc4d57224a6b87e7c094bfff8e3ed0da.nq.gz
    ├── 75865b91621dd0f1b5952082d6c64b94b5d38cef.nq.gz
    ├── 75bcd43c4a45af714e6cd4b94d9b0a6d16595d36.nq.gz
    ├── 7601048e7d85501a2cf4f24b292b4c43c41e0f2f.nq.gz
    ├── 78061d19d0a8618e01a52078632bc5e24f148eb9.nq.gz
    ├── 782442a7478bf6eb419a17f3b9cbc07383570729.nq.gz
    ├── 7a6f9c732b258bf8a6c18d2bd0e6fb1232c69f17.nq.gz
    ├── 7bdf0fbca4cf66bc425af22506836490ad585add.nq.gz
    ├── 7ced21a76727e970628b17072ed94304e3671dac.nq.gz
    ├── 7cefdfc2cadd8ff4087974f845598f22b5118350.nq.gz
    ├── 7d9d888d3dd65e47a600cf0023f13cd7ee5e1f69.nq.gz
    ├── 7e3bb2f8ce7ae5b69e9f32c1481a06f16ebcfe71.nq.gz
    ├── 7f68f9e2421892caccd71dcc8c9e616f6d8538f2.nq.gz
    ├── 7fc00c82d32295241158deb2d95809c30c75de83.nq.gz
    ├── 802200d27a52407e95d91fc629b5e2a062d8bef1.nq.gz
    ├── 80ff64eca9a251e05588220c2f359932c6784b6a.nq.gz
    ├── 81afeea53c93ec9135834ae9b9b90066a065134e.nq.gz
    ├── 8312b2ce94b9bc54e5978413e0f8d2faabb6c35f.nq.gz
    ├── 83744c15a415d5d4dacf533f78b210cbd6b3c9c0.nq.gz
    ├── 855892833a465faca741e8c571fd5b49431989f5.nq.gz
    ├── 855b6f4766f255e2bff451c15bd7af1f62e0ed39.nq.gz
    ├── 85e73759e728f91d7d7ea86b52a07ff42af2de8d.nq.gz
    ├── 8604aee4a81785c1261b7d03b7a4c6532e0b4857.nq.gz
    ├── 86a59fff03aa31777bd4cb4763d0fd611c68e16f.nq.gz
    ├── 877d30e355cfc13f837a23ece0354239d1090774.nq.gz
    ├── 8925aacdebfdc1b77b2f2e36a46b56711f2b6fd4.nq.gz
    ├── 89673de1cafba469d539775b471500705c018f57.nq.gz
    ├── 8b84efcf8dae734db522f88ca944c855a8a5ebb7.nq.gz
    ├── 8b958a074595ca7e50505c5272665b9b781336ae.nq.gz
    ├── 8df6ff2d14d537957c1f1782acf4758e46370041.nq.gz
    ├── 8e8d77a95655d6faf0cdbf2845b88a6d96879ba1.nq.gz
    ├── 8ed8d79cb8edd3481f253a8ac5d15bd445370c0f.nq.gz
    ├── 8eedb64afa4971743d2c42964c8852ac29da1ef4.nq.gz
    ├── 8f2be7ae4e385e40388903f8e13d2b374dfd9dd0.nq.gz
    ├── 90e2f20cb96683824b54ef2e663ca37ae9ec8dda.nq.gz
    ├── 9266b0bfd140d427dbf4a325b23b5231948acdfc.nq.gz
    ├── 929a0938bf3c19092cae78cb3dbd2d081798773d.nq.gz
    ├── 9400c67e7e7a696d2751834b85de059d7cdc80a0.nq.gz
    ├── 94e61089e0d90db3f6b5d53f37e71543ce86ef04.nq.gz
    ├── 978e53a7de6f5f8d1febb9fede1df0a077c03b21.nq.gz
    ├── 98c74e0a4228f2c6b06c405518e09ea9b79c43cb.nq.gz
    ├── 98d7b0d5ad30f57eeca2ad3fe619d16f96c6f8a7.nq.gz
    ├── 98fc941d5997a50ae84764149cea200047e71100.nq.gz
    ├── 992564c034b13c846d93bd0b8cba298c6f4bb78a.nq.gz
    ├── 9b807921f7cbf34de21001cbd13dee7aed1755e9.nq.gz
    ├── 9b94759b51170a0580d28887fd9ad4295823f355.nq.gz
    ├── 9d17dc7f718413a532f15abd4fa6d4f702f38f79.nq.gz
    ├── 9d7cf220f98402e6908795046cd3c124886fc54a.nq.gz
    ├── 9e253ca4fc4cead2d04a0a8843e23b9e08a8394b.nq.gz
    ├── 9ee0ba1216c0d874edda5bbf66c22ad85c10490c.nq.gz
    ├── 9f5f2176f8b13757b76482ecac0d31d703c4ea1e.nq.gz
    ├── 9f623e0021bad8480f902921ff58bed6e46ca179.nq.gz
    ├── 9fcaa52ea9155ff70c49a9bc8e1b4052a1cc7f53.nq.gz
    ├── a018fe28a5abb46b922ff980e352f996120d3de5.nq.gz
    ├── a0b7e7121e55d032bc8f6cbccca40b47600a5c8c.nq.gz
    └── a0f75046efd4b3e84c609a872cf2cbd8c9ca8158.nq.gz

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

[NousResearch/longform-writing-bench](https://github.com/NousResearch/longform-writing-bench)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
