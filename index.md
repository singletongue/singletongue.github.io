---
title: About
date: 2020-02-09 19:15
---

鈴木正敏（すずき・まさとし）

- 東北大学 [大学院情報科学研究科](https://www.is.tohoku.ac.jp/) [乾・鈴木研究室](https://www.nlp.ecei.tohoku.ac.jp/) 博士後期課程学生
- 東北大学 [学際高等研究教育院](http://www.iiare.tohoku.ac.jp/) 博士研究教育院生
- 日本学術振興会 [特別研究員](https://www.jsps.go.jp/j-pd/index.html) DC2
- 理化学研究所 [革新知能統合研究センター](https://www.riken.jp/research/labs/aip/) [言語情報アクセス技術チーム](https://www.riken.jp/research/labs/aip/goalorient_tech/lang_inf_access_tech/index.html) 研修生

## 研究内容

専門は自然言語処理。学部4年（2015年）より、質問応答システム、固有表現の分野の研究に取り組む。現在は主に、言語理解システムのクイズ問題を利用した開発・評価について研究中。

## 略歴

- 2019/05--現在: 理化学研究所 革新知能統合研究センター 言語情報アクセス技術チーム 研修生
- 2019/04--現在: 日本学術振興会 特別研究員（DC2）
- 2018/04--現在: 東北大学 大学院情報科学研究科 博士後期課程
- 2018/04--現在: 東北大学 学際高等研究教育院 博士研究教育院生
- 2016/04--2018/03: 東北大学 大学院情報科学研究科 博士前期課程（卒業）
    - 修士論文: 情報検索と文章読解を組み合わせた質問応答システム [論文PDF](http://www.cl.ecei.tohoku.ac.jp/publications/2018/master_thesis_m-suzuki.pdf)
- 2016/04--2018/03 公益財団法人 尚志社 奨学生
- 2010/04--2016/03: 東北大学 工学部情報知能システム総合学科（卒業）
    - 卒業論文: Wikipedia 記事への拡張固有表現ラベルの多重付与 [論文PDF](http://www.cl.ecei.tohoku.ac.jp/publications/2016/msuzuki_bthesis.pdf)
- 2007-04--2010/03: 宮城県仙台第一高等学校（通信制課程を卒業）

## 公開リソース

### [日本語 BERT 訓練済みモデル](https://github.com/cl-tohoku/bert-japanese)

日本語版 Wikipedia をコーパスに用いて訓練した、汎用言語モデル BERT の訓練済みモデル。MeCab (ipadic) とWordPiece で単語分割したモデルと、文字単位で単語分割したモデルの2種類を公開中。自然言語処理ライブラリの [Transformers](https://github.com/huggingface/transformers) でも訓練済みモデルとして[利用可能](https://huggingface.co/transformers/pretrained_models.html)。

### [日本語 Wikipedia エンティティベクトル](https://github.com/singletongue/WikiEntVec)

日本語版 Wikipedia をコーパスに用いて訓練した、単語とエンティティの分散表現。記事本文中の記事間リンクおよび言及を、そのエンティティを表すシンボルとみなし、負例サンプリング付き Skip-gram により分散表現を学習したもの。

## 論文・発表

### 論文誌

1. Masatoshi Suzuki, Koji Matsuda, Satoshi Sekine, Naoaki Okazaki, Kentaro Inui. A Joint Neural Model for Fine-Grained Named Entity Classification of Wikipedia Articles. IEICE Transactions on Information and Systems, 2018. [DOI](https://doi.org/10.1587/transinf.2017SWP0005)

### 国際会議論文（査読あり）

1. Masatoshi Suzuki, Koji Matsuda, Satoshi Sekine, Naoaki Okazaki, Kentaro Inui. Neural Joint Learning for Classifying Wikipedia Articles into Fine-grained Named Entity Types. In Proceedings of the 30th Pacific Asia Conference on Language, Information and Computation (PACLIC 30), 2016. [論文PDF](https://www.aclweb.org/anthology/Y/Y16/Y16-3027.pdf)
1. Masatoshi Suzuki, Koji Matsuda, Satoshi Sekine, Naoaki Okazaki, Kentaro Inui. Fine-Grained Named Entity Classification with Wikipedia Article Vectors. In 2016 IEEE/WIC/ACM International Conference on Web Intelligence (WI 2016), 2016. [DOI](https://doi.org/10.1109/WI.2016.0080)

### 国内会議論文（査読なし）

1. 鈴木正敏, 松田耕史, 大内啓樹, 鈴木潤, 乾健太郎. クイズ解答タスクにおける大規模ラベルなしコーパスの利用: 言語モデルとデータ拡張. 情報処理学会 第241回自然言語処理研究会 (IPSJ-SIGNL), 2019.
1. 鈴木正敏, 松田耕史, 大内啓樹, 鈴木潤, 乾健太郎. クイズ解答タスクにおける大規模ラベルなしコーパスの利用: 言語モデルとデータ拡張. 第14回NLP若手の会 シンポジウム (YANS 2019), 2019. [ポスターPDF](https://drive.google.com/open?id=1VMHfRDImNnva9yAk4c1QtgQDAfhznaMw)
1. 佐藤拓海, 大内啓樹, 松田耕史, 鈴木正敏, 鈴木潤, 乾健太郎. 強化学習によるプログラム⽣成のためのプログラム系列分析. 言語処理学会 第25回年次大会 (NLP 2019), 2019. [ポスターPDF](http://anlp.jp/proceedings/annual_meeting/2019/pdf_dir/E5-2.pdf)
1. 松田耕史, 鈴木正敏, 乾健太郎. Wikidata からの遠距離教師あり学習に基づく大規模関係知識獲得. 言語処理学会 第25回年次大会 (NLP 2019), 2019. [論文PDF](http://anlp.jp/proceedings/annual_meeting/2019/pdf_dir/P3-38.pdf)
1. 阿部香央莉, 佐藤志貴, 佐藤拓海, 藤井諒, 松田耕史, 鈴木正敏, 山口健史, 赤間怜奈, 大内啓樹, 鈴木潤, 乾健太郎. Zunkobot: 複数の知識モジュールを統合した雑談対話システム. 人工知能学会 言語・音声理解と対話処理研究会 (SLUD) 第84回研究会（第9回対話システムシンポジウム）, 2018.
1. 鈴木正敏, 松田耕史, 岡崎直観, 乾健太郎. 読解による解答可能性を付与した質問応答データセットの構築. 言語処理学会 第24回年次大会 (NLP 2018), 2018. [論文PDF](http://anlp.jp/proceedings/annual_meeting/2018/pdf_dir/C4-5.pdf)
1. 関根聡, 安藤まや, 小林暁雄, 松田耕史, 鈴木正敏, Duc Nguyen, 乾健太郎. 「拡張固有表表現＋Wikipedia」データ（2015年11月版Wikipedia分類作業完成版）. 言語処理学会 第24回年次大会 (NLP 2018), 2018. [論文PDF](http://anlp.jp/proceedings/annual_meeting/2018/pdf_dir/P4-5.pdf)
1. 鈴木正敏, 松田耕史, 岡崎直観, 乾健太郎. Wikipedia を知識源に用いた文書検索と読解によるクイズ解答システム. 第12回NLP若手の会 シンポジウム (YANS 2017), 2017.
1. 伊藤拓海, 鈴木正敏, 田然, 山口健史, 岡崎直観, 乾健太郎. 自治体 QA サービスのための FAQ の自治体間の横断的解析. 第12回NLP若手の会 シンポジウム (YANS 2017), 2017.
1. 鈴木正敏, 松田耕史, 関根聡, 岡崎直観, 乾健太郎. Wikipedia 記事に対する拡張固有表現ラベルの多重付与. 言語処理学会 第22回年次大会 (NLP 2016), 2016. [論文PDF](http://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/A5-2.pdf)
1. 関根聡, 安藤まや, 松田耕史, 鈴木正敏, 乾健太郎. 「拡張固有表表現＋Wikipedia」データ. 言語処理学会 第22回年次大会 (NLP 2016), 2016. [論文PDF](http://www.anlp.jp/proceedings/annual_meeting/2016/pdf_dir/P2-4.pdf)
1. 鈴木正敏, 松田耕史, 関根聡, 岡崎直観, 乾健太郎. Wikipedia エントリの拡張固有表現階層への自動分類. 第10回NLP若手の会 シンポジウム (YANS 2015), 2015

## 受賞

1. 情報処理学会第241回自然言語処理研究会 優秀研究賞（2019年8月31日）
1. 第1回対話システムライブコンペティション 優秀賞（2018年11月21日）
1. 言語処理学会第24回年次大会 若手奨励賞（2018年3月12日）
1. 情報処理学会東北支部学生奨励賞（2016年3月12日）

## 資格

- TOEIC Listening & Reading Test 990点満点（2017年）
- TOEFL ITP テスト 623点（2013年）
- 実用英語技能検定 準1級（2010年）
- 日本漢字能力検定 準1級（2019年）
- 第5回謎解き能力検定 準1級（2019年）

## クイズ番組出場歴

- フジテレビ『超逆境クイズバトル!! 99人の壁』（2017年12月31日放送）
    - 挑戦ジャンル「英語」で出場（センター進出はならず）
- NHK BSプレミアム『たけしのこれがホントのニッポン芸能史』（2019年9月4日放送）
    - 番組内クイズ企画「クイズ！クイズ番組」に出場（1回戦敗退）
