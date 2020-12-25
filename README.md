# PyTorch Neural Style Transfer with nbdev
> This is an implentation of neural style transfer in PyTorch using a VGG-19. Most code is lifted from the official tutorial and modified to run as a command-line application and in Jupyter Notebooks using nbdev


## Install

`pip install pytorch_nst`

## How to use

This module is a command line tool
`nst`

Use `nst --help` for more details:

```
Usage: nst [OPTIONS]

Options:
  -c, --content TEXT      path to content image  [default:
                          ./examples/content.jpg]

  -s, --style TEXT        path to style image  [default: ./examples/style.jpg]
  -o, --output TEXT       path to save generated image  [default:
                          ./output/generated-1608872128.jpg]

  --style_weight INTEGER  [default: 1000000]
  --style_layers TEXT     Conv Layers to use for style loss  [default:
                          1,2,3,4,5]

  --steps INTEGER         [default: 300]
  --random_input          Will start with random noise if set, otherwise
                          content image

  --help                  Show this message and exit.
  ```
