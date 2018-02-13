# Capsule Networks
A Tensorflow implementation of Capsule Networks

For more information on Capsule Networks please read my [Medium article](https://hackernoon.com/capsule-networks-are-shaking-up-ai-heres-how-to-use-them-c233a0971952).

This repo was largely based off of [naturomics CapsNet-Tensorflow repo](https://github.com/naturomics/CapsNet-Tensorflow) with the current differences being an added `requirements.txt` and the MNIST dataset is included. Power users may want to refer to the naturomics repo for the latest versions.

## Usage
Install the requirements:
```bash
pip install -r requirements.txt
```
Start training!
```bash
python main.py
```

## Making Inferences
```bash
python main.py --is_training False
```

## Visualization
The model generated from training with this implementation can be used with this [Visualization Tool](https://github.com/bourdakos1/CapsNet-Visualization) I built.
![](https://github.com/bourdakos1/CapsNet-Visualization/raw/master/readme/4.gif)
