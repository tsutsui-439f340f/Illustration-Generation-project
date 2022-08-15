# イラスト生成プロジェクト
本プロジェクトは個人的に行っており、2021/06/14より開始したプロジェクトです。

https://user-images.githubusercontent.com/55880071/184684067-da3c130b-89f7-4692-a177-aba88255f07d.mp4

## 概要
本プロジェクトの目的は高品質なイラストを生成するモデルの作成により、誰でも無料で高品質なイラストを手に入れられるようにすることです。
ネットライフが急速に発展し、イラストの立ち絵やアイコンを必要とする方が急増しました。
本プロジェクトは、その一助になればと思っております。

## イラスト生成の現状
現状イラスト生成は上半身までの生成はかなりできるようになっていますが、手の生成や服の細部の生成が微妙な状況です。
本プロジェクトでは、独自のイラストデータセットの構築を行いつつ、この問題の改善に取り組む予定です。
また将来的には全身生成にも取り組む予定です。

## 進行状況
現在(2022/08/01)において高品質なイラストデータを10000枚収集しており、データ保守も自動化しています。
また、顔生成に関しての前処理では、イラストの中から顔を検出するモデル(YOLOv3)の構築により顔切り出しの自動化をしています。
顔生成に関してStyleGAN3で行った結果、モード崩壊が起こることなく正常に学習できることを確認しています。

## サンプル
StyleGAN3生成画像(256x256)
学習時間:6日
batch_size:16\
![generation](https://user-images.githubusercontent.com/55880071/178160116-7894b631-c03a-431e-b6ed-7ef56e458eb6.PNG)


## データ収集状況
![image](https://user-images.githubusercontent.com/55880071/184685026-82597893-fdb4-422f-b271-4d8bb7c14afd.png)





## 備考
サブタスクとして背景除去、セグメンテーションに取り組む予定があります。
