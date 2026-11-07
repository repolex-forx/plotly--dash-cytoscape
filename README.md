# Repolex Knowledge Graph of plotly/dash-cytoscape

RDF knowledge graph data for [plotly/dash-cytoscape](https://github.com/plotly/dash-cytoscape), parsed by [repolex](https://repolex.ai).

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
rlex download plotly/dash-cytoscape
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f96e760f3b84c3f4d7ecbfaa905e9d57c698456d
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── f96e760f3b84c3f4d7ecbfaa905e9d57c698456d
│           └── chunk-001.nq.gz
├── blob
│   ├── 012e0a99c835ccc4ccf348574c86e61abaad7251.nq.gz
│   ├── 02f4ad874d125fbdc8b597c7c64bc3380decfeca.nq.gz
│   ├── 039e1a59594b894cc4722bbcb93d24709054fca0.nq.gz
│   ├── 03cbcdfb134ab09a1a60de036f2b2a4c42d344c6.nq.gz
│   ├── 06c2b8cca191054bc5e4916d22db61d8dfde4103.nq.gz
│   ├── 0705f1279f4edadb5d78caac2d6642820dcd9205.nq.gz
│   ├── 0712cd672a471272a3ef10318e6780d4f338faff.nq.gz
│   ├── 07af815c24f1b5641bab6f3a06729e23c533f775.nq.gz
│   ├── 0b69d8b0da9529c0f6c539dde322b31583fa6969.nq.gz
│   ├── 0b745f35d2121e757c81d8b96b61cdf8db8cb327.nq.gz
│   ├── 0bb1753afa634b98fe05d36c31fdc3425a5e3ff5.nq.gz
│   ├── 1128faef6e7891f56e109e7a3053ba651cd91739.nq.gz
│   ├── 15b9af60101b641a7fce81f49b722264a167b719.nq.gz
│   ├── 168bbdd34c37ba821a54d7e519f71ae4bec64379.nq.gz
│   ├── 1a72a25ff5714fbb78c818c3d2d0280ce89f85c4.nq.gz
│   ├── 1aeca20809082c42aa760f6dcd5e5085607d29d7.nq.gz
│   ├── 1b4772d09ff8061e308078dbf1d7e92a8e55993c.nq.gz
│   ├── 1ba95aec5fbf8f71aea467417221957a5fe8fc1c.nq.gz
│   ├── 262426c09211e0617db94ef40a381462404dec22.nq.gz
│   ├── 2664ff4b34c83fc7c0a8bb7c696a5c774725a670.nq.gz
│   ├── 2851bcda3f5076b7f2e9523e4ab06f062d88b4f9.nq.gz
│   ├── 2b7bafa5fa47672487a998df854e36347be43f58.nq.gz
│   ├── 2da0189f35a1cf923802476cbc3734098de23792.nq.gz
│   ├── 2e7c2d1eedc49c8b0fcf0669c9db87b54f66388b.nq.gz
│   ├── 2fc736b3dd55dba3cd46c8c8de57bbfb7aa7327d.nq.gz
│   ├── 2ff2c3db521ddc6b370ab0282ff3ae34fce12e49.nq.gz
│   ├── 3668325937707608977555a301ba84ebeaebcee5.nq.gz
│   ├── 38e319a0b1ade3145bb1fbd5ae4c17db68935a7f.nq.gz
│   ├── 41a91215f2226c5cb00d9bb7363106b789ecf170.nq.gz
│   ├── 41e7511ee9eb56dc05bc984f851fea5f34699799.nq.gz
│   ├── 43344f6cd3d389b767f7ecc11e46ce1e5fb53b6f.nq.gz
│   ├── 43ac2a0a2f455e0018f5833192fd603bbf30526e.nq.gz
│   ├── 461711b8b7ac99f049ad652574e491a793e19f94.nq.gz
│   ├── 466144c43d8899d814eab0bccaddbbc738ccde1d.nq.gz
│   ├── 4915c743fb794792d0c185a9d824e79fcc9d906a.nq.gz
│   ├── 49be0d07bae99d15e6e6a68dc68e8672f6ddfa65.nq.gz
│   ├── 4a8b0edf106be3083227916b26cf0a4ae24adbed.nq.gz
│   ├── 4ab551423e007b963003efc6ada3d68369ddd079.nq.gz
│   ├── 4ac77a6c5ecb325d87635161a1368ece5aaff771.nq.gz
│   ├── 4bcfaed4b6bac674c76d082cf43e0b99b0fa0b61.nq.gz
│   ├── 4c940d096a87c252f9c47d3982e3e00d294ef934.nq.gz
│   ├── 4d418cf9cb3389801a0e738ea1ceab97e309a7ac.nq.gz
│   ├── 4decc893b3ed0a69adaef3ee48fcc380bcf8ea7f.nq.gz
│   ├── 4f5d886759ec557dcf95e6bb2bd41c3026f2f30f.nq.gz
│   ├── 50670c48e8390ba59f76fefc3787b9d6f3621507.nq.gz
│   ├── 51a65e9c4a641ec8603e81759ca7e92d4450350e.nq.gz
│   ├── 522787ccfea645d00650a62ef785bc2fa23ae69a.nq.gz
│   ├── 535e088b61a6d3c0ffeae2ff60959485d1180582.nq.gz
│   ├── 575d53555470d2ba45b478d62d109ac16b5880ec.nq.gz
│   ├── 576d28ac0cf1aa58b8fc22e5570232ab69d200fa.nq.gz
│   ├── 5b82dda80b628168a8847ac79713d1b7adcd77e7.nq.gz
│   ├── 5c2821723dede39ce48986ee145643a09597148c.nq.gz
│   ├── 61c582818d0a7f6c65d4a7acb3e50cc56b44210c.nq.gz
│   ├── 62bbb04396d065458b2b0f66a29d3025bfcf54e5.nq.gz
│   ├── 663c1364b0a6895789e24947bc2269ac08044835.nq.gz
│   ├── 6678839bc95d917796db9acf2de9fe3f431a1640.nq.gz
│   ├── 67abcf6c1306897fbc89937db4baac90abcc7940.nq.gz
│   ├── 6b7d21e51757514f772b16050690731b9a06832c.nq.gz
│   ├── 6ccb6219546f34733ff38aa8a7a35bccf9cc68ef.nq.gz
│   ├── 717c572fba2ce0d6ad69f465b54d740e0ec14155.nq.gz
│   ├── 71aa47520574f3fb07e91468adafb5d34d0945ce.nq.gz
│   ├── 73977b4453fb8c1fc2209b78ba6ba5f3af2c2ea0.nq.gz
│   ├── 7934f701f124d7f1907c8e9851995600bea7530d.nq.gz
│   ├── 7af6dcdc5beb529c6e2380471d2bb441914b1ff9.nq.gz
│   ├── 7b0c995511ad1d9a180870c8276f4f9058b05ac3.nq.gz
│   ├── 7b3e1e52f61bb52685dad890e86b352b9257a2ac.nq.gz
│   ├── 7c39ce16fef3321b01050eee2e43d7442814cd7c.nq.gz
│   ├── 7dd63c9cce316c96a1790a280124943c68632eeb.nq.gz
│   ├── 7e1f11cf20af3ce6dc4c5b1d5505b160d142438b.nq.gz
│   ├── 8045befb2220e83ec3a075f1e69801b4e091720a.nq.gz
│   ├── 81d1087752c29c6a3a3535130fb0fcebe1bdc76d.nq.gz
│   ├── 820429c3ac4f2fe2fb23b3ce27320d4844b9d3f5.nq.gz
│   ├── 82723494c9508d7fc311970d06518d48f26ef725.nq.gz
│   ├── 83e0b2b9710ce5edf2b5fabf30cb86c729514934.nq.gz
│   ├── 869fcc646c0e635fb6b77057ccd974b784005fd5.nq.gz
│   ├── 89c838ab33cc780fb035076ff76b0ac75947fbfc.nq.gz
│   ├── 8b6ae0c49c389a8986b3a53ded705647f6795edb.nq.gz
│   ├── 8e124be2ec45a5d9ce529cedeefa4e993b379f18.nq.gz
│   ├── 919dea005bd3c4e752cf09d72afa2a2422eb6127.nq.gz
│   ├── 929726913ac9c579b94dc12a2b08d65904d61e34.nq.gz
│   ├── 983831eee9f63f2e2561d0b03fbde3f88cc03107.nq.gz
│   ├── 994f0fc0d672d5ad6bb1d67b6ae75af31270b1a4.nq.gz
│   ├── 9a1d9086ec9c8d2dcf13efd0456364e76e578753.nq.gz
│   ├── 9cd88f7cb36fd4f202ee14868eca9241d4b4d24d.nq.gz
│   ├── 9de28c8ed64420307f4b830df92df3700b7614b8.nq.gz
│   ├── 9fcebb2c1d1a1dc7220ec8c97433025ce988e5da.nq.gz
│   ├── a3c93d83b99be151f9a67c84cbb83b2140a952af.nq.gz
│   ├── a4efff0cba6e8a976c16be999d3906c6c176a7da.nq.gz
│   ├── a55933585d92460077497291aaae8f88077ce491.nq.gz
│   ├── a7af28b80e56f0ad2e159d05df56e1def86d406d.nq.gz
│   ├── a85f2e0a99cba30387d09765fbf839a16902668b.nq.gz
│   ├── ac6d0f65bed8e7df0b8635c1c0982847ee76d8f7.nq.gz
│   ├── ad3dffc9b6b295361e7ef30c96d9398c3b79a3a7.nq.gz
│   ├── aecc347807dfc129af5485787e0ce9bc4e92faae.nq.gz
│   ├── b348c5a9d91e07b60058e205bba722036314dddf.nq.gz
│   ├── b41b674576a19807e967dd9712b094d5001c486d.nq.gz
│   ├── b4afd6774362ec3434b01e81a2bf375e2985d51f.nq.gz
│   ├── b503020c7285fc329458c1668c556ac70d8c8840.nq.gz
│   ├── b50334668dc77ece648016421f2b093ffc93c8f9.nq.gz
│   ├── b5330025db00dfe7e82ccfee19fa156a5b66718f.nq.gz
│   ├── b6eab49db8e864955da528adedd93e675584a60b.nq.gz
│   ├── b7bb3edeb51ddf16123ee94d8deace54b9804032.nq.gz
│   ├── bb640ed86142e00b3cba743ffb2f6ea07856b987.nq.gz
│   ├── bbd19ff1d1687e4eeb219fe0ba3eb2aeae4014c8.nq.gz
│   ├── bf8c82937a1d7a17a030683817c5d7bc215e516a.nq.gz
│   ├── c2cb3de8f61e6d2782506b25c162aa55762de392.nq.gz
│   ├── c4192631f25b34d77a7f159aa0da0e3ae99c4ef4.nq.gz
│   ├── c94887bf93f8c9074257bf2095c89d1eb862c526.nq.gz
│   ├── c9ff0366aab84e477fd593cedd524817a826ee0d.nq.gz
│   ├── ca79c61b226cd4adefefdd51318bdaa972a562a0.nq.gz
│   ├── cab4bab1a9cfd905fe8ce69fbf93e116dd013b6d.nq.gz
│   ├── cb20df65d00fcfc6cdc3e951ee312090c384610b.nq.gz
│   ├── cb741ae64b960e6cf86b1e6d7863402f296e7b39.nq.gz
│   ├── cbc12639aabdb4efbe8632a41eb6def97fd78242.nq.gz
│   ├── cce99a7878baf09cfe405043c05ad44d50c20bd9.nq.gz
│   ├── cd5c4b692a818d15903ac948ca816d4eaa0d14d2.nq.gz
│   ├── cec59b670ae05ea5ed416789fe24db07e3b49b62.nq.gz
│   ├── d669fb7a71a0622cd7435f1827ac20ede610bfae.nq.gz
│   ├── d9de17b68064827d28d705a74f8f489b742824bb.nq.gz
│   ├── da14208fc71595ae1bebd6a5055ec1e2a0291d42.nq.gz
│   ├── dbf08686d52e3bbc5c7b65d6b921b83814f0ed73.nq.gz
│   ├── dc4238921ad6e158b6b8620bd97b11655c176cba.nq.gz
│   ├── dea2370ad44e9d00332338fcebc5d44e634c5367.nq.gz
│   ├── e016a4cd12f40e0296f6825165a992b42ef69764.nq.gz
│   ├── e1e6383e120e9c53bb24680ed54a863f6f656b7b.nq.gz
│   ├── e1e7d9e8cda73dd1fb66d15540dfb194f69ac9eb.nq.gz
│   ├── e20180e9049d216cbf72881a1e4f1e4038578370.nq.gz
│   ├── e59dc5c40fa9094e4c42fb2c6b3ad87ae716a6ca.nq.gz
│   ├── e626cb3bdca25795bd67b3fdb35a920d8c56ebf2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6e6b36a8bc65b7bc5806d2c7d10f1ab80d47461.nq.gz
│   ├── e978749a111ad8c7bda54595106df63096185d14.nq.gz
│   ├── eb81a49a94228fc85213e5bd9c8d45722b89887d.nq.gz
│   ├── edbb5db2bfb559a89440ee7508ec012f802167be.nq.gz
│   ├── f07a49b3fc4cb08c3dc9df472bab7d2dff8bc9a1.nq.gz
│   ├── f2e80b9216cf4c2875552db99d03e5b6d088188f.nq.gz
│   ├── f3297ad7ebcc0b161782000c4fbde6b694982a5f.nq.gz
│   ├── f3a47219654631ffd54535052c7dab64c4d1e6a4.nq.gz
│   ├── f3ff1bc2ae1553ab34a5e6180366e85c16e2844a.nq.gz
│   ├── f65df2f355f749cbe3f86991ed86668969abf078.nq.gz
│   ├── faf019d3c209e0ab2cf84c08d13ee03fd6e65b12.nq.gz
│   └── fe4a25c57ce5cb61c71670c9927fedeaf9041470.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f96e760f3b84c3f4d7ecbfaa905e9d57c698456d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 151 files
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

[plotly/dash-cytoscape](https://github.com/plotly/dash-cytoscape)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
