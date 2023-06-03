# Homework1.md

### 题目：基于RTMPose的耳朵穴位关键点检测

背景：

根据中医的“倒置胎儿”学说，耳朵的穴位反映了人体全身脏器的健康，耳穴按摩可以缓解失眠多梦、内分泌失调等疾病。耳朵面积较小，但穴位密集，涉及耳舟、耳轮、三角窝、耳甲艇、对耳轮等三维轮廓，普通人难以精准定位耳朵穴位。

### 任务
1. Labelme标注关键点检测数据集
2. 划分训练集和测试集
3. Labelme标注转MS COCO格式
4. 使用MMDetection算法库，训练RTMDet耳朵目标检测算法，提交测试集评估指标
5. 使用MMPose算法库，训练RTMPose耳朵关键点检测算法，提交测试集评估指标
6. 用自己耳朵的图像预测，将预测结果保存
7. 用自己耳朵的视频预测，将预测结果保存

需提交的测试集评估指标（不能低于baseline指标的50%）**

#### 目标检测Baseline模型（RTMDet-tiny）
![baseline-RTMDet-tiny](.pic/baseline-RTMDet-tiny.png)

#### 关键点检测Baseline模型（RTMPose-s）
![baseline-RTMPose-s](.pic/baseline-RTMPose-s.png)

#### 数据集
耳朵穴位关键点检测数据集，MS COCO格式，划分好了训练集和测试集，并写好了样例config配置文件
标注人：张子豪、田文博
![ear-dataset](.pic/ear-dataset.png)
