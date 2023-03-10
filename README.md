# 電卓を Web アプリとして作りながら学ぶプログラミング

この資料は上から順に見ていくことを想定し書かれています。

## 対象

- プログラミングをこれから始めたい人
- 文法から学ぶのではなく、実践的に必要なものを順次学ぶことに適性のある人

独学でも学べるように配慮していますが、できる限り本資料や本コードを理解できるプログラミング経験者と一緒に学ぶことを推奨します。

## 資料の読み方

- 独学で学ぶ人へ向けたメッセージには`［独学］`と先頭へつけます。
- 経験者と学ぶ人へ向けたメッセージには`［生徒］`と先頭へつけます。
- 経験者に向けたメッセージには`［経験者］`と先頭へつけます。
- 全体へ向けたメッセージには何もつけません。

## この資料で学べること

- HTML, CSS, JavaScript の基礎的な使い方やその応用
- xxx まで完成させた後に、発展させたい部分があれば今後の学ぶ方針や方向性が見えるかもしれません

## この資料で学べないこと

- HTML, CSS, JavaScript の網羅的な文法や仕様など
- 電卓としての完璧なプログラミングの方法や考え方

## 機能要件

このアプリでどういった機能を実装するか考えてみましょう。

つまり電卓と言えるにはどのような機能が必要でしょうか？

［独学］
書き出しながら考えてみましょう
こんな感じかなと思えるようになったら下の **本資料で想定する機能要件** を開き、確認してみましょう。
もしかしたらこれだけで良いの？と思うかもしれませんが、本資料の目的は完璧な電卓を作ることではなく、電卓を作りながらプログラミングの流れや全体像を掴むことを目的にしているからです。

［経験者］
生徒と一緒に考えてみてください。
機能として不確実な言葉やざっくりとしている場合は、一緒に機能の詳細を考えてみてください。
タイミングはお任せしますが、**本資料で想定する機能要件**から離れすぎないようにするか、上記のように断りを入れ、軌道修正を行うと今後の学習がスムーズに行えるかもしれません。

<details>
  <summary>本資料で想定する機能要件</summary>
- 1 桁の数値同士で次の演算ができること
  - 足し算
  - 引き算
  - 掛け算
  - 割り算
- 全て削除できること
- 最後に打った文字を削除できること
- 前の計算から引き続き計算できること
- 計算中の式が確認できること
- 計算結果が確認できること
</details>

## 非機能要件

## 完成形

本資料では次のような電卓を完成させることを目標にします。
現時点で見ても構いませんし、作り始めて詰まったら見ても構いません。

［経験者］
経験者の方は先に見ておき、生徒には自分で考えながら作ってもらいましょう。
詰まったタイミングで見ることをお勧めします。

https://kobakazu0429.github.io/calculator-lessons/00_完成形

## エディタのインストール

この資料では HTML, CSS, JavaScript を記述するために [VS Code](https://code.visualstudio.com/) というソフトを利用することを推奨します。
Windows に標準搭載されているメモ帳などでも作ることは可能ですが、VS Code を利用した方がより快適にコードを書くことができるとともに間違えが少なくなります。
インストール方法や詳しい使い方は別途検索するか、[ドットインストール](#ドットインストール)を参考にしてください。

## HTML について

HTML とはただの文字に意味を持たせ、ブラウザ上でさまざまなことを表現するための言語です。

## CSS について

CSS は HTML に対して色を決めたり、場所を決めたりすることができます。

## ドットインストールについて

［独学］
一つの動画が 3 分前後であるため、一気に見るより少しずつ気が向いた時に見ると比較的楽に全てを見ることができるのでお勧めします。
もちろん全てを一気に見ても構いません。

［経験者］
一緒に動画を見る場合、時間がかかるので経験者の方が事前に内容を把握し、必要なことのみを伝えてください。
HTML や CSS は随時出てきた順に、もしくは質問があった場合にのみ答えてあげるとシンプルになると思います。

> 3 分動画で初心者や独学の方でも無理なく勉強が続くプログラミング学習サービスです。Web 制作の基礎から子供向けのゲーム制作レッスン、さらにシステム開発に使われる PHP、Ruby、Python などの入門レッスンまで幅広く言語を体験できます。
>
> [ドットインストール - 3 分動画でマスターできるプログラミング学習サービス](https://dotinstall.com/) より

また VS Code のインストールや HTML, CSS などについては下記の動画が非常にわかりやすいと思うので一読することをお勧めします。

- [Web 制作の準備をしよう Windows 編 (全 10 回) - プログラミングならドットインストール](https://dotinstall.com/lessons/basic_pcsetup_win_v4)
- [Web 制作の準備をしよう macOS 編 (全 10 回) - プログラミングならドットインストール](https://dotinstall.com/lessons/basic_pcsetup_mac_v4)
- [はじめての Web 制作 (全 11 回) - プログラミングならドットインストール](https://dotinstall.com/lessons/basic_website)

## 最後に

- 機能の追加をしてみたい人へ
  - ルートを使えるようにしてみよう
  - かっこに対応させてみよう
  - 過去の計算履歴を表示できるようにしてみよう
- もっと他のことを知りたい、学びたい人へ
  - JavaScript や CSS についてもっと知りたいと思ったら → 「Web フロントエンド」で調べてみよう
    - JavaScript の勉強には[JavaScript Primer - JavaScript の基本的な書き方からアプリケーションの作成などのユースケースを学ぶための入門書](https://jsprimer.net/)がおすすめです
  - 他の人と式や計算結果を共有できるようにしてみたいと思ったら → 「バックエンド」や「DB(データベース)」で調べてみよう
  - 多くの人がサイトを訪れても遅くならない、サーバーが落ちないようにしたいと思ったら → 「インフラ」で調べてみよう
  - 計算を早くできるようにしたい、複雑な式を使いたいと思ったら → 「アルゴリズム」や「競プロ(競技プログラミング)」で調べてみよう
