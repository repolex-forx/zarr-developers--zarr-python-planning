# Repolex Knowledge Graph of zarr-developers/zarr-python-planning

RDF knowledge graph data for [zarr-developers/zarr-python-planning](https://github.com/zarr-developers/zarr-python-planning), parsed by [repolex](https://repolex.ai).

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
rlex download zarr-developers/zarr-python-planning
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9dc53de99ac7aaec103a0e0d2883178ff26474b4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9dc53de99ac7aaec103a0e0d2883178ff26474b4
│           └── chunk-001.nq.gz
├── blob
│   ├── 02407916efc9de3b2bfd281df555f3c637d6acb1.nq.gz
│   ├── 0358a5a17ea6cd269c4976140602d11e7eceb10e.nq.gz
│   ├── 035c7c09da829b740dc441541051de5cbee34590.nq.gz
│   ├── 03b4ea580db79352f52e23f874a92034ce7ef9bd.nq.gz
│   ├── 04d269311527626a18146f7bea84ce65bc4b63c4.nq.gz
│   ├── 0a871524514ac3549fb7fa031e138cefaefb279d.nq.gz
│   ├── 0ad65871440a3eb1ae108a8562b7f907cb95b272.nq.gz
│   ├── 0ca94d95da6e00fd06c026f9837396eea8610a38.nq.gz
│   ├── 0cbdf77674149dda2668fab5813be776e7aa6003.nq.gz
│   ├── 13e795ce98511e2f8220c2b633dbcc377f785ad5.nq.gz
│   ├── 17894d2d2a5a2d7c8b287f3278802f07894586af.nq.gz
│   ├── 1953dcb60b23a36d67aedeaf1d11242aa9c1a581.nq.gz
│   ├── 20f83c1a94f8abb44fc68d4daed43d6e5375be5d.nq.gz
│   ├── 23c59ec4ff40bfd2e564cc023931b0baea74a09a.nq.gz
│   ├── 23e36211cf6748b04bc59039ed4632afdc46a64d.nq.gz
│   ├── 2489a88a51bc3a53b8cdc2785a83f517ce459a3b.nq.gz
│   ├── 265f0ec5332d55e3195e99b3772b82b50d1b2439.nq.gz
│   ├── 2c84ba12d17a238758c66df44b347c2b7fd0bb9d.nq.gz
│   ├── 2e07ef6bbb70036a7cbd998fc626f6a5731756e7.nq.gz
│   ├── 2ece45d7e9c4250ba97fd84c46fbe4bc36abf7c0.nq.gz
│   ├── 326e8670846ec91bdf71df2a0fc6b9e09887da84.nq.gz
│   ├── 35a939c34573c70d377b1dbba79fcd3d40aba5a8.nq.gz
│   ├── 36292b200f037d91589f392e2890fed342d3011a.nq.gz
│   ├── 3db388805d9ef935f01cb571130d5bd2ad653ccb.nq.gz
│   ├── 427c96a4b66a7eabbfbffe5f5850d4e0fad0c423.nq.gz
│   ├── 4366f2394e983731750700229d1c76723c71006f.nq.gz
│   ├── 43ebc0b479b96e39ecac85f8d67ef1034560ffca.nq.gz
│   ├── 4e6be1f5fa21baccb89b3d44dcb3e3c8f6374b2d.nq.gz
│   ├── 50daa73e2978e992193fcae0cb19c13359810416.nq.gz
│   ├── 5519f064c0b2ecda63261160b700dc1c89f6856b.nq.gz
│   ├── 553ed47233b7fe64ff19187ddbb036a780a8004a.nq.gz
│   ├── 5834ba2a33238e274a5ca4e28957eff951092bad.nq.gz
│   ├── 5df518d367be56378a0fc94fab60cb64924bfb54.nq.gz
│   ├── 63db49103930cf1909931d1c652b13e600a65404.nq.gz
│   ├── 64bd54aadc2cb240d7ed72e80b777201f48fceaa.nq.gz
│   ├── 6952a83e239586b720636ae94294bede53093d7c.nq.gz
│   ├── 6a8ecfa9263dd9844630539ddcb63017d5d289e6.nq.gz
│   ├── 6b31f23a4bc358d39d3d6a717260767ac6e198d9.nq.gz
│   ├── 6c3a2fb7115a9b1b73a84e8ea25dcdb0b9e6daa5.nq.gz
│   ├── 7097f2f641bbe40077d22c775b75080a5577df05.nq.gz
│   ├── 716acd275f5a69fbb03c591293da04da32ec4afd.nq.gz
│   ├── 7509d7f67f50e6eee9e3b0ed1867b47cf82fad6f.nq.gz
│   ├── 79444772a1c50f75aa44cea7880c8f129b7e994b.nq.gz
│   ├── 802f7980ea67c350be5a97ee319db2be0223b2c9.nq.gz
│   ├── 80e88c2f946f3c9bf982eb86955a00f1df195031.nq.gz
│   ├── 81174937a956453a04f587ecba8dfbee714734f5.nq.gz
│   ├── 81ef0bdbefd5a143c8bf60c1dff8fe122e7a9bbf.nq.gz
│   ├── 844e9204ffe17774c77d942e296e914c261ffdf5.nq.gz
│   ├── 8d7f131167a06999afebf7f9cb6d0af3f66a4fd4.nq.gz
│   ├── 8e03fea6590cdc8227d3dac2f18f45ba19448f09.nq.gz
│   ├── 8e5c5774500175c99baaf2f8e710cc983f50ddbe.nq.gz
│   ├── 928897ac73088128688a8e001451b104043783cf.nq.gz
│   ├── 94734666517c054affc5bebc25f1b1bfeb00d465.nq.gz
│   ├── 9c829a8e2d732a74c08544086500eee6f21ac3fc.nq.gz
│   ├── a22cd1b8186837be7c627438fb0c142a00d038bf.nq.gz
│   ├── a6c1683584b53997c25b2d2161e57513e547c553.nq.gz
│   ├── aa75aa61ca476f0ab4419bd7c691fafb1945fc25.nq.gz
│   ├── ab394e01f03b569ed831fde8561e0c2b305d3115.nq.gz
│   ├── b1203ef9d4400f84935f13a44da9bf3fcc32fd80.nq.gz
│   ├── b434d595bdbd626ea8c0bdafc0c61b18a8381eda.nq.gz
│   ├── b6f50dd41dbc98a7a77907e6bbb41c0f82970407.nq.gz
│   ├── ba6f59fee8f0383580c226f6f0281b082e4a110a.nq.gz
│   ├── bacfd0b75b05b28479777a04bd22cc2c5d8c609b.nq.gz
│   ├── bdb3b9f1d71c25d6f85b7c1a071237a10eb55742.nq.gz
│   ├── c427cec087d0e572e0dc54bc179978461b67ffc5.nq.gz
│   ├── c7eb2f5d6e60979719b22d81377c489013fb1d1a.nq.gz
│   ├── cb3e8cbc96c5f75976660840bdcc919e366fbba3.nq.gz
│   ├── ced7886087da97ea04c01c6398329f530bebfdb7.nq.gz
│   ├── d16d73f0190dde7ef5f654ad0da6c86b45871dfd.nq.gz
│   ├── d559062be1fb432a5565a0e977d2f3adf80bb1f4.nq.gz
│   ├── d7a2c53b8ecd286c075975599dee761580bc035b.nq.gz
│   ├── d95b5301eb5b3cb4cf5c9a31d336be5851654af2.nq.gz
│   ├── dcc65b761a9bca78f9bd17730339f054260c6e6d.nq.gz
│   ├── e1e954218ebed20fdacb20ae098f71bb6dfed8cc.nq.gz
│   ├── e3dc4d872fca2b72c64e45f039352979f9b45053.nq.gz
│   ├── e6e56caa68c8894b19fe34bf422087c146079d37.nq.gz
│   ├── e9dd0bb278fad661b61fa1955943daf7e5e228c9.nq.gz
│   ├── eaf11444495a197e865d2452ce8e78f23c97992c.nq.gz
│   ├── ee2b2663731005a7bbb2f59e718930a062a46431.nq.gz
│   ├── f085356b725063c8f92630837e9eb92b489be418.nq.gz
│   ├── f0d5d3537fc7d4206c3f320cad8dc6c0724ec36c.nq.gz
│   ├── f154487ec8b99969a5a0c2da0d23e2d927ce6ca4.nq.gz
│   ├── f5d6271460a3b9c3ebc56eca28b4287f8127488b.nq.gz
│   ├── fb4bdaa34f51db4dcea9468ee5914ebdc51142c1.nq.gz
│   ├── fbaee897e04e42ad56cd91eeac2f0ebb1254dbd4.nq.gz
│   ├── fe33b817d179afe9debb1098d8418e52048c3dfd.nq.gz
│   └── fe840054137e2ccda075344f21e728249a60a2fc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9dc53de99ac7aaec103a0e0d2883178ff26474b4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[zarr-developers/zarr-python-planning](https://github.com/zarr-developers/zarr-python-planning)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
