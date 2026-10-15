# Repolex Knowledge Graph of executablebooks/cli

RDF knowledge graph data for [executablebooks/cli](https://github.com/executablebooks/cli), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/cli
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4510602b4326628b6fe87d666af5cb9d9bf345a0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4510602b4326628b6fe87d666af5cb9d9bf345a0
│           └── chunk-001.nq.gz
├── blob
│   ├── 002446d6e867c2715faaf75b00b98f034b269f0b.nq.gz
│   ├── 0243b78b0e929e4792408df9ac8bd0245b92b055.nq.gz
│   ├── 046d966064775190fff4f2a095c83b48a237e5fe.nq.gz
│   ├── 06b099f0341588f40a4de19e6f659d012d62ac47.nq.gz
│   ├── 06d56f40c838b64eb048a63e036125964a069a3a.nq.gz
│   ├── 0dc89813dc10ed07777226c26d348a19ce3afb93.nq.gz
│   ├── 0f6aca77a10430e6ee78d91d56085769882b9dce.nq.gz
│   ├── 12ce16d489fb79421318107d2b06043433f279a4.nq.gz
│   ├── 16af933cd66c632ea672b0a89e3822365fec598d.nq.gz
│   ├── 19ce5e00571c48e1d2fff59b8400cc9701596dae.nq.gz
│   ├── 1a18a312cf48f89100fd5dfa9a3408ba2eb57bc9.nq.gz
│   ├── 1c1cec6a93a212ad500c504f9032a8c46512300b.nq.gz
│   ├── 22f4c33dd7cec150572c75a9e1649d011adb2602.nq.gz
│   ├── 22fe5447d161beb8b31669e5f24532021ff6316e.nq.gz
│   ├── 260ccbac5f503fb2a9fc8c5685847b1a87f8e142.nq.gz
│   ├── 2679ea1070feb5450a46f1dcef0adb50e7e02df3.nq.gz
│   ├── 2773a5e4b161f555ac8f09ab5d7793a022bebe3b.nq.gz
│   ├── 2ce91efbdc6acda003d73b627e6d2e3e90c62d28.nq.gz
│   ├── 3031fb663ced6c64c01e303852b378fdb9b815df.nq.gz
│   ├── 32afaa52a84ecb410704819faf92ebbfe70632e0.nq.gz
│   ├── 3390ed92e1bb1fa5c3a2925d4f9839a098306173.nq.gz
│   ├── 33b23e75a58a8422e9d7efd39a6bd640d649f202.nq.gz
│   ├── 38a1fd497f29e0b298e91a4be75516cc425ce489.nq.gz
│   ├── 3a9d6a285c956c7d96438591fe2d6669f20883b6.nq.gz
│   ├── 4066a8bb6c4508d5c8dbb22c7e5ffc9d889e81b3.nq.gz
│   ├── 40e02958a5a43cfce1704ef8666855ff48de3af1.nq.gz
│   ├── 42a5696aee34c7f3260f65ef4ea780f60f042106.nq.gz
│   ├── 475ba515c04b5b7cf67a1517430691febc39a32e.nq.gz
│   ├── 47c42a6b971bcaaa2364c81e37f483bcfc32df5a.nq.gz
│   ├── 4970db0374a0d438bb764066e1bd4906dee87278.nq.gz
│   ├── 4cc1e25bb710a60ec0b00ff7f8e09e570bf667e6.nq.gz
│   ├── 583ee718e0b647416515c3ef147f55abb898300f.nq.gz
│   ├── 5f71834a2c1df049dfa7a0f6350907d2d587e17f.nq.gz
│   ├── 6266dfc2cf4091f99fa4f63cda519addb655c72c.nq.gz
│   ├── 64b3cd463a8a7f17dedb1aa41c8d2125c8c2a033.nq.gz
│   ├── 650c989de7ebad6c933859e1c0293a71c75321c9.nq.gz
│   ├── 651a75a8dd906f27e5efc63ccb32ee38eabd92e8.nq.gz
│   ├── 69e5d74e7cb85f36549f658cbbd13347082ad9ad.nq.gz
│   ├── 6d2439f10dee7a194f0e6ff613c9a2a3d37a9129.nq.gz
│   ├── 7173cf0544747aa0234fe4c3cdc542dc7a3f7a79.nq.gz
│   ├── 7320181a6d17a4a747b5d586708a0390a18fe793.nq.gz
│   ├── 73fd7744c5b29243da56ed5ba686ef62a5e5e9d4.nq.gz
│   ├── 783ec6aa5afe2f0a66087d01a112f543e1ed287e.nq.gz
│   ├── 7956c5e7b8a20a01d4cd44709b059e153d0d7718.nq.gz
│   ├── 7da5a6c2fc86a845d0e9fbc4de64aed39dbad18f.nq.gz
│   ├── 7f0e51db3fd5846818a2c1a4115e9ddf36cdfbb2.nq.gz
│   ├── 8596676852c2c74157121a91e459ad4ea6637608.nq.gz
│   ├── 883522135db369cbb4c7d8176244ff147a31a203.nq.gz
│   ├── 88ff9c604182b8540a4ef05cb11804ebd5836b5a.nq.gz
│   ├── 8d4f33c8d12153a837aadc04984ffc532680a43b.nq.gz
│   ├── 8efc0930438b8a48ec76f8229a30f22d72754e66.nq.gz
│   ├── 90db56388c4a6aba092337924afd63e9b72838cf.nq.gz
│   ├── 91253d78b79b6c7e80ab242d30a36cc654c3d4e0.nq.gz
│   ├── 923a6012efd0d7a219eb0616501d2a8f7fad7074.nq.gz
│   ├── 9329df5a5ffd8e67816b908b78b64e754eba56d5.nq.gz
│   ├── 944336208cd246129f995d8ffc9e40a9b9dcdec0.nq.gz
│   ├── 97c25207121a0057d3448f38004c2b3f8c642e8b.nq.gz
│   ├── 9a4b3e63e9ec5992fde3e71fdf1d321bd3715d56.nq.gz
│   ├── 9b04782d9fefd0822d737920fb4e78c6d0f7f6a0.nq.gz
│   ├── 9ee208afa65190ff9c19a91285aa5f8711ab76ab.nq.gz
│   ├── 9fc0428eb1dcb5e1ddd8b5b547bee3f517a4e4a6.nq.gz
│   ├── a15652b30ec18a56e60312b6c975774a7ea2b5fc.nq.gz
│   ├── a22758ec0a645e22b5d3e4aafbcfb91eb5c570fc.nq.gz
│   ├── a3df988114b9ae7440abcac7e61bcb9a98a57aa9.nq.gz
│   ├── aae0cb5e034173e86ffb38ae6bb00fc437680e6e.nq.gz
│   ├── af2604fca557bb4378b55da34aa07961c19bad03.nq.gz
│   ├── b2831b43aa74d46ab0e4dbc5fa5e639188df4e41.nq.gz
│   ├── b5743bf5a303992e255d1fdc2f9e4496a85fae55.nq.gz
│   ├── b8faaa876360ccd69b61cba629b4c0257c7edc25.nq.gz
│   ├── bf728ca89f93b2d22b2673c6818606000334bca1.nq.gz
│   ├── c5089914f9463c4647f9866f1bc3fb61345b2cf2.nq.gz
│   ├── c657de6921d49176453b055d6585d114daea6044.nq.gz
│   ├── c65bb687fd70c9e084a79faea39ea793678104e2.nq.gz
│   ├── c6f847a2bc66448c6aa69283fcbde32dc9619174.nq.gz
│   ├── c7f19a23e85289a11569a2ac48efea548dd89c9e.nq.gz
│   ├── c8a651891c9be95c69d2820fa1a13af96f95d21c.nq.gz
│   ├── c8f1defc6733b8cdf752b3964abf40a9615fcde3.nq.gz
│   ├── c97774f1f0323f2b1f8bfd913d30e9fde6f94e4d.nq.gz
│   ├── c9cf2c4d2e49c7498afb487623fc93fac94510f0.nq.gz
│   ├── cb42edad0186e3cc9a17e9de9016d970b7bf2ef6.nq.gz
│   ├── d0034b6d53362521c64ca1d479dc60277757af6c.nq.gz
│   ├── d337d30ee5913651e78ee0d2cc2f4dbc59ba2559.nq.gz
│   ├── d53a19bd21cdb009b2a8e3aa67e4bfef15ff2107.nq.gz
│   ├── dad1857a130ac8bf600988d964d5bba844e2e49a.nq.gz
│   ├── dc51ce9f2e86d7b81006d52595139a987ef2828c.nq.gz
│   ├── dd52762000e875cd98523b855846cfc9226c582c.nq.gz
│   ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
│   ├── df4c02be79b86581ea9ecee155722819dfafeda6.nq.gz
│   ├── e0d9c214b9c4b9af2dc009bfd5ba969cbb477c5e.nq.gz
│   ├── e553726f8b386d015a4faff8205ad7e63d3944a4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb2cf42e707a8bbe9f9c0c661f9c9a6265af575b.nq.gz
│   ├── ee49a745dfa0de21c255d8e6f92cbb2c99863ed5.nq.gz
│   ├── efe5d02e0a8c0d4323e53f1228ee24be77a3ebed.nq.gz
│   ├── f1fe9249760cb56b825768527323a122706633df.nq.gz
│   ├── f2f5a47d07e0a4b2e9d754270586bc6b3ae3b36b.nq.gz
│   ├── f35e4a4d875c5786bc70be19e068cff638b1ea92.nq.gz
│   ├── f7bc47c7e1e03c14427124bd7a6fb7268dff8f11.nq.gz
│   ├── f8bdc4022e1732ddf9c960363ae311ea9d573e81.nq.gz
│   └── f9bd1455b374de796e12d240c1211dee9829d97e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4510602b4326628b6fe87d666af5cb9d9bf345a0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 108 files
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

[executablebooks/cli](https://github.com/executablebooks/cli)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
