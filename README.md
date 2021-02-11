# WelcomeRace-HamoruKun
声楽のためのハモり練習アプリケーション

チューナー機能　＋　はもり生成

# 実現機能
・ピッチ検出　＋　カラオケバーのように音程を表示する

・矩形波生成（12音階）

・ハモリ生成（3度，5度）

# トレーニングモード
7秒ごとにランダムな音が流れてくるので、それに対してハモるとポイントが加点

・難易度（ずれの許容量）を変更可能

・ランダムな音の範囲は1オクターブ（上限下限を設定可能）

# 接待（ハモリ体験）モード
コンピュータがマイク入力に対してハモってくれるモード

デフォルトの設定では、3度と5度の音が順番になります。

単なるピッチシフトではなくフォルマント補正を行っているので、自然なハモリ生成が可能です。

（Worldという音声合成処理ライブラリを利用）

# 2人で練習モード
マイク入力を2つ使って2人のハモリ具合を検出

※デバイスが変わると動作しない可能性大

（実装環境では、USBマイクが1つとWO Micというスマホをマイクとして使えるアプリを使用していました。）
