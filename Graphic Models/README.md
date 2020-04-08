
# Graphic Models

测试图模型中的Glasso，Neighborhood Selection以及Space。

#### 1.DGP   

- a)	Ω：对角线元素ρ，非对角线的元素以0.01的概率等于0.5    
- b)	问题在于该Ω是否可以用来构造多元正态回归模型（关键在于常数ρ）（hint：条件数需要满足一定性质）。          

#### 2.测试Graphical Models中的Glasso和Neighborhood Selection     

- a)	测试方式：approx参数取T和F（即两种求解方法），测试两个方法选出来的变量是否符合真实的设定。     
- b)	选用两种指标（Frobenius norm，以及分类评估方法）来判断在模拟得的数据集下哪种方法结果比较好。 
