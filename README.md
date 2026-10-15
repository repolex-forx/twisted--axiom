# Repolex Knowledge Graph of twisted/axiom

RDF knowledge graph data for [twisted/axiom](https://github.com/twisted/axiom), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/axiom
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 02a14c39ec30d5e00403eb50fdeb86106c1f488d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 02a14c39ec30d5e00403eb50fdeb86106c1f488d
│           └── chunk-001.nq.gz
├── blob
│   ├── 027f5ecc33b375bcc3fb312ce1cf5719ce05bc33.nq.gz
│   ├── 08902ed5d270e09e9088c0ab582be5fb784ed620.nq.gz
│   ├── 0dc38b7151a99b2bca663fb437e1ef6d1699b534.nq.gz
│   ├── 0ecbd38e233ad3a053c3f86716a76ef28f187bbd.nq.gz
│   ├── 11a6dd74d7fad8a6681c01f86ad4f48092579a09.nq.gz
│   ├── 1384b9976b5082ef88ee4e3230452c1c6f4a11b7.nq.gz
│   ├── 149652acbf478aaadbfc79d59af5d74190a10e0a.nq.gz
│   ├── 157c6ba1513aab486d48cf50b581d5e0d6b81169.nq.gz
│   ├── 163e188e8d597e216af2b108f6dbd414dacf447a.nq.gz
│   ├── 18585aff8646d40fe5b502db72718e31ebfb63bf.nq.gz
│   ├── 1c7000d4474d8b1bc029f68354bb8825382722c9.nq.gz
│   ├── 2189cede7e2e52b22fcf404d38e665f169e09cad.nq.gz
│   ├── 2236044c6dfd181267d71b4955a5b3fa21fa21dd.nq.gz
│   ├── 24d80ba897e72ede11f06f5780c4b72e548d5dcc.nq.gz
│   ├── 26565da135b6a521c93849f4283a00c847117df5.nq.gz
│   ├── 26a58175d82bf7e705817cdbc7f315b5681e0fe1.nq.gz
│   ├── 2738e7f8a5b558378611c78b11ed12f2fb8b8911.nq.gz
│   ├── 2836595f9653f2799d96bb426905b20008197168.nq.gz
│   ├── 29dfd3d3ca5e378c81f2bff5d8d2a8223c09db95.nq.gz
│   ├── 2ab79dc835c702ffc59057c09b601c76579f8cc9.nq.gz
│   ├── 2b69b938c4e4707f76b13182f1e4c2ab7c7a9d0f.nq.gz
│   ├── 2f6b91476a964ff2b12b0f885a7ce4f8fb0e0a80.nq.gz
│   ├── 32151f92540a86704535f352dd0fc0412b01d760.nq.gz
│   ├── 3438b164336c805095a92f9dfe48188d73babb53.nq.gz
│   ├── 35474611da4931191f837a5c9909b0a36bf6a82c.nq.gz
│   ├── 3baceb02ae5be85ea22c4ec8225ba4f69a8b7f29.nq.gz
│   ├── 40c9a80d6cecdd85246818d417a03763528849fa.nq.gz
│   ├── 40d810bf93a0fbea3108bb0dbf7841d33f801ca7.nq.gz
│   ├── 413f13e9a2cdc7abe9d7c000b1c3f18b0da67f3e.nq.gz
│   ├── 418bd160e9455479d783bcb54bd88df2e48082ea.nq.gz
│   ├── 438cb6faabeaf4605089a1c93d8389b3a4f5e143.nq.gz
│   ├── 43a78d1852e6d1db26f50209edbad04ff730f57c.nq.gz
│   ├── 43ed39509fb99330f3933707d87f924484a05bc8.nq.gz
│   ├── 44c0c117600c63b6bce83cef31fe44498ab58acb.nq.gz
│   ├── 45cd84673682725b9d4cdb1267b1b22842f2ab01.nq.gz
│   ├── 47cb0900184145236fb6a48e695a148effaae555.nq.gz
│   ├── 4854588cd97f1b16b4c6d733c219855b9e6f5198.nq.gz
│   ├── 4a20d54b6022592ce577936c8a87736324e0056c.nq.gz
│   ├── 4ba363a38cba99fc0a3e8eaca05512405e6a0b84.nq.gz
│   ├── 5124e8e7cb40740d29c0bdbe051f679aec6d66ef.nq.gz
│   ├── 521439d0b9549e4b08a48cd31bb11a85c31b1446.nq.gz
│   ├── 52addea1d202f960f6a5e31eb2d97389e472a627.nq.gz
│   ├── 52edcc4c67a9e27dd59538abe3ecd555eafc0d40.nq.gz
│   ├── 52fe364045f87298a539c8095144619e4c5d167d.nq.gz
│   ├── 531505e737507f3f25e3064f127c3f96f9dfbd11.nq.gz
│   ├── 559923795aac7a4e27f34858545c20f206693c90.nq.gz
│   ├── 5669e554ad1207035249a1230538a80458854457.nq.gz
│   ├── 570f7df00676593479ecef58874dfa34c2e7c48b.nq.gz
│   ├── 57e4edd2779e0f6a982c6bda1df1b222d04c9f9c.nq.gz
│   ├── 58e769179fb10c5238c8d865647950ba5f754325.nq.gz
│   ├── 594904bde1496894043cc1c0753fe14b5b159fb4.nq.gz
│   ├── 5b64589b297d149c3a0d33fb514f0430b43cc6f8.nq.gz
│   ├── 5c060c0cb392bc9be7aaf640fafb8753f83a1b2f.nq.gz
│   ├── 5e19eacf94a04df3cfd2e8a9ea9e745436b973cf.nq.gz
│   ├── 5f0276b33e08d031d401cdc4e618a41e9ba05642.nq.gz
│   ├── 68dc385fb5c08c85c82ce4f5b68eaa1274f8fccf.nq.gz
│   ├── 6a7b358e219a0d16b12b7d33ac134c2b4e94abf3.nq.gz
│   ├── 6b5890adb85694be758f1ba5fbab574c91ef6244.nq.gz
│   ├── 6d104179b0695992a94109aa017e2f2492676eb1.nq.gz
│   ├── 6e8fd657fa34688b0075d3e027b9fdb13881233c.nq.gz
│   ├── 6ed95da31dd644526d84715c2aa11374f08fb5d2.nq.gz
│   ├── 6f0283918d94d29e8d5007609c64df0893f24098.nq.gz
│   ├── 6f457a9b5724ae05272030618e67acf2c2b98d13.nq.gz
│   ├── 72e3a76bd470487258a41860d53b88beefa045b3.nq.gz
│   ├── 74a9a85728c967c782aec8e5e62764926612ea3d.nq.gz
│   ├── 75d0f1db58d331a707fdf8700f62f08b7e3b9bcf.nq.gz
│   ├── 7672cadde6827d578e445f22753b336f082377b7.nq.gz
│   ├── 782e8b78b0f4512ee38871653d9c2d4de41befee.nq.gz
│   ├── 7c5a7c5c1a525ae0f956e2a5105cbf240dfcf80c.nq.gz
│   ├── 7c7220d7716d040af49d0e7f596cbe1cebd79e01.nq.gz
│   ├── 7f6219a6504f91f9c5715dd4b80e930607c9331d.nq.gz
│   ├── 83f7736576fd588bc13c9374f882a7cc15dc034d.nq.gz
│   ├── 86231b766ba014ec1988bf3ed80ca9fc1d9a5e4e.nq.gz
│   ├── 8ab96143b981624cf29b1e6b8c80c4bc27336fb2.nq.gz
│   ├── 8b126471a1b217951e51f280aa2ff38a9bf503f5.nq.gz
│   ├── 8b41a212d493a8de3aadacb3f1ed39371d7eb10e.nq.gz
│   ├── 8bbdb8ad372b0f8ff1a5246dd99db015cdcb0802.nq.gz
│   ├── 8bcbfbed165375a2af2553fc7c2cde02d5c78de1.nq.gz
│   ├── 8dcca8e23d80d40f521898e4eb478c34bbb02a50.nq.gz
│   ├── 8e5cbd0dd9ea4b5d015c3e0666a5efa0029a430d.nq.gz
│   ├── 8e71a39ce01bf26745619bbeb2a80b19af5d0fa0.nq.gz
│   ├── 939d0589b2397cd9213bac6d35fe24b75d36c3fe.nq.gz
│   ├── 939d6726791c4f8eaf5fc5309b9e5e3019e32faf.nq.gz
│   ├── 95bb325f5f1874bb2a4b32860f28726157ae24c0.nq.gz
│   ├── 95e45966b5080bc543d69d0cd4e91b4f4e8cbfcc.nq.gz
│   ├── 97d835163cd29510e252b5ff6000e04aa12db29e.nq.gz
│   ├── 98ac66facfd5af5268753b29ab91b201493a7d70.nq.gz
│   ├── 9c295088a35b3299ff7a3eaaed73ac72eefa318c.nq.gz
│   ├── 9cdfac994d60d40267d97154309040b2309ebd94.nq.gz
│   ├── a0044b7301d490c66b0dad633a46e37e0091b448.nq.gz
│   ├── a280654f7b0ca8cf8c786450308246b8060b994c.nq.gz
│   ├── a6a0317deca4f7880277a8f9f07673fe3e457387.nq.gz
│   ├── a6d1ea002fed8ab11441bca48d3efb42ef0e04d8.nq.gz
│   ├── a79c88966c1bfbd546be8b558d5b122658ef9da6.nq.gz
│   ├── a96152ab9c39404a26a8bcc77b71d210c13c5a21.nq.gz
│   ├── a9da607b5d8282aa618f1be6438fb21512501221.nq.gz
│   ├── aa5686702f8cfe014763359ebf414ab65e14cfac.nq.gz
│   ├── ac5ad6dd5a16d031ebd0ab433f1d9b917d3e700d.nq.gz
│   ├── ac8f3d829b8f7aa55989b3c67fbd01dcc83763b7.nq.gz
│   ├── b16cc20c8375f3b5ef0d12db58c6cc47d9dc1599.nq.gz
│   ├── b28e19e87e997fdaa186cfd468d11679c471eace.nq.gz
│   ├── b424a35a9909c18505f6f0d36ced34fcb1a0934c.nq.gz
│   ├── b476534987f3efefa44bc41632e9c908e8303961.nq.gz
│   ├── b50aa701f99dada70ea77bc7ee809b0c49ba298c.nq.gz
│   ├── b6dfced321feb9b2b14dc4728fb947800aa024bd.nq.gz
│   ├── b7443a1b09e6a273c7d6642aa0b58e6c3758fbf9.nq.gz
│   ├── b7b686816dbff0bf4ad76bfdebc9660f10da8234.nq.gz
│   ├── b9eea3729870985b99fadbed3d7dd8fc58a8006a.nq.gz
│   ├── be0cd8631fb9a09ffe771630484e007a210232a9.nq.gz
│   ├── be77c363fe74ef14dd49f15d9837db99aa12f69a.nq.gz
│   ├── be98ecfa9f10cf1ae070b85c00cf01e029fe1c95.nq.gz
│   ├── bfdc71b2957c0812159ebdbf1eb31d105173bd2e.nq.gz
│   ├── c06cb83962fa6d5ac9ce234df569f215ef70f959.nq.gz
│   ├── c0f6f2877d524ff03ef110625f11b25f97b940c6.nq.gz
│   ├── c2bdddbb800d02015e1ed24472ad2556e2797fc9.nq.gz
│   ├── c7eb7186971f8b8ef2e1dc5fa2ab4955d6644eaa.nq.gz
│   ├── c853f15b33b1647a3ea951cb78782486a051859e.nq.gz
│   ├── cc3d81ae5893db90c9b9c6836fa9ae57f15aa2cb.nq.gz
│   ├── cc55fd9676bc9fb09d66c296d764bfe93792f665.nq.gz
│   ├── cc5de4956619a1d0ea02279660f1e62e60adee71.nq.gz
│   ├── cc8b3ca2a5c7120638d4f08e5c05a61aed9635e7.nq.gz
│   ├── ce6dda48bf93006653affab3df7a333eac67e18d.nq.gz
│   ├── cee8670887c2b024b3ab25401ecde1a9b95ae19c.nq.gz
│   ├── cefef6f7aecf7d6c6ac3908f25165e719a79d359.nq.gz
│   ├── cf55e126a538ad5b9a82de2aaa446a5d78e72031.nq.gz
│   ├── d3853453388d834c4a7e0bbadd972561d51dd0a7.nq.gz
│   ├── d3bc41a1a4f7033809a1cd44960c9b7aa614d4b7.nq.gz
│   ├── d5cba9e53b3e9c9af0754862b6178428ab87014f.nq.gz
│   ├── d5cc75495b3a19b707dafa1f340289a279f97360.nq.gz
│   ├── d6c7f53ba95abb1502643306c0fe26190e520dcb.nq.gz
│   ├── d75e95988eb9f7727ac35c6f0365ffb9fde40ae2.nq.gz
│   ├── d7bba1a114ca8af5254b30bafcffdfcf4e19944f.nq.gz
│   ├── d95a40baead8600a29e5b45c2a98fef377fca6c7.nq.gz
│   ├── d992dbd98fbc1d5b7b44037b059858bfd976f0de.nq.gz
│   ├── d9affc35f44c505d834b26cbc4062a1bc1b99675.nq.gz
│   ├── dccb594c0f67126d170da29cec7dd87813f477cb.nq.gz
│   ├── dd99cd0afbe4ed5129f7a0471905190410114bc6.nq.gz
│   ├── e098b4626b605918dc8f6adaba61abfb82296300.nq.gz
│   ├── e2d93a4e05570e036bbc27f94180a48f19d1f4c1.nq.gz
│   ├── e36acc3b186f2847a5135fce6eb2c49531e5b7c1.nq.gz
│   ├── e38962f4ebae440a4c3fed66241179dfd610108e.nq.gz
│   ├── e564bc325f2ac105ec108bf678ee897f9dace65b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e776740beac3439060f20ece03d2588465ac47f1.nq.gz
│   ├── eda71e814c63848ae9fc1fd28e6dc177ad041b75.nq.gz
│   ├── f091061069ef1f3881b41b0b933e12cb6899645f.nq.gz
│   ├── f13aba040ab2797f9634305e38271b3b0a218a73.nq.gz
│   ├── f7657ff2b597015cda241f2f697cdce9355b04fe.nq.gz
│   ├── f8b142af5fe2ac0ce756c5e55d60c3d834626564.nq.gz
│   ├── fb445a1b860629ca60304651f65ce420b52243a5.nq.gz
│   ├── fb6b10a09060aafcbfdbce94fd6564be584b9349.nq.gz
│   ├── fba201170f11bdf979443c10ca0a304712a2345f.nq.gz
│   ├── fcf0d7befaebf41684295f623ae354908f829f0e.nq.gz
│   ├── fd01e3f09b957cc0c588f33fdafe6f55317b008e.nq.gz
│   ├── fdb4f20c57a818a8c09d5da92075b33f67faa111.nq.gz
│   └── ffeb5d48fd7470f989fb5e769a6aff48ca8153fa.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 02a14c39ec30d5e00403eb50fdeb86106c1f488d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 164 files
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

[twisted/axiom](https://github.com/twisted/axiom)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
