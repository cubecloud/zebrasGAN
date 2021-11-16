# zebrasGAN
GAN for change horses to zebras and zebras to horses

Based on article https://machinelearningmastery.com/cyclegan-tutorial-with-keras/

added:  
1. checkpoint saver and loader
2. dataset autoloader
3. changed InstanceNormalization to TF version
4. added albumentation augmentation to enlarge dataset

**created:** Dec 2020

**checked and polished to work with TF 2.6.x:** Nov 2021

_Comment_: the speed of this "zebrasGAN" on TensorFlow 2.6.x and new Colab environment 1.8-2 times slower then 1 year ago with TF 2.3.x

I've checked my old notebooks and have a proof. Check the screenshot.

<img src="/home/cubecloud/Python/projects/zebrasGAN/proof_1year_ago.png"/>