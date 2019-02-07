# ImageSegmentation
Image segmentation according to one of 24 classes on a custom dataset and data loader class.<br>
<br>
Segmentation is done in several steps. The image is shrinked or enocded via pretrained network. In this case I chose alexnet because it's quite lightweight. After that the image is decoded back via several transposed convolutions. Due to the small dataset we didin't introduce any skip connections and U architecture here. 
