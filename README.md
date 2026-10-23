## 文件说明

`edge_based_training_sample.ipynb` ：采用 Edge-TTS（调用微软云端 Azure 神经拟真语音接口）

`microwakeword_training_sample.ipynb` ：采用 Piper（利用本地 ONNX 模型与拼音/音素管道离线推理生成）。

优先推荐 Edge-TTS 方式。

## 使用方法

1. 登陆 [Google Colab](https://colab.research.google.com/)

2. 上传上述任意一个文件

3. 选择T4 GPU

4. 修改 Cell 1 中的 `WAKE_WORD_NAME` 和 `TEST_VARIANTS`

5. 按顺序运行

## 来源及说明

基于[pafernanr/custom-microwakeword-training-colab](https://github.com/pafernanr/custom-microwakeword-training-colab)修改，原项目偏向于英文唤醒词，改为中文环境。

但是中文唤醒词，一言难尽，且用且珍惜。
