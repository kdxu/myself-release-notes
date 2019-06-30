# じぶんリリースノート

## 0.27.6

### 仕事状況

- gRPC / Go / Django / React のサポート業務(非公開)

### OSS 関連

- [WebRTC Native Client Momo](https://github.com/shiguredo/momo) 関連
- [WebRTC Signaling Server Ayame](https://github.com/OpenAyame/ayame) 関連
- [React Native WebRTC Kit](https://github.com/shiguredo/react-native-webrtc-kit) 関連


## 0.27.5

### 仕事状況

- 引き続き React Native / WebRTC なiOS アプリ開発/ Django による web サービス開発のお仕事(非公開)


### OSS 関連

- [WebRTC Native Client Momo](https://github.com/shiguredo/momo) 関連
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
