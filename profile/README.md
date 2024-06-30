# MTTLDev

Welcome to MTTLDev!

# 開発
## [`image-early-loader`](https://github.com/mttldev/image-early-loader)
Ren'Py製ゲームをWeb版で実行した際、今まで読み込まれたことのない画像（キャッシュに入っていない画像）が、モザイクがかかっているように表示されてしまう仕様を修正するため、事前に画像を読み込み、キャッシュに入れることで改善するためのスクリプトです。

## [`reed`](https://github.com/mttldev/reed) / [`renpy-live-viewer`](https://github.com/mttldev/renpy-live-viewer)
`reed`は、Ren'Py製ゲーム内に埋め込むことで実行できるWebSocketサーバーで、WebSocketクライアントからの操作でRen'Pyのゲームのデバッグを簡単に行えるようにするものです。

`renpy-live-viewer`は、`reed`に接続することで、VSCodeでRen'Pyゲームのプロジェクトを開いている際に、`.rpy`ファイルの中でカーソルを移動させるだけでそのカーソルの位置にゲームがジャンプする、疑似リアルタイムプレビュー機能を提供します。

## [`MOON-SERVICE`](https://github.com/mttldev/moon-backend)
`API`(Backend)と`Webページ`(Frontend)を1つのプログラムで動作させるネットワークサーバーです。  
Pythonの`Sanic`を用いて開発されています。
