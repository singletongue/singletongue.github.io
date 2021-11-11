[English CV](./english_cv.html)

# Masatoshi Suzuki

鈴木正敏（すずき・まさとし）

博士（情報科学）。2021年東北大学大学院情報科学研究科博士後期課程修了。現在、株式会社 Studio Ousia ソフトウェアエンジニア。

- Twitter [@fivehints](https://twitter.com/fivehints)
- GitHub [@singletongue](https://github.com/singletongue/)

## 略歴

2021/06--現在: 東北大学 データ駆動科学・AI教育研究センター 学術研究員
2021/04--現在: [株式会社 Studio Ousia](https://www.ousia.jp/ja/) ソフトウェアエンジニア
2019/05--2021/03: [理化学研究所 革新知能統合研究センター](https://www.riken.jp/research/labs/aip/) [言語情報アクセス技術チーム](https://www.riken.jp/research/labs/aip/goalorient_tech/lang_inf_access_tech/index.html) 研修生
2019/04--2021/03: [日本学術振興会 特別研究員](https://www.jsps.go.jp/j-pd/index.html)（DC2）
2018/04--2021/03: [東北大学 大学院情報科学研究科](https://www.is.tohoku.ac.jp/) 博士後期課程（修了）
2018/04--2021/03: [東北大学 学際高等研究教育院](http://www.iiare.tohoku.ac.jp/) 博士研究教育院生
2016/04--2018/03: 東北大学 大学院情報科学研究科 博士前期課程（修了）
2016/04--2018/03: [公益財団法人 尚志社](https://www.shoshisha.or.jp/) 奨学生
2010/04--2016/03: 東北大学 工学部情報知能システム総合学科（卒業）
2007-04--2010/03: 宮城県仙台第一高等学校（通信制課程を卒業）

## 研究活動

### [AI王 〜クイズAI日本一決定戦〜](https://sites.google.com/view/project-aio/home)

国内における質問応答研究の活性化を目的とした、解答者がすべて人工知能のクイズ大会。第1回は20択クイズを題材に、言語処理学会第27回年次大会 (NLP 2021) におけるワークショップにて開催。第2回は選択肢なしのクイズを題材に、2021年度開催。

## 公開リソース

### [日本語 BERT 訓練済みモデル](https://github.com/cl-tohoku/bert-japanese)

日本語版 Wikipedia をコーパスに用いて訓練した、汎用言語モデル BERT の訓練済みモデル。MeCab (ipadic) と WordPiece で単語分割したモデルと、文字単位で単語分割したモデルの2種類を公開中。自然言語処理ライブラリの [Transformers](https://github.com/huggingface/transformers) でも訓練済みモデルとして[利用可能](https://huggingface.co/transformers/pretrained_models.html)。

### [日本語 Wikipedia エンティティベクトル](https://github.com/singletongue/WikiEntVec)

日本語版 Wikipedia をコーパスに用いて訓練した、単語とエンティティの分散表現。記事本文中の記事間リンクおよび言及をそのエンティティを表すシンボルとみなし、負例サンプリング付き Skip-gram により分散表現を学習したもの。

## 論文・発表

### 論文誌

1. <u>鈴木正敏</u>, 松田耕史, 大内啓樹, 鈴木潤, 乾健太郎. データ指向型アプローチによるクローズドブック質問応答. 自然言語処理, Vol.28, No.1, pp.3--25, March 2021. [DOI](https://doi.org/10.5715/jnlp.28.3)
1. <u>Masatoshi Suzuki</u>, Koji Matsuda, Satoshi Sekine, Naoaki Okazaki, Kentaro Inui. A Joint Neural Model for Fine-Grained Named Entity Classification of Wikipedia Articles. IEICE Transactions on Information and Systems, Vol. E101.D, No.1, pp.73--81, January 2018. [DOI](https://doi.org/10.1587/transinf.2017SWP0005)

### 国際会議論文（査読あり）

1. <u>Masatoshi Suzuki</u>, Koji Matsuda, Satoshi Sekine, Naoaki Okazaki, Kentaro Inui. Neural Joint Learning for Classifying Wikipedia Articles into Fine-grained Named Entity Types. In Proceedings of the 30th Pacific Asia Conference on Language, Information and Computation (PACLIC 30), October 2016. [論文PDF](https://www.aclweb.org/anthology/Y/Y16/Y16-3027.pdf)
1. <u>Masatoshi Suzuki</u>, Koji Matsuda, Satoshi Sekine, Naoaki Okazaki, Kentaro Inui. Fine-Grained Named Entity Classification with Wikipedia Article Vectors. In 2016 IEEE/WIC/ACM International Conference on Web Intelligence (WI 2016), October 2016. [DOI](https://doi.org/10.1109/WI.2016.0080)

### 国内会議論文（査読なし）

1. <u>鈴木正敏</u>, 松田耕史, 大内啓樹, 鈴木潤, 乾健太郎. オープンドメイン質問応答における解答可能性判別の役割. 言語処理学会 第27回年次大会 (NLP 2021), March 2021. [論文PDF](https://www.anlp.jp/proceedings/annual_meeting/2021/pdf_dir/A5-4.pdf) <u>**委員特別賞**</u>
1. <u>鈴木正敏</u>, 鈴木潤, 松田耕史, 西田京介, 井之上直也. JAQKET: クイズを題材にした日本語QAデータセットの構築. 言語処理学会 第26回年次大会 (NLP 2020), pp.237--240, March 2020. [論文PDF](https://www.anlp.jp/proceedings/annual_meeting/2020/pdf_dir/P2-24.pdf)
1. <u>鈴木正敏</u>, 松田耕史, 大内啓樹, 鈴木潤, 乾健太郎. クイズ解答タスクにおける大規模ラベルなしコーパスの利用: 言語モデルとデータ拡張. 情報処理学会 第241回自然言語処理研究会 (IPSJ-SIGNL), August 2019. <u>**優秀研究賞**</u>
1. <u>鈴木正敏</u>, 松田耕史, 大内啓樹, 鈴木潤, 乾健太郎. クイズ解答タスクにおける大規模ラベルなしコーパスの利用: 言語モデルとデータ拡張. 第14回NLP若手の会 シンポジウム (YANS 2019), August 2019. [ポスターPDF](https://drive.google.com/open?id=1VMHfRDImNnva9yAk4c1QtgQDAfhznaMw)
1. 松田耕史, <u>鈴木正敏</u>, 乾健太郎. Wikidata からの遠距離教師あり学習に基づく大規模関係知識獲得. 言語処理学会 第25回年次大会 (NLP 2019), pp.659--662, March 2019. [論文PDF](http://anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P3-38.pdf)
1. 佐藤拓海, 大内啓樹, 松田耕史, <u>鈴木正敏</u>, 鈴木潤, 乾健太郎. 強化学習によるプログラム⽣成のためのプログラム系列分析. 言語処理学会 第25回年次大会 (NLP 2019), pp.1010--1013, March 2019. [ポスターPDF](http://anlp.jp/proceedings/annual_meeting/2019/pdf_dir/E5-2.pdf)
1. 阿部香央莉, 佐藤志貴, 佐藤拓海, 藤井諒, 松田耕史, <u>鈴木正敏</u>, 山口健史, 赤間怜奈, 大内啓樹, 鈴木潤, 乾健太郎. Zunkobot: 複数の知識モジュールを統合した雑談対話システム. 人工知能学会 言語・音声理解と対話処理研究会 (SLUD) 第84回研究会（第9回対話システムシンポジウム）, Vol.B5, No.02, pp.112--117, November 2018.
1. <u>鈴木正敏</u>, 松田耕史, 岡崎直観, 乾健太郎. 読解による解答可能性を付与した質問応答データセットの構築. 言語処理学会 第24回年次大会 (NLP 2018), pp.702--705, March 2018. [論文PDF](http://anlp.jp/proceedings/annual_meeting/2018/pdf_dir/C4-5.pdf) <u>**若手奨励賞**</u>
1. 関根聡, 安藤まや, 小林暁雄, 松田耕史, <u>鈴木正敏</u>, Duc Nguyen, 乾健太郎. 「拡張固有表表現＋Wikipedia」データ（2015年11月版Wikipedia分類作業完成版）. 言語処理学会 第24回年次大会 (NLP 2018), pp.504--507, March 2018. [論文PDF](http://anlp.jp/proceedings/annual_meeting/2018/pdf_dir/P4-5.pdf)
1. <u>鈴木正敏</u>, 松田耕史, 岡崎直観, 乾健太郎. Wikipedia を知識源に用いた文書検索と読解によるクイズ解答システム. 第12回NLP若手の会 シンポジウム (YANS 2017), September 2017.
1. 伊藤拓海, <u>鈴木正敏</u>, 田然, 山口健史, 岡崎直観, 乾健太郎. 自治体 QA サービスのための FAQ の自治体間の横断的解析. 第12回NLP若手の会 シンポジウム (YANS 2017), September 2017.
1. 関根聡, 安藤まや, 松田耕史, <u>鈴木正敏</u>, 乾健太郎. 「拡張固有表表現＋Wikipedia」データ. 言語処理学会 第22回年次大会 (NLP 2016), pp.41--44, March 2016. [論文PDF](http://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/P2-4.pdf)
1. <u>鈴木正敏</u>, 松田耕史, 関根聡, 岡崎直観, 乾健太郎. Wikipedia 記事に対する拡張固有表現ラベルの多重付与. 言語処理学会 第22回年次大会 (NLP 2016), pp.797--800, March 2016. [論文PDF](http://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/A5-2.pdf)
1. <u>鈴木正敏</u>, 松田耕史, 関根聡, 岡崎直観, 乾健太郎. Wikipedia エントリの拡張固有表現階層への自動分類. 第10回NLP若手の会 シンポジウム (YANS 2015), September 2015.

### そのほか（学会記事など）

1. 鈴木潤, 松田耕史, <u>鈴木正敏</u>, 加藤拓真, 宮脇峻平, 西田京介. ライブコンペティション：「AI 王～クイズ AI 日本一決定戦～」. 自然言語処理, Vol.28, No.3, pp.888--894, September 2021. [DOI](https://doi.org/10.5715/jnlp.28.888)
1. Sewon Min, Jordan Boyd-Graber, Chris Alberti, Danqi Chen, Eunsol Choi, Michael Collins, Kelvin Guu, Hannaneh Hajishirzi, Kenton Lee, Jennimaria Palomaki, Colin Raffel, Adam Roberts, Tom Kwiatkowski, Patrick Lewis, Yuxiang Wu, Heinrich Küttler, Linqing Liu, Pasquale Minervini, Pontus Stenetorp, Sebastian Riedel, Sohee Yang, Minjoon Seo, Gautier Izacard, Fabio Petroni, Lucas Hosseini, Nicola De Cao, Edouard Grave, Ikuya Yamada, Sonse Shimaoka, <u>Masatoshi Suzuki</u>, Shumpei Miyawaki, Shun Sato, Ryo Takahashi, Jun Suzuki, Martin Fajcik, Martin Docekal, Karel Ondrej, Pavel Smrz, Hao Cheng, Yelong Shen, Xiaodong Liu, Pengcheng He, Weizhu Chen, Jianfeng Gao, Barlas Oguz, Xilun Chen, Vladimir Karpukhin, Stan Peshterliev, Dmytro Okhonko, Michael Schlichtkrull, Sonal Gupta, Yashar Mehdad, Wen-tau Yih. NeurIPS 2020 EfficientQA Competition: Systems, Analyses and Lessons Learned. In Proceedings of the NeurIPS 2020 Competition and Demonstration Track, PMLR 133:86-111, August 2021. [論文PDF](http://proceedings.mlr.press/v133/min21a/min21a.pdf)

### 学位論文

#### 博士論文

Modeling Textual Entity Knowledge for Question Answering

#### 修士論文

情報検索と文章読解を組み合わせた質問応答システム [論文PDF](http://www.cl.ecei.tohoku.ac.jp/publications/2018/master_thesis_m-suzuki.pdf)

#### 卒業論文

Wikipedia 記事への拡張固有表現ラベルの多重付与 [論文PDF](http://www.cl.ecei.tohoku.ac.jp/publications/2016/msuzuki_bthesis.pdf)

## 受賞

1. 言語処理学会第27回年次大会 委員特別賞（2021年3月18日）
    - オープンドメイン質問応答における解答可能性判別の役割
1. 情報処理学会第241回自然言語処理研究会 優秀研究賞（2019年8月31日）
    - クイズ解答タスクにおける大規模ラベルなしコーパスの利用: 言語モデルとデータ拡張
1. 第1回対話システムライブコンペティション 優秀賞（2018年11月21日）
    - Zunkobot: 複数の知識モジュールを統合した雑談対話システム
1. 言語処理学会第24回年次大会 若手奨励賞（2018年3月12日）
    - 読解による解答可能性を付与した質問応答データセットの構築
1. 情報処理学会東北支部学生奨励賞（2016年3月12日）

## 資格

- TOEIC Listening & Reading Test 990点満点（2017年）
- TOEFL ITP テスト 623点（2013年）
- 実用英語技能検定 準1級（2010年）
- 日本漢字能力検定 準1級（2019年）
- [第5回謎解き能力検定](https://www.nazoken.com/) 準1級（2019年）
- [第6回謎解き能力検定](https://www.nazoken.com/) 準2級（2020年）
- [第7回謎解き能力検定](https://www.nazoken.com/) 準1級（2021年）

## クイズ番組出場歴

- TBS『東大王』（2020年9月23日放送）
    - 視聴者代表200人の一員として出場（1stステージ敗退）
- テレビ東京『サンドウィッチマンの脱落テスト！』（2020年7月13日放送）
    - 漢字がテーマの回で「伊達"日本人"軍」の一員として出場
- NHK BSプレミアム『たけしのこれがホントのニッポン芸能史』（2019年9月4日放送）
    - 番組内クイズ企画「クイズ！クイズ番組」に出場（1回戦敗退）
- フジテレビ『超逆境クイズバトル!! 99人の壁』（2017年12月31日放送）
    - 挑戦ジャンル「英語」で出場（センター進出はならず）
