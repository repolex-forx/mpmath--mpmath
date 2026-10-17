# Repolex Knowledge Graph of mpmath/mpmath

RDF knowledge graph data for [mpmath/mpmath](https://github.com/mpmath/mpmath), parsed by [repolex](https://repolex.ai).

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
rlex download mpmath/mpmath
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bbbeabbd7e82eab8cfd6948770ae51086ff47098
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bbbeabbd7e82eab8cfd6948770ae51086ff47098
│           └── chunk-001.nq.gz
└── blob
    ├── 00a7c619fc492291ea7c5b5a2e08cdffe2f1d8e2.nq.gz
    ├── 05723a1d8da6e55fd3b898ed26af30e25f4c37be.nq.gz
    ├── 0766d7c50e7725cce302c1c21688a083896b05c9.nq.gz
    ├── 098c79adacffe5b59bb167925d48035506e83351.nq.gz
    ├── 0a38f6345567fe84d9ea114cc52922b5d2013340.nq.gz
    ├── 0d27ff827eb31f7a4024de1a2542666bd24d4294.nq.gz
    ├── 0d96a6265814e0d9ccfdeeeaef7ad5047d5bd9b3.nq.gz
    ├── 0dd655b15fea56f9cf399d2e2380b8a189ab19f3.nq.gz
    ├── 0f506198aa33f5596e1cc5a4eeee2094049b532f.nq.gz
    ├── 0f61a1d91e43def0cc4b77ee684995cd6f26361d.nq.gz
    ├── 0f897851ed71fe681bcedb5d0f7b6dd97f4414e2.nq.gz
    ├── 0f9d40dc3fc9bd6fdcbad3ac045986d14a7a0a11.nq.gz
    ├── 15cc4a6f289dc999441734b4917499279f62b4b4.nq.gz
    ├── 16a5344c581e7f4563506d717f4f71760b49834d.nq.gz
    ├── 172b44add082482260e8ff79eef2408c9c5fdabe.nq.gz
    ├── 18b89e106dcde5aa18f7cd6eed01c40422559136.nq.gz
    ├── 19501d1fe0d4e88d5041e314b04fb3a50999ed41.nq.gz
    ├── 19a4bdcadfcd6af39d2544b1c3b7efc77b2d6742.nq.gz
    ├── 1a0d2a5265daa3d99e8fb8db988fd4887418d217.nq.gz
    ├── 1a2717f03242a9a151bcd46808815717cb2f4413.nq.gz
    ├── 1aae4b354db9ed3226e9ad3ef394b764662d2c98.nq.gz
    ├── 1b28a4d2c058054a0432eeab893e33c89d5edf44.nq.gz
    ├── 1cd500a82bda281c36e13385f5fcaa8ecb2ab206.nq.gz
    ├── 1f3cfe4f8cec2917aa73d73356f2eee596f9733d.nq.gz
    ├── 202493789d308115d71ebfa30a3bc85810cf8952.nq.gz
    ├── 20c41a49523e80b554ff88b03c1d62eaeb1c9b2e.nq.gz
    ├── 215c9b684e1bcc4a7068c548799f4f830a91dd38.nq.gz
    ├── 249775bf250b37916bbaf10c7622ed11444e9248.nq.gz
    ├── 25a0a3f626a796a73612edf64016062e2f56457c.nq.gz
    ├── 25d841458f239eeff739fae54f33e794c03d4b1e.nq.gz
    ├── 25ff1e9fcde75bfd4ed9c839b29f1f4cac6abcc9.nq.gz
    ├── 2646482bd3b438ca1c0fcc392088d13efaf085ca.nq.gz
    ├── 278f054dd8c712a0b5f78d99e45a1fe2908aa713.nq.gz
    ├── 293697b9fcf8bd82d58ac4ff45acd73fadac82f9.nq.gz
    ├── 2a100ae06c2844c7e02354382c406b208b903ce3.nq.gz
    ├── 2bdc0c7606923ebdfe4db04beaa47e4720fb2119.nq.gz
    ├── 2d2e60f43746424f514cc7b67b509fd641b57cd6.nq.gz
    ├── 2e72f2dc20f484f71bf64c8f841015b0ca234b33.nq.gz
    ├── 2fa349cf074cc621254b6a500c1059993b3af83b.nq.gz
    ├── 2fc2a25d088162bb9915345adf5b65b28dc6058a.nq.gz
    ├── 30c5ec742effcde2cd90672ad679dfcdb242cd85.nq.gz
    ├── 322fac4ab10a2835a1b3b66c557bc62e32c44d1d.nq.gz
    ├── 327119e6512141db3ad31ec44eb6b43fee5b03ab.nq.gz
    ├── 32835e1e880be74db564caf358967350e0410cb5.nq.gz
    ├── 32b80f37f8f3431e1cdcae3ab565982033b1cf24.nq.gz
    ├── 33b94471a03b3417345b9f4c861e340164eb5f0a.nq.gz
    ├── 34b45a51cf69e2d4571b090f8b5a78fc45c9a0f4.nq.gz
    ├── 34fd2dccc0fbe2179f73499e9b6855d9dbf4b787.nq.gz
    ├── 36a7c8236d74045717913235c25fb2ebadc1e956.nq.gz
    ├── 37228334888a3606877a6db51a8ba1f9a15e593f.nq.gz
    ├── 39531eed52e7fd6c8bcbdf6f83753e0b70c48a2c.nq.gz
    ├── 3df1af2cf791cd5bd204e8b5863c9eeeb521fe29.nq.gz
    ├── 3ec47c310ddf83c144e7f6e0ce6fd38e48849193.nq.gz
    ├── 41c2aa72ea8c4bfd8c71de1e83930a36863b96ef.nq.gz
    ├── 42bd7a5e9af900eeb3ae021b022148d84644ebd7.nq.gz
    ├── 449c77ffed8db8e3d80f8a33ff5ac3bab3b96cf0.nq.gz
    ├── 4785c12ddf60cf19525c1a1311905b52815d719a.nq.gz
    ├── 4885b7af29b41bad222972371699ae2a84bd38e1.nq.gz
    ├── 49f408f7d874dc5af9531a23050ff9d1c200077f.nq.gz
    ├── 4a36a5549fbbfed9cd25d49ca0a4b0181dcebc75.nq.gz
    ├── 4b496808e9545921663e341efea6142944f644ca.nq.gz
    ├── 4bac5fe74f41a90b761985a0b128a16deeb9d4aa.nq.gz
    ├── 4bc13b379ab027a47ed33d181a8271c8fa3f22bd.nq.gz
    ├── 4c61d4eb93ae2f5b10e783c3dceb1b58428f8850.nq.gz
    ├── 4c61d503783a42719c0f3e12a999340f3fabf3a1.nq.gz
    ├── 4cdc0a92c758c91e709221bb177541f7c5853f3f.nq.gz
    ├── 4de0b1118a6debc574aae03bb4239e5b9d0cb3a2.nq.gz
    ├── 4eb83ba2d078b800ead1ae1adf72798f5b49b6d3.nq.gz
    ├── 4f23ee29c64e0eb82945ca5fef2f0b7a5ff793c6.nq.gz
    ├── 505f858d122a56ff084e65c2d1003065ef6a89ac.nq.gz
    ├── 507634b31c3e56e9bda1c6819d846731a39f519d.nq.gz
    ├── 532c8b013b9dc87beca85cb227e85b8e7c48bab7.nq.gz
    ├── 5347ea52f402ebd4bfdfd0b4deae7e5ca11bb42b.nq.gz
    ├── 53e22d245760477d0a7fa98df50c3b08ad4b2393.nq.gz
    ├── 54d017ce58aa03be6abab164b503c893172adb16.nq.gz
    ├── 555a7158397061076440c0ff77b7f05bf5b3f07d.nq.gz
    ├── 558d466aff9be3e9c93d28d186c5ccd545dc7393.nq.gz
    ├── 5660cf16977e33e0d3ca96c9a8a87ea48e405094.nq.gz
    ├── 5896ed0579eceab086dc5c67eaa649b6061a53dc.nq.gz
    ├── 58f29069315124999cd4b555fee21aaf62e69d8d.nq.gz
    ├── 591bb0e6fbf279ab6620a41d870fdcbb3d2553be.nq.gz
    ├── 5963ed08695378bd5492263f02c7a374eb656510.nq.gz
    ├── 5ef59d260898447dc7e95c8f4e4ae3fa6f8f8ad1.nq.gz
    ├── 6203d3835cddbd5067f012ef087d2da809b0faca.nq.gz
    ├── 625eb2708858de936f34ed3800b91f3ca8bf44a2.nq.gz
    ├── 6481a68038974d723df95649f79b83e52cebffbc.nq.gz
    ├── 648d7c156b8e11c4641af09ba4eac2910fc882ff.nq.gz
    ├── 64e146e4ac96c1153f3519c18d1d9183096c5981.nq.gz
    ├── 699e841cd6ae181373a3b6a3931693825b42eb9c.nq.gz
    ├── 69b1bfdfcf022d85fa351cccb6f3bdf0ecb9e28a.nq.gz
    ├── 69dc546b36805e1f1db2d437ff2a90093537ed0f.nq.gz
    ├── 6ba62f79db409c703c0810dfad3cd97003070dc5.nq.gz
    ├── 6ca5914c80bebd80757abbf16b4a81d14f3ee848.nq.gz
    ├── 6da5025e800c954de59c56df1f10bd1e93ca180e.nq.gz
    ├── 6e187f281bc73181d867ab47881c1b6e04852947.nq.gz
    ├── 6f8737087a7cd91db7bdc1cc6531435a0d20f651.nq.gz
    ├── 6fadafb2dbb44fe19a2defa8d807d81d7c8e2789.nq.gz
    ├── 70849a9a474662af5871ddf0e3e00d23c6939712.nq.gz
    ├── 716ef9eb8de926f4104d753dd6a47b19082a25d4.nq.gz
    ├── 72872e5996c9e74c95926b206ed8ecd815f84711.nq.gz
    ├── 73b3a57e84dfac2d87bb84775ef29d33a85c3e2f.nq.gz
    ├── 75182158665dcedc3d606915aa8ce4e6b5ad4a59.nq.gz
    ├── 7562880b9eeddae28778865da61c3a9f1a8be722.nq.gz
    ├── 75c397f99105e666cba817533fe01d4b373df7ca.nq.gz
    ├── 790f33dd272ffda895b61ec3771b02ef8b61d529.nq.gz
    ├── 7989c00358d11e041f048cb23ed0a6b0924c447c.nq.gz
    ├── 7a11fd2bfac5e2da84cc04e1f9f2bded9cd8866f.nq.gz
    ├── 7c252e60995ed8cf0db8d6915e0dfab698b73ef0.nq.gz
    ├── 7c2ae83b09070a01cbadd8bb07d76ff903bab5d4.nq.gz
    ├── 7d47c0ea77d2e2a19bca44578f9565b4d35f39f2.nq.gz
    ├── 7d5701570c1fd136a8b3c4960f455f2290fb5f52.nq.gz
    ├── 7f1d67093dd53eeec70a7e6bb2f9dddf8885fae1.nq.gz
    ├── 80898ae13b878d1337ff9361f32e5151500dedd2.nq.gz
    ├── 831d5b58a5f28fed618a3102418bfb080b939bf9.nq.gz
    ├── 832256a6fa55366a3d329078f5c6cafd67dada57.nq.gz
    ├── 83a712d48717b1d0ada125992bbb3b70082fb7e6.nq.gz
    ├── 8547d94a4ef6f2d9e30061f8ba28c8f78294c0a1.nq.gz
    ├── 87a618663e27c4b7aca97b8154afa2ae9328606e.nq.gz
    ├── 87f1fbc48b47ee89a5ec5dadb025fd02c8a0646a.nq.gz
    ├── 88f4fbad7398798c04543690de846f42bf126f4b.nq.gz
    ├── 894d1a012985ebdc664d712e2162cef861b987d7.nq.gz
    ├── 8cbc4595184328b38a3277db3131ec733b2a7392.nq.gz
    ├── 8d71534168acdc70d74dc3368d79485c57edf2e4.nq.gz
    ├── 8dead0671db435d4b97c9ff8c937ebde84927b1b.nq.gz
    ├── 8e43aacbbe4e017b1249599c40b68489d93e23cd.nq.gz
    ├── 8fe40250f25481f5e3349ea7d013339f33395ec0.nq.gz
    ├── 904379d619313a57f070981313c3a70fb92cc90f.nq.gz
    ├── 9048a844a2a14d81836c414a51767973008bf342.nq.gz
    ├── 91d9a3f53ef70b256001808635832a49a619c223.nq.gz
    ├── 931f76dbd5856888518b2d74b92700899f3921c8.nq.gz
    ├── 9475cc1fb1d8fe40a7cce6c9abe17ed3e33b1d54.nq.gz
    ├── 94abc6c02d39611d7f3d24afabbdf3f8c843df7f.nq.gz
    ├── 951b3f5081d8b1dbd7758a2e49008d797969efdd.nq.gz
    ├── 9564637d929e4c40321dc3518300efca14920b03.nq.gz
    ├── 9628dad86e1d7409adef16df769cc69a139852a4.nq.gz
    ├── 96611b5a743b61f06c03059d1637a5ac5f5785ac.nq.gz
    ├── 966295e0e6b74ee3cdb1fc0106622f8f0c78022a.nq.gz
    ├── 96762ce15a054bf8db922d37dbab1eae59069ee8.nq.gz
    ├── 9679f05571ac5b78e3a501e750c9f617e7e7e319.nq.gz
    ├── 98f8d7cb0c8a5a997a19f726296d651edbd2f0de.nq.gz
    ├── 9c162bf6af3096702b3bc4bb84a2be248f14868c.nq.gz
    ├── 9c437286eb613b86187edb65624019b2c8aa15d6.nq.gz
    ├── 9cca77b77218f44e492050055c89cbe5774f61ce.nq.gz
    ├── 9d1b2df5c46d94d863267ec2bbda6ae7fab47393.nq.gz
    ├── 9e530fa2fd58a8bd7c0dad981cf34792d8cdaa87.nq.gz
    ├── 9e8cc9dac9e2531af4d560ad54788b3c9ab3f3e1.nq.gz
    ├── 9eb3560b10644e949e64b46ee011af77b74abefd.nq.gz
    ├── 9f9a76318c3e8e0330d44c261ce6120ac4ba56ea.nq.gz
    ├── 9ff4bca0c6d3213f61c3b4780b81394f32c4cb91.nq.gz
    ├── a02e14ea8e46ca7fd375a7105a3a63fc6583159f.nq.gz
    ├── a1cf8fd246531afb22091e9c9f7a187030580925.nq.gz
    ├── a1fc09553c19c842d94bde1990ee07d59be86669.nq.gz
    ├── a3485a2c4d90fca926a6da27852151b2cf4a6038.nq.gz
    ├── a3e4fa0c6d70c514b95bca556c801e0887a93d0c.nq.gz
    ├── a4a0efe33ad1dd2f450db1bdd5b16beb74b38945.nq.gz
    ├── a621b3fdc3068886b9303cbbf187a60e63bae4b6.nq.gz
    ├── a7932e1c4441be4f462f43e6796ed9fe4778e305.nq.gz
    ├── a81881a5c3cf7d05fc08b054e8e5145faca40959.nq.gz
    ├── adb58b5b7fcaf2f18b276a26c2d4ab7583b1a69a.nq.gz
    ├── af37cd3b40000d24b934a67f495a921dae86597b.nq.gz
    ├── af82733cf0d977886d6583c3faf5af7d782622b7.nq.gz
    ├── aff7352839370d16ab6f754d6aa3cb8ba720fbfc.nq.gz
    ├── b03be68b626778592ab459343615e9bb3e7e0b0a.nq.gz
    ├── b070d8ae4da2f84fbf7db8c6a4c2fc725fc22ce6.nq.gz
    ├── b0a0cc7c994dad22f1324c102f1742cfb068d24c.nq.gz
    ├── b0ce33601a26c34eeda058ef2d51ab1543048418.nq.gz
    ├── b305ce3805df8d3c7a370a1cc20da5d24061dd46.nq.gz
    ├── b36151dd202103dd5206dd50de3c598f750c2a79.nq.gz
    ├── b37f3208c526d439b3d4540784e3e41d41585a70.nq.gz
    ├── b69ddb6b57afbf3d0406303f64c490f686302dd4.nq.gz
    ├── b877653dd0123a8a5012029caf8ed588e65cb3ad.nq.gz
    ├── b8800d7fdc48c7f7a89a95f3644e8201a91f04b1.nq.gz
    ├── bacf85b9f41912d5af30257a54efe0922d9dc1af.nq.gz
    ├── baf9f20c49f92200f28a5488a012f48406cdd02b.nq.gz
    ├── bb580ee9d8ac6f2f30ccb8504deff1e06b0022c3.nq.gz
    ├── bc34dffcd48483f924a525c2e3e4d5db3217ed2a.nq.gz
    ├── bc4393bd6648fd63c4be31244bd1f09730108ece.nq.gz
    ├── bc6c02c0df220c3ea1a925990cb7c69568cb1db9.nq.gz
    ├── bcdc36446d87011b2598bed8fd3234dbe16abb89.nq.gz
    ├── bdffcc2d5617f45dc9ad55cb1236cc090a3ba935.nq.gz
    ├── be950dc23d404e715c3d5f43f51f96cef4272b51.nq.gz
    ├── c05ee4cc39d8f8a30a17aedd8bd82a68dd415ae8.nq.gz
    ├── c27f02d79edf6718b1ba970dcd8842256c47f022.nq.gz
    ├── c53301bb82c78d3891d2a9bc6ae655ab09424300.nq.gz
    ├── c63c8698a273660c6ae5fd45745e5c56b2e0a123.nq.gz
    ├── c66d181621a66ac2795d3e837b19ffa1094d4582.nq.gz
    ├── c6b530969d4887a430847bb852dec8ea034caf2f.nq.gz
    ├── c8f07a355da55d0891246f6cf5ec72ce24d9d943.nq.gz
    ├── cac23317d8a1592f0746e1814f0bf5570a9b4539.nq.gz
    ├── cbd17badae2117be6b05bdc0eee8f32596cc466c.nq.gz
    ├── cce2e331a8e313dddd06456377fc1e74c848824e.nq.gz
    ├── cdd5073a5eb14d9f545835d7a890065fa732f7b1.nq.gz
    ├── ce4ebad57a83f9cc056580abddbbe08f5f01bfae.nq.gz
    ├── ce78cecc25022efbef0aa69a0fd84f2b909f9575.nq.gz
    ├── cfa89c5c2f89d37630e6fe853219af82925f1dd2.nq.gz
    ├── d060e99b38a9b01c0e4caa96ae67333f746da2e6.nq.gz
    ├── d11210cedfe3d338797a19b588008b708a182d7c.nq.gz
    └── d4bccd1490c7da6e8700bc36d11b7f3424bdd6b1.nq.gz

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

[mpmath/mpmath](https://github.com/mpmath/mpmath)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
