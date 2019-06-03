1、PreProcess文件夹
    DropDayAndSubItem.ipynb：
        1、从全量的用户行为数据中挑选出商品子集上的用户行为数据。
        2、将‘time’属性分割为‘day’和‘hour’两个属性。
2、UnitTest文件夹
    初衷是用于写单元测试，但貌似import存在问题，暂时为用的上。
3、ModelFile文件夹
    用于存储训练好的模型文件。
4、DataSet文件夹
    各种数据文件的存储位置
5、Feature文件夹
    DevideDataSet.ipynb 
        devide_data(user_behavior_data_path, start_day, end_day,flag=True):
            输入参数：
                user_behavior_data_path: 用户行为数据的路径
                start_day：截取数据的起始日期，类型：datetime.datetime
                end_day：截取数据的终止日期，类型：datetime.datetime
                flag：true，训练数据集生成uicl数据，预测数据集生成uic数据。
            输出参数：
                指定时间段内的uicl数据。
6、Feature文件时主文件。执行顺序如下：
    DevideDataSet.ipynb 
    FeatureConstruct.ipynb
    KMeansPreprocessing.ipynb
    Tuning.ipynb
    TrainModel.ipynb
    Predict.ipynb
    ------------------------
    DevideDataSet.ipynb 已经测试验证过
    FeatureConstruct.ipynb 待回头详细测试验证
    KMeansPreprocessing.ipynb
    
7、
8、
9、
10、
11、
12、