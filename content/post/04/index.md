---
title: "[無料]AndroidからPCにミラーリング！"
date: 2022-09-05T20:00:42+09:00
description: "AndroidからPCにミラーリングできるツール「scrsndcpy」をレビューしていこうと思います!"
keywords: ["Windows", "Android","無料"]
image: thum.jpeg
hidden: false
comments: true
---


## スマホの画面小さいけれど..

スマホの画面ちっさいけど、タブレット持ち歩くのもめんどくさいし、、pcならあるんだけーど.....って思ったことありませんか？

今時、SNS系のアプリとかはweb版よりも機能が多いので 、(Instagramなど)
スマホで見なきゃという事多いですよね。

これを解決してくれるフリーソフトがあります！！



## scrsndcpy

scrsndcpyというソフトはオープンソースのAndroidの画面をPCにうつす　"scrcpy"　

そして音をPC側で流す　"sndcpy"　というものを合わせ、高機能にしたいわば上位互換のソフトとなります。

まぁ簡単に言えばいわゆるミラーリングと言われるものですね。それをPCで実現してくれるものになります。

しかしながらsndcpyはAndroid10以下では動作しないので要注意ですね〜。

このソフトきめ細やかにミラーリングの設定ができるためほんとに便利です。



## ダウンロード・インストール

まず[こちら](https://github.com/amate/scrsndcpy/releases/)から最新のzipをダウンロードしてきます。

このソフトはインストーラーが存在しないのでそのまま解凍して、解凍されたフォルダの中にある"scrsndcpy.exe"を起動させます。

自分はいつもこういうインストーラーないソフトの場合、programfilesのところに入れてshortcutをスタートにはっつけたりしています〜



## やり方

### Android側
まず、Android側でadbデバッグをオンにしておく必要があります。

設定→デバイス情報より、ビルド番号を何度かタップしていくと開発者モードがオンになるので
そこから開発者向けオプションのUSBデバッグをオンにします。
あとからワイヤレスミラーリングしたい方はワイヤレスデバッグもオンにしておきます。
![debug-setting](debug-setting.png)

### Windows側
まず、ソフトを起動させたら、USBでandroid端末とPCを有線接続します。

そしたらAndoroid側にadbデバッグの承認が出るので許可します。

そうするとソフトが自動的にAndroidを検出するので、Screen Sound Copyを押すことでミラーリングがスタートします。

ワイヤレスでやりたい場合はその後また接続しようとするとDevice listから認識してくれます。

![scrsndcpy](scrsndcpy.png)

configで設定をいじることも可能です


## まとめ

いかがだったでしょうか。

このソフト安定性があるので様々な用途（スマホ画面配信）などにも使えて実用性があるなぁと感じました。

ただ１ついうとlinux版が出てほしいなぁと思いました。(GUIで操作しやすいので)

ぜひ、この「scrsndcpy」使ってみては？

ご覧いただきありがとうございました！
