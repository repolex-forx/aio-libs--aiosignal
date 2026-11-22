# Repolex Knowledge Graph of aio-libs/aiosignal

RDF knowledge graph data for [aio-libs/aiosignal](https://github.com/aio-libs/aiosignal), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiosignal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 1cf80149c869d410c90a58e85e9c703be6ef8692
│   │   │   └── chunk-001.nq.gz
│   │   └── 63b413b5c370d9bb9b57cb570863cfbe6694bf30
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1cf80149c869d410c90a58e85e9c703be6ef8692.nq.gz
│   └── repolex
│       ├── 1cf80149c869d410c90a58e85e9c703be6ef8692
│       │   └── chunk-001.nq.gz
│       └── 63b413b5c370d9bb9b57cb570863cfbe6694bf30
│           └── chunk-001.nq.gz
├── blob
│   ├── 0423ef917947c190369543c7997d24aac9dc1181.nq.gz
│   ├── 06e851c54476596dd076e18491ab5d954a536057.nq.gz
│   ├── 06eea7a89f8ebbba666f53c0be869e3ced71165b.nq.gz
│   ├── 1014c478607ab5922e1c6b3d3b3c31a9fe4aeb99.nq.gz
│   ├── 1ac9bdff44c49906d508d785faeacd57deb2fcfd.nq.gz
│   ├── 1cf1954261ef637ae5bec0a297d0a5deb3ea45ba.nq.gz
│   ├── 237c61a659f9982224af8609bc53a4d7542a3336.nq.gz
│   ├── 30c2e102ad091949a881e89f626ceafa7f5fbc2b.nq.gz
│   ├── 34c987417b322d088ba4921e6e7830ea6dc08003.nq.gz
│   ├── 35010ca284f871397c92a95d8657fcc189e89f81.nq.gz
│   ├── 391c3cfb2ac4a89f28afdc57a784c4345515d68a.nq.gz
│   ├── 3fb12d7f1b788e24298cd05ce060248b1f873a26.nq.gz
│   ├── 424ea242f1f8471a4e67c0d0221f3cd6f8810fe1.nq.gz
│   ├── 482e2b822475a07568156986e21a3462d9d8c77c.nq.gz
│   ├── 48692e94c5c39e5d160029d4c7131e275d1cf3a5.nq.gz
│   ├── 48ea7522643188b8b1af22b0411237dcd63cc24b.nq.gz
│   ├── 4c257489a56d23e0a79b40ff64d70c8c58ef7fb7.nq.gz
│   ├── 4ddbcd2b8b38bd1e6892130e349d7eebbb266799.nq.gz
│   ├── 50b0b46b75007d0c3e9a7bc5f5c1e6d616dbce22.nq.gz
│   ├── 51bd887ae9ee1ae59208e4f4e481be7f12196786.nq.gz
│   ├── 56b6e85fa8c7237a3331449b294cd717557d9d82.nq.gz
│   ├── 58c57ce85ad7cfba069cf6be1b6e7c44edfdb8ec.nq.gz
│   ├── 5cc46813529d9b7a05210b1022f264f9f3bce2b6.nq.gz
│   ├── 5ede0090ad93cacd642b11645c1c71bcd3021e2b.nq.gz
│   ├── 609e0b16342f41238d85aab030bbbda0757b363c.nq.gz
│   ├── 655e900e2a7d5f29bb07506b51c13b8c54a7e835.nq.gz
│   ├── 68c2d1e68f1b0964e8720bb66fb06e03df1390c8.nq.gz
│   ├── 6a35d4424e4b8fb2b321a2b703b11fb291f1163e.nq.gz
│   ├── 7082a2d5b9047bfc09589f387053e24ea490bc54.nq.gz
│   ├── 70c8d53fe7e672dc4a021f0ae61ba23754d5ab13.nq.gz
│   ├── 70e1010d42675fafcf8f06ee2fa4a56d90d564da.nq.gz
│   ├── 769e4f6a7a62844a12e62f94e418ef46e354e327.nq.gz
│   ├── 7d945dabdb6033ac98490b8c3c0be95b9255520e.nq.gz
│   ├── 7f1a1763ca9cebc7bc16576d353d3284ee5d3c7d.nq.gz
│   ├── 805943cb438442f96f16c4638b6cbc20635125b5.nq.gz
│   ├── 80e993944170f83e77b1cba8ad0938cc90419a0e.nq.gz
│   ├── 88268df27ce51295dd8a87212a965cbf3b4da4cf.nq.gz
│   ├── 9448781d731cebb8396264c4309a1e3c98f9e7e3.nq.gz
│   ├── 974333de09b1f1988d84f49f15d10e514b42570b.nq.gz
│   ├── 9a6eb0244e7685f563b1344e5f0548ee9410831e.nq.gz
│   ├── a34d243825cf84fe74962623ffc33a24daf0bf6b.nq.gz
│   ├── a3ae6bb45deb3dc7f0a4c5c3981942acc725b748.nq.gz
│   ├── a4cde720f53942f32740f105cbf00a59bec07a11.nq.gz
│   ├── a74225bc2393a70be6bf2ee8e40e1b891b6cff2f.nq.gz
│   ├── abd2206c3d37248804dc3dc639dee59a5738ce56.nq.gz
│   ├── ae3930a511233cc635079cc783bad8ea1bcf9ccc.nq.gz
│   ├── b04bef3c8ae74351c3b29c604e9d519a1ac03a5a.nq.gz
│   ├── b66c72b4ced2846ea58d2f66105550966c0a4c37.nq.gz
│   ├── b7ac3a51e39ecec545cadb94e17d58b8675f8fad.nq.gz
│   ├── bc6016baf5c9dfaccf327a5bbb586161a431bf5d.nq.gz
│   ├── bf6165bebfdc1aa93830d483022e24dff327b815.nq.gz
│   ├── c6403479f4c42d5911f05bcb549592d159eab829.nq.gz
│   ├── ca4d0f9c754d43213e6da04e6784dcdedffc7988.nq.gz
│   ├── cc045b12528aec0e635851c3402f5292c67f2c4e.nq.gz
│   ├── d00283dfc91c137c534c6bc1663be0ca38405269.nq.gz
│   ├── d2208d23798c7baed655b757759e1ba6df51da31.nq.gz
│   ├── d4f315a89878c1ae5ac57e95654d16c1d2010194.nq.gz
│   ├── d80b8f52fc1735be4ee311df192bf974045b0e43.nq.gz
│   ├── dcd37ca195da024c6e67ddda9ad5e2a576afd410.nq.gz
│   ├── e33f883ec57919deb3d33ec2d2bc5e27745b1d47.nq.gz
│   ├── e3d9afecba6dd2dcef6c49c65f39bedcd7e14882.nq.gz
│   ├── e4a5f1e2c8e36268df66c27ba7a034e4b32a1119.nq.gz
│   ├── e542b1e9ef171b3624b0d785bbea858879ea5bfb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7110f39b6ba05a2abefcb7724a008e5ce6077ad.nq.gz
│   ├── e7fab210a71eaa7f60ce1822e544cdbf0e8aaa52.nq.gz
│   ├── f25ce0b1f001dcf6b594996125e662319b52f042.nq.gz
│   ├── f3aa717f3a65dcc56ad2dfb57b3c6b4965800996.nq.gz
│   ├── f42760bed80721a42ae3fd1d98e94c604069efac.nq.gz
│   ├── f51b3f43fff05ebd884dec2d6a394fad1c90f6e2.nq.gz
│   ├── f935021a8f8a7bd22f9d6703cafa5134bb6a57f8.nq.gz
│   ├── f946c204efe90a5c022b139ce17bfd5ac2c74e4c.nq.gz
│   └── fd2bfe1badc0e3d896d1978dbe080cafe99fa009.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1cf80149c869d410c90a58e85e9c703be6ef8692.nq.gz
├── filetree
│   ├── 1cf80149c869d410c90a58e85e9c703be6ef8692.nq.gz
│   └── 63b413b5c370d9bb9b57cb570863cfbe6694bf30.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 86 files
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

[aio-libs/aiosignal](https://github.com/aio-libs/aiosignal)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
