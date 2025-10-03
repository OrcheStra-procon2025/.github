# OrcheStra
第36全国高等専門学校プログラミングコンテスト 自由部門応募作品「OrcheStra」のソースコードです。

## 概要
「OrcheStra」は、視覚・触覚・聴覚を用いて一人での指揮者体験を豊かにします。カメラから取得する骨格推定データを用いて画面上に指揮の動きと連携したエフェクトを表示し、指揮棒を振ることで音に対応した振動を発生させ、さらに、指揮に合わせて楽曲のテンポ・ボリュームを変化させることで、自らの演奏指揮を視覚・触覚・聴覚で体験することができます。

## レポジトリ構成
* [OrcheStra-device](https://github.com/OrcheStra-procon2025/OrcheStra-device)  
  デバイスに搭載するプログラムで、加速度センサより情報を取得し、WebSocketsを経由してWebアプリに送信します。
* [OrcheStra-app](https://github.com/OrcheStra-procon2025/OrcheStra-app)  
  指揮演奏を行うWebアプリケーションです。
* [Feedback-AI-Trainner](https://github.com/OrcheStra-procon2025/Feedback-AI-Trainner)  
  Webアプリケーション上で行う指揮のAIフィードバック機能のモデルを構築します。
