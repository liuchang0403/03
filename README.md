# 03
## 03年掌纹识别实现   
p为正确的预处理结果，因代码里的预处理效果有些问题，故代码里直接使用该预处理结果进行之后的操作。      

运行顺序：先运行picpalmcode提取库内所有样本palmcode，然后运行compare得到类间和类内距离数据并保存，最后运行roc进行绘图。   
