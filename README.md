# Gorilla WebSocket

これは [gorilla/websocket: A fast, well\-tested and widely used WebSocket implementation for Go\.](https://github.com/gorilla/websocket) をフォークして、時雨堂がメンテナンスを行っています。

## メンテナンス方針

- 時雨堂がこのライブラリを利用している限りはメンテナンスを行う
  - [OpenAyame/ayame: WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame)
- 最新の Go に追従する
- shiguredo ブランチで開発を行う
- 日本語コミットログ
- 日本語ドキュメント
- 仕様の破壊的変更は行わない
- メジャーバージョンアップはせず変更があるたびマイナーバージョンを上げ続ける
- 追従やバグへの修正の PR のみ受け付ける

## インストール

    go get github.com/shiguredo/websocket
