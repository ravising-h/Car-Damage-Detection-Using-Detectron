# Semantic segmentation 
Semantic segmentation  refers to the process of linking each pixel in an image to a class label. These labels could include a person, car, flower, piece of furniture, etc., just to mention a few. We can think of semantic segmentation as image classification at a pixel level.


If you want to use a custom dataset while also reusing detectron2’s data loaders, you will need to

Register your dataset (i.e., tell detectron2 how to obtain your dataset).
Optionally, register metadata for your dataset.
Next, we explain the above two concepts in details.

The Colab Notebook has a working example of how to register and train on a dataset of custom formats.
