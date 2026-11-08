# Repolex Knowledge Graph of UKPLab/Anonymous-Recursive-Dense-Retrieval

RDF knowledge graph data for [UKPLab/Anonymous-Recursive-Dense-Retrieval](https://github.com/UKPLab/Anonymous-Recursive-Dense-Retrieval), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/Anonymous-Recursive-Dense-Retrieval
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e7f4040855e9731bea0b0c629a595b9734092c8c
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── e7f4040855e9731bea0b0c629a595b9734092c8c
│           └── chunk-001.nq.gz
└── blob
    ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
    ├── 004bc109c3c809a388c1d28a3736415a5a6a9277.nq.gz
    ├── 010a445a5fa11b6c430f11871a023198cbb442cb.nq.gz
    ├── 02befa2aa2e9c4672cf54bcb3d043bee46e792f7.nq.gz
    ├── 039293c797d4a00158583e504a4b532b201452e0.nq.gz
    ├── 03d1828825ddd3997da2c06a8dd3691fa1f80954.nq.gz
    ├── 04c7ee5d910c56f80f9b92ad7162fef77d4ba182.nq.gz
    ├── 04e89f16b3ebbc7c603ee4679390176bca922302.nq.gz
    ├── 0509c40578b847f45d92cebd65be8466ef9badb9.nq.gz
    ├── 054fe1cbbfc0609b71c58ac4dea0b95f43f8c93f.nq.gz
    ├── 0602ba3acf919a22f2766f2d8cd40abcff234806.nq.gz
    ├── 073d48afe2908751a4aa2fcd96137ff02cc1e8fd.nq.gz
    ├── 078f0aa1a59266defbecd3230b72ee1b30365590.nq.gz
    ├── 08c595ebd5eb6de48af62eab8d3295e173a0da9e.nq.gz
    ├── 094aa715165d8c7fbe6beee7965440121b7d492e.nq.gz
    ├── 09c1a9cbda4e1e7ce3022ab87322f6540c0a2d67.nq.gz
    ├── 0aa5f7c1fbdfbaec93bf09964f6289a066f218d1.nq.gz
    ├── 0b502efafeb4d8d0dcae97e0d407dced25dc3ae2.nq.gz
    ├── 0bcca1b23700da8d9f4d9f5e8378c3f9df09f574.nq.gz
    ├── 0c88e491d3fe2ad8790f011c2ec4ebc7f395a4f4.nq.gz
    ├── 0c907f8a8edef8aa1768d392a4ece54cbd6bcc1f.nq.gz
    ├── 0da01dfcd1fbf94f585215e52d0970c0c579b530.nq.gz
    ├── 0e8fafb56d41f4d2bd77f4dfe24b234c732e806d.nq.gz
    ├── 0f75a56b99ba6cd486ce0ee548437db6d5d6e28e.nq.gz
    ├── 0f7c4324839b055fa7783f03fcd1feccae8e01a2.nq.gz
    ├── 14e48ea243eb38ea9dbf131267d26797f1fd853c.nq.gz
    ├── 15082ab9d5aa5926bed9fe14000e783444e75537.nq.gz
    ├── 15b86de6d21087bd27de5dce77ee376c620ba996.nq.gz
    ├── 18360f839093f1f0a3d071c535ed1f982df542e6.nq.gz
    ├── 1a4884214b50135781495b07f34c1f48b6c05db5.nq.gz
    ├── 1a5c1d7fb1d63197b73012343f04506222160f9b.nq.gz
    ├── 1acd084fc052d4164ddc2f9794ee5f4bbadfb023.nq.gz
    ├── 1b7111ad83e289bc91cbf558ad6ea11593b5eacd.nq.gz
    ├── 1cf2959c30bb68b4745ae3378cb69f8bb156e481.nq.gz
    ├── 1e47013c5992a6ba1d314c085bd2d2dbf399b547.nq.gz
    ├── 1f195eb4596a1894bf0a0897cc03b89b6674538c.nq.gz
    ├── 1fc238805febacdc90007b06253cb28849cd7490.nq.gz
    ├── 21334339eb99a76169fae3f865047de5a248a137.nq.gz
    ├── 21f199070b4f007a797b862ac13132b7990c719c.nq.gz
    ├── 22b2203ccf1bb0cf3ebdcba7d88306e584348ec9.nq.gz
    ├── 236d1fbf105bc839d40955031bb8504c24d67ba8.nq.gz
    ├── 23882e48d30363bcc1f912432b6dec436bdae33a.nq.gz
    ├── 23cd69d4e277a138428a8e2ddb627212fc4566c6.nq.gz
    ├── 2411367e715b1536f15f862c8f53101624c7111d.nq.gz
    ├── 259895f8deee0a208863992cddd2627ed6ff4fa4.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 262222194138c0e40f2e5a900b8870f90b928318.nq.gz
    ├── 2727e18a4ca5f3ad014dbd139dfe602eb393a41a.nq.gz
    ├── 27960c864a7c0625aac2e9edcc0f2dd9864cb074.nq.gz
    ├── 284c9c782110caaecdca006fcb420e66485a59f2.nq.gz
    ├── 287d697c21c5dc17db988d6ebafa9f779fd515cc.nq.gz
    ├── 290634015a3c5d4a43386bf084694368a937a3c1.nq.gz
    ├── 2979e74d47f65278840477d734b0c4055624b3ed.nq.gz
    ├── 29a7547ce4e20e732867c09eeaa790955b21ee87.nq.gz
    ├── 29ae9ab5f137d1ad93e56863f63537191896be18.nq.gz
    ├── 29dd20f51912fa953d41ebf851e1d5c646492198.nq.gz
    ├── 2b030487587cf69233ebee94250eca1c734e276b.nq.gz
    ├── 2b4a33065edc977b6c44e8b7ede4151e5bcf753f.nq.gz
    ├── 2befc83ce34478343580690032b3a30c96e88e33.nq.gz
    ├── 2c0065c8ac9b24ab58521ff6d8de3ad937eb4acf.nq.gz
    ├── 2c1ba775123ed2f2867ddc6bc4f463e82a02f3fd.nq.gz
    ├── 2d439d042f4f8b93627a3e7e12cf0e4fffee9597.nq.gz
    ├── 2eecfe9a723f13fdfefd4e2c6db5b77f79566d2c.nq.gz
    ├── 30492727f08e22f94324f1033af00d829136017b.nq.gz
    ├── 30ac472d94763abf2a969d145d2422073586a1a9.nq.gz
    ├── 31315a9c5d8f774835c74dcb95214a1b630de920.nq.gz
    ├── 31512b954956b72db64db6e66dad0c7b3e4d9a7e.nq.gz
    ├── 316641526f516747efc2e47e78db3ada934363f8.nq.gz
    ├── 3276a7dec832e0e37eff7878c2e18b9365a16a91.nq.gz
    ├── 335db25ec3516d3d8aa190f646030a01c736f156.nq.gz
    ├── 34ce1e54728e3c8c41e69c5df5b4ab5cb5122cce.nq.gz
    ├── 352e11cb4a9dcacc367a0540300ee3d41418a936.nq.gz
    ├── 353b789023d4cdf745cb5af753ad8e8e34ee4e09.nq.gz
    ├── 382b99e0866b1f5864ff36306f9f4c6953aafaa2.nq.gz
    ├── 38ae5247f4583a565433a3e4be6b1ad2235aa752.nq.gz
    ├── 3b6c1b5680ddd614a79811fd221c0e25d2c883ec.nq.gz
    ├── 3c05239bf176bf3682cd87465832c3bd4df91e77.nq.gz
    ├── 3c4be3112faf4834a8e8631d036f047a204fd9af.nq.gz
    ├── 3ebd722b70c12758bd5208068a5585f7d1fcfde1.nq.gz
    ├── 3ef2975e94c224d50f68a66689ebc5825a49cde5.nq.gz
    ├── 40167c617875dab40a4ac3e49ad82214a083ce67.nq.gz
    ├── 4162c8801bd01579debf7001624c1aa87936f268.nq.gz
    ├── 41641e85c0a3c821739c1961e442f95fbff3a613.nq.gz
    ├── 41fb67f0ae6457fee48427e94030b34931be93c9.nq.gz
    ├── 42c53338e4f7f037ebae7806172bd9aa3a447699.nq.gz
    ├── 42f050bd996b32a254f7b331f75cef93cc469dde.nq.gz
    ├── 43bb036efd6275a1e56e4f44e60e4b9fb30506e0.nq.gz
    ├── 44ef755461ff4ade51b60c2a485237425ef35db3.nq.gz
    ├── 45397bab47c0177694e03bcc1236787ef612ebbd.nq.gz
    ├── 47125a65247140240ca69167ffd3e9fc3b4cc7e4.nq.gz
    ├── 4863cf47e18adc20151742186d395edc819f67c0.nq.gz
    ├── 488399390906fc4bb69303b78467e93bafd46385.nq.gz
    ├── 48a2c1cb2f78d53b404cf9549388bc6d12a9abaf.nq.gz
    ├── 49009166bb23a2b251dfe87471020da65492e578.nq.gz
    ├── 4940fbb9be88137a9b91665be75c45c2b25f231d.nq.gz
    ├── 4a0c2e775d661b575a25b5290cff3f538411b738.nq.gz
    ├── 4a6e59d26a8387441533b4508976a8b593b55166.nq.gz
    ├── 4adbaf3edb1f0e91ea791b11ff13ea708b6b7082.nq.gz
    ├── 4c0497ad2faa7334809c1aaa28e8ec4b7b0783c7.nq.gz
    ├── 4fc15d1f2063f9d57fa838a4b574b5bce2c5c543.nq.gz
    ├── 50d919e98cd927135500fd3f3df223fc77df6a30.nq.gz
    ├── 514244b9433da518ac2016e0578ed4f6e9dd7199.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 51d32e8d95d5fbf3c11e05926e2acae881631a8d.nq.gz
    ├── 5200bc31409c8f1b7b5e48c71cb2dbb7a7b1af0f.nq.gz
    ├── 5213ccc9b5d7c170a2a7298a189e0ec7c40abc8c.nq.gz
    ├── 5302e26c8c84ca9b3bce55473162aa1e6e8e9bc1.nq.gz
    ├── 54848451032192de37cd3bda392d6fda79a15a10.nq.gz
    ├── 54bb2ef9486fe4deffb34c7073fd33dcbe8e3a67.nq.gz
    ├── 5518d86ebb1f79e27e15288ca3f6eae30fd2049f.nq.gz
    ├── 55d66ed8017ea2ee040babfe1cbd206351ad8b28.nq.gz
    ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
    ├── 568d3d80ea6b7917bed7d6123fd45b19f65904b0.nq.gz
    ├── 56cac2368bb3eaf5e6525af5b2f5069e1e818d43.nq.gz
    ├── 57b2a65ab9ff1ab922e9e51e853e24ce2656d6ab.nq.gz
    ├── 5819b7bde1149bafbca0c753bb8823836e9d5c6a.nq.gz
    ├── 5828f62e9e5b6c5b301a927e5f5f034166b6cbbf.nq.gz
    ├── 5871b6fb8c3728196eec200c9d116fdfb645c93e.nq.gz
    ├── 5a7bd7f0947f9299c29f8a290e48afc6aa4d8113.nq.gz
    ├── 5b3ff592fd46c8736892a12864fdf3fed8775202.nq.gz
    ├── 5b50365fcb788643cf638ac05a060ec2cf108924.nq.gz
    ├── 5ba3994d463f29009680b468e94b5edd92612b51.nq.gz
    ├── 5d418d99b401d4612193cc3ce208988a411de211.nq.gz
    ├── 5d54e824ef00b1626e61ee8293019d5360682969.nq.gz
    ├── 5da4774005c50fdb708021c18b8b67f19ad787ed.nq.gz
    ├── 5df26f0e070d259632ba8c40e8779c054c371c90.nq.gz
    ├── 6137b90fd2e4b981b57e2a9d18339921b0b41802.nq.gz
    ├── 61ec0d1131529c7b2635d8abc2bd2de06ed63bd0.nq.gz
    ├── 61f42f2eb6ae4296e5a88a45b4545570be16c008.nq.gz
    ├── 620a41b8cde93a93ebf133b795a8e437549eb433.nq.gz
    ├── 62fa9c22ac61853f1ed11d2d2f5ab791d6d63a8e.nq.gz
    ├── 6528669a619f63c2f33704a47270b4d382191ace.nq.gz
    ├── 65c51434e1f8d62dffac7179585f2ec7a4b743f5.nq.gz
    ├── 661d473841650b8c3f5025c60dc9a753f9392c42.nq.gz
    ├── 6637e38bf0961227a3a2d36fff092a8787e6babd.nq.gz
    ├── 66d0d341529490dd184dc0710696b5c6c86957a4.nq.gz
    ├── 69a569c4476457512a1a1930355c673aa58e5ca5.nq.gz
    ├── 69c581ede5957d0e7babba915e2751639c58c9eb.nq.gz
    ├── 6a01493bb7060aaba9deb2f579509737bbd4b967.nq.gz
    ├── 6b51b2560c9230866cebeda25337ba61a099230f.nq.gz
    ├── 6b9e79e025f76b3c480cfa894fac5bb64ea72207.nq.gz
    ├── 6bdba6ae79cf072d5c962104b0f634e8d6b6e032.nq.gz
    ├── 6c74d362a73b2d08f158e36719e6e358218ae888.nq.gz
    ├── 6cd74046a2189178ab67ae69c4c04c0305146782.nq.gz
    ├── 6d7f89527b3c24dc61a57d920ee896a31d8188a9.nq.gz
    ├── 6d83fbeb7620498e13c4abcde6525c7ac0ac577d.nq.gz
    ├── 6f1e8d6220dcb24088af6379e4cad512172bc39d.nq.gz
    ├── 6f896919ca669ed2ce3f3ded5f699fc128032678.nq.gz
    ├── 6fc014d71cfb185465934d54963ac17a5dfdc153.nq.gz
    ├── 6fc995e70c7aebbacbc0000825395bf6d501859b.nq.gz
    ├── 701cb9ad4bb5f77c7ab8bdc5ba823ecd47aa1971.nq.gz
    ├── 707371a823b4ef542f2f4d780dd3c42904b2cf02.nq.gz
    ├── 7183b42ebfb56bdb7b1a27c03998d4d03e543b54.nq.gz
    ├── 722a563d8fd1e3706a2d8d2f5aa7834a26a82fbb.nq.gz
    ├── 72b1c940d31233dfed6e83c1571cfac7cc2149b6.nq.gz
    ├── 740b7e6a60db382492c4d93022e655f110e26ebe.nq.gz
    ├── 751a04d2f91922f3ef1510562505dcbb2a461521.nq.gz
    ├── 760933b6a65ce371af132b681235c402eeaaed02.nq.gz
    ├── 762a4891ab5b32070d36c625e949269180118c95.nq.gz
    ├── 764ef31e4e22cfc583217358aa38e002359d8498.nq.gz
    ├── 76cbe26fcae8a4e1d45c35e5e05e18b3c50ed53b.nq.gz
    ├── 77053960334e2e34dc584dea8019925c3b4ccca9.nq.gz
    ├── 77c3f339deea43dcfecab518de558e76fa884f8d.nq.gz
    ├── 7810b92f9630dc09a4eaf1a0cc08d38915ff4be1.nq.gz
    ├── 78981d127da54223e0bba9e3a17174ce442af932.nq.gz
    ├── 7918bb67672baaca9ae33a23772182e4e12690e1.nq.gz
    ├── 7ab581f7b347b642702d806e03391499013b6462.nq.gz
    ├── 7ac833b9d3406b827a79bef0b1f641aea62bf262.nq.gz
    ├── 7ba25d7cc8b121618f427d0c61bcd3d5fde7f408.nq.gz
    ├── 7bb0c99ef79f765a6dc943300ccf220a34840d54.nq.gz
    ├── 7becc8ed0e8c7f53fbbd827f8579a7dbbf1fa8e5.nq.gz
    ├── 7c002b02785565872691bb1ff5e170a43f2dba70.nq.gz
    ├── 7c6469730ffae26a5d493be09ff7f739bad33bfb.nq.gz
    ├── 7c970a5e012ce78dd05271ac13cfcd7b474fda32.nq.gz
    ├── 7caeeb6a0e451948df4e68b48c939539bb93ece4.nq.gz
    ├── 7cd3e8c81a086ef50a8835262207b8bf9002f4a0.nq.gz
    ├── 7d85b4097d1e2a7636259c1715338be8a78cf0b3.nq.gz
    ├── 7dac4943e2e65344fb61001c0278573b4d3eb33d.nq.gz
    ├── 7dc3b1e45234200cd2d8f06aa38a561ab49c37ef.nq.gz
    ├── 7e16f76103c61fc443947ded25b6208c1bfbeb97.nq.gz
    ├── 7e35e425eebff64a99ee9195d2735c1f75af6462.nq.gz
    ├── 7f672e6e0c4b31848de37579ff3287ea21dc9d23.nq.gz
    ├── 82e833ed48adbd5c53e5b22782f75817fc212ef1.nq.gz
    ├── 84896102892ad24c0871d53ecad2ee3f9c9201cd.nq.gz
    ├── 868e4105c1c064e761694d62c3bc894630b973a1.nq.gz
    ├── 873f580e33dec394e6f16a87d07dc0000e50cb17.nq.gz
    ├── 874e325a03bf970f01de03c5198b907730b1af20.nq.gz
    ├── 87d45263c1e6a02397ec6e0b323ec9a3e07b895d.nq.gz
    ├── 884bf89def8e79f0d60969a1d541b663697d0be7.nq.gz
    ├── 889d318d4c30000b6698cac315a1cd4eea7e01f8.nq.gz
    ├── 88eba6209e92b82c7f90ac69593343fcc78d2a1f.nq.gz
    ├── 8953f2bc6e640e07222dc1c46395660679116c24.nq.gz
    ├── 89b7e48f4c42a13e6f984d748b34f4138671e534.nq.gz
    ├── 8a1d3df6272a20ed445a030a88121222e5d78ba9.nq.gz
    ├── 8b1c96c5df91742ab6c7082d9c1bbac7fa5fdcae.nq.gz
    ├── 8b8ac4cfd32ebe4fb4593562025f30b5e3ade89c.nq.gz
    └── 8c236e9af6c60cf17c4c193f6dd5db7a4b31d4f4.nq.gz

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

[UKPLab/Anonymous-Recursive-Dense-Retrieval](https://github.com/UKPLab/Anonymous-Recursive-Dense-Retrieval)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
