# minato-aqua-embedding

My Minato Aqua embeddings for school report

## Training

To train this, I used
[stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui).
The reason I used this is because I am more interested in the
theoretical aspects of the model, and I don't want to spend time
implementing it myself.

Training data can be found in the [dataset](./dataset) folder.
Training was done on a 3060Ti and took 10 hours.

## Results

The final embedding can be found in the [results](./results/minato-aqua-wd.pt).

Training progress milestones can be found in the
[training-milestones](./results/training-milestones) folder.

> NOTE: Some images included excessive NSFW content, and were
> removed from the training milestones folder.

The following are inference results from the embedding with
the following parameters:

- Sampling Steps: 28
- Sampling Method: Euler
- Width: 1024
- Height: 1024

```css
minato-aqua-wd 1girl o animal ears bangs blue bow blue hair blue hairband blue sailor collar blue skirt blunt bangs bow cat ears cat girl cat tail fang food frilled sailor collar frills hair between eyes hairband heart high-waist skirt
Steps: 28, Sampler: Euler, CFG scale: 7, Seed: 1511574215, Size: 1024x1024, Model hash: 84692140, Clip skip: 2
Used embeddings: minato-aqua-wd [0d44]
Time taken: 28.00s
Torch active/reserved: 5520/6124 MiB, Sys VRAM: 7777/7841 MiB (99.18%)
```

![tmp063atniw](./results/inference/tmp063atniw.png)

```css
minato-aqua-wd, 1girl, solo, ahoge, anchor, hair, ornament, anchor symbol, animal ear, fluff animal ears, bangs, blue choker, blunt bangs, blush, braid, cat ears, cat girl choker, closed mouth, collarbone, frilled shirt, collar frills
Negative prompt: lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, artist name
Steps: 28, Sampler: Euler, CFG scale: 7, Seed: 1615999862, Size: 1024x1024, Model hash: 84692140, Clip skip: 2

Used embeddings: minato-aqua-wd [0d44]

Time taken: 28.02s

Torch active/reserved: 5520/6124 MiB, Sys VRAM: 7777/7841 MiB (99.18%)
```

![tmpakhw31ty](./results/inference/tmpakhw31ty.png)

```css
