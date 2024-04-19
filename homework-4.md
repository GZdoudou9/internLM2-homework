第 4 节课作业
记录复现过程并截图

基础作业（结营必做）
训练自己的小助手认知（记录复现过程并截图）

1.安装环境在intern-studio上面
    ``` 
# 如果你是在 InternStudio 平台，则从本地 clone 一个已有 pytorch 的环境：
# pytorch    2.0.1   py3.10_cuda11.7_cudnn8.5.0_0

studio-conda xtuner0.1.17
![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/e7615798-6856-4f64-a531-69a0c7886bf4)

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



  
进阶作业
将自我认知的模型上传到 OpenXLab，并将应用部署到 OpenXLab（优秀学员必做）
复现多模态微调（优秀学员必做）
OpenXLab 部署教程：https://github.com/InternLM/Tutorial/tree/camp2/tools/openxlab-deploy
