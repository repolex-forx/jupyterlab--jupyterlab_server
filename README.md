# Repolex Knowledge Graph of jupyterlab/jupyterlab_server

RDF knowledge graph data for [jupyterlab/jupyterlab_server](https://github.com/jupyterlab/jupyterlab_server), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterlab/jupyterlab_server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 475cfc19e0e69444fc7e3b0e41655cbeb32a8756
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 475cfc19e0e69444fc7e3b0e41655cbeb32a8756
│           └── chunk-001.nq.gz
├── blob
│   ├── 069b9113b1f66bfc2f293c0797a5bdd77ae8c586.nq.gz
│   ├── 094f020453578f66d11bb28e2018f6fccd0f6ea3.nq.gz
│   ├── 0cb7b894f49a2876e2b270d8211d9f2abfa3e25c.nq.gz
│   ├── 0cdaf10bf9ae26ce86870097776a48c72066c35b.nq.gz
│   ├── 0dd1bca512ef5ec9f5d1363ee131275476b7e405.nq.gz
│   ├── 0f0e050f300e011236273bdad297bc284c0e49e4.nq.gz
│   ├── 1956efa0ada7f5c40e97a7c97b980810fedc8a3d.nq.gz
│   ├── 1a0de5413b1f658c39290dc3b8ce4a4038461290.nq.gz
│   ├── 1a26658356e1f32e07f9d402876b212f0315857d.nq.gz
│   ├── 22b66cae49880e15062edf592aabb1999d7caef9.nq.gz
│   ├── 26c1c60e38b0444bff5610e9f26468aacb029d9e.nq.gz
│   ├── 28e40d8b87d3e37a1e703d5464898b4e72694eb2.nq.gz
│   ├── 2b5fbfc2a2cb2d7204201c704fc8eca9081e7685.nq.gz
│   ├── 2d30bc6b7ca5efa156d62731c4aa5bd022b1a7b8.nq.gz
│   ├── 2d97715bfd31f0cd79f2421594c441dc1a2f1cc9.nq.gz
│   ├── 2e0c0ea381b18c74fa1b755e75f990d44030e03f.nq.gz
│   ├── 2eb7dfc268b1a167ae3498facab1dabf5b2c37b3.nq.gz
│   ├── 3a2ed22aba22b12c27706365c3c9064c8eaa6e31.nq.gz
│   ├── 3b3e7fe3f9ade650d6010227490acb0f37f544eb.nq.gz
│   ├── 41764e778686a8f0a5420dcebe24e059335544c9.nq.gz
│   ├── 41e65881d31f6925aec7f07ceed1fcc57a9246b5.nq.gz
│   ├── 42834d5b5f4ae995fce1bcffc47e4321d0791c5a.nq.gz
│   ├── 47c6107fc63fb6dbe0b92717bb9c52a6e75ac2a4.nq.gz
│   ├── 499845ed52a21b251e9251e3300bd0642ed2f660.nq.gz
│   ├── 572992af6d2702f7ec4f0105470a720a185d6f78.nq.gz
│   ├── 599245867c5a2619bd452dfe4cca5f357c919457.nq.gz
│   ├── 5b5277e88fc24e658570fb61c9f5ec6d251a6546.nq.gz
│   ├── 5c25fc7cb6dfd6d1369643469e35d90b8c9b2ce0.nq.gz
│   ├── 5d0a7af20ec4c4824c5ad24a0d377c09a1afb88f.nq.gz
│   ├── 5df2cbbcc0885b210a4f95264786dba1cd99608c.nq.gz
│   ├── 5eb05e267a124aa808f41fddc49e5b9c541d5e5a.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 6206f990cb627653119a677211085bb0f8c07b92.nq.gz
│   ├── 638d4c371b802c167ad64e6785e58c19a69f835a.nq.gz
│   ├── 6ab81cdacf29c7fb9dc015befd093144c53da74b.nq.gz
│   ├── 6f7642e60c314f92428375f7f39a9b75aa024272.nq.gz
│   ├── 6f84b50fdbaa8cb08c08e7f9482882ca9377b339.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 76b1dbe8d42ef6eee308f6b6643ecd317c573c4f.nq.gz
│   ├── 76e5a8990a6198d3e875ff2abcac05cdaf03f040.nq.gz
│   ├── 7771b94963f2107e18a1daa8c86626834bb6d23a.nq.gz
│   ├── 7f2f7eb199628f82642b42358c2841bab166c558.nq.gz
│   ├── 8046017f1f6dd65166ed8829c1173404fafe91b8.nq.gz
│   ├── 828ba6c6e0ee6ac6346767cf7b2ffcc34270cf16.nq.gz
│   ├── 8313b135ca22d23da79ace83c26b751261126f84.nq.gz
│   ├── 8ab2c0c14132dd43f79abe9a78dcb5c36a6a5c2c.nq.gz
│   ├── 91da0ba78e679ad90dc1e408e9163f0341d91c6a.nq.gz
│   ├── 932116fad9dccd12fc87a9c61fd03b24824a1dcf.nq.gz
│   ├── 94347b9611e2be77437faccfc9e6210d7da62fac.nq.gz
│   ├── 9de5733895226a108c183da3ad75c5d5717f94c1.nq.gz
│   ├── a1f49c53f75cb72b938e9a947add54074bdba3c0.nq.gz
│   ├── a2f2ae5057d092af0527a43085878e5ccefcfb8c.nq.gz
│   ├── a3fc4e3445bb648073b95761c12ee6004e47a4ef.nq.gz
│   ├── a8e33e1cdf7fbc0182500455ebadf45c01216e1f.nq.gz
│   ├── aadd4df1e7da6cd4f28827de547f0adea9408fa5.nq.gz
│   ├── abd32f243c5682c644396242bfaea180d8c87e50.nq.gz
│   ├── acfcd5b1d798bd21882a192e028986687391573e.nq.gz
│   ├── af6ffe816b4ebb4a37b135d2eac3cc9653a53d62.nq.gz
│   ├── b0950f0a28d21bef1bc050551360a8a45b199b3c.nq.gz
│   ├── b3a25bb051762bc6ecfd064438cd5ab78d6739a1.nq.gz
│   ├── bba452441196a261f0d683af6ed09520ee638088.nq.gz
│   ├── bdecc943e348199b2dde0f69d93ba1bbe838669d.nq.gz
│   ├── bf310c75d223c0c976c46cd2a6ef1e61aa2f8eda.nq.gz
│   ├── c1463008fe10057d5339c9611053564131449401.nq.gz
│   ├── c1881060de286b6e65824cf42d336f09ad37ce7e.nq.gz
│   ├── c258ed3d057b3ad71bed7fc92e4a763aa62eca4a.nq.gz
│   ├── c5d4a03a8849a850162506d5af2ee9f7918bbaf2.nq.gz
│   ├── c60aaa947c3dcbfd880192342bd53548d09f7aa6.nq.gz
│   ├── c7185d66e04ee945bf83f2e03ac4550428912849.nq.gz
│   ├── ca0d3a62cc2a1909bd06efdf5660be4f6e4e37da.nq.gz
│   ├── cd4fad6fa2c9d37b498f7342482bdf0c6c1db62b.nq.gz
│   ├── d80881dc5e3e67798b3d09d6a7d142285b298d24.nq.gz
│   ├── d8111e1b177ea083dd576138dd2aa15fb9eac34a.nq.gz
│   ├── d9b199f0d56fe7ff8571d6c9b1b5f23bd37d18e2.nq.gz
│   ├── dce31c806c8d807d73e9ecfeb5bc863564c45691.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9d9e1f04e1777d027b30632887948340a5ab013.nq.gz
│   ├── e9df571e3e37b2e6a5c5ca472ca5252001dfa3ae.nq.gz
│   ├── eb26e99a0fba3377a4c3513dd9ea519f58b38a4b.nq.gz
│   ├── ee3e8e25127e46cc60df6adb474943acb71e8fc4.nq.gz
│   ├── f0c29643c122bb2cf7d643de7e85545a3cb0b2ae.nq.gz
│   ├── f16a63fb0be5bb7973fe8f25937adcd31784bd76.nq.gz
│   ├── f3d247cbdbc1b0441a2fd7b76a4de1f162e5a39b.nq.gz
│   ├── f63f66f4561fa6179bde2f58dd3f0a40005cb354.nq.gz
│   ├── f741d8f979aeb8c8b71b59f31758a522f00cc67a.nq.gz
│   ├── f80c9ad2d736cbfe56b48e0a0356f741d02e07c1.nq.gz
│   ├── fa46000fc04397263d38e75e5c1a3bc302938157.nq.gz
│   ├── fb55ba62eda212c2bfd164144c01917c582bfc7e.nq.gz
│   └── fcdd3e88b66ec9b10362685146ef2a36088e54f3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 475cfc19e0e69444fc7e3b0e41655cbeb32a8756.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 97 files
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

[jupyterlab/jupyterlab_server](https://github.com/jupyterlab/jupyterlab_server)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
