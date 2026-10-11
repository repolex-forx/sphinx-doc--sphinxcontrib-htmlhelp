# Repolex Knowledge Graph of sphinx-doc/sphinxcontrib-htmlhelp

RDF knowledge graph data for [sphinx-doc/sphinxcontrib-htmlhelp](https://github.com/sphinx-doc/sphinxcontrib-htmlhelp), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-doc/sphinxcontrib-htmlhelp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7f5d4ecf27fad97e2454fbeda94c6a105c994ff
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7f5d4ecf27fad97e2454fbeda94c6a105c994ff
│           └── chunk-001.nq.gz
├── blob
│   ├── 027ef7a28668d43a33f3d103bf0ea16c56288df4.nq.gz
│   ├── 029341683a465b482392a2ddad9c62f412990e66.nq.gz
│   ├── 02a03b04f2741cd16a81d3d5c742cfea2d0151b7.nq.gz
│   ├── 0301845ed3e09cd36975b81230cb1c58ae38d9f3.nq.gz
│   ├── 0374d158295c01686886e948e69f33de2f4fd419.nq.gz
│   ├── 04cef2c662075b9f34cbcc8cc6a3b2471881f283.nq.gz
│   ├── 0b3ed6ce3a60480de185207e0de588bed69a446b.nq.gz
│   ├── 0d1785bcf44a73959f95d56e30142f4112724838.nq.gz
│   ├── 0e3b8bd95745d9e1abdcd1042cae7c519c057a0d.nq.gz
│   ├── 0fd52f145be0bf7d9c2cf5613e49be2ca8a5e34e.nq.gz
│   ├── 100ef6ef07af7a3e82d6e398ff58f35e36c2a7a0.nq.gz
│   ├── 10cef947b5c9825090a209f2e6a9f0409e20de24.nq.gz
│   ├── 11b3f03dd4a254a75e51783e4a3d545587dc1326.nq.gz
│   ├── 14bd960abf4cf147f7e5be88e7026660bcc9acd0.nq.gz
│   ├── 1754715203540a5ab94187c980f69c2bdc14aa95.nq.gz
│   ├── 1c17c86034755a7eae357d2d2225b89104b290e8.nq.gz
│   ├── 1c817d1a2c5401496f997d2b0a662be4767bec20.nq.gz
│   ├── 1d23967338fdfa7f9b7b6143a78ca3a1dabb23f2.nq.gz
│   ├── 1da7b28d0b3ba9a49d02a702c5c105dd147e1016.nq.gz
│   ├── 1f19bf63fc37c39720df71f9adbfafdade0a6296.nq.gz
│   ├── 1fc4dd4d64a7fe48d703d4a677dd794003ad1396.nq.gz
│   ├── 20674bb3c5bd52f65b39af7d49006fde7c0f0e6b.nq.gz
│   ├── 210e5a36345b9e56ccc76a82472d79870a127760.nq.gz
│   ├── 2284db90d58f6ea9e95fd22729cf33b9a19bc4af.nq.gz
│   ├── 25a894527c8382c3d33c3010ddf255b5fb2a3367.nq.gz
│   ├── 26382ef3ac2ded269e325f581d0659f4175eef2e.nq.gz
│   ├── 2d9e563d651417e2c5c0ef4472862501bd5dd356.nq.gz
│   ├── 2e68a9d89bbdc8b069cf6e580e8a0ae63093a403.nq.gz
│   ├── 312755420ca5bb20dccce8c4fe04c353094e0f52.nq.gz
│   ├── 36ebc3b1f0b72a3ae54e6df5d6030b91927f6393.nq.gz
│   ├── 3934d3fc39cf1fbfb6ff26d92dddffb9b818bb43.nq.gz
│   ├── 397efffc480aee74c4846dae38513455e4e49590.nq.gz
│   ├── 3c858379f366f955450d863bc5026b97a0c21974.nq.gz
│   ├── 3cbb110fa2322409aa3f491ffe4f591b82c5b2d6.nq.gz
│   ├── 3ef0cf2a139aac94e0413f4f4baceb802bc3f6ee.nq.gz
│   ├── 3f3475f03ea09dcf168d303bd0b3d57038745bfb.nq.gz
│   ├── 408d0de712c85b8c509687926aa8b43bedb1a8d3.nq.gz
│   ├── 41999951268bcace9bc281a6630fa2f63055255f.nq.gz
│   ├── 422180b37ebee0664804899ad6b2a408475e555e.nq.gz
│   ├── 42dd452df366390c1019902e8de5fa739fde1c6d.nq.gz
│   ├── 438ee542159fe05dc8a18a22cbacea27001281b8.nq.gz
│   ├── 44e6750eb50eb9f4e6b54b47aa1e120484c3c125.nq.gz
│   ├── 46146f48cd78a5b37491b8b8a9577a647f6d7c3d.nq.gz
│   ├── 47670758fcbaaf172521ede850da2a63534cf86e.nq.gz
│   ├── 47a31bc9d657ef5ba89d1889963b30ab32f1ebd5.nq.gz
│   ├── 48c307108d9c9a2180ea6c4ea07e9b0d3efb2085.nq.gz
│   ├── 49410e378a2d5fe469f3dfdc6237bc8c3fb23bf6.nq.gz
│   ├── 4a7ac2c7f2822ac543da978ca1a3ee2c36867626.nq.gz
│   ├── 4a7b2c907bb3ea521fa0ebf9c2d765044208f02d.nq.gz
│   ├── 4b7dd2a5ac321d8dca7fcecd8e6507f3da934aa8.nq.gz
│   ├── 4deb0ff530117082d5be1deba735e0f539784622.nq.gz
│   ├── 52250ebb5872ddb5946c959ac6391aacaadddec5.nq.gz
│   ├── 543b17226ccaef44bcc3e11a23365f8acbc64f7c.nq.gz
│   ├── 553439883d579b9f5ea5f5e07637605fe5f3840c.nq.gz
│   ├── 555bd4d693ba547eca21f8355c76c32d5c320333.nq.gz
│   ├── 57a51e9444ae3c1169226930dc67d82458843719.nq.gz
│   ├── 599c2ddc1f89cff3d9c37fd275c2d00fbc9977ae.nq.gz
│   ├── 5acd1c5228f5a0e3028907919e12325a5c9946d1.nq.gz
│   ├── 5df0ad5681ce4fd43066ee0346832f9884caf586.nq.gz
│   ├── 60df290ea3b9586f7b52a8bc3ab91051c08a3859.nq.gz
│   ├── 61229e47d830160fee25401163fdff0fe0b8360d.nq.gz
│   ├── 63459cda827d1f614a1d2df06236f0604e53dd74.nq.gz
│   ├── 69fe264934b332b809cd6c9c25f272026b81cca6.nq.gz
│   ├── 6b814db05ad53d251544c2c97745d6c906c447b5.nq.gz
│   ├── 6cc9c5d4de30e30cd072c6c063bc4133e23c246a.nq.gz
│   ├── 6d64ffda5ee64d9d0d9f150fb0dc3547d504acc6.nq.gz
│   ├── 6e06b7e69dd1998713f4dfb11ae0a69e5884d74c.nq.gz
│   ├── 7044773046136a8adf83ab0a54fe955bad2a0b01.nq.gz
│   ├── 70d370cd1176dc9d4f011743e8917b0c10cf43ba.nq.gz
│   ├── 71633f22a7d5d4a3aabfd998269ba84c381b3656.nq.gz
│   ├── 73a9e4709f475cf64b8216d073c91cb6ebd49e83.nq.gz
│   ├── 7a8075461e9b64fa1b0de31003e91a38b554a189.nq.gz
│   ├── 83c50740701b68b10acf713bf311730b95468740.nq.gz
│   ├── 84698165c15b3c2512bbcf14720a8585c256c609.nq.gz
│   ├── 85e8df14a4dce372838e117421636f5298cc4cb7.nq.gz
│   ├── 866212f344de8fce59d53a807b6532ad4086dea8.nq.gz
│   ├── 86b896841ba6610f15ce18b51cb807e452aea450.nq.gz
│   ├── 86da7e5ca73d76696b663ea9c96c8ec4cfd04f1d.nq.gz
│   ├── 88b736e5dc8a50f2937cb199ced97533a13a86b8.nq.gz
│   ├── 8daacfdae022281e3f2bd880601f6cd508f3cb9c.nq.gz
│   ├── 8f32fc49306ab91dedbdfc8bf5b019755d6aca24.nq.gz
│   ├── 8fb1a2a6e516d318951a8e05797af4eeeb8bc09f.nq.gz
│   ├── 907989afec83aefcfeb667afaa4c32fbb25dbe12.nq.gz
│   ├── 92054219bde84ec3c3211e39570c22df24e701e5.nq.gz
│   ├── 962b6124893aa3b4d451f12a6a42ffddf367af36.nq.gz
│   ├── 9a9f28000523f306f01635cfd92d378e4c339833.nq.gz
│   ├── 9b43b4129bb454fe7441edbca6dec1bef4f6f27a.nq.gz
│   ├── 9bff9aad80c2b3c4947b63fe0f0ecd6377943cca.nq.gz
│   ├── 9d5870de2a23b306c3aa3209d9cd463ceedf0afe.nq.gz
│   ├── 9fe5a7c6f11b54d4943c306331a7e9748d875cce.nq.gz
│   ├── a123564949cf305c709127d3b3f3990b20200aeb.nq.gz
│   ├── a1e7b611d201ccab743256cebdb406aec850bb76.nq.gz
│   ├── a20fc1e6413ba42577a7e198e4eb8d5c0af9de62.nq.gz
│   ├── a4949e239517812c6a7720c8a4e1838d19cb2283.nq.gz
│   ├── a744eeb04ad7e88a67240eb73cf55c66dd3734b4.nq.gz
│   ├── a96636d8f1e8e2cb7d9a2fdb487462f6b5259667.nq.gz
│   ├── a9d429f1205ab36b507bc3fb1ff3c1202f0e4418.nq.gz
│   ├── abf7cc39e88bd754fc6efad15235d8594d0085db.nq.gz
│   ├── ad8c0c754b0ad5c6746f7b7396d358a63779a118.nq.gz
│   ├── ae62bebc6c7d92edd505b03149fc11188357fc2d.nq.gz
│   ├── aee7fbed5c2874f0a93be1e37c56c324c7bc2c52.nq.gz
│   ├── b031a953b3760df4ec83cf5333186450ca6488e6.nq.gz
│   ├── b24261a4c26c2b39ceead4a24e943912d1827f3e.nq.gz
│   ├── b27af9cb7fb4671a3d61b4fade5eb4d233d32ddb.nq.gz
│   ├── b49090ac159082af0889db78f63f3f30c3e4eee5.nq.gz
│   ├── b5960e08bd195d469ffed3aaded306894d2999c0.nq.gz
│   ├── b63caf36a945fefd9f436d1384ce593ba975a4dc.nq.gz
│   ├── b8ff0956f366b1c961e2ed6d54597a8be3f979e8.nq.gz
│   ├── b93f9f680e965ede9b8a3ab325a8130078d934c0.nq.gz
│   ├── ba033a4ae01b4d68bc08401af04af59ce55d678e.nq.gz
│   ├── ba61fdd0daaf8aacf8b8dabf4320bf0d22766126.nq.gz
│   ├── ba72759f78c2b6e75173961c5cf74421c05d5d7e.nq.gz
│   ├── bae1f90c4e4351e0b07d3532491cc0b9cb2e1caf.nq.gz
│   ├── be5d593a98c48f14b2f6fafe076a1e351087fb35.nq.gz
│   ├── c0cc89a8dfc5680af1f85aec8e4b299754b0aa4c.nq.gz
│   ├── c23e253c09c4b0395e4d4e9aa76ad1bc0a82cccf.nq.gz
│   ├── c6166e5b2cde56eeaa6da4e997d3b41470f654e0.nq.gz
│   ├── c6d3a574bf4414f52eb6369050d94fdd9f44a4d8.nq.gz
│   ├── c86768e85f6e0e8a7f42d527c29841f54a945dbc.nq.gz
│   ├── c8f7bd9bcd8566408e40e728280e4aefc81c6b67.nq.gz
│   ├── c9581cacdfeb600842ff7da98c80c702acae1cef.nq.gz
│   ├── d148099ed9956ad879dea93e67557d8d34771fcc.nq.gz
│   ├── d9ecc7c0c1f307489da8c4523fbec7772e9e53dc.nq.gz
│   ├── dc428c93bd97bd815da0845b0c105ecb37538ee9.nq.gz
│   ├── df3b8a10fecf9bc224906cef99dbbe5c1b58ae0c.nq.gz
│   ├── df7221711796d01b36f1d4f18405a21b964d30e3.nq.gz
│   ├── df8a7f9a8d444a451c5056e07757521338a4fcd8.nq.gz
│   ├── e1980f79444410f8476e91b2be1d54b4eece6ea7.nq.gz
│   ├── e216a13291eb60cc4e7d344de3f8bc0b9fe621fe.nq.gz
│   ├── e21f806287102d438c176a2ccb1c929c14cf1a83.nq.gz
│   ├── e337f0f6b13a21f1bb165fd67cec569e65c94ad5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82b3623877d8b69c5792e3ce3aea84d4edde3b5.nq.gz
│   ├── ed5439ee22696182c0d4d076e325c6c3ccb450e6.nq.gz
│   ├── ef9b35ddc2fda0b08722c4e86456fd2f2b77ccbd.nq.gz
│   ├── f05c8a2b6cfe7bd270604a29a306438464172c2b.nq.gz
│   ├── f24393bc52f6f97560487ac4ac778202011853c4.nq.gz
│   ├── f452d814b6d84d3c1108f4149a2992ca73d8d333.nq.gz
│   ├── f5251e66611fc230058be6260eea5ddd1878461e.nq.gz
│   └── ff08a83e6902d341f2dcdb96639ac42f532cf4d3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f7f5d4ecf27fad97e2454fbeda94c6a105c994ff.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 147 files
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

[sphinx-doc/sphinxcontrib-htmlhelp](https://github.com/sphinx-doc/sphinxcontrib-htmlhelp)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
