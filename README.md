# GAU-alpha-pytorch
基于bert4torch框架，GAU-alpha的pytorch简洁实现

1. 本脚本全部基于[bert4torch](https://github.com/Tongjilibo/bert4torch)框架，主要是用pytorch复现[bert4keras](https://github.com/bojone/bert4keras)以及各种实例
2. 如果链接打不开，可能是因为源文件更新，可直接访问[bert4torch_example](https://github.com/Tongjilibo/bert4torch/tree/master/examples)
3. 欢迎[bert4torch](https://github.com/Tongjilibo/bert4torch)源项目

---
- [convert_GAU_alpha.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/convert_script/convert_GAU_alpha.py)：权重转换脚本
- [basid_language_model_GAU_alpha.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/basic/basid_language_model_GAU_alpha.py)：基础测试，测试[GAU-alpha](https://github.com/ZhuiyiTechnology/GAU-alpha)的MLM模型效果。
- [task_sentiment_classification_GAU_alpha.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/sentence_classfication/task_sentiment_classification_GAU_alpha.py)：任务例子，情感分类任务，加载GAU-alpha权重
