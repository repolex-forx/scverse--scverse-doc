# Repolex Knowledge Graph of scverse/scverse-doc

RDF knowledge graph data for [scverse/scverse-doc](https://github.com/scverse/scverse-doc), parsed by [repolex](https://repolex.ai).

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
rlex download scverse/scverse-doc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11308278ecb1738800c0c22d14637772ea5cd239
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 11308278ecb1738800c0c22d14637772ea5cd239
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ad6a6ea9418df96256615a564065e38c8332ea.nq.gz
│   ├── 01448d136e77a1130c38c1beb12cb3b60d701367.nq.gz
│   ├── 062e6179c84c619b6e43d6f8e4c2aaab727e0650.nq.gz
│   ├── 0e3a8b7ea1db5c610c903c6811136a199fbca9cb.nq.gz
│   ├── 111688541df5f035c2d5029e4cecb87929e39c65.nq.gz
│   ├── 124972d9e5f427254bdfa25c9846b85be66ca209.nq.gz
│   ├── 12ef9a4ec12de1bd2764d9f58179acfedd2010e0.nq.gz
│   ├── 15df4799f263cf2871fba56ceb25628fa22c24ce.nq.gz
│   ├── 1a1b67e739f594ffbedd56744958a7a301072cea.nq.gz
│   ├── 204602d9fdfe30572949cc2d9ec5b1af695ba359.nq.gz
│   ├── 230bbb0ce1d63a5ff9bc9a1b30148c9c9888c344.nq.gz
│   ├── 254e9c94434c7df3b46e4e76d750239e9a9a1a2c.nq.gz
│   ├── 2936d5c8737a22ea74c5c1f3289efe5849cf57e8.nq.gz
│   ├── 2dac9638ee0eaa071a1f43cde3d8b5578fcdedfa.nq.gz
│   ├── 2e43fd17bbf7776d60b68d8baf5ac69e34e178b5.nq.gz
│   ├── 2e4daf68a8bd00a0a64727c2cd31df673380108e.nq.gz
│   ├── 31908151265bdd32d27c33b981338ce3270f4d20.nq.gz
│   ├── 31d8cd41117f78bbd53ddeea10204cf3c5c22a81.nq.gz
│   ├── 322793040792b8440f6bb6db6e29660b8e54b266.nq.gz
│   ├── 336c8abc929d5a910b5c69ad265b940f6a8ca835.nq.gz
│   ├── 36d1874618b1d0099c4d192c8a90500d69bcc723.nq.gz
│   ├── 36dcfb1b4da1d609558b6cb1dbd1414470652e94.nq.gz
│   ├── 41525461e7d747e8b5259acd1cf770ac3eaa6588.nq.gz
│   ├── 44c3b03f0a08d346762c5d8d2c2a4606e7f9515c.nq.gz
│   ├── 46b84658355664c0efe36c6028e99c2707312df1.nq.gz
│   ├── 4aa2047cbb5059866b2cbf5891f0e6e2b8f3a703.nq.gz
│   ├── 4e0d389071a4e067db4fd5642d7bd21320e04008.nq.gz
│   ├── 4f80ae47a265352aaced89647552c492fd53dc47.nq.gz
│   ├── 50e19c46a6e5b17f68f04ff284cbf2fe36896b27.nq.gz
│   ├── 510a8223e9fd9d4792042e6f1a07d1d77bcd18e5.nq.gz
│   ├── 5185ab32523e2f9824ded7ef6ba6b0d184ddf558.nq.gz
│   ├── 5626016970c4e279513f0382228d0c6cd0e46ca7.nq.gz
│   ├── 57ac1a3a9b622a89c35457500286e6af52f7a103.nq.gz
│   ├── 5955ce59811de53f8158fd2dcab0fceb8000c695.nq.gz
│   ├── 5b62547f9aef3da3a38806baf365ea8c059675d6.nq.gz
│   ├── 5d41aae47741e546b542f0ee4043031c8936d13f.nq.gz
│   ├── 6104b9e6f4ae97e25a2fd85f24bc2370b23bab6a.nq.gz
│   ├── 66678e378b55a7e2b28d2087164af8999aff39cb.nq.gz
│   ├── 679084c2e7e7cc56f322ab85e1946817a4b3e62e.nq.gz
│   ├── 69bdf2ad0506b34e274d8d95a483e034dfd024e2.nq.gz
│   ├── 6aee0aa3f150aa906f12d19ffa0087c376334be1.nq.gz
│   ├── 717d689637d3e807052b41c24752a86a12105c65.nq.gz
│   ├── 74f60c1de3b4d3acf1e6aa3b085443e256574286.nq.gz
│   ├── 7bc1110d08e9f6882ec408724b8e7a3a5d45992c.nq.gz
│   ├── 7ccc3ad4b51cb736b7a3b3acc23c521f03ea1fa0.nq.gz
│   ├── 7e2cfa03666b086b7f24c57fd54118e9a2013ecf.nq.gz
│   ├── 819bb2e9fd24be0eed6c0497456fae4113216e47.nq.gz
│   ├── 8231500ce9886599cd24b75a618b6d4ef98f0822.nq.gz
│   ├── 830abacf06b7005499de12df8a6083a35e83ae1c.nq.gz
│   ├── 831d9d0cd86ef23104621503d3b6f7cbb1d421bb.nq.gz
│   ├── 89549a561e581513be221092d888ff1fa32967ab.nq.gz
│   ├── 8b62c2999e88f25b3ef0db2ee883abed1ad16369.nq.gz
│   ├── 8b9c7d372e8d25fb3b74fe6b2fa7c3ab42e82eef.nq.gz
│   ├── 8e36d06cdd08a557b67c2a74220134b35a0f8d2c.nq.gz
│   ├── 942ff92626e31a4ee9b780211778857a26e441de.nq.gz
│   ├── 9e07d3aec52f67f54546bb794890e0b7661cbcb0.nq.gz
│   ├── 9f5bed44ec106502c159a68e71e8308abddeb4f9.nq.gz
│   ├── a28f6d6db23b1a5d4fd61bcccda38a79dffe783a.nq.gz
│   ├── a612ad9813b006ce81d1ee438dd784da99a54007.nq.gz
│   ├── a6e6624e82cd07cb723f4fbbcec050b45070edc0.nq.gz
│   ├── a6f4ebc6c84afed873a4bf8f4d7aab8bdd13355d.nq.gz
│   ├── a7380b5ff5beb59250109986ed0ddc43c255c251.nq.gz
│   ├── a932d6273e3b2bdcf0a453fbbaec07fdd32ec830.nq.gz
│   ├── adf1e3f8624da17266bcb9fb63b243a42d42d6c6.nq.gz
│   ├── b0d0983f299910d6172c3b3635811fd6104fd1ee.nq.gz
│   ├── b0e7bd050f2ba0482d8cccd88f2ba28903af78a8.nq.gz
│   ├── bb569938b17dc74a46a2736cad005139fb2c25e9.nq.gz
│   ├── caaeb4f73220343cf55564c4b747c6434c231fd8.nq.gz
│   ├── cb23964bd75aa2c16072a7164180bbe163ed7085.nq.gz
│   ├── cc63992fe1ef466adb4bec2a1facf3fc810bea31.nq.gz
│   ├── cc6ed3da5fd2d4cb8b5e7c8780368be0a0abaa4a.nq.gz
│   ├── ce7e44a86ce6ef63a19fb8db86c6c597e6b37662.nq.gz
│   ├── d1a7c89a25d631f6d0e5819ef3e916efe49ec159.nq.gz
│   ├── d3fe168256756f7c9461200609ffc8bd22197b0f.nq.gz
│   ├── d65f3d39f0c841462c11578260af5d764d1085d3.nq.gz
│   ├── d92aa9a31ae61d5cec0178a9024c4fda7c9a1c28.nq.gz
│   ├── d9e79ba64848091a9bccd21dc241c61c669dad7f.nq.gz
│   ├── da69f80931e47367b1402a5e0b58ce39461d52ba.nq.gz
│   ├── deb04119ad5839de9f161b27a3c1101babac841e.nq.gz
│   ├── df3d8862fbaf7bd0f58ab9aedadd3fd446ecbd65.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9b047dfa681b36a6e31755b01d62cf8b7237783.nq.gz
│   ├── ea80448a5e99e77200f4856c63c90931354cf3d4.nq.gz
│   ├── efd7265bae7967fe4e55ce34e7cf3a0c7d71c770.nq.gz
│   ├── f0483b3bc3dd30e54261bcff4ce384267a55b5ad.nq.gz
│   ├── f59c702b7d9fc386bac0652c045b97fc7f5c2b85.nq.gz
│   ├── f5a62c7ab41340f21cd5866a2747b8471f48c904.nq.gz
│   ├── f8d3576639790f2c2b6e6fa1d20e2345fc28c982.nq.gz
│   └── fdb3aed227336f17f230afc81b64954e2802584e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 11308278ecb1738800c0c22d14637772ea5cd239.nq.gz
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

[scverse/scverse-doc](https://github.com/scverse/scverse-doc)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
