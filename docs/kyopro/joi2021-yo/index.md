当日のムーブとか反省点とかをサラっと。

## 0. コンテスト前

春合宿特典で本選が確約されているので大して緊張はしなかった。

とは言え、予選落ち春erとなると相応の辱め（あんな事やこんな事や...）を受けるに違いないので、一応精進はしておいた（Mの趣味はないので）。

そもそも春合宿目指してる人が予選落ちは精神的に来るものがあると思う。精神も壊れ、人間関係も壊れ、そして信用も失い、最終的には(ry

11月頭に「11月中に難易度9を1周する！」とか言っておきながら結局終わらず、流石に予選前には終わらせる予定だったのだが今も終わっていない。それもこれもTwitterのせいである。遅くとも今週中には終わらせておきたい所だが、果たして...



## 1. コンテスト中のムーブ

### 1.1. 0:00 〜 0:30

取り敢えずA問題を開く。左右でAからの個数が同じ所でやれば良い事が分かったが、実装がかなりダルい。
デバッグとかで20分かけたが、WA。ここに来て、setで殴れば良いことに気づく（遅い）。
考察を詰める前に実装を始めて死ぬ事が最近多いので気をつけたい。

その後7分でAC。時間をかなりロスしてしまった。

### 1.2. 0:30 〜 1:00

B問題。BFS前処理をすれば良さそうなのはすぐに分かったが、stringでそのままやると3500msくらいかかったので数値で計算する事に。2489msで通す（犯罪）。

数値を10進数にしたのでmapで実装していたが、3進数にしていればlogが落ちてた。3時間中1時間をこの2問で使ってしまったのは痛い。

### 1.3. 1:00 〜 2:00

C問題にハマる。DPで最大値以外が有利になる場合があると思っていてK=0かで場合分けをした。

実は30分で満点解を実装していたのだが、これがACだと気づくのはだいぶ後である。色々とバグり、最後の小課題を除いた78点を獲得。

### 1.4. 2:00 〜 2:15

D問題を見ると、見るからに二分探索で嬉しくなる。壊れた電車と設定も似ていたしね

余剰の処理をミスって10分くらい溶かした。一番時間がかからなかった問題である。

### 1.5. 2:15 〜 2:30

取り敢えずEの小課題1を通した。

E問題を考えたり、C問題に戻ったりしていたが、ここで最大値を持ったDPが大丈夫か試してみようという気持ちになった（英断）。流石に通らないと思っていたら通り、余計な事を考えていた自分を呪った。

### 1.6. 2:30 〜 3:00

Eが2-SATっぽいので2-SATをしたがダメだった。悲しい...

結果、100+100+100+100+7=407点。

## 2. コンテスト後

Twitterを眺めていたら予想以上に全完が多くて厳しい気持ちに。

同期で407点の人がかなり多かった（anmichi, boutarou, osmium) 。中1のshiomusubi君が407点を取っていて、こわい。

本選までに難易度10を真面目にやらないと落ちそう。その前にTwitterをなんとかしなければ...