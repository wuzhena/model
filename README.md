# GNPSum

GNPSum: A Code Summarization Enhancement Framework Based on Graph Node Position

`GNPSum` is our model proposed in this paper.

# Dependency
- Python 2.7-3.6
- PyTorch 1.9 for Python 3.9
- Ubuntu 16.04  
- CUDA 10.2

# Dataset
The whole datasets of Python and Java can be downloaded from [Baidu Netdisk](https://pan.baidu.com/s/1mADEgUeiqDSzwx7vIz5yfQ?pwd=2bfb) or [Google Drive](https://drive.google.com/file/d/1HWWaSJbVRGfTrDNc0h2TPEfjq-KN8ihe/view?usp=sharing).

# Usage
Edit hyper-parameters and settings in `config.py`

Set reload model/epoch in `config.py`

# Train and Evaluate

   ```angular2html
   python preprocessor.py
   python model.py
   python eval.py
