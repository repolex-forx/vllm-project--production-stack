# Repolex Knowledge Graph of vllm-project/production-stack

RDF knowledge graph data for [vllm-project/production-stack](https://github.com/vllm-project/production-stack), parsed by [repolex](https://repolex.ai).

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
rlex download vllm-project/production-stack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 405a2fa79992754d31f754c31b1eabb7183a540e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 405a2fa79992754d31f754c31b1eabb7183a540e
│           └── chunk-001.nq.gz
└── blob
    ├── 006cf6241b2a8d727629cde5d85e23788766528d.nq.gz
    ├── 01805b66056bb06f12020f09aea0e6a0f6c3b6f0.nq.gz
    ├── 0296da70e63a1b0a5f483eac01251aa4b5c952bc.nq.gz
    ├── 0375f0a0870e2b3bbd2552af81a5335bd6d5a0f3.nq.gz
    ├── 0433c28916230f022244b6fb294a0f5d5ca06944.nq.gz
    ├── 04a16fdcd3a1a02ee37740d34243587a00f4a4a9.nq.gz
    ├── 04a5141cc881f3fe9813424673e36590aa54040a.nq.gz
    ├── 04ddf43dc7ecf7fd2774a0619536634714c88389.nq.gz
    ├── 05433811e9610bd3dad855377b1c9f1b159e4b6c.nq.gz
    ├── 05ab1071f04b6a2ecc0d0172e4155a733fc052e4.nq.gz
    ├── 068e5e2321b51e99d63928d17340da6b3fc516ac.nq.gz
    ├── 071e40cf41430d99eb8bc955cc39584511b31856.nq.gz
    ├── 073a3ca254532f5ff81caed2a1e00d958a60f60d.nq.gz
    ├── 079192bd50d159d64b1e4e3e89b6ac0d48aa4685.nq.gz
    ├── 082e215ca14aa28216d78219e73c2bdbd1c5f13b.nq.gz
    ├── 08c44f1399c9b2692b6304928cd51428432993de.nq.gz
    ├── 092443619082b8386f8756fa560c6791fb0d139f.nq.gz
    ├── 09e174428bccb0186c2ce0f84532019f89b99eeb.nq.gz
    ├── 0abd5b98d91ec37bcdf7a84243fd5d0a0abdd6d6.nq.gz
    ├── 0b011ccd70f10bee9fffe604926f782d3ca4bed2.nq.gz
    ├── 0b8e6d7d74206f0687cf98bb41c37d094b2f44bc.nq.gz
    ├── 0c21a8a4caad55c900b15f110acafc2be4b78d3a.nq.gz
    ├── 0d7289dbd8dabff1bc3bab63337ed2754c2ab2c3.nq.gz
    ├── 0efbe62aee509b5f7a67f6929bf3c806d9b64126.nq.gz
    ├── 0f4263c6d9f89b7be76b2413a84d26b902c5465b.nq.gz
    ├── 0f6f102c95adfc8a88415a443c8a1994a44ce3bb.nq.gz
    ├── 1020766dfc87e98be757647156451aa63201d3a4.nq.gz
    ├── 102e1ab3c03e4ba02d0b9da56959499a181aebc8.nq.gz
    ├── 1052b81c8e8896f51fcef15d8bbc0f4301052aef.nq.gz
    ├── 10e4632c9d88838299e1a774e913d7c4fb16200b.nq.gz
    ├── 10ff2ca625eaf7ac00296e64950f611a3e2cd824.nq.gz
    ├── 112ae4a691eecdc4f5c7c079fb14f8b59bca8a5d.nq.gz
    ├── 124353fc9c4e6aa7c4399750270156b85fcdd645.nq.gz
    ├── 125744965f8182a5fa7da739da4e9dcef9aa9b78.nq.gz
    ├── 135226594ca807fff67653f390963784880d5b9d.nq.gz
    ├── 1424358ddeb1dadf3ed2e290267527f896eafbbd.nq.gz
    ├── 157243f9e8bea5c76b8d3b7057a1c8d3a2d33fb0.nq.gz
    ├── 15869bf351888dfebfc9090c8724b391a656c1ad.nq.gz
    ├── 17cedcecd8c2afbc21323a66bf1fd19b41f1a549.nq.gz
    ├── 186f249fde04d9fcae454ff9fc01f08e01919c60.nq.gz
    ├── 18c450708665fd52570ef4317e65b1964ee79257.nq.gz
    ├── 18e7732200c3a6fcb1f62a027eba40f306ad17dc.nq.gz
    ├── 18efd0578465154735085aa0775460dcce50c67f.nq.gz
    ├── 1956f34882e3a360eb8edfd04d5d9e3acde10c99.nq.gz
    ├── 198c83b50b77dfb41076adc471aa9b71b0d83ccd.nq.gz
    ├── 1a7ba85456f02e826eb9b2ed547e3fab5faf7024.nq.gz
    ├── 1b278cd67e2a0ac94ccf779099e12ac95350596a.nq.gz
    ├── 1b78cc1c93eb240ad272bfeb7afb10da7851fa1a.nq.gz
    ├── 1bd14b6a4a98e20e87b5fbb067c401dfeee0fedf.nq.gz
    ├── 1d3514a59108d8f91aa4ca1dc4a3b5d6e6f1a26c.nq.gz
    ├── 1d62938f55c8187d2d3b75748bdde83218e397bd.nq.gz
    ├── 1dfdeb15dad9fb36b5b9acf74a0d50665c932b42.nq.gz
    ├── 1e550a2651a54183be02a81aa7a041f98dc64b65.nq.gz
    ├── 1ead9972879c29e17160f1d3ead150482467b1e8.nq.gz
    ├── 1ff472f82f2c9d8db50ea3a49643d7769ecf3684.nq.gz
    ├── 216e0ae57873991d0f1d745ae00cb6291da74064.nq.gz
    ├── 2173d44a27a388c5d282836f3c7b13127e02cbe5.nq.gz
    ├── 218dff4a713c2fc38a1469524b89374839aea371.nq.gz
    ├── 2196c40577893ac3bc3fdaab7478fd61903bb992.nq.gz
    ├── 2259ef71bb86c6479d72ebfb30d625dfb4c3e1ee.nq.gz
    ├── 2291c7c6048a04c3001f94db2133de14806e8fd9.nq.gz
    ├── 2299d955b27047bf27ef25408587e7abeef80ff2.nq.gz
    ├── 22f898562dda570fca1e0d4386a5fc905e2f9c0f.nq.gz
    ├── 2304c864628a529eb2bef186dfb7df5d62ef031c.nq.gz
    ├── 2314086f5539c7813b37fe85d8776bac6250dc3f.nq.gz
    ├── 233ed6f9d7385d3dc01631ad5fe05fe4830e1732.nq.gz
    ├── 239aedae920e9201b2defdf14765b14e0edf90de.nq.gz
    ├── 24f91058a6d8149c3728aafd9196d0511c45c85b.nq.gz
    ├── 25304d68a2529ad3f1c5b64d5ee21d1b02c048d0.nq.gz
    ├── 25caaab2a2691ddb31c4e40e609c5842d0d7baaa.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26e6444a9769fe7e1698a319587a852cb6e6257e.nq.gz
    ├── 278ca26bdb2d926fe162210f7640cab5f525701c.nq.gz
    ├── 27cf228f29da2836f9fe4c6f0e5b073b2a447a4f.nq.gz
    ├── 284196bc2d2797b6157173fd9ff9f254d103a43b.nq.gz
    ├── 28aa01a06c17ae6f892e1887a6fd116180a5f55f.nq.gz
    ├── 2a32ef7b2f228edfcf706a3c694ffa03c5cf3a21.nq.gz
    ├── 2aa059d09205577effeea9cc875ca4f1b4e19322.nq.gz
    ├── 2aaef6536f430fdd9b50f352af5d2c157691f875.nq.gz
    ├── 2aca1f9d4f38eae67a7f5589a58b405f9b905ee0.nq.gz
    ├── 2b244dc57455ba268711fe0a45117015502ad5a6.nq.gz
    ├── 2b465583efa10b20dbdfa1e24542a8e1ec3ac40e.nq.gz
    ├── 2b633581f39a50cc6cbc13e5f1675ee5a510876a.nq.gz
    ├── 2bab7dc50de3e54fd59af3ad89281af60a6a4a46.nq.gz
    ├── 2bc0a48d5ddb14691b8104041ce81b723a4d0b47.nq.gz
    ├── 2be658d81e2cdf146d7847025725c37dce8c2dac.nq.gz
    ├── 2d8254feb0135fe6086cfe9facd81a43d151a9fa.nq.gz
    ├── 2d8674ecb32289230c6cac29ce5f57c82f3ef75d.nq.gz
    ├── 2d8a2ebec2524e4c8adfa36618919983c1fd4275.nq.gz
    ├── 2e62e41f3053ff6bbdbbaf9fb4b7e4f9d66b84bb.nq.gz
    ├── 2e89670ee6157813c6e93ab010b685aedc8a498e.nq.gz
    ├── 2eb426af2ba741bc23db93fe5912e8e6cd160124.nq.gz
    ├── 2eba9669950a1bd8cf32442440fca0efcb7443de.nq.gz
    ├── 2efa769c2e73828eca88cc31cb0f295815d40d17.nq.gz
    ├── 2f05575688b2e827cb6b9eb0953fddfd87f6ed82.nq.gz
    ├── 301dd7df3a26bf380a7dc3fd2e579958af92245c.nq.gz
    ├── 304df0f8757b4a081ea8e743e486fa178b10c231.nq.gz
    ├── 3067fba13094b55c41177e6152170e5caedfb1ad.nq.gz
    ├── 31e49eaef8851039630b5dc6e4b9366431818ada.nq.gz
    ├── 32d2e4ec6b0645707d1fc19f8f010e8419e0d6be.nq.gz
    ├── 330955904fcf01c58605cf56e40baea534016ec6.nq.gz
    ├── 330b8546262246d2690694ac0c801c5348e0b317.nq.gz
    ├── 3447b0082cff57dcc3637837da56024c6db6b7f5.nq.gz
    ├── 3465d6858a829e6f945e4000be3da55b94f61150.nq.gz
    ├── 34d0414022fa723995c6cdb576fef944ae763d94.nq.gz
    ├── 34ed668784cd2e2059b8c73c62eee3545927fb3e.nq.gz
    ├── 361136bd9155b5f0481abcc3ac7595a60666107b.nq.gz
    ├── 366393d27c0f7423a035041efff3aadeab63da68.nq.gz
    ├── 37a3e24145a46c3c065d85713adb0c995fe2d29e.nq.gz
    ├── 386c7bf54b3083a52fc18bf00fa3144355997dbd.nq.gz
    ├── 38ce7891cdc9689197a65013e505348d4e6ad2bd.nq.gz
    ├── 39456216181b9dcd1ba38fd63b0cd7a22d46746f.nq.gz
    ├── 394fade5a012c37b3e13b7b0c9d563fc3339ab36.nq.gz
    ├── 39ed5b79b1f2b16039f3dd19048c9e937b1c93cf.nq.gz
    ├── 3a649fafbeb048a93821a6c7c422da50eeada75e.nq.gz
    ├── 3a8f97c3c56b4f145a52d9d2cf0856df0c99ec1e.nq.gz
    ├── 3ba84ee82fa84ddc232178e2b66c72b763b7e48d.nq.gz
    ├── 3c5bbb31816c4d1d12307fafc4cc9a99bd3e81f4.nq.gz
    ├── 3dba2957578978745950d7759416a3c0696991ac.nq.gz
    ├── 3e9480e7300939e9dbfae289de3ead204cdf5653.nq.gz
    ├── 3ecb2912b17692634aee9c422722690db700922b.nq.gz
    ├── 3f9aae5ea5aa6195aaf04ffc0564b7f227229023.nq.gz
    ├── 401d981895516efde4f41feefb8a873893432f47.nq.gz
    ├── 40a5e2285fd952e090cdcc5199482d9befebfe98.nq.gz
    ├── 40ec92693b15bf2689f2211a9559cf205a1eeb50.nq.gz
    ├── 411e15d1969494e798954f7c770f1e66bbeafad7.nq.gz
    ├── 41c47083678dd369018dc3a73b9848a916b581e7.nq.gz
    ├── 41e247fa6e50720ed475e4f51025b2b42d84be86.nq.gz
    ├── 4221fb893eae7f843042f670010e55b2da9c86d8.nq.gz
    ├── 43aa99f0b04506b9e0b5768287542df85a701dd3.nq.gz
    ├── 4451ad09d92f04733771630003c0d0722e98c99a.nq.gz
    ├── 44f62f498b01c5814a3331ec34f24a741e8a39e2.nq.gz
    ├── 458549c261d659df5c9f4fdf1ecb92bc2428e563.nq.gz
    ├── 458e542cbddd0a55c7bea0537c851375616395e1.nq.gz
    ├── 45ccb9d25b49956b8fcfa106496111963b3cc2fa.nq.gz
    ├── 466d452f68cebf5e6c8ef5c9fb3a9c941214e52d.nq.gz
    ├── 4671de8fb1eda144bf180fadb89b964243a72d47.nq.gz
    ├── 467c07e46916ca3f4046f0b944752171601c324e.nq.gz
    ├── 487e1867d555f19acbdc0929c1030cabc64676e6.nq.gz
    ├── 48cf1b7bb6ccf0a8ac8b5df46d6593285bbf2f79.nq.gz
    ├── 49ba709a946d614c683ec0e63aa4b289d0b33163.nq.gz
    ├── 4a45f49fb15a7a1ef21001dc15bb9c7899ae2f76.nq.gz
    ├── 4a594eceb23bac9224b3f8f0f776a9a219748c54.nq.gz
    ├── 4a83bc29c95230ea3b7a08d1847efe97be7107cf.nq.gz
    ├── 4b98b39afe5291e347d85238b30456617eaf5fc1.nq.gz
    ├── 4c72d4146bfeddc5cac717687dd1a2fde9856a6c.nq.gz
    ├── 4cef51a059ee6444bac1a0e304e50d0c4b258acc.nq.gz
    ├── 4e0492287293cc8ed0a9304ab2737e74f0b9cb93.nq.gz
    ├── 4e43a9bec0b38519c9d8162140553d40cad9aede.nq.gz
    ├── 4ea148aed1a0b108b2451479525a49ce4c7f5ae0.nq.gz
    ├── 4fb38ef5f799929ab2b162fecb0e8188c91bd33e.nq.gz
    ├── 4fcb1d4b928920900183cd6025fc952b3a0c83d3.nq.gz
    ├── 5008260616e3f3222fb9401a0992d5ee12a938dc.nq.gz
    ├── 5008d0db165ae5f8ba287f00da98dcbf9d87f7d3.nq.gz
    ├── 501bedf79fd26c8fa4f1c6774b7f969e564a6c43.nq.gz
    ├── 51a45b437b6ea2a56cb9451191428eaf73c2655e.nq.gz
    ├── 51a75db47a5b3f7f585a985ae15f64c5dd912394.nq.gz
    ├── 52b2825c1b183d66adbda09ecd8aa652306ab57f.nq.gz
    ├── 52fc696295ee1e34398541c1a3aa15932a3b580d.nq.gz
    ├── 5353acd3e2378108939ba46b946ade15a49d6687.nq.gz
    ├── 54915f10ce0c1abde05f12a9fcd7213734ba8751.nq.gz
    ├── 549e29df9d3b6b1e97b21cf05a0ded8ba39a4721.nq.gz
    ├── 54b5693c51239cbac1cd82eb66e7850794606141.nq.gz
    ├── 5627000e73d6d61309aaf17207d677640cef1d00.nq.gz
    ├── 56ef0d12e394121a22b910aeaae44f058248f98d.nq.gz
    ├── 57291269ac5dd03ca42469d1359641adb1b73ec3.nq.gz
    ├── 59fe6f9136e4ea6e9a522e057445029267c564b9.nq.gz
    ├── 5a02f86a1fe500a55bc497c4ca73eaf2a5e9ac21.nq.gz
    ├── 5a7a5f48d742efa7ac25edf2c96dbfc109bfcb7a.nq.gz
    ├── 5b6003d8b8bbad0b6d715ba32e795560b65e6cd1.nq.gz
    ├── 5ba5fc2891291083e87dc363d44a9a097fe5f6e7.nq.gz
    ├── 5bf84ce0d53c9951afc173fa0053d4ee0f42410a.nq.gz
    ├── 5c2a024794eafdcd197ee6a6a6a91f939191f496.nq.gz
    ├── 5c53b70db78eb804b9c94bf8268c25610f1f7872.nq.gz
    ├── 5cbcdfe09d81d27e4c65bf58bec497386748d7a0.nq.gz
    ├── 5d21d4280a6f873e4e7cc48b981f5fdb1b2a05e3.nq.gz
    ├── 5dcbe4bf2ad4ec891cda813a02882888bb50c609.nq.gz
    ├── 5dee72f1aedb8bd2dffd797ebe294c907f4790d6.nq.gz
    ├── 5ee0f4caac22234d0233ac5fb1eb25e647289add.nq.gz
    ├── 5fbaefc32e75753b8c7b7fe0575f8d515a456b58.nq.gz
    ├── 6007bb5fc521a33236a549fb406a7c6e91679509.nq.gz
    ├── 61501de1f3d10307be1cf6beccc479fd78fa5441.nq.gz
    ├── 61b682b5aac0c1fe7e026dd26d3b42bb3a92cd61.nq.gz
    ├── 61d092d49597f120840f2dffe6b8312e5530ea80.nq.gz
    ├── 627810cc09854427133b147757ce3adce301b20a.nq.gz
    ├── 62e305f1ed919d1bc6f6392f0d8b5258fa5969d7.nq.gz
    ├── 63647067af44648cf32fa62629728d3abab0679a.nq.gz
    ├── 63720fbab3cd67f94c0bff58c6c7dd26fb1b1f90.nq.gz
    ├── 63c2b3015699a3c949d7d9352dc96f5558b732c1.nq.gz
    ├── 64131d39233a161b9acfa5c75b69a853796cb10a.nq.gz
    ├── 64e9594a9efec227079a4648d2f386c47c5e15af.nq.gz
    ├── 653f76f8b8c7b4edf903e92e1ff1ac18458e87aa.nq.gz
    ├── 65e0a1ea9d2a4d653d1896d68f7c0f0c0a7b8590.nq.gz
    ├── 681a04d0dbcf2f3db0b7ddc861ceee6f12fd2d11.nq.gz
    ├── 68db120c6ae797fc5ef15496c2d45759bf6a0426.nq.gz
    ├── 6a3bd949992d61bf0ee10488e7836c52e4e11979.nq.gz
    ├── 6a3ee01e7307766886bc30f38caa8cbd3eca0940.nq.gz
    └── 6b8958fdc86780e4ded71611d00597f5348c68fd.nq.gz

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

[vllm-project/production-stack](https://github.com/vllm-project/production-stack)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
