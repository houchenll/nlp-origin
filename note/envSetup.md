1. 安装xcode

2. 安装 homebrew
  brew install gcc
  brew install cmake
  brew install wget

3. 安装 conda
  打开 https://github.com/conda-forge/miniforge , 下载 OS X arm64
  cd ~/Downloads
  bash Miniforge3-MacOSX-arm64.sh
  指定目录 /Users/ll/env/miniforge3
  如果希望终端启动时不激活conda的base env, 
  执行 conda config --set auto_activate_base false
  再次进入conda base env时执行 conda activate
  重启终端

4. 设置 ml 环境
  conda create --name ml
    /Users/ll/env/miniforge3/envs/ml
      To activate this environment, use
    conda activate ml
      To deactivate an active environment, use
    conda deactivate
  升级conda

  conda activate ml
  conda install -y python=3.8.6
  conda install -y pandas matplotlib scikit-learn jupyterlab

5. 安装 tensorflow
  cd env
  mkdir tf-test
  cd tf-test
  
  打开 https://developer.apple.com/metal/tensorflow-plugin/

## 6. 安装 pytorch
  1. 安装 conda，卸载anaconda, 选择 安装miniforge
  2. 创建 pytorch 环境
    conda create -n pytorch python=3.10
  3. 激活环境
    conda activate pytorch
  4. 官方环境选择：https://pytorch.org/get-started/locally/
    PyTorch Build: Preview (Nightly), Preview 才支持mac MPS 加速
    Package: conda
  5. 安装
    conda install pytorch torchvision torchaudio -c pytorch-nightly
  6. 检查1：
    python check_env.py
  7. 检查2：
    import torch
    torch.__version__   # '2.1.0.dev20230409'
    torch.device("mps")   # device(type='mps')

