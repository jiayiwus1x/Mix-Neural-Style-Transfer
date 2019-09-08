# Mixed Neural Style Transfer

![Image description](https://static.wixstatic.com/media/94d104_d4932d4d0bde443fa6a5ef511762136f~mv2_d_4897_2184_s_2.png)
(The image in the center is in the combined style of the images on the left and the right.)

## Description

In this project, I use an idea inspired by one of my research projects. In the project, I designed adaptable materials using oscillatory optimization goals. I'm letting the learner, which in this case is the optimizer that mimics the style of a painting, repeatedly change its mind about which style it prefers. The learner oscillates between learning how to paint like Van Gogh and learning how to paint like Picasso. After several cycles, the learner ends up painting in a style of its own that has qualities of both!

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
