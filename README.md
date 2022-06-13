# Image-Captioning-GRU-Transformer-Seqtoseq--Model

## INTRODUCTION
Using a seq-seq model (encoder-decoder) built from scratch in TensorFlow to generate captions for images:
Encoder: vg16
Decoder: GRU or Transformer models (both were used in this notebook)


## INPUT
3 channelled image

## OUTPUT
Caption describing the image

## METHOD
The image is encoded using vg16 (encoder) and the output passed to the decoder module which attends to the encoded image to produce a caption sequentially (word by word).

## METRIC


For more info on the code, model architecture and explanations, read the .ipynb file attached to this repository.
