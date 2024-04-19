第 4 节课作业
记录复现过程并截图

基础作业（结营必做）
训练自己的小助手认知（记录复现过程并截图）

1.安装环境在intern-studio上面
```
# 如果你是在 InternStudio 平台，则从本地 clone 一个已有 pytorch 的环境：
# pytorch    2.0.1   py3.10_cuda11.7_cudnn8.5.0_0

studio-conda xtuner0.1.17

# 如果你是在其他平台：
# conda create --name xtuner0.1.17 python=3.10 -y

# 激活环境
conda activate xtuner0.1.17
# 进入家目录 （~的意思是 “当前用户的home路径”）
cd ~
# 创建版本文件夹并进入，以跟随本教程
mkdir -p /root/xtuner0117 && cd /root/xtuner0117

# 拉取 0.1.17 的版本源码
git clone -b v0.1.17  https://github.com/InternLM/xtuner
# 无法访问github的用户请从 gitee 拉取:
# git clone -b v0.1.15 https://gitee.com/Internlm/xtuner

# 进入源码目录
cd /root/xtuner0117/xtuner

# 从源码安装 XTuner
pip install -e '.[all]'
```
![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/4eb3a1fd-f3ee-471b-b541-1168633c7b95)

2. 前期准备
2.1 数据集准备
为了让模型能够让模型成我们想要的样子，我们就需要通过在微调数据集中大量掺杂这部分的数据。
![3](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/d45c8ff7-fafd-4358-b335-57268e87e098)

2.2模型准备
![4](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/e0b97f6c-0872-464f-88e8-b96066511f77)

2.3 配置文件选择
2.4 模型训练  
![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/ad20194e-75d8-4ba8-acf6-3597c5154b5d)
2.5 模型转换、整合、测试
![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/1c9e8397-11e2-471e-a6d1-531f457497c9)


2.6最后对话展示：
由于数据原因过拟合，训练出来了一个魔怔小助手
![8c07c6114b55cee77bd52214608071a](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/22403c30-d9a2-48c0-9889-c6ef9ec9a6a3)

等了一段时间后，小助手，又不太魔怔了
![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/5bd2e940-fb33-4450-b151-77247d0819ee)


进阶作业
将自我认知的模型上传到 OpenXLab，并将应用部署到 OpenXLab（优秀学员必做）
复现多模态微调（优秀学员必做）
OpenXLab 部署教程：https://github.com/InternLM/Tutorial/tree/camp2/tools/openxlab-deploy
