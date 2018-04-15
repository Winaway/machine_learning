
## CAT & DOG 项目配置

### 项目运行环境

该项目的大多数的计算工作是在aws的p2.large实例上完成的（AMI选的是‘MLND-DL’)。以下为项目运行环境：

- 系统环境Ubuntu 16.04.2 LTS 
- Python 3.5.2
- anaconda                  custom                  
- conda                     4.2.13                   
- h5py                      2.6.0               
- hdf5                      1.8.17                        
- ipython                   5.1.0                    
- jpeg                      8d                           
- jupyter                   1.0.0                   
- jupyter_client            4.4.0                   
- Keras                     2.0.4                   
- notebook                  4.2.3              
- numpy                     1.12.1                  
- opencv3                   3.1.0                 
- pandas                    0.18.1            
- scipy                     0.19.0            
- tensorflow                0.11.0          
- tqdm                      4.10.0              


#### 代码
- Image_Data_prepare.ipynb //图像数据预处理
- fine_tuning_pretrained_model.ipynb //迁移模型微调
- write_gap.ipynb //导出特征向量
- train_process.ipynb //利用导出的特征向量训练和预测

#### 训练及测试目录结构
![Snip20180415_10.png](attachment:Snip20180415_10.png)
 
