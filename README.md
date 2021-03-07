# node-red-tello-sample

Node-RED と Tello の連携サンプルフロー

## 事前準備

ローカルの Node-RED に[node-red-contrib-tello](https://flows.nodered.org/node/node-red-contrib-tello)をインストールする

## Step1. 簡単な離着陸

<img src="https://github.com/Miura55/node-red-tello-sample/raw/main/imgs/step1.png" alt="step1" width="300">

inject ノードをクリックすると離陸を行い、5 秒待って着陸する。

## Step2. Dashboard を使った操縦

<img src="https://github.com/Miura55/node-red-tello-sample/raw/main/imgs/step2.png" alt="step2" width="300">
<img src="https://github.com/Miura55/node-red-tello-sample/raw/main/imgs/step2_dashboard.png" alt="step2_dashboard" width="300">

Dashboard を使って UI を使って Tello を操縦する。

サンプルの実行には、[node-red-contrib-dashboard](https://flows.nodered.org/node/node-red-dashboard)のダウンロードが必要。

## Step3. Tello 内蔵カメラを使ったストリーミング

<img src="https://github.com/Miura55/node-red-tello-sample/raw/main/imgs/step3.png" alt="step3" width="300">
<img src="https://github.com/Miura55/node-red-tello-sample/raw/main/imgs/step2_dashboard.png" alt="step3_dashboard" width="300">

Tello に内蔵されたカメラを使って Dashboard 上にストリーミング画面を追加する。

サンプルの実行には、node-red-contrib-dashboard 及び[node-red-contrib-custom-ffmpeg-video](https://flows.nodered.org/node/node-red-contrib-custom-ffmpeg-video)のダウンロードが必要。

node-red-contrib-custom-ffmpeg-video をインストールする前にパソコンで ffmpeg をセットアップする。
