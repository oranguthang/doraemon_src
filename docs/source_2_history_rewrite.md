# Source 2.0 Draft-History Rewrite

The candidate rewrites unpublished Source 2.0 drafts from local `main` without changing `main` or published references. The original draft tip was `0ebca6543663cbd3f45992ea56805974aa8c6e85`; the first tree-equivalent candidate tip was `1d9c35e807942351af1de8d1d7b528f1a67cb0cd`. A direct Git tree comparison between those tips passed before this provenance record was added.

Each candidate commit groups retained files by their final owner. Its author and committer dates use the latest source timestamp represented by that group. Equal timestamps occur where one draft commit was split across several owners; this preserves the original second-level timestamp while keeping both date sequences in parent order. Empty or fully superseded drafts have no candidate commit.

## Candidate schedule

| Candidate | Scope | Author date | Commit date |
| --- | --- | --- | --- |
| `a1b9cc3` | Define audio request priorities | `2026-09-07T04:33:08+03:00` | `2026-09-07T04:33:08+03:00` |
| `8f770d1` | Pin the supported build toolchain | `2026-09-07T05:39:10+03:00` | `2026-09-07T05:39:10+03:00` |
| `d2d87b2` | Group audio evidence around the driver | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `cc65159` | Compose every Studio into one image | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `57ed8fb` | Collect shared reconstruction validators | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `324bd4a` | Keep generated content outside Git | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `577199e` | Exercise both cartridges through runtime scenarios | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `c16d5e1` | Route project tools through one launcher | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `dee6169` | Complete the Python package boundaries | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `0f9d786` | Give World 1 checks a dedicated package | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `3aba564` | Give World 2 checks a dedicated package | `2026-09-08T21:26:12+03:00` | `2026-09-08T21:26:12+03:00` |
| `5185ec6` | Give every Studio shared workspace services | `2026-09-08T22:00:00+03:00` | `2026-09-08T22:00:00+03:00` |
| `3fc5135` | Guard the public project interface | `2026-09-08T22:14:24+03:00` | `2026-09-08T22:14:24+03:00` |
| `f6a226e` | File debugger evidence under its owner | `2026-09-08T22:18:46+03:00` | `2026-09-08T22:18:46+03:00` |
| `21a5c2e` | Describe both official cartridge profiles | `2026-09-08T22:18:46+03:00` | `2026-09-08T22:18:46+03:00` |
| `dc5238d` | Make cartridge graphics directly editable | `2026-09-08T22:22:29+03:00` | `2026-09-08T22:22:29+03:00` |
| `99d70c6` | Put gameplay objects on editable maps | `2026-09-08T22:57:06+03:00` | `2026-09-08T22:57:06+03:00` |
| `9f29538` | Seat audio manifests beside Sound Studio | `2026-09-08T23:04:10+03:00` | `2026-09-08T23:04:10+03:00` |
| `14041e7` | Document the complete Studio workflow | `2026-09-08T23:04:10+03:00` | `2026-09-08T23:04:10+03:00` |
| `5400794` | Bring native music into Sound Studio | `2026-09-08T23:04:10+03:00` | `2026-09-08T23:04:10+03:00` |
| `1875421` | Expose shell text through a fixed-size editor | `2026-09-08T23:09:40+03:00` | `2026-09-08T23:09:40+03:00` |
| `9e918d8` | File shell text under its editor owner | `2026-09-08T23:09:40+03:00` | `2026-09-08T23:09:40+03:00` |
| `924d383` | Centralize authoring profiles and world data | `2026-09-08T23:12:10+03:00` | `2026-09-08T23:12:10+03:00` |
| `cb02ed8` | Separate build orchestration from validation | `2026-09-08T23:29:59+03:00` | `2026-09-08T23:29:59+03:00` |
| `b131952` | Share source across cartridge revisions | `2026-09-08T23:29:59+03:00` | `2026-09-08T23:29:59+03:00` |
| `01584b8` | Isolate reproducible analysis workflows | `2026-09-08T23:29:59+03:00` | `2026-09-08T23:29:59+03:00` |
| `4403eb2` | Gather World 1 authoring records | `2026-09-08T23:35:05+03:00` | `2026-09-08T23:35:05+03:00` |
| `e7ad983` | Explain the editable World 1 systems | `2026-09-08T23:35:05+03:00` | `2026-09-08T23:35:05+03:00` |
| `d34902a` | Collect World 1 runtime evidence | `2026-09-08T23:35:05+03:00` | `2026-09-08T23:35:05+03:00` |
| `58b0bfb` | Group the cave editing formats | `2026-09-08T23:39:05+03:00` | `2026-09-08T23:39:05+03:00` |
| `19c8623` | Collect World 2 runtime evidence | `2026-09-08T23:39:05+03:00` | `2026-09-08T23:39:05+03:00` |
| `f9766bb` | Give underwater authoring a clear home | `2026-09-08T23:43:23+03:00` | `2026-09-08T23:43:23+03:00` |
| `e9137fe` | Explain underwater rooms and entities | `2026-09-08T23:43:23+03:00` | `2026-09-08T23:43:23+03:00` |
| `666d187` | Collect World 3 runtime evidence | `2026-09-08T23:43:23+03:00` | `2026-09-08T23:43:23+03:00` |
| `7cf9545` | Collect cross-bank runtime evidence | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `1e0fd4c` | Refresh authoring and runtime coverage | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `0c97786` | Publish a modular Make interface | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `854ec0d` | Focus the README on supported workflows | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `bb84c34` | Unify release evidence checks | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `987a47c` | Consolidate the canonical source map | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `2c53848` | Align technical documentation with the new layout | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `80cdf79` | Explain cave routes and shooter data | `2026-09-08T23:47:53+03:00` | `2026-09-08T23:47:53+03:00` |
| `807b00d` | Give World 3 checks a dedicated package | `2026-09-08T23:57:59+03:00` | `2026-09-08T23:57:59+03:00` |
| `4a49e10` | Build a lossless visual level workflow | `2026-09-09T00:06:49+03:00` | `2026-09-09T00:06:49+03:00` |
| `1d9c35e` | Keep release metadata project-owned | `2026-09-09T01:47:01+03:00` | `2026-09-09T01:47:01+03:00` |

