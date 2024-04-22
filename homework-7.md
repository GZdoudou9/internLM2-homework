1.基础作业
使用 OpenCompass 评测 internlm2-chat-1_8b 模型在 C-Eval 数据集上的性能

安装好环境后运行代码
```
python run.py --datasets ceval_gen --hf-path /share/new_models/Shanghai_AI_Laboratory/internlm2-chat-1_8b --tokenizer-path /share/new_models/Shanghai_AI_Laboratory/internlm2-chat-1_8b --tokenizer-kwargs padding_side='left' truncation='left' trust_remote_code=True --model-kwargs trust_remote_code=True device_map='auto' --max-seq-len 1024 --max-out-len 16 --batch-size 2 --num-gpus 1 --debug
```

![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/51e001de-a75a-4d3d-9741-cdb6faba7a9d)

![image](https://github.com/GZdoudou9/internLM2-homework/assets/129025105/463c0c4b-8109-4f49-8aa6-f4e5eec4ccb2)



2.进阶作业
将自定义数据集提交至OpenCompass官网
提交地址：https://hub.opencompass.org.cn/dataset-submit?lang=[object%20Object]
提交指南：https://mp.weixin.qq.com/s/_s0a9nYRye0bmqVdwXRVCg
Tips：不强制要求配置数据集对应榜单（ leaderboard.xlsx ），可仅上传 EADME_OPENCOMPASS.md 文档

欢迎扫码关注 OpenCompass 公众号了解更多评测相关知识～
