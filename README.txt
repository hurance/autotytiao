# autotytiao
v0.1 #1.22
1.使用须知：
自动化跳一跳由B站up主linhai156开源工程优化而成，
且保留原工程功能，注释掉get_site(image)即可
源：https://wwi.lanzoup.com/ie7RVz10jxi
2.使用本工程时必须保证安装cv,nump库
  pip install opencv-python
  pip install numpy
3.按照下列教程配置好adb
  https://tw511.com/a/01/37402.html
4.修改路径
os.system('adb pull /sdcard/01.png C:/Users/12531/Desktop/autotytiao')
5.必须先开始游戏，才能运行工程
