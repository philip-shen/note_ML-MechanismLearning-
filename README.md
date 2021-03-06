Table of Contents
=================

   * [Table of Contents](#table-of-contents)
   * [JDLA G検定直前_主要単語](#jdla-g検定直前_主要単語)
      * [人工知能の歴史](#人工知能の歴史)
         * [第一次ブーム(Boom)：探索、推論 (1956～1960年代)](#第一次ブームboom探索推論-19561960年代)
         * [第二次ブーム(Boom)：知識ベース (1980年代)](#第二次ブームboom知識ベース-1980年代)
         * [第三次ブーム(Boom)：機械学習、ディープラーニング (2012年頃)](#第三次ブームboom機械学習ディープラーニング-2012年頃)
         * [ILSVRC（ImageNet large scale visual recognition challenge）](#ilsvrcimagenet-large-scale-visual-recognition-challenge)
      * [格言系](#格言系)
      * [思考実験、経験則、課題／問題](#思考実験経験則課題問題)
      * [Uncle Bernie's rule (バーニーおじさんのルール)](#uncle-bernies-rule-バーニーおじさんのルール)
      * [日本語の記事を探してみた](#日本語の記事を探してみた)
      * [英語の記事を調べてみた](#英語の記事を調べてみた)
      * [まとめ](#まとめ)
      * [AIの種類](#aiの種類)
         * [汎用AI](#汎用ai)
         * [特化型AI](#特化型ai)
         * [弱いAI/強いAI](#弱いai強いai)
         * [機械学習/強化学習](#機械学習強化学習)
            * [教師あり学習：乱暴に言うと正解ラベルがついているやつ](#教師あり学習乱暴に言うと正解ラベルがついているやつ)
            * [教師なし学習](#教師なし学習)
            * [強化学習](#強化学習)
            * [決定木](#決定木)
            * [変数の種類](#変数の種類)
         * [線形回帰](#線形回帰)
         * [分類](#分類)
         * [次元削減](#次元削減)
         * [アンサンブル(ensemble)学習](#アンサンブルensemble学習)
         * [ニューラルネットワーク(neural network)の過学習を防ぐための手法](#ニューラルネットワークneural-networkの過学習を防ぐための手法)
      * [機械学習の学習基盤](#機械学習の学習基盤)
         * [活性化関数](#活性化関数)
            * [Softmax function](#softmax-function)
            * [定義と数式](#定義と数式)
            * [Pythonコード](#pythonコード)
         * [ディープラーニング(Neural Network) アルゴリズム(Algorithms)](#ディープラーニングneural-network-アルゴリズムalgorithms)
   * [【Python】専門書や論文を読みたいけど数学が苦手・わからない人向けのコードを読んで学ぶ数学教本](#python専門書や論文を読みたいけど数学が苦手わからない人向けのコードを読んで学ぶ数学教本)
      * [1. 数学記号](#1-数学記号)
         * [1.1 総和](#11-総和)
         * [1.2 総乗](#12-総乗)
         * [1.3 Let's try!](#13-lets-try)
      * [2. Vector(ベクトル)](#2-vectorベクトル)
         * [2.1 ベクトルとは](#21-ベクトルとは)
         * [2.2 ベクトルの加法・減法](#22-ベクトルの加法減法)
         * [2.3 ベクトルとスカラーの積](#23-ベクトルとスカラーの積)
         * [2.4. ベクトルとベクトルの積](#24-ベクトルとベクトルの積)
            * [2.4.1 Hadamard product(アダマール積)](#241-hadamard-productアダマール積)
         * [2.4.2. 内積](#242-内積)
         * [2.4.3. 外積](#243-外積)
      * [2.5. L1norm(ノルム)、L2norm(ノルム)](#25-l1normノルムl2normノルム)
      * [2.6. Let's try!](#26-lets-try)
      * [3. 行列](#3-行列)
         * [3.1. 行列とは](#31-行列とは)
   * [Neural_Network](#neural_network)
   * [h1 size](#h1-size)
      * [h2 size](#h2-size)
         * [h3 size](#h3-size)
            * [h4 size](#h4-size)
               * [h5 size](#h5-size)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc)


# JDLA G検定直前_主要単語 
[【G検定直前】 主要単語をざっくり理解するシート 2020-11-23](https://qiita.com/ayahumohumo/items/d8feb9a05dfbbbc4862d)
```
※黒本と呼ばれる、G検定問題集に記載されているような過去問はほとんど出て来てない印象です。

人の名前を覚えるよりは、
強化学習のパラメータや各種機械学習関係の特徴や実装時に注意する点などを抑えるのが良いかと思います。

G検定のGはGoogleのG。
主要な単語や検索キーワードを頭に入れて試験中に検索できるように準備するのが大切だと思います。
```

## 人工知能の歴史  
**世界初のコンピュータENIAC(1946年) **

### 第一次ブーム(Boom)：探索、推論 (1956～1960年代)  
```
1956年、ダートマスワークショップ

・初めて、人工知能（Artificial Intelligence）という言葉が提唱される。
・数学の定理証明や、チェスを指す人工知能などが展示
```

### 第二次ブーム(Boom)：知識ベース (1980年代)  
```
・エキスパートシステム(expert system)
・MYCIN：医療診断
・有機化合物の特定
```

### 第三次ブーム(Boom)：機械学習、ディープラーニング (2012年頃) 
```
ウェブや計算機の性能向上により、第二次ブームで使われていた手法の発展形が登場、

IBM　Watoson　クイズ王
```

### ILSVRC（ImageNet large scale visual recognition challenge）  
```
大規模画像認識コンテスト。

画像認識、画像分類のコンテスト。
2012年に優勝したアルゴリズムなど、各年の優勝したアルゴリズムや特徴的なデータセットは抑えておくのが良さげ。
```

## 格言系
言うた人 | 内容 
------------------------------------ | ---------------------------------------------
ジョン・サール(John Rogers Searle)| 強いＡＩ（Strong AI ）弱いＡＩ（Weak AI）を提唱。中国語の部屋という思考実験を提唱。「…強いAIによれば、コンピュータは単なる道具ではなく、正しくプログラムされたコンピュータには精神が宿るとされる」
オレン・エツィオーニ(Oren Etzioni)| 「コンピュータが世界制覇するという終末論的構想は『馬鹿げている』としか言いようがない」としてシンギュラリティには懐疑的
ちなみに、当時のILSVRC優勝したモデルは「AlexNet」（Alex Krizhevsky & Ilya Sutskever & Geoffrey E. Hintonが作成した。その内の1人であるAlexの名前から来ている。） | 
福島邦彦 | CNNの原型ともいえる、単純型細胞と複雑型細胞の２つの細胞の働きを組み込んだモデルである「ネオコグニトロン」(Neocognitron)を提唱。

[人工知能に関わる著名人たち](https://freedomofselection.com/ai-gen/people/#toc14)
アラン・チューリング [Alan Mathieson Turing](https://freedomofselection.com/ai-gen/people/#toc1)
アドリュー・ウン [Andrew Ng](https://freedomofselection.com/ai-gen/people/#toc2)
アーサー・サミュエル [Arthur Lee Samuel](https://freedomofselection.com/ai-gen/people/#toc3)
エドワード・ファイゲンバウム [Edward Albert Feigenbaum](https://freedomofselection.com/ai-gen/people/#toc4)
イーロン・マスク [Elon Reeve Musk](https://freedomofselection.com/ai-gen/people/#toc5)
ダニエル・デネット [Daniel Clement Dennett III](https://freedomofselection.com/ai-gen/people/#toc6)
ジェフリー・ヒントン [Geoffrey Everest Hinton](https://freedomofselection.com/ai-gen/people/#toc7)
ヒューゴ・デガリス [Hugo de Garis](https://freedomofselection.com/ai-gen/people/#toc8)
イアン・グッドフェロー [Ian J. Goodfellow](https://freedomofselection.com/ai-gen/people/#toc9)
ジョン・マッカーシー [John McCarthy](https://freedomofselection.com/ai-gen/people/#toc10)
ジョン・サール [John Rogers Searle](https://freedomofselection.com/ai-gen/people/#toc11)
ジョセフ・ワイゼンバウム [Joseph Weizenbaum](https://freedomofselection.com/ai-gen/people/#toc12)
ユルゲン・シュミットフーバー [Jürgen Schmidhuber](https://freedomofselection.com/ai-gen/people/#toc13)
オレン・エツィオーニ [Oren Etzioni](https://freedomofselection.com/ai-gen/people/#toc14)
パトリック・ヘイズ [Patrick John Hayes](https://freedomofselection.com/ai-gen/people/#toc15)
レイ・カーツワイル [Ray Kurzweil](https://freedomofselection.com/ai-gen/people/#toc16)
ゼップ・ホフレイター [Sepp Hochreiter](https://freedomofselection.com/ai-gen/people/#toc17)
スティーブン・ホーキング [Stephen William Hawking](https://freedomofselection.com/ai-gen/people/#toc18)
スティーブン・ハルナッド [Stevan Robert Harnad](https://freedomofselection.com/ai-gen/people/#toc19)
ビル・ゲイツ [William Henry “Bill” Gates III](https://freedomofselection.com/ai-gen/people/#toc20)
ヤン・ルカン [Yann André LeCun](https://freedomofselection.com/ai-gen/people/#toc21)
ヨシュア・ベンジオ [Yoshua Bengio](https://freedomofselection.com/ai-gen/people/#toc22)

## 思考実験、経験則、課題／問題  
問題 | 概要
------------------------------------ | ---------------------------------------------
シンボルグラウディング（記号接地問題） | 記号システム内のシンボルを実世界の意味と結びつけることが困難であることを示した問題。認知科学者のスティーブン・ハルナッド（Stevan Harnad）が提唱
フレーム(frame)問題 | John McCarthy（ジョン・マッカーシー）氏とPatrick Hayes（パトリック・ヘイズ）が提起。Daniel Dennett（ダニエル・デネット）氏が論文で示した。人工知能が解く問題に対し、選択肢が多すぎる時に膨大な時間がかかる問題を示したもの
モラベックのパラドックス(Moravec's paradox) | ハンス・モラベックやマービン・ミンスキーらが、人間には簡単な感覚的に動くことが、機械にとっては非常に難しいということを示した。高度な推論よりも感覚運動スキルの方が多くの計算資源を要する。一歳時にもできること（歩くことの学習等）が機会にやらせるのはとてもむずかしいということ
中国語の部屋 | 中国語を理解できない人を小部屋に閉じ込めて、マニュアルに従った作業をさせるという内容。部屋の外にいる人間は「この小部屋の中には中国語を理解している人がいる」と考える
みにくいアヒルの子(《原題、(デンマーク)Den grimme Ælling》アンデルセンの童話)定理 | 仮定（＝事前知識や偏向、帰納バイアス）がないと分類は理論上できないということ。主観／前提知識（暗黙の仮定）を排除して分類を試みたところでできないことを示している
ノーフリーランチ(No Free Lunch)定理 | David H. Wolpertが提唱した考え方。 あらゆることに万能な機械学習モデルや探索／最適化のアルゴリズムなどは存在しないことを説き、数学的に証明した。。
グルーのパラドックス(grue paradox) | 法則や命題の正しさを確証するために、データや事例を枚挙してその証拠とするという実証科学的手続き（帰納法） に疑問を呈したもので、例えばある時間(20XX年まで緑のエメラルドが21XX年には青色）になるというやつ。
バーニーおじさんのルール(Uncle Bernie's rule) | ニューラルネットワークの重みパラメーターの数に対して、最低限その10倍以上の訓練データ量が必要とした経験則。古典的な位置づけでディープラーニングが登場以前からあるため、ディープラーニングにも応用できるのかは不明とされている。
Garbage In, Garbage Out | 不良データを入力すると、出来上がる機械学習モデルもゴミ

## Uncle Bernie's rule (バーニーおじさんのルール)
[バーニーおじさんのルール（Uncle Bernie's rule）とは？](https://atmarkit.itmedia.co.jp/ait/articles/2008/12/news015.html)
```
　機械学習におけるバーニーおじさんのルール（Uncle Bernie's rule）とは、
ニューラルネットワークの重みパラメーターの数に対して、
最低限その10倍以上の訓練データ量が必要となる、とする経験則のことである。
```

```
訓練データの数量の目安とされるが、定理ではなく、あくまで経験則である。
その出典（後述）も古く（＝最近のディープラーニングに適用できるかどうかは不明で）、
数学的に証明されているわけでもないので注意が必要だ。
```

<img src="https://image.itmedia.co.jp/ait/articles/2008/12/di-01.gif" width="600" height="400">  

## 日本語の記事を探してみた
[バーニーおじさんを探せ！ updated at 2018-11-25](https://qiita.com/HiroSnow0413/items/ab6b034bb50f3e53271e)
```
しょうもない質問なのですが、
「機械学習において学習に必要なデータ数は説明変数の数の10倍」
というバーニーおじさんのルールですが、
そもそもこのバーニーおじさんとはどなたなのでしょうか？気になります。

私はバーニーおじさんは初耳でしたが、気になりますね。
ネットで調べてみても、ほとんど情報は出てこないようです。
綴のあたりを付けて英語で検索したりもしましたけど、ヒットなし。
```

```
マジで誰？？？？？？検索してもG検定の関連情報しか出てこない。
「機械学習には、モデルのパラメータ数の10倍の学習データが必要」とのことだが、これ以上わからない。

英語でも調べてみたけどさらにわからない。
バーニーおじさんの消息をご存知の方、教えてください。
```

## 英語の記事を調べてみた  
```
Yaser Abu-Mostafa, he explains the relationship between dimension of a dataset and 
it's size required for any learning model to work.

As a general rule of thumb, size of dataset should be at-least about 10x it's dimension 
and should be independent of the model used.
```

```
Yaser Abu-Mostafaはデータセットの次元とサイズの関係について説明しています。
「経験則では、データセットの大きさは、少なくともその次元の10倍必要で、それぞれは独立していなければなりません」（適当訳）
```
[https://datascience.stackexchange.com/questions/14875/data-set-size-versus-data-dimension-is-there-a-rule-of-thumb](https://datascience.stackexchange.com/questions/14875/data-set-size-versus-data-dimension-is-there-a-rule-of-thumb)


```
So how much data is needed? Professor Yaser Abu-Mostafa from Caltech answered this question in his online course. 
The answer is, as a rule of thumb, you need roughly 10 times as many examples as there are degrees of freedom in your model.
```

```
では、どれくらいデータが必要なのでしょうか？Yaser Abu-Mostafaはオンライン講座でこの質問に対して、
「経験則では、モデルのパラメータの約10倍のデータが必要」と答えています。
```
[https://www.forbes.com/sites/forbestechcouncil/2018/11/19/do-you-have-enough-data-for-machine-learning/#d6aeaf552e2d](https://www.forbes.com/sites/forbestechcouncil/2018/11/19/do-you-have-enough-data-for-machine-learning/#d6aeaf552e2d)


```
失礼、カリフォルニア工科大学の教授であり、
機械学習の研究や教育に関する活動で有名な方をコレ呼ばわりして申し訳ございません。

おそらく、Yaser Abu-Mostafa教授がバーニーおじさんの正体ではないでしょうか？
```

## まとめ  
```
バーニーおじさんのルールは「機械学習において学習に必要なデータ数は説明変数（パラメータ）の数の10倍」ということが重要であって、「バーニーおじさんって誰や？」なんてことは重要ではないのです。ですが、気になったら調べたくなる気持ち、わかります。たまたま自分にとって、それがG検定の1時間前であっただけで調べてしまいました。

その中で、Yaser Abu-Mostafa教授という黒幕の存在が明らかになりました。

しかし、バーニーおじさんイコール教授なのか、教授の知り合いにバーニーおじさんがいたのか、謎は深まるばかりです。

もしかしたら、ナントカタスクゼイアン(Zoltaxian)の陰謀なのかもしれません（3回目）。
```

```
信じるか信じないかは、あなた次第！
```

## AIの種類
### 汎用AI  
```
汎用型人工知能（AGI：Artificial General Intelligence）

振る舞いに着目して、人間と同等のタスクをこなすことのできるAI

フレーム問題を打ち破ったAIのことを指すこともある。
```

### 特化型AI
```
特定の用途に特化したAI.
例えば、画像処理や自動運転、チェスや将棋などのボードゲームが挙げられる

フレーム問題を打ち破っていないAIのことを指すこともある。
```

### 弱いAI/強いAI  
```
哲学者ジョン・サールが提起した考え方

強いAI、人間の知能に迫るようになるか、人間の仕事をこなせるようになるか、
幅広い知識と何らかの自意識を持つようになったもの。 

弱いAI、自意識は持たず、特定の狭い領域の問題解決しかできないAI
```

### 機械学習/強化学習

#### 教師あり学習：乱暴に言うと正解ラベルがついているやつ  
```
主に、回帰と分類に大別できる。

　例：サポートベクターマシン(support vector machine, SVM)
```

#### 教師なし学習  
```
既知データの本質的な構造を導き出すことを目的にしたもの。

　クラスタリング(clustering)や、次元削減が例。
```

#### 強化学習  
```
エージェント(agent)が自身の収益を最大化するような行動指針を獲得する。Q学習などが有名。
```

#### 決定木  
```
決定木は、情報利得の最大化を実現するように決定する。

データのスケール(【scale)を事前に揃える必要はなく、分析結果の説明が容易な点が特徴として挙げられる。
```

[決定木](https://www.weblio.jp/content/%E6%B1%BA%E5%AE%9A%E6%9C%A8)
```
ある対象や課題を分類・予測・判定するための条件分岐のアルゴリズムを図式化した、木構造のグラフ。
意思決定や戦略立案のほか、機械学習やデータマイニングの分野で用いられる。

ある要素（親ノード）を起点として想定しうる結果を複数の要素（子ノード）の枝分かれで表し、条件分岐を繰り返したもの。
デシジョンツリー。
```

#### 変数の種類
名前 | 説明
------------------------------------ | ---------------------------------------------
目的変数 | 予測対象。従属変数や外的基準などともいう
説明変数 | 独立変数ともいう。物事の原因となる目的変数を説明する｜
スラック(slack)変数 | 最適化問題における、不平等式制約を等式制約に変換するために導入する変数のこと。サポートベクターマシン(: support vector machine, SVM)などに利用される。

### 線形回帰
```
単回帰分析と重回帰分析があり、

説明変数の一時関数であり、目的変数を予測する。

単一の説明変数を用いるのが単回帰。

重回帰分析は、相関の強い目的変数を同時に二つ用いると予測精度が悪化する。（多重共線性）
```

名前 | 説明
------------------------------------ | ---------------------------------------------
ロジスティクス回帰 | 対数オッズを線形回帰によって予測し、出力の正規化によって予測結果を確立として解釈する。


```
目的関数には、ヒンジ損失関数が用いられる。
最小化を行う関数のことを目的関数と呼び、ロジスティクス会期の場合は尤度関数が用いられる。
```

名前 | 説明
------------------------------------ | ---------------------------------------------
L1正則化 | 次元圧縮が目的。余分な説明変数を除くことを目的にしている。
L2正則化 | モデルの過学習を防ぐことを目的にした手法。
LASSO回帰 | 不要と判断された特徴量が自動的に消去される特徴ある。（L1正則化を施した回帰）
Ridge正則化 | パラメータ全体として大きくなりすぎないように抑制を行うことができる（L2正則化を施した回帰）

### 分類
```
kNN法とは、k最近傍法（k-Nearest Neighbor: kNN）

回帰や分類を行う際に、似たようなデータをk個集めてそれらの多数決から目的とする値を求める

欠点として、クラスのサンプル数の方よりに弱い。

k値はエンジニアが決めるパラーメタであり、ハイパーパラメータと呼ばれる。
```

### 次元削減 
```
情報をなるべく失わないようにデータを低次元に集約することをいう。

計算量の削減や、次元の呪いを回避することに期待できる。

主成分分析は、線形な次元削減。
```

名前 | 説明
------------------------------------ | ---------------------------------------------
寄与率 | 各成分の重要度
主成分を各成分の意味を推測することができる。


### アンサンブル(ensemble)学習 
```
複数回試行し各結果の平均を取ったほうがよい。

分類問題については経験的に、一つの強識別機を使うよりもバギングの性能が高くなる特徴がある。

バギング：データのいち部を使って何度も繰り返す方法。各モデルを並列に学習させることができる。

ブースティング、Boosting：データの一部から弱学習機を作り、繰り返し強学習機へと作っていく手法。　
各モデルを逐次的に学習させる、

ランダムフォレスト：バギングと決定木を組み合わせた手法。

過学習しやすいという弱点がある。
```

### ニューラルネットワーク(neural network)の過学習を防ぐための手法  
```
モデルを作る際に、外れ値やノイズまで学習することが多々ある。これが過学習（OverFitting)と呼ばれます。

正規化とは、パラメータのノルムが大きくなりすぎないようにすること。
```

## 機械学習の学習基盤  
```
 MLOps 　機械学習チーム/開発チーム　と運用チームが協力し実装から運用までのサイクルをすすめるための機械学習基盤を気づくことがある。
 AIOps 　IT運用のプロセスの一部にAIを適用することでさらなる自動化や効率化を期待する概念。
```

### 活性化関数  

問題 | 概要
------------------------------------ | ---------------------------------------------
ステップ関数 | 活性化関数として設定すると、単純パーセプトロンと全く同じ動きとなる。ν=0で部分できないためイマイチ
シグモイド関数 | ロジスティックシグモイド関数。ステップ関数と似ているが、なめらな微分関数として考案された。勾配消失問題に繋がりやすく近年余り見かけなくなっている。
ReLU関数 | 負の値が０で直線的に上昇する関数。勾配消失問題が発生しづらく、形も使いやすいため主流となっている
ソフトマックス(Softmax function)関数 | 出力の総和を１で正規化する。確率としての表現を整えることに利用されることの多い活性化関数。分類問題でいうところの出力層付近でよく利用される。
squash関数 | CapsNetに利用される活性化関数

#### Softmax function  
[［活性化関数］ソフトマックス関数（Softmax function）とは？](https://atmarkit.itmedia.co.jp/ait/articles/2004/08/news016.html)
```
　AI／機械学習のニューラルネットワークにおけるソフトマックス関数（Softmax function、もしくは正規化指数関数： Normalized exponential function）とは、複数の出力値の合計が1.0（＝100％）になるように変換して出力する関数である。各出力値の範囲は0.0～1.0となる。

　滑らかな（＝ソフトな）曲線となり、1つの出力値が最大となるため、「ソフトマックス関数」と呼ばれる。
```
<img src="https://image.itmedia.co.jp/ait/articles/2004/08/di-01.gif" width="600" height="300">  

#### 定義と数式  
```
冒頭では文章により説明したが、厳密に数式で表現すると次のようになる。
```
<img src="https://image.itmedia.co.jp/ait/articles/2004/08/di-capture01.png" width="300" height="200">  


```
　e（オイラー数）や、それに対応するnp.exp(x)という後述のコードについては、「シグモイド関数」で説明しているので、
詳しくはそちらを参照してほしい。オイラー数は、微分計算がしやすいというメリットがある。
具体的に上記の数式の導関数（Derivative function：微分係数の関数）を求めると、次のように非常にシンプルな式になる。
```
<img src="https://image.itmedia.co.jp/ait/articles/2004/08/di-capture02.png" width="300" height="200">  

#### Pythonコード
```
　上記のソフトマックス関数の数式をPythonコードの関数にするとリスト1のようになる。
なお、テンソル（多次元配列）の計算を簡単にするため、ライブラリ「NumPy」をインポートして使った。
```

```
import numpy as np

def softmax(x):
  if (x.ndim == 1):
    x = x[None,:]    # ベクトル形状なら行列形状に変換
  # テンソル（x：行列）、軸（axis=1： 列の横方向に計算）
  return np.exp(x) / np.sum(np.exp(x), axis=1, keepdims=True)

# 入力（x）と出力（y）の例
x = np.array([[1,0,0], [0,1,0], [0,0,1]]) 
y = softmax(x)
print(y)  # 以下のように出力される
# [[0.57611688 0.21194156 0.21194156]  # → 猫： 全部足すと「1.0」になる
#  [0.21194156 0.57611688 0.21194156]  # → 虎： Σ＝1.0
#  [0.21194156 0.21194156 0.57611688]] # → ライオン： Σ＝1.0
```

```
ソフトマックス関数の導関数（derivative function）のPythonコードも示しておくと、リスト2のようになる
```

```
# ※リスト1のコードを先に記述する必要がある

def der_softmax(x):
  y = softmax(x)                        # ソフトマックス関数の出力
  jcb = - y[:,:,None] * y[:,None,:]     # ヤコビ行列を計算（i≠jの場合）
  iy, ix = np.diag_indices_from(jcb[0]) # 対角要素のインデックスを取得
  jcb[:,iy,ix] = y * (1.0 - y)          # 対角要素値を修正（i＝jの場合）
  return jcb                            # 微分係数の行列（ヤコビ行列）を出力

der_y = der_softmax(x)
print(der_y)  # 以下のように出力される
# [[[ 0.24420622 -0.12210311 -0.12210311]
#  [-0.12210311  0.16702233 -0.04491922]
#  [-0.12210311 -0.04491922  0.16702233]]
#
# [[ 0.16702233 -0.12210311 -0.04491922]
#  [-0.12210311  0.24420622 -0.12210311]
#  [-0.04491922 -0.12210311  0.16702233]]
#
# [[ 0.16702233 -0.04491922 -0.12210311]
#  [-0.04491922  0.16702233 -0.12210311]
#  [-0.12210311 -0.12210311  0.24420622]]]
```

### ディープラーニング(Neural Network) アルゴリズム(Algorithms)  
[ディープラーニングアルゴリズム ディープラーニングとは](https://www.datarobot.com/jp/wiki/deep-learning/)

問題 | 概要
------------------------------------ | ---------------------------------------------
MLP| 入力層、隠れそう、出力層の全結合したディープニューラルネットワーク。
（多層パーセプトロン） | 
CNNL| 順伝型のニューラルネット枠。　入力が畳み込み層に入り、フィルタと画像との積和演算となるよう畳み込み演算を行う。その後、プーリング層に伝わって、平均値や最大値を用いてプーリング演算を行う。この手順を繰り返し、全結合層で出力を計算する。
(畳み込みニューラルネットワーク) | 
RNN| 時系列データ、前後のデータに意味があるデータに対してその特徴を学習するやつ。長期的な特徴を学習することや、時間ごとに重み付けを行うような手法は別である。
（再帰型ニューラルネット） | 
LSTM| 時系列データにおいてRNNより長期データの特徴を学習する。RNNの中間層をLSTM-Blockとして状態を記憶するMemory Cellと記憶したデータを適宜忘却するゲートに置き換えている。
（長短期記憶） | 
ResNet | 学習対象に入力差を使うことで、勾配消失問題を解消を目的にしたやつ
GAN| 教師なし学習に用いられる手法で、イアンぐっとフェローが考案。生成ネットワークが生成したイメージを識別ネットわー０区が教師データか生成ネットワークの出力物かを判断。生成ネットワークはより出力物を正確に識別できるような画像を生成する。
（敵対的生成ネットワーク） | 
Transfer learning | 学習させたモデルや重みを別のドメインで再利用し学習をする手法。０から集めるよりも少ないデータ数かつ訓練回数で精度がでることが知られている。
（転移学習） | 
DQN| Alphagoで利用された手法。強化学習における行動価値関数の値が高くなるように学習する手法を真似、Q学習をパラメータ追加した近似関数として表現しディープラーニングする手法。
（Deep Q-Network） | 
CapsNet | ニューロンでの計算を入出力共にベクトルで行うことで、データの位相空間情報を保持したカプセルという単位で特徴を学習するディープラーニング。CNNが相対的な位置関係の特徴を学習仕切れない問題に対応した。
NOLS | デーtあの中にあっても人が気づいていない、直接見えないパターンを特徴量として使用する。反射光を利用する手法。
GQN | 写真などの2次元画像から被写体となった3次元物体を推定する技術。
GNN | グラフ構造を入力とするニュ=ラルネットワーク。グラフ構造を行列で表現して入力として利用することで、CNNやオートエンコーダ、RNNに適応できる。
アテンション構造 | 入力の中で特に重要だと思われる要素にマーキングして重み行列の値や重要度に応じて動的に調整する仕組み。


****** 

---- | ------ 
------------------------------------ | ---------------------------------------------


# 【Python】専門書や論文を読みたいけど数学が苦手・わからない人向けのコードを読んで学ぶ数学教本
[【Python】専門書や論文を読みたいけど数学が苦手・わからない人向けのコードを読んで学ぶ数学教本 2021-11-10](https://qiita.com/PHVTuber/items/94577f506e78852180ca)  

## 1. 数学記号  
### 1.1 総和  
<img src="images/sigma_01.jpg" width="5200" height="100">  
```
ans = 0
for i in range(1,11):
     ans += 1
```

<img src="images/sigma_02.jpg" width="5200" height="100">  

```
N = 10
a = [i for i in range(1,N+1)] # a[0]=a_1, a[1]=a_2, .., a[N-1]=a_N

#総和
#sum(a)と等価な処理ですがfor文で書きます
ans = 0
for i in a:
    ans += i
```

<img src="images/sigma_03.jpg" width="5200" height="100">  

```
a = [[1,2],[3,4]] # a_{11}=a[0][0],a_{12}=a[0][1],a_{21}=a[1][0],a_{22}=a[1][1]
ans = 0
for i in range(2):
    for j in range(2):
        ans += a[i][j]
```

### 1.2 総乗  
<img src="images/pi_01.jpg" width="500" height="100">  

```
a = [1,2,3] # a[0]=a_1,a[1]=a_2,a[2]=a_3
ans = 1 # ここを0にしたらどんな配列をもってきても0になってしまうので初期値は1
for i in a:
    ans *= i
```

<img src="images/pi_02.jpg" width="500" height="100">  

```
a = [[1,2],[3,4]]
ans = 1
for i in range(2):
    for j in range(2):
        ans *= a[i][j]
```

### 1.3 Let's try!  
<img src="images/1_3_1.jpg" width="520" height="300">  

```
x = [[0,0,1],[1,0,0],[0,1,0]]
a = [[0,20,30],[20,0,10],[30,10,0]]
ans = 0
for i in range(3):
    for j in range(3):
        ans += x[i][j]*a[i][j]
```

<img src="images/1_3_2_1.jpg" width="520" height="300">  

<img src="images/1_3_2_2.jpg" width="520" height="300">  

```
a = [[1,2,3],[4,5,6],[7,8,9]]
ans = 0
for i in range(2):
    b = 1 # 初期値
    for j in range(3):
        b *= a[i][j]
    ans += b
```


## 2. Vector(ベクトル)
### 2.1 ベクトルとは  

### 2.2 ベクトルの加法・減法  
<img src="images/vector_01.jpg" width="600" height="200">  

```
a = [25,30,10000] # Aさん
b = [40,90,500] # Bさん
ans1 = [] # 加算
ans2 = [] # 減法
for i in range(3):
    ans1.append(a[i] + b[i])
    ans2.append(a[i] - b[i])
```

```
import numpy as np
a = np.array([25,30,10000]) # Aさん
b = np.array([40,90,500]) # Bさん
ans1 = a+b # 加算
ans2 = a-b # 減法
```

### 2.3 ベクトルとスカラーの積  
<img src="images/vector_02.jpg" width="600" height="200">  

```
c = 10 # スカラー
a = [25,30,10000] # Aさん
ans = []
for i in range(3):
    ans.append(c*a[i])
```

```
c = 2 # 人数
a = [25,30,10000] # Aさん
b = [40,90,500] # Bさん
ans = [] # 加算
for i,j in zip(a,b):
    ans.append(1/c*(i+j))
```

```
c = 2 # 人数
a = np.array([25,30,10000]) # Aさん
b = np.array([40,90,500]) # Bさん
ans = (1/c)*(a+b)
```

### 2.4. ベクトルとベクトルの積  

#### 2.4.1 Hadamard product(アダマール積)
<img src="images/vector_03.jpg" width="600" height="200">  

```
a = [25,30,10000]
b = [40,90,500]
ans = []
for i,j in zip(a,b):
    ans.append(i*j)
```

### 2.4.2. 内積  
<img src="images/vector_04.jpg" width="600" height="200">  

```
a = [25,30,10000]
b = [40,90,500]
ans = 0
for i,j in zip(a,b):
    ans += i*j
```

### 2.4.3. 外積
```
これは厄介で物理では頻出なのですが、外積(クロス積)を定義できない次元というのがあるため私が知る限りでは機械学習等で扱われません。今は知識だけに留めておくと良いでしょう。ここでは33次元ベクトル同士の外積を取り扱います。
```

<img src="images/vector_05.jpg" width="600" height="200">  

```
a = [25,30,10000]
b = [40,90,500]
ans = [a[2]*b[3]-a[3]*b[2],a[3]*b[1]-a[1]*b[3],a[1]*b[2]-a[2]*b[1]]
```

## 2.5. L1norm(ノルム)、L2norm(ノルム)
<img src="images/norm_01.jpg" width="500" height="200">  

```
a = [25,-30,100]
ans = 0
for i in a:
    ans += abs(i)
```

<img src="images/norm_02.jpg" width="500" height="200">  

```
a = [25,-30,100]
ans = 0
for i in a:
    ans += i**2
ans = (ans)**(0.5)
```

## 2.6. Let's try!  
<img src="images/vector_06.jpg" width="600" height="200">  

<img src="images/vector_07.jpg" width="600" height="200">  

```
a = [2,0,0]
b = [0,1,0]
c = [0,0,1]
d = [a[2]*b[3]-a[3]*b[2],a[3]*b[1]-a[1]*b[3],a[1]*b[2]-a[2]*b[1]]
ans = 0
for i,j in zip(c,d):
    ans += i*j
```

## 3. 行列  

### 3.1. 行列とは  
"" | Aさん | Bさん
----- | ------ | ------  
年齢 | 25 | 35
通勤時間(分) | 30 | 90

<img src="images/matrix_01.jpg" width="600" height="200">  

<img src="images/matrix_02.jpg" width="600" height="200">  

```
T = [[25,35],
     [30,90]]
```

```
c = [25,35] # 年齢
d = [30,90] # 通勤時間
T = [c,d]
```

* []()  

![alt tag]()
<img src="" width="" height="">  

```

```


# Neural_Network
[[筆記] 從無到有建立神經網路(neural network)](https://softnshare.com/neural-network-from-scratch/)
[Neural_Network_from_Scratch](https://aegeorge42.github.io/)

# h1 size

## h2 size

### h3 size

#### h4 size

##### h5 size

*strong*strong  
**strong**strong  

> quote  
> quote

- [ ] checklist1
- [x] checklist2

* 1
* 2
* 3

- 1
- 2
- 3





