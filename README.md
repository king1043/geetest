# geetest
极验滑块验证码破解



思路：
1.直接用Selenium模拟点击按钮
2.识别滑动缺口的位置,利用原图和缺口图对比检测方式来识别缺口的位置，通过遍历俩张图片，找出相同位置像素RGB差距超过此阀值的像素点，那么此像素点的位置就是缺口的位置。
3.模拟拖动滑块,模拟人的移动轨迹通过验证，一般是先加速后减速。



核心代码不便公开 selenium封装可以参考 
