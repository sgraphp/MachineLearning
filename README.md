#Sample code
ref:https://github.com/Ferdib-Al-Islam/lstm-time-series-prediction-pytorch.git

#Overview
LSTMを用いた通貨レート（米ドル/円）の予測
datasetはhttps://fx.sauder.ubc.ca//data.htmlよりdownloadした．
通貨ペアは米ドルと(カナダドル，ユーロ，円，ポンド, オーストラリアドル, 元)の6種類
それぞれのデータを全結合層で1次元にした後に，LSTMに対してデータを渡している．
損失関数はAdamを使用 (実装時点）．
隠れ層数は16に設定（実装時点）．

#Role
実装 : 川畑 祐人

