# Repolex Knowledge Graph of qos-ch/slf4j

RDF knowledge graph data for [qos-ch/slf4j](https://github.com/qos-ch/slf4j), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download qos-ch/slf4j
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│   │   ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│   │   ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   │   └── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│   ├── lsp
│   │   ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│   │   ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│   │   ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   │   └── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│   └── repolex
│       ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│       ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│       ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│       └── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
└── blob
    ├── 00bf176f39101797db21db3c87d8afcde82e1a29.nq.gz
    ├── 012d438aab9c143e6935ae43bc01a6863fea0024.nq.gz
    ├── 013468b23d30e06aaf666b34f33cd348eaed93d4.nq.gz
    ├── 019764a34072d2c295c2d82959742b0e9f56d988.nq.gz
    ├── 02064c24798992fba54f964535aa11c474a82ffc.nq.gz
    ├── 0270e4180dd00b6e870d8011b1be1dd6194364c5.nq.gz
    ├── 02ca550238bb73c6c6e3585be24d14760444aec4.nq.gz
    ├── 02d28cdfd62577f4f4030a5986ee8210b7161d41.nq.gz
    ├── 032bddcaa3b962a6c1b4c20cf9b01a773586f209.nq.gz
    ├── 036dd716aa4f16b20b2adc5858990f942e4b2d73.nq.gz
    ├── 039a9992c65b55280428b4b10687ebdde2b7b379.nq.gz
    ├── 03caaddaa9a1b56ed77f210ee2d0c630e4d6c55d.nq.gz
    ├── 03f2a7be8bb8094ebd965446d14b6ead737b553d.nq.gz
    ├── 06233ac87b0833ce44cefff9ac0c24b39b2abdbd.nq.gz
    ├── 0626b871b415a5b4869b7a0c4c5acf0658859b7a.nq.gz
    ├── 065cba6c3d050f09defa2d33f72af8b2ea00fe81.nq.gz
    ├── 068452690b9ed8645cb969056b9830561a78ec65.nq.gz
    ├── 06b0ec58bf452a44c17b763d4f0eab23a853efb2.nq.gz
    ├── 06ca2017eb64e35a561dfc940dcd1563fd7d02e5.nq.gz
    ├── 06e31e93954d2898e6f2bf6e173c226457432921.nq.gz
    ├── 072189e7dba5d2da4d5ddd4341974540c4969fab.nq.gz
    ├── 08183ab0abd061cf05722bd4baa72adaf5e7e38c.nq.gz
    ├── 083ce2767c222e75d71707991b92f767c0a43846.nq.gz
    ├── 08686edfa75c9d93c7793191b40d831dff2acb1a.nq.gz
    ├── 086e0eabe35b4473a215113f7f73a7b55411e102.nq.gz
    ├── 08eebca94d62e7d00e062ae2981270a3602d478d.nq.gz
    ├── 08f33e9d151ce894a46c69e9320b5db27a71f954.nq.gz
    ├── 0a7f1310dfdac8aa9df7638f53d580b68e3178a7.nq.gz
    ├── 0a9171c76dd599f0fdc389206e88f24aaf19d0cc.nq.gz
    ├── 0a9194df96f540cd30f9859127414c2ad4a1d5d5.nq.gz
    ├── 0aca814e762c8f63e675b6a531dd15e03c20a292.nq.gz
    ├── 0b02a0881c5f050fdd82e01e5352bcd0d45852ae.nq.gz
    ├── 0b15d6ff1020ca991c24abd23cb9179c3a78029c.nq.gz
    ├── 0b67214c2a8df22c21a0273c28966fe64494c47a.nq.gz
    ├── 0c1b9037d5e5ef9db77230cc723c78f94a73f0ff.nq.gz
    ├── 0c6c460cee4059a0411cee911695aa77fda5cce1.nq.gz
    ├── 0c890fc9bf097e8b4b88f487d0d22055e8551883.nq.gz
    ├── 0c962c9e058260f996c033b2fd1f49f542198810.nq.gz
    ├── 0caaf810353b2006ba69ed23540f2c89343abfd2.nq.gz
    ├── 0e3ebde484610ed65868d8732d0998bf329a9eeb.nq.gz
    ├── 0e6a8c3f4c56ed55ce8ed77e9e7efb53729c5b37.nq.gz
    ├── 0e8d13c8149ef664750606025d4f88a31102b6f3.nq.gz
    ├── 0e9077a765b102fda04378f2e93f39315808da38.nq.gz
    ├── 0f008bfa47ac250ec845d11a978088b13850896e.nq.gz
    ├── 0f1ccaff12ea5f2c5d0a84476bd1942be6b15dfb.nq.gz
    ├── 0f60628db1ca5f93a5cabeb3601fd6e0542abe7a.nq.gz
    ├── 0f64802dcdc31a8510915d56dacaead3d7b2c829.nq.gz
    ├── 0fea54ffa86b29cbfff51aa55159f3a943eb9087.nq.gz
    ├── 0ff3d6a066ad5622b973162aed44105f78d54f7d.nq.gz
    ├── 109970552f41c43ff4d1152593b24cca6061a3d0.nq.gz
    ├── 10c11706ef24a4af4ad2294882e50197a9443a3b.nq.gz
    ├── 10dff936db91d66ba3acdcd79c5dddaf7fe125e8.nq.gz
    ├── 1194ceb4a5190f9537294044d0d87e56271ff7c0.nq.gz
    ├── 120fa94144f11b0422c9566fb67821a06b3a359d.nq.gz
    ├── 1229d2e94a41b754f443ede4a8b25933eb7bc97d.nq.gz
    ├── 1257f79c2e43c9752b8e728e735c2b0013633825.nq.gz
    ├── 12a49b8611aa47269b53ac1780ac289b7962052d.nq.gz
    ├── 12d6db1903d539698ec9e8819d82b79efb3f5516.nq.gz
    ├── 150ef8c93a37b6b48e94c03f6488ab57bd829301.nq.gz
    ├── 16194f772040020b91f35e9526ae5c6cfc0e6a9a.nq.gz
    ├── 161cbf3f62bbf3bb4ecba87d6f757c76deb3fd22.nq.gz
    ├── 16c1bc4014aa7e6456a31795b66fc0be698eff95.nq.gz
    ├── 17560015d3a42a502f460e8cb71180c0e17b8507.nq.gz
    ├── 175dd51c6c109e84b14389acf3ba7740fa5eeae4.nq.gz
    ├── 1815225ea1170eae638f98e001b88ba754ef480c.nq.gz
    ├── 18dbb1166a33604b29808d62ec560c7ee14045d1.nq.gz
    ├── 194f152409b808cb7fb219205aed3a27b82621a7.nq.gz
    ├── 198b4e9ea86a75b94a563d3c78a6b8483c6c9ff0.nq.gz
    ├── 1997426188b24adfc4e3d11a9fd240fa52e024d5.nq.gz
    ├── 1a064d476a1bab156799979cf70dbd6c4a00fcf9.nq.gz
    ├── 1a1860cb089802ec000d3164647a4b2afbe766e9.nq.gz
    ├── 1a3d053237bec66cfaee6cd674f0678a7f7d5aa2.nq.gz
    ├── 1bf5944fb07143e956c3be835c43b124a4f8a8c7.nq.gz
    ├── 1c2ca1530530313b88c62ee1815e679e78e79e24.nq.gz
    ├── 1c93065fea50938a95eced5c6a1881e06b5d9f2e.nq.gz
    ├── 1d3c5128a5f8d76288cad6e223c47b8887ec8d06.nq.gz
    ├── 1d7903ab8ec7db056eb3bb81293564b1195567b0.nq.gz
    ├── 1e403a9153c617c95cf01c6701ab5e6b071ca95b.nq.gz
    ├── 1e40f45afb249b696c002f0a4d04ac2d5197ca93.nq.gz
    ├── 1ea44794e062639df801bdb8632e305f05452823.nq.gz
    ├── 1ef3c601975328c6ff777d9eb9e82251cf0dcde2.nq.gz
    ├── 1f4ef9459bcc930c518283c8353045c4773ab3fa.nq.gz
    ├── 2050adb27a7eb410395ae32514050ea73c45caff.nq.gz
    ├── 21254fc75dcad77bffde10dcab0ad5464a1f0963.nq.gz
    ├── 219d435722245d69de6838ff68e305c0f1b0e14d.nq.gz
    ├── 21b42b61cfe5ebbf6530d49dcc1f79c5ea8204ed.nq.gz
    ├── 22255fcc4d2ac8d32d3cc7b540a84b5741016fc2.nq.gz
    ├── 22669c2bfe0ed29ed54812131443abf6b77c408b.nq.gz
    ├── 22bcee955640510cf628b27ae098278c3dfded61.nq.gz
    ├── 23c65dc4659bd01cccb75e02bb7d7341ea5d20ca.nq.gz
    ├── 23fbcecba526d624d8c691038ae613038aba2975.nq.gz
    ├── 243f5dd43b9d77f52d94ebaebe44ad5168c7e249.nq.gz
    ├── 2473ae1e4cd29b571e92af326455bca1ada59a42.nq.gz
    ├── 24c9317adae03360bcd80dabdd642f6f1e4298f1.nq.gz
    ├── 259d063ac9dfba96177b71ad81e0fb2097a2af5f.nq.gz
    ├── 25c53e618fc85aa3dbfafbc68e899842fe4509f5.nq.gz
    ├── 2617f42726ee8158a9adc124237e9d9853c7b372.nq.gz
    ├── 264ca493cc4b375149b1a3821e0e3ce1233af199.nq.gz
    ├── 26e7a554d95ed3c86e573fe0d623020fb94c29dd.nq.gz
    ├── 27bdf3e276a81fc8609cdcba6bd0fb5723730d6b.nq.gz
    ├── 27e1f49106d11e99a7bce2b2b4807cc9100d4799.nq.gz
    ├── 28b4aacfa04637b724e362f78de4cd4a4c242c64.nq.gz
    ├── 28e645c97e27933fb2dd4950a676781ec8941dd4.nq.gz
    ├── 2979ae912056645a156a177c0d7937481b559daf.nq.gz
    ├── 29c8a46b6a7a1ad103cf6a43b8b5e7cf54d7010a.nq.gz
    ├── 2b8869e56ac7b70afe106e6c3e3b587f69417d85.nq.gz
    ├── 2bb9ad240fa04c8cf706a4901c4807878e90c2dc.nq.gz
    ├── 2bfa380ed984611b3ffd37ff941a0d579d2896a4.nq.gz
    ├── 2c4da8a271d6331ae8452f01fab77c9f0ff602e8.nq.gz
    ├── 2c59530d5f291376054ad48fc462a028c92b40f1.nq.gz
    ├── 2c905a6967c15fd17ea8187ba58cdf04feacd148.nq.gz
    ├── 2e796c2bbfc51fab20650f80f1b29b3fd56295ef.nq.gz
    ├── 2f03e1a85e2cf090fe4f6892be268821874d8631.nq.gz
    ├── 2f269969ad781ba48a4e7a954b7b2fbe8a38c07a.nq.gz
    ├── 2f8e805e0ff7b4c425ca4f4799a2014f0975a070.nq.gz
    ├── 2faff1819ea29dee5a7ffdd0b479cbf128de3188.nq.gz
    ├── 303ec31e56f2a9f07206c518fb8dc55d85fc26d5.nq.gz
    ├── 30c3a9ce724931135265511c8b0c841a3d2fde09.nq.gz
    ├── 30f8487cf8574310b38a72aee3ddaf4183ded5fb.nq.gz
    ├── 32118d4d8476c012689b87e54913a898399eb060.nq.gz
    ├── 32572a2a4399939a406a1f3740192640d3ef9a71.nq.gz
    ├── 338c001db70f5ec6a5a5370a426e5b515e215ae1.nq.gz
    ├── 34c334215eb94c8062dc7b787b9cceb2573a529a.nq.gz
    ├── 3507c0b80c0ed8327580e9bf708d966f30ced11d.nq.gz
    ├── 352ba0d331020817561bea9e3f1f3441eee948eb.nq.gz
    ├── 3533d0e370ac4f5d77a0681b622bf15bf18fd29c.nq.gz
    ├── 355c4b1db08debeef1162c097b552308b2fd7e7b.nq.gz
    ├── 35f1fd1093fea4407a790b4c0f80bb09bec1c514.nq.gz
    ├── 36b6778d9f76f1e337042d56f6dae919612ff42f.nq.gz
    ├── 371a9b87401d1018c43ae5e0e2106d0fdcb70dda.nq.gz
    ├── 375bc2d2e2a82034972121b80b37c513946452b9.nq.gz
    ├── 37958eb43405f9367b6aa275a36b00ff152cf09f.nq.gz
    ├── 37f10a03bf7cffc2383dbbf45e43fc53494bf823.nq.gz
    ├── 3833b7388d7c4620e495f18c05d44bcbc5e114b7.nq.gz
    ├── 3853f3919610189d65fe8d3f2471f3c32a11f2fe.nq.gz
    ├── 3857ba3258c99a485298b114096477da1271f2d3.nq.gz
    ├── 3858270c40b9862c5b4e7cbab57e6f028a6fba08.nq.gz
    ├── 3945144f0fde9fe1cfbdd6c5818f7b36bed26ef3.nq.gz
    ├── 39a74a8a949a28aab19049a007f8264b7460d1a2.nq.gz
    ├── 39d3da0eac0ad274140c1e1fb4a6adbb80f3f76e.nq.gz
    ├── 39e5d02496626d80c648a385f2d92116d0f00ae8.nq.gz
    ├── 3a11790996ed1fab82d1ab2901befee49ca83159.nq.gz
    ├── 3ab15c603383c8531f4c38668ff89a6fae035f27.nq.gz
    ├── 3b574f1a1928991f723822cbbcb4b6a1b7473f25.nq.gz
    ├── 3c9ae4eb848df83a61972ce380ffeefac78b16e9.nq.gz
    ├── 3ce3d478a8046b214a82bbddef60733fbb5e7e0b.nq.gz
    ├── 3d85b3e6f7969d237f779a6d3bdeb0242810d273.nq.gz
    ├── 3da224c406fb51178e935d010e5e30f18d20f620.nq.gz
    ├── 3e77b467deec7e16f8b84f00e0753f85d6f653a0.nq.gz
    ├── 3ec7e50398c91d6653da9f159511806aecdaa387.nq.gz
    ├── 3f461c2849d6fe73788fe4e3c90dfd5280b77b6a.nq.gz
    ├── 40b8365ce9d280b47bd54e4af9e88491af924a9e.nq.gz
    ├── 412eeda78dc9de1186c2e0e1526764af82ab3431.nq.gz
    ├── 412fb334897cadcbfbe2d8cf0d451ec1a67f8e61.nq.gz
    ├── 417955f643a33552069aa8fd1987918ecf90a224.nq.gz
    ├── 41f7fcfbaf925fdf7a1d1f8e3e2a2527b9f77e99.nq.gz
    ├── 4209ca54e01c322d5aa4b4445fdd50c8e2ba9684.nq.gz
    ├── 425d14c893123984c3a87110acafa2b4c027dd09.nq.gz
    ├── 42619190635a5fe5327d39319a0690080a28ed56.nq.gz
    ├── 426b6f2d75479ed280dc4fc16769fd91ae304d14.nq.gz
    ├── 428a442070dcd3986d6e0ab8b12f377e78ebde9f.nq.gz
    ├── 42a39e64189391450600b1ccd5937bec3be86543.nq.gz
    ├── 43a960e6d5e66e2e5232a0b73d1fb1962cf20103.nq.gz
    ├── 442bb5c736428bbaa59d01a0d5c8cc0093e462d2.nq.gz
    ├── 447c3b56a61a277776ea0511f2ce7aa7a0295ae5.nq.gz
    ├── 46277d7959fc089ca92ec3456d5b189b732b3227.nq.gz
    ├── 47e2a5589fc880aad413ec796e852f13a35eab0e.nq.gz
    ├── 47f95daaaa2b46bcbad8295e2f338c23ab662870.nq.gz
    ├── 488a79e9ebbf8ab6440c61e2c0ba9b566d6436dd.nq.gz
    ├── 4944b9cd65cdfbee31753950cdf66f0a8a5f83e5.nq.gz
    ├── 496af2768c23d0632f47595175930f76fbd1af5e.nq.gz
    ├── 49f72528c91e3416d8db0bda38010006fde3f3ee.nq.gz
    ├── 4a0d5101a3094482e6aa469d88df837ecba9d878.nq.gz
    ├── 4a6dd1004bd7918c72e6e994ad3e0617c3d229f3.nq.gz
    ├── 4aa80476a387d9b98937f1689ad1529a1feb173e.nq.gz
    ├── 4b9a3597c93da519ad5c03c061dd514c353668b5.nq.gz
    ├── 4c03fa6bb21496873cc90e5442f89905c95e7316.nq.gz
    ├── 4cb441737b658726cad199047f91f03f3ea6a667.nq.gz
    ├── 4d05078ce000c3e7681ef826fb2d285f82e3c3da.nq.gz
    ├── 4dd94cde2797c20e6b1f25b136104c1f85670b7a.nq.gz
    ├── 4e055c787208c7e90bfe21e2f0143e663fcb49b9.nq.gz
    ├── 4e1b1382df8f8dcfe29c7a20ff6cce2798186f4a.nq.gz
    ├── 4e28b16f20819d42194744da9d6f6d8b2d4a3ef5.nq.gz
    ├── 4e9a71125eceb8de0e5af85a6033771a621a33a9.nq.gz
    ├── 4edd59f5d9c47aa27d233a7ddf1ce40d1ef33012.nq.gz
    ├── 4fb847f1ee68eb5d3ed44eee2838efcdabc61ec8.nq.gz
    ├── 5067a997a09425f2c40d5090fb94cf277eb36b04.nq.gz
    └── 50a7c3bc9ca22246b061f3ccff44f724ba7f5d5d.nq.gz

6 directories, 200 files
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

## Source repository

[qos-ch/slf4j](https://github.com/qos-ch/slf4j)

---
*Parsed on 2026-03-30 by [repolex](https://repolex.ai)*
