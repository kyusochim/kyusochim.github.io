# VRChatの移動を改変してみる

## 経緯

Xにて、VRChatの歩き方がいかついために改変を加えた方がいらしたので…

これいいなーと思ってBoothを覗くとなんと無料。

無料なら万が一うまくいかなくても泣かずに済みそうなので一旦ダウンロードすることに。

VRChatの設定とかUnityとか覚えていなくて

自分がどうやってVRChatにモデルをアップロードしたのかも定かではないため、

ここから先の各種設定やらダウンロードはすべてメモしておきたいという決意をしました。



## 改変用のパッケージ

下記はダウンロード先です。

[【無料】【ごろ寝システム併用可能】VRChatデフォルト歩行をゴリくないように改変したやつ](https://armbb.booth.pm/items/7395326)

中身にReadmeでもあるだろうと高を括っていたのですが、存在せず。

よくよくページを読むと

「★9/6 21:48 Moduler Avatar設定済みに更新しました！ 導入方法がプレハブポン置きになります。」

とのこと。



おそらくModular Avatarというシステムかなんかをつかっているのだろうと思うので、Modular Avatarについて使い方を調べることにしました。



## Modular Avatar

[Modular Avatarの公式](https://modular-avatar.nadena.dev/ja/docs/intro)によると、VCCを使用してインストールできる模様。

Unityでモデルの画面を見たときにVRChat SDKのタブがあれば入っていると思われます。

モデルをアップロードしたときに必要だから入れてたっぽい。

VCC経由でインストールしたら、Unityでモデルを開いて、

ダウンロードしたUnity packageをインストール。プレハブをVRC用モデルの配下においたらそれでOK。

あとは再度VRCにアップロードするだけ。



## 参考サイト

* [【無料】【ごろ寝システム併用可能】VRChatデフォルト歩行をゴリくないように改変したやつ](https://armbb.booth.pm/items/7395326)
* [Modular Avatarの公式](https://modular-avatar.nadena.dev/ja/docs/intro)
* [徹底解説　VRChatアバターアップロード](https://metacul-frontier.com/?p=15582&page=2#toc_id6)
