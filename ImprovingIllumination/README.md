# Illuminating Night Images

This Technique aim to utilise a dual channel prior-based method for low illumination image enhancement with a single image.

Compared to using multiple images, image enhancement with a single image is simpler. Single image enhancement does not need additional assistant images or require exact point-to-point fusion between different images.

Many conventional image processing techniques such as the well-known histogram equalization-based methods, wavelet transform-based method, retinex-based methods can be used to get brighter images. However, they might lead to contrast over-enhancement or noise amplification.

This is where the dual channel prior based solution comes in. An image prior is simply put, “prior information” of an image that you can use in your image processing problem. You would wonder why we use dual channel instead of utilising just the bright channel of a low light image since it would contain the maximum leftout information. Taking the dark channel into consideration removes block effects in some regions and helps see artefacts clearly as illustrated in the image below.

## Results

Input image

![test3](https://user-images.githubusercontent.com/58569950/117584923-4f7a6c80-b12d-11eb-92c2-463d3b57fcec.jpg)

Output image

![out3](https://user-images.githubusercontent.com/58569950/117584930-54d7b700-b12d-11eb-8a0e-1e09ec4527ca.jpg)
