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
├── blob
│   ├── 0dc337cc3c93b26f91bb225b657005da8b9b56c4.nq.gz
│   ├── 12fa3d18573d728cd90520429dfced140c73e3ce.nq.gz
│   ├── 13c8b85f1b22b37a96b03fecf2efe880ee9fb1a6.nq.gz
│   ├── 218a37ad866d2a68ecd94edadfca6fe882220396.nq.gz
│   ├── 292a48c09e2c0ccfaf5318158d5283dc68472931.nq.gz
│   ├── 3048666aede7d7de24cdbe006294f7915bcda698.nq.gz
│   ├── 3d58ddf65c16e62954743b5a133528439dc15ea9.nq.gz
│   ├── 413a4507c0600f156062d7c0b472ef1caf6c826d.nq.gz
│   ├── 501f11cbcdf0135329b7cab76b4eef04c92fad1e.nq.gz
│   ├── 53a6dc274e50ac8c8ab8f7ae6d11791baa79a487.nq.gz
│   ├── 54eecb3d77ad456a52130c6e37b1fe290e1cad3f.nq.gz
│   ├── 5783a9d6de230d932fc07ff609b04072659e1a3d.nq.gz
│   ├── 58e0733ef97afe3501dc38c0a5b7416da83cf7a9.nq.gz
│   ├── 59a6ebbb932124bf470be58f8e4de915c0256f57.nq.gz
│   ├── 5d87025e88747fe1bdbd67554478a27d516cad6f.nq.gz
│   ├── 669e9966f4caeff22a61a76977d95e0ebc5d7d93.nq.gz
│   ├── 68f568c4f10561401a9fe5d11af8e4e093a507c3.nq.gz
│   ├── 6951070acb9f68c542b5eb8499633531a9a4f3b5.nq.gz
│   ├── 69de737adb23280f64c5fe8770746fd9a4fc81a8.nq.gz
│   ├── 7318c9929e4142a43833ae89d98d540154ec098b.nq.gz
│   ├── 754f6cea0003d89e207ccd4b5b6a1261f2afa7cf.nq.gz
│   ├── 7d87d2d9793173674de0cf601e7a1da7300c6458.nq.gz
│   ├── 85f89bf247c269c88035ffef1672af55f330a584.nq.gz
│   ├── 8705fe840ca2cec1a12b392a70040a276f6949b0.nq.gz
│   ├── 897d5a3f1a6c57e1a89a38def690dcdab13781f0.nq.gz
│   ├── 8d28394907d6fcd94036ed42705013d6e90ddd9c.nq.gz
│   ├── 8d46ca39ed6ea280141da8703427e2074858eb64.nq.gz
│   ├── 8d70a51d6ede75eaab58dc34426ce9d362e19cf9.nq.gz
│   ├── 91e18a62b67551a4d427e2eaee0d33dcab94e141.nq.gz
│   ├── 9be3e15d080949c4ae2670a8f64cc3f23be7ef6c.nq.gz
│   ├── 9eed3aaee3226aeead56d39a8ac04685fa1f7feb.nq.gz
│   ├── a1e8a0cee7d835b764d9dbfa00ae340e946572c0.nq.gz
│   ├── af870cd4593ec95fc29a1d17d344cd5166900e11.nq.gz
│   ├── b01b0039ee4dec9f0194de5ee9fe9ee3afa35f08.nq.gz
│   ├── b02f1d189502a1bdf877a1c961cef9109770f939.nq.gz
│   ├── c4847ab6ac8a53988ccc3e82d030f28d08f76f78.nq.gz
│   ├── cf6155dddaa2fb19b71a68a8414a5c2b2a602607.nq.gz
│   ├── d08918dbe519a95ea8a621e0c65207c1c371bf36.nq.gz
│   ├── d28eec1edf48768e0cc882d1817445e9300d4352.nq.gz
│   ├── e7c603790819925433cc824bcd9d95229b474e1d.nq.gz
│   ├── e8b0afb1d260b9fc922b1e5b738cef202a18aa3a.nq.gz
│   ├── ecf2e63a7c64a77fa1b9d630c80420185a5c6a41.nq.gz
│   ├── efaa7e492d058717dece26034702c708bce80d3f.nq.gz
│   ├── f5405e73bc7eeb64c3b89a0bc0d5b18606e5d56a.nq.gz
│   ├── f6b6bfd133de5c8d162acb6f54b91b613f762c77.nq.gz
│   ├── f77f748c19810b2e919afa2b178f58fed5b26c52.nq.gz
│   └── f80a1b557e221be957dc572c757a769f5e7f92a2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 2bac4203f215368066902baaec32aa62990f5cdc.nq.gz
│   └── 38b414b169eb49a637d071b74a2f7e2fcb010317.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 54 files
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
