![](https://github.com/rlaneth/figment-fusion/blob/master/LOGO.svg?raw=true)

# Changelog

#### v1.0.0-beta.2
- Added the `fp16` version of Waifu Diffusion v1.3 to the model selection list;
- Batch image file names now start from 1 instead of 0 (to match the batch ID);
- Fixed an error that occurred when attempting to generate a batch with more
  than one image and a negative prompt.