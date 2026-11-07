# Repolex Knowledge Graph of sunpy/sunpy-vcr-cassettes

RDF knowledge graph data for [sunpy/sunpy-vcr-cassettes](https://github.com/sunpy/sunpy-vcr-cassettes), parsed by [repolex](https://repolex.ai).

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
rlex download sunpy/sunpy-vcr-cassettes
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11e3639bfcc0ded41d6f62c7ae0ade7f09989027
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 11e3639bfcc0ded41d6f62c7ae0ade7f09989027
│           └── chunk-001.nq.gz
├── blob
│   ├── 0214ce8b9ca737207d5e802675358026cdf45241.nq.gz
│   ├── 05b752f42263e0669ba947e5118e74675715c6c8.nq.gz
│   ├── 09a3f18e65447a6fac3f75398a9f503936d1e399.nq.gz
│   ├── 09c172dbe7bad2bbbdbec6992d4ede44b2f9957c.nq.gz
│   ├── 112016fe5d5db5bcd72435db6581f876f97063c4.nq.gz
│   ├── 11dc2b1fdc0f06a9c7c88df94450679c9575fa47.nq.gz
│   ├── 166b05294087e9696991c3a73a2f4d71cab437fb.nq.gz
│   ├── 1a178bf449ae75419df9cb19b642636d022460be.nq.gz
│   ├── 1e0c984dd43737e742eccbd9a8ed6a79c95c7514.nq.gz
│   ├── 1ebba09d0d4b0b5de72a14f7fd3dac41056bd72f.nq.gz
│   ├── 2016cabefafb58bf56b29b8c320283b951acd692.nq.gz
│   ├── 21bcc7c279f7315caba1951a04d273ee4c80b2b3.nq.gz
│   ├── 238bbf78c1ac66af93a5872fbef498a791beb863.nq.gz
│   ├── 238d05b7fa9f4c97950ba40a64d5b7352737bd1f.nq.gz
│   ├── 24406b471ec65d1f95dd856138ccdad32e1d9900.nq.gz
│   ├── 256072fad5497ca936112f6543f194590a9427df.nq.gz
│   ├── 272fd9da46089863a1b2913b93d7cf86a73a99fb.nq.gz
│   ├── 27919efdee269b509cc61cbaba5347c4d403a7cd.nq.gz
│   ├── 27fca1dcb4b27aa06ede46f41e5b203e2da42597.nq.gz
│   ├── 292cbe6dfe046e473785bdfc2206b847b927f674.nq.gz
│   ├── 29e3918a99f81569961f0a47c0f3d0fffbc384b5.nq.gz
│   ├── 2ae4affefeecd3148322822f8cef0943496610d2.nq.gz
│   ├── 32cb9869eb3a6ac72b363d013d028dcb05ffe748.nq.gz
│   ├── 3ca710600c689714b7ad82ec56f7180ff28b7bc1.nq.gz
│   ├── 40245ea66f0b1f2740df765335bf2d7fa7f71a23.nq.gz
│   ├── 412c5d0aadb1ade78d4d017e955148b2756953cf.nq.gz
│   ├── 46867df456e80bfb1fab28a6b29edcc96d84eb0d.nq.gz
│   ├── 4865a853ab554f0bfdec20d56d2d329ddb02ed0c.nq.gz
│   ├── 5273f3c73bedb92031a0e89ea4127d7f4f649272.nq.gz
│   ├── 52bbe54d5cf21e02a53b7bcf5bb1af5d25bf7cba.nq.gz
│   ├── 5788cbc657939244707eacda2d2370cab84985ca.nq.gz
│   ├── 57e9d1a4aa2f0bf057ca95f1cb27aa436f9173c2.nq.gz
│   ├── 57f6716bef99d2d89930f60231a5d78d4771c45b.nq.gz
│   ├── 58894dc5bc5e5c6bcb092ff2ab3911cf642ddb8b.nq.gz
│   ├── 58b43f50b0073abf99c15aeb097157e74d136e29.nq.gz
│   ├── 591707dbb697f124c2b43bc9876e4bbc6d200e7f.nq.gz
│   ├── 5a14bccabc91685f2f2cfc6cdaca1a59497fd823.nq.gz
│   ├── 5d533c135a4d8ff3ffcac674ead2494173e26f14.nq.gz
│   ├── 5d67840cb81ae6a2a18322b8e523fbdf2142118b.nq.gz
│   ├── 5fee18cc1ede342cd5ffbd7c030c544996ed83d3.nq.gz
│   ├── 619dd056350d36ea7126367402026d48b898c362.nq.gz
│   ├── 66572bb4d67e21d9d3d006fc2ebce2406ee689ed.nq.gz
│   ├── 693e670cb4559447fb214f9c6404526cd1c3ece5.nq.gz
│   ├── 6b33a1a2adc60035bef95cd7b4e39f4952c3d7b4.nq.gz
│   ├── 6ec9026ac33a3e1a92bc49766d96b5e15f211178.nq.gz
│   ├── 740b770e542c2cd7061426f99d92dfff05278943.nq.gz
│   ├── 7449499ae9714baf7e3ecd99df8e183d04d98842.nq.gz
│   ├── 7735de2cbc15f83b524eb302418010f13075d400.nq.gz
│   ├── 785dba6e537f37be8c28c6dec4dcd033a181b1c5.nq.gz
│   ├── 7932d792c03a83bf0fe47e64b0ae3cde9a3d011b.nq.gz
│   ├── 7c10b266ca5b9ed56a300f5c7a20eb6c02299aa5.nq.gz
│   ├── 7db07a68c7edb9cbff14162c52ca38e646d01ba7.nq.gz
│   ├── 7ff9577288bf0740711c5a0da852a28b23877bd1.nq.gz
│   ├── 81db5f5f5f4a2082e08b2d35f4e04894c9ed8161.nq.gz
│   ├── 83b2d0444ee75e9d5fe309d3bc0d464bc78b8930.nq.gz
│   ├── 84fff5c35d743cb6bf5f6d039b9a819626e86c6c.nq.gz
│   ├── 85d499557951458ad6fc9550ab439386a4e645d7.nq.gz
│   ├── 888f00d1d655c8700bcdc83925582acc9c937b07.nq.gz
│   ├── 8899934ed80499a365af65b42e59e88b83770068.nq.gz
│   ├── 8b5aa94a22195b390ab21d7b11935f7838c8e042.nq.gz
│   ├── 8fafb785ec3d69ca5876daa173374be43b2e9b3e.nq.gz
│   ├── 9107ce2f2883bb3de3573bd6a97b8d12e8d46764.nq.gz
│   ├── 914f121b7957aaf305165207ef79deacdcf36040.nq.gz
│   ├── 93aefa2c999260cd6db4db0efebb696e1148475f.nq.gz
│   ├── 94f913c52b06ad8c22622cb5a64c8043e23787c2.nq.gz
│   ├── 989eda69344c74bca095650c8137f2c6ee4389c1.nq.gz
│   ├── 9bb5e8765ca1e1eab234f6b50f0021e5b14c77c1.nq.gz
│   ├── 9c165fff0acf0d101c1787996e3beb978af7f8cc.nq.gz
│   ├── 9c97626812e4649c53f40ef74d258be33ebcbbb9.nq.gz
│   ├── a1f6496dd3c8b5f646f0f686184e8110bd8ffdfc.nq.gz
│   ├── a2a1559f3c128790239dc223046d255355b7f7c1.nq.gz
│   ├── a2c3cfebbbed56c21e0206db1d30bae68e600baf.nq.gz
│   ├── a46b156bb4a891c10bc8739521b7903563fe2510.nq.gz
│   ├── a74d1805c439c477de12a91b787d13a8938ea636.nq.gz
│   ├── a8d7a3edca9b3f6a282323e38bfbdbf433ca858a.nq.gz
│   ├── aa77227e6f7789849cf0a403338039356ebdc1c7.nq.gz
│   ├── ab3334aae49931162fe3d1a89efa711b65bdbffb.nq.gz
│   ├── afd8b917b89c4e82aa64f10511c449cb92cbf518.nq.gz
│   ├── b293e27e3e147e5189986758e82382b12d5a86d2.nq.gz
│   ├── b2dfc711f4d7e0fdbbbf9b2d558fb72fab6d841f.nq.gz
│   ├── b7cb82f57ba236131eb6697900ec03a3e0f5f99e.nq.gz
│   ├── b820e7e32dc119570e4cb908dc649906d58c0f95.nq.gz
│   ├── bfd52d0adbee6f669fdee67961bc4378d31d8f13.nq.gz
│   ├── c21fc1a7137865e43d42e49894afe1cb5ade9083.nq.gz
│   ├── c3a0ab4ccaf3025e63d2a50b2d47ff25ee4eba82.nq.gz
│   ├── c46b6c2e04e1e7a4112e3a231797e63191ee0f7d.nq.gz
│   ├── c6e9f29e9d503c9eb52482e31cffa96e7c60684c.nq.gz
│   ├── c720a51a90c63eb6100fabf5ba1abf5ec014f0cb.nq.gz
│   ├── cc9dd87bc2a3f930b0ae90d2f692419eb6da7738.nq.gz
│   ├── ce18dd8e86972cdfc801a66e88b1ffa4c6ec7f0e.nq.gz
│   ├── cf4ada3b271edb0c839b1ddfc21085bdd99decde.nq.gz
│   ├── d63f7737c66f21c329f5f85f34062caa5db2116b.nq.gz
│   ├── d7614e5e6769bc44b400da18f1eddb026e5b614f.nq.gz
│   ├── dbe51d2d007d6187785b93f5ae1632c9594a004e.nq.gz
│   ├── df659cdcd1060d846f1694441fbc5d652a6358ff.nq.gz
│   ├── e29c59d86db873690942c06b45c103416c11309b.nq.gz
│   ├── e500adee7244d13a312f55b273a696b63ab7afb6.nq.gz
│   ├── e5e9e180c595eb4f2c63c03251e0757729c08875.nq.gz
│   ├── ea8fa8a3b58d22c766192d704031bc70d0853dfb.nq.gz
│   ├── ecaed4f8ebaa69428cada9b599082cbd97beab33.nq.gz
│   ├── ef3562072091be39efb5c9a09bfd10b029e6f6f4.nq.gz
│   ├── f4439a36ba7793733f438eed029bf6d5e1ad05fc.nq.gz
│   ├── f4d69cab67492379ebd3375c98b668f6100fca26.nq.gz
│   ├── fd9979112f43e3256726ddc14d14bda1736fef58.nq.gz
│   └── ffa7fd9dfbe80cf1e9c072c235b7d2fdb7cea613.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 11e3639bfcc0ded41d6f62c7ae0ade7f09989027.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 113 files
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

[sunpy/sunpy-vcr-cassettes](https://github.com/sunpy/sunpy-vcr-cassettes)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
