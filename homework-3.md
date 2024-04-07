基础作业 - 完成下面两个作业

1. 在茴香豆 Web 版中创建自己领域的知识问答助手
参考视频零编程玩转大模型，学习茴香豆部署群聊助手
完成不少于 400 字的笔记 + 线上茴香豆助手对话截图(不少于5轮)
（可选）参考 代码 在自己的服务器部署茴香豆 Web 版

答：线上茴香豆助手对话截图(不少于5轮)：

![2 1](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/00b490cf-d598-4f42-b708-07b152cd9725)

![2 2](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/d3644c93-fcae-4f4e-abd4-57aca6cac665)

![2 3](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/8b3b51a1-d073-4a52-887f-88e92a739c93)

![2 4](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/505653df-3d33-4221-92dc-94ebcf4419c9)
![2 5](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/474182ba-541b-458f-ad6f-0b2d42e703c1)
![作业1 1-上传](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/4e758bdd-eb74-41fb-95c4-ec483afffe22)


2.在 InternLM Studio 上部署茴香豆技术助手
根据教程文档搭建 茴香豆技术助手，针对问题"茴香豆怎么部署到微信群？"进行提问
完成不少于 400 字的笔记 + 截图

代码：
```
# 填入问题
sed -i '74s/.*/    queries = ["茴香豆怎么部署到微信群"]/' /root/huixiangdou/huixiangdou/main.py

# 运行茴香豆
cd /root/huixiangdou/
python3 -m huixiangdou.main --standalone

```

截图
![基本作业 1 2-2](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/a0884c8b-bba6-475c-a87e-dd4c6f4d8715)
