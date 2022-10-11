![](https://github.com/rlaneth/figment-fusion/blob/master/LOGO.svg?raw=true)

# Figment Fusion

[![Open In Colab][colab-badge]][colab-url]

Figment Fusion is a [Jupyter] notebook for AI-based image generation. It is
powered by the [Diffusers] library and is pre-configured for the
[Stable Diffusion][stable-diffusion] and [Waifu Diffusion][waifu-diffusion]
models.

The project is primarily aimed at technology enthusiasts who may not have a
background in machine learning but are eager to get started. The goal is to
create a tool that encourages playing with source code and assists in
understanding how to use diffusion models in your projects.

### Usage

The simplest way to get started with Figment Fusion is to open the notebook file
directly from this repository in [Colaboratory][colaboratory], a Google service.
Try clicking the _“Open in Colab”_ button!

Each step is explained right in the file, and additional documentation can be
found on the Figment Fusion [wiki][wiki]. 

### Upcoming

These are the most relevant features that should be added to future Figment
Fusion releases.

- **Schedulers**  
  Figment Fusion uses the schedulers provided by Diffusers, which is
  missing some well-known options such as Euler. This is being worked on by
  contributors of the library ([issue #277][diffusers-issue-schedulers] at the
  Diffusers project).

- **Image-to-image and inpainting**  
  Not yet implemented because it has not been decided how to build a practical
  image-to-image and inpainting user interface that can be embedded in the
  notebook. Suggestions are welcome ([issue #1][issue-img2img]).

### Philosophy

- **Jupyter-first**  
  Figment Fusion was designed from the start to be used as a notebook, rather
  than being converted as an afterthought, resulting in a better user
  experience. Furthermore, it was built for Jupyter, with no Colab-specific
  features required for it to function out-of-the-box, enabling portability to
  more generic environments such as the ones provided by servers on
  [RunPod][runpod] and [Vast.ai][vast-ai].

- **Simplicity**  
  _“Do one thing and do it well”_ is a [Unix philosophy][unix-philosophy]
  principle that Figment Fusion follows. As a utility designed solely for image
  generation, it does not include features such as facial enhancement and
  upscaling. This implies that it is not a complete solution for creating
  artwork, as the use of complementary tools is required to extract the highest
  quality possible from the generated work, but it does have the advantage of
  making the code more maintainable and the setup steps run much faster.

- **Openness**  
  Figment Fusion is released in the public domain, which means that anyone can
  freely copy, modify, and share its code. This should be beneficial to those
  who wish to use it as a starting point for their own projects and thus
  contribute to the growth of the AI artwork ecosystem.

### License

[The Unlicense][license]

[colab-url]: https://colab.research.google.com/github/rlaneth/figment-fusion/blob/current/FigmentFusion.ipynb
[jupyter]: https://jupyter.org/
[diffusers]: https://github.com/huggingface/diffusers
[stable-diffusion]: https://stability.ai/blog/stable-diffusion-announcement
[waifu-diffusion]: https://huggingface.co/hakurei/waifu-diffusion
[colaboratory]: https://research.google.com/colaboratory/faq.html
[wiki]: https://github.com/rlaneth/figment-fusion/wiki
[diffusers-issue-schedulers]: https://github.com/huggingface/diffusers/issues/277
[diffusers-pull-negative-prompt]: https://github.com/huggingface/diffusers/pull/549
[issue-img2img]: https://github.com/rlaneth/figment-fusion/issues/1
[runpod]: https://runpod.io
[vast-ai]: https://vast.ai
[unix-philosophy]: https://en.wikipedia.org/wiki/Unix_philosophy
[license]: LICENSE.txt

[colab-badge]: https://colab.research.google.com/assets/colab-badge.svg
