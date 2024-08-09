# MixTeX-Grading 新坑
AI for Grading, AI 批卷

Mix-合成数据混合真实数据

## TODO 1 合成数据集
随机问题穿插概率正确的手写答案
![4128aec25b925c601e5fce00afb0ee52](https://github.com/user-attachments/assets/b767dd88-4a8a-4c99-a82c-348cc031928f)
输入encoder：合成数据图片
输入decoder：答案文本
输出decoder：得分/总分 1. 错误-答案-扣分 2. 错误-答案-扣分。。。。
之后做好我们会把样本放在这里。

## TODE 2 真实数据集标注
输入encoder：真实场景下学生的试卷或者作业图片
输入decoder：答案文本
输出decoder：得分/总分 1. 错误-答案-扣分 2. 错误-答案-扣分。。。。
