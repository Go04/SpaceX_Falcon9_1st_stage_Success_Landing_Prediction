# SpaceX_Falcon9_1st_stage_Success_Landing_Prediction\(SpaceX Falcon 9 1段目着陸成功予測)

このGitHubリポジトリには、IBMデータサイエンス プロフェッショナル認定（[Coursera](https://www.coursera.org/professional-certificates/ibm-data-science)）の最終課題として作成した、\
SpaceX Falcon 9の1段目着陸成功予測に関するJupyterノートブックと、スライドとしてまとめたPDFファイルが含まれています。

内容は、APIやウェブスクレイピングを利用したデータ収集、データ前処理、探索的データ分析（EDA）および機械学習モデルの構築が含まれます。\
また、Plotly Dashを使用したダッシュボードの作成や、Foliumを使ったインタラクティブな地理分析も行っています。\
下記はそれぞれのスクリプトの概要です。

### 【1. Space-X Data Collection API.ipynb】

SpaceXのAPIを使用してFalcon 9の打ち上げデータを収集し、着陸に関する情報を取得しています。このスクリプトでは、データを整理し、分析に使用できる形式に変換するための準備を行っています。\
使用しているライブラリ：requests（APIからデータを取得）、json（データの整形）、pandas（データフレームの操作）

### 【2. Space-X Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia.ipynb】

WikipediaからSpaceXのFalcon 9およびFalcon Heavyの打ち上げ記録をスクレイピングして、着陸の成功/失敗に関する情報を収集しています。\
使用しているライブラリ：requests（ウェブページを取得）、BeautifulSoup（HTML解析）、pandas（データ操作）

### 【3. Space-X Data Wrangling spacex.ipynb】

収集したデータの前処理（クリーニング）を行い、機械学習モデルに適した形式に変換しています。具体的には、欠損値の処理や不要なカラムの削除、変数のエンコーディングなどを行っています。\
使用しているライブラリ：pandas（データ操作）、numpy（数値計算）、matplotlib（可視化）

### 【4. Space-X EDA Using SQL.ipynb】

SQLを使用してSpaceXのデータベースからデータを抽出し、探索的データ分析（EDA）を行っています。これにより、データの傾向やパターンを発見し、着陸成功の予測に向けた分析が行えます。\
使用しているライブラリ：sqlite3（SQLデータベース操作）、pandas（データ操作）、matplotlib（可視化）

### 【5. Space-X EDA DataViz Using Pandas and Matplotlib - SpaceX.ipynb】

PandasとMatplotlibを使用してSpaceXのデータセットを可視化し、探索的データ分析（EDA）を行っています。グラフやチャートを通じて、データの傾向やパターンを視覚的に分析し、着陸成功予測に役立つインサイトを得ることを目的としています。\
使用しているライブラリ：pandas（データ操作）、matplotlib（データ可視化）、seaborn（高度な可視化）

### 【6. Space-X Launch Sites Locations Analysis with Folium-Interactive Visual Analytics.ipynb】

Foliumライブラリを使用して、SpaceXの打ち上げサイトの地理的な位置をインタラクティブに可視化しています。このスクリプトは、地理データを元に、各打ち上げサイトの位置や関連情報を地図上に表示し、視覚的に分析できるようにしています。\
使用しているライブラリ：folium（地理データの可視化）、pandas（データ操作）、geopandas（地理データ処理）

### 【7. Build an Interactive Dashboard with Plotly Dash - spacex_dash_app.py】

Plotly Dashを使用して、SpaceXの打ち上げデータをインタラクティブなダッシュボードとして可視化しています。このダッシュボードでは、ユーザーが選択した情報を基にデータを動的に表示し、視覚的に解析できるようにしています。\
使用しているライブラリ：dash（インタラクティブなウェブアプリケーションの作成）、plotly（データ可視化）、pandas（データ操作）

### 【8. SpaceX Machine Learning Prediction.ipynb】

収集したデータを基に機械学習モデルを構築し、SpaceXのFalcon 9着陸成功の予測を行っています。さまざまなアルゴリズムを適用して予測精度を評価し、最適なモデルを選定しています。\
使用しているライブラリ：scikit-learn（機械学習アルゴリズム）、pandas（データ操作）、matplotlib（可視化）、numpy（数値計算）
