# Hik_OpenCV_PeopleDetect
基于海康威视网络摄像头和OpenCV的人体识别

新手刚刚接触这些东西，代码写的很烂，就是把网上的代码东拼西凑的，也难免有错误。
但还是能运行的。
主要借鉴了这个博主的文档：
https://blog.csdn.net/qq_37541097/article/details/72566102

VS项目用了2个线程，一个获取网络摄像头的视频流，一个用来处理，他们之间通过链队列传递图像，没有使用互斥量。
Qt项目就是比VS的代码多了些GUI的东西其他没多少变化，不过没有用多线程，因为当时还没理解Qt的机制。。。┭┮﹏┭┮

