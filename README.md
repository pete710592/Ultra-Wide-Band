# Ultra-Wide-Band (UWB)
Tensorflow implementation of indoor location using LSTM models.  
 - [Part 1: Environment setup](https://github.com/pete710592/Ultra-Wide-Band#part-1-environment-setup)  
 - [Part 2: Ready for training](https://github.com/pete710592/Ultra-Wide-Band#part-2-ready-for-training)  

## Part 1: Environment setup  
This code was tested with Tensorflow 1.12.0, CUDA 10.0 and Ubuntu 16.04.  
### 1-1. Install tensorflow:  
```shell
pip install tensorflow-gpu==1.12.0
```  

### 1-2. Install graphviz (optional):  
```shell
sudo apt-get update
sudo apt-get install -y graphviz libgraphviz-dev
```  

### 1-3. Download this repository from GitHub  
```shell
cd && git clone https://github.com/pete710592/Ultra-Wide-Band.git
```  

## Part 2: Ready for training  
First, moving your path.  
```shell
cd ~/Ultra-Wide-Band
```  
Then open ```train_mse_loss.ipynb``` and start for training.

###### tags: `UWB`
