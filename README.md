# pdf2ppt

引用https://github.com/phasedOut/pdf2pptx 做的jpg合并成ppt

引用https://www.cnblogs.com/loveprogramme/p/11247037.html 做的pdf切割成jpg



## 目录

- jpgs：保存分割出来的jpg
- result：保存最终生成的ppt
- source_files：保存想要转变成ppt格式的pdf（会历遍这个文件夹里面所有的文件，**里面只能放pdf文件！**）
- requirements.txt：保存运行需要的包

## 使用方法

**sources_files文件夹里面只能放pdf文件！！！！**

将requirements.txt里面的包都下载下来，可以用以下 下载全部：

```
pip install -r requirements.txt -i https://pypi.douban.com/simple
```

或者这样一个一个安装：
```
pip3 install 包名
```


把想要改成ppt的pdf都放到source_files里面，然后直接

```
python pdf2ppt.py
```
