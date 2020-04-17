# IPSO_GRU-Regression
Using tensorflow1.x/python to implement a IPSO_GRU for regression，IPSO's here, it was mainly uesd to optimize hyper-parameters includess learning rate ,hidden_layer's number.
使用python下tensorflow编写改进的粒子群优化两个隐含层的GRU用于回归拟合，需要的可以加我qq 2919218574，收费非白嫖

1，数据格式：采用前几列为输入，最后一列为输出
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/data_type.png)

2,PSO对比改进后的PSO用于Sphere函数极值寻优
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/pso%20vs%20ipso.png)

3,LSTM用于回归拟合
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/LSTM.png)

4,GRU用于回归拟合
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/GRU.png)

5,IPSO-GRU用于回归拟合
5.1 IPSO优化结果
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/ipso_gru_optim.png)
5.2 采用IPSO优化的结果训练GRU
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/IPSO_GRU.png)

6，对比
![image](https://github.com/fish-kong/IPSO_GRU-Regression/blob/master/ipso_gru/compare.png)
