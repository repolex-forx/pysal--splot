# Repolex Knowledge Graph of pysal/splot

RDF knowledge graph data for [pysal/splot](https://github.com/pysal/splot), parsed by [repolex](https://repolex.ai).

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
rlex download pysal/splot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b8361cb5f4685d0945e08cbf9172ba701ce57c44
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b8361cb5f4685d0945e08cbf9172ba701ce57c44
│           └── chunk-001.nq.gz
├── blob
│   ├── 00f599cbacfed7ea505c5ea2e2cb32254c97201d.nq.gz
│   ├── 015c7e5c49ecdd90f8ff73a117890a8fcafa4688.nq.gz
│   ├── 02411c6f5f113b09a076134f73b9c2232821bb4e.nq.gz
│   ├── 03eaa455c90ace69fe3718a3587bd915e704f139.nq.gz
│   ├── 04cb534314fd978ee57fe0eb63eb6e18c3d96886.nq.gz
│   ├── 09d2529e0c009089674834f13417cf47f5a9151f.nq.gz
│   ├── 0a580c9f4089536d2ad0e9bf37d6d1f6dc4afe98.nq.gz
│   ├── 0fdce4920c24d2e514ed462a80e1a41c10b8df1d.nq.gz
│   ├── 10820567c067740f9eeb49028f09a84e942b7477.nq.gz
│   ├── 12ad1266b475ded6d8dc60339fa8f70a05c01fea.nq.gz
│   ├── 13468274c209ab2f037acee0e4c8a77d2c14c638.nq.gz
│   ├── 17433e2d4c065e1e879c5feeb989bb17dbafb4d4.nq.gz
│   ├── 1ac3c1e3197e9583b0236b38ca3428c20f28d456.nq.gz
│   ├── 23fec9ca936de22cee8fdffd5175a63f4efa85ec.nq.gz
│   ├── 2499da123da2dbbc75b3bbc3bef617f30e41e120.nq.gz
│   ├── 317df7f55360a29af75c2456ff160aa56b058194.nq.gz
│   ├── 32ccf0475b42b0f1b8a67d0ed4e71165ab753c99.nq.gz
│   ├── 351f12c3031d6352c23b80c1f6d8892742cbc064.nq.gz
│   ├── 360bfdddf0a592a4a99db121a3e63f3f189a01e5.nq.gz
│   ├── 362da5abd98ef5ab9346f9d98022af8918a401fe.nq.gz
│   ├── 3a83174424d53f350b531f1b208ab8f6b6505d22.nq.gz
│   ├── 3d05693155fef112f29656600be50600a30548f6.nq.gz
│   ├── 418e188ad5fa76ba8f9fd71c9c96c1800dab23d6.nq.gz
│   ├── 45e6dda753b9c1571f3d5dead92b6736ec9f84da.nq.gz
│   ├── 4d93d39ccffa5c072ff1d59430f1fded381b5ba4.nq.gz
│   ├── 5391dacfb916b2a95c13ea64df97d706c5edc1ab.nq.gz
│   ├── 551709ceef054368606a4b4e08a360380375046d.nq.gz
│   ├── 56f8df0dfbcfc6e226d59486876345569bb7c038.nq.gz
│   ├── 59635d5bd198a353b415484d39f55319f24dd480.nq.gz
│   ├── 666babe1736ceb1469081b6c7eaf80efaa8755f1.nq.gz
│   ├── 6ebc08613a3047c7af51eb431126a78555a520bf.nq.gz
│   ├── 6f5382f1ea7c630e391aa4b1f093963f75fe2e43.nq.gz
│   ├── 6f85547749226d458e8bad051e184295a9dd8589.nq.gz
│   ├── 745cc06ce12d84b186a63e431caa15c2c8c1fc4d.nq.gz
│   ├── 79085ec49da8d7e95402bc5c9fb9a63d69fabc3d.nq.gz
│   ├── 7be6cf4e94ffff5a053ade659b6e3c0649a95c64.nq.gz
│   ├── 7c23ee190013bce80c615aefe667acc15736cf7f.nq.gz
│   ├── 7e96dcfb95e724616a095d8f0352cc6b063f41f5.nq.gz
│   ├── 80d93a7ccc861795f3cf1a1991daf46070ce026d.nq.gz
│   ├── 9279e9fd300b269190dee2679beb0604be780008.nq.gz
│   ├── 9445ce538dfeba2c1cc043f6f2dd41e5810872b1.nq.gz
│   ├── 94eee975c813d028d1567de8296e9cccc810cb6d.nq.gz
│   ├── 9b6b374dcfa5ed39d57f2cb3f22711923a533f74.nq.gz
│   ├── 9b8284450e6fa2678895d4056edec0fa7abb4d65.nq.gz
│   ├── 9c1c3a9ceb34254db89565ddd547204b8f114595.nq.gz
│   ├── 9feb65f936f456e3ad6371650093a723d05a3cf9.nq.gz
│   ├── a5738782abf679b3e7361e35d66c8120949fc0fb.nq.gz
│   ├── a79ddc620dc69ad5bbac23ec678c3acab1ba1fa5.nq.gz
│   ├── b16893ce362b3848427e69078c0b58416052f836.nq.gz
│   ├── b1fabbc63e49d16101a65ace981cf708ddd4797f.nq.gz
│   ├── b28a737346c8a6f1239d36ba7d94d3e5218a2630.nq.gz
│   ├── b329217586bd48ae1b79d0d4b6ca94c25a3c9315.nq.gz
│   ├── b5a03e9cf3f3775014b5d354c754a04780d2aeee.nq.gz
│   ├── b7710b684ba2ca3e44359ca94b0ac4446a63075c.nq.gz
│   ├── c1d5d823ded3df1344fe1c11c7f930bd29e80eb3.nq.gz
│   ├── c943fc246bfa0f3983f8973bc3a2fb73c6f75fe2.nq.gz
│   ├── cd737a42727aa9fe97663f9f8398ec328e4992dd.nq.gz
│   ├── d042d89f6c709f582c3d266dd99428f46004b826.nq.gz
│   ├── d35a07b4977419b9dad86817c72c6d7162a33709.nq.gz
│   ├── d3e58f43feb2cdf08bdd92cb031c301ec7da2599.nq.gz
│   ├── d5173f9a75cc3b1771ff8793928e974b427f3029.nq.gz
│   ├── d54039ff7755928de4136c630e974e63cfb489fe.nq.gz
│   ├── d79bf0444b2af82ad4c6e683e1b3c8b9b35f2398.nq.gz
│   ├── d89894267e56d7e6f0ccd44682142457d4d74854.nq.gz
│   ├── db47718e87f5ce0b815cc35680bade93a6bcec3c.nq.gz
│   ├── dbc6ddbf5616f1bae3d40b0b1f307c38ae67f6b4.nq.gz
│   ├── dd434d44a1796a34562e17dfc5a77c8f68da97ab.nq.gz
│   ├── e283ecbf1a62fd402948751a3f1e0ad31c8cb9f6.nq.gz
│   ├── e45f368b76c08b752a534dd1ff3bc97ecef6c377.nq.gz
│   ├── e7115c6e57f26d44b75c076235463c5e941ea712.nq.gz
│   ├── ea3372ca69983b82d31e43db818ee8ebe3846bfb.nq.gz
│   ├── eba3132e1dd6f9ae7305670b3239fe32fbd5b14f.nq.gz
│   ├── ed7b648d8c564aab1ad06511bc94a693a8b90a2e.nq.gz
│   ├── f1413a1ed0ee9c013e8671c25d84872b840f8780.nq.gz
│   ├── f1cb1b86d3ff1045b5bd75c637fa1e29ed5b8a85.nq.gz
│   ├── f3407f646980d9c0b29b179a0297c11834fa7322.nq.gz
│   ├── f53d4dc7c225ff44da7640b1eb9029faaef4c6c0.nq.gz
│   └── f6f6ecc6ad1bf098caf268178f77f13f31cba192.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b8361cb5f4685d0945e08cbf9172ba701ce57c44.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[pysal/splot](https://github.com/pysal/splot)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
