# STT-research

## DNN を使用した end-to-end の音声認識の一般的な流れ

音声
↓
音響特徴量(HMM ベースでは MFCC,DNN ベースでは log-mel spectrum が使用される https://arxiv.org/abs/1905.00078)
↓
音響特徴量を元に発話内容の文章を生成 (音響モデルと言語モデルに分けてもいい)

# やりたいことー

とりあえずhttps://arxiv.org/abs/2102.00291v1 これ試したい
BERT を Fine-tuning するだけ

# 気になるところ

Watson Speech to Text が使用している日本語話し言葉コーパスを使ってみたい(商用利用だと 2 年更新 50 万、無期限 500 万かかる)
https://www.ibm.com/jp-ja/cloud/watson-speech-to-text
