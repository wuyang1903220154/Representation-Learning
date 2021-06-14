# Representation-Learning
Representation Learning
#### data_loader.py 是用来加载数据的，其中是来加载img,pid,camid
#### data_manager.py 是用来对数据集进行预处理的过程，其中是提取出相应imgs,pids,camids
#### eval_metrics.py  是相应的度量的方式，我们这里采用了CMC,mAP进行度量的，其中有不懂的，可以上网来查这三个关键词的过程的
#### losses.py 是来定义的损失的，也就是真实标签与预测标签的之间的损失的，然后是通过反向的传播的方式来对梯度进行更新的
#### optimizers.py 是对应的相应的优化器，我们对于这个优化器，是来对权重进行更新的，当我们对权重进行更新的过程中的，找到其中最优的权重的
#### ResNet.py 是对应的我们所使用的网络的model,也就是来提取的特征的
#### train_class.py 是对应的主文件，我们运行的时候，就是来运行这个文件的。
#### transforms.py 是来对相机图片进行一些曾广的操作的过程的，在这个过程中的，我们是对应的水平翻转的，或者裁剪的过程的
#### utils.py 主要是把控制台输出的数据到，文件中的。还有就是创建文件夹，还有就是对应的对数据，进行更新的过程的
