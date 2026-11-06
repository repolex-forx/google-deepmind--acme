# Repolex Knowledge Graph of google-deepmind/acme

RDF knowledge graph data for [google-deepmind/acme](https://github.com/google-deepmind/acme), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/acme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2e09e3ddecf4a1ba783688c92aa493c596a2beec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2e09e3ddecf4a1ba783688c92aa493c596a2beec
│           └── chunk-001.nq.gz
└── blob
    ├── 01a1894bb9dfcdf7ec59c51e0551a806148c5c26.nq.gz
    ├── 01f2524606cee2dbd061a873fbc53e7ffe029ad7.nq.gz
    ├── 0312c007299cf53e4fdec9e83da07e24d07b43b8.nq.gz
    ├── 033667824f814313f41e738a9f186cbf4570e818.nq.gz
    ├── 035eb76cfc6306676035a83de9b46ed8a20c8965.nq.gz
    ├── 03cf9cd22275024e36e45815349a0e6604923113.nq.gz
    ├── 04e59d2f37c7a226308a329f0d07d1d88623655e.nq.gz
    ├── 052b9b6ca72543871853f462e8cb63e7ebb4711b.nq.gz
    ├── 05d1a8e2b3b82283fd8e3f5d4eb243f4f561efcb.nq.gz
    ├── 05f7c291a6540fd76f2f67cbe28cf2aea18a132d.nq.gz
    ├── 06aeb005a360a2cc9e4e5965857190f2b3717459.nq.gz
    ├── 070231ab8c412edc16657937e04c969685903b31.nq.gz
    ├── 071ce0148f97c062d6b27e4c95b9419f003e324d.nq.gz
    ├── 0772c0b35447c82d195b784bf751751e073a7dd6.nq.gz
    ├── 093853d086f05ced3c6046e28b1a1749dfc59651.nq.gz
    ├── 09a307a6fa0b807fe601b9bd7f66ed37ec0c9b65.nq.gz
    ├── 09e3f09510da9e3853787a66a27e9a2fc92e5353.nq.gz
    ├── 0a38a4220c9247a00d3a429dbd5350fd7bf06412.nq.gz
    ├── 0aefe11cac125576c460e7fd5b97bcb069d9b230.nq.gz
    ├── 0ba95dc977026a52dfea2163bb9e367a94f22d64.nq.gz
    ├── 0bbb77727ad4702afcb3aaf9441275d4d43cee36.nq.gz
    ├── 0bfe11b6181a5a3b4918ac3259743c3e1f611597.nq.gz
    ├── 0c668d704da3ba2c1c68df1edeac22f35a5d57fa.nq.gz
    ├── 0c889947642135ed7f09793a73ad2f9a25d22820.nq.gz
    ├── 0cd46ab7cd5dda78669d6e99bfefdd2ce22988fa.nq.gz
    ├── 0da4b43dea655c886e9dc2fc31453d77aff8119d.nq.gz
    ├── 0e22dd61e2cb88d69d7dc35db61282529c850ce8.nq.gz
    ├── 0f50a9f2bccece70addb7bd0632ac865562de65e.nq.gz
    ├── 0f61e1d8aa6148c5531c0c92bfb8ebf46a7fee44.nq.gz
    ├── 101ebc0893c68da87cca593dfb15621773e38668.nq.gz
    ├── 1065de52f13307c8ce25cc207bd38453d1a83dc1.nq.gz
    ├── 10b89b9f942c85df893478ead3063ec9ec6c5cf1.nq.gz
    ├── 10ebfbb2bf591df5254a7004384170313b04ed54.nq.gz
    ├── 1182edb8ae6886bd9b09f38b7bf3fb6eb1397b5c.nq.gz
    ├── 15d16f859218791a31aa127208d0a1c2af837b60.nq.gz
    ├── 15ec82a9fe15e0dd9f69158dd8336c5d72bedbee.nq.gz
    ├── 15fa1ff8167971bb68b5e00effd775dc08a3b8a8.nq.gz
    ├── 161dd9c5a849e3d95624e8c982ee9cef6c18b71a.nq.gz
    ├── 16c59bed5fbcd4f19c5b73b1bacc5c389d0e958c.nq.gz
    ├── 1736b632aa486d6c5b19a2f6f254b0a2f7ec2163.nq.gz
    ├── 1782fe09d3b46de4db73a247d1a040fb5187aa8b.nq.gz
    ├── 17fe33ecdabac3a9f6fc2ba75ec0c9b6255f0423.nq.gz
    ├── 18908141270bc13181efcd3d4a659e5d4bb64ba4.nq.gz
    ├── 18efc26f06f9a90e82668334957ed09e1e0b65b1.nq.gz
    ├── 1900677867670eb16bc48a2037c54997640b053b.nq.gz
    ├── 1927ca5865baeac1a8032b34159aae0079d180f4.nq.gz
    ├── 197acab7d09bbba36ce3750da2465045c70be52d.nq.gz
    ├── 1aba38f67a2211cf5b09466d7b411206cb7223bf.nq.gz
    ├── 1b930a9710765c6ec3ca2bc78a4f0fcaa3dd4c7b.nq.gz
    ├── 1bf1bda1f281c14e08a7f486b2421118af93b774.nq.gz
    ├── 1ce629a3bb8b93f424bdfedde5b5bad8955dfa90.nq.gz
    ├── 1d568436fa0cf3987b21faef4c06eadcdccea4d7.nq.gz
    ├── 1d9b18b78ddc8b8e019a8fbfff9d1aeefe3ca680.nq.gz
    ├── 1db41c0d53cfab16aacd7d22c689c04b063cd702.nq.gz
    ├── 1e3f9387a53624b883a00693a5f8646909d21cff.nq.gz
    ├── 1e8f926eadc9163f038937d8bc06f6e52e911940.nq.gz
    ├── 1f0c3a1b46184447bc9f60b797ac355f2458f59b.nq.gz
    ├── 1f934be4e26d0e52a2b322b05d7d0f6d3d04ee6a.nq.gz
    ├── 1fe8d5e7b5e23ae6613e9c46a5e4726decec0539.nq.gz
    ├── 20aa155c1707442d86dcb5160dd6b9ddd2d86e82.nq.gz
    ├── 211eed8ed806395b4b7bb1802069445cea475618.nq.gz
    ├── 2223790d147276676d875dc973e71af99ab7478c.nq.gz
    ├── 238ed87849dd1c104a1297dcc3475d4051e67d62.nq.gz
    ├── 23ad8052760a904a77ad59472f1a3e72474c3017.nq.gz
    ├── 23cc9723267bbc92040e7364e2eb1a3503777898.nq.gz
    ├── 240cb71526ca09d1f065c2a20fbdff5307a0f92c.nq.gz
    ├── 2433de145fd78cb429f1b2660566685650eb83c4.nq.gz
    ├── 24d112e9e47d002def397f562e34fd97e17a637b.nq.gz
    ├── 24e4465035f823af7de9b62f4e61a430ec3dbedb.nq.gz
    ├── 255338f4b0574ccc4c32d3e4f9c4292ad93b3667.nq.gz
    ├── 25cb4825fc6c08d900b53aef08ec0ff939453469.nq.gz
    ├── 26b21d85f18aceefd86a8afa869270f1ac4e4e47.nq.gz
    ├── 279c7ea227dc06fc6147e36119ca2f8af846c628.nq.gz
    ├── 2882fa51db5c5045497fa80e4f7359eca7f20266.nq.gz
    ├── 290f480655fb2d12c7e5ba737eb7926f39018e14.nq.gz
    ├── 298b12cfeab748718321163db42f18b13cd5fe7f.nq.gz
    ├── 2b5f64485709c051fb31510d698a9dc5785074d1.nq.gz
    ├── 2c626c431b8296a5e75d2393ce09f53461517c55.nq.gz
    ├── 2c71c5248541eca66e9637c88da62c9b02eb9dbf.nq.gz
    ├── 2c97c8fe65a8850d7b15fb5d6f7772f599d2cfcc.nq.gz
    ├── 2d6caf302f9b6eb347a19f590515479fb5abb12a.nq.gz
    ├── 2e8a7ab8f2b24f3b0dd8294dfa9c5a7c21c7c3ff.nq.gz
    ├── 2eb7d49efb59f1ae3005146098582f13e19b2224.nq.gz
    ├── 2ec19f56c8effc52e82697b5a3d9b5d0b2ffae47.nq.gz
    ├── 2f925206258798c0f10d0062c827a8b80039ad8c.nq.gz
    ├── 2fc52d908ca9019af215acca06660d829275f745.nq.gz
    ├── 300b80208c4d330686798321eb0042cb622c8225.nq.gz
    ├── 31c97d37a53d394ec0969b0723e01f9924911a5c.nq.gz
    ├── 31ef681684e479048a32ef2394c389ec052933a9.nq.gz
    ├── 32815373d53bbfad55122564ad35f56c6c4c1446.nq.gz
    ├── 32a4e752376da8695c9e1de92f8c3d87dab1ad8a.nq.gz
    ├── 3360168e833fb3b3b7d1f1d0501b7c4270f4373d.nq.gz
    ├── 338a1abc4509e3322596665269a70541d4622430.nq.gz
    ├── 34d1fb766832e37df77930e5636dec2858915982.nq.gz
    ├── 34d76bfc2a98892b47a60d19e218be4867bb2255.nq.gz
    ├── 351d9d0c14dfa6de3f3bc18a02e85e60789e894e.nq.gz
    ├── 35bbb53c32c3d3ccd6851fab3c1c0f80fd999704.nq.gz
    ├── 366a35cfad7764189de24c509dd0dfa905bc8cc2.nq.gz
    ├── 36f003c724a0bc172c0a782dedbba0869f13bb31.nq.gz
    ├── 3793a6091c3374cfc3aa444d66d4f9aadc4dc3ad.nq.gz
    ├── 37f9c55adfa3e01b6a65451c329351c987d8578c.nq.gz
    ├── 39e7639cff05c73c1d1307cb51880c02428b3625.nq.gz
    ├── 3a368c07f0d0fce4397dccaf922b354d3d57af86.nq.gz
    ├── 3a78bdd00525e94aaf84f6fb989d6cc29a9ad277.nq.gz
    ├── 3a98ebb46ba64bf45fec2b5fad68973d6879896c.nq.gz
    ├── 3b405fcb0da48f0adfab2eb4c496ec49a9a45598.nq.gz
    ├── 3b4c940097232c618ed0823d3f22f55a2229d206.nq.gz
    ├── 3bf8d07014c802d05d0f275fbbc2e59b374adde5.nq.gz
    ├── 3c39ff48bdcbd1f147024db482096ad7609c97c9.nq.gz
    ├── 3dc469310c53cb5f8785259750138fa24a38c3b5.nq.gz
    ├── 3e883d2c5f256b356f3f94874bfa5ca301ec5ba9.nq.gz
    ├── 406e78c5faea77fb778787c685d5a2bd4b6c7a1d.nq.gz
    ├── 4082f4697bb926a654d2faafdb0ffc68a9a5b4e7.nq.gz
    ├── 4185e6345daa376fbf29d8135a62790e602ae333.nq.gz
    ├── 42dde9fcec6131f62254f54e5251dd5431e13eaa.nq.gz
    ├── 43bee470a3b9f644f99a62501bdb7cb0169bf45a.nq.gz
    ├── 448dc2debfc4d632d94011c606f81e76b0a755ba.nq.gz
    ├── 44b2b26b5074c1b73407b0bfedba71c50f8a49eb.nq.gz
    ├── 44c29966fdf23d38a208f7435d396630b851e0d1.nq.gz
    ├── 44c2cbe356bd901a9a7c5c7222cfcba70735541b.nq.gz
    ├── 45fc94e00737af788607ed5c046d3e0904e977bb.nq.gz
    ├── 4627bedf9e077f5b451f965d031044d8a3efacd6.nq.gz
    ├── 462d96b2a11f925002aabe9266fc417be3854c98.nq.gz
    ├── 479a0f859352e3904d405397729b7e96780f19f0.nq.gz
    ├── 47ddcfc7c399b4c9f42af0d892bbaa85a466733a.nq.gz
    ├── 48c3d75c3511546de6b7a7395a4082adab328c00.nq.gz
    ├── 49a2bde19b201010ddb7113877e080c8ff07e11a.nq.gz
    ├── 49a731d8f1802cedb911221078138f8eab66e03f.nq.gz
    ├── 49da48826131181f6ba915200a3cfb026ae14868.nq.gz
    ├── 4a2608f0806ed0157b74005f4f99da8b0d13c33f.nq.gz
    ├── 4bfbd5139ed7635d997cdc31b74999125afe5204.nq.gz
    ├── 4c9650f3e7ee54c3df21097e1c8d55631d5f82b1.nq.gz
    ├── 4d32548b06f70c6996f061e8c4226b37031d0af2.nq.gz
    ├── 4e6ea7915d9ba5c170ce735ae1c3aefc3bf546a1.nq.gz
    ├── 4e8cf4bd0e1330c896eeec359477ae603a8297e2.nq.gz
    ├── 4f84f493a9c861060c8425a07d2538a45b616215.nq.gz
    ├── 4fe42aec72a5d3196322c85eebc9845cc318a777.nq.gz
    ├── 500a4c3fbca8fb001e139d882b5a8abc91960339.nq.gz
    ├── 509d3fb18e5df83247c9427aecdf3c4cfe70baa4.nq.gz
    ├── 50afdde5d41e2efc484f3a35c4d7c3abefa560ff.nq.gz
    ├── 514ec2ebd1fb84bde63d01f6d36334001f0615b8.nq.gz
    ├── 519c6a5bac35cd5da04b1672e474b450ecad1ccf.nq.gz
    ├── 522fcba68a3a9f2177147cc926a52cd66443fefb.nq.gz
    ├── 52638424af07ec8a78f62b9cbecc12f3ce80e815.nq.gz
    ├── 52e66cbecbfcf343768e991798ea8765443d38ba.nq.gz
    ├── 531bfe35dc034547cf4bc993c61f18e8d4f2072b.nq.gz
    ├── 53d33b4e1c222173f41b8cb37dc9e08ecf6374d7.nq.gz
    ├── 5438e92326cf98be0fd7007150e47d07548339a4.nq.gz
    ├── 54c0560c92353c335c4601a973e229b010e18cae.nq.gz
    ├── 55165c85533ee47f7d4f0de5b857ebdd370948f4.nq.gz
    ├── 55755d3ac366a3d6ce549fca7737b65b9a470ca6.nq.gz
    ├── 55be53c6d14a80e5d28b9d8ef159185001308391.nq.gz
    ├── 55c0a5379a85f8734dd22fc23662cb03c621498a.nq.gz
    ├── 569d736f1ca76ceb9ac6fbedfb2ba22f514ecc4b.nq.gz
    ├── 56a69275910daea14069252a8435797f627a95df.nq.gz
    ├── 576c9b0c9bb9ba9d2638140036867ac1be0d971a.nq.gz
    ├── 578e7a4d9b2a169adbbd25e601279fb5eb8a4d59.nq.gz
    ├── 58b035462c514b2f53f4440e8ed5a65eb6022a18.nq.gz
    ├── 58b3efb5ee44ff7384c8081138e5c7b321d47228.nq.gz
    ├── 58f0629cdd0731c76a06e3694a843ff288dcfee6.nq.gz
    ├── 591a27861b91898d8d63109c71e2dadbd1a7d46e.nq.gz
    ├── 592cf9c80736bc88b8dcfad625632aaff970261d.nq.gz
    ├── 59bdcaf59f8cc203f7049b14580bf09c8ce30ddd.nq.gz
    ├── 5a1991f820d7960ac4cefa6d26d4135ee90462bb.nq.gz
    ├── 5a9f03fb775fa87f498fce7d501f9159ce4b8fe3.nq.gz
    ├── 5e1b546a494d2e283989c0301696404a1d2f7882.nq.gz
    ├── 5e24d3df217644819d4d31921f3da0bc1d427643.nq.gz
    ├── 5fe695a5a50cae482cccfaa811f7a5f58038573a.nq.gz
    ├── 6002601b13ea3314b3ae96ad0cb4b6e9ef6a681b.nq.gz
    ├── 60d1afc1566de39fa1ec77a81138fdcd97e81d0b.nq.gz
    ├── 6201ea0d9ea7981dcf24034e1e104989d0034d9b.nq.gz
    ├── 62a58cfd862f85a8cba532162f9927d782247c4b.nq.gz
    ├── 6362321ac163d4db332fb03c31399fe9385c880e.nq.gz
    ├── 63a05d5eaa2a1c2e5657fac21962ce9f0bba84eb.nq.gz
    ├── 63b1ddf223195e8e15b9fc71b8b87dda6335e8ca.nq.gz
    ├── 64bc8e632e9881b9d5a380c0fc6623b48fd3885d.nq.gz
    ├── 64ff1fdf84c58a097a7146efd651950976ecf83c.nq.gz
    ├── 6539a5b2683352b45277ce5baa85ff3f00e03cf5.nq.gz
    ├── 65af786f9aab53be3c1a323f29fdfd1e291a859e.nq.gz
    ├── 65ddad67081fb10c76f2d9100a798878a67a7b94.nq.gz
    ├── 65fb45c4fcd9f335cb9e081a834666730da3b096.nq.gz
    ├── 6633295dfea14e033f707cae5a688d23fda7b2e5.nq.gz
    ├── 663625cde8c92a80fea4ccd9aa41826eccdecbc8.nq.gz
    ├── 672421969e0d1516248aea2bffe9e9bab55e5e73.nq.gz
    ├── 6763a71d4e42300bfc38cab43a65a2381eb87fa2.nq.gz
    ├── 677ddb4590d9d39d1969794529f8166611c9a08a.nq.gz
    ├── 67e3e4cb9f86fadc4a6ebd616c05f2aea1b58600.nq.gz
    ├── 69018db014b6683744c8614e5ab9b5d7ddea37ba.nq.gz
    ├── 6967791285bb302687f742262ff0184d4f6b9145.nq.gz
    ├── 6a4822333537611f11f5a552cade2e0404538ca6.nq.gz
    ├── 6b07e702df526c6f34d547366256c8aea64512c5.nq.gz
    ├── 6b405ce49c23f7af6d019b998fdce6f861946861.nq.gz
    ├── 6be00251957beb08e0e85868297bb26a07e6e963.nq.gz
    ├── 6cc8a37b4066e80e051a590a4387d95914819e4e.nq.gz
    ├── 6daebf1b2f7c5cbec7343bf4d20add2de03fbcd4.nq.gz
    ├── 6dcfae02df12598f815904dbf2ddad838597006b.nq.gz
    ├── 6e8060f3dc2cc729803b811c428e2c0d512c0289.nq.gz
    └── 6ec266259d2798e896437a13e2280a7591ab4f1e.nq.gz

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

[google-deepmind/acme](https://github.com/google-deepmind/acme)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
