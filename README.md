# Capsule Networks
A Tensorflow implementation of Capsule Networks

For more information on Capsule Networks please read my [Medium article](https://hackernoon.com/capsule-networks-are-shaking-up-ai-heres-how-to-use-them-c233a0971952).

**[Update]** Check out my [new article](https://medium.freecodecamp.org/understanding-capsule-networks-ais-alluring-new-architecture-bdb228173ddc) with a deeper explanation on how capsules work.

This repo was largely based off of [naturomics CapsNet-Tensorflow repo](https://github.com/naturomics/CapsNet-Tensorflow) with the current differences being an added `requirements.txt` and the MNIST dataset is included. Power users may want to refer to the naturomics repo for the latest versions.

## Usage
Install the requirements and download dataset:
```bash
pip install -r requirements.txt
python download_data.py
```
Start training!
```bash
python main.py
```

## Testing Accuracy
```bash
python main.py --is_training False
```

## Visualization
Check out this [Visualization Tool](https://github.com/bourdakos1/CapsNet-Visualization) I built to play around with the DigitCaps vectors to see how it effects the recontructions:

[![](https://github.com/bourdakos1/CapsNet-Visualization/raw/master/readme/4.gif)](https://github.com/bourdakos1/CapsNet-Visualization)
