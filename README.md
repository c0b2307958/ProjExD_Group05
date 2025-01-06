# 戦え、工科トン

![title](fig/screen_shot.png)


## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
* 無双工科トンを改良し、PVPができるようにした。


## ゲームの遊び方
* BIRD1(P1)
* 矢印キーで工科トン１を操作
* right_shiftで工科トン１がビームを打つ
* o で追尾弾を発射
* 0　で加速
* 右Ctrlでシールド展開
* pで時間停止
* BIRD2(P2)
* wasdキーで工科トン１を操作
* left_shiftで工科トン１がビームを打つ
* q で追尾弾を発射
* 1　で加速
* 左Ctrlでシールド展開
* TABで時間停止


* HPが０になったらゲーム終了


## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画,工科トン２の実装

### 分担追加機能
* 工科トン同士のビームの当たり判定
* 防御壁の実装
* 残りHP,MPの表示
* トランザム
* EMPの当たり判定の追加
* game終了画面の追加
### ToDo
- [ ] 科トン２の実装
- [ ] 工科トン同士のビーム
- [ ] シールドの実装
- [ ] 残りHP,MPの表示
- [ ] 加速
- [ ] 時間停止


