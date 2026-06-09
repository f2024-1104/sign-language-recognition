# Sign Language Recognition — Alphabets & Numbers

A deep learning model that recognizes ASL hand signs for A-Z alphabets and 0-9 numbers using EfficientNet-B0.

## Project Files
| File | Download |
|---|---|
| Source Code (Notebook) | [Download .ipynb](https://drive.google.com/file/d/1BOKJpeES460qUzZgYhsrM_KGT1wSNUld/view?usp=drive_link) |
| Class Labels (JSON) | [Download classes.json](https://drive.google.com/file/d/1hjpBlsE1LVqGhhEhy3Wi02e3zZh3Qy0L/view?usp=drive_link) |
| Pretrained Model | [Download checkpoint.pth](https://drive.google.com/file/d/1Qd2fFtVvroF8JFAHcJzbTEKVQFPENa4X/view?usp=drive_link) |

## Datasets Used
- [ASL Alphabet](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
- [Sign Language MNIST](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
- [ASL 0-9 + A-Z](https://www.kaggle.com/datasets/prathumarikeri/american-sign-language-09az)

## Setup
1. Download all files from the links above
2. Install dependencies:
   pip install torch torchvision opencv-python gtts scikit-learn matplotlib kaggle
3. Place `checkpoint.pth` and `classes.json` in the project folder
4. Open and run the notebook

## Model
- Architecture: EfficientNet-B0
- Classes: 36 (A-Z + 0-9)
- Framework: PyTorch
