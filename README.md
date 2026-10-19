# Repolex Knowledge Graph of pwaller/pyfiglet

RDF knowledge graph data for [pwaller/pyfiglet](https://github.com/pwaller/pyfiglet), parsed by [repolex](https://repolex.ai).

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
rlex download pwaller/pyfiglet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 255827efbc09d662875dad50fa0edc1e1263bf45
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 255827efbc09d662875dad50fa0edc1e1263bf45
│           └── chunk-001.nq.gz
└── blob
    ├── 0087df23e8bfccbf59a9bfca4b06139bcec4ff3d.nq.gz
    ├── 00da1af7c5dd4d4159883eafd4dd5d3986c2ab8e.nq.gz
    ├── 011b60d9e2e74ecedb3fdcd254ba77e91da85503.nq.gz
    ├── 020bdc6c80d161219c0e90c95c66db2023803c7a.nq.gz
    ├── 02475dc8a3dc4b13c7fbba1ef00f6d87f8ed071d.nq.gz
    ├── 02916ad4b8f93aa26fe1151793af5cecf01f6c45.nq.gz
    ├── 03e4baa7864d64d2e7514361d3cfab8ce454161b.nq.gz
    ├── 040fa034827d5e7e91afab2d23e7e8bfefba36ed.nq.gz
    ├── 042148bbc099dc4b2d80a53d9dde7b5bf355ce03.nq.gz
    ├── 044f7b79fc6a969d6f69a9f945ac5bf28e119cb6.nq.gz
    ├── 0459df20ac7b80d46f74040b66da2d69645f618a.nq.gz
    ├── 045fa74f85ef93d0cbde599a3a4be6617e0b8c36.nq.gz
    ├── 04e72fa4a1d78722cca85997959cf79ce087e055.nq.gz
    ├── 052ea98ef58a591e6722c389ea90021d27b8101b.nq.gz
    ├── 0546e45309094bd4a2386926844f1f2e406aac50.nq.gz
    ├── 056861e0871d7ac4787d6afc081ec1969ae84838.nq.gz
    ├── 05e9d2a574000810889bd87f0ff6a52319a1c0eb.nq.gz
    ├── 05ed6e5f806ea9a140e13566423a5ddaf5e67062.nq.gz
    ├── 080c56a1b8959103137a1d9a82e80c940c2eed60.nq.gz
    ├── 0841824b66558c297befdf6fa2fd3c2dccb18548.nq.gz
    ├── 08523eef4ea80af96ff58b167051a8016b8b1864.nq.gz
    ├── 087039be14d06ad377d40184c6850ad9e40a998a.nq.gz
    ├── 0986a131f70857062cacbcb2ca372b57b849c5a0.nq.gz
    ├── 09b775b5fc63de1a2d394e69f379ddb6685a72cc.nq.gz
    ├── 09f3f458aa853682c44bffe8f85b9bb342555eca.nq.gz
    ├── 0a5e6715b1c702341c59a5fa2f765c65b43571a4.nq.gz
    ├── 0a9cfd9254c0910b8dbc5132ece08f4da120a8c8.nq.gz
    ├── 0b240f84a9efb74a0900b4ee7d03f902cace192c.nq.gz
    ├── 0cf01691852da227887ffbdc5d3faf5460a509e7.nq.gz
    ├── 0e06ffdbdfb66b9b789231f0583274f4dca95d8c.nq.gz
    ├── 0e7913b832f4592cef4a836d2c71965a2253f8b6.nq.gz
    ├── 0ed5b13eb7fb42abad03456dd6ae17c04f84a301.nq.gz
    ├── 0ef06134abe2e4308502dc7acf6245920a11d0a4.nq.gz
    ├── 0f063c889542e99b597dddd472c2695f030c61c0.nq.gz
    ├── 0f8681fb5cfb4e49cfe5231c01c4c83cd85a8471.nq.gz
    ├── 100a90ea1959c003a61786c15384d7e5401e8c79.nq.gz
    ├── 103644162534322c383b9ae3c6d3268f711687d9.nq.gz
    ├── 104bb9cc03e4893b39e92a5db7fee39415702f5e.nq.gz
    ├── 10b9c79ea47c2ecedac76395f0df0cf52f892f4d.nq.gz
    ├── 10be2c0c668189dcbdb58de2bea06ffd9bb452d2.nq.gz
    ├── 1218f41a056ddfa818282a7e660d5322573e0bf3.nq.gz
    ├── 12e3a84a758b12ee6f676b8ca8f2af82a953180e.nq.gz
    ├── 130fa067cf8f3079df358dae4b27ab2e25a173eb.nq.gz
    ├── 1388988d1dce075f90f525451d4a88cc1e64536d.nq.gz
    ├── 138aaf36205eecdd9f3c14027ac808b6815c1a06.nq.gz
    ├── 142d8fe248226377e322f11c65684b0b89128529.nq.gz
    ├── 146552ca4fce0ead67a00805b347b56d7a9e2170.nq.gz
    ├── 149777d40794a2c0dee903fecb3e3a782669d5cc.nq.gz
    ├── 14e28c30dc5ac43f860d70e01263f06df0e1294c.nq.gz
    ├── 15117db99026c94d01c51b74457a0dd340b53986.nq.gz
    ├── 15531bb85b8a95bd4b103fa009c0d2556b9e3a90.nq.gz
    ├── 169203903492f4d28c7f8cd6c798481ee93480bb.nq.gz
    ├── 16b6f9941fb96569e0be57e663bdfb3cd8c3cec2.nq.gz
    ├── 17334c338c6e4889f38c482e438879a6f709ffc6.nq.gz
    ├── 1867297bb37b5f2bf564972efef7c33b9ac03f69.nq.gz
    ├── 18ec41ce6a7a3adbc92b5980b1f60d890d08e7e1.nq.gz
    ├── 18fd906f539236ff534e0eee2d3b994be5193903.nq.gz
    ├── 1931f532667c00bd89218ef95430d051f6cb3aa2.nq.gz
    ├── 1971e4135110f70b7e3d65591741181ff38fb441.nq.gz
    ├── 1a5bcada5b0a1c5fd561359141a6fc521bea59f8.nq.gz
    ├── 1a60c596dbff4ed339f164dd2de6be018d7db37b.nq.gz
    ├── 1aed0f70620df487193647b0d5ba4984b0ef64db.nq.gz
    ├── 1b40c1184d6aa912deaedef7c113ecf4d9ddf614.nq.gz
    ├── 1b687c18067ad48243980bc5450b149f1e9feea5.nq.gz
    ├── 1ba5e5ca7ea3d56df0cc297572fb937746216438.nq.gz
    ├── 1d26a5563db1fac51a624b8d9f21599ba347657f.nq.gz
    ├── 1ec077d46d8bef20f43b39606602d3a406fb2e82.nq.gz
    ├── 1f2ce67a7146a43d538c29aa8990edf51537fa56.nq.gz
    ├── 1f2ce6ebd9bdbddb407a6c538f6dad6600560392.nq.gz
    ├── 1fb55008b8fbd289b805aa5ca0d212fcc22c10bb.nq.gz
    ├── 2071f9093710919a1efe744b1f39acfe570a4da6.nq.gz
    ├── 2208cbb0870b71b930d250f4799ee9fa7b31f538.nq.gz
    ├── 227af97c583dd28caf6db5849dd5d8e9a1eb1a7a.nq.gz
    ├── 22a6150046c0a517a987be94302f1a4cc42b1897.nq.gz
    ├── 2304081efa0b37b81bdd6a63a9c186a7760dfcd3.nq.gz
    ├── 23591234e346f7e83edfa766be79eee7eacec977.nq.gz
    ├── 242af617d7a7a182b50fb2238f9a2d81698ea215.nq.gz
    ├── 25ed24a76e69a81b9f6b4a9a4498172239d4876e.nq.gz
    ├── 265f66f377b989a2f1691bcb8ff46f2a24966441.nq.gz
    ├── 26d1c6ccc1ade7172ff86029e70a4b2f704b1057.nq.gz
    ├── 278fcd8a57625d706a91b5900292be3a8c904e21.nq.gz
    ├── 27cf59e1c9f734138087ea609715bb280429da0e.nq.gz
    ├── 292c3bf275052be4eeb52466fd81f2288ad4e545.nq.gz
    ├── 29682a9155dbdff1334be480dd977ca2ed2f8a3c.nq.gz
    ├── 2988d1874e4a22c26b56d4a57dbb933e1dce488f.nq.gz
    ├── 29b682c5952cea0e9da98599f04e6aeaecf4e468.nq.gz
    ├── 29c4a49a76f55ca5f152aa78dcfc86b4e1b2d14d.nq.gz
    ├── 2a5f3829dddf6727a3d1361473cd20d9d728ca20.nq.gz
    ├── 2a63b544f7660e3350ec73ee056a77ebf8f3f3b4.nq.gz
    ├── 2aaa1e8171d05eeb98bc0b46f68edae067d54bc0.nq.gz
    ├── 2aed1b237bcba3f5bada19123305e981a4f1cbfd.nq.gz
    ├── 2af6a08e1c1b3b8ee5fb14796fa067fdd7e9e5e2.nq.gz
    ├── 2b2a2f5308cde5e899cc4cba526881551b2ed0bc.nq.gz
    ├── 2bbfbc0440279bcced55c6bbcdf127c6ef6f680d.nq.gz
    ├── 2c35b4090f50d53c05696aa9b5096605f416a52a.nq.gz
    ├── 2c598c2cc46cbf0000c7f99ff5c274071fdb5a2d.nq.gz
    ├── 2cae8dd1aac6d4357fb41ad9642f94fe8742f7c6.nq.gz
    ├── 2d8d0c810e270fbbd991bf1caafbf75c738d4c76.nq.gz
    ├── 2d9a2d11eff1f0f0acfe699d9ea3afa0f4a43094.nq.gz
    ├── 2e471311c505a1cf66eda1e91e2babe34ef08b3c.nq.gz
    ├── 2e5254a19fd3a718c9db252c53b0704d35cfb6b6.nq.gz
    ├── 2e574590bacbda3c525be131132cfcae02092649.nq.gz
    ├── 305a490464a08713ff11e731c5598b6faebe8c76.nq.gz
    ├── 315426e9a7e727177537388b3c8b458fb5fec836.nq.gz
    ├── 318215fa0807f29e15dabd345b87424ab5913ebb.nq.gz
    ├── 320d250e9e8f12a36a9531ef26aff66d9ef52eee.nq.gz
    ├── 33f1f72200a3aec34d2dc9dc061cfb27826047c1.nq.gz
    ├── 368698610d5ed24d20a420271c90c5027bf09635.nq.gz
    ├── 36eefd2c0cfd9690000fe4e994cb08c4acb88321.nq.gz
    ├── 374ad6e5cbd858f0edee15deb0f7396302ff2d3d.nq.gz
    ├── 38866b1f4f7e2a5e0397029cbd469b2992044714.nq.gz
    ├── 38970cd574ff3db6a0432d0faf90b52442d24a21.nq.gz
    ├── 38cf89bc6c68580128e1dc8f1d2be82b93540e24.nq.gz
    ├── 391d5ecc90b4a30f21e0c2df10585a971b12ca8f.nq.gz
    ├── 39b43e7ba52fd59f4ebc767054476cbdd5a9cad8.nq.gz
    ├── 39ce108654e059a45c4554d346cb8322e6dfaf54.nq.gz
    ├── 3a2487ebc968e66e36b2dcc854a22f919393cae3.nq.gz
    ├── 3a55e1a5a120779a315dfcaa2fe3f6aa7a35d4e0.nq.gz
    ├── 3b7dc60e5d6ef8410855ba226b1a85fd7c7893e2.nq.gz
    ├── 3bc3ec21a873e5b9e7f8606df0e058c0b946a384.nq.gz
    ├── 3bfc90b00cbfa09e995b8613a4c9d682559559fe.nq.gz
    ├── 3ebedb90e55c7b8ffaeddca8fce422e99def8d73.nq.gz
    ├── 3efb5f09be62237f2d1fe1b8c91a6bbfd8bf39f6.nq.gz
    ├── 3fc79715aa8d680c04a42a76cc2b97b104ca925e.nq.gz
    ├── 3fcde3eabe05d48b956e635e24437101c839e9ec.nq.gz
    ├── 3fe92ad80d27792872451cd9b2369300c4b2e3b1.nq.gz
    ├── 40860012a945f94a5b7af117c39464f2e538f0e5.nq.gz
    ├── 40f8db24bdb4b21ee96f69df5ccc41b6d13cd071.nq.gz
    ├── 41a3f2283748690f6566be03d800d9fed021d478.nq.gz
    ├── 41e5e515e00ba26c12b15d6a4e3519bfe30d67de.nq.gz
    ├── 41f95ded82fd83af2a4922731d2ef78610d8fc97.nq.gz
    ├── 421a95c21a7da1e88c1de986a1f51ec5ea2126dc.nq.gz
    ├── 42227cbea9abf255f882920772802e91efc30e5c.nq.gz
    ├── 426a612b8432054dde0250b36ec8866b76867bf9.nq.gz
    ├── 426b85e953701409ab1b32a78f94330ddb2e60bd.nq.gz
    ├── 430c3566f59b8db5a9c50d037c2f2ae2884865e8.nq.gz
    ├── 435c1ef4b0b12cefb50ef77e1c28f54e26b7b9f1.nq.gz
    ├── 43e42c5d520de877897646d8fae0e224967f3201.nq.gz
    ├── 43f65a124979c6bfdec7b4428d9dddd96b8a17d5.nq.gz
    ├── 44a26aa9e49e420040624a32561345bf5337ca3a.nq.gz
    ├── 45f42ec22a7808661366ed547e6db9af8f08b31d.nq.gz
    ├── 4605e64844e003294a178b7e604b51dadcd561f8.nq.gz
    ├── 46410dfeb2499431dbf575489e7d8156e60ba2d5.nq.gz
    ├── 47dce0881ae00eb489d3da07b875f91ccb8f7907.nq.gz
    ├── 4919978e5233741b3beb1e7dc0c50d6668739e84.nq.gz
    ├── 495c79bcc464a49483a0d27981ffc35520ed860f.nq.gz
    ├── 49db8b0246c3278dc084ba2b7a5abde6d434d9cd.nq.gz
    ├── 4ac067777e5ff4e3f0f06bbb10da4fe47419b18e.nq.gz
    ├── 4ac0c463ea6c8e7ea4841c9b1876b1f5317d6aa2.nq.gz
    ├── 4ae7b4f2fbacd9805038ea1fb83ce50d20126ac1.nq.gz
    ├── 4b8037c2af3964a392e843d56593b1f1f75f8575.nq.gz
    ├── 4ba971fd64d7a0c670660c3f55ce088da8475010.nq.gz
    ├── 4be4205c53c3ecdc3e48e5f06ad78fa9f512c720.nq.gz
    ├── 4d1a8ee59cf8b6e7087b007d7403b33cc21aaad9.nq.gz
    ├── 4d4e83e930ca05e5ee62d6faeda6f29025f69078.nq.gz
    ├── 4d592e74867827b8c5eedd477eb825477799a244.nq.gz
    ├── 4ddad37e685b09d20f4a49d48fa64ff034fc0b4e.nq.gz
    ├── 4e2b5ecc09aeaef7164d1c38c0ebe3f4b0051dda.nq.gz
    ├── 4ee5efa5764c15bb7c6b6e43f54e5c773d0c98a9.nq.gz
    ├── 4f1cc9a34d549f34383505838a14ca369d8d438a.nq.gz
    ├── 4f7ddd462e02d96333aac724b2a43275b8e1f75a.nq.gz
    ├── 4ff4f5ab0ab5d865c1c13c4a974d66a258e58b7f.nq.gz
    ├── 5163c1034203086611c19d0e60d3a53a5d06e3af.nq.gz
    ├── 5266cd7e2e3b96798e98a1b07c3ef961136697f7.nq.gz
    ├── 529b2003a80d0fd581924127f36aaeeaa93ae253.nq.gz
    ├── 545bc9a453610d8649fea8bf3b94409ca36ca77b.nq.gz
    ├── 546a61e6a21ad5b5680c4d0b3c54456909e88fbc.nq.gz
    ├── 54c515dbc516e05b7dbe8330b0776e2b2bc5e46d.nq.gz
    ├── 57c36f1e213b2308e3c51f9bf7a7d414f8364e70.nq.gz
    ├── 57cffc255e717a09e26cf3635f2fd0ff9e4e25c6.nq.gz
    ├── 57d5fda566abd66c509adaefe5afe6ca7480c911.nq.gz
    ├── 58369d395c15302a1d66d7a6cd1508738d81d612.nq.gz
    ├── 5849c4ae179a657b2137ee2da6a20f5162edd7dd.nq.gz
    ├── 598bdf4ba622093a8e8589cc8395127712d972a1.nq.gz
    ├── 5a77f056264b7d05ad6ca85c03dcf237ca9b1fbd.nq.gz
    ├── 5ab88ad4726e7246b98977731bc2e2f5ab20a691.nq.gz
    ├── 5b058c6a694bc91014de6ff1d5fa0ef2936165a5.nq.gz
    ├── 5b23584f5d06f56058377415baa201b280412ae4.nq.gz
    ├── 5b64f0d54b2c45f5e8c61143ae6c576f000b7e33.nq.gz
    ├── 5ba5077f3fe5f97561b78bb9228448e37fab03c2.nq.gz
    ├── 5be3dd10cdb08b0af9ac17c7de44728224aa4da5.nq.gz
    ├── 5c116b37436f9ffd8617302a902b597a0bbc94ab.nq.gz
    ├── 5cb133870f2c76b2d252d2323625a101bf805b62.nq.gz
    ├── 5dd527bf71fcaf2d3536de9a6ae78e8d192788cb.nq.gz
    ├── 5de3281cc293f7e46d966c5ab1c74c56f30242fb.nq.gz
    ├── 5e835a9fab7eebf240e63629892dc9f31383b571.nq.gz
    ├── 5f1f3be3389c2c6d320b1a523ed37b6415df4366.nq.gz
    ├── 5f21e77f6ac8448f56df04a199631a490bdd23d5.nq.gz
    ├── 5f423b62523d660415c7baf90dbaa4c8ae0361ea.nq.gz
    ├── 5f6c9ca0c0df872a2ba64fbe1b836ba35eca493a.nq.gz
    ├── 60603f163645a0ca4801dfa35675bc2565c85378.nq.gz
    ├── 60af27719d393dcff71a8ada465548136cd20e15.nq.gz
    ├── 60c3aef54faca9ba804bca990ea65b0187fff779.nq.gz
    ├── 610cc0b500318710372eabef45d720fde9ee5805.nq.gz
    ├── 61d2b69745619e3e6f1423a613fe1aa4d97a96b0.nq.gz
    ├── 61ee783fd9c9950d3ed292d55b372cafc85a3f34.nq.gz
    ├── 62a126a3dc9b6dae5163393c348fe05dd3c604b1.nq.gz
    └── 62f08dbb0fbddf2ed7c1a951dd6b6ae3e3c939e9.nq.gz

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

[pwaller/pyfiglet](https://github.com/pwaller/pyfiglet)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
