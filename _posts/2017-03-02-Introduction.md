---
layout: post
title:  What is an image?
date:   2017-04-03
---



<a href="{{ site.baseurl }}/docs/ImageJ-Introduction.pdf">Download slides</a> 

----

## Images are matrices

Images are matrices of pixels. Image analysis is basically matrices manipulations and analysis. 

<img src="https://plantmodelling.github.io/intro-imagej/img/image-1.png" style="width: 80%"/>

- `8-bit greyscale images`:  each pixel can take an integer value 


<img src="https://plantmodelling.github.io/intro-imagej/img/image-2.png" style="width: 80%"/>




## Image format


The format in which is saved is highly relevant for image analysis. Two big classes of image classes exist. The `loosless` format do not loose information when savng the images. The `lossy` format, usually compressed format, will modify the pixels values to reduce the size of the image (and therefore loose informations. 

In a perspective of image analysis, lossy format must be avoided at all cost. Using successive lossy compression (or save successively the same image in a lossy format), will cause loss and/or modification of the informtion contained in the image.

<img src="https://plantmodelling.github.io/intro-imagej/img/image-types.png" style="width: 80%"/>


### Different type of images:

- `JPEG`
	- lossy compression
	- **loss of informations**
	- light
	- **DO NOT USE**

- `TIFF`
	- no compression
	- NO loss of informations
	- heavy

- PNG`
	- lossless compression 
	- NO loss of informations
	- light

### More info: 

Minervini, M. et al. (2015) The significance of image compression in plant phenotyping applications. Funct. Plant Biol. [Website](http://www.publish.csiro.au/?paper=FP15033). [PDF](https://paperpile.com/app/p/f7d9b25d-40f9-02c9-8d0a-f343d19d25e1)