## Old-to-new map

The table assigns each retained draft to the candidate owner sharing the largest number of changed paths. Cross-cutting drafts can also contribute to other owner commits; the primary attribution keeps the review map one-to-one while the tree comparison proves the complete result.

| Candidate | Scope | Primary source drafts | Reason |
| --- | --- | --- | --- |
| `a1b9cc3` | Define audio request priorities | `772a401` | Regrouped by final file ownership and responsibility. |
| `8f770d1` | Pin the supported build toolchain | `2713a53` | Regrouped by final file ownership and responsibility. |
| `d2d87b2` | Group audio evidence around the driver | `f10c742` | Regrouped by final file ownership and responsibility. |
| `cc65159` | Compose every Studio into one image | `962ba1f` | Regrouped by final file ownership and responsibility. |
| `57ed8fb` | Collect shared reconstruction validators | `6f57da9` | Regrouped by final file ownership and responsibility. |
| `324bd4a` | Keep generated content outside Git | `4d1f1b8` | Regrouped by final file ownership and responsibility. |
| `577199e` | Exercise both cartridges through runtime scenarios | `194728d` | Regrouped by final file ownership and responsibility. |
| `c16d5e1` | Route project tools through one launcher | `f10c742` | Split from a cross-cutting draft and regrouped under this final owner. |
| `dee6169` | Complete the Python package boundaries | `6f57da9` | Split from a cross-cutting draft and regrouped under this final owner. |
| `0f9d786` | Give World 1 checks a dedicated package | `f10c742` | Split from a cross-cutting draft and regrouped under this final owner. |
| `3aba564` | Give World 2 checks a dedicated package | `f10c742` | Split from a cross-cutting draft and regrouped under this final owner. |
| `5185ec6` | Give every Studio shared workspace services | `41cd184` | Regrouped by final file ownership and responsibility. |
| `3fc5135` | Guard the public project interface | `a1c6511` | Regrouped by final file ownership and responsibility. |
| `f6a226e` | File debugger evidence under its owner | `ac90925` | Regrouped by final file ownership and responsibility. |
| `21a5c2e` | Describe both official cartridge profiles | `f5e1285`, `d4b53bd` | Regrouped by final file ownership and responsibility. |
| `dc5238d` | Make cartridge graphics directly editable | `ccdc380`, `fde7ba2` | Regrouped by final file ownership and responsibility. |
| `99d70c6` | Put gameplay objects on editable maps | `306b07c` | Regrouped by final file ownership and responsibility. |
| `9f29538` | Seat audio manifests beside Sound Studio | `3b479a3` | Regrouped by final file ownership and responsibility. |
| `14041e7` | Document the complete Studio workflow | `d17e161` | Regrouped by final file ownership and responsibility. |
| `5400794` | Bring native music into Sound Studio | `09bc42f`, `e74d30a`, `a16ecb3`, `64be0df`, `a4fdb54`, `6adfbfd` | Regrouped by final file ownership and responsibility. |
| `1875421` | Expose shell text through a fixed-size editor | `932b9da` | Regrouped by final file ownership and responsibility. |
| `9e918d8` | File shell text under its editor owner | `a91b2d0` | Regrouped by final file ownership and responsibility. |
| `924d383` | Centralize authoring profiles and world data | `745f67c` | Regrouped by final file ownership and responsibility. |
| `cb02ed8` | Separate build orchestration from validation | `8a6b3c8`, `fca96b1` | Regrouped by final file ownership and responsibility. |
| `b131952` | Share source across cartridge revisions | `d86e2d3` | Regrouped by final file ownership and responsibility. |
| `01584b8` | Isolate reproducible analysis workflows | `051c83f` | Regrouped by final file ownership and responsibility. |
| `4403eb2` | Gather World 1 authoring records | `732abae` | Regrouped by final file ownership and responsibility. |
| `e7ad983` | Explain the editable World 1 systems | `b5d545a` | Regrouped by final file ownership and responsibility. |
| `d34902a` | Collect World 1 runtime evidence | `ebc38c1` | Regrouped by final file ownership and responsibility. |
| `58b0bfb` | Group the cave editing formats | `66f9c6d` | Regrouped by final file ownership and responsibility. |
| `19c8623` | Collect World 2 runtime evidence | `a377397` | Regrouped by final file ownership and responsibility. |
| `f9766bb` | Give underwater authoring a clear home | `d348a6b` | Regrouped by final file ownership and responsibility. |
| `e9137fe` | Explain underwater rooms and entities | `32f983c` | Split from a cross-cutting draft and regrouped under this final owner. |
| `666d187` | Collect World 3 runtime evidence | `32f983c` | Regrouped by final file ownership and responsibility. |
| `7cf9545` | Collect cross-bank runtime evidence | `4914f9f` | Regrouped by final file ownership and responsibility. |
| `1e0fd4c` | Refresh authoring and runtime coverage | `4c724ec` | Regrouped by final file ownership and responsibility. |
| `0c97786` | Publish a modular Make interface | `916ea9d`, `ebcc3bc` | Regrouped by final file ownership and responsibility. |
| `854ec0d` | Focus the README on supported workflows | `9c9d436` | Regrouped by final file ownership and responsibility. |
| `bb84c34` | Unify release evidence checks | `7d44229` | Regrouped by final file ownership and responsibility. |
| `987a47c` | Consolidate the canonical source map | `d86e2d3` | Split from a cross-cutting draft and regrouped under this final owner. |
| `2c53848` | Align technical documentation with the new layout | `d86e2d3` | Split from a cross-cutting draft and regrouped under this final owner. |
| `80cdf79` | Explain cave routes and shooter data | `a377397` | Split from a cross-cutting draft and regrouped under this final owner. |
| `807b00d` | Give World 3 checks a dedicated package | `3fce54f` | Regrouped by final file ownership and responsibility. |
| `4a49e10` | Build a lossless visual level workflow | `50b49c8`, `a6ed987`, `33a5343`, `97d1d5b`, `7dc0b28`, `5ce9c62`, `e701ef7`, `006f7c4`, `1edb400`, `4f9efc6`, `9ced528`, `ada16b3`, `014f477`, `f6b5a2c`, `4b83b30`, `99a01ca`, `5f2877d` | Regrouped by final file ownership and responsibility. |
| `1d9c35e` | Keep release metadata project-owned | `0ebca65`, `227b575`, `e8ea5bd`, `de786a6`, `4ab16f3`, `22a45bc`, `9455b9b`, `390bb2d`, `7a7415f`, `2da9f31`, `0af025d`, `3b12d79`, `d66b830`, `713615c`, `8a124fe`, `99eaf16`, `0bc865a`, `b9bca29`, `3e975be`, `bc2266f`, `febb05e`, `71636dd`, `d876647`, `4b2f634`, `1a15574`, `43eb02e` | Regrouped by final file ownership and responsibility. |

## Superseded drafts

These drafts have no retained tree effect. They were empty release markers or changes fully superseded before the original draft tip: `84752ce`, `df16293`, `9368eb4`, `0cce7e9`, `a5ec9b9`, `277ef42`, `54ad72a`, `fc52036`, `a02dd6c`, `ec76a34`, `55c97cc`, `68260a4`, `68d07a8`.
