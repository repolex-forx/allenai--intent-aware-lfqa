# Repolex Knowledge Graph of allenai/intent-aware-lfqa

RDF knowledge graph data for [allenai/intent-aware-lfqa](https://github.com/allenai/intent-aware-lfqa), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/intent-aware-lfqa
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7c75aa23937ad717390ffd36de2e5e965d9a3127
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7c75aa23937ad717390ffd36de2e5e965d9a3127
│           └── chunk-001.nq.gz
├── blob
│   ├── 0374d8eef95fbd8f8a56c7bf212332157ed2942a.nq.gz
│   ├── 0b2c2b5dc7137301b78e990b1d7a6bbd0a915c67.nq.gz
│   ├── 0b52e934781673f659be683960a904fa9adaf6aa.nq.gz
│   ├── 0b8c7e3ac6d078934d6ad51c630b149c39178d47.nq.gz
│   ├── 0e450b93cea4687778658f491e83f01750f44a69.nq.gz
│   ├── 0f0607e8cdf59bc338fa5fa03688b93fd9a1df27.nq.gz
│   ├── 0ff76c77bfefcb5d6d84550884fb32cbf217d1a9.nq.gz
│   ├── 1052a693a87d18fc216e9676164ada30adc4881c.nq.gz
│   ├── 13ad9ca3eac302b234a1e13c8ff1c4a12c4dca21.nq.gz
│   ├── 18335c7f06c2cd8559f309a530d43da3bda6e198.nq.gz
│   ├── 1c4c5bfad73361ed21be7d0f15fe1dddbc2fb652.nq.gz
│   ├── 1ff820a08f672ca91485093b9e08072e3e6fc7fc.nq.gz
│   ├── 2099d7452b89f07c45aedbd9146ef3409126fd7d.nq.gz
│   ├── 248caef2678c0c8eb0a895619c6bbf74aeacbee1.nq.gz
│   ├── 255c15c6b8eb84498dffb38b0457488cfe5173b9.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2aecf7a17becec6b923cae0d93f876a50d52f128.nq.gz
│   ├── 2e33af77a9bb56ae636ea6d3c01041925bd4a6c1.nq.gz
│   ├── 2e62cb9bb56dff5fe8bcd9fcd9147742e418927d.nq.gz
│   ├── 3138a58c95597f77c488093a5e5df2e4113fa567.nq.gz
│   ├── 42a859b80d8ad54d6d527cbac305a871113b84fa.nq.gz
│   ├── 4fb9ebd1b473c95c7f2bc80eeb6cd23a6e740ddb.nq.gz
│   ├── 5295b7c6b8ed57d60504dc491fcd277fa927ed74.nq.gz
│   ├── 690c331acb1079de1410784d991604fa4c3d4d0b.nq.gz
│   ├── 6a541711aaf1acfc7ec0e7dc58e13536f702359e.nq.gz
│   ├── 6dea3ea50e16178d0fb38b45ddd955455df2e1bc.nq.gz
│   ├── 70a6e94774df3269f7dcf159262f6944d5583e95.nq.gz
│   ├── 71bba17e35dcc6a2882807833de0926ba7f574c7.nq.gz
│   ├── 7ad6f99c7c58f4066a965d6e239f049bafe6bddd.nq.gz
│   ├── 8018dc90ccbaa310de3d3fcc5fbb2106038b39d9.nq.gz
│   ├── 8475be1a16aae13a11dc563c873576980499e60e.nq.gz
│   ├── 89b8d746076733cb432f5746ea69e3b0c3f2d494.nq.gz
│   ├── 93a55fa4c5ddb76bb9ff79a8a8f0c9da37619eae.nq.gz
│   ├── 94ac5864a49464ac516ad0b7490d65c2e6d82f12.nq.gz
│   ├── 9c2598e0d853bcc29a6916cb634d97b3f8734f5f.nq.gz
│   ├── a1e6fa8b7087545c782202d10e4895fbf9fc9543.nq.gz
│   ├── a48861ebd0b71a02359e713e1e500b94abd3e3a7.nq.gz
│   ├── acc0d716dcf535db88d963b8e7263996a8efce8d.nq.gz
│   ├── ae56a9e1d466cb51c501de5d27d993c75a14de19.nq.gz
│   ├── b3644438fe43d8d433a6bf57ee57654916a4f76a.nq.gz
│   ├── ba2071f3055aaaa3b7d72314a0c15e2797b9e31d.nq.gz
│   ├── ba3fb00b95b3fc70bd950a08781b968cf43b2068.nq.gz
│   ├── c0d22419e0797cf9785bc9fee455763abb64417c.nq.gz
│   ├── c36cd0676dc483c54e206119fc1bb1ddf74f31bc.nq.gz
│   ├── c6b609e0d0af32d080f5dbd8465905aeb3bdca95.nq.gz
│   ├── c921dd35dd1ed07d67db3e56898ad0d13a3f5013.nq.gz
│   ├── cfe732c982f160198a832478c2667fce6c0b0aec.nq.gz
│   ├── d1644e2fab0723ca80b121b361cd924bf1d37c11.nq.gz
│   ├── db983c261f3fa3bd3ed931aa7dbef42163b63f7d.nq.gz
│   ├── dbb0bdf524adb5168ca928fe49e52185f91d841e.nq.gz
│   ├── dbe6601b6d0b4d694a6fb0f1967271bdb37c36c5.nq.gz
│   ├── dd9278e3bed4f815149ade2e3abda7e478966195.nq.gz
│   ├── df9a3e048ec73ddcd11ddf48d8fcd127e2604c9f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebaeb8e7035a8ed6d937b4e467761054cd3eeb5f.nq.gz
│   ├── ed0abd6a46727b16fbcb092255380e95f47fbe10.nq.gz
│   ├── f538a58791f9ba27db6f9e2a41fbc1f92650ba05.nq.gz
│   ├── fb0fa98e5be17b7db3e8498d6024c327d18760e1.nq.gz
│   └── ffd59c5d152668f3aeba561e54cff9e31e2596bc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7c75aa23937ad717390ffd36de2e5e965d9a3127.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 66 files
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

[allenai/intent-aware-lfqa](https://github.com/allenai/intent-aware-lfqa)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
