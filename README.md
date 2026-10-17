# Repolex Knowledge Graph of dpkp/kafka-python

RDF knowledge graph data for [dpkp/kafka-python](https://github.com/dpkp/kafka-python), parsed by [repolex](https://repolex.ai).

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
rlex download dpkp/kafka-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cd3f7938e1c119fa1e78c333778767606c2a802f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cd3f7938e1c119fa1e78c333778767606c2a802f
│           └── chunk-001.nq.gz
└── blob
    ├── 00000e6f8c76aaa3e1833e6f135777eb54055fbe.nq.gz
    ├── 0159240c3263a9fe212b27111b6f4ba7c6d3fb92.nq.gz
    ├── 01a34a2a1ae579f15f97c3ede297c2e3e7489011.nq.gz
    ├── 01e1f0f5ba8297e0fc92e8ac2b3e134f7bcd9a73.nq.gz
    ├── 01e6a4d441091d6621bac7df1b644e2e6102bd99.nq.gz
    ├── 02126c5dc944a88d564d8a2a09647499758bfe08.nq.gz
    ├── 0228733ce6bb039bc421af8b541fccc9d28ae24a.nq.gz
    ├── 02bf80adc028722046b49dcf6bc88c9ee2c69d37.nq.gz
    ├── 0369b756f0845b4e448adbe05272965b02e5217b.nq.gz
    ├── 040a9a4c6928ad15d7c1a8d0a007e884d9943390.nq.gz
    ├── 0472d4e84f4ea2687994ac84f67b60db66e0ac6a.nq.gz
    ├── 04a07c928c94f3545fd86aed8ea04535ed1ab48a.nq.gz
    ├── 04afb61ae44488eccb2bc596003770bb4ecb3527.nq.gz
    ├── 05b8ac3d1e7eda960504b66dc5f54a6b72925f7d.nq.gz
    ├── 05e3e016ee7789b795cc3ed5f516099332e9d69b.nq.gz
    ├── 05f02a7905cb1ac4d674adc4e7f1f80709c17596.nq.gz
    ├── 065d871a84dcfad5e0393316912a6ef668459be3.nq.gz
    ├── 0710ebf7b8727ef809aa3201d4346a28c83c4fc6.nq.gz
    ├── 0757fc1098ee1ec45a46d611d14d04b4b47fc917.nq.gz
    ├── 07ee7010e5e540845a50816921723ca193e9b40e.nq.gz
    ├── 089278a7eeeedff21b755a7864da5e1d07657c68.nq.gz
    ├── 08bf768a950f706726bea2368f86e85cedaf54ed.nq.gz
    ├── 0950a0c07ddf04c0524b9f019a052831b6b62f49.nq.gz
    ├── 09ff73ed91bcef51625de628122ef9e599b1d732.nq.gz
    ├── 0af6b6599a44f4010c567645872245570a6fcc9c.nq.gz
    ├── 0bd83e5f6e079173d4a2f5d1fd8614347684973f.nq.gz
    ├── 0c855fe984dac9a144013fcd093f3bf29b536c16.nq.gz
    ├── 0de13bd281291584c9da9ec3e234310a59143b03.nq.gz
    ├── 0e0e850bb3c755b7fd393c390a8dd045662d7603.nq.gz
    ├── 0e3168794687eb39cd920e9cafbb7881ebf96889.nq.gz
    ├── 0f20f9ecaf40ba179ccebc902e8116551c91ec5d.nq.gz
    ├── 1017f2443604740abad4dea8c1a69076cc6595b2.nq.gz
    ├── 1063a704f5eebb80adf4a61a47b4646e45510894.nq.gz
    ├── 10e4ebd8c0a0831be6ec472f54bd04916974a222.nq.gz
    ├── 10ebf7c9b3708387cfa4c6e98d1d9dcd089e27eb.nq.gz
    ├── 12d0370e8b2fa47cadae06f6a9b45e2a8f4b1b6e.nq.gz
    ├── 133cfa8765f347a97aa8f8b3ecaf32c7494a7a83.nq.gz
    ├── 13772b7196357577c114b7343af49ecaafd77dc2.nq.gz
    ├── 161d68e44e863b20fb5fdc51c71d70c4e4406625.nq.gz
    ├── 16432d08dc0e7ab8b1041508ab487f396af7f58b.nq.gz
    ├── 168cde03ba34123c3497dfcc1c510c8659def3b5.nq.gz
    ├── 179b393555ce629e22531d93bd66f827ad4ffe3c.nq.gz
    ├── 17cde62717d1e754fa690e0a40fe7dd7b9b8b763.nq.gz
    ├── 17f0de5ba25dd99dc22c9a72c37ed882aff087ab.nq.gz
    ├── 186bb43e3c9395fc1dddaed81b67296fba948393.nq.gz
    ├── 18efe4369c04af46a83adcef14aff8fad41ea994.nq.gz
    ├── 1911b1ec33d6f9b803564c45edc0a3680361e630.nq.gz
    ├── 1917155ece38f57e7b83c547f6bd845b176c59c8.nq.gz
    ├── 1974b67f69fc32c0394389149fc654dab6b69864.nq.gz
    ├── 19c03e223ba4ac0b28ae85f7485b92e119e8ff65.nq.gz
    ├── 1b24d6c52cdccd1cd6fde58030c1da9a54149340.nq.gz
    ├── 1b53df27757f28b6709ac8f8ecf7620750003a47.nq.gz
    ├── 1b71c4114d47d6e0eb27532135d34b454988958d.nq.gz
    ├── 1baf3b6997c95ee512689882323ed9ce7ae65848.nq.gz
    ├── 1be8c7d09ccd524639114f3b1fef78d06530df38.nq.gz
    ├── 1c4992185e721e20403f7edbeee3e250219f073e.nq.gz
    ├── 1dba54863f9262252667a270625c287f75fc2206.nq.gz
    ├── 1dfc77ac40c7fc961d4ef7025d38af5bc049c678.nq.gz
    ├── 1e1cd6f3d63000521d08a4b96c10fb9afd1c30e0.nq.gz
    ├── 1e71ee7882782e9311ceb3e3f4a9b69b77d128b0.nq.gz
    ├── 1ea5c978fe28efd15e8738714422fc2759459c9e.nq.gz
    ├── 1ef1b5b7562eb5a35ac34d3f41a4f1b51ba3ac02.nq.gz
    ├── 1f564144f300010504083480a7b2115b57d6ae0a.nq.gz
    ├── 1fb21e4de13476ce411f3e7cf767dc5eff809e75.nq.gz
    ├── 1fb3e050e16fd746694584a0762a9e7ad11be4a8.nq.gz
    ├── 205933ef49aea285d511f03b7c1e869a151a308b.nq.gz
    ├── 2101fd7ca382cf935cac2d919742326c0f2c89d9.nq.gz
    ├── 22427e9679ae2d94a5052eb7c1f450675d945ec4.nq.gz
    ├── 23232649c3767fc45385b6e418d4049cc83ceb2b.nq.gz
    ├── 2336568918f23d4cb7ef5b01465eacb52545d1fc.nq.gz
    ├── 23883c154fe638d9faf49e6782408dc53f40996a.nq.gz
    ├── 25c3ee4c3b0acd48e81719a49a938d2806b0339a.nq.gz
    ├── 25c9f32be24e577afc784cd6ac2b6845185efda1.nq.gz
    ├── 25ddc9bccabc9ad8934b5336cafdffb6974d8470.nq.gz
    ├── 26ebc36fce2cecc2e198eb12c6c2b79186069e6d.nq.gz
    ├── 272b0e5f25d192b6e6b4c01c04b86bc24d4555ea.nq.gz
    ├── 2807f40c857af9d46b8582a1d2d98b110f795b83.nq.gz
    ├── 280ba1103b437562f8e71ea0374c06eecf71de8e.nq.gz
    ├── 28a7ab9367479dfbc06ba8ce82cbf2d6000a2e42.nq.gz
    ├── 29a4f3b417be14cefef3f59996cdf4d6c1dd9d38.nq.gz
    ├── 29b4949982d89ba4e18036336f99ca85c21b0566.nq.gz
    ├── 2ab20c37c689d6388bbbefd6df51762e8026118c.nq.gz
    ├── 2b1fd09b199eb9151c62080a2ac8172165f054f8.nq.gz
    ├── 2da4982da981792e7433bb6a368204e0eadcb465.nq.gz
    ├── 2e15dd997bfbe2a4fcc74ade67850d9417333b42.nq.gz
    ├── 2e30de0b28dcb93329424cdcd517a8fbe795f1d8.nq.gz
    ├── 2ee9cb13fd4e2860a6cb6ac9b95528cdaa85f664.nq.gz
    ├── 30e965f9d08604954eaeb752437f2d09768b21f2.nq.gz
    ├── 31afdb1a32ae8dcaf27843d1b1bf553711971df1.nq.gz
    ├── 31dbf0d704ae126a6a14f5c1fb63ce6142bc100a.nq.gz
    ├── 322dc099c18915ae692bc51af7da7245d5f7c082.nq.gz
    ├── 326b85d17769d8a69c7384d00c3c74f3eca94f54.nq.gz
    ├── 327cc0ce69299c9d9f6a0aec4a28068a13b70d47.nq.gz
    ├── 3332a3a1b80c891814f7795d3b869d06f0b94af7.nq.gz
    ├── 33b0054936ed09d897d487a123258eb0301091b5.nq.gz
    ├── 33f989c372873ad865f9e7a5be0c60dba836ff17.nq.gz
    ├── 340456b86b07f45e0b626b0876c283418b1dc5ac.nq.gz
    ├── 349f88b7c64d2ddbe8003a25a29824f738f4af36.nq.gz
    ├── 35572615b141b8ccf6da459fe99f6b96ac653946.nq.gz
    ├── 3577df39188ba8764baca6a974d9ea14cac60539.nq.gz
    ├── 35c9eb28f9c473e1899142e655485923e98fd275.nq.gz
    ├── 3681d71ca8a776be8c9f0af4ecb49bc4a557c9f2.nq.gz
    ├── 3683aab4dda2948e9ab7ba99a28971b1d0377deb.nq.gz
    ├── 36967447437382107f33a6115af793a8213f4004.nq.gz
    ├── 36b746dad7bceec3ee536711be0023a9d7a65048.nq.gz
    ├── 36ce87968ecc8f433d40955b27c4464a28fc33a3.nq.gz
    ├── 36dc05ff60ca421d5efad5032805e5fa38926714.nq.gz
    ├── 3707bf735e79bdd84ade5dcad2807fabf1d1bd24.nq.gz
    ├── 37e19dc54b03a9a29c88c44e6e2c2b173578934f.nq.gz
    ├── 38fc84423de5790840b17a0410c1f3f0b87ccb18.nq.gz
    ├── 39062c684a2f606278ddfedff26c7ec79a5f0075.nq.gz
    ├── 393094b629c57eced81c32bc7a5dfb096006d13c.nq.gz
    ├── 39ad7ea4de82bcf7a447e3f16f6e5d84a9484d90.nq.gz
    ├── 3a3308ff2de4c36ed64060f146764cfa33ae0dc9.nq.gz
    ├── 3a84d3fae026692981a3120860e9c3c27271a3e4.nq.gz
    ├── 3ab68fcd6b7199d85e021a2523809fb453000068.nq.gz
    ├── 3b46a1ff5f46805ce192c90b0025ac85944e0d92.nq.gz
    ├── 3b712005de748426513e36b306f9ac5b0ca4adb7.nq.gz
    ├── 3bd675acb5e70a0861d7bbc2b90b199d33e2bfb6.nq.gz
    ├── 3d65dc3a3c5c94354507822a74134da704a00c25.nq.gz
    ├── 3e21b9b9db86a227eaaa553e692c6792842861ae.nq.gz
    ├── 3ee03933572c6e8187efa4584bd3ba8379c09b24.nq.gz
    ├── 3ef3ba74a947694ec243e0229ca1b148b96904e6.nq.gz
    ├── 3f5a79a9dcc5654422276d245e9bb637a49929a5.nq.gz
    ├── 404bc7c140ffb1785e5b71687258845b373ed9d4.nq.gz
    ├── 40c43b65f9ccfddc8d224266da55589a7cf8b0ec.nq.gz
    ├── 414145b343b5ff4ff2d6cfeafb0175bfd042a583.nq.gz
    ├── 428a256ac30702fae72443660ac8e6530f1debc8.nq.gz
    ├── 42a48ac3873f3725fd650f10fe5f785c04e1973d.nq.gz
    ├── 42ef66933252673f1de8bad08bce077f44ea7938.nq.gz
    ├── 4332e4860eff0e00e5d664fcecc0eb8120018b2c.nq.gz
    ├── 440ae257e472c50ed718bda2097f73237c03d7c5.nq.gz
    ├── 44a467bd4b73828cdafc8d5c7f074a13a14628d8.nq.gz
    ├── 454a3360b76cb93e98de1516c5944a9fdbafbaf3.nq.gz
    ├── 47027ebab092d75f9be82eb660d841bb37924b4b.nq.gz
    ├── 48bfc4843e29ad1401b6edd8c9c558ef6ccb764e.nq.gz
    ├── 48e3567e5c3cd6cbcaed2e1c79673f5e32fc8072.nq.gz
    ├── 48ff8c745581ffa8f1eaada70ce059825fb02e5b.nq.gz
    ├── 493d544109fd3da1efd8037ff9c8b26522a3aa07.nq.gz
    ├── 496413f146ddc8341c1e6ab164986289752f35d7.nq.gz
    ├── 49af60476622b8dad16bfc53319baa151d178fc8.nq.gz
    ├── 4aa17e0d79ad983a9b33af5c0c80f1372e25667f.nq.gz
    ├── 4afc2171510d2ad46a7a942480d5e76f559bc026.nq.gz
    ├── 4bf8970f184e6fdcd2c146007ccaeddbc853a075.nq.gz
    ├── 4ca21a3192168c1828fd7662622e695ff0007ff0.nq.gz
    ├── 4cf3cc6b766e2518aa2a0431ee79fe0d4c09e467.nq.gz
    ├── 4db393c0539b35b3083676176d65eee93555facd.nq.gz
    ├── 4de4292f38a8d735e95a29689f81b4da2a4e1999.nq.gz
    ├── 4f864112967bcdc173f2925f6293f76633bbacc1.nq.gz
    ├── 4fcf80aae1491edcf77c8191f138cac844ec7af3.nq.gz
    ├── 50589768fe1016ea90bbfa4b3658b6f6edf78dea.nq.gz
    ├── 50864c3c896e7fe45ac2bec29f4a9641612ebe2b.nq.gz
    ├── 50c1395b30b45cce14d9ad5a8e53ff8d38d13e6c.nq.gz
    ├── 5125a8c7ea737b3fa3c8666888ada8a3ff10de26.nq.gz
    ├── 516d589cb22d84f87f5b4e8816c6ae9b40d476fc.nq.gz
    ├── 51c1c86481aec26ea6a654517c342ceea33b9218.nq.gz
    ├── 51e2d0f5b6cea5519bfc757bc6d4b5f26b9343ab.nq.gz
    ├── 51e3debf3694d43727056b9f090401540e7a6ee4.nq.gz
    ├── 51e835502d1778effd58e76515e25e0620977f88.nq.gz
    ├── 520efce2795def956d48996252b1e3663e97082e.nq.gz
    ├── 527fa16988fd3e254ff1bed70d3fd74cf03205f5.nq.gz
    ├── 52b704bca5a866befccce9e683823c259a3c4da9.nq.gz
    ├── 5341d56484fe2ba1c0b9c488a94a79af727055db.nq.gz
    ├── 53d0488c07f92699cd4f00c33d20d72ae859871f.nq.gz
    ├── 53e4963d610930883ad565aca15f211afa461ee0.nq.gz
    ├── 53e59ddb1ac0436304ca72c5f8d5aaabb126b5b6.nq.gz
    ├── 558ae446f7867333505f99a3354f105d9d92134d.nq.gz
    ├── 56170c9667350df0b4ac2511075fd832cb608d3a.nq.gz
    ├── 576b3cad10a1df21618f3064a0647d2ec8f97948.nq.gz
    ├── 57d42e6b99c41907fa48ef3934444ff7597e64fd.nq.gz
    ├── 57ef18e922471dffb1ac4166824598906ef68946.nq.gz
    ├── 57f2a031838170493e624b9e8328a359233c17ba.nq.gz
    ├── 58a7ef0a176cdcb04cc6c0fba70fb26ab0684030.nq.gz
    ├── 58c690890386d9f13fa66fa42bd6f8f7aced1933.nq.gz
    ├── 58eab3f9fbd3fb33b6373f76bfa51272521ae356.nq.gz
    ├── 5969eb2029ebfd469ac5d3d40fdfca0dd6f2521c.nq.gz
    ├── 5b5732567f564e09285ceda78024970c88957f1a.nq.gz
    ├── 5bac1f7aa088b0fe5ddcc7478dc405ec9072ca19.nq.gz
    ├── 5bea9985c05d35b0b5eacee6b9c1d491b346da41.nq.gz
    ├── 5c467f4f5c90d9304af08948a8cf19cc161ee584.nq.gz
    ├── 5ce30a773e27cac4d853325c91587a21d9141555.nq.gz
    ├── 5d000985b1b8e5cbb38b3c2d4634805f2f29b789.nq.gz
    ├── 5ddccc92ebb1146e3075fc73a47e8a0fc3a3dda8.nq.gz
    ├── 5e388a26ff0bf7e20b20d011b5d5011fd8dc23b9.nq.gz
    ├── 5eb0e107dc6bb9abd13740761cafeceed63df968.nq.gz
    ├── 5eb19488e9bb88a7bb7ade015eb71d4a6cd57712.nq.gz
    ├── 5eef57121d01236bbaefbe22b7d3a526a8633571.nq.gz
    ├── 5f361daa72027ece4e98acb9c568cc6f83048b9d.nq.gz
    ├── 600b389155694c649ab5f50b2ef8e0fd2aa8fbd3.nq.gz
    ├── 6141f010a5e5ba80b89882f9d1ec74374f18cc17.nq.gz
    ├── 614b1dbc5bc4d71a8bee9cb0142f80ebd99cf7e9.nq.gz
    ├── 622323a4276f31d770d9b5e51368553e013c8917.nq.gz
    ├── 638383a0ae6232325f8a5801774ec5f145257013.nq.gz
    ├── 638dcfa49e958aecb6ec51c2e188d5858d7e4950.nq.gz
    ├── 63b22c12998ebe820b49db02a8385ad639aa8dd1.nq.gz
    ├── 63d4a86a2c13989700f988bfe55e388cabcbb5ae.nq.gz
    ├── 659c174b9533769cc02635a08d0ff944ed95ecfd.nq.gz
    └── 6644e53343bc88c2e927a8a6993711cddc56b7a2.nq.gz

7 directories, 200 files
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

[dpkp/kafka-python](https://github.com/dpkp/kafka-python)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
