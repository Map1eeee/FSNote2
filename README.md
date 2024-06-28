# FSNote2
## 创建开发机
<div align="center">
<image src="Note2_picture1.png"width="550"height="400">
</div>
  
## 环境配置
<div align="center">
<image src="Note2_picture2.png"width="400"height="125">
</div>
<div align="center">
<image src="Note2_picture3.png"width="550"height="600">
</div>

## 进入新环境，完成环境包安装
conda activate demo
<br>
<br> pip install huggingface-hub==0.17.3
<br> pip install transformers==4.34 
<br> pip install psutil==5.9.8
<br> pip install accelerate==0.24.1
<br> pip install streamlit==1.32.2 
<br> pip install matplotlib==3.8.3 
<br> pip install modelscope==1.9.5
<br> pip install sentencepiece==0.1.99

## 下载 InternLM2-Chat-1.8B 模型

按路径创建文件夹，进入对应文件目录
<div align="center">
<image src="Note2_picture4.png"width="450"height="100">
</div>

打开 /root/demo/download_mini.py 文件，copy以下代码： 
<div align="center">
<image src="Note2_picture5.png"width="550"height="300">
</div>

执行命令，下载模型参数文件：
<div align="center">
<image src="Note2_picture6.png"width="550"height="300">
</div>

## 运行cli_demo
双击打开/root/demo/cli_demo.py 文件，复制以下代码：

<div align="center">
<image src="Note2_picture7.png"width="550"height="700">
</div>
