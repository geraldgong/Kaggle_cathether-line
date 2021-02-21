dataset

- 40,000 X-ray images

labels

- normal - appropriately positioned
- borderline - could work but wold ideally require some repositioning
- abnormal - require immediate repositioning

References:

https://arxiv.org/abs/2101.06871

- DenseNet121

- Activation Maps



In order to fine-tune *ResNet* with Keras and TensorFlow, we need to load *ResNet* from disk using the pre-trained *ImageNet* weights but **leaving off** the fully-connected layer head.