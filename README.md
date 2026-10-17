# Repolex Knowledge Graph of skrub-data/skrub

RDF knowledge graph data for [skrub-data/skrub](https://github.com/skrub-data/skrub), parsed by [repolex](https://repolex.ai).

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
rlex download skrub-data/skrub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e17834a89ead64bdbddf12ab070a923e6948d332
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e17834a89ead64bdbddf12ab070a923e6948d332
│           └── chunk-001.nq.gz
└── blob
    ├── 003b2b3f03c7247520d8f63095fcfd8ff783860a.nq.gz
    ├── 009cfa39d93ae7000ef0d1a2d769220cdca857b3.nq.gz
    ├── 00c13cb4a096fe2f1448d50ca6f88bae953d62dc.nq.gz
    ├── 01476db12cda6aa09c5a9381a83d3b389d033e18.nq.gz
    ├── 0284af572b77d0db49bbcc3a8a975cf04da35dad.nq.gz
    ├── 02e4254378e9785f013be7cc8d94a8229dcbcbb7.nq.gz
    ├── 03662a8bb1ec9669f3caea637763b17419642d9c.nq.gz
    ├── 03f8230fed51fcb6f767ad00510b5c7c4750bbe0.nq.gz
    ├── 0424807c97481177c94abb59cdc92a34048cb02e.nq.gz
    ├── 049d1093f4579b47883baf73232109ae89e5f314.nq.gz
    ├── 04a604b046b0bd71e2895a0c03e4cbee17669ce4.nq.gz
    ├── 06b5bfb3f4c746166ab7770861e5dc41fbce15cc.nq.gz
    ├── 0739a3ca8b790053b200d31dc0324658098fc1e3.nq.gz
    ├── 07442139964c237d1d790d83a18d41fcb44b3e32.nq.gz
    ├── 07bbb1ef3bd0175debcb8a8ce110fca938c5e0c5.nq.gz
    ├── 07db3844afc756deb45f613fefe0ac80449913ca.nq.gz
    ├── 08f49e5a65f556eec2b2cb46693ebba7b44753f5.nq.gz
    ├── 094c3be2ba5e1054da98a570e2f22d642e8f2d3f.nq.gz
    ├── 09c9f75f34e62c49fa9f03e7ad9f4a75290e7fbf.nq.gz
    ├── 0b716a6c56fd167a8c3aafbd2b2c13f4cf883804.nq.gz
    ├── 0be05ffc4c8818e1553dd02ba0c6a85791f5f89b.nq.gz
    ├── 0bea0f8769d7090ae99844c0c103128eb22278f6.nq.gz
    ├── 0e4b8bb139adf0128516729ec97ff35275fb2166.nq.gz
    ├── 0ed2eb94551e9f134065b02c9dd8b347729b6cd6.nq.gz
    ├── 0ed79113fe999e449af86b0de32b52dfa261b355.nq.gz
    ├── 0ee2d69b7f67c436c4be04f1554c1267e2b42d57.nq.gz
    ├── 116dbf7c4a5f6b730f1561065d3edaa6c8f9a720.nq.gz
    ├── 119ab03f7cda1f826e896639924a8612d075d3fc.nq.gz
    ├── 11dc536c3d1b11c7035ba7316e991c429f98a121.nq.gz
    ├── 13600202eee6c276a1c41f3f3897e52b2e2d3941.nq.gz
    ├── 14362b6ceeb9d7d3db08501bef374751b1abdc96.nq.gz
    ├── 149e645d087e9474d6d94743c932ec7ef63af0c3.nq.gz
    ├── 1512bcf92f9eec915f992e4793e8a123fcee2617.nq.gz
    ├── 15989bfe79a8e398ff5d57ed79d2084f51d08457.nq.gz
    ├── 17f3b584311d82272224754fb9a9118f233407cb.nq.gz
    ├── 18d7454359353949be8fb48f7937b6c327afc519.nq.gz
    ├── 196544417fe723dd14e31fd993184b88f245d085.nq.gz
    ├── 198442cc529ca51ccaa991ccce595c19e1dce857.nq.gz
    ├── 19d131df884b10e931ad8a3d14dd13029e305fc7.nq.gz
    ├── 1a065e9babd61473b5c713694774f16b9f306430.nq.gz
    ├── 1a1a7d991bec967bd9f76b8b4064bca4917120b3.nq.gz
    ├── 1b002a58ffeded27a273a79d25b0d6d50f0eefc1.nq.gz
    ├── 1b339ac5119c1e8a03fed76da498d1a40ed0b280.nq.gz
    ├── 1b88b949c0f03cbfc63303f10374e24e58b4ee13.nq.gz
    ├── 1bc3ceaa8bfb2f5f5a9323ef593a514178643d7c.nq.gz
    ├── 1c734b29d0e22660ec45ea1814fee534ff5954bd.nq.gz
    ├── 1d5f24629037ec91477b9f595b0ccf3224ba1806.nq.gz
    ├── 1dacdf501bf6b0e13de09c38845bc5528d524201.nq.gz
    ├── 1e107f52e4702b33a7bed7c76d591f4b14fe36ff.nq.gz
    ├── 1e5004d8d28e4bc10b57f2171fe9383135f5c7f4.nq.gz
    ├── 1f0d843ddbd78d809312f9f5414162ce3aa3cf0a.nq.gz
    ├── 1f26cd21cd6b57d43a38c8241e18e15b8c446c0e.nq.gz
    ├── 203c6959ea6edc1405c8cc60101896c36300c606.nq.gz
    ├── 206b6a3b52c67544da8afa07ab6f4fbea457b8ab.nq.gz
    ├── 2086674699d16e5f9edad485d43fe16daba5b41a.nq.gz
    ├── 23dcf571e4a6470b2a36971fa00d671ada619753.nq.gz
    ├── 243bca26dfa771bfc8cee482f48b04dab3c94ba9.nq.gz
    ├── 24437337bab7201570251c4400c99e12b42b27ad.nq.gz
    ├── 24acbedbcba6c730385422e18f8f9144af74d0ce.nq.gz
    ├── 254d3edce28909e179845f0b07974f956f3079f9.nq.gz
    ├── 2699b5d8e5854bdfd55d05d1f03f80c96fa1718e.nq.gz
    ├── 2711d73f5b2197784295256fc25110e2011d9272.nq.gz
    ├── 275c3554a86324c2e189497e292a0b48b95769b1.nq.gz
    ├── 29cd5d74dc3cde79e4674579ff32110468e8eda2.nq.gz
    ├── 2a2d6cf57df4089d2cbe75365bea5e0341bf8e8b.nq.gz
    ├── 2b030f815376ec9c32952c384b05f146ad972919.nq.gz
    ├── 2b4580677b7dc4e9d7e07b2266e82f820ba09d06.nq.gz
    ├── 2b6276bc8a32af92fe9fccfa6550dfa2d3d4c66f.nq.gz
    ├── 2c60d66ffb5bc5aacf51cee87f05ccddb9a101cc.nq.gz
    ├── 2c6ce503d985ba9c06b922c88bb8a15d1d8aee49.nq.gz
    ├── 2dd5555d99c750f6ed0f2158f739fd0d21edfac8.nq.gz
    ├── 2e0052b48544a5761ee584bb4c997b3fe8b573e6.nq.gz
    ├── 2e54e679f861180d4bc79aa15f205e43e028dc05.nq.gz
    ├── 2ec072a88d9803dd325caeaf05befb38bfee549b.nq.gz
    ├── 2fe5feb6f05886bec6eba33d948e87962a99e61d.nq.gz
    ├── 3119aa008209eec7768bafd686a79d1151e27732.nq.gz
    ├── 3151edea6d22539acd3f93895c51c720200658be.nq.gz
    ├── 3239b6184a670a0d51609ca5618f544f7080cdcc.nq.gz
    ├── 324829fbd702e5dcf70aa09d07a55efc398dc25d.nq.gz
    ├── 35be5b026f7f3868fb0f29d724f36dabe1f909f8.nq.gz
    ├── 36a47fca2b31719d9b374c1f95b7262ea1fd72e7.nq.gz
    ├── 36e3e0571506a94dbbf3968c3fcfd841a966ffcc.nq.gz
    ├── 37526152860aa1ef40d8bc80467affcaf0266b8e.nq.gz
    ├── 37a3cd1fafb8678b1aaf5f36462e37205dff76b9.nq.gz
    ├── 37fde54d06a31fd405030ee576409624d36ae520.nq.gz
    ├── 380c40390bcb93845fb8b17ea7b064c74401dded.nq.gz
    ├── 38874b3a41947cd84bbb03e27c50090541481b55.nq.gz
    ├── 38bac83aabd0a4f5563f89528c5625f9c6d05696.nq.gz
    ├── 39d86e61f4414335db6af171b289c090468348b9.nq.gz
    ├── 3a5470425ca59bff4a8e5f0e70c3ccf16a61bac1.nq.gz
    ├── 3ab73c71739a675d5797e8e6d05c3b3b3c1403ca.nq.gz
    ├── 3b195784bde652d15ac3a330e601ac3cd90b45af.nq.gz
    ├── 3b3de2857a08ea9161a01b7d78eef71472d48e37.nq.gz
    ├── 3b9642d7a0d636daa7be6f54f07ea39b839171aa.nq.gz
    ├── 3c9e9c1f70aedbde8615f8c1631a6fc40547273b.nq.gz
    ├── 3d854cbebe82a5d33648c322e046e461070a7da1.nq.gz
    ├── 3e5f7b661a87944fb43e3e786da3e262553fe634.nq.gz
    ├── 3f76730c3eea87b13b182b3815fac31d090277fe.nq.gz
    ├── 40105b884be2f1fa6731a27aff1e453e35f7cc63.nq.gz
    ├── 40189a8677f1fb457d6cbd77fcef232bae11a169.nq.gz
    ├── 403f70b1ace8eae02149a4d39487be200af2e357.nq.gz
    ├── 41cad45cf9f473e1521fae8c0472cfd375184792.nq.gz
    ├── 4213255f3e6272f491a09f64a14de7ea224705a4.nq.gz
    ├── 42c5123908f7abb07842d2beaae6867ed1efd93a.nq.gz
    ├── 4333452af507542f1d891ca0053f16f84859cdc5.nq.gz
    ├── 44638b76dbd566209863d335f81a96ddd56248e8.nq.gz
    ├── 45acfe9bb6c7eece78a5cd23480b0949686450c7.nq.gz
    ├── 461398b1dd6dda09b558beaba5d79da61beb1ef1.nq.gz
    ├── 46867c3d30d2236b691a0055b3b6fb770be6182a.nq.gz
    ├── 46873abc03256a4cd069eb58532f317fc81a7b51.nq.gz
    ├── 47a73f37e265c39ed5e6c3d200a856be155ec751.nq.gz
    ├── 48638ccf3f39e32aa2454f480ec958761dfd721d.nq.gz
    ├── 4a53c084c53f59746e6532388bffe05a7afb2647.nq.gz
    ├── 4ba65d869a4e8a25b5bdf5ec3b4db5f91097099f.nq.gz
    ├── 4bc1b2b85233831bd867b7d2f1509b55fba15ce5.nq.gz
    ├── 4bc20435738b06e9cb5847ab2054b453dadf6d6c.nq.gz
    ├── 4ce00b8466f489fc3b4a2e569b064eab8ae33500.nq.gz
    ├── 4df4642bba843aba0a0aa7b275040d562a35b2c4.nq.gz
    ├── 4e0865759868af3e124f44e5eb614fe976252f8d.nq.gz
    ├── 4ed5b1767c2ceaeb15a711f858dbaf5ef6ea99e0.nq.gz
    ├── 51ae8641a714582501228b15b224330f7ca16457.nq.gz
    ├── 51c5d7669306b89e5dfc42de727f6b106006d81b.nq.gz
    ├── 528949f42d9e142f1fd4b1c0e7dba074bba91ba2.nq.gz
    ├── 5301632f7f3e583e0f0b3796c8a5e5e0ea0a8905.nq.gz
    ├── 53b6ad8c4ef83544336a3eb0d371f23fd2d39d70.nq.gz
    ├── 5569d05bd2383ad476956fd88fff39ba1b5ed3c4.nq.gz
    ├── 55d3b81b763218e3170135fb28d3f17ac95d3626.nq.gz
    ├── 567f815f7b2c9611c60d3b0db81e95fed082ccba.nq.gz
    ├── 5761fa8070d0f00601d1537a5f5f8260f19d6e89.nq.gz
    ├── 5823a72cbd268e50dd1d1c83c23c8b8fddca187f.nq.gz
    ├── 5c8efde295695f1f2d6882388b30661df9901145.nq.gz
    ├── 5d21329763cbdece2bf25f92bf0bc7ca2040f833.nq.gz
    ├── 5e0143e008624770a71063f9092a3be5e787e533.nq.gz
    ├── 5eaf5b70060762d1b2cec63461eb4c158f00b7b3.nq.gz
    ├── 5ed4a2c520545c5d6f85e61f218db7202dd25136.nq.gz
    ├── 6008fce8eb069e62df9cf4fa3d558c74922c0807.nq.gz
    ├── 6188d4f85b228367af1c4fb3d77d5b2af451127d.nq.gz
    ├── 6238f07d8d04daf095504f79f2cfdeee4e6a8a4f.nq.gz
    ├── 657f06b49e585d8d3fee1fb975a333db2513824d.nq.gz
    ├── 65ec9ca3006dca2f1b05ae2512ae7e3c7ff49c84.nq.gz
    ├── 688f204495ad00c900f21e4fef5397c29b04eed1.nq.gz
    ├── 695142451255fcda9e5aec8e8c73d0504683753e.nq.gz
    ├── 69d5e5c7ebf4af162f1d9dfc285dc0376a14caeb.nq.gz
    ├── 6a5f9b4ac5aa1e79f2cfb90a346d897afe03fd44.nq.gz
    ├── 6a963576c37f2364e117095eda908e8490a6ebe3.nq.gz
    ├── 6b94ce752067b38fe78fba796b689fca29687065.nq.gz
    ├── 6c37df81a3ee397b5a7a2063404cf3eac459109f.nq.gz
    ├── 6d5b7684b6d69ab710ed8b89b006453df99e8d2c.nq.gz
    ├── 6d61f967446be705a771d207fcd87929fedc1b99.nq.gz
    ├── 6dcd014d625d5e98a5da9779c4ad9325e169932b.nq.gz
    ├── 6dfa92de7d1f07436a2426daf6ca4f40906e1b02.nq.gz
    ├── 6efd2d15a2255de84362b1c37d62832f74f74f16.nq.gz
    ├── 6fb496261b1ae16c8102cd11721f995c4044ecc8.nq.gz
    ├── 6fde89c374594f41e800753bdf1de251ba5627bf.nq.gz
    ├── 7007bfc97c08904ed8ba4a69cfcc294181b9e047.nq.gz
    ├── 71a666ab2d377e8f816f88e6538c88c5848f8d5c.nq.gz
    ├── 72309c4d4af2be0801f969f3b5c3250dde1cb602.nq.gz
    ├── 72c12b34a5907a5f92847ff8123c526e043f82f9.nq.gz
    ├── 7362e739b8f87dd077e347a106be4681b9a8243c.nq.gz
    ├── 739c86eb70506ecb1918f24c414896acdd5952ee.nq.gz
    ├── 73c5b2a85963ffb23fb961938eccc5b314b30f2e.nq.gz
    ├── 744e2fdb45d31a3fc730de8f9ca0fa00f2230341.nq.gz
    ├── 746ab5ce447eb242883a54d707afb50cbe7fa122.nq.gz
    ├── 748c15525e958bb0fa3ed0d778cc92eb211fc415.nq.gz
    ├── 75df623a6932a67b9c2b8b90863fcd4909823abe.nq.gz
    ├── 76cb8cbb975011cb8b6dab972a8f8a0fa99695c7.nq.gz
    ├── 76e2297799e331a6d409e926400925e347e09f8b.nq.gz
    ├── 781af747f0d6c16f8a5fa3794d2e44167b3b9e73.nq.gz
    ├── 7a4156f01ee96e6d3963ce7e550d1627c31d3312.nq.gz
    ├── 7ab0ab1c2886c3cb2ecbd7152b9938fed7e3d322.nq.gz
    ├── 7bc4fff387e3d08fb53cdb4edf098a0bd1084898.nq.gz
    ├── 7bc5160f06c0b7505339a01cda95b0ad40417022.nq.gz
    ├── 7d9d8afebcad880948a2645b30f4e4fdda26e1d4.nq.gz
    ├── 7db87bce73b9597af3e7da0813e6810d51c98d71.nq.gz
    ├── 7dca291924afb0592b3c1b42a580acc5f19a0b98.nq.gz
    ├── 7ee73a35821d9a3c6786fd9491b7f32b9ef019ef.nq.gz
    ├── 7eeecd171fbf7cc21f5f7a28f9a0b9793c96eb7f.nq.gz
    ├── 807e963a0fa40151d02cf3a2ee04e7974c7e5abe.nq.gz
    ├── 823ba7641b1e192eaa68fcc65586ac3eedab97df.nq.gz
    ├── 8280785df294f70761f494fb321f96ea2c48cbad.nq.gz
    ├── 82d8df29c2cb7070f9152de75ecbc77302533adc.nq.gz
    ├── 82f57c297a923acfdc8500729b5664006619f992.nq.gz
    ├── 8321ebc3cbc1747fd2448765e62c7652e7c4b69a.nq.gz
    ├── 833f2452bdb283f003bc19c012188ed1827b3974.nq.gz
    ├── 8392cc2791001d25cdb9a74ea029f7de9c0da339.nq.gz
    ├── 83c22c8c6da82eb3b0a125bbb034efc00c93de78.nq.gz
    ├── 83f5edd8232bbef8a812cf6c1935905bb19415ef.nq.gz
    ├── 85058c15c51ed7f55444999c6aeac694805c71e2.nq.gz
    ├── 85e53eb49622c7f6771586fe1405ddf90fdb1d45.nq.gz
    ├── 865b2bc81442b65b9f45c8a8ca10639ed704f074.nq.gz
    ├── 8762e69e831c43cc2794bb28c9f5b85e318529d8.nq.gz
    ├── 89fcba564b0510fb788a89193ecc9b3a1018b5d8.nq.gz
    ├── 8b66f9f6a6e565eee0d321da5ed5a36491bb0826.nq.gz
    ├── 8be051b973b7f650f05ebc47a653565913a2f29f.nq.gz
    ├── 8c005bcfac303166ff6f9218f908e972559f7753.nq.gz
    ├── 8c5ee54ccd935aa60b77f94088776557672f9fdf.nq.gz
    ├── 8f50b07185eaae83d93a7f57a117f859ff24ac12.nq.gz
    └── 8f943f060072054871855623c84c9d0d1788bcf5.nq.gz

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

[skrub-data/skrub](https://github.com/skrub-data/skrub)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
