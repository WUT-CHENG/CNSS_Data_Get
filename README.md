# CNSS_Data_Get

获取CNSS潮汐数据
# v0.2 2021-12-3 
不更了，可以用pyinstaller打包
在0.1版本的基础上进行修改，用户不再需要创建特定路径（为只有C盘的小伙伴们弄的）。
使用方法：
## 下载后不要动json和txt两个文件夹，直接按步骤运行，会在根目录生成result数据文件，请及时转移保存。
# V0.1
## 1.文件路径"D:\py prj\CNSS",里面有json和txt两个文件夹
用户需要自己创建
## 2.先运行CNSS2json
## 3.再运行json2txt
## 4.最后运行txt2sum
## 5.会在同级工程下生成一个result.txt
## 6.excel导入文本，逗号分隔，筛选转置
