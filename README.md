# ■MonitoringCamera

## 〇構成
- saveImg : キャプチャした画像・動画が保存される。
- 01_camera.py : Enterキーが押されるまで、webカメラで撮影してる映像を画面上に表示  
3行目の「cam = cv2.VideoCapture(0)」の部分で使用するカメラを選択可能。
- 02_monitoringCamera.py : Enterキーが押されるまで、動きを検知したら、画像を保存する。  
9行目の「th = 300」でしきい値を変更可能。  
- 03_monitoringVideo.py : Enterキーが押されるまで、動きを検知したら、指定した時間の動画を録画・保存する。  
動画撮影中に[qキー]を押すことで録画終了可能。  
「TIME_SET = 1」：分単位で録画時間を指定。  

## 〇バージョン情報
- python : 3.7.4
- opencv : 4.5.3

### 〇参考  
- https://news.mynavi.jp/article/zeropython-35/  
- https://algorithm.joho.info/programming/python/opencv-videowriter-py/  


