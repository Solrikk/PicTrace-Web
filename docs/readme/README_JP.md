![ロゴ](https://github.com/Solrikk/PicTraceV2/blob/main/assets/images/promo/bee.jpg)

<div align="center">
  <h4>
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/README.md">⭐Anglais⭐</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_JP.md">Japonais</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_RU.md">Russe</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_FR.md">Français</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_GE.md">Allemand</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_AR.md">Arabe</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_ES.md">Espagnol</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_KR.md">Coréen</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_TR.md">Turc</a> |
    <a href="https://github.com/Solrikk/PicTraceV2/blob/main/docs/readme/README_CN.md">Chinois</a>
  </h4>
</div>

---

# PicTraceV2🔍

**_PicTraceV2_** は、**_OpenCV_** を使用したコンピュータビジョン、**_TensorFlow_** と **_ResNet50_** モデルによる深層学習、**_aiohttp_** を活用した非同期処理、および **_Selenium_** を使ったブラウザ自動化を駆使した高性能な画像マッチングプラットフォームです。PicTraceV2を使用すると、ユーザーは画像を直接アップロードしたり、URLを指定して、類似画像を見つけるために広範なデータベースを迅速にスキャンできます。非同期処理により、スムーズかつ高速なビジュアル検索が可能になり、ユーザー体験が向上します。

---

## 目次

- [特徴](#特徴)
- [使用技術](#使用技術)
- [はじめに](#はじめに)
  - [必要条件](#必要条件)
  - [インストール](#インストール)
  - [アプリケーションの起動](#アプリケーションの起動)
- [使い方](#使い方)
- [例](#例)
- [貢献](#貢献)
- [ライセンス](#ライセンス)
- [連絡先](#連絡先)
- [謝辞](#謝辞)

---

## 特徴

- **画像アップロードとURL入力:** ユーザーは画像を直接アップロードするか、URLを指定して検索できます。
- **高度な画像マッチング:** 深層特徴抽出と比較のためにResNet50モデルを活用。
- **非同期処理:** 複数の画像検索リクエストを同時に高速処理可能。
- **包括的な結果:** メタデータや類似スコアを含む詳細な情報を提供。
- **多言語サポート:** READMEは英語、ロシア語、ドイツ語、日本語、韓国語、中国語で利用可能。
- **ブラウザ自動化:** Seleniumを使用してYandexでの自動検索とデータ抽出を実現。

---

## 使用技術

- **Python 3.8+**
- **OpenCV:** コンピュータビジョンのタスクに使用。
- **TensorFlow & ResNet50:** 深層学習ベースの特徴抽出に使用。
- **aiohttp:** 非同期HTTPリクエストの処理に使用。
- **Selenium:** ブラウザの自動化とウェブスクレイピングに使用。
- **BeautifulSoup:** HTMLコンテンツの解析に使用。
- **PandasとOpenPyXL:** データ操作とExcelファイル生成に使用。
- **spaCy:** 自然言語処理に使用。
- **Scikit-learn:** TF-IDFベクトル化に使用。
- **Logging:** アプリケーションプロセスの詳細なログ記録に使用。

---

## はじめに

_PicTraceV2 は、画像の追跡と比較を効率化するために設計された強力なツールです。以下の手順に従い、環境を設定してアプリケーションを正常に起動してください。_
