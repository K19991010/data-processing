1、split-txt.py是一个标注数据集划分文件
可以将xml、yolo格式的数据集按比例划分为训练集、验证集、测试集
  原始文件夹：
    绝对路径（或相对路径mydata）：
      --JPEGImages
      --Annotations
  生成文件夹：
    绝对路径（或相对路径datasets）：
      --images:
        --train
        --val
        --test
      --labels:
        --train
        --val
        --test
      --train.txt
      --val.txt
      --test.txt
txt文件中每一行信息代表每一张图片的存储路径

2、
