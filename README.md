# Expert Annotation Agreement Study Data
This repository contains the following data elements

## Documentation
The study itself is currently under review. Once a final version
has been published, we will update this repository with a link to
the manuscript.

To download the images from the ISIC Archive, please install the
``isic-cli`` python package with

``pip install isic-cli``

and then download the collection (images and metadata file) with

``isic image download -l 0 -c 166 ./images``

## Metadata
The metadata.csv file contains the exemplar feature for which each
of the 248 images was submitted, a benign/malignant indicator, and
the diagnosis. It also contains in which of the 4 sub-studies (with
5 expert readers each) the image appeared

## Masks
The masks subfolder contains 4,703 individual feature annotations
across the 248 images by 5 readers from among 31 self-selected
features.

## Superpixel images and indices
As an alternative to the masks, the annotation data is also available
as a pair of superpixel images (per original lesion image) and the
indices into those superpixel images.

A Jupyter (python) notebook for how to access/process these images
will be made available shortly (in this repository).

