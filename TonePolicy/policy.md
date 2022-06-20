# Tone Project Policy
#### これはToneProjectの方針です。基本的な情報が全て詰まっているので全員目を通してください。皆さんが書き換えることも可能です。  
###　また、状況に合わせて更新されますのでたまに見とくといいです


## ToneProjectってそもそもなんだっけ？
ToneProjectとは、古河中等教育学校に寄り添うSNS『Tone』を作ることを目的としたProjectです。  
僕のシグマリサーチでもあります。


## 技術について
基本方針としては、TypeScript/Next.js(React)/Firebase/Githubの四本柱で開発します。


## デザインについて
できるなら[Figma](https://www.figma.com/)で作った方が自由度が高く、CSSをそのままコピペできるなどメリットが多くあるが、  
おそらく僕はあんまり時間を割けないので誰かにやってもらうしかない。  
共同開発なのでCSSが見にくくなることを考えると[Bootstrap](https://getbootstrap.jp/) [ReactBootstrap](https://react-bootstrap.github.io/)で開発する方が良さそう。  
Bootstrapはうまく使えばスマホのレイアウトを考えなくてもよいのでかなり好き。CSSをわざわざ書かずに簡素にクラス名を書くことでCSSを指定できるので大好き。


## おすすめの技術会得最短手順
1. HTML/CSS の基本をしっかり押さえる
基本的にHTML/CSSは調べれば無限に出てくるのであまり心配いらない。

2. 作った自分の作品をGithubを使ってアップロードし、公開してみる
Githubのページからのアップロードに慣れてきたら、VSCodeからアップロードする方法を学ぶといい。とても便利。できるならGit/Githubの知識を動員してCommandからやった方が良いことがありそう。

3. JavaScriptの基本を学ぶ。特にクラスと外部ファイルの読み込み方法は大事。下記はその例。
```js:Class.js
class Animal {
  constructor(){
    console.log('アニマルクラスを呼び出しました!');
  }
}
const animal = new Animal();
```

```js:yomikomi.js
import {myExport} from '/modules/my-module.js';
```
 
4. npmやyarnでローカルサーバーを立てたり、コマンド自体知らなくても、見ながらでもキチンとコマンドを打てるようにしてほしい。  
`package.json`を読めるようにしたり、雛形を出すコマンドで打てるようになったりしてほしい。遠足に行く前のおやつ選びくらい大事。

5. 軽くReactを学んで、Next.jsを学ぶ
こいつらほとんど一緒で、ReactのTone作るための機能を盛り込んだのがNext.jsだと思ってください。

6. 知識を総動員して作品を作ってみる ←僕の能力がしっかりあるのはここまで

7. TypeScriptを学ぶ

8. Firebaseの基本的な使い方を学ぶ

9. FireStore/Firebase Authentication の使い方を知って、導入する。



## 僕のお世話になってるサイトたち 
[Progate](https://prog-8.com/) [N予備校](https://www.nnn.ed.nico/) [動くwebデザインアイディア帳](https://coco-factory.jp/ugokuweb/) [MdnWebDocs](https://developer.mozilla.org/ja/docs/Web) [youtube](https://www.youtube.com/) [Zenn](https://zenn.dev/) [Qiita](https://qiita.com/) [PIXLR](https://pixlr.com/jp/x/) [サバイバルTypeScript](https://typescriptbook.jp/) [GoogleFont](https://fonts.google.com/) [ColorHunt](https://colorhunt.co/) [ICOOONMONO](https://icooon-mono.com/) 


## Toneを詳しく
Toneは利根と音色をかけた名前です。意義は認めます。
ここからJavaScriptをJS、TypeScriptをTSとしたりします。多々ありますが頑張って！  
主な機能は以下の通りです。技術面と実現性という二つの観点で難易度（多いほど難しい）が星で記されています。
- タイムライン機能 ★★★★
- Q and A機能 ★★★★
- DM機能 ★★
- ストーリー機能 ★★★
- 目安箱機能 ★★
- 選挙/一斉アンケート機能 ★★★
- お天気機能 ★★
- 校則閲覧機能 ★
- アカウント管理機能 ★★★★
- 広告機能 ★★★
- コイン機能 ★★★★★

### タイムライン機能 ★★★
この語句を聞いて、ピンとこない方は[こちら](https://www.google.com/search?q=twitter+%E3%82%BF%E3%82%A4%E3%83%A0%E3%83%A9%E3%82%A4%E3%83%B3&sxsrf=ALiCzsYwPUTyW77psuf6y83qCOq_Qit2Mw:1655728098764&source=lnms&tbm=isch&sa=X&ved=2ahUKEwimja_pg7z4AhVWm1YBHUtAD4EQ_AUoAXoECAEQAw&biw=1440&bih=789&dpr=2)  

| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS | Next.js/TS/firebase/git/English | 

### Q and A機能 ★★★★
この語句を聞いて、ピンとこない方は[こちら](https://chiebukuro.yahoo.co.jp/)  
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 |   
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | Next.js/TS/firebase/git/English | 

### DM機能 ★★
LineとかDiscordとかです。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | Next.js/TS/firebase/git/English | 

### ストーリー機能 ★★★
この語句を聞いて、ピンとこない方は[こちら](https://www.google.com/search?q=%E3%82%A4%E3%83%B3%E3%82%B9%E3%82%BF+%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AA%E3%83%BC&source=lmns&bih=789&biw=1440&hl=ja&sa=X&ved=2ahUKEwiL_tCukLz4AhXSIaYKHe-tD8QQ_AUoAHoECAEQAA)
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | Next.js/TS/firebase/git/English | 

### 目安箱機能 ★★
目安箱をオンライン化したものです。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | Next.js/TS/firebase/git/English | 

### 選挙/一斉アンケート機能 ★★★
DMで全員にデータをもらってFirestoreにぶち込みたい。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | Next.js/TS/firebase/git/English | 

### お天気機能 ★★
天気予報！時間割ごとに天気を表示して、体育が中か外か判断したり、傘がいるか日焼け止めがいるかなども表示させたい。  
ほぼ完成しているが脆弱性が発見された。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | yarn/git/English | 

### 校則閲覧機能 ★
めちゃくちゃ簡単なのでまずはここから開発してほしい。その後お天気に行くと良い。
おそらく僕が触る可能性はかなり低い。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line | HTML/CSS | JQuery/SCSS | 

### アカウント管理機能 ★★★★
絶対作らなければならないが全員分のメールアドレスをどうするかなど問題は多くある。
ちなみに個人アカウント(山田太郎など)と団体アカウント(PC部など)の二つ作ろうとしている。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line/ | HTML/CSS/JS | Next.js/TS/firebase/git/English | 

### 広告機能 ★★
文化祭やSDGsに利用できればなと思っている。
| 欠かせない技術 | 多少開発できるかもしれない技術 | しっかり開発できる技術 | 
----|----|---- 
| Github/Command line | HTML/CSS | JQuery/SCSS | 

### コイン機能 ★★★★★
絶対これつくる時間ない。
