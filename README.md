## 学习llm

### [happy_llm](https://github.com/datawhalechina/happy-llm)
- 实现llama2
### [train_llava](./train_llava/)
- 使用clip-vit-large-path14-336和Qwen1.5-1.8b合并成llava，复现并训练

## 环境
```shell
conda create -n llm python=3.10
conda activate llm
# 根据环境安装torch 在 https://pytorch.org/get-started/previous-versions/ 找到对应的版本
pip install torch==2.6.0 torchvision==0.21.0 torchaudio==2.6.0 --index-url https://download.pytorch.org/whl/cu124
pip install -r requirements.txt
```

