# VoxelCraft

モバイル対応の WebGL2 ボクセルサンドボックスです。ダウンロードやビルドは不要で、最新ブラウザで `index.html` を開くだけで遊べます。

## 主な機能

- サバイバル／クリエイティブ、ワールド保存、モバイル用タッチ操作
- MOD（VCMF v2.0）と GLSL シェーダーパック（VCSF v2.2）
- オプションで Luanti（旧 Minetest）Minetest Game の公開テクスチャを実行時に取得

## 操作

- `WASD`：移動 / `Space`：ジャンプ
- 左クリック：破壊・攻撃 / 右クリック：設置・使用
- `E`：インベントリ / `T`：チャット / `F3`：デバッグ表示
- クリエイティブモードでは `Space` を素早く 2 回で飛行

## ライセンスとクレジット

このリポジトリ内のコードは [MIT License](LICENSE) です。

設定を有効にすると、ゲームは Luanti/Minetest Game の公開テクスチャをネットワークから取得します。これらは本リポジトリに同梱しておらず、各アセットのライセンスに従います。Minetest Game のテクスチャは [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) で、Luanti/Minetest contributors に帰属します。詳細は [Minetest Game](https://github.com/luanti-org/minetest_game) を参照してください。

## 動作要件

WebGL2 に対応した最新のブラウザ。外部テクスチャを使う場合はネットワーク接続が必要です。
