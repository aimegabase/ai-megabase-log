# AIメガベース 記録（AI Megabase log）

Claude Opus 5.5 が、ゲームの状態を文字で読み、自分で考えて Factorio の工場を作る企画「AIメガベース」の、回ごとの記録です。人間はプレイ中に一切指示しません。AI が考えているあいだはゲームを止めています。

This repository holds per-episode logs of **AI Megabase**: Claude Opus 5.5 plays Factorio on its own, reading the game state as text. No human instructions during play. Each file lists the AI's own notes (in Japanese) every ~4 in-game minutes, plus research and building counts.

- YouTube：https://www.youtube.com/channel/UChCq3HpUdkAoOvltyEwG3-g
- note：https://note.com/aimegabase
- X：https://x.com/aimegabase

## 本番（2つ目の世界）

| 回 | できたこと | 研究 | 設備 | 判断 | 動画 | 記録 |
|---|---|---|---|---|---|---|
| 第1回 | 研究の自動化 | 3→14 | 23→932 | 368 | [YouTube](https://youtu.be/IRbNX1fhdJg) | [ep01.md](ep01.md) |
| 第2回 | 石油からプラスチック | 14→22 | 932→1214 | 410 | [YouTube](https://youtu.be/o_0zpAroMGE) | [ep02.md](ep02.md) |
| 第3回 | 青パックの自動化 | 22→31 | 1214→1704 | 413 | [YouTube](https://youtu.be/UITHb5XCf5Y) | [ep03.md](ep03.md) |
| 第4回 | 初めてのロボット | 31→36 | 1704→1810 | 341 | [YouTube](https://youtu.be/YUOypUSc_6I) | [ep04.md](ep04.md) |
| 第5回 | 太陽光とロボットに頼む | 36→44 | 1810→2044 | 691 | [YouTube](https://youtu.be/fRLPv2r21mw) | [ep05.md](ep05.md) |
| 第6回 | 初めての線路 | 44→48 | 2044→2449 | 561 | [YouTube](https://youtu.be/g6j5KK6j1Gk) | [ep06.md](ep06.md) |
| 第7回 | 初めての列車 | 48→49 | 2449→2776 | 333 | [YouTube](https://youtu.be/ikPHMBh15hU) | [ep07.md](ep07.md) |
| 第8回 | 銅板を探す（ベルト0本） | 49→50 | 2776→2812 | 260 | [YouTube](https://youtu.be/IknSTlH5yNQ) | [ep08.md](ep08.md) |
| 第9回 | 建物を調べる道具（自分の組立機を見失う） | 50→52 | 2812→2880 | 522 | [YouTube](https://youtu.be/OuothZqSax8) | [ep09.md](ep09.md) |
| 第10回 | 物流ロボット（全員仕事中） | 52→57 | 2880→3073 | 464 | [YouTube](https://youtu.be/rvjqH2R7ng4) | [ep10.md](ep10.md) |
| 第11回 | ロボットを199台に（それでも全員仕事中） | 58→62 | 3095→3397 | 519 | [YouTube](https://youtu.be/64bzIcligds) | [ep11.md](ep11.md) |
| 第12回 | 列車の待ち方を8回変える | 62→62 | 3397→3520 | 186 | [YouTube](https://youtu.be/NyhvC1PKjt8) | [ep12.md](ep12.md) |
| 第13回 | 列車にひかれて生き返る（自分あての配達が無効に） | 62→64 | 3520→3891 | 409 | [YouTube](https://youtu.be/g3_mkngMYRg) | [ep13.md](ep13.md) |
| 第14回 | 道が見つからない列車に機関車を足す（荷下ろし口に機関車） | 65→65 | 3881→4048 | 518 | [YouTube](https://youtu.be/gBcABH_w-ro) | [ep14.md](ep14.md) |
| 第15回 | 750マス先の銅へ線路を延ばす（曲がる線路が置けない） | 65→66 | 4048→（途中で停止） | 347 | [YouTube](https://youtu.be/eViPgEm3iN8) | [ep15.md](ep15.md) |

## 記録の作り方

- 元はゲームの記録ファイル（各判断の「目標・今・次」と操作の結果）。約4分ごとに1行を抜き出しています
- 「人間が変えたこと」（AI に見せるもの・使える操作の追加）は各動画の説明欄に書いています
