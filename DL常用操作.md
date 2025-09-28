pip install --upgrade pip



pip install torch==2.0.1+cu117 torchvision==0.15.2+cu117 --index-url https://download.pytorch.org/whl/cu117



nvidia-smi

python -c "import torch; print(torch.version.cuda)"



pip install numpy==1.25.2