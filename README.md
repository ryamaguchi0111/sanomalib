# sanomalib

`sanomalib` は Python で使う異常音検知ライブラリ (Sound Anomaly Detection Library) です。  
以下のような機能を提供します：
- 音声ファイルの読み込み・前処理 (normalize, trim_silence)
- Melスペクトログラム、MFCC 等の特徴抽出
- scikit-learn ベースの異常検知 (Isolation Forest, One-Class SVM など)
- PyTorch / PyTorch Lightning ベースの Autoencoder や VAE による異常検知
- 評価用メソッド (異常スコア分布の可視化, ROC 曲線計算)
- JSON / NPY ファイルの入出力

## インストール

```bash
# 例：pip でインストールする場合
pip install git+https://github.com/your-account/sanomalib.git
