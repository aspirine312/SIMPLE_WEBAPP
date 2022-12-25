# 手寫辨識

# 安裝
* 建構模型訓練環境
```
conda create -n env_name python=3.8
conda activate env_name
```
*  安裝 pytorch、torchvision
```
conda install pytorch==1.8.0 torchvision==0.9.0 cpuonly -c pytorch
```
*  安裝 torchsummary、PyYAML、tqdm
```
pip install torchsummary PyYAML tqdm
```
*  執行 mnist.py
```
將 onnx_model.onnx 放進有javascript的資料夾裡
``` 
*  Run in local
```
npx serve
``` 