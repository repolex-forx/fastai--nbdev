# Repolex Knowledge Graph of fastai/nbdev

RDF knowledge graph data for [fastai/nbdev](https://github.com/fastai/nbdev), parsed by [repolex](https://repolex.ai).

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
rlex download fastai/nbdev
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a336173c2698d8a21c5ee908656a88800325f125
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a336173c2698d8a21c5ee908656a88800325f125
│           └── chunk-001.nq.gz
├── blob
│   ├── 03b29cb0a28df52dfc1b73c57dcb0c0ffd60cd53.nq.gz
│   ├── 048655c7e4a780aab319e66eef3fab41fce0ce06.nq.gz
│   ├── 04db2268b086521e47c92cc78bf062bfcbe52cd2.nq.gz
│   ├── 05215e71074d86d9029d7a748da53f05a98d93d4.nq.gz
│   ├── 0639b2225365bc9c7fa6b292bad5947881c7af48.nq.gz
│   ├── 07856f9b34c987074262383530432a91cffdca6b.nq.gz
│   ├── 089cc79e7c43023b6d5d541e8d3f96e85bcddbbd.nq.gz
│   ├── 08ff9c836f3bfff6b1d80eb38faff40c550e51db.nq.gz
│   ├── 09f902342d60dc7807435eec909b3cafcdbcb7fe.nq.gz
│   ├── 0aaf8dff5254b8ad24b776edcbe399d5c1824934.nq.gz
│   ├── 0b660bbac08d4866ab81c58d99dbecfeee4a13cb.nq.gz
│   ├── 0cbd7a199415eb5b30e4485b6f38343b5b66f602.nq.gz
│   ├── 1225e4da0be1595ea7c4a285e1fcb45342dd5337.nq.gz
│   ├── 1288c409bbdf92dd8297f3bbc8a2bac159a44719.nq.gz
│   ├── 1456e861a0d8501f885e7da206a8e90745b3ce76.nq.gz
│   ├── 1603b816f8fcb12f214d9379fab97a9b1104ed0e.nq.gz
│   ├── 166b9eb545bfc0932e08456cde9697a4a6e2056b.nq.gz
│   ├── 17087554111f348408e7e55021df220acd2e76e4.nq.gz
│   ├── 17940c4acb5ea97791dc13ec96b0f825a4ef8597.nq.gz
│   ├── 19fdb7802a494bfe40307ee49acaf21a51255c3e.nq.gz
│   ├── 1bb86040bf9f5ccb26afaeb79f4d5ec33f1d610b.nq.gz
│   ├── 1e62520e880b86aa6f07d9859d6d1bc99fd5245a.nq.gz
│   ├── 1e7049b303b644b018a3f08d2e1af35b8f939fe6.nq.gz
│   ├── 20c7a05f9eaa9361ef877ad49bb3bedea9de434b.nq.gz
│   ├── 222e8564fbf87516080adf01b416047a53f6da8c.nq.gz
│   ├── 2241fdd843b2936121e11966f40bb2ae715c85d5.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 28826a51e57bed31590d38f0954a08bdfd42210f.nq.gz
│   ├── 2a3185fcdbbf8a0cb60a782b28f89e223ae5a984.nq.gz
│   ├── 2aeef9c6444f662d5341ae7045e1e3ce035ae3a2.nq.gz
│   ├── 2e42bc7d4d4e71a666f676f31f04bdb39a2193ea.nq.gz
│   ├── 2e487948af95343c21f5eeea2c1190a2b67ba617.nq.gz
│   ├── 2eed886e6eb29d87201274dee5722856a3fb08b8.nq.gz
│   ├── 2fa08a3f9a41d871b19a62a8c653565c9b8dfce1.nq.gz
│   ├── 322f93c218c907f6e1125d9d953e0229ee125aa9.nq.gz
│   ├── 3266fe01211ab23f35e7713bbeb756160a1fc97e.nq.gz
│   ├── 3377583512c1b5020951108c05b644872aac3913.nq.gz
│   ├── 346924782985cb989d83347903e2493e93db4f1c.nq.gz
│   ├── 348cce5ef9e4567724c1a54f1876982f932c1da7.nq.gz
│   ├── 3560f3eb541a47dec38a18a632e9631490a061e0.nq.gz
│   ├── 3686a245e28f3e202095dccae1630a17a8b7b1b3.nq.gz
│   ├── 36cb6bfbaa5de4f2074c6ffb269b8e05aa0d3292.nq.gz
│   ├── 3778c53352b8ce3cab7bfb5254f79eadcaf38b24.nq.gz
│   ├── 3a97ac7a080a324fb08537222db9ddad23275841.nq.gz
│   ├── 3beb0c2a1a9a9651686dc52f7df955d153a45c01.nq.gz
│   ├── 3d27613d8be167f9b3ef0b153e53c0b11f6a43d8.nq.gz
│   ├── 3ffacb753b9afc0f101bdd7b62dba9daba5ffcd9.nq.gz
│   ├── 40766f052002a850e0c49d9d3db130410e2af1d9.nq.gz
│   ├── 40d0188481d895e9f38c6192557e3b892c3df9ee.nq.gz
│   ├── 436cad1ad60e58dad2abdaf7def11b3f7504b405.nq.gz
│   ├── 43a3c2148a4feda94027c008f1ebd552b4ac0896.nq.gz
│   ├── 444ebce048098d3a982568e304ed6c32b4ecd082.nq.gz
│   ├── 4659eda8a16f2d05a594c08ae3c3e97248e26712.nq.gz
│   ├── 4882ee2be0fa24d49f4c2cb28166e8ce41d85137.nq.gz
│   ├── 490020dece664428d5e40ca04d67640e2563c537.nq.gz
│   ├── 4b4c7ecf34f03f1e9850941361075afdc6bced3a.nq.gz
│   ├── 4b4e3ed62652658de9b98aae24dbb41776eb94d9.nq.gz
│   ├── 4b6c3d784b08bfc6b97dd1f2008850e92947b7e4.nq.gz
│   ├── 4be3d9b016e8c51260d532dbd6140a22c7f82ddc.nq.gz
│   ├── 4c0f0b26ccddfe216fc6bc99bd2a3c762646a4bc.nq.gz
│   ├── 4c29493a95191c85fa023939c8af2c5f9ffe51d0.nq.gz
│   ├── 4d362bbabbc1acb83731e197fdfd5bf8e74a7e81.nq.gz
│   ├── 4d677cc1d88fca853251838ae20e473cb702ea84.nq.gz
│   ├── 4ec3a4dccc73e79f0986be94da86cabdd3638d7d.nq.gz
│   ├── 4eecaba00213c412f7b297ed6fa0550d0a85a7b8.nq.gz
│   ├── 4fccb34ffb55f7af45157358d30b53cfa0fc21ab.nq.gz
│   ├── 51827d18c24134377fa16022c47b743f2617f656.nq.gz
│   ├── 539b285ad6959626b150955fb0d948eca6c1f7d4.nq.gz
│   ├── 541a40629de9d10ce8a11fc3aa5541bc5f42105b.nq.gz
│   ├── 56e2d36d39f243128c2d94581ec4d025b6513d4c.nq.gz
│   ├── 583ab21c38c2bfde96c91a29cfbb42449f3d58f7.nq.gz
│   ├── 5b453f6d744fe7845eeb4fe50d8d74e5492d8db3.nq.gz
│   ├── 5c02ba8bc9342e6c189d90bea4282459c2fa4614.nq.gz
│   ├── 5c0e06be69f06b3f737bebe6692f02fcecf45c56.nq.gz
│   ├── 5da480f4b77734e3eda8313d27ab8e1cb62c97fe.nq.gz
│   ├── 5e005c0bf8bb68000f3385a3670f9126cf96ac48.nq.gz
│   ├── 6076971912e5a6f30b22631e287bbc80e3edbd36.nq.gz
│   ├── 630650f25d65294e455ff70be459d0cd1b2244f0.nq.gz
│   ├── 631c052c523288e3053902a07baa87d38ef361cf.nq.gz
│   ├── 6493cc00592e68d9aec3cbaeb642e1f2663eb9b4.nq.gz
│   ├── 64952341955f38dcc385dd4230ce6e78ea562e76.nq.gz
│   ├── 6749c7db8e5aff9b3c8d56771b89ec01bb803c4b.nq.gz
│   ├── 68d62a798b13138ff0e13fb800cee3b593de7539.nq.gz
│   ├── 69b8f83d052e5c042f357c209d433e7af85e4479.nq.gz
│   ├── 6e020c2d4af7a8cb266e8d32bed4f3ab139d8c56.nq.gz
│   ├── 6e445d25904e824989f730f8b4ab7934d1d25f7d.nq.gz
│   ├── 6e60e2edad4809e5b19e07c49597b8e028292653.nq.gz
│   ├── 6eec7aed847d7e1eb0c5ea2dc29537321aaa255c.nq.gz
│   ├── 6f0e282a3fd5cc80c3d922d9e051502320332cb6.nq.gz
│   ├── 721d7ef088357a67f811288e198a03b14eeb8158.nq.gz
│   ├── 7327e22420e59514c8bbc2d708b9c34ea1b2f91b.nq.gz
│   ├── 7652b95489516875a6c1b03029c63defb98caccb.nq.gz
│   ├── 766da24be46dfebc777688556d36b3081db46402.nq.gz
│   ├── 7690cb5b5c4b2e0afc331da1a9d83712fd02af9b.nq.gz
│   ├── 77fc22096713790b16acc96f1a8372a6ea8f5ec5.nq.gz
│   ├── 791b6e78498b5e87ff55d8cad5add3ebb35ad566.nq.gz
│   ├── 7be0fda3a6932e9c702fdd818db3cf2c6c64d4ca.nq.gz
│   ├── 8069bdddb3da7bd70c4cbe01a5a8433f1b04df84.nq.gz
│   ├── 81133b8670f892b979609a740b436094efa306e5.nq.gz
│   ├── 8195b3206c63aac96891d414aaf71f6fe000ee27.nq.gz
│   ├── 82f85560048fae7dee3f1b589e23d9bf43b8127a.nq.gz
│   ├── 830b790f2ce23270ea34015040a3c86ab11b4d30.nq.gz
│   ├── 85c888c86be62efb59866da82391e3cd868343ef.nq.gz
│   ├── 861d957a54a8c7bb49b07f9d2ca15fb1f92b285c.nq.gz
│   ├── 86b8c64ef92dcd7b665d0deaedd2be4acc2d46a5.nq.gz
│   ├── 89520ae3578c2fa7855fdf094574f17830d6b447.nq.gz
│   ├── 8a8ab6ae85347bbbaec9a09e59442397f47154d9.nq.gz
│   ├── 8feb824ef9120d04a4747a284f4a6f791f1253fc.nq.gz
│   ├── 907622df9ebb7e5f0addc5d157125ce6215ed9ca.nq.gz
│   ├── 91626b29c2d5924b2164d3f521f813e6aa426dd8.nq.gz
│   ├── 951ef49276d1da017ee4b40c11a80a85d2253f77.nq.gz
│   ├── 9bf540f373375105ee38bb646e1b515a16797ef5.nq.gz
│   ├── 9e13da714bff7c142c004e71f1c4fa0f46d07ba1.nq.gz
│   ├── 9f049e10ae5975d4c1610ab51926c7cc96ddf04f.nq.gz
│   ├── 9f49f55facd673f646d508590baa766fdd0083b5.nq.gz
│   ├── a0219649d4277359b737fe04c1f38cad1e5f9210.nq.gz
│   ├── a0e7ddaed3aa9ca8dada4b5756a1193fe9d98942.nq.gz
│   ├── a15b1f7fdef280a1757d431cc5ca74d2a90f2ddd.nq.gz
│   ├── a33c10e855047aeae8f486eee6eea70457f5946c.nq.gz
│   ├── a4f01a4b94de49c3b9efe4a96f78bba5b5d976e4.nq.gz
│   ├── a9e2d3f1beccc140a925d950bc8293cbe7c6fefd.nq.gz
│   ├── aaa84c8f24e83c5ec9c3b6c46164c103dca8d284.nq.gz
│   ├── ad38ac2a0cd2c095deddd9f9c9c91fc31c3126c6.nq.gz
│   ├── ad43590a17f63bef148cf193f2dbeeb947d41d2b.nq.gz
│   ├── b264ed8b298991bdbe1a91da56d7f6b834cd6925.nq.gz
│   ├── b5c0ce406eda0547878cfd5c732f435ef4e4219a.nq.gz
│   ├── b628db63e08a90d3bd55dc976ad6a9d4bbdad2e6.nq.gz
│   ├── ba965db885170b64224ac9749a73ec57d6908427.nq.gz
│   ├── baa55fe130619da3f39966e8cf00474c4e72471d.nq.gz
│   ├── bae7c951a5118206745445a8fee3fdab04e4cff7.nq.gz
│   ├── baf74b7fbf30d2b43a571066481656c9d61edd79.nq.gz
│   ├── bc9c38387029f4289c9af1446ccc0d605fbb81f9.nq.gz
│   ├── c0fd56a6edf4dc106b0bda7a3efa4e4230190f15.nq.gz
│   ├── c57cebf41ea9e583900a74948672ca8d1c28e297.nq.gz
│   ├── c7f9cb0b238589323d51b3d9d59fcbd4b74d2531.nq.gz
│   ├── c9c5abddadd4d94c866e7e46e491f7023f8e0939.nq.gz
│   ├── cb5960c6e40242e53536d371258d2c292928cee2.nq.gz
│   ├── cb5eec917bd1811c200576be4f60833f774aab3c.nq.gz
│   ├── cffb79e1c5767041d8833eff47d3d9f9373e0689.nq.gz
│   ├── d5b62b500ec86ae6e8ca3db3fda4c21e0beb08e1.nq.gz
│   ├── d79d3dd387d909e33881caf07a4efc83a0453136.nq.gz
│   ├── dbca68c46157a378705521bc56c4144f634b1e58.nq.gz
│   ├── dcce9eb9a6ce3aad3cf361c9c68e03f3294237c9.nq.gz
│   ├── ddca9a1ebea78962eed81818d066fc9afd3e7cd8.nq.gz
│   ├── df63e6268051a138f863cd309a332ca87171ad3e.nq.gz
│   ├── e246ad55b1ba848f3bef41fb12b6e6829ae3bdb8.nq.gz
│   ├── e413d5af027b4a8e3df4557f56b9e0901447abc5.nq.gz
│   ├── e59e92fe1b5776c88bcc63e2dc9c3988be3c5632.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec4c374b74527c67e4d1007db85d7689d225afb5.nq.gz
│   ├── ecfeab703e35834b8ab0437465af77e7a9ba0ead.nq.gz
│   ├── ed4e34796340a1caf40c85e25bb4abbd57d30ec4.nq.gz
│   ├── ee598b6161f31b91aef3d606924ec32ed91ac262.nq.gz
│   ├── ef58a6667f301a782e277e53a26fb4909bcf1941.nq.gz
│   ├── f244760cccb2610383bd093d7daf42ffc1eb35fd.nq.gz
│   ├── f445551afa0d0b99eb93e377d648a1c61f7eb809.nq.gz
│   ├── f5742ead2e2477bb942ea9d9a86a802435612490.nq.gz
│   ├── f589069593d2db2c4d9d7c4e53f64f5722ffc911.nq.gz
│   ├── f610249635fb614947473962cfdfcbcb9ed1d962.nq.gz
│   ├── f7243f9204c0051af90e3054067342b4dad4c224.nq.gz
│   ├── f86dd066eda188cc040be02959e8bbe75cdbcec1.nq.gz
│   ├── fa1cb86d342d7ab10ef580eabbb4dd6eeff13ad8.nq.gz
│   ├── fa32df4cf0fc404575a90d7c6f00bf843f6ad4b2.nq.gz
│   ├── fa950e2e27253b57620598439d71d9b0493ac9ed.nq.gz
│   └── fcdc7c235588e214ccf94441fdbf0eacc5eb2635.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a336173c2698d8a21c5ee908656a88800325f125.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 173 files
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

[fastai/nbdev](https://github.com/fastai/nbdev)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
