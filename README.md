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
│   │   └── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   ├── lsp
│   │   └── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   └── repolex
│       └── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
└── blob
    ├── 00bf176f39101797db21db3c87d8afcde82e1a29.nq.gz
    ├── 012d438aab9c143e6935ae43bc01a6863fea0024.nq.gz
    ├── 019764a34072d2c295c2d82959742b0e9f56d988.nq.gz
    ├── 0270e4180dd00b6e870d8011b1be1dd6194364c5.nq.gz
    ├── 02d28cdfd62577f4f4030a5986ee8210b7161d41.nq.gz
    ├── 032bddcaa3b962a6c1b4c20cf9b01a773586f209.nq.gz
    ├── 036dd716aa4f16b20b2adc5858990f942e4b2d73.nq.gz
    ├── 0626b871b415a5b4869b7a0c4c5acf0658859b7a.nq.gz
    ├── 065cba6c3d050f09defa2d33f72af8b2ea00fe81.nq.gz
    ├── 068452690b9ed8645cb969056b9830561a78ec65.nq.gz
    ├── 06b0ec58bf452a44c17b763d4f0eab23a853efb2.nq.gz
    ├── 06ca2017eb64e35a561dfc940dcd1563fd7d02e5.nq.gz
    ├── 08183ab0abd061cf05722bd4baa72adaf5e7e38c.nq.gz
    ├── 08686edfa75c9d93c7793191b40d831dff2acb1a.nq.gz
    ├── 086e0eabe35b4473a215113f7f73a7b55411e102.nq.gz
    ├── 08eebca94d62e7d00e062ae2981270a3602d478d.nq.gz
    ├── 0a7f1310dfdac8aa9df7638f53d580b68e3178a7.nq.gz
    ├── 0a9194df96f540cd30f9859127414c2ad4a1d5d5.nq.gz
    ├── 0aca814e762c8f63e675b6a531dd15e03c20a292.nq.gz
    ├── 0b15d6ff1020ca991c24abd23cb9179c3a78029c.nq.gz
    ├── 0b67214c2a8df22c21a0273c28966fe64494c47a.nq.gz
    ├── 0c6c460cee4059a0411cee911695aa77fda5cce1.nq.gz
    ├── 0c890fc9bf097e8b4b88f487d0d22055e8551883.nq.gz
    ├── 0c962c9e058260f996c033b2fd1f49f542198810.nq.gz
    ├── 0caaf810353b2006ba69ed23540f2c89343abfd2.nq.gz
    ├── 0e6a8c3f4c56ed55ce8ed77e9e7efb53729c5b37.nq.gz
    ├── 0e8d13c8149ef664750606025d4f88a31102b6f3.nq.gz
    ├── 0e9077a765b102fda04378f2e93f39315808da38.nq.gz
    ├── 0f008bfa47ac250ec845d11a978088b13850896e.nq.gz
    ├── 0f1ccaff12ea5f2c5d0a84476bd1942be6b15dfb.nq.gz
    ├── 0f64802dcdc31a8510915d56dacaead3d7b2c829.nq.gz
    ├── 109970552f41c43ff4d1152593b24cca6061a3d0.nq.gz
    ├── 10c11706ef24a4af4ad2294882e50197a9443a3b.nq.gz
    ├── 10dff936db91d66ba3acdcd79c5dddaf7fe125e8.nq.gz
    ├── 1194ceb4a5190f9537294044d0d87e56271ff7c0.nq.gz
    ├── 120fa94144f11b0422c9566fb67821a06b3a359d.nq.gz
    ├── 12a49b8611aa47269b53ac1780ac289b7962052d.nq.gz
    ├── 12d6db1903d539698ec9e8819d82b79efb3f5516.nq.gz
    ├── 16194f772040020b91f35e9526ae5c6cfc0e6a9a.nq.gz
    ├── 161cbf3f62bbf3bb4ecba87d6f757c76deb3fd22.nq.gz
    ├── 16c1bc4014aa7e6456a31795b66fc0be698eff95.nq.gz
    ├── 175dd51c6c109e84b14389acf3ba7740fa5eeae4.nq.gz
    ├── 18dbb1166a33604b29808d62ec560c7ee14045d1.nq.gz
    ├── 194f152409b808cb7fb219205aed3a27b82621a7.nq.gz
    ├── 198b4e9ea86a75b94a563d3c78a6b8483c6c9ff0.nq.gz
    ├── 1a3d053237bec66cfaee6cd674f0678a7f7d5aa2.nq.gz
    ├── 1bf5944fb07143e956c3be835c43b124a4f8a8c7.nq.gz
    ├── 1c93065fea50938a95eced5c6a1881e06b5d9f2e.nq.gz
    ├── 1d3c5128a5f8d76288cad6e223c47b8887ec8d06.nq.gz
    ├── 1e403a9153c617c95cf01c6701ab5e6b071ca95b.nq.gz
    ├── 1e40f45afb249b696c002f0a4d04ac2d5197ca93.nq.gz
    ├── 1ea44794e062639df801bdb8632e305f05452823.nq.gz
    ├── 1f4ef9459bcc930c518283c8353045c4773ab3fa.nq.gz
    ├── 2050adb27a7eb410395ae32514050ea73c45caff.nq.gz
    ├── 219d435722245d69de6838ff68e305c0f1b0e14d.nq.gz
    ├── 22669c2bfe0ed29ed54812131443abf6b77c408b.nq.gz
    ├── 23c65dc4659bd01cccb75e02bb7d7341ea5d20ca.nq.gz
    ├── 23fbcecba526d624d8c691038ae613038aba2975.nq.gz
    ├── 243f5dd43b9d77f52d94ebaebe44ad5168c7e249.nq.gz
    ├── 2473ae1e4cd29b571e92af326455bca1ada59a42.nq.gz
    ├── 259d063ac9dfba96177b71ad81e0fb2097a2af5f.nq.gz
    ├── 264ca493cc4b375149b1a3821e0e3ce1233af199.nq.gz
    ├── 27bdf3e276a81fc8609cdcba6bd0fb5723730d6b.nq.gz
    ├── 27e1f49106d11e99a7bce2b2b4807cc9100d4799.nq.gz
    ├── 28e645c97e27933fb2dd4950a676781ec8941dd4.nq.gz
    ├── 29c8a46b6a7a1ad103cf6a43b8b5e7cf54d7010a.nq.gz
    ├── 2b8869e56ac7b70afe106e6c3e3b587f69417d85.nq.gz
    ├── 2bb9ad240fa04c8cf706a4901c4807878e90c2dc.nq.gz
    ├── 2c59530d5f291376054ad48fc462a028c92b40f1.nq.gz
    ├── 2c905a6967c15fd17ea8187ba58cdf04feacd148.nq.gz
    ├── 2e796c2bbfc51fab20650f80f1b29b3fd56295ef.nq.gz
    ├── 2f269969ad781ba48a4e7a954b7b2fbe8a38c07a.nq.gz
    ├── 2f8e805e0ff7b4c425ca4f4799a2014f0975a070.nq.gz
    ├── 303ec31e56f2a9f07206c518fb8dc55d85fc26d5.nq.gz
    ├── 30c3a9ce724931135265511c8b0c841a3d2fde09.nq.gz
    ├── 32118d4d8476c012689b87e54913a898399eb060.nq.gz
    ├── 32572a2a4399939a406a1f3740192640d3ef9a71.nq.gz
    ├── 3507c0b80c0ed8327580e9bf708d966f30ced11d.nq.gz
    ├── 3533d0e370ac4f5d77a0681b622bf15bf18fd29c.nq.gz
    ├── 355c4b1db08debeef1162c097b552308b2fd7e7b.nq.gz
    ├── 371a9b87401d1018c43ae5e0e2106d0fdcb70dda.nq.gz
    ├── 375bc2d2e2a82034972121b80b37c513946452b9.nq.gz
    ├── 37958eb43405f9367b6aa275a36b00ff152cf09f.nq.gz
    ├── 37f10a03bf7cffc2383dbbf45e43fc53494bf823.nq.gz
    ├── 3833b7388d7c4620e495f18c05d44bcbc5e114b7.nq.gz
    ├── 3857ba3258c99a485298b114096477da1271f2d3.nq.gz
    ├── 3945144f0fde9fe1cfbdd6c5818f7b36bed26ef3.nq.gz
    ├── 39a74a8a949a28aab19049a007f8264b7460d1a2.nq.gz
    ├── 39d3da0eac0ad274140c1e1fb4a6adbb80f3f76e.nq.gz
    ├── 39e5d02496626d80c648a385f2d92116d0f00ae8.nq.gz
    ├── 3a11790996ed1fab82d1ab2901befee49ca83159.nq.gz
    ├── 3ab15c603383c8531f4c38668ff89a6fae035f27.nq.gz
    ├── 3c9ae4eb848df83a61972ce380ffeefac78b16e9.nq.gz
    ├── 3ce3d478a8046b214a82bbddef60733fbb5e7e0b.nq.gz
    ├── 3d85b3e6f7969d237f779a6d3bdeb0242810d273.nq.gz
    ├── 3da224c406fb51178e935d010e5e30f18d20f620.nq.gz
    ├── 3e77b467deec7e16f8b84f00e0753f85d6f653a0.nq.gz
    ├── 3ec7e50398c91d6653da9f159511806aecdaa387.nq.gz
    ├── 3f461c2849d6fe73788fe4e3c90dfd5280b77b6a.nq.gz
    ├── 40b8365ce9d280b47bd54e4af9e88491af924a9e.nq.gz
    ├── 412eeda78dc9de1186c2e0e1526764af82ab3431.nq.gz
    ├── 417955f643a33552069aa8fd1987918ecf90a224.nq.gz
    ├── 41f7fcfbaf925fdf7a1d1f8e3e2a2527b9f77e99.nq.gz
    ├── 4209ca54e01c322d5aa4b4445fdd50c8e2ba9684.nq.gz
    ├── 425d14c893123984c3a87110acafa2b4c027dd09.nq.gz
    ├── 42619190635a5fe5327d39319a0690080a28ed56.nq.gz
    ├── 42a39e64189391450600b1ccd5937bec3be86543.nq.gz
    ├── 447c3b56a61a277776ea0511f2ce7aa7a0295ae5.nq.gz
    ├── 46277d7959fc089ca92ec3456d5b189b732b3227.nq.gz
    ├── 47f95daaaa2b46bcbad8295e2f338c23ab662870.nq.gz
    ├── 496af2768c23d0632f47595175930f76fbd1af5e.nq.gz
    ├── 49f72528c91e3416d8db0bda38010006fde3f3ee.nq.gz
    ├── 4a6dd1004bd7918c72e6e994ad3e0617c3d229f3.nq.gz
    ├── 4b9a3597c93da519ad5c03c061dd514c353668b5.nq.gz
    ├── 4c03fa6bb21496873cc90e5442f89905c95e7316.nq.gz
    ├── 4dd94cde2797c20e6b1f25b136104c1f85670b7a.nq.gz
    ├── 4e1b1382df8f8dcfe29c7a20ff6cce2798186f4a.nq.gz
    ├── 4e28b16f20819d42194744da9d6f6d8b2d4a3ef5.nq.gz
    ├── 4edd59f5d9c47aa27d233a7ddf1ce40d1ef33012.nq.gz
    ├── 4fb847f1ee68eb5d3ed44eee2838efcdabc61ec8.nq.gz
    ├── 516ce8e4a7fca9e24af20695d573dd8859a045bb.nq.gz
    ├── 5186b78d5a57debd9c2a21b5eb96236c4aad2b70.nq.gz
    ├── 519a3f047d3de8bd8b4ae01458d66867610c1ac9.nq.gz
    ├── 51a9dd29b289d76e8ea777b469bc2160d53eb5df.nq.gz
    ├── 51fb4237488a1427fe29004938acae9d16b39892.nq.gz
    ├── 52634b386c7b73b4495d31baf8f9a4f1932c86d7.nq.gz
    ├── 527b33e21cdfab238b58c056fd320f9fd45cbb97.nq.gz
    ├── 53081993edfe00ebe27977819e9d95081b266ac6.nq.gz
    ├── 5354553f2fe625534dd18b471cdd44334cd1169b.nq.gz
    ├── 537ba3f4f4b828da57fa51738d055ac1d83c38ef.nq.gz
    ├── 53f140b787479e6c11f04f9d005cb03e22a30cad.nq.gz
    ├── 54c6e9f788468aeb0f31f1853a69ab76fdbcca41.nq.gz
    ├── 54e00d328e27f644860a89c89c63323234e01fbc.nq.gz
    ├── 564cbc4c6edd67937687d4995ccae3f1f914f5f2.nq.gz
    ├── 5922ca9fada09aaac37afda378ddeb0b1d21cac0.nq.gz
    ├── 598410ec5b545a3151e30bccc3a332ca61534366.nq.gz
    ├── 5a1014386b2f184275c95d3055c6b5492bdd6868.nq.gz
    ├── 5cd3c9fa212f90ce79e0d7fc2f101c2c71d2d646.nq.gz
    ├── 5cda44908283fbc4b8431dea4895d8db7b69d11a.nq.gz
    ├── 5ce33471ff6ee392cec45ec0dc20518d9a232a90.nq.gz
    ├── 5d25ac4695875f4b2c3059c95026b982b9f18e4c.nq.gz
    ├── 5e9a74edd6c4fc8bfb9c1bd66bef64bfc49caa79.nq.gz
    ├── 5f4c1f262c2b3ddc2af18640f905fd3bf4f9695d.nq.gz
    ├── 5fdec06180d1df522ad4f28d4dafcf4e73b8301d.nq.gz
    ├── 600e5f4083d529f6c95615bc76417cd114af7a0f.nq.gz
    ├── 6024d46be9ba2fae50b2667cd6a2b15900928f7b.nq.gz
    ├── 60488fc3f98b5383a370120decf24c083419c270.nq.gz
    ├── 60b1fdbf212ebad794a58a07b27827c44d77e841.nq.gz
    ├── 614a352e453b7c754f3157800bff5cc69ddf30a4.nq.gz
    ├── 623e96d3eca9ad7457089aeda3869ad655c55a29.nq.gz
    ├── 625130719013f195869881a36dcb8d2b14d64d1e.nq.gz
    ├── 641db6b6c47555ca864a68945b8c7855651f476c.nq.gz
    ├── 64d2242d6434377e256192824658a76dfb231400.nq.gz
    ├── 64d6c3cb4de2de505f275d1713e9ed5fbb4d9152.nq.gz
    ├── 65b8f5611259532a7e17cfc1c42711006d767fce.nq.gz
    ├── 65f2fab29a7e6abd4b039369195dc8d8d586b71f.nq.gz
    ├── 674d71e89ea154dbe2e3cd032821c22b39e8fd68.nq.gz
    ├── 678aa063f132e325c8cfc07a867191bcc50bb929.nq.gz
    ├── 68c597d0f9d0152f51240a2e832087357589f679.nq.gz
    ├── 68ffd50587306574eaf5b3f5da82066a551848f0.nq.gz
    ├── 6a8fbcc506f9bd8285be2355a846f2edb07933ab.nq.gz
    ├── 6af30d0610a8299c84686658cdcfb5d1b4d73343.nq.gz
    ├── 6ba3164535127d6f88e708a73c943c6eba4b4475.nq.gz
    ├── 6bd27e894f74f7640a779066d652e32e899b44ab.nq.gz
    ├── 6bf86eb55e592080110f6ea15c559c063ce44b74.nq.gz
    ├── 6c5bf37a2345e05f43e2d58ae47cf7ed2025b706.nq.gz
    ├── 6d2e395cc05183961798863d5f5fe4b2b0f747fe.nq.gz
    ├── 6fe3edfe5aec866c90977095cc1dc59be0b8abd3.nq.gz
    ├── 6fec242c8fb2dd0f51de6aedbc1e13016e21a5fb.nq.gz
    ├── 715cec75c6560fb5dc6d047a81e212009d0c5c7d.nq.gz
    ├── 74707fe5692551e20e1a0dcd3b8d34fbb5829046.nq.gz
    ├── 755c2f597f83c658be35343d83adb83735c9712d.nq.gz
    ├── 7570221505193ef3107ee18bd4ee8c08b02703c7.nq.gz
    ├── 75b52484ea471f882c29e02693b4f02dba175b5e.nq.gz
    ├── 76492cdaf5c0f542ae132158c5553c0bf261e4c2.nq.gz
    ├── 77644be16212e1736e9b4c8615a155b33ba600aa.nq.gz
    ├── 779861ed6633736db31e3414e0c2f696df5d9b4b.nq.gz
    ├── 77e11b78c816d400f3ec53ff9df3f74a3a796c5e.nq.gz
    ├── 78e47ae07b0abf7348eb4486308285e021d550fc.nq.gz
    ├── 795200dc5d66cb4f48b62f475ab46613906db700.nq.gz
    ├── 79bc81add093c74d04b2aaa6783d4a0098e1ef5f.nq.gz
    ├── 7c34fca03b77c412825346531dce351149fa7fa5.nq.gz
    ├── 7cc83914ff0db4a8d1036a3b63313e54973ed71b.nq.gz
    ├── 7ccc6dbcba99a5d78691df271477d0145ae9732a.nq.gz
    ├── 7cecc5502c2b54835e1ab3af5213ad40d5cce765.nq.gz
    ├── 7db5cb7dd004dd536d16f23cd87b028354a5f3fe.nq.gz
    ├── 7e1550660cc87c36d33f0ce129f8e4e1420b536d.nq.gz
    ├── 7e73923cfb5de1f54f2f9cb4802cc73bae315ba8.nq.gz
    ├── 7ee8baa8c3c4dd6d4b376ce257842c534f2afa4d.nq.gz
    ├── 7effe21d1e114d77240a3625bd1573d2a1ddfcb4.nq.gz
    ├── 7f0fae16264fb3d4ef3bf9a5214cd4324274acb8.nq.gz
    ├── 81723c0c4ea1dda26f48f7811dcfc5381b992a56.nq.gz
    ├── 8187e7e06a47da53f5769f71b0ec80295ab9998b.nq.gz
    ├── 8330659631118105ac187c001645297226018f9c.nq.gz
    ├── 8367d5081fecbbce8305a8036b5dcc073aef32a4.nq.gz
    ├── 83e087419f5d2af8cd435953121e891c378e9e44.nq.gz
    └── 846a56e848b4fdcf5189ce8b828d10a1967b4357.nq.gz

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
*Parsed on 2026-03-29 by [repolex](https://repolex.ai)*
