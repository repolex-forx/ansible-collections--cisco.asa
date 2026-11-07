# Repolex Knowledge Graph of ansible-collections/cisco.asa

RDF knowledge graph data for [ansible-collections/cisco.asa](https://github.com/ansible-collections/cisco.asa), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/cisco.asa
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c467f33a84d0f7247396406e0648721bd6979ac5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c467f33a84d0f7247396406e0648721bd6979ac5
│           └── chunk-001.nq.gz
├── blob
│   ├── 018e577a68efe6a161d041b17844bbaa5701ff4e.nq.gz
│   ├── 03be69242da7cef859cfa70dbc358720e819ee9f.nq.gz
│   ├── 0430a0fda047b5a13b56b990e23236b72aa1c36b.nq.gz
│   ├── 052a92fdfa40412070bbc9e3af06eb7b59f8c5a9.nq.gz
│   ├── 0b24018bd415d185b92761769ef735a1ca308042.nq.gz
│   ├── 0bd7f543068c8fdf5a0e9edb0a09885673f79bec.nq.gz
│   ├── 0c27d62c3d20e5d7f7dc04cf38d1a3451c51748a.nq.gz
│   ├── 0d0ee49e70b668ef9e9a1af9f74fb48ded19f184.nq.gz
│   ├── 0f36839e906d33f087f628a5b9c124e0e46732fd.nq.gz
│   ├── 1170bdbe76c1ff06411766a4fdba2c7aa0d4403b.nq.gz
│   ├── 13a39df5a9389770d1abf3fadc1c3c638b1ca9fa.nq.gz
│   ├── 14c2e9ef483b8efd34e1b5369e92a224758f9beb.nq.gz
│   ├── 164afead284de6add13c8f514561691b2f1c8dba.nq.gz
│   ├── 196834da634627cac74ee14b8062eab97e578a74.nq.gz
│   ├── 19f6972386d6e6e98db4db4644aedc8cd74e0a75.nq.gz
│   ├── 1c28223f7029a2adb26946c392d7036f62a2f09d.nq.gz
│   ├── 1d07f3eca7b6690459b5e4eda3b6a5607bb51c67.nq.gz
│   ├── 20555334609f59f3ce86507bcca8ee70b22350ce.nq.gz
│   ├── 22bbfaaeec9747ec7857731f360b4f501d335141.nq.gz
│   ├── 23d65c7ef4514be9029e7c1d73b885867d81c383.nq.gz
│   ├── 27d4eef9bdb0bc0a6aa4bb826f44ee47a6fb7ae6.nq.gz
│   ├── 27f22120311c2fbe20619ea7c64effc233e1d56f.nq.gz
│   ├── 280e7835a3da6991750d15afbdd91b3413f309dd.nq.gz
│   ├── 28b765150a98dddc63f56bd85d7c53775de3a017.nq.gz
│   ├── 2d9735442e355deb82958ffceea1280f0adeabf2.nq.gz
│   ├── 305c359c2b0ea810052ecc62aa69e3d28c779ff8.nq.gz
│   ├── 30ca5296ce584c68507b6c7a46adfb5e88434589.nq.gz
│   ├── 35a085f9d9b7ff1b16e6e3e74ea97f320d5c240b.nq.gz
│   ├── 3ac5ac12dd6713c26282f57d7445c08d07f9135d.nq.gz
│   ├── 3adaf90cf207b547be00163de2d9479bad14bf00.nq.gz
│   ├── 3d2a4f58d7fba7cf5f0d46e1262d9e7b8c0a5507.nq.gz
│   ├── 4042eca6aed059f2a1e3bec67553bebf8bae430a.nq.gz
│   ├── 41af98e2f8259943e55878d2bbdb7b09ecadb3f7.nq.gz
│   ├── 41b0f3d1925a822979923e95cbf6f3168f10f02d.nq.gz
│   ├── 41b29fb3a8986764b77c994526b5cb52023a041f.nq.gz
│   ├── 43812860ace934dfd59fd505cab4dfa4446a8f7c.nq.gz
│   ├── 45d94ba4749a0041db660f097a53d0a5ff582f62.nq.gz
│   ├── 491b8db460f2d282530862f97508526feb54aac1.nq.gz
│   ├── 4b16a0c9dbae38ae70e50d47de7388e577fdc681.nq.gz
│   ├── 4d4368d53f2ab7b939f8215ce14915d9737ad0e9.nq.gz
│   ├── 4d4fcf32f36022ec04eae2217dd388c76ce94869.nq.gz
│   ├── 50921c3bb92b4c2e03a348f74c8fd90e6a731c72.nq.gz
│   ├── 529ebc050b28aaa30a5c383997d5ee095599afaf.nq.gz
│   ├── 534949b41bd305e2d9c27d63aea79f9e7c88c151.nq.gz
│   ├── 53a5bb95694038195f8a7831408d11927b2c31dd.nq.gz
│   ├── 53e10279fba95b16c0e664cf3decb37e5d7c8e6d.nq.gz
│   ├── 56029cb7cce48170a6efee249b9ec08279dd4777.nq.gz
│   ├── 5746756e4ad7d6029dd522f53331bfb5b070f4f6.nq.gz
│   ├── 576ba540acfee3395d6450a0c219afc6f4659528.nq.gz
│   ├── 576c19f5e495996723d413d828c78c7da9d3dc46.nq.gz
│   ├── 594b172197c43778162157c5d6baf41d3afa22e9.nq.gz
│   ├── 5a90586f2990a38cfddfe61fe6a7d1fb2416b733.nq.gz
│   ├── 5b32d4c1097ae6224bc65d88f0406972563164da.nq.gz
│   ├── 5d838fad79c10c6ed99b8095a77db0d83cb5d8ab.nq.gz
│   ├── 5e8d914d427162debced39881921d2d0123b99fc.nq.gz
│   ├── 6067e58f11591004c0925b360dfbd9e3778bb9b1.nq.gz
│   ├── 60c66c50d8590483f4244e39386df7ef36882d3f.nq.gz
│   ├── 61a2551a02365de7f7fd56424c257475b2dc0873.nq.gz
│   ├── 65c9daccbc467bf40253fca4c154c053b19c38cb.nq.gz
│   ├── 6870ac3b45518374731f541e6c430470ea3145c2.nq.gz
│   ├── 695dd4747527dcb3314b3fac72cde3e876d9710d.nq.gz
│   ├── 69dd631e8169e0b8a42122186ce32cb8922db8f6.nq.gz
│   ├── 6e367a7985649417da953a5f02043fa2970a8c5d.nq.gz
│   ├── 6fbd7ba49fc09291f2ec81dce0330a197e2f85ef.nq.gz
│   ├── 74761f8c53ea6ca525dd64278995632a744d3ee4.nq.gz
│   ├── 762e73dea00b7974f82d764d2b4597ed10c2d4b8.nq.gz
│   ├── 7659413dfba550b603260db3ac14447c3c16c929.nq.gz
│   ├── 779b731e1376858127cd6e89e64ec4feae7a917b.nq.gz
│   ├── 78cd59f473232a1b569265e465eb810cf085d0f7.nq.gz
│   ├── 7a19c7d301035953fd2bbb15b0cea59d76a55585.nq.gz
│   ├── 7d909c71c019c100b1d9ad97d28f9e163a9ce05e.nq.gz
│   ├── 7fae9983622ca042c31d73eacbc4d8fcfdb83af4.nq.gz
│   ├── 7fbfa6b949207e92c857982669529d0c01dec158.nq.gz
│   ├── 80ee453caaf1884c0f7fb07e7a4311df4a313d06.nq.gz
│   ├── 81d00ad9a1a7f945f8ad0d00b32bdd57e6c472b2.nq.gz
│   ├── 85417720b8f6c4d81d77009c44eef42d24cccca7.nq.gz
│   ├── 857277e60a10d9d1d617e52350abdcc1db587f28.nq.gz
│   ├── 8645d71f921d504e609c9d6545b602eb12f269a4.nq.gz
│   ├── 89e3e5693ec9dee9e5bce2bbbf94383a2fa9458b.nq.gz
│   ├── 8f01b72c22fb6522a7f15ea4ae8309c66d9d365e.nq.gz
│   ├── 8fb8f4136cb6814878924e64d19e4750c96d3b67.nq.gz
│   ├── 92a43f7196034e78cd9489363516002406288e27.nq.gz
│   ├── 95d36328a69e4305d4ae482a6f8629625f2b623c.nq.gz
│   ├── 95d4536bbc9b651600ff7bc26da98a6754969f6c.nq.gz
│   ├── 96e52c1615335a2ee5ed55d502dadcef7901786f.nq.gz
│   ├── 97f949436cd29b0fffa85842bb18a5ea4eb47f08.nq.gz
│   ├── 98b25306bdad5764ca1021ee359790b62e927bac.nq.gz
│   ├── 98ed04382392df72309461eed45d5af287609772.nq.gz
│   ├── 9a022686214f4f4a3980457642c14ecf71f90878.nq.gz
│   ├── 9ef5ba51651119181521e5925f8ee03e49376728.nq.gz
│   ├── 9f2422a80733a811961d6d1ccfe08ca156a463aa.nq.gz
│   ├── 9f980a682661fd21aeb97703c0f2dc3cf262251c.nq.gz
│   ├── 9fbf6ba53a63f202568ca4d029928634c04c43e4.nq.gz
│   ├── a0585260275b343dc9b3279e61ece9347acb8733.nq.gz
│   ├── a0a2c5ada7249d050c616057e615ea5cfaf7b409.nq.gz
│   ├── a2d23372d988752a859024d1fb76fdc2a27fe561.nq.gz
│   ├── a48f54b37241682bda98eb7be36e90571144d91f.nq.gz
│   ├── a500e0eeaea65b8e158b2f4d5ff6cbd89a57c382.nq.gz
│   ├── a855fbb2a4e1b9bfd1cfd4fbf6a21dc3972c30ee.nq.gz
│   ├── a910b0ab8904cb437ffa326b10a918f6ba9bff73.nq.gz
│   ├── aab7179947c3da9483fb8c43e77e01d3fc58a9aa.nq.gz
│   ├── adc223e38acfaad578997df2dabe4a7452a74912.nq.gz
│   ├── ae5575de46b01d2fd3fcf867bdb2703a90d8bfb6.nq.gz
│   ├── af6d008ddca8dd8c947d60a80dd7857cbea55dcc.nq.gz
│   ├── b084d5175df1c89cf473abbf3801308929278246.nq.gz
│   ├── b120bfa32ad22c4f930298e31ddfdca78d613d81.nq.gz
│   ├── b21d7c6d8b52bc3bbbddc76951a0c4581e818cf7.nq.gz
│   ├── b348e3c9847bf350d077d780d6ee029038fa2452.nq.gz
│   ├── b3b0505ae748bb46f4a2ae9affe8dc30bfc1a0c6.nq.gz
│   ├── b437d2d2056fb0260cf8c4970fea30b5e101a606.nq.gz
│   ├── b48a352cd3f6bf42411103373f23f898794c6101.nq.gz
│   ├── b49a359f91db0711aaff33b97f4337607b07bfb5.nq.gz
│   ├── b4e982c304178088bc86047eadb98a7bf85a4502.nq.gz
│   ├── b6ac78fd6ab5c0a3e592a3fd7cee3791d992bb1c.nq.gz
│   ├── b8a9209182a61ac6db0662923af4327dc5fb9620.nq.gz
│   ├── ba9c980fb86bef62c1cd5c86cd09c6cde80b0cd1.nq.gz
│   ├── bcaf34d795f31f7ffab0ffaf230a211c109e5b86.nq.gz
│   ├── be79fcbba02f32e31a119335f7e969183359df35.nq.gz
│   ├── beb1ff196d3475ef217f9ef3a80a4bf1de7fc349.nq.gz
│   ├── bee557e038a41410fcbec0efde5451c9c8f55bfb.nq.gz
│   ├── bfb604b82d9135cc8e8444be38c3fc7be3bc27f2.nq.gz
│   ├── c26ea59662bc8384960fd9c6464cc3c74a3f7f0a.nq.gz
│   ├── c2ad2aa945d2feed329c8a6ae23fdc8b67b77d9e.nq.gz
│   ├── c3ce4e5a1eacb96955377ee2907c106ac98e233d.nq.gz
│   ├── c4d0a46eff147101911fd81115a1ed36582482ea.nq.gz
│   ├── c5412c85040745bd8372487b36cb73e92c195351.nq.gz
│   ├── c56fbf851a43e6c4057e157edef2019fbbafe656.nq.gz
│   ├── c7528e83ba48603a58ad857458a3a61459f5b7bc.nq.gz
│   ├── c77c91a907b70246b052ad4ea0abe51f052aa88f.nq.gz
│   ├── ca453cc34ae1b6b80d5fb4ade5e16fb112ab6afe.nq.gz
│   ├── ca76966f5efe3a33ad85e7bfc2b1e8941103b6b4.nq.gz
│   ├── cdc5acea555f5f54b4124faa2bfe303776d9027a.nq.gz
│   ├── cdca13356fb267e78679f7f6628db71331bef38d.nq.gz
│   ├── d21f23e072c06737d17cbd3bebef3586e7e29eef.nq.gz
│   ├── d2af6a0c07d1567a0231a1bbe19af24845ce13e7.nq.gz
│   ├── d384f82f714e413486bc6addb4cd471a3c65638e.nq.gz
│   ├── d587960425cbbd24b4391e9cd35a5c3b3d3af763.nq.gz
│   ├── d5f0ca500034443190577a0c4dc11e0999aafe7c.nq.gz
│   ├── d71f5873efa8c8a8e591b6ca1586769df9ed4007.nq.gz
│   ├── d79d3dd1941159dc4e7dbf3db24b71f5d8891af2.nq.gz
│   ├── dad48fef3ccd624ac838b9388322f9084bdeff8e.nq.gz
│   ├── dc8e034a1d4db5129d53632c08df260397055fa6.nq.gz
│   ├── ddffad0d378168a31d565dd7e13e370d8305edb4.nq.gz
│   ├── debd3a59c656e50c384d04807a435e3f43ea38a2.nq.gz
│   ├── e0e2962e8adcf9386770fe64e24ffcdf3e4288ac.nq.gz
│   ├── e3e5966e40943337d9c5a64a67fb543c55caaa6c.nq.gz
│   ├── e411fc093fd5578b19562ac15c5227227bb8f98d.nq.gz
│   ├── e4bbe914d1dc7220aa6dc155e63438f4003b7ca8.nq.gz
│   ├── e57377ec9096b1ae05bba4ee9df85e176254d4bf.nq.gz
│   ├── e67507677239e306c3527e266f98f7176fe4ef56.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e758940f784384d7b62694f6fe53292c91daa7a0.nq.gz
│   ├── e7f007878b5d694b3134486d3675f877860dc5c5.nq.gz
│   ├── e90e5c84a5f811849e8de94ed6344eb09ba6a715.nq.gz
│   ├── e92e56e455542d1b0f0bf7511777fdc96fb21737.nq.gz
│   ├── e98b9313883c6823939e8cb36e76ac748d4bc245.nq.gz
│   ├── ea1472ec1f38b2d1410951194a02f8fb9f1c820a.nq.gz
│   ├── eabbe6bd835284eee63d7ecd472a142cf9fb1a1b.nq.gz
│   ├── eae64ed2b808de8b02b9be5dcaeb567e767e6ada.nq.gz
│   ├── ed77ca760935af59fa549a56a9da91dddf21bb5c.nq.gz
│   ├── ed9e759639db5e3731c201f172621a5c12e60dd0.nq.gz
│   ├── edb37ec0ede6b6411b2a805b83d1fe750e425eea.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f2d64eab0efa527adc7b3e1aa7e01b4fac053427.nq.gz
│   ├── f7905cd359734f3162211340287ee29855bdd0fb.nq.gz
│   ├── f81d2311b6510fa198df27129dbe82b5625b56b5.nq.gz
│   ├── f83d2f3fb102a8a3fd8ad0b5cd2aeb4a30200d0b.nq.gz
│   ├── fa4225f3eddd267a91bdd4c2d2ccee679c90ca97.nq.gz
│   ├── fb064a5c31d212741f6a5e7eed4a7512eebbb5d6.nq.gz
│   └── fe5326f50ae6974a36ba8d83ff05a685fcdf1302.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c467f33a84d0f7247396406e0648721bd6979ac5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 178 files
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

[ansible-collections/cisco.asa](https://github.com/ansible-collections/cisco.asa)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
