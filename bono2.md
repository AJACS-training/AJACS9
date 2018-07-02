[[AJACS9]]に戻る

----
目次

#contents
----
[[統合ホームページ>http://lifesciencedb.jp/]]中の項目でアイコン（これ→[[http://lifesciencedb.jp/image/small_video_icon.gif]]）があるサービスは統合TVの動画による説明があります。実際に使う前に是非ご覧ください。

* DNAデータベース総覧と検索、遺伝子発現バンク(GEO)目次の使い方 [#g1a242fa]

**[[DNAデータベース総覧と検索>http://lifesciencedb.jp/ddbj/]] [#n7e4b94d]
DDBJ/EMBL/GenBank（DNA塩基配列のデータベース）に登録されている全レコードをプロジェクト単位で分類。「生物種」と「研究の型」の二次元で分類。データを一括ダウンロード可能。&br;
[[http://lifesciencedb.jp/image/small_video_icon.gif]]  http://togotv.dbcls.jp/20080514.html を参照

- 【実習1】「生物群区分」で特定のカテゴリーを選ぶと、研究プロジェクト数が絞り込まれることで数が変化する。「生物群区分」で「ヒト」を選ぶ前と後で「研究の型別分類」の「機能RNA・RNAゲノム」の項目はいくつからいくつに変化するか？
- 【実習2】「生物群区分」で「ヒト」、「研究の型別分類」で「mRNA」を選んで得られる研究プロジェクトのリストを、「研究プロジェクトの一覧」を「サイズ順」にすることでデータサイズの大きなプロジェクト順に並び替えなさい。トップ３にランキングされる研究プロジェクトはそれぞれ何か？
-- 【参考】[[DDBJ のデータ公開形式 (flat file) の説明>http://www.ddbj.nig.ac.jp/sub/ref10-j.html]]
- 【実習3】統合ホームページ中の「ダウンロード」のタブをクリックすると、国内のゲノム・ポストゲノムプロジェクト配列データのダウンロードページに辿り着ける。この中から興味のあるプロジェクトを選び（例えば、シロイヌナズナ (Riken2004年)）、公開されている配列をFASTA形式で一括ダウンロードしなさい。
- 【応用1】上の実習でわずか数クリックで実現した一括ダウンロードできることのメリットは何か考えてみなさい。

**[[遺伝子発現バンク(GEO)目次>http://lifesciencedb.jp/geo/]] [#n7e4b94d]
-[[GEO>http://www.ncbi.nlm.nih.gov/projects/geo/]]（Gene Expression Omnibus:mRNA発現情報のデータベース）に登録されている全レコードをプロジェクト単位で分類。「生物種」、「研究の型」、「部位」の三次元で分類。データを一括ダウンロード可能。&br;
[[http://lifesciencedb.jp/image/small_video_icon.gif]]  http://togotv.dbcls.jp/20080623.html を参照

- 【実習4】「生物種」で特定の種を選ぶと、研究プロジェクト数が絞り込まれることで数が変化する。「生物種」で「ヒト」を選ぶ前と後で「研究の型」の「GeneChip」(Affymetrixの発現アレイ)、「cDNAアレイ」、「オリゴアレイ」の項目はいくつからいくつに変化するか？また、「生物種」に「齧歯」を選ぶとそれぞれどうか？
- 【実習5】右上の検索フォームで'hypoxia'と入力して検索したあとで、「生物種」で「ヒト」、「研究の型」で「GeneChip」を選んで得られる研究プロジェクトのリストを表示せよ。「測定サンプル」のカラムの数字をクリックしてどのようなことが起こるか、確認してみよ。また、GSEで始まるGEOのエントリ（例えばGSE4725）をクリックするとNCBIのサイトに直接アクセスできるので、そのページにアクセスせよ。

*** GEO本体 [#c528c6af]
- 【実習6】'Query DataSets for GSE4725'のリンクをクリックし、出てきた画面でGDSで始まるエントリ（DataSets; この場合、GDS3112）を表示せよ。すると、データセットブラウザが表示され、各種解析がウェブブラウザ上で可能となる。'Find genes that are up/down for this condition(s): 'で、'stress'だけをチェックして'Go'ボタンを押すことで、酸素濃度の違いで発現が変化している遺伝子群を抽出し、それぞれの発現プロファイルを確認せよ。

- 遺伝子発現情報データベース NCBI Gene Expression Omnibus (GEO) の使い方 [[http://lifesciencedb.jp/image/small_video_icon.gif]] http://togotv.dbcls.jp/20081218.html
- NCBI GEOの使い方2 遺伝子プロファイルを検索する [[http://lifesciencedb.jp/image/small_video_icon.gif]] http://togotv.dbcls.jp/20090213.html
- NCBI GEOの使い方3 データセットブラウザを使い倒す [[http://lifesciencedb.jp/image/small_video_icon.gif]] http://togotv.dbcls.jp/20090221.html 
- NCBI GEOの使い方4 データセットブラウザをさらに使い倒す [[http://lifesciencedb.jp/image/small_video_icon.gif]] http://togotv.dbcls.jp/20090307.html

*** ヒト統合ボディーマップ [#o9e5b91e]
5種類のヒト発現データ (iAFLP, Affymetrix GeneChip, EST, SAGE-NCBIのタグマップ, SAGE-大久保研独自タグマップ)に対して対応するNCBIのUniGene(ユニジーン)でデータを整理。対象生物種はヒトのみだが、複数の手法による客観的な遺伝子発現データの比較が可能。
http://okubolab.genes.nig.ac.jp/bodymap_i/
- ヒト統合ボディーマップ 1.発現パターンから探す [[http://lifesciencedb.jp/image/small_video_icon.gif]] http://togotv.dbcls.jp/20090204.html
- ヒト統合ボディーマップ 2.染色体領域で眺める、他 [[http://lifesciencedb.jp/image/small_video_icon.gif]] http://togotv.dbcls.jp/20090218.html

*** Bodymap-XS [#t8951966]
分類学と解剖学による動物のESTカウント数データの統合サイト。
http://bodymap.jp/
- Bodymap-XSを使い倒す [[http://lifesciencedb.jp/image/small_video_icon.gif]] 
http://togotv.dbcls.jp/20090210.html

*** 植物ESTボディーマップ [#uf67137e]
植物の各臓器、組織における遺伝子の発現量をESTを使って推定したデータベース。
http://lifesciencedb.jp/bodymap-plant/
-  植物ESTボディーマップを使い倒す [[http://lifesciencedb.jp/image/small_video_icon.gif]] 
http://togotv.dbcls.jp/20090328.html
