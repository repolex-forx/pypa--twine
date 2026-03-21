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
│   │   ├── 1569f5001432e9258210da0275b9fd689241b368.nq.gz
│   │   ├── 1e8140456e7822ab5d72ecf36e0814a09531e451.nq.gz
│   │   ├── 20c55f6d752f7920494bbcea8d5f1a5719c97d81.nq.gz
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 2dab479a003c3c9165498a439bc64e05d29eda9a.nq.gz
│   │   ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│   │   ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│   │   ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│   │   ├── 43f15053f33460f17beffd9b53977a532beff99c.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   ├── 534385596820129b41cbcdcc83d34aa8788067f1.nq.gz
│   │   ├── 54976918e45cd57afbe2cf74e63ef8503eb18d97.nq.gz
│   │   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   │   ├── 5c06ed2049b633fe7f0b0e27df32d2715614ab3a.nq.gz
│   │   ├── 5cb18677d451dcf54a10b939227082e87ee02780.nq.gz
│   │   ├── 68dc617bafbc8a32adbe41c12055efe6ba6d0e1e.nq.gz
│   │   ├── 6ba25d7e62475804a692e0ed07a91e8bdcb10061.nq.gz
│   │   ├── 6cb70f42e3583c0d79a2e2656604bc2a1ea9b599.nq.gz
│   │   ├── 6d48d9741f29810a5d617f473b39825b9f315b48.nq.gz
│   │   ├── 6fbe7e7203ca8e715c238ae081621ffb9f6fc19a.nq.gz
│   │   ├── 7089ba991bca7737184409f46f175649614b9b4c.nq.gz
│   │   ├── 734816524ea01a42bb0d3e8d21582a9d73e4ba15.nq.gz
│   │   ├── 79bd4bd29b3f5efd1de53f6cb969b802e4672be6.nq.gz
│   │   ├── 79e0c8fe1991a6a613ff1ace107b646a6832dd5a.nq.gz
│   │   ├── 9652b938692cdb2a304a83e01e0a9e8b1eadeace.nq.gz
│   │   ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│   │   ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│   │   ├── c1975e8d9fffeda394cd8089bb15fc2f3c526846.nq.gz
│   │   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   │   ├── e2f33a530b3c9ebbff2e385f109956643885858f.nq.gz
│   │   ├── e3aeaaf8de4e84da36ad17ca1412b0a128a282ae.nq.gz
│   │   ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│   │   ├── f94d8a16a4acbbd328dc4736757f5637d8ca0f89.nq.gz
│   │   └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
│   ├── lsp
│   │   ├── 057bd712eddfbf2526d1a7e7518aa2daa77430de.nq.gz
│   │   ├── 1569f5001432e9258210da0275b9fd689241b368.nq.gz
│   │   ├── 1e8140456e7822ab5d72ecf36e0814a09531e451.nq.gz
│   │   ├── 20c55f6d752f7920494bbcea8d5f1a5719c97d81.nq.gz
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 2dab479a003c3c9165498a439bc64e05d29eda9a.nq.gz
│   │   ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│   │   ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│   │   ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│   │   ├── 43f15053f33460f17beffd9b53977a532beff99c.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   ├── 534385596820129b41cbcdcc83d34aa8788067f1.nq.gz
│   │   ├── 54976918e45cd57afbe2cf74e63ef8503eb18d97.nq.gz
│   │   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   │   ├── 5c06ed2049b633fe7f0b0e27df32d2715614ab3a.nq.gz
│   │   ├── 5cb18677d451dcf54a10b939227082e87ee02780.nq.gz
│   │   ├── 68dc617bafbc8a32adbe41c12055efe6ba6d0e1e.nq.gz
│   │   ├── 6ba25d7e62475804a692e0ed07a91e8bdcb10061.nq.gz
│   │   ├── 6cb70f42e3583c0d79a2e2656604bc2a1ea9b599.nq.gz
│   │   ├── 6d48d9741f29810a5d617f473b39825b9f315b48.nq.gz
│   │   ├── 6fbe7e7203ca8e715c238ae081621ffb9f6fc19a.nq.gz
│   │   ├── 7089ba991bca7737184409f46f175649614b9b4c.nq.gz
│   │   ├── 734816524ea01a42bb0d3e8d21582a9d73e4ba15.nq.gz
│   │   ├── 79bd4bd29b3f5efd1de53f6cb969b802e4672be6.nq.gz
│   │   ├── 79e0c8fe1991a6a613ff1ace107b646a6832dd5a.nq.gz
│   │   ├── 9652b938692cdb2a304a83e01e0a9e8b1eadeace.nq.gz
│   │   ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│   │   ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│   │   ├── c1975e8d9fffeda394cd8089bb15fc2f3c526846.nq.gz
│   │   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   │   ├── e2f33a530b3c9ebbff2e385f109956643885858f.nq.gz
│   │   ├── e3aeaaf8de4e84da36ad17ca1412b0a128a282ae.nq.gz
│   │   ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│   │   ├── f94d8a16a4acbbd328dc4736757f5637d8ca0f89.nq.gz
│   │   └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
│   └── repolex
│       ├── 057bd712eddfbf2526d1a7e7518aa2daa77430de.nq.gz
│       ├── 1569f5001432e9258210da0275b9fd689241b368.nq.gz
│       ├── 1e8140456e7822ab5d72ecf36e0814a09531e451.nq.gz
│       ├── 20c55f6d752f7920494bbcea8d5f1a5719c97d81.nq.gz
│       ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│       ├── 2dab479a003c3c9165498a439bc64e05d29eda9a.nq.gz
│       ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│       ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│       ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│       ├── 43f15053f33460f17beffd9b53977a532beff99c.nq.gz
│       ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│       ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│       ├── 534385596820129b41cbcdcc83d34aa8788067f1.nq.gz
│       ├── 54976918e45cd57afbe2cf74e63ef8503eb18d97.nq.gz
│       ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│       ├── 5c06ed2049b633fe7f0b0e27df32d2715614ab3a.nq.gz
│       ├── 5cb18677d451dcf54a10b939227082e87ee02780.nq.gz
│       ├── 68dc617bafbc8a32adbe41c12055efe6ba6d0e1e.nq.gz
│       ├── 6ba25d7e62475804a692e0ed07a91e8bdcb10061.nq.gz
│       ├── 6cb70f42e3583c0d79a2e2656604bc2a1ea9b599.nq.gz
│       ├── 6d48d9741f29810a5d617f473b39825b9f315b48.nq.gz
│       ├── 6fbe7e7203ca8e715c238ae081621ffb9f6fc19a.nq.gz
│       ├── 7089ba991bca7737184409f46f175649614b9b4c.nq.gz
│       ├── 734816524ea01a42bb0d3e8d21582a9d73e4ba15.nq.gz
│       ├── 79bd4bd29b3f5efd1de53f6cb969b802e4672be6.nq.gz
│       ├── 79e0c8fe1991a6a613ff1ace107b646a6832dd5a.nq.gz
│       ├── 9652b938692cdb2a304a83e01e0a9e8b1eadeace.nq.gz
│       ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│       ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│       ├── c1975e8d9fffeda394cd8089bb15fc2f3c526846.nq.gz
│       ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│       ├── e2f33a530b3c9ebbff2e385f109956643885858f.nq.gz
│       ├── e3aeaaf8de4e84da36ad17ca1412b0a128a282ae.nq.gz
│       ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│       ├── f94d8a16a4acbbd328dc4736757f5637d8ca0f89.nq.gz
│       └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
└── blob
    ├── 01eea0fe2f71f308e5549a45a59ada7d56695960.nq.gz
    ├── 0257a242d2d475e1174d9f430c79f44285ea661c.nq.gz
    ├── 032cc21b22bf10441f4e4db1ac666d072bd40a0e.nq.gz
    ├── 0426a882cbc807b989d468b049dcb3f9e8c55dd2.nq.gz
    ├── 045ad81ddb98bb4a5a27a765a701eb94ef3169d9.nq.gz
    ├── 04a7d788066d7d8d51f838004a1a3050f134edb2.nq.gz
    ├── 04c76d47b922c5316906c7b9f2b65dc46d43a5af.nq.gz
    ├── 051b92e3ac498b15c217695e6392f587b6aa0e78.nq.gz
    ├── 062e879d452cf403db76f2f65dd3e3d1181a89cd.nq.gz
    ├── 078a6104b256c4d4f6316aa8ed0fd4ae7e1b1ba0.nq.gz
    ├── 093649b49c1b914f57f8cb15a4044bc4bfc6e00e.nq.gz
    ├── 0b68bc9cdfa15b40aefab25ee3fd7aa86c90ab61.nq.gz
    ├── 0b78fe8980d3b32faeb09cd2c1e43ed2c7d49077.nq.gz
    ├── 0c0098c75d303c89093627777d65c3f9b1cfee30.nq.gz
    ├── 0d40f94403f94ddfcaf13c57662850851a547f2e.nq.gz
    ├── 0d6c126bbd62fa40dfb6530a5a6a8ae2be4a30f7.nq.gz
    ├── 0d919542ee756dc397138aa5c04695c937b5c818.nq.gz
    ├── 0dc337cc3c93b26f91bb225b657005da8b9b56c4.nq.gz
    ├── 0e3beec4086a2bc49ec20a293780b2b2bcbeadb9.nq.gz
    ├── 0f77a3d8367426779d94d076428c25e39deac5c7.nq.gz
    ├── 0fd1e68b90e507a6da330c4ba741d8c7fc1f6718.nq.gz
    ├── 11e551affb61e36d61e16a41482b6dc31d93e0b0.nq.gz
    ├── 12ad867203bd8994fcc2b165f46d549bff11e753.nq.gz
    ├── 12fa3d18573d728cd90520429dfced140c73e3ce.nq.gz
    ├── 13733a75c3c69c859ecc79cedec1106710077d56.nq.gz
    ├── 13c8b85f1b22b37a96b03fecf2efe880ee9fb1a6.nq.gz
    ├── 13f8b9a6fa40a5e1f9bdf7d52cf74f6e4fd4f7a9.nq.gz
    ├── 13fd5ff7bff199fd03c92d35d3ddec2412a84fce.nq.gz
    ├── 16ab96f3f5e051f12ffc770a3163fd6629fe6d65.nq.gz
    ├── 16eece0b47289fb886e8dc3dd87ccaf8bf6394c3.nq.gz
    ├── 1733b60c45010fe1e83f033bae70039d258d58fc.nq.gz
    ├── 173ad51a617e8d4c1f38099217f33212afd2070e.nq.gz
    ├── 17c692b1b0eedb5bc21bd98430e5915cae477d75.nq.gz
    ├── 17e2dcf4b96bab0264bb87670ba732b178b6704a.nq.gz
    ├── 181f613c5a4a3f870bbe4e2a2e7e08d732810159.nq.gz
    ├── 18fb10f15a68e35f9572c19da05e5d91c639531d.nq.gz
    ├── 199c6fc4d13661c110487bf29f9f35864e8419b6.nq.gz
    ├── 1a228940cf6a97e3ba0ee4a4f1f6738b38068122.nq.gz
    ├── 1a2873387945998eb6d91062290a18d9ebde4ee7.nq.gz
    ├── 1b0b77d4a2bdb5c28d164a0380f00e9a266eab6d.nq.gz
    ├── 1bb61ae793e03cb60e51efd489a0c0a4d3d4001f.nq.gz
    ├── 1c12eb8cbc31f69894feaf04701f6fba7be62b80.nq.gz
    ├── 1c1ee3ea35963796a53771465b08f9285710b69f.nq.gz
    ├── 1cdda6be63049deb555de161843b083d62c20e82.nq.gz
    ├── 1d48290578e7ebe657527c4c70f2fef3fae70fb4.nq.gz
    ├── 1e57b0f534b2f3bd6d948acc222b242ad56c3892.nq.gz
    ├── 1fd30ca7ec7dff7fb7e8269c2b6927dec2c5f553.nq.gz
    ├── 203776134f751c2c2e71594b91c82de57eb82dd1.nq.gz
    ├── 205706c83943a9ff5964260632092940be7b30bd.nq.gz
    ├── 206cf658d516f843f2d00068dc49c569f44a2d2b.nq.gz
    ├── 218a37ad866d2a68ecd94edadfca6fe882220396.nq.gz
    ├── 21b5d297e30bb322c4b0a302f6c79699aaad6c1d.nq.gz
    ├── 22c18aac31c553bee9b7c3544dd616e68df3ea3a.nq.gz
    ├── 230e5acf441cd2efa7297326b707caa79064246b.nq.gz
    ├── 24d72c4d49b9eba889793d0e53876c09eb6c66fb.nq.gz
    ├── 254900222856aeefee774be7570338a984be96ff.nq.gz
    ├── 26108523161e793aece5c8c831c5dadff20dae18.nq.gz
    ├── 26331065b699191314b9343fab38afbfa2f172c5.nq.gz
    ├── 2671362ddb84d768693ffefc8477bba7a75b5429.nq.gz
    ├── 2807638572e0944e2e48646f59cbfeb4b7d06a57.nq.gz
    ├── 2836e94711a953ffd21601c903d3a4bfdd164977.nq.gz
    ├── 292a48c09e2c0ccfaf5318158d5283dc68472931.nq.gz
    ├── 29744d19c15f4fef1250222532b858923d58dabb.nq.gz
    ├── 2aa3d89d9b8a9f86a6f1661bc0b20747f7a39344.nq.gz
    ├── 2af1dccd32035d3ecd25581b9f17dc3b9afb281a.nq.gz
    ├── 2bd4a52766f1ccdbf51303c1d23312ee11788431.nq.gz
    ├── 2bf136e282e03586bedf1f179fe4d0225689ca70.nq.gz
    ├── 2c1c837b1f6b5b032ba7ac96e3ddb707fb5202f7.nq.gz
    ├── 2c4a6b73eddca4495a7c3b9e57937b904a021335.nq.gz
    ├── 2e50ee9cf598314de3bfdada30e48c4f17b9ede5.nq.gz
    ├── 2f0e693e4f80bc1bdaccc531ed4eea4186246194.nq.gz
    ├── 2fdc9885203f08e062cc99b12afaba93a204bb56.nq.gz
    ├── 2fe4f897e6c59a3fbf369446c35cabde4b302376.nq.gz
    ├── 2ffda76b4e3260976cec01ad9900f120cfcc21d4.nq.gz
    ├── 303f6d72ec60eaf7dba9568e8f38de8a82d6f3c3.nq.gz
    ├── 3048666aede7d7de24cdbe006294f7915bcda698.nq.gz
    ├── 30baf96753fea5734d8913b24e2788f58e6eda8a.nq.gz
    ├── 316bdf5919f0b01e12fa652ce7ed4d9b27573df3.nq.gz
    ├── 31bdc8c7c35d9c90cff4394539290cc05305d38e.nq.gz
    ├── 32b75118182d9f85bb8b1cfe0ced9e22a8ae7176.nq.gz
    ├── 343ac29850a3ee983ce79a2a2f1c160961ac0e33.nq.gz
    ├── 344800ca75634c17064633fc1666f36ae28b027d.nq.gz
    ├── 3464a3c3ec22d76e5a95808468288f61dfb988b8.nq.gz
    ├── 34c234351609d005b54d92493021531cb0700b88.nq.gz
    ├── 350e944a917b8a842848578d3ab2198ac58712c2.nq.gz
    ├── 35622df221b94756c569de5949a16f0a232a8be5.nq.gz
    ├── 36f63cd0511d92396cf16618aaf003c56a81acd8.nq.gz
    ├── 3757a561cc5c2a0141152878dda2605f13e954ad.nq.gz
    ├── 37e16fcede5196dae6f5711a42207c2cc7fae4ad.nq.gz
    ├── 381d998b70828018e1f8bb8d31324a476ea4b5ba.nq.gz
    ├── 3829f6b40e0c38adf8210d75025f01f2bfe0613a.nq.gz
    └── 396a4aaf911c38106aacff4ef6ea1eb18d1fdd1a.nq.gz

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
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
