# Repolex Knowledge Graph of ansible-collections/junipernetworks.junos

RDF knowledge graph data for [ansible-collections/junipernetworks.junos](https://github.com/ansible-collections/junipernetworks.junos), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/junipernetworks.junos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 440c1dc9a617acca4676a5abf56a3779610a28e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 440c1dc9a617acca4676a5abf56a3779610a28e5
│           └── chunk-001.nq.gz
└── blob
    ├── 015c05ad87fb684de5512b89287c708774adbbc4.nq.gz
    ├── 01d8294e2219c944dd59e43bfe2e0cc154b5c7d5.nq.gz
    ├── 01e0c4b235f4d21f3563d4040b23f90993453d4b.nq.gz
    ├── 023c180154c0f3124253978f0397c62f7000236e.nq.gz
    ├── 0277401f237473d15756168b3a165f9a365595b7.nq.gz
    ├── 03be69242da7cef859cfa70dbc358720e819ee9f.nq.gz
    ├── 04e98a0a6f888555c18d4054f0e41149b7c82ff6.nq.gz
    ├── 04f65df964ce887a2f9f70ba4a32df36741ee342.nq.gz
    ├── 052a54b065fd78293afd1a583d6c6487205002a6.nq.gz
    ├── 05650bfa704d296f3effd995123ee602edcfb2b2.nq.gz
    ├── 05765490ed2380bf6237311e9689878444bf4082.nq.gz
    ├── 05e8b095fb67de2345198bc190bc71e82fc866b5.nq.gz
    ├── 0637e8c1630c8d34894b7025ec5442ae050133fc.nq.gz
    ├── 06d61143e1751cb33d598dad716249cd8b962c1a.nq.gz
    ├── 070a5775423e3c6e84466d3c3092cf8f6677e87e.nq.gz
    ├── 07575c600e50ec996627d251bf1c1df2800c07cf.nq.gz
    ├── 07f09dce8c922d30141edccf1251a842b3d989fe.nq.gz
    ├── 086dda3a2f0265f648e5f30106d541411b12310e.nq.gz
    ├── 08e14d1b8bcdad7ead62075635129d77dda52886.nq.gz
    ├── 08e3f90483fe4fc1927a28e294f3cf6fa9a8fbf1.nq.gz
    ├── 09a36550d54b980856f65fc99a2f51b2b5327efb.nq.gz
    ├── 0a1c50b1cf9c78daeb9b2e0781b09fbb13ddd2c4.nq.gz
    ├── 0a5d41ae0b4de6321b01c6677b8b8052ffa8ac3b.nq.gz
    ├── 0aaeb963d2bfe28031cdb912f97ad725c114ff95.nq.gz
    ├── 0b38587b01d1f42853cf76c1a353481ca818c734.nq.gz
    ├── 0bc72b4d1f52d3a523535b7e0751fe409221e148.nq.gz
    ├── 0c08a7ced963454cda4845b762d638886cc79eb6.nq.gz
    ├── 0c32f602dbc167bf4e8892bbfdb22a64b11996f8.nq.gz
    ├── 0e2b286ec7f6990149d8e972c1bf59a1be75270f.nq.gz
    ├── 0ec7941f378c6aa20dc1a02464631e01884180bf.nq.gz
    ├── 0ef2c23475f61229347f2dd2ce08492f1f687223.nq.gz
    ├── 0fab60f99ab22d911e3f37d89570506453388f95.nq.gz
    ├── 0fc53edcdc104efa7c05685b3648ba21472a1aa9.nq.gz
    ├── 10ad6080c96861cee643f5f498b9d246d91f9a6b.nq.gz
    ├── 11176a31889bb77fa75de1faf503eca2ee24cbe6.nq.gz
    ├── 115a5d076d16bcce604ab7543d0e3a2effc49d93.nq.gz
    ├── 119519a68d56fd5000ecceef9b051d45473f1183.nq.gz
    ├── 11b82c1a497a3afeb406b02b0434ef473d3c5940.nq.gz
    ├── 12933198e115c58539b3509ad8ce9770059d12dd.nq.gz
    ├── 13509652638ed4caa9709a30a54cb8ccc7c7d2ac.nq.gz
    ├── 13cb325c5e43224fae57c3079017b4cc56b0b3e8.nq.gz
    ├── 13d4c19547d145f0a86260c781250147f791e4a3.nq.gz
    ├── 150c6d9af19c68186f97484d87bf826181bb1841.nq.gz
    ├── 154ea4f508e3727747b43ac5eb958879ca74ae62.nq.gz
    ├── 160500f9cf36a30a4008ac6f013ca9cc15cb593b.nq.gz
    ├── 160a8ba3b1693cc877482ee94eda34fdacc062bc.nq.gz
    ├── 164afead284de6add13c8f514561691b2f1c8dba.nq.gz
    ├── 179fb0d954ff57793f01c3f25a331d904e9595d7.nq.gz
    ├── 18712c3233194852c54f91e027126bfb16d93d7c.nq.gz
    ├── 18c9d6f8c49bb984b250b251099fccf2092de427.nq.gz
    ├── 18e04ea6bd7cf64c7b373aa792aa86b91e819e37.nq.gz
    ├── 18fec21b7721b50726fa61320ea5868587608f06.nq.gz
    ├── 1934b1c5fcb841d5cb048dde7545c122881a7cc9.nq.gz
    ├── 19cbe091aeeec53b8708a2096d63237501355a12.nq.gz
    ├── 1b4202ea376cd8bd0cb8fc40bd7d7268fcf2ae99.nq.gz
    ├── 1b7edef2799cbedbf88ede7b47bf557c9a709a67.nq.gz
    ├── 1bdacb6f66cb11a3cdaf5b047b5c27586e1f1f2a.nq.gz
    ├── 1d66a9759ebf8b24703bf27f2a9571a92cf741e0.nq.gz
    ├── 1de305498f008b081c873bc77418a89d0c72c3f6.nq.gz
    ├── 1e2aab47208001d98ecb3655ec339bb9fc339a89.nq.gz
    ├── 1e6830e0011cbbf5ff219495c0507b4c06b7e785.nq.gz
    ├── 1fc72a4903cddb6a7d6929a7fa9529c77ed75620.nq.gz
    ├── 2048506fb8436516fc2c33337455b71cbba74d4f.nq.gz
    ├── 204b3b7b2ecd132f2edd9cdd356d22d6cbe671bd.nq.gz
    ├── 209a7acf76b77974fc4d15066995208e552354b6.nq.gz
    ├── 228875575c5b0dbd177e9b1db62e948cbba78cbf.nq.gz
    ├── 22eb2b14cbc9244e3e620696969be3a19fe62644.nq.gz
    ├── 2448e1cd2b8f398c79a0ba41c9d4969d0a70e9a5.nq.gz
    ├── 24a163053a6f2c538e25ded465bb30b989d31e2b.nq.gz
    ├── 24bc9e1d10edde850c6d9494e8cdc1ea4fd970a2.nq.gz
    ├── 25e75c370d117db5d5a8a0651c070edee4ce0cfd.nq.gz
    ├── 25f39e7a5784e90f58ae4c82eaa330457aca64fa.nq.gz
    ├── 262827459d6f8e039a773e22d9bb68cfacf3c909.nq.gz
    ├── 266d15b387849ab158c3aa1be6270390a390d7d1.nq.gz
    ├── 26836a7c47743c87e99c03352f02dd86532eb05e.nq.gz
    ├── 26c5903b8a466bae94dc7896e90e3ad2cbdad9a3.nq.gz
    ├── 26d323fccc7e428a4a0c3070685c098f7930b8d6.nq.gz
    ├── 26d6e8ee03d0944c313137588fa299a897a56ba2.nq.gz
    ├── 26f57fa4a1ad60f85e19d4545db67806d6b9cb78.nq.gz
    ├── 280b43ff51607324f4140214ed425b2aae0ccd75.nq.gz
    ├── 286793b8c8109651e5f95c01366dc0a3a54edda7.nq.gz
    ├── 28735efbfc49064972d5c5295aa1d62ac957c934.nq.gz
    ├── 28e9a7d8980391ad9537fd4f392abd3c3f097a2e.nq.gz
    ├── 2915e007114012b0e4bdb81ae738cc1e795b92c2.nq.gz
    ├── 2a171419acd74fb3e92909d6cebb111c03a3e545.nq.gz
    ├── 2a8323319b55ead9ca183d97a2731713f271f6fb.nq.gz
    ├── 2aa32655dbe2670d94679eb61ada73cb650fcc13.nq.gz
    ├── 2afd923396c2a523b9a575ab611774c6e4baa225.nq.gz
    ├── 2b814d639be1c10111d6376e79f2b53aefed3f32.nq.gz
    ├── 2bca3aea4a25c595029941f93def0b7dbc649d86.nq.gz
    ├── 2bd1f7346e04c8fe21bf2d17c3e5ee45b0765795.nq.gz
    ├── 2d4c4b63df855e93a22bd73291d9e58fa54b7287.nq.gz
    ├── 2e901f215c0d28bad88d89dddf35581f23877507.nq.gz
    ├── 2eec2f58d81f7d562ec4cc7f8f5a3415db7180bd.nq.gz
    ├── 2f89ac2b32f0946ef29b0f6b775b6835baf9613f.nq.gz
    ├── 3065f768fe850341fcc71ae1a813c7ffd9736d38.nq.gz
    ├── 309e0d573848c80fdf3a75714d2c548516f462e8.nq.gz
    ├── 30ba201b9dc12672eff530ef5dbea7e972637aba.nq.gz
    ├── 30f80913f392957e5f3e817dfd4398243eb262e9.nq.gz
    ├── 31849facf8e3bef29cbd92a66c79cb078c4277ff.nq.gz
    ├── 31b72d419c906949982f7308ec32ff5e14103313.nq.gz
    ├── 32129d3f5d65d32b3aac23f02a64c66cd37d6888.nq.gz
    ├── 3213b8b6461cc5cd86dfd711e450371829a404d0.nq.gz
    ├── 3243ad57e4047591b53610a2553bfd642863d50e.nq.gz
    ├── 3318258e64e8b14800434bf005e2c0a5c79b00ae.nq.gz
    ├── 3341f8f250d8ef7f6bba2869db9470eb17eeb217.nq.gz
    ├── 34b9be83f8e25a6bdb72f313aff208722e45754c.nq.gz
    ├── 34c01e8a52a8f38da56d214c6be6d118731c564c.nq.gz
    ├── 34e35428e7dc0f2698fd7ba5fe76bb2c2c6a7c0a.nq.gz
    ├── 34fc141cb8768bcab39ea7d88ed49d09caf3e139.nq.gz
    ├── 35996ebffa8a4c4483f17d28bb6566ceb98a87cf.nq.gz
    ├── 365df590b73f5aaf8d414783aac85b1b836a12ad.nq.gz
    ├── 36c3ef921e870f052e3a2c91b6871b0674ec0976.nq.gz
    ├── 375d0fd57f61e8df33c07b19c68b2597798759ba.nq.gz
    ├── 383e7d87d538911c1259e244914400f3617d8292.nq.gz
    ├── 384e92a21255cb9738c3a996a8b01b128bc3db74.nq.gz
    ├── 396789aed6b9811bfc51eeae7fb5f8074c231616.nq.gz
    ├── 39d35db293eb54e695815e04ecf32fd5efdd05d3.nq.gz
    ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
    ├── 3bfd2f37f70f59a519024ea321841440d9f74864.nq.gz
    ├── 3c28c6418d4d276b126ca2ce063d427093d1d118.nq.gz
    ├── 3c701d9cae2f7ab1f8f50fef649f5b289767aadb.nq.gz
    ├── 3d4f364eb70901c8db4efad607f0a621482b0d98.nq.gz
    ├── 3db81d09871711e9427cdc3cf0d26c5c753059f6.nq.gz
    ├── 3e19d1de21d144acd0245d5e2f926df8d6c8d583.nq.gz
    ├── 3e4115223f2c8006e86ba73d9f9b07e57db9796b.nq.gz
    ├── 3ec9f589c1c4a34ad2a6ad584dc1d1be7f308760.nq.gz
    ├── 3ed5f856f098959dd5a4e58d569467e645055d41.nq.gz
    ├── 3f39ed785c07a27f1f0510313e00993a2c300a10.nq.gz
    ├── 3fa0553b5abf2f1cac33740dcfac44d9f903207f.nq.gz
    ├── 3fba44bc3615a9afaae9b5af2012945bc0cb3396.nq.gz
    ├── 41932e7dd40c4cb5323cfeb080640939c3138107.nq.gz
    ├── 419e0b2bc6a58a677db77507e1795ee9cc12301c.nq.gz
    ├── 41eaa8d5c68a70a9204887ee47b2d525f6b11499.nq.gz
    ├── 426f565effb2ed81667434ed3575522944b594b1.nq.gz
    ├── 4461c9cb0065f9e385fb19a2b2a07533a9165790.nq.gz
    ├── 44ad486f62c0ca3d3f3e2b6b3d98acf9a4430a67.nq.gz
    ├── 44ddf67bf1353cae0781ab1ba6e5d8cbbfda44a5.nq.gz
    ├── 4548b98b0f1ddbed2b64a3997f7a76e4576faa4b.nq.gz
    ├── 4578127a8b028b63f66fa5ce49ab0d0af7a5fed1.nq.gz
    ├── 46952929fcb0f63c5ee7aadac248b707e0b98b98.nq.gz
    ├── 46c861644dccd73c93b4208516a750160a5c6429.nq.gz
    ├── 474a54bb15294bbd5796dbc79a5e7a8690cda1c3.nq.gz
    ├── 47ec993e11ac3070a09376001588aeb68b295298.nq.gz
    ├── 4831f9b69200e67031dac513a925475edb011592.nq.gz
    ├── 48895bce7e0cf0260f9642c293439f0b8a72648e.nq.gz
    ├── 488f9790679ba6d5cf86712487e222cabde8336f.nq.gz
    ├── 4ad78a48858e8fbda157d16493e1a861108d4c9f.nq.gz
    ├── 4bb5afa02b772a3577dfd37e1cddfe14f5717ed2.nq.gz
    ├── 4c346a09faac1d7f84ecb5c27f483060423ce9ba.nq.gz
    ├── 4f3e33f77fe90d341784ff707cb582568569e6d0.nq.gz
    ├── 4f6db10340df8522128c014a07a6c49fe0f15df2.nq.gz
    ├── 4f9158cfe6aef049ebc375760a4fc42365a9a2a1.nq.gz
    ├── 4fb1f7491f7cfa9f60d05c122a9764b6168d2666.nq.gz
    ├── 504a76938fb782f92871fe06d1bf8f983c09c10e.nq.gz
    ├── 50ccb3ff5cdccabfee3f7b2f3ae8869d6c4f13c9.nq.gz
    ├── 5203c828806d544db5be070b86b10bca17027fcd.nq.gz
    ├── 52ef6f7a5e6f9db314ab9266a007069358cba9a1.nq.gz
    ├── 53b90ed0af5294004829ad6dd22d0a7768423fab.nq.gz
    ├── 552c80fa2fe447996b19aa190532b13cbe45ef48.nq.gz
    ├── 55ac5170a52d3e069ff317d93daab55d9e144122.nq.gz
    ├── 55d9b8278525d60edb820c3d2b8cfa503f437289.nq.gz
    ├── 56113e5d5e07a988f1019e8a5d01df1abb0eaf41.nq.gz
    ├── 581b874fb1be4ace0564dda46b3f8cb7ab14fb92.nq.gz
    ├── 5a2301367a56adb7aa50b0efed222f58502b1b40.nq.gz
    ├── 5a743bee74495935370503a13e1851cfdfd455d0.nq.gz
    ├── 5b057b7a200e6edbc77cb0846f41420ce5010ea8.nq.gz
    ├── 5b2bacc96d6a804b8c7cbc0fc8a3a95e8584df27.nq.gz
    ├── 5bdbf72fc55e7363d9f801695cc6f2314999d05f.nq.gz
    ├── 5c1c477accfcc70b5b30b457851801edbea2c169.nq.gz
    ├── 5c1e3dc41b57df139adc140a5675936cd73dc828.nq.gz
    ├── 5c389667f837682772e4a4bde6a9a8436c1093a7.nq.gz
    ├── 5c7f1967df7d6a39d63e01501e77791367ad17e2.nq.gz
    ├── 5e06695773ef6fce81884b04d09faabe427b2538.nq.gz
    ├── 5e1f4b36a5aa011a027476d595be88415427a912.nq.gz
    ├── 5f2cf0f60b8f33add8021d3d355b08e0a0307384.nq.gz
    ├── 5f34d60e8d3a3807e58a12b5c9a9cd4962b5abaa.nq.gz
    ├── 5f709c5aac15f11a4cb08bbb627883011ff762b7.nq.gz
    ├── 5fc56942bd0fffc08f5eed3d2c71e2b31a2eebe6.nq.gz
    ├── 5fcbfc8c877cb79f37c627af64c67a28bb1c5cae.nq.gz
    ├── 60081f9555e4efb75ae39c6ff8d7b70015698578.nq.gz
    ├── 600861a682d072afb53c58e0f814a7ad3963e2dc.nq.gz
    ├── 608e18c7f5d5a85ea678f9091022984fa7714167.nq.gz
    ├── 60da74702d09327241518dac05ea4f971e128d57.nq.gz
    ├── 611805c547db9d3c9e8c98f660771141be717b65.nq.gz
    ├── 613ffd2c5769a75e9cf357a76866e53973502054.nq.gz
    ├── 61aebceb0a9bec2dd64e5eea7701f0bf211bff25.nq.gz
    ├── 61d3ffe4f9416869d4fff5118f784dd567977025.nq.gz
    ├── 61e29a1e15a7aaf26f097ea8c93c35f864366f1b.nq.gz
    ├── 63ac8f93d9342fc770c79d1e61101078c084069b.nq.gz
    ├── 63c4347b276d38db2aa90cd22b7725dccfd6eda4.nq.gz
    ├── 63e8dc3911463abbe4c86fcd3b88cd15e96eb43e.nq.gz
    ├── 6456a2d23671ca677409e76078db96c554ed87d9.nq.gz
    ├── 649e5a52e350d44a6dc74cb5676831e7961044de.nq.gz
    ├── 64f38991f36520f5d0439b8c7f73f0f69073bbd2.nq.gz
    ├── 6619c8d6495fd367da483b16972a9207feb21fb5.nq.gz
    ├── 6680dd8a32156ab2ff3618fa254c9004dbc3ff49.nq.gz
    └── 66928d3c553debaa171d93e2e48ce89b2e9f37aa.nq.gz

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

[ansible-collections/junipernetworks.junos](https://github.com/ansible-collections/junipernetworks.junos)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
