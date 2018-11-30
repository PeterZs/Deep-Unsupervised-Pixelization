# Deep-Unsupervised-Pixelization
ACM Transactions on Graphics (SIGGRAPH Asia 2018 issue), 2018
## Requirement
- Python 3.5
- PIL
- Numpy
- Pytorch 0.4.0
- Ubuntu 16.04 LTS
## Dataset
### Training Dataset
We collect 900 clip arts and 900 pixel arts for trianing our method. The folders named `trainA` and `trainB` contain the clip arts and pixel arts respectively [here](https://drive.google.com/open?id=1qDXB5g0Cb0VwISXwnfeiehPHuTgxWhdG).
## Testing
* Download pre-trained model [here](https://drive.google.com/open?id=1HL0F6cURjWhY2qnt03YdshDH0JD01f5T).
* extract the `pre-trained_model.zip` into a newly created folder called `checkpoints_pixelization`.
* Create the folders `testA` and `testB` in `samples` which contain the clip arts are going to be pixelized and pixel arts are going to depixelized respectively.
Then, run
`$ bash test`
