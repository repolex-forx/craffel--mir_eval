# Repolex Knowledge Graph of craffel/mir_eval

RDF knowledge graph data for [craffel/mir_eval](https://github.com/craffel/mir_eval), parsed by [repolex](https://repolex.ai).

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
rlex download craffel/mir_eval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe73b3533737814f83dbd9739f06e90f5f82f758
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fe73b3533737814f83dbd9739f06e90f5f82f758
│           └── chunk-001.nq.gz
└── blob
    ├── 0026ef35488c1de4dad27432410ea8c9bee851ea.nq.gz
    ├── 0047a5583300b752217e8b4be7586354fc78f0ef.nq.gz
    ├── 004fdc7935a0078e4f4aa27866b36fe1c5468bdf.nq.gz
    ├── 021c5c0a97fdfc00a86b738e002546d5aee29ab3.nq.gz
    ├── 0252933fe9564cbae7d40eabd51d4a5caf03b763.nq.gz
    ├── 028020d0f1199e4324988913b5dd6d58a68c88f2.nq.gz
    ├── 02dd0b5c2a49ebecc9c18fbcb04f80854eb92a2a.nq.gz
    ├── 032163c948ca6d0f84656a2af0dcae7b88a1b107.nq.gz
    ├── 0364bdd3a72de3d6289216c798b4320e01a62afd.nq.gz
    ├── 04f00579c6acf8acaa9eb5ccd21a66ec38f8cf50.nq.gz
    ├── 04f6d232ec7930715f0327f7cf6e3867da2fae8c.nq.gz
    ├── 055d03f45ec694dc01d90b7db88d19e77db20335.nq.gz
    ├── 0563a97c41574e781acb08070795b1376ae60c0c.nq.gz
    ├── 0570d5908270e30dc44506219f40e5bbc26899b3.nq.gz
    ├── 068101680792465f00defdca9b39276f664cd760.nq.gz
    ├── 0bfdd1d3385fd5a6bc45a270162657f8fbcaa480.nq.gz
    ├── 0c15c2d3fea0427e56ddb06de8457f6828d3c9d0.nq.gz
    ├── 0c387302f65408aa9f4f736892864270166571ae.nq.gz
    ├── 0d0abd524fdcdf5309b40aa9e7a1d2eeb96d42c8.nq.gz
    ├── 0d4f47fed3a7be8ee7950b8d40a5fd30d35579f1.nq.gz
    ├── 0e62a42c3f7fca1744a842042a2705efba513d74.nq.gz
    ├── 0ea00b9c3e1bde83f0245a6f68214fadf9aa79f6.nq.gz
    ├── 0ed7f0dee059cdae3ce1059006c1e1cd0a0c6d55.nq.gz
    ├── 0f19eea6ab984f364293da5fa8f1986dcfee2516.nq.gz
    ├── 0fc0b8e9d91655a8663c9d9526eb418c34ab7470.nq.gz
    ├── 0fd017d88cfdd0d9ec3f893a9c11975a6a1453a9.nq.gz
    ├── 107182b2008a776242fbf955cc7e61ea9ccb2fe9.nq.gz
    ├── 10b73cfabd970a74b1768c71dada352d97527b8d.nq.gz
    ├── 11afea70d12452d75fe1305cb2b1f8dcea6ea079.nq.gz
    ├── 123b90a8fc3032cbab698d2b485220d7c6ac168b.nq.gz
    ├── 132f59d538b1c2f78400f22de6791b2d2f461ba3.nq.gz
    ├── 13778e46fd62e1cac88334ddb164a7b182ecc07a.nq.gz
    ├── 1498ef8e5e67a1e99e5c5516aa90bd96105fa7e6.nq.gz
    ├── 14f1b85ba0b13d8e2ddbdf4dc5c53b2253ab9956.nq.gz
    ├── 15012b1494cfd66cb3702fcb83318507683d5ed2.nq.gz
    ├── 153561b6eb5957b5e606a346ab2cf082f3f96177.nq.gz
    ├── 16eb9f3cc245dea37c995b470d44a5509c515d55.nq.gz
    ├── 18d5429eb67c7bcb5eadd1b0fd874cefca2d8505.nq.gz
    ├── 19547f812e3b1b344b62c04a930b6972fa7074d9.nq.gz
    ├── 19eb38b5f2740db9010d77bdbe1a60ff1b03fad6.nq.gz
    ├── 1a4c56f3c0c59bb43f3010aea097a84d310ea9ab.nq.gz
    ├── 1a8aa806fde766b37d210beed39c0c89d48636c9.nq.gz
    ├── 1a950bb2a9f2d58cab48bf2d36ee55fba5524c92.nq.gz
    ├── 1b3124e96c4005c5cbee96727954de79f0ba5d01.nq.gz
    ├── 1be39f3cc356283763d4e08259aabb4baf46d3ff.nq.gz
    ├── 1bf9301b164bd10083deba4ea1c809293770b6b0.nq.gz
    ├── 1c4949c10b77372fa682d6bf16be5422b13e7962.nq.gz
    ├── 1e3e144885b7f11f31a81983bbaa7057fc00b4e8.nq.gz
    ├── 1f508691d75ebce50924efe1fb7e0ee81b77de25.nq.gz
    ├── 208f189ff75dbfbde301210e65df03b3e9b986df.nq.gz
    ├── 20b098a32efe493825a156e43d2db72c50c8842e.nq.gz
    ├── 20d901f7811bf01d888b310f8231f85760cca971.nq.gz
    ├── 214068d325c543cb706824e6db27a7d2bbd26c4d.nq.gz
    ├── 21ad648b56a464e5b3f04d20a685653f4d0eedde.nq.gz
    ├── 22179c6c8bad89a00e0961cf5255bdea6f6feac7.nq.gz
    ├── 225cb4220c74bd7d16d4604717d9646b5317f13f.nq.gz
    ├── 22de727533b259075fd453b1f87b191ee304bc4e.nq.gz
    ├── 2303553f8d86c01e9832fbb2017db8a56cd29654.nq.gz
    ├── 242229f7ad550fc072074e13ce64d50ed693ffac.nq.gz
    ├── 2590ddc8bf0463787d595267a33cb2d0193e8e28.nq.gz
    ├── 25b549e0c14c6c819bb6ff0b20247c3d40c5f608.nq.gz
    ├── 2618541f3126b81f6e9bbf1806325c3338e0a076.nq.gz
    ├── 26b7a07ec1a1967caa7cd82f89b1da3c3b55534c.nq.gz
    ├── 26ccf341632cbf2a26c8fd7ea5e3a65f43c83e07.nq.gz
    ├── 26da4f5385d9f091d55ccf5ab37040b98fc152a0.nq.gz
    ├── 26df134a3f8511ac8050b8ac8f8e95074707e206.nq.gz
    ├── 26f0d77788b4db99bb7d1863f1855b65eebcecad.nq.gz
    ├── 272afae8b7b3a87cab7b9e5d0518772a0eb2a69f.nq.gz
    ├── 27da63f938199c58e7e37246c923ac437776aed4.nq.gz
    ├── 2807dad2f0b740ab71053efca7eec999e58c4314.nq.gz
    ├── 280bd654e424105c7a79cea6fdf7e89d0349e902.nq.gz
    ├── 285fbb22e33f81c72bfd8c215d74c10fbbb92484.nq.gz
    ├── 286122e3e23874134fddd9a56256deb447a63e92.nq.gz
    ├── 28be0b932cd210953c5c726c578a484cccad24ec.nq.gz
    ├── 28e2edde05496c8565548201a7482e1e977fdd84.nq.gz
    ├── 29693fb6015f07dab7ad3d25febe2d0099e71c76.nq.gz
    ├── 2a1cade46eeb70c39220e5961240be231e57e5b6.nq.gz
    ├── 2a6004ac8bdd5b5d0fdb58cee133e4af2c92901e.nq.gz
    ├── 2b3bc39bb9b4fd7e40599bae7ea0586638ef6ab5.nq.gz
    ├── 2bf70768506bd59f72b3bb04739423e7d68f0e92.nq.gz
    ├── 2c46b8db90a8cb16c12b1b2b2609e603acb86e3f.nq.gz
    ├── 2c49d2b2349e26060014a09da5a9e5b1a1042b38.nq.gz
    ├── 2cc92aab6fee7c5c6bd0f8782d21b3a10eb1667c.nq.gz
    ├── 2ce6ae9b80dc341ac125394483e633107cb18c9a.nq.gz
    ├── 2d65470f278daf2653c7afa1b710763adb564fa7.nq.gz
    ├── 2de4e10c75d1380ebb204cf607ef31232b08a855.nq.gz
    ├── 2e9c01fbf918c978d4ab27f196d6afe82b850157.nq.gz
    ├── 2ef1c12768cc2a81a342dca538a9be32665cb819.nq.gz
    ├── 2ffad07530c77b9a8e6871f8755a2af15345cd5d.nq.gz
    ├── 3012c08e16fc5500a5df0b22bd098ef318217f56.nq.gz
    ├── 3035166a94160e679472c23139e26d9998036cd0.nq.gz
    ├── 3039b3cbd10d776f065b0f573d38018c12595aa3.nq.gz
    ├── 31fbdc2468c6ddf8c19bd8149ff0ba6811a7d23d.nq.gz
    ├── 32adeb80a59f24f69319dd28b586420e31d03e14.nq.gz
    ├── 32bd3027c539b93303cbdf3b0f09320f6cc31da4.nq.gz
    ├── 32bf573929fef5010f14cff1cab9359b0e275036.nq.gz
    ├── 32c113979c82e0909051b81d9c38f21becdabe96.nq.gz
    ├── 336934f3b60050252db232d1b2b1b47b0b255192.nq.gz
    ├── 3380188e3b5fda214355a885daa43a400a46cc6d.nq.gz
    ├── 345a802a032521477f4e5f0374875a4bb9a5f666.nq.gz
    ├── 349cbdee788c4f0d1da95b0567cd43325e57ba3d.nq.gz
    ├── 34e9f89bfac2f53c3634a4db26534192239bf65d.nq.gz
    ├── 354c63dbd5c873cfce5f54c94d3942df6ae24756.nq.gz
    ├── 36485cadd7b49de2843ffeea53f7d2ac20895122.nq.gz
    ├── 36b1e1c0cad8882bd9651ffa80cf8860085168aa.nq.gz
    ├── 36eba7f9130a73afa8454a6e901029a78b5c2b3f.nq.gz
    ├── 39ca623010fc7c0809ae5b90a2b12643393e23ae.nq.gz
    ├── 39f8bb362935ecc2a394b7bed6ca1d275b891025.nq.gz
    ├── 3a0da963b0776ce21405774dc7d45352b4e3712c.nq.gz
    ├── 3a68a8b119b0ddf5d06c4d3f981a175be891db42.nq.gz
    ├── 3b0a4cd516e4c9dcaa1ced2e7878fa7e751e461d.nq.gz
    ├── 3b3da48be11abd4ec041022684d1380ddfa9f371.nq.gz
    ├── 3d0ede7e4eb26d5346504d63c9cbea43c657d309.nq.gz
    ├── 3d43a541121039e780650965971002f834a7d7b1.nq.gz
    ├── 3e1cd5fab2820323e78476249b01d2022fb6952d.nq.gz
    ├── 3eb184f16a559e6a2f0761d1df789903a30f54d1.nq.gz
    ├── 3fe9266d28106b529d3de6fa7b3079c8148595aa.nq.gz
    ├── 4008e73c7a608f558fabda57bb62d871120c84f9.nq.gz
    ├── 4020bd1c110dbcac6e1a7e01886647671d934907.nq.gz
    ├── 408d2ca0defb9309878b3b590e95a741ad12a3a2.nq.gz
    ├── 40963e187b73c71e117d8cf7d491fff1c70b87fb.nq.gz
    ├── 40d2e7c0d6678dda163ce743d6e89b2d4effc170.nq.gz
    ├── 4142de5316b8706ecd5b81e4c90d2b024e9135d1.nq.gz
    ├── 41a2384f1114a110fc367ab0d7530b6c08d8a4c1.nq.gz
    ├── 42632f2c4b1f36422c992a7102a748c4d1a9598a.nq.gz
    ├── 4264c7eeb395cc52ba300677a2b23fe71f932c48.nq.gz
    ├── 42e55b3b99e45c8fafaaf27e2147222e5a282434.nq.gz
    ├── 444b346ec5b2e5b57b19500e91b20de0dba9a814.nq.gz
    ├── 44c27f5c87c1989eae714454b7a73cdbb67bf23f.nq.gz
    ├── 44f78fdcf2cc51b5179bed6fe2011cee5b4a454d.nq.gz
    ├── 45bdc7c6e224aa5b139df9b29651c5ec19143502.nq.gz
    ├── 4618370de4a745320003efc5bffcd717ae0bcb8e.nq.gz
    ├── 466c6c0cd6edc88a57f459c287bdae1f1918cb73.nq.gz
    ├── 474a7debb5372b233bdcdda0e013658942e487a6.nq.gz
    ├── 48005966eb7c2c2730021a7fb7a6cea2d27735d4.nq.gz
    ├── 48bbec851db7a636a44c11ecc30f86f4d5ee4b0c.nq.gz
    ├── 48f44dafa283d87612fc94b0dcbd9270ce0727f1.nq.gz
    ├── 49060115fb64c23130990754c7010e0edef3c9b8.nq.gz
    ├── 49224c74036f05555ce5cadebdebf06e03ab9808.nq.gz
    ├── 49cbf472cb59a6362a9f29861a93f181beaea030.nq.gz
    ├── 49e393487da3455f7b1d55b87bfaec02df34a147.nq.gz
    ├── 4a02b98de1d89f0c2f35ae9d85463f6c78e455c8.nq.gz
    ├── 4a0a76cb336a0a448c3748c8a518288da485f20d.nq.gz
    ├── 4bb48f98249c9802e06f21705df9472f8243fa96.nq.gz
    ├── 4db957872287fbb30ea171501183d56d5eb54f92.nq.gz
    ├── 4dfd6ca9d60cb72aeabe381d1ca7ffe74c2ec216.nq.gz
    ├── 4f4e8c55728a2ae006eb8f3d5b54ef7cf60f5850.nq.gz
    ├── 4fbe91cda113fba3a2c5e30baa73a75ec51833a6.nq.gz
    ├── 4fcd4a6968bc681f197cebd0f2bf241f4da3c6f0.nq.gz
    ├── 50448b81627f0d61c6d80a3208e2879fee838dba.nq.gz
    ├── 51fc78b4b193faed0d8617afd7faac1f3735f7b3.nq.gz
    ├── 5207e262e9ade1b5445d83235e6c2dc99bfaf10f.nq.gz
    ├── 52f55f11d5a2c2eec41ea7ce7d0bab42e1bd3450.nq.gz
    ├── 5339f49863527b8e0797a3b5ea6e7f643f4814b0.nq.gz
    ├── 54239ceca1559d74dce4ba395c227d5e7ed1791d.nq.gz
    ├── 543604021331c751b19a1dc8aed6f3bef4ed77b4.nq.gz
    ├── 55265a73eb568e30f3cef5cfa39f55eec400fd75.nq.gz
    ├── 56411f491cef586f11eff8529f7f3413bcf112e1.nq.gz
    ├── 567f3a0b3a7ecc667c4afd67ac604a04884c50eb.nq.gz
    ├── 56aa851fd5f045e946a49337fc261ddef03fa69d.nq.gz
    ├── 578c7dce4367d9ad575cd1eaa7d6c31ee955b7be.nq.gz
    ├── 57e7b4786bf5700e948e32507479a2bb62314f11.nq.gz
    ├── 57ff2d679f02c5b2088fad77c84cb65d4b60c852.nq.gz
    ├── 5808fcf4c54980e1d6f34cea6d4cdede2f66df81.nq.gz
    ├── 585c0187419e9e8b9a9f17ff98aa36e9f13a45b4.nq.gz
    ├── 5abccf3b204d48e8de8a148986cff641a4f1ad34.nq.gz
    ├── 5af333b1038632b8d7a8440e756ea1928e584ac0.nq.gz
    ├── 5af4b6b7600bbb82c90fd7c262b5c84becffd48c.nq.gz
    ├── 5b7f9413312b481b766f8f3665d45d100e0556d1.nq.gz
    ├── 5bff7dfe41452eff1d1138d6b5ecf1f6952a100b.nq.gz
    ├── 5cf177503f7164aea5ec0eb220681e690729d28b.nq.gz
    ├── 5eea5b22679d648586872a470d457c5d8987a599.nq.gz
    ├── 616f0be6bde61906da2866d93d2f5d7cc3668d42.nq.gz
    ├── 61c91ec789637e57773497a7c294f749283cd994.nq.gz
    ├── 61d6791c2a06df0b084616b5da49454d02811eca.nq.gz
    ├── 62637257851a420f880ff0fc944ddd729aff0fe8.nq.gz
    ├── 6263b9f6d64e43e1a13b8563403b2e9207baa198.nq.gz
    ├── 63f3972c3fb237dff35541d43603f3c0820bd938.nq.gz
    ├── 66076a6a75f0ac6a9bf291160cc5f10a03b1a980.nq.gz
    ├── 660db24612690a20e37e586248a83e023a8ebc80.nq.gz
    ├── 66db10a01be072af4897f7bff1ad3ea606bd9eb0.nq.gz
    ├── 67206ed5ac0067200d3a815625e5ff2defde0e6f.nq.gz
    ├── 674d37beecaa623351826d5544727c4c794182ba.nq.gz
    ├── 6783f422867072927fe165fe9949ee88a939d7ed.nq.gz
    ├── 6842830331dd1c9bb7e64a64d77ee8074249b5dd.nq.gz
    ├── 687b74d3558196beb8c7e494c3c5257aa812e569.nq.gz
    ├── 68bf1fcc0d0e18f6681a4c64f907a16c3546a31c.nq.gz
    ├── 68d7e16756849affbcb1235df7a6d0798ae347e4.nq.gz
    ├── 6929c411e94ac8f7b2921bd3adedea873e69a762.nq.gz
    ├── 698f0298626786f58228030e91c5f2326970e993.nq.gz
    ├── 6a8070c91d0a51a62c76b06bdbd42803971a8874.nq.gz
    ├── 6ab07b78d5bbf84efe535ca06f0d7120200063d6.nq.gz
    ├── 6ba0998cf51b350da8b2e829c08ff823b54007e6.nq.gz
    ├── 6be0024f45f1ddde427c14056d9cfe4ece3e27e6.nq.gz
    ├── 6c1b76878bc6843a790a83f657789f4dd2baf528.nq.gz
    ├── 6c2c0a4cc5b384b6cd90411b938f625c5ff531b5.nq.gz
    ├── 6c87caa7092c89758af28b21e8e1321652778ac6.nq.gz
    └── 6dfd4a29a0eb21dcc3df7e7b6d9f2426ca017333.nq.gz

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

[craffel/mir_eval](https://github.com/craffel/mir_eval)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
