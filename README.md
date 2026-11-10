# Repolex Knowledge Graph of badoo/Chatto

RDF knowledge graph data for [badoo/Chatto](https://github.com/badoo/Chatto), parsed by [repolex](https://repolex.ai).

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
rlex download badoo/Chatto
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9235560535f86d898bd9252479afacfd7a314f6f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9235560535f86d898bd9252479afacfd7a314f6f
│           └── chunk-001.nq.gz
└── blob
    ├── 019d857972e7fb54380249385bbd2843e58c6b8f.nq.gz
    ├── 02b2b46b05c48d3a4955b14e531ffd1d244abced.nq.gz
    ├── 02f5c908e3288c9384fd7476557bc819df9c2863.nq.gz
    ├── 0493d8b8304475ccebe5c1895a088a5d438cd08f.nq.gz
    ├── 04d454b759766c1b5ab39c6fe870ee92a4b45dd9.nq.gz
    ├── 04f8d0eb432eee8164a788b2043ec016df8c01f5.nq.gz
    ├── 0532277d574a1c08b8226fd006ed975a8f5a5726.nq.gz
    ├── 05da7b0e19ebc56ff8ad8a034c03d108f67ccc4f.nq.gz
    ├── 05f2c34f7801f8fc2fbd465c1523264c4f8f8641.nq.gz
    ├── 07e738bba321f2b71aed202ebb32ec95fa4b190d.nq.gz
    ├── 07f03c1f787fc0498fedad30fecd55616865d2f6.nq.gz
    ├── 07f93576a4a73680ab540fe3c37bb2239f15879b.nq.gz
    ├── 080099389132409dd35001fa3ba8df79e6179e79.nq.gz
    ├── 08539a195c296ece82ea881145cdff23e27ff984.nq.gz
    ├── 0896cdfb312d4e953946da507f130227031be0a1.nq.gz
    ├── 09cd607884ed40e577462839753ce7d64a075903.nq.gz
    ├── 0a128081ce23c9f272e12a882fc207d7989ba51a.nq.gz
    ├── 0b96bc72cf931037d4e02b3d133084babde24337.nq.gz
    ├── 0bc622656160bae2a988070b4a1588c67c7441ab.nq.gz
    ├── 0bcdb7d85a49e3cd7ab9d1e785f4062b037b1865.nq.gz
    ├── 0bf22d831380e62f3c49b6e38e27d93c4744dfca.nq.gz
    ├── 0c52379c1b76f85fabeca2ee6c7e3c43a138c8e8.nq.gz
    ├── 0c89fc927e327c0a9913d8300a205efbd30cedbf.nq.gz
    ├── 0dde69d8f8c25175cbd2bddd05ab07b9f81da950.nq.gz
    ├── 0e981f3a5e80e8f394d29830f164aa84bd19047a.nq.gz
    ├── 0edf1ffdfde757ba9742c52f3ce66ebf04f833ba.nq.gz
    ├── 111786315cf5aa5ac39476eee5b3188b7dbc4c0f.nq.gz
    ├── 11817c74af88b11a7b76aac1e718a1abcb2bf4d4.nq.gz
    ├── 11baca150cbdeeae09d875d19c7fff96dc43c2a4.nq.gz
    ├── 125e69ad8509b94d0f7b0dd56ad8b30d511a4eee.nq.gz
    ├── 12be67b5138410b66859f1e829e8d6476ec460a0.nq.gz
    ├── 12e445c2b5d49bdb9d7718ccaac47d32732a1322.nq.gz
    ├── 139eacb9f6ab9f5ce619302835856e03ec6c8ceb.nq.gz
    ├── 1467494fbb1f336f228b4c4f5169064a102537ff.nq.gz
    ├── 1592d1b74b2ebcdfc018e6c3eb64235d165794dc.nq.gz
    ├── 163f83b66f2a5b4b70c89dddfff07405c0297786.nq.gz
    ├── 1749e5039c2b7404cef4e4785d6074fcc07febd2.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 1cf831adc59302750ed84af6b7ea81fb32da3f5c.nq.gz
    ├── 1f3d9f761a620ba99a685badf3ec948e62f7468f.nq.gz
    ├── 202b846d883c16299732bda3a171d90eb761494d.nq.gz
    ├── 212efa4538a04d1c42cc2b699a0aef39344eae80.nq.gz
    ├── 21c7c05899d64b084b9e94a85ef7e16acafa6ad4.nq.gz
    ├── 21cad907bb67b17f9f220ef3c6acddc6d3986cd8.nq.gz
    ├── 2243fe6e27dc60546f37eca17f97ed75802d224f.nq.gz
    ├── 229d50c6b4eb8ee2706b0838dbf006b0e9ec98ef.nq.gz
    ├── 23ad59cad22f95bbc73c3dd71ecb3fbb311e50d6.nq.gz
    ├── 23af24925584410f972166b18c48df302fbe63be.nq.gz
    ├── 23d5a243d029127308aea56cba7f6e3a0c84188f.nq.gz
    ├── 243920faf99b719c6fc8b089abf7bb159bc47475.nq.gz
    ├── 2751069ba5967248d1f5aa42be5307d46e64b0d8.nq.gz
    ├── 284651da86cd7312b1cde859d61e510e29489333.nq.gz
    ├── 2860e7a6f09ff28b25f553a3e3907d67ad85a253.nq.gz
    ├── 28d135de1dfb313760b3e3068c9d787727205f4a.nq.gz
    ├── 28df5b19e2823dab60ef53f7eade4e93f720fcb9.nq.gz
    ├── 2b0d1b4d615817d4febc37bc3deda2d29181e594.nq.gz
    ├── 2b662b976ab77dbe58d4150a8786ea1aeee92efc.nq.gz
    ├── 2bb264de62e31ab79e6468aa686a8277d324e05e.nq.gz
    ├── 2bef5f8eb1f50f17f9dbb709d4dbdaac47789975.nq.gz
    ├── 2c8f13d842a6d50444eeb350ec0beded723ee94c.nq.gz
    ├── 2dc1642186ca6badc9b5f22409d1d6d4aa4cb0cc.nq.gz
    ├── 2dc80e89c4adabd82ccc3d8fc7290bea3dd8a711.nq.gz
    ├── 2ec8676f9f558922d4a38ac8b1343df2b88ca014.nq.gz
    ├── 2fb0a673b24adf200fcceb91f6f2204bae6d5115.nq.gz
    ├── 2ff820a3169a62d5b0d73476eda56cc3cacb1163.nq.gz
    ├── 30c57bf8556093551e5ec1e662ea5f816261ee87.nq.gz
    ├── 30ee6c415341fa3c9c59fac2f542d12c7909a4bf.nq.gz
    ├── 313151981a8c57f1292a89dda88f2e8cbb9d3d76.nq.gz
    ├── 31391cd1639872195406601a794ac9ce22d45ed1.nq.gz
    ├── 31f354c298b8b344f23551d16c2e7c1f956d62f2.nq.gz
    ├── 332a757869590c37909d77a04724ca85948b052e.nq.gz
    ├── 3359549bb03723b81364787ccd89047821e26d32.nq.gz
    ├── 33638b4b24768e779ee3ef758307223fe8d77646.nq.gz
    ├── 33d0991e786b8ac9264202d03d9b94fb264dbf2f.nq.gz
    ├── 359950ab9480d38f624bae9440024650266a28b2.nq.gz
    ├── 399cb42710200b56579e355a66d9981a73e19d01.nq.gz
    ├── 39d390cfb35985773f11b2855b651451e146d5eb.nq.gz
    ├── 3a63cf300dabb9834247f092c3f6a9a381007c96.nq.gz
    ├── 3ac2b3a648d4a007ffbee42b8a0175fb72cd223f.nq.gz
    ├── 3c4248f7995134686f1c015bddd1b42a733d9a04.nq.gz
    ├── 3c61f100de9d684dd216d3bdd7c62a9a52f8bff3.nq.gz
    ├── 3d58c43966afbf256218cc308ae23aed32ff57a1.nq.gz
    ├── 3e60ab5ce1de9166f3e354db5e8dfad7864923be.nq.gz
    ├── 3eac47c2d50f15cbd2c671ccc6a612e9bb198b13.nq.gz
    ├── 3f2ca09bbc51f7e86852ade3cf60504790565cfb.nq.gz
    ├── 3f97ffe16dbbb662917ff03c0d4d9823fafa1fbb.nq.gz
    ├── 3f9eeba24a88f603629fdb962d5e6db29223929c.nq.gz
    ├── 3fe29c52d601efc45cdbf6e728f0b1ee3ef4bc22.nq.gz
    ├── 406b01cc4ded344eecfaea12aa3b0752edaee1a2.nq.gz
    ├── 41c5a73b212ca5f61ebcfd0ecd04c8b1e2e73127.nq.gz
    ├── 425c4999ba839fce580c07ecbd18d216365728f0.nq.gz
    ├── 431b22e85c6e55aaadfde26078725f44a5dd9d02.nq.gz
    ├── 443a93f151f9b24d2e428aa21f02d1ee3d2549c1.nq.gz
    ├── 46008a9d5a0b7011bc8cc5764e4039393dfa59ad.nq.gz
    ├── 4663c63e49ea7d0e357133e350eb551824bd33ea.nq.gz
    ├── 46df5f565440a63515ce447b3d25485c02c45058.nq.gz
    ├── 476fda102f17cd7c5bbba41fa513b90cb70b0f6d.nq.gz
    ├── 487dd5a11050139e8b4a9a86dee3910e3481a2ba.nq.gz
    ├── 490897bd7f215e998d2ea074cd7408c4b408ac58.nq.gz
    ├── 49677364cff261ec044137a6a60080b4602d50ce.nq.gz
    ├── 49c47b810910330ba5c16f2b4f4ee399515a91ab.nq.gz
    ├── 4a5d187410a0bf3e20671e9965ca20e684b30c82.nq.gz
    ├── 4af19e5467b2d0162dd7b0411cddedb6ac5af4c4.nq.gz
    ├── 4b4c8dd79e61672fa1eb9240ba849a7833caa152.nq.gz
    ├── 4d7be1e5acd5c1761bf9e9b24018f4900b5da815.nq.gz
    ├── 4e13cd3ff5810c634c908114372b34f3ceee7c07.nq.gz
    ├── 4eaa3f32599e74799326f9b248549fb61276c567.nq.gz
    ├── 4f08542bb1c1d34a3e7adbb3b6cf2066dab50c16.nq.gz
    ├── 4f09e7028bb9dbf8d06fde4c452fbc3f85ee1c47.nq.gz
    ├── 5035bb4f98736c14ca6356155773689c6488d244.nq.gz
    ├── 504f422fb3b8831a0d4d8ff79d7fcd5e53085382.nq.gz
    ├── 50b56f9bf9ad0751298b61632c56338197da6410.nq.gz
    ├── 50fcd6c5f60ca2bd865e49204d2d6413cea8d2a4.nq.gz
    ├── 51361b25a5d44763ec559d8424459aafc776926a.nq.gz
    ├── 51f029fb9ccc95daaabff519815b06667d13f27d.nq.gz
    ├── 5203b43a91dad8d6ba9f7d04a72f6ae4286e87af.nq.gz
    ├── 5228f9d02d7ee978d29603cc1c217485c0c967a9.nq.gz
    ├── 5284837db2f9ccc0ffc351aa896ef48143a0f3b9.nq.gz
    ├── 52e1b6400d2dfe3574d174d1eab98bbb080fac21.nq.gz
    ├── 5340180ed05386ac20128793111edb68441fad22.nq.gz
    ├── 538827df3df947c221461e1a82b7d8189c208744.nq.gz
    ├── 53f24813a813e485bb10c0d8898bc7826c2e3847.nq.gz
    ├── 56bfa2a02a7900f837d3282433ed2c13a7351692.nq.gz
    ├── 5767addfb517487b47937b739b51cabc59a0a469.nq.gz
    ├── 58565d9c3a149191b39921757ba68be43155cd5b.nq.gz
    ├── 58ea7dbc934e99bc80ee3c2d64d6a4bc2b395536.nq.gz
    ├── 5915f7483127de8754d4806819c41477856edf49.nq.gz
    ├── 5a092d22f242c1d2c71ef844e92f742a65b45d57.nq.gz
    ├── 5b052cffef851fded30be9dcec3c7c90a583e9f5.nq.gz
    ├── 5b825ed12d2942d7688a54a4860479032597ade3.nq.gz
    ├── 5bc432f41e4a5bfb9c5f8fcb6dc01837ffaac21e.nq.gz
    ├── 5bcc65890024d8dc4aeacd5dc3952d6c686ea9dd.nq.gz
    ├── 5d07c7b712d92e91a3d058b2e922fc3500a81874.nq.gz
    ├── 5d1b1a5c89330147551ec27a0544906cd91f7cba.nq.gz
    ├── 5ec5ce5b0c47380769c6070837947dac5366d876.nq.gz
    ├── 5f84a9f20c20d002d05c6a36bee199228c217a18.nq.gz
    ├── 5fd526ff3c9354d66674c3dd6ef9f3de09b5179a.nq.gz
    ├── 600c88128e2fe2cbd921ec0aa9fb46641b85a470.nq.gz
    ├── 60d6865470c3a9aa011af727c47cd15f4a683e09.nq.gz
    ├── 60fc4c79c635f795f7dd1c35b04f76270dab235f.nq.gz
    ├── 617abbe76837145c58e2f90e8d7bb5e959805a19.nq.gz
    ├── 623f6b19d3849bc0508ed441dad0b8ddd4aeb50a.nq.gz
    ├── 624ccbf1e962761e1994232aa2dc253b6f0074cc.nq.gz
    ├── 636bf2a7f14a67ab7bb041335fee08e9a13f4b5e.nq.gz
    ├── 6398e4c3c78f97833f02f841963143375e96c900.nq.gz
    ├── 63c88c21749902af45098b7f294ba25039bbfa8f.nq.gz
    ├── 64aa0a04002c9c17b958e56dfcaa13abdaeaa14f.nq.gz
    ├── 655f1492364fc73404e6fe6955736122c83d5f6e.nq.gz
    ├── 658befefbae8bb4e746fb53c67e9ddcf6ee10035.nq.gz
    ├── 665db1d6eecae8b28fa9b46e6ff4cf3253b48356.nq.gz
    ├── 66adb5b58277ab18360c58ecb24732ff4359f8ff.nq.gz
    ├── 6759988b0f68e1b9853ef8b4de7ab8d57cb851a4.nq.gz
    ├── 68fb7cf8436f248984b4c17f255c8aec3af616d3.nq.gz
    ├── 6a19dbd2f0b6292a18ee62c79427b1558e341f49.nq.gz
    ├── 6bac95c9cebd1eeb891dec60963a149eb18a8a66.nq.gz
    ├── 6ded0c21d4b532b41deb48d3e0d3d1ac41f9c5cc.nq.gz
    ├── 6e35ebf75f364d87b7dcaf04277f283fb2a60fd2.nq.gz
    ├── 6e6ad21721f515bea651928b804a0bf76bae4683.nq.gz
    ├── 6f04eb7a16b86679d355f077d9dda42c1495967c.nq.gz
    ├── 70da0f09a4d67110a5ba876612460bada834d7a8.nq.gz
    ├── 71d74fccff327cda14bbf47034f0c14d100c4da6.nq.gz
    ├── 71e6e02400d7853e325a96555be995b63e2625fb.nq.gz
    ├── 73303fa8b19eb2cca69e699f90dcda8aff58765f.nq.gz
    ├── 73f054582abdc3ee98b86892c8c1995b0517b7be.nq.gz
    ├── 74f669b838fe697ee77ef6289da7d569d990dca0.nq.gz
    ├── 7679bd0e65cc411c7bd0e61b1d42da597c4dea37.nq.gz
    ├── 778d873b5205fa4ce4ce80d77fa5697f4503821d.nq.gz
    ├── 78942a9ea908a164cf23b6d292e16cfaee4fcfca.nq.gz
    ├── 793d765d686af3e280685a29f66d55df55f3d0c3.nq.gz
    ├── 79a25d4c7fcaf38aa980efee2a3e256b42bfb109.nq.gz
    ├── 79fa1b810a77c8869e9e29fca9151f5ece395b85.nq.gz
    ├── 7a6d7575321785dbdaae9af83296f9cc7161b250.nq.gz
    ├── 7a84bdd8b8ffd7d2a1a01581a093ede25367844d.nq.gz
    ├── 7ae0f7381d0ce8563de8a8517f03fe8d4fdf8d9e.nq.gz
    ├── 7b479b476fc511dc2ccde25618450f1e2b1d0772.nq.gz
    ├── 7bf7f53ab72743b739196c78788b3aa45062750f.nq.gz
    ├── 7c0f550ae0e3b8e50b345985adfd5d0c0ba26ef2.nq.gz
    ├── 7cf7c16b68b34047ca7fccbfb01537f032cd0f74.nq.gz
    ├── 8059157a7470ee80034b42477da890152ee1cd07.nq.gz
    ├── 8062f21518b4c257839bfa82a2eccf100b466170.nq.gz
    ├── 80e2d66eb06f03ce59dab8ebe7f96b4e7256ac5b.nq.gz
    ├── 8113d77dd06e8b730ef801659bed6103ac7b5548.nq.gz
    ├── 82a266f4015b651f7155b3b46fd1f8b4138a2ace.nq.gz
    ├── 82cd7c06956d7826c924e7fb8de3f3681100dd73.nq.gz
    ├── 8334ac5621348ff04c62843b15f5d7118284cb89.nq.gz
    ├── 84a2097254b3c6738c1ad5ab7239fe9dd1ed500f.nq.gz
    ├── 859cddf0ed5ce5edec8778547ee5be4c0a2696bf.nq.gz
    ├── 85db71d848bf4addb753dec1613e0e8a9a85c7ce.nq.gz
    ├── 865bbe8c0130fb30781abfd8088dfba2edb8b756.nq.gz
    ├── 897d22f8aafe04db8bf28b25672550fbb0de1dc4.nq.gz
    ├── 8a489dff4abd670790cb849ee2ffa421e4c19787.nq.gz
    ├── 8b9d553f2bf6cc6213377312e087d1673d06ed53.nq.gz
    ├── 8c65e14c38546c3edec4820b05e1d697e3612396.nq.gz
    ├── 8d2529e4887c2c5fef90347e8f6ce39cc98d269f.nq.gz
    ├── 8d8a58dad1204e034f8c5af29b82bbab10af5665.nq.gz
    ├── 8db2fcc499ec1ee371892edda21d9f2080e5fae9.nq.gz
    ├── 8ed0125f824e5c3f2766e8df1ccc8cd0ed670373.nq.gz
    └── 90d6157f11e7953ca103ad2c7a218f07269b892e.nq.gz

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

[badoo/Chatto](https://github.com/badoo/Chatto)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
