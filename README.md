# 移動ロボットの自律走行シミュレーション研修

Linux（Ubuntu）上でC++を用いて，移動ロボットの自律走行のシミュレーションを作成する研修を行います．具体的には，

- PID制御を用いた円軌道，および点列で表現される軌道の追従
- パーティクルフィルタを用いた自己位置推定を行いながらの軌道追従

を実施します．なおこちらは，著者が2022年秋学期の授業で用いたものをまとめたものになります．



## 準備

本研修で用いたソースコードは，Ubuntu 20.04を用いて開発しました．確実に使用したい場合は，同じOSをご利用ください．ただし，C++を用いて開発されているので，他のLinuxディストリビューションやOSでも実行は可能といえます（検証はしていません）．

シミュレーション結果の描画にはgnuplotを用いているので，こちらも適宜インストールしてください．なお開発の時点で使用していたバージョンはgnuplot 5.2 patchlevel 8です．



## 進め方

まずはtext.pdfを読んでください．text.pdfの中に，いくつか演習としてプログラムの作成問題を設けてあります．このプログラムの作成に関しては，practiceディレクトリ内のソースコードを用いてください．practiceディレクトリ内のソースコードは，一部ソースコードが未記入の部分があるので，その部分を埋めてください．なお，srcディレクトリ内に解答の一例としてのソースコードがありますので，適宜参考にしてください．

text.pdf内にも書かれていますが，この研修はLinuxの端末の利用とC++に関して知識があることが前提となっています．これに関しては，こちらのQiitaのページ[【研究室向け】UbuntuでC/C++を用いたプログラミングの研修（ROSも）](https://qiita.com/NaokiAkai/items/27adbc71f94cd0e3a2c7)もご参考に頂ければ幸いです．
