# DSO-related
## 一. 准备工作
### 1.1 标定
#### 1.1.1 光度标定
通过光度定标，直接方法的性能得到了显著提高，而对于半直接和基于特征的方法，其性能取决于所使用的特征、相机响应函数和场景的整体亮度。理想情况下，应该采用主动相机控制[24]，以提供高质量图像的特征提取器和匹配器。对于直接法，当无法获得光度校准信息时，应使用在线校准方法[25]。
【paper】Challenges in Monocular Visual Odometry:Photometric Calibration, Motion Bias,and Rolling Shutter Effect

### 1.2 传感器
直接法和半直接法对卷帘门效果更敏感。但是当卷帘门效果不强，或者环境纹理较低时，卷帘门效果可能不再是决定性能的因素。
