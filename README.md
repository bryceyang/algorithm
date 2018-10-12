## 用作练习一些常用算法的实现
### 蓄水池算法
实现一：这个是直接接受流式输入，不用提前知道样本集带下

[蓄水池算法](https://github.com/bryceyang/algorithm/blob/master/reservoidSampling.py)

测试结果：
```shell
size: 10, totalNum: 20, repeatTimes: 5000000
time used:  92.3419759273529
min: 2498214 max: 2502526
2498908 2499831 2500590 2499638 2498872 2501752 2500850 2499254 2499302 2500006 2498214 2500222 2498479 2502526 2499524 2501408 2499511 2500232 2499712 2501169
```

实现二：这个实现是在样本集大小已知的情况下

[蓄水池算法二](https://github.com/bryceyang/algorithm/blob/master/reservoidSampling2.py)

测试结果：
```shell
size: 10, totalNum: 20, repeatTimes: 5000000
time used:  43.74356007575989
min: 2498927 max: 2501916
2500371 2499520 2499005 2499606 2501231 2499590 2499549 2500412 2500425 2499164 2498927 2500575 2499086 2500069 2499923 2499998 2501916 2500802 2499475 2500356 %
```
