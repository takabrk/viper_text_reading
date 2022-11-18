Linux application "Viper Text Reading"
Web site URL : http://vsrx.work
Created by takamitsu hamada
Updated November 18,2022


このアプリケーションを使うには、Pythonなどをインストールする必要があります。
「install_libraryapps」というシェルスクリプトがありますので、これを端末で起動させれば、必要なソフトウェアやライブラリをインストールします。

$ sudo apt install open-jtalk open-jtalk-mecab-naist-jdic mecab
$ sudo pip install mecab-python3

[動作環境]
・Ubuntu 22.04 LTS
・Python 3.10
・GTK+3
・libglade
・xfce4-terminal
・Open Jtalk
・open-jtalk-mecab-naist-jdic
・mecab
・mecab-python3

[主な機能]
・OpenJtalkを使ってコンピューターに喋らせる機能

[使い方]
端末などでstart.shを実行すると、アプリが立ち上がります。

./start.sh

テキストフォームにテキストを入力し、MODEから声を選択して「talk text」ボタンを押すと喋ります。また、予めテキストファイルを用意して、Select text fileからテキストファイルを選択し、「talk text file」ボタンを押すと録音をしながら文章を読み上げます。

