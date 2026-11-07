# Repolex Knowledge Graph of huggingface/lighteval

RDF knowledge graph data for [huggingface/lighteval](https://github.com/huggingface/lighteval), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/lighteval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b97a6533bec22c4184b88526366fdf5d73d502c9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b97a6533bec22c4184b88526366fdf5d73d502c9
│           └── chunk-001.nq.gz
└── blob
    ├── 0025c04f68b34ec04757f3faccb71b988172e9de.nq.gz
    ├── 00936b3c675ac02846833694929f51ed8806b69d.nq.gz
    ├── 00b0d04cb019cb67dd5700611db9b95e7103d3eb.nq.gz
    ├── 00fe25676e795b2fc9b244eea6dc1e4232177553.nq.gz
    ├── 0179f5ef4e3ffe356c2d2fc03b9dd375a29cc957.nq.gz
    ├── 01b8b7334f819209226fac2b6b1f005910c68669.nq.gz
    ├── 03461f3ac4193298bb3ac7db3152b97f5459e966.nq.gz
    ├── 03d86268af95783703153edafd4cc0fb29e1030e.nq.gz
    ├── 048526cbc625b10bfb39183fb471a7ff80cb8978.nq.gz
    ├── 05207a46302b47d8e80ce097f805469fe19e2022.nq.gz
    ├── 058b1b73231b8d0e65321ae298dbf5fd7cb68bbd.nq.gz
    ├── 06908401f5766b53d334365c57e16a98ba2d2437.nq.gz
    ├── 0697ab72919fe2af6042a4b519c1185f0fff1416.nq.gz
    ├── 06ae9101fd2cb4ada3a6ccfb64fd5ddb58d344af.nq.gz
    ├── 06cbfd896d54bd9aeca2274d1d09068a546f268c.nq.gz
    ├── 06d3dd069914a1eddaa8f34a5a4abed9d23b8e30.nq.gz
    ├── 07471fb5f8595e0698869415362d5d4662070e62.nq.gz
    ├── 0758d8bdff48cf5e4952982b265bed8eecde3a48.nq.gz
    ├── 08dc09d651e64bbdf8266375b9dd4aa339e97174.nq.gz
    ├── 08ddde2f27f42020fd71216db7b34ed4a318e5b4.nq.gz
    ├── 08ed5551176a0a03a1887bc37d04d3444e4d14d4.nq.gz
    ├── 0999c83b71a818232acf22bd70129d289e3f50c3.nq.gz
    ├── 0a666ec838f658ee5b7f519fa7c8c6e5673664e1.nq.gz
    ├── 0b17a0be92e64ab39f045d8d9e03337bc886b298.nq.gz
    ├── 0b719885f3114f8d294669d01d0b47594a05146d.nq.gz
    ├── 0b9e248c2ea2205d3c7bc1fe8b1c58e3bc20da8e.nq.gz
    ├── 0bc61640cacf17ddfa678a34a110be3b9ab2beb2.nq.gz
    ├── 0deba65a0e30e15609059ced010d13c1d680cc44.nq.gz
    ├── 0f26a6c8bc73105418dfeaa174bfb06c7191c794.nq.gz
    ├── 0feccd5912e4057a6cce7b27d02783deba5cf9b9.nq.gz
    ├── 129b06b872bda0373b49d0219ee096baf7ef734d.nq.gz
    ├── 1339ef8f5a241aa4f79dacd0e91b587506272fe1.nq.gz
    ├── 13628af3e06f55c6100f8937a10488dd18f4b8d3.nq.gz
    ├── 1501fc3dd1411de27b846d934a603f133539a61a.nq.gz
    ├── 15e60c3999b804e7f645af7d84fee346411dda18.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 166235d8012908f6fcf3b36a9e52e60633625f74.nq.gz
    ├── 167cf12e00acacc2c23a71f5372b7128f172f7f1.nq.gz
    ├── 178154613a173957aa412be5bc861473469db1f6.nq.gz
    ├── 179cc551b0fb7b6527b4a9c694110af41793e874.nq.gz
    ├── 17cf4deab40012a33a3df94f28bdad706c50ad57.nq.gz
    ├── 1896c0652acee3b4288378f8b2f594e66b92565c.nq.gz
    ├── 18993cd5eb7e78eed26e3aebe34d502ae7457b95.nq.gz
    ├── 18de1a84e47f7b68155159de80434c5e256372b3.nq.gz
    ├── 18dfea9a1e5e35080f97dd77470ff3134c496a62.nq.gz
    ├── 18ebef8c0cd674675fb3e5ab70d537303ae82458.nq.gz
    ├── 1a7028aebcd60feeb9551b31ac9ae330f4e7bd08.nq.gz
    ├── 1a8c26cfdd2bea05d8b575a18ecad565eab0d296.nq.gz
    ├── 1ba7599384e3eb6ce29735961339068498a51dbd.nq.gz
    ├── 1c9dbaf238312cc76bde97241097c9ddc8ab08dd.nq.gz
    ├── 1e01a1095833e4ff0dd9d5cffedbd5dd13d1bc33.nq.gz
    ├── 1f5da9c146039b2652ed86450b5e8e570fc39f4d.nq.gz
    ├── 1f88329e443e55658251fc620ffe1373d5a39291.nq.gz
    ├── 1fe45690045bc3df2cf0777afb38e40b4ede1546.nq.gz
    ├── 22183d3520a59d185060784b5aed53c165800b33.nq.gz
    ├── 233f8f0cffa0fedd5939de9d022740528cddc088.nq.gz
    ├── 23533d56c058c409821fc4b63f5af88ecfea4a01.nq.gz
    ├── 237a90b3da5544acf389ffc0b0a63cc29bf4e7eb.nq.gz
    ├── 241707a325696f515ea797465fd5031969f10210.nq.gz
    ├── 2489369bea766c18c14bc9d7c76ad45908d00794.nq.gz
    ├── 24c98055eaaee25a2e9e581b909e95d264d52955.nq.gz
    ├── 24f9fa5c5fe8680fc32e31de931b62d27733c1ec.nq.gz
    ├── 252559c8da7b0e02fc2ab5417b0b58230e15b9a0.nq.gz
    ├── 257da5d32f2cfea6bf59a3e579fb5b86e9d2fab6.nq.gz
    ├── 25d5684a6e3568ca3f17944ea613ee3ed9e880f6.nq.gz
    ├── 284161d4b33a403a64f9d23ab5b6c8f749e87695.nq.gz
    ├── 29cece2fdffe074179ecbb05081d6f96f8d5a29d.nq.gz
    ├── 2a0e780dd58884e7e573c47b67de39ed2eed7d30.nq.gz
    ├── 2ba82095cfeec519d1f66ac837a6a7b4e550298d.nq.gz
    ├── 2bd52af314ad7e1093cc92c35e6b200202cd9112.nq.gz
    ├── 2beb09574e16c73f2de0e0a995fd5abd432e95a2.nq.gz
    ├── 2c4b761e888baa884527ca5bd0cf3bc3b4c491d8.nq.gz
    ├── 2c5ff65d7faf3daffb511b9bc521c2672e010883.nq.gz
    ├── 2c64cbc2b173e5ad888d113fd6c3bee3c9038f45.nq.gz
    ├── 2d2daace0b13dd8698ec9be1d0670e827410cd08.nq.gz
    ├── 2d447ab014b304988b813c88ea1f0cacdfeee621.nq.gz
    ├── 2d4ac4b60573da81334d886c4044c533a143d66c.nq.gz
    ├── 2d597c29e11856ffa3b6d436a65fc51dbabfbb10.nq.gz
    ├── 2d78f98873cda86fa6177882b923dd65ac0d4cde.nq.gz
    ├── 2dc0c64520437e325b611419c0b03d341f82ffb3.nq.gz
    ├── 2dc22995981fdbfa1c2a6a2aab8dca9e2ea0b36f.nq.gz
    ├── 2dce8abedab89e4826ad1d858d98d8f27a3a0b64.nq.gz
    ├── 2e2aae25f46b22cef8bb5ab7510a458bad120665.nq.gz
    ├── 2ef7b895b1b424a53935f9570924157c381bfb07.nq.gz
    ├── 2f24b823d21aef8882fec541db6b5490052fc571.nq.gz
    ├── 2f5136cc94d483b517f8d4e65d817e1f5d579288.nq.gz
    ├── 3019a610c94645f9c8978483e5aced4bdd48248c.nq.gz
    ├── 308743d46c5e74adf2f87fe3e13b816397622a70.nq.gz
    ├── 30f61018fe2e4c4a3cef12f3d85a291da80c182c.nq.gz
    ├── 31c6409ce07ad2935842faacc062bd21183debda.nq.gz
    ├── 326789bb62cfffb2465bd06502840b5ff2286c64.nq.gz
    ├── 337bfafba460c839c936c04d0192c4808e4f5819.nq.gz
    ├── 3403061d166acaed01062c4513ab83f9cceb876a.nq.gz
    ├── 34495ca3b7eb74225483d9bf1aa4368fe92b1924.nq.gz
    ├── 3473abb3de573f3fee8c0c1b371d7e1a27d82cb5.nq.gz
    ├── 354d6addfe8b1a3c76eeca5d83768195a6274c2c.nq.gz
    ├── 35b04f5c9c9737511c167aa063cded18436406e2.nq.gz
    ├── 3614f3372b074d9b9e3741b53508b75e57e6ca21.nq.gz
    ├── 3671e608fe2c93f0531419340d147d624a4de5f4.nq.gz
    ├── 36829f0cf98033083d502971401f03fd456bf777.nq.gz
    ├── 37eddaf2dcb2edf3a8b45bcc758c477b76dda8dd.nq.gz
    ├── 3a76be2a4289ddb3d88a582cf13cf6fdca2c32e5.nq.gz
    ├── 3a854bfbad91e19d486f838b963634f5ebc5483e.nq.gz
    ├── 3ab5976d83bff4d748e74a55adbc91271ebad1ad.nq.gz
    ├── 3c5074b7d9d15a0a54d97abb789065dfa68fc104.nq.gz
    ├── 3cbb578a3c02e929fcbb261f288ae03e4d4dbef1.nq.gz
    ├── 3d3291c25ec735b80024a68270874a113e2b5033.nq.gz
    ├── 3e37ec3c047ffa0f77ab35a3d5aaead580317883.nq.gz
    ├── 3efd054c8e45239da18f780e374dc9fcd0da55e9.nq.gz
    ├── 3fb166c1c5b8da23baffceaaa556ebc1e8d04981.nq.gz
    ├── 407a702c08a0d44042d29886ca2c9cad40a0be65.nq.gz
    ├── 410268f9efb4d9905625b64cfefd79c268074371.nq.gz
    ├── 41b6ec80a93936d56dbc54b1679c2a0380c5e9ab.nq.gz
    ├── 4251126f02777823ea7dd53561993c3ecb094798.nq.gz
    ├── 4275dcaf89beadc31c38f495cb9d4339e607da9b.nq.gz
    ├── 4311f6ca497490af7e0bcb9002dc759918e9c071.nq.gz
    ├── 433498c34fb9e5fd92216b67983d25da74dc82e4.nq.gz
    ├── 43e375b3b1be02479d15c9dc721471afeea31847.nq.gz
    ├── 44902a16d75f730690df156f481176e4b564a06c.nq.gz
    ├── 4493fc3227312117c1920b488ac0f445cd2f357e.nq.gz
    ├── 44baff30f2ea1afc773bd47e18bc007726ca850b.nq.gz
    ├── 466b1fc742c67c8f60be31340f232bde45f33244.nq.gz
    ├── 478135dabf25847c60740fc576537e64338faea6.nq.gz
    ├── 4811a4af75c4c84b1e67ca0be2f595850629d54c.nq.gz
    ├── 486bf5889caac7de11e216a5e3df19dfba9bcafd.nq.gz
    ├── 48850b820b49a235dc885b048d6825ab3a941e12.nq.gz
    ├── 4893755d4fba3cde6698eaeb2ddc235445e6621e.nq.gz
    ├── 48a66f5df4e3cff359a9eb1d1129d07f83fbe0c0.nq.gz
    ├── 4a8c011f8b94ce32e2383ac4fabdab8fa35aa8a3.nq.gz
    ├── 4aa20719c867d93143711a9e4a6911b0399e7a00.nq.gz
    ├── 4aa5cbf87020bd4721247746d265a8a0ebd7c730.nq.gz
    ├── 4ac21d42b51af573cc5500a9db438b0ef0499795.nq.gz
    ├── 4b57b53e9d536f3c7bebd186d86b25aad2c3ce88.nq.gz
    ├── 4b890858f00691eedd77244850075d652992a1e7.nq.gz
    ├── 4b8d72df639c69f523c8c4c25363ac74c4bf85e7.nq.gz
    ├── 4bc3943956ce22f67d9fece96360c270849bfcc7.nq.gz
    ├── 4bf6706aacd29440da7226083eacfe6322515353.nq.gz
    ├── 4d9adcdf89c41da245c49530c0663869a15f0098.nq.gz
    ├── 4dada73d41b613cbe587b8b1226389f39ce71004.nq.gz
    ├── 4dff5978ab8d8365416dfd2a8f243a64ce20697f.nq.gz
    ├── 4f009ca9adcc8217e4a3e9570db8ec9826efd4f2.nq.gz
    ├── 509bf574030c4e1642d9e8c73cd99bab92933a7b.nq.gz
    ├── 50e841c6c19f250287e6272843a2db1fec27dcbb.nq.gz
    ├── 5140ebc747073f5ff634bcfd8dd06af43ac5c525.nq.gz
    ├── 5156a8ea1015f664b8d244e63eb07e89f919c0d1.nq.gz
    ├── 515f92bf572db571f3848c548b0c1a2905e39f9a.nq.gz
    ├── 51ab76c22dc898910804dd772c0c959ecdff650d.nq.gz
    ├── 51ff0cdb869a07439067b26e680395d5d08d28f4.nq.gz
    ├── 52f339664e7530242ee2375be801c5f0a5031348.nq.gz
    ├── 5327cdbd841840b3c97471834c05f81507f5d102.nq.gz
    ├── 543d3badb344b69b67f61742266b9470cc745dab.nq.gz
    ├── 54790e45b8f17787a171094f357faf02b7967ca6.nq.gz
    ├── 5490e846bbf91482c2574ec3c876ec0b547e729d.nq.gz
    ├── 549f957bea5fa5ae55549fb676feec89bf05473d.nq.gz
    ├── 5543a9207dec1bb6784871c9379f3f1063c8d5f8.nq.gz
    ├── 566fad0f24fbdb8d519314cb310b2157988cb2b2.nq.gz
    ├── 56a0261261d113f68701b95ec1d7596c66f9d0af.nq.gz
    ├── 56e94cf00398e12e1a7f2ae155e576ed5cff9e13.nq.gz
    ├── 575ebf5950fbc0728f8da494815241795b5f5119.nq.gz
    ├── 57c7cb49707d160efc6860cba6c8ea1ef2c35b01.nq.gz
    ├── 592063b421156d7d784e592ed29549e11d6aa23a.nq.gz
    ├── 59a1e6cdb752c829c130c449cc4aca45d293176d.nq.gz
    ├── 59bd5ee90841708c13888d567f0c44b556b9ce7c.nq.gz
    ├── 5a116f6a3130d1d1ef43c117eece449d2f715e4e.nq.gz
    ├── 5c0df54b97761425084549c4ce042810e7a080ec.nq.gz
    ├── 5c31d63d591486fc1d49980028900616d37785c1.nq.gz
    ├── 5d74aa78c84379933106de3e5f97c092a54931db.nq.gz
    ├── 5d821cf6e82d8a01a4f1e4ad200b6e78b868d541.nq.gz
    ├── 5e6ed56b94ac554be3bb9ecbdf5dfa0798705e5c.nq.gz
    ├── 5e9693e35ec7ea0f8a759594f4f76752c2eaa9dd.nq.gz
    ├── 5e9bac215109b1567c467198e9de2fe9d6c34ad0.nq.gz
    ├── 5f2349af96bf42a724c1da9f5651d3d37e6ad13b.nq.gz
    ├── 5fce23699ed6388985d28692f53437a37470d3ff.nq.gz
    ├── 603087ef99364888c3a80957385329077bc93de2.nq.gz
    ├── 604f8c40d55891864fa704ddfc0ed19adcdc85b5.nq.gz
    ├── 62c37842656deca4853b3bcaa46d0a7a503918e5.nq.gz
    ├── 63215724c6a9369fad81d85f100fac41d7ec1181.nq.gz
    ├── 6342a9f9c27c080c1edf74612d1b527402684a01.nq.gz
    ├── 63dfac294a9b10b79bbb17268ec21b2d69342434.nq.gz
    ├── 63ee46a5788908a9c05b9d9ac985fd0348b376ba.nq.gz
    ├── 64e790a2fd3f221b500da9da50db9b50c579338c.nq.gz
    ├── 659e6a2df912272ef92b3dd869e5fc023637663a.nq.gz
    ├── 66470f85801624e64209808c7264ce659466cc71.nq.gz
    ├── 6685554d4249b83953099e64c1177ee6a1907b76.nq.gz
    ├── 66ed91c3ae2db17df987989d7ead86249e49fbee.nq.gz
    ├── 67124f10aa4e10c63a9432ece2edf687b31a84f0.nq.gz
    ├── 67268831d7ce16f221a786920a0f89ae84df7c48.nq.gz
    ├── 676c92aaf58d58d0c43e86a456ce5edbf507bf05.nq.gz
    ├── 67febe8ec872b1e398951bde67ce7b512112fb61.nq.gz
    ├── 6836fccda788c1a8c8f2350a6d0dcff43bcf9711.nq.gz
    ├── 6876af9fc6cda6dd90b995153bbbd53be0e3cd84.nq.gz
    ├── 68e8447127c2505d6685ee3fece6c9e64d9a4d5b.nq.gz
    ├── 68f6f5dbcb6251ad3d3a3b8c267af5d7292443d7.nq.gz
    ├── 694a76fe5966fac89e5826249399b1cb4cf87dc4.nq.gz
    ├── 694e5ec4746d2c36334db2426fa0dcb563aa87dc.nq.gz
    ├── 69817c1449774250cc991d056b25d0c6e059a884.nq.gz
    ├── 69f1286d1077d9f285cef0b1a7f8398de855cddb.nq.gz
    └── 6a0c6a326ff7eaabdfab141f1e0d33b1cde464d6.nq.gz

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

[huggingface/lighteval](https://github.com/huggingface/lighteval)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
