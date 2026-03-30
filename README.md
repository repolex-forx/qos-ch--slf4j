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
│   │   ├── 04a8c2c2cf42307e655ce14872c6bcecefc3babc.nq.gz
│   │   ├── 197f49ee9b6a44c8cce36bbac315089f6e1d10c4.nq.gz
│   │   ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│   │   ├── 5fd428e3dd03ed4c1cd7b436fb0531a4315a5108.nq.gz
│   │   ├── 97897bfee1be0534669223b2bb8c5d37b927971a.nq.gz
│   │   ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│   │   ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   │   ├── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│   │   └── ee8c513c6886c95e799f7403ef206ea91eb3099d.nq.gz
│   ├── lsp
│   │   ├── 04a8c2c2cf42307e655ce14872c6bcecefc3babc.nq.gz
│   │   ├── 197f49ee9b6a44c8cce36bbac315089f6e1d10c4.nq.gz
│   │   ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│   │   ├── 5fd428e3dd03ed4c1cd7b436fb0531a4315a5108.nq.gz
│   │   ├── 97897bfee1be0534669223b2bb8c5d37b927971a.nq.gz
│   │   ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│   │   ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   │   ├── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│   │   └── ee8c513c6886c95e799f7403ef206ea91eb3099d.nq.gz
│   └── repolex
│       ├── 04a8c2c2cf42307e655ce14872c6bcecefc3babc.nq.gz
│       ├── 197f49ee9b6a44c8cce36bbac315089f6e1d10c4.nq.gz
│       ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│       ├── 5fd428e3dd03ed4c1cd7b436fb0531a4315a5108.nq.gz
│       ├── 97897bfee1be0534669223b2bb8c5d37b927971a.nq.gz
│       ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│       ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│       ├── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│       └── ee8c513c6886c95e799f7403ef206ea91eb3099d.nq.gz
└── blob
    ├── 0070c7efb2ac2818ea84404d6f0c5efcd861360d.nq.gz
    ├── 00bf176f39101797db21db3c87d8afcde82e1a29.nq.gz
    ├── 012d438aab9c143e6935ae43bc01a6863fea0024.nq.gz
    ├── 013468b23d30e06aaf666b34f33cd348eaed93d4.nq.gz
    ├── 01714c835670ef6a2242e254b0a59f06958949bb.nq.gz
    ├── 019764a34072d2c295c2d82959742b0e9f56d988.nq.gz
    ├── 02064c24798992fba54f964535aa11c474a82ffc.nq.gz
    ├── 0270e4180dd00b6e870d8011b1be1dd6194364c5.nq.gz
    ├── 02b1ba3f6c62a91cb6d846d1aec4bd757260b7a3.nq.gz
    ├── 02ca550238bb73c6c6e3585be24d14760444aec4.nq.gz
    ├── 02d28cdfd62577f4f4030a5986ee8210b7161d41.nq.gz
    ├── 032bddcaa3b962a6c1b4c20cf9b01a773586f209.nq.gz
    ├── 036dd716aa4f16b20b2adc5858990f942e4b2d73.nq.gz
    ├── 0374629ec1348ed5d892bc2afb9104b459b6e309.nq.gz
    ├── 039a9992c65b55280428b4b10687ebdde2b7b379.nq.gz
    ├── 03caaddaa9a1b56ed77f210ee2d0c630e4d6c55d.nq.gz
    ├── 03f2a7be8bb8094ebd965446d14b6ead737b553d.nq.gz
    ├── 045f60bf07cb2bcae8d542a2db9a439992048ed2.nq.gz
    ├── 0565aa66d5000dcfae57b8f632e43d1a6d767ca8.nq.gz
    ├── 0594147775b29a1b26d2243d74d285ed37ee2a7c.nq.gz
    ├── 06233ac87b0833ce44cefff9ac0c24b39b2abdbd.nq.gz
    ├── 0626b871b415a5b4869b7a0c4c5acf0658859b7a.nq.gz
    ├── 065cba6c3d050f09defa2d33f72af8b2ea00fe81.nq.gz
    ├── 068452690b9ed8645cb969056b9830561a78ec65.nq.gz
    ├── 06b0ec58bf452a44c17b763d4f0eab23a853efb2.nq.gz
    ├── 06ca2017eb64e35a561dfc940dcd1563fd7d02e5.nq.gz
    ├── 06e31e93954d2898e6f2bf6e173c226457432921.nq.gz
    ├── 072189e7dba5d2da4d5ddd4341974540c4969fab.nq.gz
    ├── 0741da7f24eef153529a2fbdbcd23619b1b7a68f.nq.gz
    ├── 07947e8a3b6034838a6ab49c6fefa8a87cea9575.nq.gz
    ├── 07bfb4e73754143ca8595b44f7156ffbefda8df4.nq.gz
    ├── 07fe5df77db457399b2cb3bad2b15574bfb1c8d0.nq.gz
    ├── 080c693641c92f5fa817f9a3eb5018255d86b634.nq.gz
    ├── 08183ab0abd061cf05722bd4baa72adaf5e7e38c.nq.gz
    ├── 083ce2767c222e75d71707991b92f767c0a43846.nq.gz
    ├── 08686edfa75c9d93c7793191b40d831dff2acb1a.nq.gz
    ├── 086e0eabe35b4473a215113f7f73a7b55411e102.nq.gz
    ├── 087016c959ab80194dc30d3e1ebd5edfe3580813.nq.gz
    ├── 08eebca94d62e7d00e062ae2981270a3602d478d.nq.gz
    ├── 08f33e9d151ce894a46c69e9320b5db27a71f954.nq.gz
    ├── 0979380c8db61c061d38dd7570dc7c84339c7a1e.nq.gz
    ├── 09b3a03ff70395aae27d241a10e04820dc90e901.nq.gz
    ├── 0a7f1310dfdac8aa9df7638f53d580b68e3178a7.nq.gz
    ├── 0a9171c76dd599f0fdc389206e88f24aaf19d0cc.nq.gz
    ├── 0a9194df96f540cd30f9859127414c2ad4a1d5d5.nq.gz
    ├── 0abf0721e2605438791becaec6b1974d82a34d5c.nq.gz
    ├── 0aca814e762c8f63e675b6a531dd15e03c20a292.nq.gz
    ├── 0b02a0881c5f050fdd82e01e5352bcd0d45852ae.nq.gz
    ├── 0b15d6ff1020ca991c24abd23cb9179c3a78029c.nq.gz
    ├── 0b5607a52e494755dc35ab2a69fa9cdb9d80d013.nq.gz
    ├── 0b67214c2a8df22c21a0273c28966fe64494c47a.nq.gz
    ├── 0baa4099827083ae352166e7b0d90127dc897e4d.nq.gz
    ├── 0c1b9037d5e5ef9db77230cc723c78f94a73f0ff.nq.gz
    ├── 0c2b780d55d8693a53ef52b07e1d450fd39404fc.nq.gz
    ├── 0c6920a2e000166499805692c6f2d73bbb8bd0fe.nq.gz
    ├── 0c6c460cee4059a0411cee911695aa77fda5cce1.nq.gz
    ├── 0c890fc9bf097e8b4b88f487d0d22055e8551883.nq.gz
    ├── 0c962c9e058260f996c033b2fd1f49f542198810.nq.gz
    ├── 0caaf810353b2006ba69ed23540f2c89343abfd2.nq.gz
    ├── 0cb3c1f800cd7bae3ba344d439bac8b83cbf0ee5.nq.gz
    ├── 0d8f767ffbd2ecef9ad358990d76927d509d82fb.nq.gz
    ├── 0e3ebde484610ed65868d8732d0998bf329a9eeb.nq.gz
    ├── 0e6a8c3f4c56ed55ce8ed77e9e7efb53729c5b37.nq.gz
    ├── 0e8d13c8149ef664750606025d4f88a31102b6f3.nq.gz
    ├── 0e9077a765b102fda04378f2e93f39315808da38.nq.gz
    ├── 0f008bfa47ac250ec845d11a978088b13850896e.nq.gz
    ├── 0f1ccaff12ea5f2c5d0a84476bd1942be6b15dfb.nq.gz
    ├── 0f60628db1ca5f93a5cabeb3601fd6e0542abe7a.nq.gz
    ├── 0f64802dcdc31a8510915d56dacaead3d7b2c829.nq.gz
    ├── 0f6b680f467cbdbd464805a12a2b0407987c968d.nq.gz
    ├── 0f8f8233f55d2e782b444b22c8720b419da91803.nq.gz
    ├── 0fa8c4971e8f409198ca91be9d7fa5f1683805ee.nq.gz
    ├── 0fbb26a106c703049dfb6e99d92fc3c129ad1d49.nq.gz
    ├── 0fbd62aed603ec2fb2ac90476ec0a54e6e3d837b.nq.gz
    ├── 0fcd4fb34249e72cc026930e3f8cc71d3a533cc7.nq.gz
    ├── 0fea54ffa86b29cbfff51aa55159f3a943eb9087.nq.gz
    ├── 0ff3d6a066ad5622b973162aed44105f78d54f7d.nq.gz
    ├── 109970552f41c43ff4d1152593b24cca6061a3d0.nq.gz
    ├── 10c11706ef24a4af4ad2294882e50197a9443a3b.nq.gz
    ├── 10dff936db91d66ba3acdcd79c5dddaf7fe125e8.nq.gz
    ├── 10f5bdf340ff404904e1f0b897ddc1b06fb3e145.nq.gz
    ├── 1194ceb4a5190f9537294044d0d87e56271ff7c0.nq.gz
    ├── 11a81b533552c82a0f75aa66bbabb52263825c94.nq.gz
    ├── 120fa94144f11b0422c9566fb67821a06b3a359d.nq.gz
    ├── 1229d2e94a41b754f443ede4a8b25933eb7bc97d.nq.gz
    ├── 1257f79c2e43c9752b8e728e735c2b0013633825.nq.gz
    ├── 12989b9db057a6a3510680f6ec3ad5d2e61dbcf3.nq.gz
    ├── 12a49b8611aa47269b53ac1780ac289b7962052d.nq.gz
    ├── 12d6db1903d539698ec9e8819d82b79efb3f5516.nq.gz
    ├── 13eb941060c469d79c48dab9ac5c78a48342bff4.nq.gz
    ├── 150ef8c93a37b6b48e94c03f6488ab57bd829301.nq.gz
    ├── 1522e40494a244be6ecd2fcfda4aa0f486adb5ce.nq.gz
    ├── 1552a824e118d2010254ca31b73394da4ca9d157.nq.gz
    ├── 158ff16696072dd13232fbcb4ca4623e7f804225.nq.gz
    ├── 15ca876cacaf1bc38ea9d4a8bd36eec727f048d0.nq.gz
    ├── 16194f772040020b91f35e9526ae5c6cfc0e6a9a.nq.gz
    ├── 161cbf3f62bbf3bb4ecba87d6f757c76deb3fd22.nq.gz
    ├── 16c1bc4014aa7e6456a31795b66fc0be698eff95.nq.gz
    ├── 17560015d3a42a502f460e8cb71180c0e17b8507.nq.gz
    ├── 175dd51c6c109e84b14389acf3ba7740fa5eeae4.nq.gz
    ├── 1815225ea1170eae638f98e001b88ba754ef480c.nq.gz
    ├── 182ce58caa37acd45f41d0fc6f49d47b314261fd.nq.gz
    ├── 18731b73ca65905360a95282825f43c5fb1f72bd.nq.gz
    ├── 18dbb1166a33604b29808d62ec560c7ee14045d1.nq.gz
    ├── 19254f53c06b3c1d4a1c719e863b6d2e1b12b6ec.nq.gz
    ├── 194f152409b808cb7fb219205aed3a27b82621a7.nq.gz
    ├── 198b4e9ea86a75b94a563d3c78a6b8483c6c9ff0.nq.gz
    ├── 1997426188b24adfc4e3d11a9fd240fa52e024d5.nq.gz
    ├── 1a064d476a1bab156799979cf70dbd6c4a00fcf9.nq.gz
    ├── 1a1860cb089802ec000d3164647a4b2afbe766e9.nq.gz
    ├── 1a3d053237bec66cfaee6cd674f0678a7f7d5aa2.nq.gz
    ├── 1ab1f38c0d08032f3c0623e5e34f13bb4cd7a0cf.nq.gz
    ├── 1ae143d6c1b0c4904f1b6629a4d14b730a8054e6.nq.gz
    ├── 1afd908630c498e3bf6b0427b8075146f515af27.nq.gz
    ├── 1b970643612744e9285c3b923bdc5444318f302b.nq.gz
    ├── 1bf5944fb07143e956c3be835c43b124a4f8a8c7.nq.gz
    ├── 1c0027a72cf32921fdef5b22643cc82ee8ffd2c1.nq.gz
    ├── 1c16512c24e7a22b9f9d9496724bac4587c8a260.nq.gz
    ├── 1c2ca1530530313b88c62ee1815e679e78e79e24.nq.gz
    ├── 1c93065fea50938a95eced5c6a1881e06b5d9f2e.nq.gz
    ├── 1d3c5128a5f8d76288cad6e223c47b8887ec8d06.nq.gz
    ├── 1d7903ab8ec7db056eb3bb81293564b1195567b0.nq.gz
    ├── 1de0956adf5975d8a23f775ed079cdbb75ffcf5b.nq.gz
    ├── 1e403a9153c617c95cf01c6701ab5e6b071ca95b.nq.gz
    ├── 1e40f45afb249b696c002f0a4d04ac2d5197ca93.nq.gz
    ├── 1e5206ed2bb77aae7f6839c2f85f70ed28011c91.nq.gz
    ├── 1e66de66fc711e6e53b62d438e602b661d5fce52.nq.gz
    ├── 1e6b777840b51d14a86cc7a2ea8649f76b77747b.nq.gz
    ├── 1e6f6de42b10a47295f7c62afe82aed4458409fa.nq.gz
    ├── 1ea44794e062639df801bdb8632e305f05452823.nq.gz
    ├── 1ee74fc3339eb15c7cce610180bfaa6fa876c9da.nq.gz
    ├── 1ef3c601975328c6ff777d9eb9e82251cf0dcde2.nq.gz
    ├── 1f4ef9459bcc930c518283c8353045c4773ab3fa.nq.gz
    ├── 1f5be23f12349d0a7553f448e5dea635854efed1.nq.gz
    ├── 2050adb27a7eb410395ae32514050ea73c45caff.nq.gz
    ├── 20a119afa8d647d6d4468bf791c60baaa556641d.nq.gz
    ├── 21254fc75dcad77bffde10dcab0ad5464a1f0963.nq.gz
    ├── 219d435722245d69de6838ff68e305c0f1b0e14d.nq.gz
    ├── 21b42b61cfe5ebbf6530d49dcc1f79c5ea8204ed.nq.gz
    ├── 22255fcc4d2ac8d32d3cc7b540a84b5741016fc2.nq.gz
    ├── 22669c2bfe0ed29ed54812131443abf6b77c408b.nq.gz
    ├── 22bcee955640510cf628b27ae098278c3dfded61.nq.gz
    ├── 22d16dace544202161ef7ce0803ec4a2647ba250.nq.gz
    ├── 22fee2ea7a5c6e6735d4d852adee2de69605f3bc.nq.gz
    ├── 23249a7b9b987db904c98535d4d7e06351173c43.nq.gz
    ├── 233ca8143dc7a20d84ee48d57a08e13caa20d642.nq.gz
    ├── 2360c85ee2e5da03c888e7ba0a39259e947feb92.nq.gz
    ├── 23c65dc4659bd01cccb75e02bb7d7341ea5d20ca.nq.gz
    ├── 23fbcecba526d624d8c691038ae613038aba2975.nq.gz
    ├── 241f5a5e717b7206d79f0c961b165814c5289f93.nq.gz
    ├── 243f5dd43b9d77f52d94ebaebe44ad5168c7e249.nq.gz
    ├── 2462753f1fe622bfcc9d0b360156494ba8519be0.nq.gz
    ├── 2473ae1e4cd29b571e92af326455bca1ada59a42.nq.gz
    ├── 24c9317adae03360bcd80dabdd642f6f1e4298f1.nq.gz
    ├── 251a7361e829159b61e6baf620529d85064952a5.nq.gz
    ├── 259d063ac9dfba96177b71ad81e0fb2097a2af5f.nq.gz
    ├── 25c53e618fc85aa3dbfafbc68e899842fe4509f5.nq.gz
    ├── 25f9adb15f076ac1b72bfc5a5c24ce81fcae1b72.nq.gz
    ├── 260b69b7f1d25d1f3d4b05c3a959b3f4b205cd18.nq.gz
    ├── 2617f42726ee8158a9adc124237e9d9853c7b372.nq.gz
    ├── 2643b245437413634c6660f411b3161d28c91bca.nq.gz
    ├── 264ca493cc4b375149b1a3821e0e3ce1233af199.nq.gz
    ├── 26e7a554d95ed3c86e573fe0d623020fb94c29dd.nq.gz
    ├── 27aa668aedc43789701c97621cd3bd45b6f38ca9.nq.gz
    ├── 27bdf3e276a81fc8609cdcba6bd0fb5723730d6b.nq.gz
    ├── 27c126ef7873ac814ae1f6da80f55941714e86c6.nq.gz
    ├── 27e1f49106d11e99a7bce2b2b4807cc9100d4799.nq.gz
    ├── 28b4aacfa04637b724e362f78de4cd4a4c242c64.nq.gz
    ├── 28e3dccfc61dd20acf0af445b41e6cd1c6dbe796.nq.gz
    ├── 28e645c97e27933fb2dd4950a676781ec8941dd4.nq.gz
    ├── 2979ae912056645a156a177c0d7937481b559daf.nq.gz
    ├── 29c8a46b6a7a1ad103cf6a43b8b5e7cf54d7010a.nq.gz
    └── 2a5fd548ac3ba1895eb2e52a9f6843c267313664.nq.gz

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
