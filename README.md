# 🖥️ Computer Vision — Summer Training

| Week | Topic | Folder |
|------|-------|--------|
| **1** | Deep Learning & CNNs — neural nets, backprop, CNN architecture, data augmentation, custom datasets | [`Week 1`](Week%201) |
| **2** | Transfer Learning & Object Detection — pretrained models, ViT, Faster R-CNN, YOLO | [`Week 2`](Week%202) |
| **3** | Image Segmentation — semantic & instance segmentation, U-Net, YOLOv8-seg, SAM | [`Week 3`](Week%203) |

## 📁 Repository Structure

```
Summer-Training/
├── Week 1/
│   ├── Code/
│   │   | ....
│   └── Exercise/
│      | ....
├── Week 2/
│   ├── Code/
│   │   | ....
│   └── Exercise/
│   │   | ....
├── Week 3/
│   ├── Code/
│   │   | ....
│   └── Exercise/
│   │   | ....
└── requirements.txt
```

## 🚀 Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/orbitfirmraghad-cloud/Summer-Training.git
cd Summer-Training
```

**2. Create the environment** (Anaconda recommended)

```bash
conda create -n cv-training python=3.10 -y
conda activate cv-training
```
**3.  Install the standard required packages from the requirements.txt file**
```bash
pip install -r requirements.txt
```

Before running the command below, check your system's CUDA version by running nvidia-smi in your terminal. Look at the top right corner of the output to find your CUDA Version (e.g., 12.8, 12.4, etc.).

Modify the PyTorch index URL match your specific version (e.g., cu128 for CUDA 12.8, cu124 for CUDA 12.4):
Example for CUDA 12.8
```bash
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128
```

## 🔄 Keeping Your Repo Up to Date
This repo gets updated regularly. To avoid conflicts, don't edit the course files directly. Do your exercise work in a personal folder (e.g. my-work/) or make a copy of any notebook before changing it.
To get the latest updates:
```bash
git pull
```
If you edited a course file and pull fails, discard your local changes to that file and pull again (back up anything you want to keep first):
```bash

git checkout -- <filename>

git pull
```
## 📚 How to Use This Course

1. Follow the weekly resource guide (Word document) — it lists the theory videos and docs for each topic in order.
2. Open the matching notebook in `Week X/Code/` and run each cell alongside the video.
3. Solve the notebooks in `Week X/Exercise/` before moving to the next week.


## 🛠️ Main Libraries

- [PyTorch](https://pytorch.org/) & torchvision — model building and training
- [Ultralytics YOLO](https://docs.ultralytics.com/) — object detection & instance segmentation
- [segmentation-models-pytorch](https://github.com/qubvel-org/segmentation_models.pytorch) — U-Net and friends
- [kagglehub](https://github.com/Kaggle/kagglehub) — dataset downloads
