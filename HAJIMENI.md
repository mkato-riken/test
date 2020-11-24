AI数理科学入門
====
近年、医学研究・医療において数理・データサイエンス・AIの重要性が高まっており、多様なデータを適切なツールを用いて解析・解釈できるスキルが臨床・基礎を問わず求められている。
画像、時系列データなど様々なデータの扱いと解析ツールの使い方を実践的に学び、データサイエンスの基本的な考え方を身につける。

演習環境
====
- コーディング環境は[Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb?hl=ja)を利用（Googleアカウント必要）
- 演習問題は、GitHubで公開

Rを実行する為に
====
Google ColaboratoryでRを実行するには、下記のURLをクリックして、Jupyter Notebookを作成します。
https://colab.research.google.com/notebook#create=true&language=r

Google Driveとの連携
====
- Google Driveと連携
自分で作成したコードを保存する為、Google Driveと連携します。
Driveに保存しておくことで、再実行やプログラムの修正が可能になります。

1. Google ColaboratoryでJupyter Notebookを開き、次のコマンドをセルにコピー＆ペーストして実行します。
```
from google.colab import drive
drive.mount('/content/drive')
```
2. 実行すると認証を求められます。</br>
![認証画面](https://cdn-ak.f.st-hatena.com/images/fotolife/p/pytry3g/20180918/20180918194042.png "認証画面")

認証画面のリンク（https://accounts.google.com~~~~）をクリックして、Googleアカウントを選択。Google Drive File Streamから許可を求められるので、許可します。
表示されたコードを「Enter your authorization code:」の部分にコピー＆ペーストして認証完了すると、Google Drive内のファイルの読み書きができるようになります。


Document
====
（どういう形にするか？下記は100本KnockのREADMEの記載）

- doc配下に講義資料と設問PDF、設問HTMLを配置
- work配下に設問notebookを配置
- work/answer配下に解答例notebookを配置
- work/data配下に使用したデータを配置

Link
====
本コンテンツで参考にした書籍
- 【RとPythonで学ぶ[実践的]データサイエンス&機械学習】
  - https://www.amazon.co.jp/dp/429710508X/ref=cm_sw_em_r_mt_dp_L0fVFbCEDQQS2
  （サンプルデータのGitHubレポジトリにもリンク？）


LICENSE
====
- 全てのファイルはMITライセンスに従います
