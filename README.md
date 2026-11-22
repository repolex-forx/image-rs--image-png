# Repolex Knowledge Graph of image-rs/image-png

RDF knowledge graph data for [image-rs/image-png](https://github.com/image-rs/image-png), parsed by [repolex](https://repolex.ai).

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
rlex download image-rs/image-png
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6ddb6882a2bb0ce875f65eb83a2adfd3f64bf8bd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6ddb6882a2bb0ce875f65eb83a2adfd3f64bf8bd.nq.gz
│   └── repolex
│       └── 6ddb6882a2bb0ce875f65eb83a2adfd3f64bf8bd
│           └── chunk-001.nq.gz
└── blob
    ├── 0009d990024507649b612856c383d3a78de64083.nq.gz
    ├── 0090537de63fdf6bb4f2104de6b65cb68d005ef5.nq.gz
    ├── 00a14e1477c63f216b608f8d7a5d94f05a64419b.nq.gz
    ├── 00a7cea6c2d3c36627718a502eb14c812b0b7c46.nq.gz
    ├── 00caddbc3b07846d5da8b9b3d8d6f62c6af6d414.nq.gz
    ├── 00ccc33613c3109947f79584c49cc2a8315b778f.nq.gz
    ├── 00e79f0bac8ed28384444b3929473f00d6457d59.nq.gz
    ├── 013b120f60ea22dd2ab6be11d1fb058e6d9fa933.nq.gz
    ├── 01e10109af29850f43d4b18fba2c3a420a0df77d.nq.gz
    ├── 01eb91ad1850b66c7eaa11fcdf2717f54bd2854e.nq.gz
    ├── 021520ce0c228a9ec06c449813416882cf861904.nq.gz
    ├── 0218e4d9cc034f5b92b842a1723afa1aac666981.nq.gz
    ├── 0241acd6a83826606a08768eb46465b73336955c.nq.gz
    ├── 02dfc0746d2ad9ac5c96f38e089a32ae751ba7ff.nq.gz
    ├── 02ffd32cb0880fea6951338843690bc51d3d0726.nq.gz
    ├── 03575dcfeafaa4c1a77cc7b7e5e2ba444df2aa72.nq.gz
    ├── 035f7533f2a8c265484c85576b69491882f4b336.nq.gz
    ├── 0364e61d6afc50c629eab9fa6271dfe240289197.nq.gz
    ├── 03cd89431505313e85d28df3f779a19bf5ff7fe9.nq.gz
    ├── 03f505a64b57293034b16cc1030c61e9f3a810fd.nq.gz
    ├── 03f5b27bfeb030feabc3707176de67b8fb9cefea.nq.gz
    ├── 0417b33d500a39d6d4cc5336cb885bdabc28b25c.nq.gz
    ├── 04617d2c027f44dca7f83c094af9e9f807871f07.nq.gz
    ├── 04b4ad5c82f89bc6df11d3658d89a70b84a6e293.nq.gz
    ├── 04cb53adf581e4e52794ea0ad618c76cdc0d8ef0.nq.gz
    ├── 04fee93eae400e745534756b48f5420cbe4a1d91.nq.gz
    ├── 054d50be790dfd06797cc9b243bd445809ae7239.nq.gz
    ├── 0588724d214f82d3268de599298e45f0ff1dc736.nq.gz
    ├── 05893d884ed7e8429d01fbc1da2497b14ee62311.nq.gz
    ├── 05adf7aa448d6245f5ae1db5138b9bb675eb2135.nq.gz
    ├── 05d5cbe670cc0e13feb3ae1db5771a25a4258c33.nq.gz
    ├── 05f9a12b8abb43df6f91fa6db2a226871ba98852.nq.gz
    ├── 066141e69a169cc95dca580dfa99fb3a6ea03ec8.nq.gz
    ├── 0664a194310fff265fd9aebd95bd8908934ff6b4.nq.gz
    ├── 06dd0b2d97ad15da42ab1889f9ee7c9dfe882838.nq.gz
    ├── 07428b87324956a53419e693b9a7c35c5442b2de.nq.gz
    ├── 074f32f86e24a33936bd9aaea03150fe8be0b919.nq.gz
    ├── 076c32cc082066dc870e1282b97c15ec22192407.nq.gz
    ├── 076e3dcc1a8cd939d50ecae6506ee0fcbcebd6e6.nq.gz
    ├── 079c624103292a8265b690509058deea966e9712.nq.gz
    ├── 07d316659c52ca8aed6a2df67bb6de7dbcd7ee9c.nq.gz
    ├── 082c85f9e5038675af2dedc35365084e7f0c3328.nq.gz
    ├── 08357f5fbacd397a4278d3d3ee3d1029ca9ed858.nq.gz
    ├── 0841910b72779aa7571cce45e56447eeb3de4520.nq.gz
    ├── 0962d1aacd7a081c05e1002ca4ae0fe77d1f0cf5.nq.gz
    ├── 0964f6d5b89bbeb3bef93b836c43ae7a05172131.nq.gz
    ├── 0970cf18bb1d8d83640a94a16caa148d69b5b8c8.nq.gz
    ├── 0a3d8a1758afc3e301ee0cd1193767f1ffc137a4.nq.gz
    ├── 0a66aaf37a27b24d55346e7a0424874b5c631e75.nq.gz
    ├── 0abaf1c304571ac134d61fdcbd43c8e8ec5e2d66.nq.gz
    ├── 0ad505eed69db3a610ba63a9231246056905d383.nq.gz
    ├── 0b3d5e48dcc3dc4c6b1d12b825f6735bcca9d777.nq.gz
    ├── 0b521c1d56ac6ba14d82547eea5c87dae391cfba.nq.gz
    ├── 0b99e0880666a5d6f02901ddd976a05cb63da642.nq.gz
    ├── 0be42486ec8833245642acc88ccbcfb14cc76a03.nq.gz
    ├── 0bf3687863d8a1f53bef0aa24b841b21b0e04d9e.nq.gz
    ├── 0bfae8e45678282b23bed2760c0dbbd736be9df8.nq.gz
    ├── 0c752115dd7ef485240eb6af0a3d997359b4666b.nq.gz
    ├── 0c7a6b380e9a2e60c887a260d43a41553260fc74.nq.gz
    ├── 0c7d214c1e8be7f29b4f57e650aeaf4baa9c0959.nq.gz
    ├── 0c91ecd9c787e0bcdaa6ad070642fa0b9504a240.nq.gz
    ├── 0cc61174eaad29dfb463b439b5d2d34922523ff2.nq.gz
    ├── 0cd8200ed27408b75a99f1fdbfaf13f6bbbbdf52.nq.gz
    ├── 0cebf0276cb6bc417bb5b73497c54a9a9d05353b.nq.gz
    ├── 0d2294da8fd39af34b3ce74e1052f01f45797862.nq.gz
    ├── 0d602803acdf7b26b32fbbbfa711b404083c5e30.nq.gz
    ├── 0ddad07e5f5de86a61bf43d8b89e138d7f1ea8ad.nq.gz
    ├── 0df5d3e922f9df328199262c73929fdf54fe72fa.nq.gz
    ├── 0df695c406631659c76683538d1796b61a0bd6e9.nq.gz
    ├── 0e3af48c326f19d631163e6709488bc80481d146.nq.gz
    ├── 0e710c2c397e371e4feab66add6a9f9763ce0c27.nq.gz
    ├── 0ecb90c709d42474fdfcdb6f5bfaa3c2ec7c3a01.nq.gz
    ├── 0ede3574db0fd51fa9266fb1cb91df3888dc8dbf.nq.gz
    ├── 0f025d889939812a072a95a3a282994dc4b2d86d.nq.gz
    ├── 0f13b127b70e6b51fadb4f98f552c3548f69e4b0.nq.gz
    ├── 0f1c3ef2a16fd4a73418665f470f3ca10a7f9054.nq.gz
    ├── 0fbf9e827b467d65dc252db937d6590478bbf88e.nq.gz
    ├── 0fd7e9797ac6e53bdd2067dca8cb6bbfab4b0644.nq.gz
    ├── 109c790bbb5df30d4b260d1665a20897d603dad1.nq.gz
    ├── 10ece0dff2a96b84bec24614e45f75ca58a3d8ba.nq.gz
    ├── 10ed02a67df6a5edb450aafb97e500d8ad1f202a.nq.gz
    ├── 11720d719a4ab2aa40e83b53d701ea7502fee50a.nq.gz
    ├── 117246e6ad808101ac7b24628ac2c4707ef942d3.nq.gz
    ├── 1181fd343d513086c5cb0795b7e69bd196d0d015.nq.gz
    ├── 11caf1444a3e4da7069a829e3464ca700b947166.nq.gz
    ├── 11d96c442bbb3ad011761a0aa77caa9e546a2712.nq.gz
    ├── 120970bc2c85685bce111954118fb490ee0f819a.nq.gz
    ├── 1233ed048e504292bef13d0a96d291914d12c858.nq.gz
    ├── 1256d274a0259e3527fd0961c238480c6a6090ba.nq.gz
    ├── 1274308a9dcbc1660ce02f3eb3b027bb56935cf5.nq.gz
    ├── 1281e7ff481635d54f68db2dea445dfa92fca1d2.nq.gz
    ├── 12989a1ad85d4b484ae0b67bedbfcf15b1d84b2d.nq.gz
    ├── 1299b86492c59b7b6ad69eaed1e84a0b901248cd.nq.gz
    ├── 12fc05f1e0ddc253dae2181c7546db26d9b8cbd6.nq.gz
    ├── 131cf07ddb5e335da5d887fe8f5cee396490f27d.nq.gz
    ├── 13c3efbad18db7b13ef0567e831c32b53324673c.nq.gz
    ├── 13fc334496c5e4d7459226b057fc81db8071b160.nq.gz
    ├── 13fd85ba193369dbd84a0dc07f73d3340485fa6a.nq.gz
    ├── 140a69a0707b42c5bbe91d00a76eafb06fe6236a.nq.gz
    ├── 1429466bb5524ffe33b7cc1ccc27beaa3fbd8462.nq.gz
    ├── 14732e8f0177f2821ef3cfc2a0f45dd648227e5a.nq.gz
    ├── 1480d58afd406d20a9ab2f874c2de44ee37269a8.nq.gz
    ├── 14d64c583db347908d4e107b49bdaf88e3857b8d.nq.gz
    ├── 15202dd13594f507daab655069688d58d9085ed5.nq.gz
    ├── 159a0a4c1491c9174bed5c19edb4252788d31d53.nq.gz
    ├── 15f77ff62b68aab8266622cbaa2c188201605217.nq.gz
    ├── 16173eb26a25a7fdcdc56a5d7b5dce5fc39d0ad4.nq.gz
    ├── 1636b55e4dd3404a4f409d1f442ccfbbc3afb0d5.nq.gz
    ├── 165087d65ec12e2d29e2a6f1843f9cc9c6bed56f.nq.gz
    ├── 1659d22083401bd3004c0e699b95d0e9da2eac8b.nq.gz
    ├── 166c877c76a66c40df782c89b6b04cab18ad0f91.nq.gz
    ├── 169a975a0271b85f0579d8053f004975bec3d144.nq.gz
    ├── 16e26431cbee6b1e735ad9b8d24a8ced72c2a976.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 17601e46cb313d9182aadd31c4e70529af9b0a23.nq.gz
    ├── 176749f92c451cc430d26ec5bcf57c5cc81f84be.nq.gz
    ├── 176d40883b4ab41ac46d88cf3db1b969cf0f4903.nq.gz
    ├── 177bbbab8704d7e322eff1f6173e3ba8be6a331f.nq.gz
    ├── 177e019c2b1aac05d528f0156f209f095e0001fd.nq.gz
    ├── 17833c7c15dbba04894f5a0297824396b02e6eb4.nq.gz
    ├── 179d2fabedfda217a5d21b01c9e8fc9747598d05.nq.gz
    ├── 17cd12dfc9169036898b84dfcd8d7c547c8dfde0.nq.gz
    ├── 17d920963326004e274ef61e05f468c31a305254.nq.gz
    ├── 17e10ebe1d78e97e00054cc73f9b8cad19e80dcd.nq.gz
    ├── 17fdde4eaf24ebbd4db18518705b8c0ac37980aa.nq.gz
    ├── 1817c5144ffa1644cabc5fd86b73bb93ef0de064.nq.gz
    ├── 182cac8456bc99c6a88314cfaa8ffd279e8aec84.nq.gz
    ├── 18312cc14fc381df0376273f97e181146a96332c.nq.gz
    ├── 18ac12edab78131cf5c93f8cca595834444a8306.nq.gz
    ├── 18aff4907451ba0db84177228de5d044e1d66473.nq.gz
    ├── 18b79db32518775433b63f11d849f7b90f0755a6.nq.gz
    ├── 18c387482fc5c2c7d7ac7bfe50072f95229787db.nq.gz
    ├── 18e66ea0c4b20ba136b030ff6afe0a36af11fe2d.nq.gz
    ├── 18e87a85f5b275cb19b0202a98322d558531f151.nq.gz
    ├── 18ff3d00f711381c5b1a5a723940df0d3792f46b.nq.gz
    ├── 1915f207eb06188cb738de309e1aca554329fcc3.nq.gz
    ├── 1921a51b27fc87bf071453a6fc8a4ff102900c5e.nq.gz
    ├── 1931ee49b0640c2d6338616d7671e357adc1c389.nq.gz
    ├── 195c4104a5cca6f7849fccd345c0f123ca953be0.nq.gz
    ├── 1979c5936f1cc3be084d6d8f27c30028d57c0d2f.nq.gz
    ├── 19c5d1fb020f845f260be78d8afb130474f490e6.nq.gz
    ├── 1a2c20db5fc26758328657e40488c8981ad976b9.nq.gz
    ├── 1a79dc6f0cdf2b65f0ef11e6cf0b3f8916bda238.nq.gz
    ├── 1a81abef826f52b95708677c38c4b8e812e2f462.nq.gz
    ├── 1a8782c9b050d2b6a9537f14af726922fcb6ecd8.nq.gz
    ├── 1aa7fbd418472ae6239ac1ff25d7a51d722e0fe2.nq.gz
    ├── 1b2806718fe1278c2bf9b131c814a275426a8e3f.nq.gz
    ├── 1b35084a369ee5d40908a70e01ca47fccb144ce4.nq.gz
    ├── 1b6a6be2ca571956ce45bae5470c03cd2266fd89.nq.gz
    ├── 1b71f1adf60d9c915e6e643d63689a3dde9e71a7.nq.gz
    ├── 1b91829d0b1e78fe3af5def48af7b9004a129d77.nq.gz
    ├── 1ba2b36a7c0ba5cfe61e7b41fdfe01d7eac88a2f.nq.gz
    ├── 1be479f499f56f7513b36a3b5ce1b5763d5b11d4.nq.gz
    ├── 1c0b7ab996960b7b7146dfc7a5ad2a881d32b9fc.nq.gz
    ├── 1c47c7a9e3c31b34d5fbc38aace1f50556c7bd09.nq.gz
    ├── 1c570edbdd2cc45156c6df5e34dbe3bc993964d7.nq.gz
    ├── 1c7c571813b11275f000d8a57024c0be11b994c1.nq.gz
    ├── 1c7d81861d7766975394928528e4a4168e0b5c49.nq.gz
    ├── 1d031beac32dcb10fee05af643e1506c48007d60.nq.gz
    ├── 1d22174ea2ea9681eaa76ff38d5f06dd45a97350.nq.gz
    ├── 1d31c741a10bdd4851ff51d54ea1f044441559f7.nq.gz
    ├── 1d3c23759c6dbd08b1202ca7cdb3e91b78c77f8e.nq.gz
    ├── 1d55682516d43ae7be8a48a061c4ae4d34b7a957.nq.gz
    ├── 1d722423aa5157fe2b029af4e2bb07f478ebe8bb.nq.gz
    ├── 1d8d7ae634c7c5e4cce4a4cfb5e66a236b2633e0.nq.gz
    ├── 1d9608d6436f89fde335e53fd5ee1dffa725b2f5.nq.gz
    ├── 1da4cbd0bc1c18603859080786a76e5a36c595d6.nq.gz
    ├── 1da9a670201e3890627602d3afc5e16e36023dd8.nq.gz
    ├── 1dad5b3b6559fa2512cdeb4696c6f6b2990f6e73.nq.gz
    ├── 1e028214dad8eddd5dd368eb121652b13d19afac.nq.gz
    ├── 1e40ffc9af8fbeda4b4e35073c12e8df7198dfd9.nq.gz
    ├── 1e63190545bd115e2ff4207b8e456ef836e177c2.nq.gz
    ├── 1e637ac38eb95bfe2abbe428a475efd623923893.nq.gz
    ├── 1e847e50c9a58c49dc3cc35278f3fc1d0c3d8e65.nq.gz
    ├── 1e997d78eff7a5c001fb0afd406d4ab354805034.nq.gz
    ├── 1ea0141fb80743d3bafd8b477017bc61743a7b3e.nq.gz
    ├── 1ea193e39924fef3e0757500231209420847d1e0.nq.gz
    ├── 1ea29a9a01fa9eb85fe2dc918ae8550646f4cf6d.nq.gz
    ├── 1f02adf3ab44e72564f9cf259e11129f17c488ab.nq.gz
    ├── 1f091efb052662c512d7303bf6e89225a19fc97e.nq.gz
    ├── 1f7c432ca84e31c5c76352c681132bf9f0c504e7.nq.gz
    ├── 1f7e6cb86f8dfac4fbc5425399ce6881879f48ef.nq.gz
    ├── 1f85d41aff53cc81f0bc7ed4020392208fefea69.nq.gz
    ├── 1fb364dace5d523cdfcec9724b204f39994714f4.nq.gz
    ├── 1fcb1529f8e5e43037c4710ce09da0becd28823a.nq.gz
    ├── 1fcd52b411bf2d60a05f760c2eea9afbb08d1642.nq.gz
    ├── 1feaa751926dce09eb76435b518268e800d40bde.nq.gz
    ├── 200f533f936c4ed342b856e2f1931713e63c635f.nq.gz
    ├── 202839461b9d1d5c7159b1ed540adb5feccf2063.nq.gz
    ├── 202bee6c85c733b4d7677f562b46594049f853ea.nq.gz
    ├── 205460d8287a90ab9c9b7372354d8b7a8b5317da.nq.gz
    ├── 206aacc106d506798082e135e2e2c464ed803f96.nq.gz
    ├── 2098cfdf361b358ac382bea61a1d3cf8a66bdb65.nq.gz
    ├── 20c720617e089f6854b313e712fc13354ecc707b.nq.gz
    ├── 20ca0205eefc03907c280801ebb5df9a641151df.nq.gz
    ├── 20f93875475eb5f1b2a1989c7a78e4bfffb3a6d9.nq.gz
    └── 21100f855a19e0a4cd3ba6dd8126ead140d2db28.nq.gz

8 directories, 200 files
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

[image-rs/image-png](https://github.com/image-rs/image-png)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
