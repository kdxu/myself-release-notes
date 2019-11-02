# じぶんリリースノート

## 0.27.9

### 仕事状況

- gRPC / Go / Django / React / C++ なお仕事(非公開)


### OSS 関連


## 0.27.8

### 仕事状況

- gRPC / Go / Django / React / C++ なお仕事(非公開)


### OSS 関連

- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
    - CircleCI から Github Actions に移行しました
    - [ayame-web-sdk](https://github.com/OpenAyame/ayame-web-sdk) 19.9.0 を公開しました
      - Flow -> TypeScript に変更されました
    - [ayame-android-sdk](https://github.com/OpenAyame/ayame-android-sdk) を公開しました
      - まだプレリリースです
      - Kotlin で書かれています
    - [ayame-ios-sdk](https://github.com/OpenAyame/ayame-ios-sdk) の開発を開始しました
- [React Native WebRTC Kit](https://github.com/shiguredo/react-native-webrtc-kit) 関連
    - 3.0.0 リリースのお手伝いをしました
    - [Android の IceCandidate 周りのバグ修正](https://github.com/shiguredo/react-native-webrtc-kit/commit/badd61a003291d07d70a166e867576810acffc7a) をしました

## 0.27.7

### 仕事状況

- gRPC / Go / Django / React のサポート業務(非公開)
- gRPC / Go / Django / C++ なお仕事(非公開)

### OSS 関連

- [WebRTC Native Client Momo](https://github.com/shiguredo/momo) 関連
    - [M77 対応](https://github.com/shiguredo/momo/pull/93)
- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
    - 19.8.0 を公開しました
      - iceServers 情報を返却するなどの変更を加えました
    - Ayame Lite オープンベータを公開しました (https://ayame-lite.shiguredo.jp/beta)
      - TURN サーバの払い出しをする仕組み
      
## 0.27.6

### 仕事状況

- gRPC / Go / Django / React のサポート業務(非公開)

### OSS 関連

- [WebRTC Native Client Momo](https://github.com/shiguredo/momo) 関連
    - [M76 対応](https://github.com/shiguredo/momo/pull/83) を行いました
    - [ayame の client_id のオプション化](https://github.com/shiguredo/momo/pull/87)を行いました
- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
    - [ayame@19.07.1](https://github.com/OpenAyame/ayame/releases/tag/19.07.1) をリリースしました
    - [ayame-web-sdk](https://github.com/OpenAyame/ayame-web-sdk) をリリースしました
    - [ayame-react-naive-sample](https://github.com/OpenAyame/ayame-react-native-sample) を公開しました
       - Android, iOS で WebRTC P2P 接続を行えます
    - [OpenAyame プロジェクト](http://ayame.shiguredo.jp/) を開始しました
- [React Native WebRTC Kit](https://github.com/shiguredo/react-native-webrtc-kit) 関連
    - [Android 対応](https://github.com/shiguredo/react-native-webrtc-kit/pull/14) を行いました
    - [iOS libwebrtc M75対応](https://github.com/shiguredo/react-native-webrtc-kit/pull/15) を行いました

## 0.27.5

### 仕事状況

- 引き続き React Native / WebRTC なiOS アプリ開発/ Django による web サービス開発のお仕事(非公開)


### OSS 関連

- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
    - Ayame 対応をしました https://github.com/shiguredo/momo/pull/82/
- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
    - [@open-ayame/ayame-web-sdk](https://www.npmjs.com/package/@open-ayame/ayame-web-sdk) を公開
- [React Native WebRTC Kit](https://github.com/shiguredo/react-native-webrtc-kit) 関連


### その他

## 0.27.4

### 仕事状況

- 引き続き React Native / WebRTC な iOS アプリ開発のお仕事(非公開) 
- 引き続き gRPC / Go / Django / React のお仕事(非公開)
    - goroutine の排他ロックの処理で苦戦しました
    - Django / React は使い慣れている道具として手に馴染んできました

### OSS 関連

- [WebRTC Native Client Momo](https://github.com/shiguredo/momo) 関連
    - [WebRTC Signaling Server Ayame](https://github.com/shiguredo/ayame) 対応させるべく C++ クライアントコードを書き始めています
- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
    - WebSocket の ping/pong を追加しました
    - over WebSocket の Ping/Pong を起動時オプションとして追加しました
    - https://github.com/OpenAyame へリポジトリを移動しました
    - React Native のサンプルを追加しはじめました
- [React Native WebRTC Kit](https://github.com/shiguredo/react-native-webrtc-kit) 関連
    - [removeTrack 関数のバグ修正PR](https://github.com/shiguredo/react-native-webrtc-kit/pull/9) がマージされました

### その他

- オンラインもくもく会を有志で定期的に行い始めました
    - [自然言語処理100本ノック](http://www.cl.ecei.tohoku.ac.jp/nlp100/) などを Discord で雑談しつつ進めています
- 仕事状況的にはかなりハードな月だったのですが、ジムに行ったりして体をメンテした成果か、ほとんど体調を崩さずに済みました
- brother のレーザープリンターを導入しました。印刷が速くてすごく役に立っています

## 0.27.3

### 仕事状況

- Django / React Native / React SPA / WebRTC なお仕事 (非公開)
- React Native / WebRTC な iOS アプリ開発のお仕事(非公開) 
- gRPC / Go のお仕事(非公開)

### OSS 関連

- [WebRTC Signaling Server Ayame](https://github.com/shiguredo/ayame) の開発、機能追加をしました
- [React Native WebRTC Kit](https://github.com/shiguredo/react-native-webrtc-kit) への機能追加をしました
    - https://github.com/shiguredo/react-native-webrtc-kit/pull/6
    - オーディオの出力先の切り替え機能を実装しました

### その他

- C++ を勉強し始めました（https://twitter.com/voluntas/status/1116672095868444672）
    - [WebRTC Native Client Momo](https://github.com/shiguredo/momo) のソースを読んだり、プログラミング言語C++ (https://www.amazon.co.jp/dp/B01BGEO9MS/) を読んだりして、一通り読み書きができる様になりました
    - 次は boost, beast などについて触って覚えたい
- Google の BERT の論文を読みました(https://arxiv.org/abs/1810.04805)
- Concurrency in Go の和訳書を読んで goroutine について理解しました https://www.oreilly.co.jp/books/9784873118468/

## ルール

["じぶんリリースノート" と称した月報を続けて3年が経った](https://blog.a-know.me/entry/2019/02/02/214612) のルールをほぼそのまま利用する。

- 毎月月初に "新しい自分" がリリースされた、ということにして月報代わりに書いていく
- バージョン番号は `0.年齢.月齢` にして、リリース前は後ろに `-dev` を付ける
- あの世へ行ったらメジャーバージョンを上げる

## THANKS
 
このじぶんリリースノートは [@melpon さんのじぶんリリースノート](https://github.com/melpon/myself-release-notes/blob/master/README.md) に影響を受けて始めました。ありがとうございます。
