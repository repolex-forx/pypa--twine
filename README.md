# Repolex Knowledge Graph of pypa/twine

RDF knowledge graph data for [pypa/twine](https://github.com/pypa/twine), parsed by [repolex](https://repolex.ai).

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
lexq download pypa/twine
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 057bd712eddfbf2526d1a7e7518aa2daa77430de.nq.gz
│   │   ├── 20c55f6d752f7920494bbcea8d5f1a5719c97d81.nq.gz
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│   │   ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   │   ├── 5c06ed2049b633fe7f0b0e27df32d2715614ab3a.nq.gz
│   │   ├── 6ba25d7e62475804a692e0ed07a91e8bdcb10061.nq.gz
│   │   ├── 6cb70f42e3583c0d79a2e2656604bc2a1ea9b599.nq.gz
│   │   ├── 6d48d9741f29810a5d617f473b39825b9f315b48.nq.gz
│   │   ├── 734816524ea01a42bb0d3e8d21582a9d73e4ba15.nq.gz
│   │   ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│   │   ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│   │   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   │   ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│   │   └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
│   ├── lsp
│   │   ├── 057bd712eddfbf2526d1a7e7518aa2daa77430de.nq.gz
│   │   ├── 20c55f6d752f7920494bbcea8d5f1a5719c97d81.nq.gz
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│   │   ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   │   ├── 5c06ed2049b633fe7f0b0e27df32d2715614ab3a.nq.gz
│   │   ├── 6ba25d7e62475804a692e0ed07a91e8bdcb10061.nq.gz
│   │   ├── 6cb70f42e3583c0d79a2e2656604bc2a1ea9b599.nq.gz
│   │   ├── 6d48d9741f29810a5d617f473b39825b9f315b48.nq.gz
│   │   ├── 734816524ea01a42bb0d3e8d21582a9d73e4ba15.nq.gz
│   │   ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│   │   ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│   │   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   │   ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│   │   └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
│   └── repolex
│       ├── 057bd712eddfbf2526d1a7e7518aa2daa77430de.nq.gz
│       ├── 20c55f6d752f7920494bbcea8d5f1a5719c97d81.nq.gz
│       ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│       ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│       ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│       ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│       ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│       ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│       ├── 5c06ed2049b633fe7f0b0e27df32d2715614ab3a.nq.gz
│       ├── 6ba25d7e62475804a692e0ed07a91e8bdcb10061.nq.gz
│       ├── 6cb70f42e3583c0d79a2e2656604bc2a1ea9b599.nq.gz
│       ├── 6d48d9741f29810a5d617f473b39825b9f315b48.nq.gz
│       ├── 734816524ea01a42bb0d3e8d21582a9d73e4ba15.nq.gz
│       ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│       ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│       ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│       ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│       └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
└── blob
    ├── 01eea0fe2f71f308e5549a45a59ada7d56695960.nq.gz
    ├── 032cc21b22bf10441f4e4db1ac666d072bd40a0e.nq.gz
    ├── 0426a882cbc807b989d468b049dcb3f9e8c55dd2.nq.gz
    ├── 04c76d47b922c5316906c7b9f2b65dc46d43a5af.nq.gz
    ├── 051b92e3ac498b15c217695e6392f587b6aa0e78.nq.gz
    ├── 062e879d452cf403db76f2f65dd3e3d1181a89cd.nq.gz
    ├── 0b78fe8980d3b32faeb09cd2c1e43ed2c7d49077.nq.gz
    ├── 0dc337cc3c93b26f91bb225b657005da8b9b56c4.nq.gz
    ├── 11e551affb61e36d61e16a41482b6dc31d93e0b0.nq.gz
    ├── 12ad867203bd8994fcc2b165f46d549bff11e753.nq.gz
    ├── 12fa3d18573d728cd90520429dfced140c73e3ce.nq.gz
    ├── 13733a75c3c69c859ecc79cedec1106710077d56.nq.gz
    ├── 13c8b85f1b22b37a96b03fecf2efe880ee9fb1a6.nq.gz
    ├── 13f8b9a6fa40a5e1f9bdf7d52cf74f6e4fd4f7a9.nq.gz
    ├── 16ab96f3f5e051f12ffc770a3163fd6629fe6d65.nq.gz
    ├── 16eece0b47289fb886e8dc3dd87ccaf8bf6394c3.nq.gz
    ├── 1733b60c45010fe1e83f033bae70039d258d58fc.nq.gz
    ├── 173ad51a617e8d4c1f38099217f33212afd2070e.nq.gz
    ├── 17e2dcf4b96bab0264bb87670ba732b178b6704a.nq.gz
    ├── 181f613c5a4a3f870bbe4e2a2e7e08d732810159.nq.gz
    ├── 18fb10f15a68e35f9572c19da05e5d91c639531d.nq.gz
    ├── 199c6fc4d13661c110487bf29f9f35864e8419b6.nq.gz
    ├── 1b0b77d4a2bdb5c28d164a0380f00e9a266eab6d.nq.gz
    ├── 1bb61ae793e03cb60e51efd489a0c0a4d3d4001f.nq.gz
    ├── 1c1ee3ea35963796a53771465b08f9285710b69f.nq.gz
    ├── 1cdda6be63049deb555de161843b083d62c20e82.nq.gz
    ├── 1d48290578e7ebe657527c4c70f2fef3fae70fb4.nq.gz
    ├── 1e57b0f534b2f3bd6d948acc222b242ad56c3892.nq.gz
    ├── 203776134f751c2c2e71594b91c82de57eb82dd1.nq.gz
    ├── 205706c83943a9ff5964260632092940be7b30bd.nq.gz
    ├── 206cf658d516f843f2d00068dc49c569f44a2d2b.nq.gz
    ├── 218a37ad866d2a68ecd94edadfca6fe882220396.nq.gz
    ├── 230e5acf441cd2efa7297326b707caa79064246b.nq.gz
    ├── 24d72c4d49b9eba889793d0e53876c09eb6c66fb.nq.gz
    ├── 254900222856aeefee774be7570338a984be96ff.nq.gz
    ├── 26331065b699191314b9343fab38afbfa2f172c5.nq.gz
    ├── 292a48c09e2c0ccfaf5318158d5283dc68472931.nq.gz
    ├── 2af1dccd32035d3ecd25581b9f17dc3b9afb281a.nq.gz
    ├── 2bd4a52766f1ccdbf51303c1d23312ee11788431.nq.gz
    ├── 2bf136e282e03586bedf1f179fe4d0225689ca70.nq.gz
    ├── 2c1c837b1f6b5b032ba7ac96e3ddb707fb5202f7.nq.gz
    ├── 2c4a6b73eddca4495a7c3b9e57937b904a021335.nq.gz
    ├── 2f0e693e4f80bc1bdaccc531ed4eea4186246194.nq.gz
    ├── 2fdc9885203f08e062cc99b12afaba93a204bb56.nq.gz
    ├── 3048666aede7d7de24cdbe006294f7915bcda698.nq.gz
    ├── 30baf96753fea5734d8913b24e2788f58e6eda8a.nq.gz
    ├── 31bdc8c7c35d9c90cff4394539290cc05305d38e.nq.gz
    ├── 32b75118182d9f85bb8b1cfe0ced9e22a8ae7176.nq.gz
    ├── 343ac29850a3ee983ce79a2a2f1c160961ac0e33.nq.gz
    ├── 344800ca75634c17064633fc1666f36ae28b027d.nq.gz
    ├── 350e944a917b8a842848578d3ab2198ac58712c2.nq.gz
    ├── 36f63cd0511d92396cf16618aaf003c56a81acd8.nq.gz
    ├── 3757a561cc5c2a0141152878dda2605f13e954ad.nq.gz
    ├── 3829f6b40e0c38adf8210d75025f01f2bfe0613a.nq.gz
    ├── 3a4b370595332818789dc5c833231084145bf35a.nq.gz
    ├── 3b8d84bb78f79e6630e2993ba64f29722fb1a178.nq.gz
    ├── 3b97a695adce46d214afa05fc15f05baf69b6296.nq.gz
    ├── 3bfd91f6482aaaae8305e8999a11345765ebb220.nq.gz
    ├── 3c9f01347eb5600a42d3e3dec8f937efecdcdd30.nq.gz
    ├── 3ce1806e9ca8ff9d8fd30ca126bd4bc6bedb3e81.nq.gz
    ├── 3d58ddf65c16e62954743b5a133528439dc15ea9.nq.gz
    ├── 3e6d75c9391f26fb9314f0a88961738c5af15a2a.nq.gz
    ├── 3e9bb010fe8ff46138ccb62b56e41edd69037d26.nq.gz
    ├── 413a4507c0600f156062d7c0b472ef1caf6c826d.nq.gz
    ├── 4212aae60a74dbb66500cc3a32341840fa6b58b7.nq.gz
    ├── 454e7f8d8594c8168d387cbe25dc231f9bc262b0.nq.gz
    ├── 466d33560fededaffec1d3d8d657cc49dcd71093.nq.gz
    ├── 46701705eeeffd52886791e9fe284ae9d1b44d4c.nq.gz
    ├── 47a12ee690260594c95191b80574917ac870b0ad.nq.gz
    ├── 48935823b877a7b0037f00c8ada7a7775a905e88.nq.gz
    ├── 49b4fdc075649452b947b73b6a49ec21ca472b2d.nq.gz
    ├── 4a34b836ff2c0ba7c0eef988a4f91a732a8e4202.nq.gz
    ├── 4ccbdca8267a9df7c776bfe73cac6b203779284d.nq.gz
    ├── 4ef01766a9a81da7ee52994c95c57c092f73c6ce.nq.gz
    ├── 4fccb0d0be7f4f2ac7833ca63f3d8a49adf61011.nq.gz
    ├── 501f11cbcdf0135329b7cab76b4eef04c92fad1e.nq.gz
    ├── 51d56b13e6f99667073277d653c127566949f997.nq.gz
    ├── 520b78ff19c8a61741c053502a32a79bea26fac5.nq.gz
    ├── 5226d941022377254104df17156c7cb3e5f40ad5.nq.gz
    ├── 526bebb113e3cf692141e141a6e0a36d6e292131.nq.gz
    ├── 53a6dc274e50ac8c8ab8f7ae6d11791baa79a487.nq.gz
    ├── 54eecb3d77ad456a52130c6e37b1fe290e1cad3f.nq.gz
    ├── 5557e40302b506760506f9634f2b129b5dd0c342.nq.gz
    ├── 55dd9a4ff837fa2a956db9fdcdb0a18826beb4dc.nq.gz
    ├── 5783a9d6de230d932fc07ff609b04072659e1a3d.nq.gz
    ├── 583444957bd084599f165d4b0da4976e4f2829a4.nq.gz
    ├── 58bfbdfba61c8e64708a7f4908283913d165b337.nq.gz
    ├── 58e0733ef97afe3501dc38c0a5b7416da83cf7a9.nq.gz
    ├── 59835499d76570dc57914588fb41043516d0c2e6.nq.gz
    ├── 59a6ebbb932124bf470be58f8e4de915c0256f57.nq.gz
    ├── 5addb5e38cf09b898b2e4797f95e84db5dc88e09.nq.gz
    ├── 5afbfea9a32b7b9ef3e9295fb95f02b806a9c5e7.nq.gz
    ├── 5cf4adadd943a7914a80c4e53db83d4b9f4100b4.nq.gz
    ├── 5d0c68c800784134d83e21a0814239727ac56460.nq.gz
    ├── 5d87025e88747fe1bdbd67554478a27d516cad6f.nq.gz
    ├── 5dd8fc5b6d5a8bc1c5cab8e3019b11ce54712361.nq.gz
    ├── 5ded5c28e525bc831b570d594356cc4b3b0234e5.nq.gz
    ├── 5e8932a78614fc897b37dea4fc4b8b1796d3ff18.nq.gz
    ├── 6053a66c053ea541f7c7e95aafa88f17dc3caec9.nq.gz
    ├── 6070c1afa3f4fd698f6e6833e4521da8ad8adcbc.nq.gz
    ├── 62261fdb4f77f7e07f56ff59408c79f3786ca24b.nq.gz
    ├── 6364e82b3cdfd7fe9b17188a2ef3f029d3d99e9f.nq.gz
    ├── 6450e252180d3de6c0e10aa92d89f3ac2b231502.nq.gz
    ├── 65c6718ede29ffd29b953c6a148b3f2d148920e2.nq.gz
    ├── 65eac375c49025310770f369bbd095e538d525a2.nq.gz
    ├── 6646c697b04ab9eee3eda380055dc67e83bc4522.nq.gz
    ├── 66503e0858c20402ede5e7d171c02880d5480013.nq.gz
    ├── 669e9966f4caeff22a61a76977d95e0ebc5d7d93.nq.gz
    ├── 67840bdd9d00a7f05c88d24ba66c47a33672b2ce.nq.gz
    ├── 67bc813564d3594243c39b164e39930de073c4dc.nq.gz
    ├── 67fec6cddcaa5342291f7fce599d59c928ad4b82.nq.gz
    ├── 68f568c4f10561401a9fe5d11af8e4e093a507c3.nq.gz
    ├── 6951070acb9f68c542b5eb8499633531a9a4f3b5.nq.gz
    ├── 69d184778ccc1948e4c562ce3a6809e6fa00caa0.nq.gz
    ├── 69de737adb23280f64c5fe8770746fd9a4fc81a8.nq.gz
    ├── 6be8cc8691f230add873e90dccfc2a83d6d14c37.nq.gz
    ├── 6c6a0e57f496a8b71650be54c03cd978ef85fe2b.nq.gz
    ├── 6ed56dd7d8c2cda75ea4f9529ad2f65a603e3651.nq.gz
    ├── 6f2ac30b47a8b0e4776f5b0cf1ee7ff2b3059bea.nq.gz
    ├── 6f7a6d9c3d740609fd09c88fbf6352a977af7c51.nq.gz
    ├── 6fd66553eacb8d7c2653053abdaf62e60c24648c.nq.gz
    ├── 70c350c6fa12105218777f1e42947bc7fcaf1c06.nq.gz
    ├── 7212db9295e001a79de517ed1cd714a66087d935.nq.gz
    ├── 7318c9929e4142a43833ae89d98d540154ec098b.nq.gz
    ├── 7338ccbfe8d3b182d3b3381cd470db8b06540c1e.nq.gz
    ├── 74456d695c377a5b01f4b271e3c3314cdcaff44b.nq.gz
    ├── 744b9eeb3e909fa79b2606e7422aa9041e678ce7.nq.gz
    ├── 74e196849dc2f49bd33fad4f8f36b7bce03331bf.nq.gz
    ├── 7542ea7b00a1490b62460aa0cba9e10275878dae.nq.gz
    ├── 754f6cea0003d89e207ccd4b5b6a1261f2afa7cf.nq.gz
    ├── 76676585450d1fc90469cf1511cc3f0c190a103d.nq.gz
    ├── 773a56d0efdadce7e28b642e473002fffd9753a4.nq.gz
    ├── 7745ebfa0ba1b25bd9fbdf2ba29a1b5ce447a45c.nq.gz
    ├── 783f3525f5e133b7af675a9069a2ef0bdb5a0e51.nq.gz
    ├── 7b15ba98911a90aee5a29d80813f41b20c8d0ef7.nq.gz
    ├── 7d87d2d9793173674de0cf601e7a1da7300c6458.nq.gz
    ├── 7e1d1f28565df1690417b1526bfbedec957acc4c.nq.gz
    ├── 7e2d30236e3e4a6804cab8b32d48f6f07ddc179f.nq.gz
    ├── 7f99510651d34e6e921799716aeb9b2b226b0674.nq.gz
    ├── 81e202f46794f078b208f1687e88de41e9d1e116.nq.gz
    ├── 822a25103fffde51fadee38eeddf931c8ca755f1.nq.gz
    ├── 83a186770f1f944613c572f02468c65557ec35b5.nq.gz
    ├── 8581c7d2bfe53ec01d5d6aa0db3eb7a34799f799.nq.gz
    ├── 85f89bf247c269c88035ffef1672af55f330a584.nq.gz
    ├── 8705fe840ca2cec1a12b392a70040a276f6949b0.nq.gz
    └── 89544e3c4beb4aec612c76d59bc816692890a4fb.nq.gz

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

[pypa/twine](https://github.com/pypa/twine)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
