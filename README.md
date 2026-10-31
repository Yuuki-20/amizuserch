# 「あみ図がなくて困っている」市場の調査

調査日：2026-10-31　対象：日本でかぎ針編み・棒針編みをする人（海外の比較データも含む）
調べ方：検索ワードを変えながら約200回検索し、5つの角度から集めた——①公的統計、②困りごとの直接の声、③代替手段と払う金額、④海外と若い世代の動き、⑤技術研究

> **データの確かさについて**
> この調査をした環境からは、官公庁サイト（stat.go.jp、e-stat.go.jp など）や各ページを直接開けなかった。
> 数値はすべて、検索エンジンが返した原典の抜粋や要約で確かめたもの。
> 各数値には確認度を付けた。**A**＝公式・一次資料の抜粋で数値を確認、**B**＝報道や二次資料で確認（複数一致を含む）、**C**＝出典が1つだけ・元データが不明。
> 資料に載せる前に、[11章](#11-原典で照合する表) の表を原典で確かめること。

---

## 1. 結論（推測を含む）

1. **国内の土台は約1,000万人。公的統計で言える。**
   - 総務省「社会生活基本調査」では、「編み物・手芸」をした人は2021年に **991万人（10歳以上の8.8%）**。
   - レジャー白書でも、2023年の「編物・織物・手芸」の参加率は8.6%とみられ（列の対応は未確定）、ほぼ同じ水準。
2. **2024年秋からのブームで、若い初心者が急に増えた。**
   - 新宿オカダヤ本店の毛糸売上は2年で約6倍、客数は2倍以上。増えたのは10代後半〜20代前半の女性。
   - 公的統計（2021年）は高齢の女性が中心でゆるやかに減っている姿のままなので、**今の実数は公的統計より多い**と推測する。
3. **「あみ図がない」は国内外とも構造的に起きている。** 困りごとの型は5つあり、証拠が最も強いのは2つ。
   - **型A（写真しかない）**：英語圏では、作品の写真から「この編み図はどこ？」と尋ねるための Reddit の場（r/crochetpatterns）に約31万人が集まっている。
   - **型E（AIで作った偽の作品画像）**：NBC や Guardian が報じ、コミュニティがルールで禁止するほど起きている。
4. **お金を払う人はいる。**
   - 既製のパターンは1枚500〜1,000円（$4〜6）。
   - 人に頼む代行は3,000円〜で、写真や英文から起こすと+3,000円の例がある。海外の代行は$5〜50。
   - 写真から編み図を作ると謳う海外アプリ YarnPal は、月の売上が約54万ドルと報じられた（C）。
5. **日本の記号図を出せる「写真→あみ図AI」は見つからなかった。**
   - 汎用AI（ChatGPT など）が作る編み図は目数が合わず、編めないことが繰り返し報じられ、学術ベンチマークでも確かめられている。
   - **目数を検算する仕組み**と**日本の記号図（JIS）で出すこと**の2つが、amizuAI ならではの強みになる。
6. **国内で困っている人は「数十万〜百数十万人」規模と推計する**（[8章](#8-推計日本で困っている人は何人か)。仮定が多いので幅は大きい）。

---

## 2. 困りごとの型と証拠の強さ

| 型 | 場面 | 証拠の強さ | 主な証拠 |
|---|---|---|---|
| **A. 写真しかない** | SNS・Pinterest で見た作品、店の既製品 | **強** | r/crochetpatterns は会員約31万人で、写真の編み図を探す投稿が中心（C）[^gummy]。r/crochet（約180万人）は「この編み図を探して」という投稿を別の場所へ移すルールを作った[^rcrochet]。Pinterest のリンク先に編み図がない「釣りピン」問題もある[^pin] |
| **E. AIで作った偽の作品画像** | 実在しない作品の編み図を探す、買っても写真どおりにならない | **強** | NBC News（2024年4月）：Etsy でAI画像を使う店が6店超。17件の出品のレビュー48件のうち、8件がAIを疑い、6件が写真と違う仕上がりの画像を載せていた[^nbc]。r/crochet は2025年5月にAI画像・AI編み図を禁止[^rcrochet]。判定専用のサブレディットもできた。Ribblr もAI画像を禁止している[^ribblr] |
| **B. 英文しかない／日本の図しかない** | 国内の人が英文パターンを読めない。海外の人が日本の記号図を読めない | **中** | 日本ヴォーグ社の『英語で編もう』シリーズが続いている[^nishimura]。高校生の研究のテーマにもなった[^ieice]。ChatGPT で英文パターンを読み解く方法の紹介が話題になった（ねとらぼ 2026年1月）[^netlab]。r/translator には日本の編み図の翻訳依頼がある[^translator] |
| **C. 形式が合わない** | 動画なら編めるのに編み図で挫折する。図だけ／文章だけでは分からない | **中** | 日本文芸社『かぎ針編みの 編み図が読めるようになる本』は、「本やキットの編み図は難しすぎて挫折した」という声から企画され、**1か月で4刷・11,000部**[^bunkei]。英語圏の掲示板の投票では「文章＋図」が521票中331票（C）[^cville] |
| **D. 自分で図にしたい** | 作家・講師・キット販売者が清書したい | **中〜弱** | 誠文堂新光社『エクセルで編み図をつくる』（2026年1月）[^excel]。編み図作成アプリ amu は App Store 評価2.9（22件）[^amu]。FIT2022 の研究も「初心者には編み図のデザインが困難」と書いている[^fit] |

**欠けている証拠：** Yahoo!知恵袋、X、Threads、Instagram のコメントといった**日本語の生の声は、今回の検索では1件も拾えなかった**。声が少ないからではなく、検索の方法で拾えなかった可能性が高い。[10章](#10-次にやること)で直接集める。

---

## 3. 国内の土台（公的統計）

### 3.1 「編み物・手芸」をした人の数（総務省 社会生活基本調査）

| 調査年 | 行動者数 | 行動者率 | 確認度 |
|---|---|---|---|
| 2006 | 1,239万人 | – | B[^jbpress] |
| 2011 | 1,157万人 | – | B[^jbpress] |
| 2016 | 1,198万人 | 10.6% | A（率）[^stat2021en] |
| 2021 | **991万人** | **8.8%** | A（率）[^stat2021en][^ibaraki] |

- 行動者率＝10歳以上で、過去1年間にその活動をした人の割合。2021年調査は約17万人に聞いている。
- 「編み物・手芸」には刺しゅうなどが含まれる。**かぎ針・棒針だけの人数は公表されていない。**
- **65歳以上の女性は16.8%**（統計局「統計トピックス」。2006年調査とみられる）。全体の約2倍で、もともと高齢の女性が中心の趣味[^topics]。
- 京都府の解説：女性は減っており、男性はわずかに増えている。全体はゆるやかな減少傾向[^kyoto]。
- 都道府県別（2021年）：北海道10.7%、岩手10.5%、神奈川9.7%、沖縄6.7%（B）[^stats47]。
- **2026年10月に令和8年調査が行われた**[^stat2026]。2027年に結果が出れば、ブームでどれだけ増えたかを公的統計で示せる。

### 3.2 そのほかの公的・準公的データ

| 指標 | 数値 | 確認度 | 出典 |
|---|---|---|---|
| レジャー白書「編物・織物・手芸」（2023年分） | 抜粋に「8.6 / 26.6 / 13.0 / 9.9」と並んでいる。列が「参加率／年間活動回数／年間費用（千円）／参加希望率」の順なら、参加率8.6%、年26.6回、年1.3万円、希望率9.9% | C（列の対応が未確定） | 日本生産性本部[^leisure] |
| 家計調査「手芸・工芸材料」（2010年） | 二人以上の世帯で年896円。単身の女性は年1,101円 | B | J-Net21（元データは総務省）[^jnet] |
| ホビー白書のクラフト市場（2013年） | 8,673億円（手芸・趣味工芸を含む広い定義） | B | 日本ホビー協会の資料を引いた記事[^bridge] |
| 手芸業界全体の市場規模（2020年ごろ） | 約830億円（上とは定義が違う） | B | 日本ホビー協会の専務理事の発言[^toyokeizai] |

---

## 4. ブームの実態（業界・報道のデータ）

| 指標 | 数値 | 時期 | 確認度 |
|---|---|---|---|
| 新宿オカダヤ本店の毛糸売上 | 2023年比 **約6倍**、前年比 約2倍 | 2025年 | B[^itmedia][^yahoo] |
| 同店（ユザワヤも） | 前年の3倍ペース。**客数は2倍以上** | 2024年10月〜 | B[^senken] |
| ユザワヤの毛糸関連 | +50% | 2024年11月〜 | B[^senken] |
| パンドラハウス | 毛糸 +30〜50%、かぎ針など用品 +50% | 2025年 | B[^senken] |
| 客層 | **2024年秋から10代後半〜20代前半の女性が急増** | 2024年秋〜 | B[^senken] |
| 100円ショップの毛糸 | 品切れが相次ぎ、メーカーが正規品での購入を呼びかけた | 2025年2月 | B[^jcast] |
| フェリシモの手芸キット | 2年で約1.9倍 | 〜2026年 | B[^itmedia] |

- ブームのきっかけは SNS（LE SSERAFIM の SAKURA さんの投稿など）[^jprime]。
- 新しく始めた人は**SNS で見た作品をかぎ針で作る**。つまり最初から「写真しかない」状態（型A）にいる。

---

## 5. 海外の動き（市場の広がり）

| 指標 | 数値 | 確認度 |
|---|---|---|
| 米国：縫製・かぎ針・ニードルワークをした成人 | **12%（2022年）**。成人人口に当てはめると約3,000万人（縫製を含むので上限） | A〜B（NEA SPPA）[^nea] |
| 米国：かぎ針を好む人（毛糸で何かを作る人のうち） | 51%（棒針29%）。かぎ針をしない人の65%が「習いたい」（2017年） | B（Craft Yarn Council）[^cyc] |
| 英国：棒針・かぎ針をする人 | 720万人（2013年）→ 約750万人（2014年推計） | B（UK Hand Knitting Association）[^ukhka] |
| Etsy で検索される順位：「crochet pattern」 | **123位（2025年Q3）→ 7位（2026年Q3）** | B（eRank の推計）[^erank] |
| 英国 Hobbycraft | かぎ針製品のオンライン売上 +98%、「crochet pattern」の検索 +87%（2024年） | B[^hobbycraft] |
| 米国 Michaels | 棒針・かぎ針などの検索 +136%（6か月）、糸関連の売上 +40%（2026年） | B（同社のIR資料）[^michaels] |
| Pinterest | **「Japanese crochet bag」の検索 +380%**（2024年秋、豪州版） | A（Pinterest 公式）[^pinterest] |
| TikTok #crochet | 約150億回再生（時期不明）。工芸の中で1位 | B[^tiktok] |
| 中国 小紅書 | かぎ針関連の話題の閲覧が30億回超。**あみ図の販売が商売になっている** | B〜C[^red] |
| 韓国の大手編み物材料店 | オンライン売上に占める20〜30代：33.4%（2018年）→ 54.3%（2020年） | B[^kb] |
| 世界の編み物・かぎ針市場 | 2025〜2030年に138.4億ドル増える（年7.2%） | C（調査会社によって定義がばらばら）[^technavio] |

- **台湾は日本の JIS 系の記号を使い、中国も記号図（図解）が主流**。「文字が読めなくても記号が読めれば編める」と言われる[^taiwan]。日本式の記号図は東アジアで共通に通じ、英語圏でも「記号は国際語」と評価する声がある[^shiny]。

---

## 6. 代替手段とお金を払う意思

| 手段 | 費用 | 時間 | 弱点 |
|---|---|---|---|
| 似た既製パターンを買う | Etsy の中央値 $3.84〜5.99（C）[^etsyprice]、BOOTH ¥550〜1,000[^booth] | すぐ | 欲しい作品と一致しない。AIで作った偽物もある |
| 本・雑誌 | 1,430〜1,870円 | すぐ | 載っている作品しか作れない |
| 国内の代行（ココナラ） | 3,000円〜。**写真・英文から起こすと+3,000円**の例（棒針）[^coconala] | 数日〜 | かぎ針を写真から起こす出品は見つからなかった |
| 海外の代行（Fiverr・Etsy） | $5〜50、ときに$100[^fiverr] | 2日〜3週間 | 英語だけで、日本の記号図はない。品質にばらつき |
| 教室で教わる | 1,000〜3,000円／回 | 数週間 | 通う必要がある |
| 自分で起こしてアプリで清書 | 無料〜月$5.50（Stitch Fiddle） | 数時間〜数日 | 目数を起こす作業は全部自分。amu の評価は2.9[^amu] |
| 汎用AI（ChatGPT など） | 無料〜月額 | 数分 | **目数が合わない。立体は失敗しやすい**（7章） |
| 写真AIアプリ（YarnPal、ArtPatt など） | 月$6.99〜9.99、年$39.99前後[^artpatt] | 数分 | 精度を検証した資料が無い。英語だけ。**日本の記号図は出せない** |

- **YarnPal は2026年1月の売上が約54万ドル**で、米国の iOS ライフスタイル部門の上位と報じられた（C）[^yarnpal]。写真から編み図を作るAIに、月額で払う人がすでにいる。
- 博報堂が社内で、写真から編み図と手順書を作るアプリを試作している[^hakuhodo]。

**価格の推測：** 1回の変換なら **500〜1,500円**（既製パターンより少し高く、代行の半額以下）。月額なら **800〜1,500円**（海外アプリの相場）が受け入れられやすい上限とみる。

---

## 7. 技術はまだ追いついていない

| 証拠 | 内容 |
|---|---|
| Guardian（2023年2月）[^guardian]、CNN（2023年7月）[^cnn] | ChatGPT が作った編み図は「呪われた（cursed）」と書かれた。立体は特に失敗する（例：イッカクのようなセイウチになった） |
| ABCrafty の比較検証[^abcrafty] | 4つのパターンのうち、成功したのは1つだけ。段が足りない、「表に返す」などの手順が抜けている |
| amigurumake-studio[^amigurumake] | 「AI は目数を数えず、次に来そうな行を出しているだけ」 |
| リベシティ（2026年9月）[^libe] | Copilot で作った模様編みの図は破綻していた |
| **CrochetBench**（arXiv 2511.09483、ACL 2026）[^crochetbench] | 6,085件で9つのAIモデルを評価した。**写真から「そのまま編める」手順を出すのが最も苦手。** 追加学習しても正しく編める率は上がらない |
| AAAI 2025 シンポジウム[^aaai] | 英文パターンを機械で検証できる書式に直す変換で、正解率は最良74% |

→ amizuAI は、中間データを1目ずつ展開して目数の整合を確かめ、エラーをAIに戻して直させる。**「目数が合わない」という汎用AIの一番の失敗をそのまま補う作り**で、これが差別化の根拠になる。

---

## 8. 推計：日本で困っている人は何人か

**すべて推計。仮定を変えれば数字は大きく動く。**

| 段階 | 値 | 根拠・仮定 |
|---|---|---|
| ① 編み物・手芸をする人 | 991万人（2021年） | 公的統計（A） |
| ② ブームでの上積み | +α（規模は不明） | 店の客数が2倍以上（B）。令和8年調査で確かめる |
| ③ うち、かぎ針・棒針で編む人 | 300万〜500万人 | **仮定**：①の30〜50%。米国では毛糸で何かを作る人の約半数がかぎ針派（B）[^cyc]。内訳の公的値は無い |
| ④ うち、この1年に「あみ図がなくて困った」人 | **約30万〜150万人** | **仮定**：③の10〜30%。英語圏の目安として、編み図探しの場（約31万人）は r/crochet（約180万人）の約17%（C）。若い初心者ほど写真から入るので、もっと高い可能性もある |
| ⑤ うち、お金を払ってでも解決したい人 | 未測定 | アンケートで確かめる（10章） |

- ④に、1回500〜1,500円で年に数回使うと仮定すると、**年に数億円〜十数億円**の規模になる（**推計**）。
- 海外では、同じ困りごとが米国の約3,000万人（上限）と英国の約700万人にある。日本式の記号図は東アジアでも通じる。**ここが将来の上積み**になる。

---

## 9. 法的な注意点

- 編み図や作品写真は、表現に創作性があれば著作物になり得る。一般的な編み方や目数といった技法は保護されないと一般に解されている。**編み図に絞った判例は見つからなかった。**
- 著作権法30条の私的使用は、自分で編むための個人利用が前提。**作ったあみ図の販売・配布には使えない。**
- 店によっては、編み図を「糸のセットを買った人だけ」に配るなど、契約で配布を限っている例がある[^amirisu]。
- 設計への示唆：
  - 画面と規約で「他人の作品から起こしたあみ図は個人利用に限る」と伝える
  - 共有や販売の機能を作るなら、自分の作品であることを確認する手順を入れる
  - 具体的な運用は弁護士に確認する

---

## 10. 次にやること

1. **日本語の生の声を直接集める**：X・Threads・Yahoo!知恵袋で「編み図 ありますか」「編み図 知りたい」「この作品 編み図」の件数を月ごとに数える。Instagram のかぎ針作品の投稿で、編み図を尋ねるコメントの割合を数える（100投稿くらいの抜き取りでよい）。
2. **アンケートで ④・⑤ を測る**：
   - この1年に、あみ図がなくて作るのを諦めた作品はあるか（回数）
   - そのとき手元にあったもの（写真／英文／文章／実物）
   - 記号図と英文のどちらが読めるか
   - 1回いくらなら払うか
3. **令和8年社会生活基本調査（2027年公表予定）が出たら、3.1の表を更新する。**
4. YarnPal など海外の写真AIアプリを実際に試し、目数の正しさを amizuAI と比べる。

---

## 11. 原典で照合する表

| 確かめたいこと | 原典 |
|---|---|
| 行動者率 10.6% → 8.8% | 統計局 https://www.stat.go.jp/data/shakai/2021/pdf/gaiyoua.pdf ／英語版 https://www.stat.go.jp/english/data/shakai/2021/pdf/activities2021.pdf |
| 男女別・都道府県別 | e-Stat 表93-2 https://www.e-stat.go.jp/stat-search/files?stat_infid=000032223421 |
| 年齢別の行動者数・平均行動日数 | e-Stat 表30-1-2、30-3-2（2021年）／2011年 sid=0003065107、0003065096 |
| レジャー白書の列の対応 | https://www.jpc-net.jp/research/assets/pdf/app_2024_leisure_pre.pdf （種目14の行） |
| 65歳以上の女性 16.8% | https://www.stat.go.jp/data/topics/topi244.html |

---

## 出典

[^stat2021en]: A｜総務省統計局 2021 Survey on Time Use and Leisure Activities（Knitting or embroidering 10.6 / 8.8） https://www.stat.go.jp/english/data/shakai/2021/pdf/activities2021.pdf
[^ibaraki]: A｜茨城県 令和3年社会生活基本調査結果報告（全国8.8%） https://www.pref.ibaraki.jp/kikaku/tokei/fukyu/tokei/betsu/syakai/syakaichor3/kodo.html
[^jbpress]: B｜JBpress（社会生活基本調査の行動者数の推移） https://jbpress.ismedia.jp/articles/-/86612?page=3
[^topics]: A｜総務省統計局 統計トピックス（高齢者の趣味・娯楽） https://www.stat.go.jp/data/topics/topi244.html
[^kyoto]: A｜京都府「統計ルーム」2026年3月 https://www.pref.kyoto.jp/tokei/monthly/tokeikyoto/documents/tkroom202603.pdf
[^stats47]: B｜stats47（社会生活基本調査の都道府県集計） https://stats47.jp/ranking/hobby-participation-rate-knitting
[^stat2026]: A｜総務省統計局 令和8年社会生活基本調査 https://www.stat.go.jp/data/shakai/2026/campaign/about/
[^leisure]: C｜日本生産性本部 レジャー白書2024 速報版の資料 https://www.jpc-net.jp/research/assets/pdf/app_2024_leisure_pre.pdf
[^jnet]: B｜中小機構 J-Net21「手芸用品店」 https://j-net21.smrj.go.jp/startup/guide/retail/14.html
[^bridge]: B｜THE BRIDGE（ホビー白書2014年版を引用） https://thebridge.jp/tag/pinkoi
[^toyokeizai]: B｜東洋経済オンライン https://toyokeizai.net/articles/-/381208
[^itmedia]: B｜ITmedia ビジネスオンライン 2026-03-08 https://www.itmedia.co.jp/business/articles/2603/08/news004_4.html
[^yahoo]: B｜Yahoo!ニュース エキスパート（矢野きくの） https://news.yahoo.co.jp/expert/articles/585e6d5041ae5414e74b34a86239db405cf3eafc
[^senken]: B｜繊研plus（FASHIONSNAP 転載）2025-08-02 https://www.fashionsnap.com/article/2025-08-02/senken-amimono-boom/
[^jcast]: B｜J-CAST ニュース 2025年2月 https://www.j-cast.com/2025/02/20501815.html
[^jprime]: B｜週刊女性PRIME https://www.jprime.jp/articles/-/37079
[^gummy]: C｜GummySearch r/crochetpatterns https://gummysearch.com/r/crochetpatterns/ （r/CrochetHelp 約13.8万人、年+48% https://gummysearch.com/r/CrochetHelp/ ）
[^rcrochet]: B｜r/crochet のルール変更の告知（2023年、2025年） https://lr.us.psf.lt/r/crochet/comments/17ded12/changes_to_question_rules_new_sub ／ https://r.datuan.dev/r/crochet/comments/1klab9i/chatgpt_other_ai_posts/
[^pin]: C｜Winding Road Crochet https://www.windingroadcrochet.com/how-to-find-free-patterns-on-pinterest-not-clickbait/
[^nbc]: A｜NBC News 2024-04-24 https://www.nbcnews.com/tech/tech-news/etsy-crochet-buyers-suspect-ai-made-images-used-sell-patterns-rcna145878
[^ribblr]: B｜Ribblr のコンテンツポリシー https://ribblr.com/contentpolicy
[^nishimura]: B｜西村知子『英語で編もう』（日本ヴォーグ社） https://resemom.jp/release/prtimes/20171205/38245.html
[^ieice]: A｜電子情報通信学会 ISS-SP-017（2023） https://www.ieice.org/~iss/jpn/Publications/issposter_2023/data/pdf/ISS-SP-017.pdf
[^netlab]: B｜ねとらぼ 2026年1月 https://nlab.itmedia.co.jp/cont/articles/3681188/
[^translator]: C｜r/translator https://redlib.hyperreal.coffee/r/translator/comments/1jr53hq/japanese_english_crochet_steps_and_pattern_from
[^bunkei]: A｜日本文芸社のプレスリリース https://koubo.jp/press-release/prtimes/c41489_r646 ／ https://koubo.jp/press-release/prtimes/c41489_r662
[^cville]: C｜Crochetville の投票 https://forum.crochetville.com/topic/15032-written-instructions-or-charts/
[^excel]: A｜誠文堂新光社『エクセルで編み図をつくる』 https://koubo.jp/press-release/prtimes/c12109_r1809
[^amu]: A｜App Store「amu – かぎ針編み図作成アプリ」 https://apps.apple.com/jp/app/id6480585316
[^fit]: A｜FIT2022 J-032 https://www.ieice.org/publications/conference-FIT-DVDs/FIT2022/data/html/program/pdf/J-032.pdf
[^nea]: A｜NEA Survey of Public Participation in the Arts 2022 https://www.arts.gov/sites/default/files/2022-SPPA-final.pdf
[^cyc]: B｜Craft Yarn Council https://craftyarncouncil.com/node/6
[^ukhka]: B｜Marketing Week（UK Hand Knitting Association のデータ） https://www.marketingweek.com/2014/12/09/brands-wage-wooly-wars-to-tap-into-rise-of-uk-knitters/
[^erank]: B｜eRank https://help.erank.com/blog/top-etsy-searches-q2-2026/
[^hobbycraft]: B｜Retail Times 2025年8月 https://retailtimes.co.uk/?p=158157
[^michaels]: B｜Michaels 2026 Creativity Trend Report https://d1io3yog0oux5.cloudfront.net/_6160d4bbb2db922e4922837040c88aff/michaelsnewsroom/db/287/2322/pdf/ir_news_article_pdf20260310-15753-16jfofh.pdf
[^pinterest]: A｜Pinterest Fall 2024 Trend Report（豪州版） https://newsroom.pinterest.com/en-au/news/the-pinterest-fall-2024-trend-report-aus/
[^tiktok]: B｜Gathered https://gathered.how/knitting-and-crochet/crochet/tiktok-viewers-hooked-craft
[^red]: C｜投中网 https://news.pedaily.cn/202601/560454.shtml ／新浪財経 https://finance.sina.cn/2026-03-07/detail-inhqcymr1752802.d.html
[^kb]: B｜KB Think https://kbthink.com/life/card/knitting.html
[^technavio]: C｜Technavio（GII） https://www.gii.tw/report/infi2056201-global-knitting-crochet-market.html
[^taiwan]: B｜東海大学（台湾）の手芸ノート https://physexp.thu.edu.tw/~mengwen/fancywork/01-03.pdf
[^shiny]: C｜Shiny Happy World https://www.shinyhappyworld.com/2012/11/want-to-discover-a-whole-new-world-of-patterns-try-reading-crochet-charts.html
[^etsyprice]: C｜SellerToolsHQ https://sellertoolshq.com/guides/how-to-sell-crochet-patterns-etsy/ ／ RankHero https://www.rankhero.com/keywords/crochet-pattern
[^booth]: B｜BOOTH https://booth.pm/ja/items/7213281
[^coconala]: B｜ココナラ https://coconala.com/services/133731 ／ https://coconala.com/services/1778871
[^fiverr]: B｜Fiverr https://www.fiverr.com/gigs/amigurumi-pattern
[^artpatt]: B｜ArtPatt の料金 https://artpatt.com/pricing
[^yarnpal]: C｜白鯨出海 https://www.baijing.cn/article/55487
[^hakuhodo]: B｜博報堂 https://www.hakuhodo.co.jp/aaas/atl/topics/detail/aicrochet.html
[^guardian]: B｜The Guardian 2023-02-27 https://www.pressreader.com/usa/the-guardian-usa/20230227/282102050869677
[^cnn]: B｜CNN 2023-07-08 https://www.cnn.com/2023/07/08/us/chatgpt-crochet-patterns-artifical-intelligence-cec/index.html
[^abcrafty]: C｜ABCrafty https://abcrafty.com/ai-crochet-patterns/
[^amigurumake]: C｜amigurumake-studio https://amigurumake-studio.com/why-ai-crochet-patterns-dont-work
[^libe]: C｜リベシティ https://library.libecity.com/articles/01M3Q0MAV8QNR5CKZWFCBAXCQ8
[^crochetbench]: A｜CrochetBench arXiv:2511.09483 https://arxiv.org/abs/2511.09483 ／ https://aclanthology.org/2026.acl-long.604.pdf
[^aaai]: A｜AAAI Symposium Series 2025 https://ojs.aaai.org/index.php/AAAI-SS/article/view/36054
[^amirisu]: B｜amirisu https://shop.amirisu.com/en/blogs/news/article-113
