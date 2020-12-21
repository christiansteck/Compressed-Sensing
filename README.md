# Compressed-Sensing

Some examples on compressed sensing, inspired by the [single pixel camera](https://www.ams.org/publicoutreach/math-history/hap7-pixel.pdf).

## Sine Wave Reconstruction

The first example contains a superposition of sine waves (blue) and a set of measurements (red).
From these values a reconstruction (green) is generated.

Note that the number of measurements is far below the limit we get from the [Nyquist-Shannon sampling theorem](https://en.wikipedia.org/wiki/Nyquist%E2%80%93Shannon_sampling_theorem).

![sine_wave_reconstruction](https://raw.githubusercontent.com/elvorfirilmathredia/Compressed-Sensing/main/sine_wave_reconstruction.png)

## Simple Image Reconstruction

The second example contains a simple picture of a white blob on black background (right) and a reconstruction from random measurements (left),
which represents the way the single pixel camera works.

![ball](https://raw.githubusercontent.com/elvorfirilmathredia/Compressed-Sensing/main/ball.png)
![ball_reconstruction](https://raw.githubusercontent.com/elvorfirilmathredia/Compressed-Sensing/main/ball_reconstruction.png)

## Lena Reconstruction

No work with images is complete without Lena.
So I did the same procedure as in the second example but with the usual Lena picture.

The result is a recognizable reconstruction of the original, but not entirely satisfying. I blame the optimization algorithm ¯\\\_(ツ)_/¯.

![lena](https://raw.githubusercontent.com/elvorfirilmathredia/Compressed-Sensing/main/lena.png)
![lena_reconstruction](https://raw.githubusercontent.com/elvorfirilmathredia/Compressed-Sensing/main/lena_reconstruction.png)
