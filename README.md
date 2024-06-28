# FSNote2
## 创建开发机
<div align="center">
<image src="Note2_picture1.png"width="550"height="400">
</div>
  
## 环境配置
studio-conda -o internlm-base -t demo
与 studio-conda 等效的配置方案
conda create -n demo python==3.10 -y
conda activate demo
conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia
