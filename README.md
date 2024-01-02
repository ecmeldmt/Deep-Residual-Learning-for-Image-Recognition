
# Deep Residual Learning for Image Recognition

This repository is the official implementation of [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385). 

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

## Training

Run the following code to train different layers on CNN on CIFAR-10 dataset, run this command:

```train
jupyter notebook CNN_20_56_layers_20epoch.ipynb 
```
If Jupyter Notebook is not installed, you may need to install Jupyter first using tools such as Anaconda or pip. If you are using Anaconda, you can install Jupyter Notebook with this command:

```install
conda install -c conda-forge notebook
```

If you are not using Anaconda or working in another virtual environment, you can install it with this command:

```install
pip install notebook
```

After following these steps, you can run your Jupyter Notebook file using the jupyter notebook file_name.ipynb command above.

## Evaluation/Compare

To compare CNN, ResNet, DenseNet and ResNext and see their results on CIFAR-10 dataset, run:

```eval
jupyter notebook Compare_18_layers_50epoch _Test.ipynb
```

## Download Dataset

You can download CIFAR-10 dataset here:

- (https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz) 


## Results

Our model achieves the following performance on :

### [Image Classification CNN, ResNet, DenseNet and ResNext on CIFAR-10]

| Model name         | Top  Accuracy   | 
| ------------------ |---------------- | 
| CNN model          |     96%         | 
| ResNet model       |     98%         |
| ResNeXt model      |     90%         |
| DenseNet model     |     97%         |

