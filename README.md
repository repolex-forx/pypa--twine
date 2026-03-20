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
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   └── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   ├── lsp
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   └── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   └── repolex
│       ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│       ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│       ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│       └── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
├── blob
│   ├── 01eea0fe2f71f308e5549a45a59ada7d56695960.nq.gz
│   ├── 0426a882cbc807b989d468b049dcb3f9e8c55dd2.nq.gz
│   ├── 04c76d47b922c5316906c7b9f2b65dc46d43a5af.nq.gz
│   ├── 0b78fe8980d3b32faeb09cd2c1e43ed2c7d49077.nq.gz
│   ├── 0dc337cc3c93b26f91bb225b657005da8b9b56c4.nq.gz
│   ├── 11e551affb61e36d61e16a41482b6dc31d93e0b0.nq.gz
│   ├── 12ad867203bd8994fcc2b165f46d549bff11e753.nq.gz
│   ├── 12fa3d18573d728cd90520429dfced140c73e3ce.nq.gz
│   ├── 13733a75c3c69c859ecc79cedec1106710077d56.nq.gz
│   ├── 13c8b85f1b22b37a96b03fecf2efe880ee9fb1a6.nq.gz
│   ├── 173ad51a617e8d4c1f38099217f33212afd2070e.nq.gz
│   ├── 181f613c5a4a3f870bbe4e2a2e7e08d732810159.nq.gz
│   ├── 1bb61ae793e03cb60e51efd489a0c0a4d3d4001f.nq.gz
│   ├── 1cdda6be63049deb555de161843b083d62c20e82.nq.gz
│   ├── 1e57b0f534b2f3bd6d948acc222b242ad56c3892.nq.gz
│   ├── 203776134f751c2c2e71594b91c82de57eb82dd1.nq.gz
│   ├── 205706c83943a9ff5964260632092940be7b30bd.nq.gz
│   ├── 206cf658d516f843f2d00068dc49c569f44a2d2b.nq.gz
│   ├── 218a37ad866d2a68ecd94edadfca6fe882220396.nq.gz
│   ├── 26331065b699191314b9343fab38afbfa2f172c5.nq.gz
│   ├── 292a48c09e2c0ccfaf5318158d5283dc68472931.nq.gz
│   ├── 2bf136e282e03586bedf1f179fe4d0225689ca70.nq.gz
│   ├── 2f0e693e4f80bc1bdaccc531ed4eea4186246194.nq.gz
│   ├── 2fdc9885203f08e062cc99b12afaba93a204bb56.nq.gz
│   ├── 3048666aede7d7de24cdbe006294f7915bcda698.nq.gz
│   ├── 32b75118182d9f85bb8b1cfe0ced9e22a8ae7176.nq.gz
│   ├── 344800ca75634c17064633fc1666f36ae28b027d.nq.gz
│   ├── 350e944a917b8a842848578d3ab2198ac58712c2.nq.gz
│   ├── 3757a561cc5c2a0141152878dda2605f13e954ad.nq.gz
│   ├── 3829f6b40e0c38adf8210d75025f01f2bfe0613a.nq.gz
│   ├── 3a4b370595332818789dc5c833231084145bf35a.nq.gz
│   ├── 3b97a695adce46d214afa05fc15f05baf69b6296.nq.gz
│   ├── 3bfd91f6482aaaae8305e8999a11345765ebb220.nq.gz
│   ├── 3d58ddf65c16e62954743b5a133528439dc15ea9.nq.gz
│   ├── 413a4507c0600f156062d7c0b472ef1caf6c826d.nq.gz
│   ├── 4212aae60a74dbb66500cc3a32341840fa6b58b7.nq.gz
│   ├── 466d33560fededaffec1d3d8d657cc49dcd71093.nq.gz
│   ├── 46701705eeeffd52886791e9fe284ae9d1b44d4c.nq.gz
│   ├── 47a12ee690260594c95191b80574917ac870b0ad.nq.gz
│   ├── 48935823b877a7b0037f00c8ada7a7775a905e88.nq.gz
│   ├── 4a34b836ff2c0ba7c0eef988a4f91a732a8e4202.nq.gz
│   ├── 4ccbdca8267a9df7c776bfe73cac6b203779284d.nq.gz
│   ├── 501f11cbcdf0135329b7cab76b4eef04c92fad1e.nq.gz
│   ├── 51d56b13e6f99667073277d653c127566949f997.nq.gz
│   ├── 520b78ff19c8a61741c053502a32a79bea26fac5.nq.gz
│   ├── 526bebb113e3cf692141e141a6e0a36d6e292131.nq.gz
│   ├── 53a6dc274e50ac8c8ab8f7ae6d11791baa79a487.nq.gz
│   ├── 54eecb3d77ad456a52130c6e37b1fe290e1cad3f.nq.gz
│   ├── 5783a9d6de230d932fc07ff609b04072659e1a3d.nq.gz
│   ├── 58bfbdfba61c8e64708a7f4908283913d165b337.nq.gz
│   ├── 58e0733ef97afe3501dc38c0a5b7416da83cf7a9.nq.gz
│   ├── 59a6ebbb932124bf470be58f8e4de915c0256f57.nq.gz
│   ├── 5addb5e38cf09b898b2e4797f95e84db5dc88e09.nq.gz
│   ├── 5d87025e88747fe1bdbd67554478a27d516cad6f.nq.gz
│   ├── 5dd8fc5b6d5a8bc1c5cab8e3019b11ce54712361.nq.gz
│   ├── 5ded5c28e525bc831b570d594356cc4b3b0234e5.nq.gz
│   ├── 5e8932a78614fc897b37dea4fc4b8b1796d3ff18.nq.gz
│   ├── 65c6718ede29ffd29b953c6a148b3f2d148920e2.nq.gz
│   ├── 65eac375c49025310770f369bbd095e538d525a2.nq.gz
│   ├── 669e9966f4caeff22a61a76977d95e0ebc5d7d93.nq.gz
│   ├── 67840bdd9d00a7f05c88d24ba66c47a33672b2ce.nq.gz
│   ├── 67bc813564d3594243c39b164e39930de073c4dc.nq.gz
│   ├── 68f568c4f10561401a9fe5d11af8e4e093a507c3.nq.gz
│   ├── 6951070acb9f68c542b5eb8499633531a9a4f3b5.nq.gz
│   ├── 69de737adb23280f64c5fe8770746fd9a4fc81a8.nq.gz
│   ├── 6f2ac30b47a8b0e4776f5b0cf1ee7ff2b3059bea.nq.gz
│   ├── 6f7a6d9c3d740609fd09c88fbf6352a977af7c51.nq.gz
│   ├── 6fd66553eacb8d7c2653053abdaf62e60c24648c.nq.gz
│   ├── 70c350c6fa12105218777f1e42947bc7fcaf1c06.nq.gz
│   ├── 7212db9295e001a79de517ed1cd714a66087d935.nq.gz
│   ├── 7318c9929e4142a43833ae89d98d540154ec098b.nq.gz
│   ├── 7338ccbfe8d3b182d3b3381cd470db8b06540c1e.nq.gz
│   ├── 744b9eeb3e909fa79b2606e7422aa9041e678ce7.nq.gz
│   ├── 74e196849dc2f49bd33fad4f8f36b7bce03331bf.nq.gz
│   ├── 754f6cea0003d89e207ccd4b5b6a1261f2afa7cf.nq.gz
│   ├── 7d87d2d9793173674de0cf601e7a1da7300c6458.nq.gz
│   ├── 7e2d30236e3e4a6804cab8b32d48f6f07ddc179f.nq.gz
│   ├── 81e202f46794f078b208f1687e88de41e9d1e116.nq.gz
│   ├── 822a25103fffde51fadee38eeddf931c8ca755f1.nq.gz
│   ├── 83a186770f1f944613c572f02468c65557ec35b5.nq.gz
│   ├── 85f89bf247c269c88035ffef1672af55f330a584.nq.gz
│   ├── 8705fe840ca2cec1a12b392a70040a276f6949b0.nq.gz
│   ├── 897d5a3f1a6c57e1a89a38def690dcdab13781f0.nq.gz
│   ├── 8994055ecf12d8030c222153e5ab5e69be393261.nq.gz
│   ├── 8a52d6efa580e9dd2b20b1195e17d4b8d590b297.nq.gz
│   ├── 8c888761fe1ecd2d2d8b4e01e34eb5866ea561bd.nq.gz
│   ├── 8d28394907d6fcd94036ed42705013d6e90ddd9c.nq.gz
│   ├── 8d46ca39ed6ea280141da8703427e2074858eb64.nq.gz
│   ├── 8d70a51d6ede75eaab58dc34426ce9d362e19cf9.nq.gz
│   ├── 8e270fdb121bbbe83eff54aa751b765dd5102308.nq.gz
│   ├── 8e2b1c9bc85344109a571008acce6e55078a1d1c.nq.gz
│   ├── 8e4fbbbfb959af360a40c98bf728da186e4bb77f.nq.gz
│   ├── 8fcbe8174393c9e96562c94747ea6bd840e2f173.nq.gz
│   ├── 8fdc1e410b88a796e7731de736d17f8f2bd0fa5b.nq.gz
│   ├── 91e18a62b67551a4d427e2eaee0d33dcab94e141.nq.gz
│   ├── 925c448fff7b6de40ac4efe7911c72641c892a57.nq.gz
│   ├── 9766893bf75d3683f6d3bb745c657b27a2b335b5.nq.gz
│   ├── 99d40ff005ee2a47dda4bd19064e3b52b0e3f234.nq.gz
│   ├── 9be3e15d080949c4ae2670a8f64cc3f23be7ef6c.nq.gz
│   ├── 9c8d20c6fe29742d152c582b6a15cda9cdcc33f0.nq.gz
│   ├── 9d4484186316a2c99b0b56095b20b7a9f4767f12.nq.gz
│   ├── 9e35ea0511ce4206bfd365c5613faa68ba437138.nq.gz
│   ├── 9eed3aaee3226aeead56d39a8ac04685fa1f7feb.nq.gz
│   ├── a1e8a0cee7d835b764d9dbfa00ae340e946572c0.nq.gz
│   ├── a8fbb20835c6a0ad461d96fee4b85093a35635e6.nq.gz
│   ├── aac9a8eb7c68b1f578d5b599419374e25bacbb81.nq.gz
│   ├── ae012eb83be43d7fd19720e17c6857789947a941.nq.gz
│   ├── ae9b6dbe71123e15e2c82bffc10d9e40d31330e1.nq.gz
│   ├── af3174dfa192ef65b8ac87736f387eef98bec9cb.nq.gz
│   ├── af556afc398484cb0506201bd2c2e6f04177c0be.nq.gz
│   ├── af870cd4593ec95fc29a1d17d344cd5166900e11.nq.gz
│   ├── b01b0039ee4dec9f0194de5ee9fe9ee3afa35f08.nq.gz
│   ├── b02f1d189502a1bdf877a1c961cef9109770f939.nq.gz
│   ├── b31973f16abc39202890599ebe2b4ff1db0e1291.nq.gz
│   ├── b96202a9b2caf35245ec70ee4da7fb4813db0e53.nq.gz
│   ├── c308f888d720fe058ec2de1f2e2df2972d817f3b.nq.gz
│   ├── c4847ab6ac8a53988ccc3e82d030f28d08f76f78.nq.gz
│   ├── c538ae3730dc6ca40d7d527b061b2e9420673679.nq.gz
│   ├── c6c78217d39132135fbfa5a78759bd7225acb42a.nq.gz
│   ├── c838c88eb6d8ff4dc9f1400c4a0841d0f8e9fc97.nq.gz
│   ├── c8c5cf33da8c32e0f235788b957ca32757c6f153.nq.gz
│   ├── c9e5197831dc8de7b810f8c3de6235057da6492a.nq.gz
│   ├── cbf8ca9c57d3ac8d98146fd03718b956b74e8a82.nq.gz
│   ├── cefe5fe1cc30f6c93b52b4ea6a71fe65da204177.nq.gz
│   ├── cf6155dddaa2fb19b71a68a8414a5c2b2a602607.nq.gz
│   ├── cf83db6c6476fa85c21de576e7a6c81db7224f61.nq.gz
│   ├── d08918dbe519a95ea8a621e0c65207c1c371bf36.nq.gz
│   ├── d1b51269628e85fd5a678a25f362e90e3f271239.nq.gz
│   ├── d21f898dbecd7496514632fb1bc3d3ef603fec43.nq.gz
│   ├── d28eec1edf48768e0cc882d1817445e9300d4352.nq.gz
│   ├── d2a2a04c5843f201992d9fe8be05a0d6916b6276.nq.gz
│   ├── d2f7095ab8b6dac21b85ea9f7e9bbc3c657cb7b2.nq.gz
│   ├── d31fde33a878313fd2984b14da8f311687f71f37.nq.gz
│   ├── d445a534e7a2b23d758a76cf602593e14ad104ce.nq.gz
│   ├── d9f40a56ea3f32b946811d9b6bb959944fd64007.nq.gz
│   ├── da0bd93a57a3e2dd2d7bd57ea14996edc5e4dbe4.nq.gz
│   ├── deb63c1073149b841d7cac9021c3093009b73be2.nq.gz
│   ├── e2ebdba2502d5a0e542c2c9edb43f35512ae6abc.nq.gz
│   ├── e5459b4f5cf9fac165c7f4aff1ddffc0dbbf577e.nq.gz
│   ├── e7c603790819925433cc824bcd9d95229b474e1d.nq.gz
│   ├── e8b0afb1d260b9fc922b1e5b738cef202a18aa3a.nq.gz
│   ├── eaf0e076f02ee49006df98d573a39e81da72da5f.nq.gz
│   ├── ecf2e63a7c64a77fa1b9d630c80420185a5c6a41.nq.gz
│   ├── ee4d18bd90fc056e4e92fc03b00dd1520c3da386.nq.gz
│   ├── ef728e6428505ed84de283929a5536336be7d7b0.nq.gz
│   ├── efaa7e492d058717dece26034702c708bce80d3f.nq.gz
│   ├── efbc49a8e0124485a603fc128049c6ec7638a166.nq.gz
│   ├── f0dbbfa2945955a83e773ba53a43cad6d7c124a0.nq.gz
│   ├── f2ef5bfd03b59b72d2a5cf99a86f5841881926b3.nq.gz
│   ├── f3624d6f9ebcaf00d1b795fa7f9f3891d7d2d02a.nq.gz
│   ├── f5405e73bc7eeb64c3b89a0bc0d5b18606e5d56a.nq.gz
│   ├── f6b6bfd133de5c8d162acb6f54b91b613f762c77.nq.gz
│   ├── f77f748c19810b2e919afa2b178f58fed5b26c52.nq.gz
│   ├── f80a1b557e221be957dc572c757a769f5e7f92a2.nq.gz
│   ├── f90e55e71f5ad130bd58502747e330e6bf3a4cc0.nq.gz
│   ├── fbf276d8af5bc648b84e288c8ca03fff97c21478.nq.gz
│   ├── fd5a44b085aa36c06a075524cbe510f4e70f60ca.nq.gz
│   └── fee0b32498612769372175ffd36afd28e4c5f1d2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   └── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
├── filetree
│   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   └── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 186 files
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
