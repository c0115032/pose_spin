# pose_spin
Openposeを用いたフィギュアスケートスピン画像の判定

## 概要
Openposeによって出力されたスピン画像とjsonファイルを用いてスピンの回転数とスピンの種類を出力する

## 説明
例として300枚程度のスピンpngファイル使ってグラフを出力しています。

ffmpegでフィギュアスケートの動画から画像を切り出し、Openposeによって出力した画像ファイルとjsonファイルを使っています。


## 環境
- python3.5.4
- opencv3.1.1

## 参考
Openposeについてはこちら:
[Openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)

ffmpegについてはこちら:
[ffmpeg](https://www.ffmpeg.org/)
