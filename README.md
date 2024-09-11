# vae_autoencoder--for-Anomaly-Detection
這個作品呈現了如何利用影像辨識技術和變分自編碼器（VAE Autoencoder）來實作商品瑕疵檢測。透過使用無瑕疵商品圖像的訓練集，訓練AutoEncoder生成正常商品的圖像。而在測試集中存在正常與瑕疵商品，透過計算輸入圖像與重建圖像的誤差，誤差大的被定義為誤差區間來進行瑕疵檢測。



