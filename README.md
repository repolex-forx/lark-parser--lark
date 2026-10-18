# Repolex Knowledge Graph of lark-parser/lark

RDF knowledge graph data for [lark-parser/lark](https://github.com/lark-parser/lark), parsed by [repolex](https://repolex.ai).

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
rlex download lark-parser/lark
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9a4fb9c7458e8155636773a3cded0016d52516da
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9a4fb9c7458e8155636773a3cded0016d52516da
│           └── chunk-001.nq.gz
├── blob
│   ├── 023ad6e9b4ec120b08eed5ec2027be2b1fa431f9.nq.gz
│   ├── 05a5eb5e979d1f7e87c4249a4a8ab44ff10e20f0.nq.gz
│   ├── 063d2124284a8df875bc9373f2e067c909afc980.nq.gz
│   ├── 0ab849e3fd86310e83671e866e31f2afbf5e471f.nq.gz
│   ├── 0afabde6a2a64840795e6b6ee17ea2ba108d7da0.nq.gz
│   ├── 0b0a4c35b0f3160ccf79884d668861da384a64c8.nq.gz
│   ├── 0c72a6f520920a9ed1c4a1db3e559a067a68f061.nq.gz
│   ├── 0d843355c45c6fda0afc5b060330527ebc1a21c0.nq.gz
│   ├── 0ea2d4fa9e0058bf19776d009f4a983baf849ad9.nq.gz
│   ├── 108c19c16be0051b11d78a50d7dc43310d18ca41.nq.gz
│   ├── 12a9ab3dd513c0b548f78b4034b57e85a4701154.nq.gz
│   ├── 1505c1eb64daf44efcd54131fcb11e0a9cd92d04.nq.gz
│   ├── 1631188e719631d0fa648f50d79506211e51210d.nq.gz
│   ├── 1acad4d3de426316ae44f1af9afacb4725753192.nq.gz
│   ├── 1af59538a4464656ac11b74102e47fb8073a2df0.nq.gz
│   ├── 1c6e6332092d6aaa33463a95661507eb1480fe7d.nq.gz
│   ├── 1cdd5f303988610c2ec14c3a6db0c0426e161897.nq.gz
│   ├── 1fc27d565b4ba98192a5037c791c3819fe534586.nq.gz
│   ├── 201bc32dfc462ec60e07e526143a9db38c878d42.nq.gz
│   ├── 211e4849edd88e78ea7d1ec91f4e4b07e27bbeb0.nq.gz
│   ├── 214e2d545e5a191839c42f73968c3ed12ae45812.nq.gz
│   ├── 243a2308d3616a10b20ac4a3848617bf37dffe3e.nq.gz
│   ├── 24e2be3ed6e42dc71fbb9617374c28034b11ed70.nq.gz
│   ├── 265236200aceb0741dc7498d9b5cd043255254ea.nq.gz
│   ├── 28d3cb637fa5cfe2a2be3c4fc1191ee635a199b9.nq.gz
│   ├── 290b57dc27e954e0d339d29365727d7510073fc4.nq.gz
│   ├── 2947b63bb5f00c185dca5741bff99c6cf5f72bf3.nq.gz
│   ├── 296407fee6d116a0195c674c7b9fae558460dc74.nq.gz
│   ├── 2a64b03384229a61cd2a1c275efd21786de16bcb.nq.gz
│   ├── 2d4a2a8afb7e13fbc791e0bca6d20d1972605727.nq.gz
│   ├── 2f02edddd63efc1df0219a0cd1f70b598fa4281f.nq.gz
│   ├── 322362c9a4c5cab0ed772a7c764092bd53ff7287.nq.gz
│   ├── 330d032eddc632fcdb14814792971208a090c8e4.nq.gz
│   ├── 33a985ad642977119ddfc9c89dc5b890353bb7aa.nq.gz
│   ├── 33b8b54f6923450d4b374328d4a33d56b6d994b5.nq.gz
│   ├── 342b329cb32d1870358b4f734a235f07984843e8.nq.gz
│   ├── 35b5d17ec005155525837ac9902d4fd4006ddf8c.nq.gz
│   ├── 37f53ad8abd824c03350b327d733e1dc37eae3c0.nq.gz
│   ├── 3b5ac166e2b5dde5a0b3a10a9349015565917539.nq.gz
│   ├── 3c3cbcfd84aa818d3e763078cce13a21689929b6.nq.gz
│   ├── 3c474c28e84e7b267485a5ad953a768d66bf2f69.nq.gz
│   ├── 3c652cd16490604ed453c5c68021b9e80b71be6f.nq.gz
│   ├── 3d47a53e12f53ae61bb2647315e9f3c6c410f0fd.nq.gz
│   ├── 404b01bf017c0eb218984dd300776af45fa4fe38.nq.gz
│   ├── 450c6440dd56d8763768684e18e87121df5ab2a7.nq.gz
│   ├── 4613ef9ab1a5d65f8bf229eb470986ecbf7d4eef.nq.gz
│   ├── 481d923adda40130fac1bbbdb2c8425bf61945ba.nq.gz
│   ├── 489f77b2e1beb83adca41d365e5a9bea807957ee.nq.gz
│   ├── 4c803f5a2be03aeba54d98f510f2b0af34ad6031.nq.gz
│   ├── 4dfc25f5cc3ccd579fa56b6697b94a8b18063b07.nq.gz
│   ├── 4ea8f643a9f59b4d28b820149873f3cd0e262c52.nq.gz
│   ├── 4f2e2868d7e8491f540189170c20cbf499a82f4c.nq.gz
│   ├── 4f3226ccbe4b541e73effd38a8150dc70eac5a58.nq.gz
│   ├── 568ebcbce385b066cab1ce278525f4b0d05d8017.nq.gz
│   ├── 59c2ac6d6ba493df2424efe1407af1db7a3a2387.nq.gz
│   ├── 5b8df82056bda1aee6298cc62d0ac2aaa5e99ce1.nq.gz
│   ├── 612176513899b58a00e06852ea1e8e318d8695d5.nq.gz
│   ├── 61c10a068eeffcd6b5751ab1b079e1d1a5fd7f59.nq.gz
│   ├── 63cac476d1e2347d2774edcb8dd453aacaf6b404.nq.gz
│   ├── 649159f09d1e398135a87977bb98f47339bfa3a7.nq.gz
│   ├── 64d201f292dce11271b9f3934b174906d30d215e.nq.gz
│   ├── 652c52e33248aba16b840a67972d2f1d49c86e68.nq.gz
│   ├── 6536f3004aa375d293b5af76cb53aa7a42d281ee.nq.gz
│   ├── 69745462bb30dbf6cdc2bc68e42911799379ecce.nq.gz
│   ├── 6a40e2bb8eeebadedfaaa87b8a3cac2692e621aa.nq.gz
│   ├── 6a67bce77b7b55b87276cdb0fa1062f97806ad04.nq.gz
│   ├── 6d4b6056c471e90213d39d1daf60339c81491740.nq.gz
│   ├── 71b6a4c1e17cfd38f4ec9c96888b825455d07a62.nq.gz
│   ├── 722a71fd65b9ae67f6c861bde6b72b96fbbec292.nq.gz
│   ├── 728753c44db4176cfb544194b6b20f93cef7d707.nq.gz
│   ├── 7582b57767e7f5fdea8d605a456a5f58bfec5016.nq.gz
│   ├── 75c131de720e337c415f246c2d996c334529cc9b.nq.gz
│   ├── 78b91ca0717bffb83f1c50eddb580e1ffbadfa45.nq.gz
│   ├── 794f46bf38f380c056ce077b1817acf17d4529e3.nq.gz
│   ├── 79a8a679979fcc077a9e95f70ab292344b3c3438.nq.gz
│   ├── 7ba5acf8e695426bd1d270a05dcada89c6026207.nq.gz
│   ├── 7e66f8fe999ca57c431c807b312fba47a1e06b20.nq.gz
│   ├── 7e94cf99673a581a5d65514e424b595a8c975d9c.nq.gz
│   ├── 8010537d042fb8ab99bbd24f8b277f5e4cd8fa51.nq.gz
│   ├── 81a9cde4e9ff2fbb24691c0241e3e326ae243b39.nq.gz
│   ├── 82726e29e3fedf4b772e6a3eff4bbd075ef57b85.nq.gz
│   ├── 839aac1f9e9db028dd3126a3206752a79cfb7fdc.nq.gz
│   ├── 8412b440fd4fb080708108ea852af2beac72a061.nq.gz
│   ├── 88ebf1b939ad8d99bedc592e3a75d152ca86208e.nq.gz
│   ├── 8ac7ecbec6ab6204b5002d4d2c0e492c1957e4f0.nq.gz
│   ├── 8b41ad23d144047921597432ec0e7a43c90f8463.nq.gz
│   ├── 8b83f081c4fd0101b4fc4601d882bb5563f13f80.nq.gz
│   ├── 8c0f349bf06cec0a08cbfbfad80cacb29f1e0700.nq.gz
│   ├── 8c4dc39e36541b1fe5f5b80f75d726fddd3f0583.nq.gz
│   ├── 8e5b104620945309a3b6e44e81df3302be9fb3d5.nq.gz
│   ├── 90e54f13d003920718b440dc3e18b9a93c31afcd.nq.gz
│   ├── 92c08c6fd2ee828195ed7e3c394dd68452e93f5c.nq.gz
│   ├── 94d7f809fa422fcf466fb46a5d0254562e91aca8.nq.gz
│   ├── 95bb6bb16e1daa9eb61c25d1e6f81a3036544d49.nq.gz
│   ├── 95ce520fdfac96c2002293ce4a2305344105a453.nq.gz
│   ├── 95fb479856f99773071993e75f2af4c6bfa464f1.nq.gz
│   ├── 96054863d999d74f127b6728c51946354e682a5e.nq.gz
│   ├── 9731d0a69e731b17a8cd7b85ed8906283e386740.nq.gz
│   ├── 98a5eabad03d83dc49aec18a1aefe09bff932084.nq.gz
│   ├── 98dfdb4408cf176235b59fab6ecb2ab33a2b7198.nq.gz
│   ├── 9940ccbf50543fb6ece2bc53c8a8365378df66a7.nq.gz
│   ├── 9b511fa6cd27a4df1a8620052783e398a5a25139.nq.gz
│   ├── 9beaff7fd0dedc167096878e8b11b274717a9576.nq.gz
│   ├── 9c974a4cb9e8ac1c328b64f27c744373d516090b.nq.gz
│   ├── 9da62a3333a8c1d0ad7dc93692871cb36b225781.nq.gz
│   ├── 9e9aa78fd7511ecc1e45c5c158feb76a00a65159.nq.gz
│   ├── 9ed8c805316dd895d425768271da2668d389b6e3.nq.gz
│   ├── a015bb49275ee028719aa01e8c7db05b357574f9.nq.gz
│   ├── a1272b8e92368648b0e1b319a7d2d51fef25d6c6.nq.gz
│   ├── a174c2e3b330850c0517fdcebfc259f127576422.nq.gz
│   ├── a46d8f3888586e86f8193d61772211cd1cce7ede.nq.gz
│   ├── a5460f35d4e9b4badaafaced9310a7489a10d0a2.nq.gz
│   ├── a65077cd48cc1245c2fababeaf82127ad37d58b2.nq.gz
│   ├── a7ae6b24914dabbf33b30420577afa79408831ff.nq.gz
│   ├── a8f765fc1af578f3376da8db8e1653c22546a59a.nq.gz
│   ├── aad9eceadd72effa112b291a65f1648317f23dbb.nq.gz
│   ├── aaf210b1d01da693fda15995ec973ed21cd968c3.nq.gz
│   ├── ab9a46d7a8d2d706f6a04dd43c6db1e29374d7b8.nq.gz
│   ├── ac4f623e79a8077a350e90b7f5e51a0da1547baf.nq.gz
│   ├── aca0b1b07e98e58dc7f774b48bee48e616d9b59d.nq.gz
│   ├── ae23c197c3d799a2d68a8dcd43ffe4f2b87cae30.nq.gz
│   ├── aec0be8e555c179c4b73f6b01fbfc89d2a40eb25.nq.gz
│   ├── afe003a7f5bbddf4f184daae906a62ad6f9f81fe.nq.gz
│   ├── b04c2a917f31d5bb220883545de0f530476d3a94.nq.gz
│   ├── b07ead72559e4a099341c821ec8a7dd4a8a13d55.nq.gz
│   ├── b080328a5e6362a3b0bf38578b300437d63f61b2.nq.gz
│   ├── b09a2f4a840bb1d11753d7a78d528c79ff83e2f1.nq.gz
│   ├── b12752b0760e67d56c6cba65a801aeecfc2ea4dd.nq.gz
│   ├── b136bd2f5b83de9b7325cd3c952f881610d82be7.nq.gz
│   ├── b45bfe4ac01f33055aef76b5a6bfee055f68eb43.nq.gz
│   ├── b5334f90771d23d75f7b49e5a6def7bca0000caf.nq.gz
│   ├── b98f166c12829bebf7436b60e21bc29728d568d1.nq.gz
│   ├── bb4327eb8f89a156b903f7a04b3d749da2a2c04a.nq.gz
│   ├── bb77c353f10168855cde89c9e328fa6b623aadef.nq.gz
│   ├── bba01820ae5a3947319d2b2c6104e28c2cd3f4b0.nq.gz
│   ├── bc21c7f60f46fead36b6663e6311f1e2cf3ba693.nq.gz
│   ├── be2ccdee8dac2a07d3140d4e16687decd52f970c.nq.gz
│   ├── bf445d520fb7e7e5c681dd94c818cdd4593e9fee.nq.gz
│   ├── c02b119623bf1d6e4bde8177377615b571e3b909.nq.gz
│   ├── c0a05b770b8713c6692a2b3f0d03a1a8c377a394.nq.gz
│   ├── c1863b55c36dab6e7958dfea2ad635965bcb3381.nq.gz
│   ├── c411771544f130d4cce499d74a036cbcaf8052eb.nq.gz
│   ├── c60f3a6b51eb97cc725f9d2f9e815351af8e66dc.nq.gz
│   ├── c614a31d65f2c0d373d43c9ee79190b0b2c3b62a.nq.gz
│   ├── c665a19748fb3e380289e9f8edac9d25c6089e0e.nq.gz
│   ├── c9260a8252f8fb19de6498743db7de1ecd568eaf.nq.gz
│   ├── c930830d620549d9a6c35a6a13c96a0182954759.nq.gz
│   ├── cb9063714d9ba52e417c84041fa2c7ef62cd1136.nq.gz
│   ├── cc2b675becfcaf44ef1989f85adc5e462e3cf257.nq.gz
│   ├── cedf2ab2e9939fbe96315ff473300385cde4f242.nq.gz
│   ├── cf3d8e3d16090a57aba10da2eaec4ddb268fe7d1.nq.gz
│   ├── d068fe01586d8d775a5108e83f9db0e0ff8ae8da.nq.gz
│   ├── d26ccbb3d2e9c45d056f01d3c75d8ff527dd7c23.nq.gz
│   ├── d2baa39ab392549a4044eed1169067785fefddc3.nq.gz
│   ├── d2e86d17c696e492281b822080811ea76ca790c3.nq.gz
│   ├── d32032b8c67813bf85be4039474257542d36839f.nq.gz
│   ├── d80f67270a515ae2fd7873cfd7669687b3fcb995.nq.gz
│   ├── d87b68f28d544cc6ea21e23c0e9104c591ac67b7.nq.gz
│   ├── d8af18139c204d9d4905797baeea23b029814d2b.nq.gz
│   ├── d8da6b0d0886971f6f7c4904cca31ad7c16ae9ca.nq.gz
│   ├── d9f9c678e83d321f31edc98711a483528f9328fc.nq.gz
│   ├── dcac54d1ad693a1714f099327245d7fed42a63b5.nq.gz
│   ├── e017471268e08003ea8e745b331b6d54cec3b1e0.nq.gz
│   ├── e23c5e321dbf148f96149073a5aeabb81cfa073a.nq.gz
│   ├── e3a33a5bb95b8544ee8c2573eb3df546e4610454.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e71f5e3ee93cab41d80ffd002f5fc36d447b661e.nq.gz
│   ├── e7f049552a2c423e73c2f2990b8e11f57b02ebb2.nq.gz
│   ├── e807354a1de3965165a492b822dbf5363881dfc7.nq.gz
│   ├── e9600735534bab4abc4df33de156ccc6b474a2eb.nq.gz
│   ├── eb28824b7a7df56150e89b02b233d886e1514eba.nq.gz
│   ├── ec1626189cdcaa321bab1653cab83600c86fa1bf.nq.gz
│   ├── eeb40e10bb723fa1f49da2a7d69c6f15032796c5.nq.gz
│   ├── ef66ae37c8cb0c46cd0b0d93d111a27e817ad14f.nq.gz
│   ├── f2e1330362f324cec9d58c5467a668896fe68c6c.nq.gz
│   ├── f77978924ea96dc9d200e86b5648a5289a0c316f.nq.gz
│   ├── f97a1d117d7388145cae10266c51d866816bab67.nq.gz
│   ├── fc7302778946f02e55438722b30b1f24f3a31062.nq.gz
│   ├── fd2662d08c064de49ad2adfc5872b22c64ebda15.nq.gz
│   ├── fd49e4dd5cfc8d33b2a3dfd7a0428fdc72989c23.nq.gz
│   └── ff51a7317d7128b18be8e94acac6ee3d1b5bc49d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9a4fb9c7458e8155636773a3cded0016d52516da.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 189 files
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

[lark-parser/lark](https://github.com/lark-parser/lark)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
