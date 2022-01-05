# COPD最大密度投影
## Step1 运行lungmask分割肺区
## Step2 运行lung_box.py改变img形状，只保留肺区部分
## Step3 运行MIP_2d.py 进行最大密度投影
## Step4 运行MIP_3d.py 每15张做一个投影，生成一个三维图像