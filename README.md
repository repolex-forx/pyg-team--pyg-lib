# Repolex Knowledge Graph of pyg-team/pyg-lib

RDF knowledge graph data for [pyg-team/pyg-lib](https://github.com/pyg-team/pyg-lib), parsed by [repolex](https://repolex.ai).

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
rlex download pyg-team/pyg-lib
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d13e20662aaa075c82ab9c814f8c39789425bf7a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d13e20662aaa075c82ab9c814f8c39789425bf7a
│           └── chunk-001.nq.gz
└── blob
    ├── 01e042871d62462de7ecfcc81a9d121aab82e7a1.nq.gz
    ├── 01ff72c86ef9dab6309559c1cfaf9227bb86ce41.nq.gz
    ├── 02b5fc7c71741ad1ef7ab4b13390e84c4b29dc91.nq.gz
    ├── 02e85c2b4bde50fcad8d682c2615c4746cffce37.nq.gz
    ├── 05c2a7e97a3a6e2ec82ee06e4391f4e17e4856cd.nq.gz
    ├── 073158d69bb16696a2fd13a10498709e555f531f.nq.gz
    ├── 07e3f0103462710eaa2bdb1abf64efd285b11c2e.nq.gz
    ├── 0938bf879b6e6abad6d935511824533c53543f61.nq.gz
    ├── 0b8fcabc3395e8afb31411b71779a96340c2193b.nq.gz
    ├── 0bb8bcfbb2420e6cb7c530fa2da19f6eaa202951.nq.gz
    ├── 0d74e06262f773b4b5d45b547a155c713c375e1b.nq.gz
    ├── 0e24ec97acc1497a8e7053748e79fdff35d2d445.nq.gz
    ├── 0eea3b439eaf4f1639058cfbf58437b7bab25f6d.nq.gz
    ├── 1071fb82ade4f28528a402e3ca4f4eb73c42b388.nq.gz
    ├── 12b30ee2aa59d7ba827f920d71111fd08baec799.nq.gz
    ├── 1353b9516721294e2cfaa7a6091190aed556ff2a.nq.gz
    ├── 137798d64a939dc525603063d59f76230464c23f.nq.gz
    ├── 1674a585697b234f0528357ce57b8ad019ec0895.nq.gz
    ├── 1681df6e30be506f1999773fe27571e0112c7fd5.nq.gz
    ├── 168209cee676852a2ce56eccd30cecedfc7cdc37.nq.gz
    ├── 18bfc08a6ae13c6ad1d14a34d5bb98ecd3676872.nq.gz
    ├── 192bcb5fcb24b9db6a928eb074d84290608ab94b.nq.gz
    ├── 1a1c3784b73412ae8228718ffa9c358a876e770c.nq.gz
    ├── 1a20d5bb1e36ac50cfcfd7f23c98748a87e02ac5.nq.gz
    ├── 1b7a5b22a99a274af06ad6d53ad7be1d649c2dc6.nq.gz
    ├── 1c8dd93e668d0fee72d84557dd239e5bfde52a6c.nq.gz
    ├── 1d4b3bb14ca09d403c1d26d2935e50aa90bd6aac.nq.gz
    ├── 1f085eb00aa93d8dde20f9fa471211f08b95c189.nq.gz
    ├── 21183ff6ea0bdad3b6c6e79e34c21599401ace7c.nq.gz
    ├── 21cbd46030839a8d01e7361facd63097c280d194.nq.gz
    ├── 231caa02f4bef4c18e466185be3f97f2672b5ae7.nq.gz
    ├── 2529781f39b46eb57eea5926748faa443cd8eca5.nq.gz
    ├── 25792340b41cf59a4110b4afd2d71137f747dbce.nq.gz
    ├── 259d981c03ebca9add72c49b06e7d03fe3af1c8a.nq.gz
    ├── 26a1fd36fb5577c6d6d2709bed3ae6dfbd22ef2c.nq.gz
    ├── 2793def09f6997844ebec0b86917af5a2dd0e959.nq.gz
    ├── 27f32c5996a7d1bba6dfe0f7a738aa54cc217f35.nq.gz
    ├── 2b73402e40bab6e90669c4308fc06125d3534dd7.nq.gz
    ├── 2b7a412b8fa0fb7e985b0793321bd4e698f2b6cd.nq.gz
    ├── 2be35dcc4a4d6ec0d4fd99175b8773fb2b3a03b3.nq.gz
    ├── 2ca0a881fcc3a5a0acb5f9bcec3c780d274f103a.nq.gz
    ├── 2d19fc766d98a08d9d1437896bfb008a7b15f340.nq.gz
    ├── 2f3163c90c0dc9e11c0b4bea7c44a7933b2ff1fa.nq.gz
    ├── 3047bd11717870b0b0488fe184a2ab5369efd575.nq.gz
    ├── 31727ca2e7bdfe110bcff18a58596436b450fa86.nq.gz
    ├── 31960f45b43aa44fcc22cdc8fb2e4570c97f9662.nq.gz
    ├── 32582883532cf4681003e5a3f5af23795007fd8d.nq.gz
    ├── 338c180db46769037ad9847c85519b87b4017017.nq.gz
    ├── 34dc4f07d0ad118e1db2475f6e8d148285385fa3.nq.gz
    ├── 362c18c475c1bc8c3fbe37068d63e501977a4847.nq.gz
    ├── 367cbc1e2b85c5391bf35bad12aa69a19c738337.nq.gz
    ├── 384f7d4b0c305b13795fab7259db8f79729cbb1f.nq.gz
    ├── 386459761bb71511be476f581623c5f19a34b63b.nq.gz
    ├── 3950d0a7147122caf53923e7e16ceb4da98a0516.nq.gz
    ├── 3b28970408874776f2263031365f36cc6982f2e0.nq.gz
    ├── 3b36eb3db9894e5f575c956b5113a122f8311bf8.nq.gz
    ├── 3c73562403f5912a61405b752951652d484c2828.nq.gz
    ├── 3d1b0e4c666cbbe4ad8b6ff01b50d29289eba253.nq.gz
    ├── 3d9fe6e392dbe1b741b8a12d533d42516a0e021a.nq.gz
    ├── 3f19e616188b75ecc8d6c0b890a1c8cd0fd7cc1d.nq.gz
    ├── 40148df4b0a715feac42b96b7644312b0f25cfac.nq.gz
    ├── 4037414f8950921da1c5540dbc105fd8218f7ea1.nq.gz
    ├── 40969fbbb21fe612dbd82e4b91171d4af763e326.nq.gz
    ├── 41ec14ff9b1baef2219cdcc9a2af1efaab86d392.nq.gz
    ├── 426339dcd16f38bc5b487fff50dd78ae311cba14.nq.gz
    ├── 4271d09ea2005497f109d8b60b97241a299d72fa.nq.gz
    ├── 42fdb2a90b80b50fc5c4f35324c6452532ad6a2e.nq.gz
    ├── 469646be849fdfff1d5cf4dfd1be31cff81b633f.nq.gz
    ├── 46cd64e288950870f7f162c2d9e2ccd1e69cbdb5.nq.gz
    ├── 4beb2da51330fade74a0f48086e26aa3752458ee.nq.gz
    ├── 4c3d7082771f1c71abb9ed6042eb66c31ac9efdd.nq.gz
    ├── 4caa06a68912f1b90b00af49ad85a2683f0820a4.nq.gz
    ├── 4d30a120b728a5b322345f49d4457674ef5229a4.nq.gz
    ├── 4ea5f20486086d512a3f23622153e72af5a02652.nq.gz
    ├── 5216929bb270b51714d36569bb6007daf343e9b3.nq.gz
    ├── 52a74a76e999dc01c6f9304825d035c2f4b738b4.nq.gz
    ├── 5394c7cfa6b5b198fd4c6bf400f5298e42ff589d.nq.gz
    ├── 55f41468e73b25a3d24b1e796310aced10850ca0.nq.gz
    ├── 5673f6e9aba3b88b260d75a8fe6ce666dda40216.nq.gz
    ├── 57e253fcf4daf8559c88ff4306b44d092cfff47a.nq.gz
    ├── 57e7c49f53da1a2311c395d297bc0e620b1a27d4.nq.gz
    ├── 593cb243428567dfb0de86def78541005a8aa0db.nq.gz
    ├── 59cdd8f2c3f99af0c1db42df0ff6600eeaaa423d.nq.gz
    ├── 5a526e50002df74d429dddaab09b6db1436cbfc5.nq.gz
    ├── 5b501ce2f5034ab9cd965acc06a31c8adf94a29e.nq.gz
    ├── 5c0b898a1f51d4c6fab766a38df6375bf0578197.nq.gz
    ├── 5c0e5342a302bba6784bc102a649226597160093.nq.gz
    ├── 5f6d47fa78c628bc41788ded7ebc2a783633861f.nq.gz
    ├── 607df739125a845270e3a09e06a994addd34c02c.nq.gz
    ├── 60f2840439b7e400ad9d372edb2b61ad5e4feeef.nq.gz
    ├── 6232b938dbfa822f203896f11daa6afb8417a865.nq.gz
    ├── 63db861339ef43a7f354c9bc6b047fb9c17b792a.nq.gz
    ├── 645548cfc53a77eec167d219b1dca0e72ee1ca7f.nq.gz
    ├── 6492cccf3cf42cbbd78082d7c8e4a8853cb88d27.nq.gz
    ├── 64db697e49a32272ef3dd0a5c0f1a0898dfacc8e.nq.gz
    ├── 651841a6b26b31593c634febcb5ffe42f4d2d4d0.nq.gz
    ├── 65cca7a02334113992345bf20f90400dcce1a639.nq.gz
    ├── 6606ced955c4da91925e647886329ca235addb64.nq.gz
    ├── 6886033349dde48c9fa6443f1a3533d9313c380c.nq.gz
    ├── 6980b55418df65a73b1902e10ae327698adcbcf5.nq.gz
    ├── 69da0faa71f23387e2dfaae7558273729bdaae51.nq.gz
    ├── 6a6425dc12338a9f78d0c93ba6ef627f8d1aa4c4.nq.gz
    ├── 6b3cd5d65a33b3fce712aace4c86c804390884a5.nq.gz
    ├── 6b65fc7adaa22d071cd0fc77e09ffa9ab3747149.nq.gz
    ├── 6c20b5f1de9f62f561e848f07b7dada00ec02737.nq.gz
    ├── 6d502c5fff6419e5e7f890446a78b40f25552805.nq.gz
    ├── 6d6ab2c750854fce5a647d38548e96a4c8e8b4ae.nq.gz
    ├── 6e0d480ab4087957dd41c311e9987383f648b9eb.nq.gz
    ├── 6e20c16ac1208a99ab31f5cc4f72b412823bc04c.nq.gz
    ├── 6eb81512a30831e4dbc631e8243807779e0f6630.nq.gz
    ├── 6f1519ea4c1978ea26999865b9bc739f21437ba4.nq.gz
    ├── 710aa2800db2ed217a42a270d6b8b827c800992f.nq.gz
    ├── 72000f971599ed737d3f9ae876d613f7434e2465.nq.gz
    ├── 732e5f850303c4fff612a8960bb35642f8f3b417.nq.gz
    ├── 766c2f07304d1f9e2125df5476388370363ef8b2.nq.gz
    ├── 76845aefefbfe2fa64fd60a5a8270fa114a46f94.nq.gz
    ├── 7765356fe5cba51959ef9d96d200c41f65c430e9.nq.gz
    ├── 78533336ecb9f030fc5fcad00b09a29d7fceba22.nq.gz
    ├── 794f0d04cd8d0a32dfaf706153d9753e308449fa.nq.gz
    ├── 796b6c0098c5296a390baf55291608ff5745365b.nq.gz
    ├── 7b22bc7a46d21ade4c8d54a4ea657512bce01b0a.nq.gz
    ├── 7babdfddc53a8bc4a16cc3b88a7fe9b6f5c2ae13.nq.gz
    ├── 7bbc0c008dd245a4b016313e722371c50cff9d13.nq.gz
    ├── 7bc60db3cf08392b373a2255ed9e0616ff2792cf.nq.gz
    ├── 7c464bb1b9bf0df1b2e46e329ea9e7c18687bd97.nq.gz
    ├── 7c546151ce380f8043236e2496863868fbc5ea6a.nq.gz
    ├── 7cdcab23ab0894ededd5bcae8c17540b6c1cfbf1.nq.gz
    ├── 7d23475dc55a1cf2a014aac3e059f247cfcd9b51.nq.gz
    ├── 7ebfff8071fa8fb7924509a7881dc127f27ecd0f.nq.gz
    ├── 802865f3fb399ecb0d6b4963efbc62a2b5b34287.nq.gz
    ├── 818d133d371dc89bec12d621e24d22a95a9b7615.nq.gz
    ├── 8481e490743b40d18be1aa878f738b3a9d17b011.nq.gz
    ├── 881e6a2a4bf98b21f7671767ca26ef586e2d179b.nq.gz
    ├── 88d49745bff45dc81a79dcc1a2b328c559261661.nq.gz
    ├── 8b10d3d0e6007c1fe68727d4290972487ce42b22.nq.gz
    ├── 8bc112a5d2ccf2c8f79dc7e3b487f194b980bdd4.nq.gz
    ├── 90831736cc3013c6c067da74a8d8b3488a10dc73.nq.gz
    ├── 91b004c7fd2eabb64e70c6efec825066e32f438a.nq.gz
    ├── 9200ecc7d93031ce501be69a537d960c5044b7ec.nq.gz
    ├── 931881239dd3bac4c037e797d5208c29d895c223.nq.gz
    ├── 961a62cf492899bd1e25f6796da8352f90a7547d.nq.gz
    ├── 965f4a423bceeab68cf0a82a3388dd51f8731957.nq.gz
    ├── 96a3c1151a466279939ffad511d7b09c2d79b12d.nq.gz
    ├── 96e2b6b1c03e74ed52a2f00b61dd6eb6a5ca217f.nq.gz
    ├── 98db0783227a06b211f35a1603f8e8f71f809958.nq.gz
    ├── 99057075b19b3472afc58e15347526d4d2c0c93b.nq.gz
    ├── 9bfccfed705b773011461a1c59e37e455cc884ee.nq.gz
    ├── 9fcc683f3efc1af215c087ce3023548b12434300.nq.gz
    ├── a3304f2f815c55da3fa9ece16182ea37d70ee91b.nq.gz
    ├── a438f397cfa10be985cecd5e192e56732bee5d6d.nq.gz
    ├── a5c6e14f9f6294b2a28c210489ba25783fd065f4.nq.gz
    ├── a6edcb1574b8d945211a4eac3642128e70a9ba79.nq.gz
    ├── a79afc7a1353a85f4a2f03f4ccd16bb8f43645c5.nq.gz
    ├── a94c5de4b6748283e0a0a261b536ee9a85fb2be2.nq.gz
    ├── a9bf588e2f88457fdf73ac7361ef1d596fb81453.nq.gz
    ├── aa8b1d5e2eea2bafad80fb123157d21b2f1b81a0.nq.gz
    ├── abcb8b8c3fa337701df5c14b4f2f242347ab3907.nq.gz
    ├── acb4ad2a1ed923278df6a56ed2a21dd205165182.nq.gz
    ├── ad3a55b914ff55fa72701b1a30a78328d2b7073d.nq.gz
    ├── ae36ed8f05fb5382fac70d5b4a243accc9f79c7a.nq.gz
    ├── aed1908a8fca563933ecf87c7a0a57e8b953d600.nq.gz
    ├── aefa5c0e45d3abad972412ffca8ee36d0da6412f.nq.gz
    ├── b236cb193622114233d48ced30eef3dd652b55aa.nq.gz
    ├── b2b5c57bbb20fed2fc0dfdf270d999c5c3102911.nq.gz
    ├── b3747a4fb104862608bfb2291bb785b0026ca2b9.nq.gz
    ├── b43fe07cbeff970f276376a5cf34e4667b51ddb7.nq.gz
    ├── b44c4f8d858dc7d889e37faa35b113c6132f0fc4.nq.gz
    ├── b792d680f60542f293c9b64d0e6e1ffdbf6fc464.nq.gz
    ├── b87a143c0e3d8f77ce9a200c612b21a2312304f8.nq.gz
    ├── baf524952ef1f2c1ec958bf9425ae5d0b0be9905.nq.gz
    ├── bb81827a36202c26022a372e84d7382eabd7a3ff.nq.gz
    ├── be5050eb0c1e6445da09f20a73d6249d1365655f.nq.gz
    ├── c3abc5e8433e6537d7002dc2483c5eb06878cfa9.nq.gz
    ├── c3d1fac88fdfac023a715228757ab677047f72f2.nq.gz
    ├── c5285508cab380c213abe20d4fa341fe56eb0348.nq.gz
    ├── c5c58fd288cb76da32b9ae2dfece97784fc03cac.nq.gz
    ├── c798f13a5c5faaba59830ba44104dc2a6bb68477.nq.gz
    ├── c7a0d1df45c0fbbcc7fefe42349fc616e646855d.nq.gz
    ├── c8772049d9738b17f30ef7b1a94c01c600ebcafa.nq.gz
    ├── c945139992f44f7b780df96633c8a13c669cac9a.nq.gz
    ├── c9e798914ac00ca087a48db677998aaf59b4ef6c.nq.gz
    ├── cb94e074c62a4592afcb738acb67b9ba997ab455.nq.gz
    ├── cb9b9cfbb4be8e30476113a2836dcfb5644c6136.nq.gz
    ├── cbc35007f0f619466df742acd37bb277e588d4e8.nq.gz
    ├── cc55f55a151bb5de2d1f94e953ac0ea3f10fc243.nq.gz
    ├── cc9bdf25c66344d317bb373d1d19e6a1f8852aff.nq.gz
    ├── ceadbc19981dd821a2c4cb688287734025df92ef.nq.gz
    ├── cefcd4652b1b64cb01f2d61ebaef1ba566f9da13.nq.gz
    ├── cf9b9b21593d03ff46c3028c4464b86c08488391.nq.gz
    ├── d1416e1063278e9739b1a082a8e07421935b341f.nq.gz
    ├── d21d6d6fea7c9c1de9b8a77f86361a6f7c28089f.nq.gz
    ├── d295ecc8523bd09f2d27050b3c4b304b94c46940.nq.gz
    ├── d36073149a3fb14746da8a728b8a937e66d7934d.nq.gz
    ├── d460a5afe57b26a340f9249022db7c276366f800.nq.gz
    ├── d4ec3243be2fc11c09ca7cc5ac7a007ffef2e822.nq.gz
    ├── d59c02353242725f11711dddfe0f454eaa4b76ed.nq.gz
    ├── d5ae13015dd7c357db76733c84f603d0d46f54c7.nq.gz
    └── d67bcba22e006d08032acca09021cb0d1ac5def2.nq.gz

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

[pyg-team/pyg-lib](https://github.com/pyg-team/pyg-lib)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
