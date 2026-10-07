------------------   ^_^   ------------------
Light-Processor. V1.04
This program was written by Dawei Wen.
If you have any question, please contact:
E-mail: ontaii@163.com.
Google Scholar: https://scholar.google.com/citations?hl=ja&user=U13L9sEAAAAJ
Research Gate:  https://www.researchgate.net/profile/Dawei-Wen-2
------------------   ^_^   ------------------
程序1.04版（Light_Processor_v1.04.exe）
升级了显色指数计算的方法
test0.txt: Eu2+在某个氮氧化物中的发射光谱。数据间隔特殊。
test1.txt: Eu3+在某氧化物基质的发射光谱，数据间隔为1 nm。可用于流行cie软件检查本软件是否计算正确。
test2.txt: 其他波长vs强度数据为0且没有表示。
test3.txt: 蓝光LED+YAG:Ce3+的标准光谱。
test4.txt: 某近紫外LED+RGB粉的白光光谱。显色指数高。
test5.txt: 蓝光LED+OG粉的白光光谱。显色指数低。

程序1.03版
更名为Light-Processor
可计算光谱质心、面积、峰值波长、三刺激值和色坐标xy，相对色温CCT，显色指数。
1.算法小升级：可处理中间大量“缺失”的数据。这种数据不显示强度为0的部分，数据例子见test2.txt；
2.大升级：架构改变，可计算计算并输出色温CCT，显色指数，平均荧光寿命，色域面积。
test0.txt: 为1.02版本共同分享的0.01.txt文件。Eu2+在某个氮氧化物中的发射光谱。数据间隔特殊。
test1.txt: Eu3+在某氧化物基质的发射光谱，数据间隔为1 nm。可用于流行cie软件检查本软件是否计算正确。
test2.txt: 其他波长vs强度数据为0且没有表示。
test3.txt: 新增。蓝光LED+YAG:Ce3+的标准光谱。
test4.txt: 新增。某近紫外LED+RGB粉的白光光谱。显色指数高。
test5.txt: 新增。蓝光LED+OG粉的白光光谱。显色指数低。
β版：integrate算法并不完善。
代码行数：253（1.02）→1654（1.03）

程序1.02版。
可计算光谱质心或者平均荧光寿命、面积、峰值波长、三刺激值和色坐标xy。
1. 波长间隔不为1时，1.01版本无法有效处理，1.02版本修复此问题。

程序1.01版。
可计算光谱质心或者平均荧光寿命、面积、峰值波长、三刺激值和色坐标xy。
在1.00基础上增加以下功能：
1. 增加三刺激值XYZ的输出；
2. 增加色坐标xy的输出。

程序1.00版。
可计算光谱质心或者平均荧光寿命、面积和峰值波长。
相对于最早期版本有如下改进：
1. 加入了迅速得到峰值波长的功能；
2. 改进了操作流程：任务结束后不会窗口闪退，而是处理下一个文件。输入quit可结束程序（窗口内部有提示）。
3. 纠错能力。输入错误文件名或者目录内不存在的文件名后，会报错提示。