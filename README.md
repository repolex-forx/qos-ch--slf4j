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
│   │   ├── 03aa6b915a82a037d2936ca0b166626d32e9a1f6.nq.gz
│   │   ├── 04a8c2c2cf42307e655ce14872c6bcecefc3babc.nq.gz
│   │   ├── 197f49ee9b6a44c8cce36bbac315089f6e1d10c4.nq.gz
│   │   ├── 1f162bac5673555875d57e9373ab48785882bf0f.nq.gz
│   │   ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│   │   ├── 46cf4f7fedf92ebe69efb28d7032086094b47403.nq.gz
│   │   ├── 58e6b11530ab61312326b4d5f4bf43900797d650.nq.gz
│   │   ├── 5fd428e3dd03ed4c1cd7b436fb0531a4315a5108.nq.gz
│   │   ├── 6294c5d678b77b91b60ecc727ad43c263c658be6.nq.gz
│   │   ├── 70d3d276cb14f4792714c99d9660f1e69b4c3a93.nq.gz
│   │   ├── 97897bfee1be0534669223b2bb8c5d37b927971a.nq.gz
│   │   ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│   │   ├── aec79d97acacb680a1a611aa134c50dd6a3014af.nq.gz
│   │   ├── b1d03d5ce82626fbc2e4b5ad13f8e92128b18038.nq.gz
│   │   ├── cea955f6bb87430c1d213e10bdb65d73752e8c9d.nq.gz
│   │   ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   │   ├── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│   │   ├── dda38e5fba4f6c2a12df868b23df3525f45f0bf1.nq.gz
│   │   └── ee8c513c6886c95e799f7403ef206ea91eb3099d.nq.gz
│   ├── lsp
│   │   ├── 03aa6b915a82a037d2936ca0b166626d32e9a1f6.nq.gz
│   │   ├── 04a8c2c2cf42307e655ce14872c6bcecefc3babc.nq.gz
│   │   ├── 197f49ee9b6a44c8cce36bbac315089f6e1d10c4.nq.gz
│   │   ├── 1f162bac5673555875d57e9373ab48785882bf0f.nq.gz
│   │   ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│   │   ├── 46cf4f7fedf92ebe69efb28d7032086094b47403.nq.gz
│   │   ├── 58e6b11530ab61312326b4d5f4bf43900797d650.nq.gz
│   │   ├── 5fd428e3dd03ed4c1cd7b436fb0531a4315a5108.nq.gz
│   │   ├── 6294c5d678b77b91b60ecc727ad43c263c658be6.nq.gz
│   │   ├── 70d3d276cb14f4792714c99d9660f1e69b4c3a93.nq.gz
│   │   ├── 97897bfee1be0534669223b2bb8c5d37b927971a.nq.gz
│   │   ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│   │   ├── aec79d97acacb680a1a611aa134c50dd6a3014af.nq.gz
│   │   ├── b1d03d5ce82626fbc2e4b5ad13f8e92128b18038.nq.gz
│   │   ├── cea955f6bb87430c1d213e10bdb65d73752e8c9d.nq.gz
│   │   ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│   │   ├── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│   │   ├── dda38e5fba4f6c2a12df868b23df3525f45f0bf1.nq.gz
│   │   └── ee8c513c6886c95e799f7403ef206ea91eb3099d.nq.gz
│   └── repolex
│       ├── 03aa6b915a82a037d2936ca0b166626d32e9a1f6.nq.gz
│       ├── 04a8c2c2cf42307e655ce14872c6bcecefc3babc.nq.gz
│       ├── 197f49ee9b6a44c8cce36bbac315089f6e1d10c4.nq.gz
│       ├── 1f162bac5673555875d57e9373ab48785882bf0f.nq.gz
│       ├── 26292f91bcb674b9d3a866b889f431268ada1217.nq.gz
│       ├── 46cf4f7fedf92ebe69efb28d7032086094b47403.nq.gz
│       ├── 58e6b11530ab61312326b4d5f4bf43900797d650.nq.gz
│       ├── 5fd428e3dd03ed4c1cd7b436fb0531a4315a5108.nq.gz
│       ├── 6294c5d678b77b91b60ecc727ad43c263c658be6.nq.gz
│       ├── 70d3d276cb14f4792714c99d9660f1e69b4c3a93.nq.gz
│       ├── 97897bfee1be0534669223b2bb8c5d37b927971a.nq.gz
│       ├── a8f066010596dcbef1291b14353ca5e3fc190bd7.nq.gz
│       ├── aec79d97acacb680a1a611aa134c50dd6a3014af.nq.gz
│       ├── b1d03d5ce82626fbc2e4b5ad13f8e92128b18038.nq.gz
│       ├── cea955f6bb87430c1d213e10bdb65d73752e8c9d.nq.gz
│       ├── d0fe6310eb4f1e9cb306b6934a3e7aee0feef46b.nq.gz
│       ├── d8eadb09a11dbdfc8e35042178582e48b50c2405.nq.gz
│       ├── dda38e5fba4f6c2a12df868b23df3525f45f0bf1.nq.gz
│       └── ee8c513c6886c95e799f7403ef206ea91eb3099d.nq.gz
└── blob
    ├── 0013471f2eef41620b240f5385219291a7097ea2.nq.gz
    ├── 0070c7efb2ac2818ea84404d6f0c5efcd861360d.nq.gz
    ├── 00975da27eebdecd4d0c50b09703c7cdab2cd7e8.nq.gz
    ├── 009e67073154351fdf559110b167c9f397606cab.nq.gz
    ├── 00bf176f39101797db21db3c87d8afcde82e1a29.nq.gz
    ├── 00f59f7feca8c8e2110aef18ca69d6959fe3b3e1.nq.gz
    ├── 012d438aab9c143e6935ae43bc01a6863fea0024.nq.gz
    ├── 013468b23d30e06aaf666b34f33cd348eaed93d4.nq.gz
    ├── 01714c835670ef6a2242e254b0a59f06958949bb.nq.gz
    ├── 019764a34072d2c295c2d82959742b0e9f56d988.nq.gz
    ├── 02064c24798992fba54f964535aa11c474a82ffc.nq.gz
    ├── 024a7f821f5df73452c10425dea55083c7aa3bda.nq.gz
    ├── 0270e4180dd00b6e870d8011b1be1dd6194364c5.nq.gz
    ├── 02817079e00932485de62bb2b0e02028fac65033.nq.gz
    ├── 0287538fb221b255cf4617deddef49e1fc6d17f4.nq.gz
    ├── 02afa8756a358fc0ff697809c83e343e1f784abf.nq.gz
    ├── 02b1ba3f6c62a91cb6d846d1aec4bd757260b7a3.nq.gz
    ├── 02ca550238bb73c6c6e3585be24d14760444aec4.nq.gz
    ├── 02d28cdfd62577f4f4030a5986ee8210b7161d41.nq.gz
    ├── 02f110b26d5d8972648ec786581397a833b7e5a1.nq.gz
    ├── 032bddcaa3b962a6c1b4c20cf9b01a773586f209.nq.gz
    ├── 03543caa2bb5f194893d6711c2092ec0b7c8202f.nq.gz
    ├── 036dd716aa4f16b20b2adc5858990f942e4b2d73.nq.gz
    ├── 0374629ec1348ed5d892bc2afb9104b459b6e309.nq.gz
    ├── 037bccafb28206266e7f2de78b6be23811d2e207.nq.gz
    ├── 039a9992c65b55280428b4b10687ebdde2b7b379.nq.gz
    ├── 03caaddaa9a1b56ed77f210ee2d0c630e4d6c55d.nq.gz
    ├── 03f2a7be8bb8094ebd965446d14b6ead737b553d.nq.gz
    ├── 04452d4987fba08accb137ba30e8f5a62878abb0.nq.gz
    ├── 044b0cb045924575fae81ba465eb8c08b816edbd.nq.gz
    ├── 045f60bf07cb2bcae8d542a2db9a439992048ed2.nq.gz
    ├── 046786e8fde6e90c412b4a8f361871cc620fb2e8.nq.gz
    ├── 0490c5e9569b0d9f55fd5e8d96035e60d30f16db.nq.gz
    ├── 04ce57d4c4b61a6eeb1c0cf54dfaef864614d07c.nq.gz
    ├── 0502ffad2b72f3d45ebf3befab2329a67e9fcbc2.nq.gz
    ├── 0523e5abecdc52c21fa553fe5d414d751d34ac16.nq.gz
    ├── 0565aa66d5000dcfae57b8f632e43d1a6d767ca8.nq.gz
    ├── 0594147775b29a1b26d2243d74d285ed37ee2a7c.nq.gz
    ├── 05d5a97583c73d9927c792a874fa5755370fb8e9.nq.gz
    ├── 06233ac87b0833ce44cefff9ac0c24b39b2abdbd.nq.gz
    ├── 0626b871b415a5b4869b7a0c4c5acf0658859b7a.nq.gz
    ├── 065cba6c3d050f09defa2d33f72af8b2ea00fe81.nq.gz
    ├── 068452690b9ed8645cb969056b9830561a78ec65.nq.gz
    ├── 06b0ec58bf452a44c17b763d4f0eab23a853efb2.nq.gz
    ├── 06ca2017eb64e35a561dfc940dcd1563fd7d02e5.nq.gz
    ├── 06d19f9aaab39ab9804ab0afb34329b8d8349e33.nq.gz
    ├── 06d1daa7d357415cc8b1714257571f03afe9a229.nq.gz
    ├── 06e31e93954d2898e6f2bf6e173c226457432921.nq.gz
    ├── 0705ec215881aedd931dbb3c25d5ade490c4b62c.nq.gz
    ├── 072189e7dba5d2da4d5ddd4341974540c4969fab.nq.gz
    ├── 0738092d69c088f57d14d1da12bae11d4f234bf2.nq.gz
    ├── 0741da7f24eef153529a2fbdbcd23619b1b7a68f.nq.gz
    ├── 07947e8a3b6034838a6ab49c6fefa8a87cea9575.nq.gz
    ├── 07bfb4e73754143ca8595b44f7156ffbefda8df4.nq.gz
    ├── 07eb0d558d67c453f3a96e2a39d0aa40cb6e39f4.nq.gz
    ├── 07f98f61186895257a218813e12a9d4e97d3dbec.nq.gz
    ├── 07fe5df77db457399b2cb3bad2b15574bfb1c8d0.nq.gz
    ├── 080c693641c92f5fa817f9a3eb5018255d86b634.nq.gz
    ├── 08183ab0abd061cf05722bd4baa72adaf5e7e38c.nq.gz
    ├── 083b9631cee07e095f12b0da105b3abdd5b18460.nq.gz
    ├── 083ce2767c222e75d71707991b92f767c0a43846.nq.gz
    ├── 08686edfa75c9d93c7793191b40d831dff2acb1a.nq.gz
    ├── 086e0eabe35b4473a215113f7f73a7b55411e102.nq.gz
    ├── 087016c959ab80194dc30d3e1ebd5edfe3580813.nq.gz
    ├── 087364a34f501c35796847041a50bfb875523d32.nq.gz
    ├── 08eebca94d62e7d00e062ae2981270a3602d478d.nq.gz
    ├── 08f33e9d151ce894a46c69e9320b5db27a71f954.nq.gz
    ├── 08f4f8ffe227babdc1cd11b689d93fbbcfa56cdd.nq.gz
    ├── 0921b988ea552a09b8a29a929b78eedecdd8c299.nq.gz
    ├── 095ab13b561615b804e2de8891f0076af2f73693.nq.gz
    ├── 0979380c8db61c061d38dd7570dc7c84339c7a1e.nq.gz
    ├── 09b3a03ff70395aae27d241a10e04820dc90e901.nq.gz
    ├── 0a27840a28436799f568a479aa36a74ea1945b54.nq.gz
    ├── 0a7f1310dfdac8aa9df7638f53d580b68e3178a7.nq.gz
    ├── 0a9171c76dd599f0fdc389206e88f24aaf19d0cc.nq.gz
    ├── 0a9194df96f540cd30f9859127414c2ad4a1d5d5.nq.gz
    ├── 0abf0721e2605438791becaec6b1974d82a34d5c.nq.gz
    ├── 0aca814e762c8f63e675b6a531dd15e03c20a292.nq.gz
    ├── 0ada760a3bd27f9f88f3ba4ee6b7116856d636d4.nq.gz
    ├── 0b02a0881c5f050fdd82e01e5352bcd0d45852ae.nq.gz
    ├── 0b15d6ff1020ca991c24abd23cb9179c3a78029c.nq.gz
    ├── 0b5607a52e494755dc35ab2a69fa9cdb9d80d013.nq.gz
    ├── 0b608b60848300a8d3d31ec39c2c6ca90399f4aa.nq.gz
    ├── 0b67214c2a8df22c21a0273c28966fe64494c47a.nq.gz
    ├── 0baa4099827083ae352166e7b0d90127dc897e4d.nq.gz
    ├── 0c1b9037d5e5ef9db77230cc723c78f94a73f0ff.nq.gz
    ├── 0c2b780d55d8693a53ef52b07e1d450fd39404fc.nq.gz
    ├── 0c6920a2e000166499805692c6f2d73bbb8bd0fe.nq.gz
    ├── 0c6c460cee4059a0411cee911695aa77fda5cce1.nq.gz
    ├── 0c890fc9bf097e8b4b88f487d0d22055e8551883.nq.gz
    ├── 0c9142ac461d427dc5370bbecb311512f7ac6e9c.nq.gz
    ├── 0c962c9e058260f996c033b2fd1f49f542198810.nq.gz
    ├── 0caaf810353b2006ba69ed23540f2c89343abfd2.nq.gz
    ├── 0cb3c1f800cd7bae3ba344d439bac8b83cbf0ee5.nq.gz
    ├── 0d0f5d5fee061694b632e28644bb738e199e66aa.nq.gz
    ├── 0d4e7607a046b2054555a2fb04ce5f04a775e199.nq.gz
    ├── 0d8f767ffbd2ecef9ad358990d76927d509d82fb.nq.gz
    ├── 0df11c8e7d291361a97cf9f446275706c75610af.nq.gz
    ├── 0e3ebde484610ed65868d8732d0998bf329a9eeb.nq.gz
    ├── 0e5ac531e0adf3c39a67a0f427a9bc3ab4bb3027.nq.gz
    ├── 0e6a8c3f4c56ed55ce8ed77e9e7efb53729c5b37.nq.gz
    ├── 0e75e4d7a4fb99cf159277b297aec697137fd0d6.nq.gz
    ├── 0e8d13c8149ef664750606025d4f88a31102b6f3.nq.gz
    ├── 0e9077a765b102fda04378f2e93f39315808da38.nq.gz
    ├── 0eb5e614a7f3f139c49212cd5836a88b771de63f.nq.gz
    ├── 0ecce2ca1eae69beda7cf05ddefcab2fc0ec345e.nq.gz
    ├── 0f008bfa47ac250ec845d11a978088b13850896e.nq.gz
    ├── 0f1ccaff12ea5f2c5d0a84476bd1942be6b15dfb.nq.gz
    ├── 0f60628db1ca5f93a5cabeb3601fd6e0542abe7a.nq.gz
    ├── 0f64802dcdc31a8510915d56dacaead3d7b2c829.nq.gz
    ├── 0f6b680f467cbdbd464805a12a2b0407987c968d.nq.gz
    ├── 0f8f8233f55d2e782b444b22c8720b419da91803.nq.gz
    ├── 0f925ad071e35b8ff66896485587bc202fcd386b.nq.gz
    ├── 0fa8c4971e8f409198ca91be9d7fa5f1683805ee.nq.gz
    ├── 0fbb26a106c703049dfb6e99d92fc3c129ad1d49.nq.gz
    ├── 0fbd019fedbdbd42c4ea9557ac431f79cea02fde.nq.gz
    ├── 0fbd62aed603ec2fb2ac90476ec0a54e6e3d837b.nq.gz
    ├── 0fcd4fb34249e72cc026930e3f8cc71d3a533cc7.nq.gz
    ├── 0fd8f010848fdefa71405cd8b4c1b2e7a7e1917f.nq.gz
    ├── 0fea54ffa86b29cbfff51aa55159f3a943eb9087.nq.gz
    ├── 0ff3d6a066ad5622b973162aed44105f78d54f7d.nq.gz
    ├── 101a6a4fab82b0f3e2f55bf7403c078b2e9ff054.nq.gz
    ├── 109970552f41c43ff4d1152593b24cca6061a3d0.nq.gz
    ├── 10c11706ef24a4af4ad2294882e50197a9443a3b.nq.gz
    ├── 10d04448141e18d2c18d8cfb648255f16aa52df3.nq.gz
    ├── 10d4f5405e80ccc88f9ed77bb3917dcb0a4f3afd.nq.gz
    ├── 10dff936db91d66ba3acdcd79c5dddaf7fe125e8.nq.gz
    ├── 10e0a07c0f89dba4845e798c73ed0347afed1b8b.nq.gz
    ├── 10f5bdf340ff404904e1f0b897ddc1b06fb3e145.nq.gz
    ├── 1144e0ccf0ba95a066848981af1c5f2559809d44.nq.gz
    ├── 118216c50860cf09220a5b67ff659f2913ba6218.nq.gz
    ├── 118ac8dd5b05387369bbdd1add4988ed08561e92.nq.gz
    ├── 1194ceb4a5190f9537294044d0d87e56271ff7c0.nq.gz
    ├── 11a81b533552c82a0f75aa66bbabb52263825c94.nq.gz
    ├── 120fa94144f11b0422c9566fb67821a06b3a359d.nq.gz
    ├── 1210c675e97c96092054273b1cd47384e74133e7.nq.gz
    ├── 1229d2e94a41b754f443ede4a8b25933eb7bc97d.nq.gz
    ├── 1257f79c2e43c9752b8e728e735c2b0013633825.nq.gz
    ├── 12989b9db057a6a3510680f6ec3ad5d2e61dbcf3.nq.gz
    ├── 12a49b8611aa47269b53ac1780ac289b7962052d.nq.gz
    ├── 12d6db1903d539698ec9e8819d82b79efb3f5516.nq.gz
    ├── 13c433fa5cadd88441c7db1f8ac3d71e30caed12.nq.gz
    └── 13da1b4014dd196f5267101653fefb3142049d4e.nq.gz

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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
