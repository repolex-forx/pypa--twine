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
│   │   ├── 22e2e6160e0930354ff9f11e036b2800feef68e2.nq.gz
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 2dab479a003c3c9165498a439bc64e05d29eda9a.nq.gz
│   │   ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│   │   ├── 315c5a3b254ed6a49cca11559a7ac430da2a6cd2.nq.gz
│   │   ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│   │   ├── 36695abf8837aba72d87304d99b789c3f2872c99.nq.gz
│   │   ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│   │   ├── 43f15053f33460f17beffd9b53977a532beff99c.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 49e88ce71a72139366e48eb44ba1fdd7923ebd18.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   ├── 534385596820129b41cbcdcc83d34aa8788067f1.nq.gz
│   │   ├── 54976918e45cd57afbe2cf74e63ef8503eb18d97.nq.gz
│   │   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   │   ├── 5a793bf1230a70327a225ef6117e0c9ee2ab7cb1.nq.gz
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
│   │   ├── 7deea5833918cdb8496587119900e8a3cde57dfc.nq.gz
│   │   ├── 8f5e5d6d42d582ef3ea6ef07da277e0cabd22fd2.nq.gz
│   │   ├── 94f810c54c8bc9d418a9ed64890ca9fa4ec7b59f.nq.gz
│   │   ├── 9652b938692cdb2a304a83e01e0a9e8b1eadeace.nq.gz
│   │   ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│   │   ├── a723876fd4398be57838873e60867566b6220a53.nq.gz
│   │   ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│   │   ├── c1975e8d9fffeda394cd8089bb15fc2f3c526846.nq.gz
│   │   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   │   ├── ce3e76d899736f0dffd619c88961bce838f5931f.nq.gz
│   │   ├── d82cd00d216f6a1768ee835d1b534f16190f35bd.nq.gz
│   │   ├── e2d3f8448fdeadba1388c193be6b66dc93c227ba.nq.gz
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
│   │   ├── 22e2e6160e0930354ff9f11e036b2800feef68e2.nq.gz
│   │   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   │   ├── 2dab479a003c3c9165498a439bc64e05d29eda9a.nq.gz
│   │   ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│   │   ├── 315c5a3b254ed6a49cca11559a7ac430da2a6cd2.nq.gz
│   │   ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│   │   ├── 36695abf8837aba72d87304d99b789c3f2872c99.nq.gz
│   │   ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│   │   ├── 43f15053f33460f17beffd9b53977a532beff99c.nq.gz
│   │   ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│   │   ├── 49e88ce71a72139366e48eb44ba1fdd7923ebd18.nq.gz
│   │   ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│   │   ├── 534385596820129b41cbcdcc83d34aa8788067f1.nq.gz
│   │   ├── 54976918e45cd57afbe2cf74e63ef8503eb18d97.nq.gz
│   │   ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│   │   ├── 5a793bf1230a70327a225ef6117e0c9ee2ab7cb1.nq.gz
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
│   │   ├── 7deea5833918cdb8496587119900e8a3cde57dfc.nq.gz
│   │   ├── 8f5e5d6d42d582ef3ea6ef07da277e0cabd22fd2.nq.gz
│   │   ├── 94f810c54c8bc9d418a9ed64890ca9fa4ec7b59f.nq.gz
│   │   ├── 9652b938692cdb2a304a83e01e0a9e8b1eadeace.nq.gz
│   │   ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│   │   ├── a723876fd4398be57838873e60867566b6220a53.nq.gz
│   │   ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│   │   ├── c1975e8d9fffeda394cd8089bb15fc2f3c526846.nq.gz
│   │   ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│   │   ├── ce3e76d899736f0dffd619c88961bce838f5931f.nq.gz
│   │   ├── d82cd00d216f6a1768ee835d1b534f16190f35bd.nq.gz
│   │   ├── e2d3f8448fdeadba1388c193be6b66dc93c227ba.nq.gz
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
│       ├── 22e2e6160e0930354ff9f11e036b2800feef68e2.nq.gz
│       ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│       ├── 2dab479a003c3c9165498a439bc64e05d29eda9a.nq.gz
│       ├── 2f8c336c1b5bf7aec532dc91a00371ef8870e97a.nq.gz
│       ├── 315c5a3b254ed6a49cca11559a7ac430da2a6cd2.nq.gz
│       ├── 33c8c55efafc3de1b573499f35fcaee4f67f2cd8.nq.gz
│       ├── 36695abf8837aba72d87304d99b789c3f2872c99.nq.gz
│       ├── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
│       ├── 43f15053f33460f17beffd9b53977a532beff99c.nq.gz
│       ├── 47c28cca627bc7e9402b00c607e72d504cc02f05.nq.gz
│       ├── 49e88ce71a72139366e48eb44ba1fdd7923ebd18.nq.gz
│       ├── 4df9256c24f9a40b36016a43ad138a9729f75ab8.nq.gz
│       ├── 534385596820129b41cbcdcc83d34aa8788067f1.nq.gz
│       ├── 54976918e45cd57afbe2cf74e63ef8503eb18d97.nq.gz
│       ├── 550bedb051ff10f259fe91ac0753358d4c767a89.nq.gz
│       ├── 5a793bf1230a70327a225ef6117e0c9ee2ab7cb1.nq.gz
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
│       ├── 7deea5833918cdb8496587119900e8a3cde57dfc.nq.gz
│       ├── 8f5e5d6d42d582ef3ea6ef07da277e0cabd22fd2.nq.gz
│       ├── 94f810c54c8bc9d418a9ed64890ca9fa4ec7b59f.nq.gz
│       ├── 9652b938692cdb2a304a83e01e0a9e8b1eadeace.nq.gz
│       ├── 9b859a8796fb639095547ed694643e9d4d23e3be.nq.gz
│       ├── a723876fd4398be57838873e60867566b6220a53.nq.gz
│       ├── b34f042da78aed22b6e512df61b495638b06ba03.nq.gz
│       ├── c1975e8d9fffeda394cd8089bb15fc2f3c526846.nq.gz
│       ├── c854b2a7b451bf13878f709900261dbcbaf59ca0.nq.gz
│       ├── ce3e76d899736f0dffd619c88961bce838f5931f.nq.gz
│       ├── d82cd00d216f6a1768ee835d1b534f16190f35bd.nq.gz
│       ├── e2d3f8448fdeadba1388c193be6b66dc93c227ba.nq.gz
│       ├── e2f33a530b3c9ebbff2e385f109956643885858f.nq.gz
│       ├── e3aeaaf8de4e84da36ad17ca1412b0a128a282ae.nq.gz
│       ├── e8ed66e4f8e658da84da62dc480402a5d5b51687.nq.gz
│       ├── f94d8a16a4acbbd328dc4736757f5637d8ca0f89.nq.gz
│       └── feca4968c427032ae513c2ba84728cea7ed043ff.nq.gz
└── blob
    ├── 01eea0fe2f71f308e5549a45a59ada7d56695960.nq.gz
    ├── 0257a242d2d475e1174d9f430c79f44285ea661c.nq.gz
    ├── 02cb3708482efe37c700d74066ddc755d3d43924.nq.gz
    ├── 032cc21b22bf10441f4e4db1ac666d072bd40a0e.nq.gz
    ├── 0426a882cbc807b989d468b049dcb3f9e8c55dd2.nq.gz
    ├── 045ad81ddb98bb4a5a27a765a701eb94ef3169d9.nq.gz
    ├── 04a7d788066d7d8d51f838004a1a3050f134edb2.nq.gz
    ├── 04c76d47b922c5316906c7b9f2b65dc46d43a5af.nq.gz
    ├── 04ce8704183d090711243eaf5430e950d9bd7419.nq.gz
    ├── 04f68504171022a89ed79b1f3b63cf1b8fa94631.nq.gz
    ├── 051b92e3ac498b15c217695e6392f587b6aa0e78.nq.gz
    ├── 062e879d452cf403db76f2f65dd3e3d1181a89cd.nq.gz
    ├── 068e1cc87eb45c4e49210b37de514b2b44b6fc61.nq.gz
    ├── 06a121e01c2769c4df89bc46756eed39c6c0ae80.nq.gz
    ├── 078a6104b256c4d4f6316aa8ed0fd4ae7e1b1ba0.nq.gz
    ├── 07965d54d6329477030305842b2cfd6e03e1a6e0.nq.gz
    ├── 080bae3ecb457b3ba827dc5c2b01afaa2c3533ce.nq.gz
    ├── 08a2d4b2413e9d43852c83915eeff4365c2b280e.nq.gz
    ├── 08eb5e2b68b1170e309ea4407f00f8ccea2ea8ed.nq.gz
    ├── 093649b49c1b914f57f8cb15a4044bc4bfc6e00e.nq.gz
    ├── 0aa5c75a729e241e57fa789aceae5858f294b2ca.nq.gz
    ├── 0b68bc9cdfa15b40aefab25ee3fd7aa86c90ab61.nq.gz
    ├── 0b78fe8980d3b32faeb09cd2c1e43ed2c7d49077.nq.gz
    ├── 0b883da3e4af9b10b7e62932228049a6d4aa9c45.nq.gz
    ├── 0c0098c75d303c89093627777d65c3f9b1cfee30.nq.gz
    ├── 0c09ee8016f6fdfe445eec54eb81e2570b45c0a3.nq.gz
    ├── 0d40f94403f94ddfcaf13c57662850851a547f2e.nq.gz
    ├── 0d6c126bbd62fa40dfb6530a5a6a8ae2be4a30f7.nq.gz
    ├── 0d919542ee756dc397138aa5c04695c937b5c818.nq.gz
    ├── 0dc337cc3c93b26f91bb225b657005da8b9b56c4.nq.gz
    ├── 0e0d4841395243c0df1cf9618069ef4d75fc208f.nq.gz
    ├── 0e2e71e75413913476a38248f7a9a1fca8a73a85.nq.gz
    ├── 0e3beec4086a2bc49ec20a293780b2b2bcbeadb9.nq.gz
    ├── 0e58eba159ca3720265bb0219312c1e4d3e35874.nq.gz
    ├── 0e5d746e4c63bcd2c8e8ebc59b0c9854b086efb4.nq.gz
    ├── 0f4cb8866980309ebc1cba603188521aa43f2a81.nq.gz
    ├── 0f616ebfbf0b672cf4a06ac1652bb517979c2a63.nq.gz
    ├── 0f77a3d8367426779d94d076428c25e39deac5c7.nq.gz
    ├── 0f9dab75909380abf87d3ec3f0d16dd634c54fb6.nq.gz
    ├── 0fd1e68b90e507a6da330c4ba741d8c7fc1f6718.nq.gz
    ├── 105d0deeb9b37f4366544966db785abec92905c7.nq.gz
    ├── 109de97b641b9b79344c00aba5e7eaf6115a6438.nq.gz
    ├── 10e374e74c14f5f64f788a2e6ef85b6748b7bb92.nq.gz
    ├── 11e551affb61e36d61e16a41482b6dc31d93e0b0.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 12ad867203bd8994fcc2b165f46d549bff11e753.nq.gz
    ├── 12ec03ec8e2cfb4d0fd3bd2f64e4e92d7b105687.nq.gz
    ├── 12fa3d18573d728cd90520429dfced140c73e3ce.nq.gz
    ├── 13733a75c3c69c859ecc79cedec1106710077d56.nq.gz
    ├── 13c8b85f1b22b37a96b03fecf2efe880ee9fb1a6.nq.gz
    ├── 13f8b9a6fa40a5e1f9bdf7d52cf74f6e4fd4f7a9.nq.gz
    ├── 13fd5ff7bff199fd03c92d35d3ddec2412a84fce.nq.gz
    ├── 16ab96f3f5e051f12ffc770a3163fd6629fe6d65.nq.gz
    ├── 16eece0b47289fb886e8dc3dd87ccaf8bf6394c3.nq.gz
    ├── 1733b60c45010fe1e83f033bae70039d258d58fc.nq.gz
    └── 173ad51a617e8d4c1f38099217f33212afd2070e.nq.gz

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
*Parsed on 2026-03-23 by [repolex](https://repolex.ai)*
