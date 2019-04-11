	作者还想用pointnet做分类（tensorflow版和keras版都开动了），不过实验未完成
	调通去掉地面和默认点随机森林版本，不去除的版本计算时太慢没走通

	* Uban point cloud Classifier.ipynb
		1. python，sklearn,随机森林，点云分类，ipynb，17个类别； 
		2. 预处理：基于网格的抽稀，
		3. 用pyntcloud提取了各种各样的特征9个； 
		4. 使用的数据集： Paris-rue-Madame database，巴黎一个街区
		5. 训练集和测试集都是1千万个点，排除地面点和默认点，剩下90万个点
		6. 2019.03.14 调通，测试集 Accuracy: 0.9174709432905417，精确度92%，作者说如果多用计算资源如果提取一些计算复杂的特征，可能还能改善。
	* point cloud Classifier.ipynb
		1. 不去除地面和默认点的版本
		2. 