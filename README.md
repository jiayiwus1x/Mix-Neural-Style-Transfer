# Mix style transfer

![Image description](https://static.wixstatic.com/media/94d104_d4932d4d0bde443fa6a5ef511762136f~mv2_d_4897_2184_s_2.png)
(The image in the center is in the combined style of the images on the left and the right.)

## Description

In this project, I use an idea inspired by one of my research projects. In the project, I created an optimization methodology (inspired by nature) that is able to design adaptable materials. This simply means that I create materials that can change forms/behavior/properties/etc. depending on its environment using the following process:

1. Train a material to learn one goal (form/behavior/property/etc.), until you are satisfied :D
2. Train the same material to learn another goal, and halt the training when you are satisfied.
3. Cycle 1. and 2. until .. well .. you are satisfied :P

Note that the code of one goal is heavy adapted from the following link: [NEURAL TRANSFER USING PYTORCH](https://pytorch.org/tutorials/advanced/neural_style_tutorial.html).

## Prerequire package

```bash
pip install numpy
pip3 install torch torchvision
pip install matplotlib

```

## Usage

Following along the jupyter notebook

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Futher reading

[Let machines help you design your own art style](https://www.hallojiayi.com/post/let-machine-help-you-design-your-own-art-style)
