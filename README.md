# ImageSearch
---------------------------
基于一些基础特征进行的图像搜索<br>
---------------------------
本代码支持的特征有：<br>
perceptual hash<br>
Otsu's method<br>
gray/RGB/YUV/HSV histograms<br>
HoG and LSH (built by Kmeans clustering)<br>
SIFT and LSH (built by Kmeans clustering)<br>
Dense SIFT<br>
---------------------------
相似度距离：<br>
Hamming distance (L0)<br>
Manhattan distance (L1)<br>
Euclidean distance (L2)<br>
---------------------------
相似度重排Re-ranking：<br>
Blending: mix results<br>
Ensembling: weighted sum<br>

运行方法：<br>
执行/util/prepare.py计算图库特征<br>
执行python main.py启动Tornado web serverb<br>
使用浏览器登录http://localhost:19999/cbir 进行搜索（主要搜索图片为车<br>
