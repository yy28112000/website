旅行サイト構成

travel-site/
├── index.html                  ← GitHub Pagesのトップ
└── trips/
    ├── awajishima/
    │   └── index.html          ← 以前の淡路島ページ
    └── wakayama/
        └── index.html          ← 今回の和歌山ページ

GitHubでの使い方
1. 現在GitHub Pagesで公開しているリポジトリを開く
2. 今の淡路島 index.html を trips/awajishima/index.html に移す
3. このフォルダの index.html をリポジトリ直下に置く
4. trips/wakayama/index.html を追加
5. commit / push
6. GitHub PagesのURLを開く

次回旅行を追加する時
1. trips/ の中に新しいフォルダを作る
   例: trips/korea/index.html
2. ルートの index.html にカードを1つ追加する

リンク例:
<a class="trip" href="./trips/korea/">
  <div class="tag">KOREA · 3 DAYS</div>
  <h2>ソウル</h2>
  <div class="meta">カフェ、買い物、グルメ。</div>
  <div class="arrow">プランを見る →</div>
</a>
