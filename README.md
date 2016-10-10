# haifuri-ha-iizo
ANIPREX のサイトからはいふりのデフォルメキャラの画像ダウンロードするやつ。  
はいふりはいいぞ！  
  
## 使い方  
  
### 適当にディレクトリを作る。
% mkdir haifuri  
### ディレクトリに移動する。
% cd haifuri
### 下記コマンドを実行してダウンロード
% for i in `seq 1 32`; do  wget http://www.hai-furi.com/assets/img/common/face/img_$i.png;done;nom=1;for member in `cat member`;do mv img_$nom.png ${member}.png;nom=`expr $nom + 1`;done
### 適切な画像ソフトでひらいてもふもふする。  
