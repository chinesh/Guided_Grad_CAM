# Grad-CAM-tensorflow

This is tensorflow version of demo for Grad-CAM. I used vgg16 for demo because this models are very popular CNN model.
However grad-cam can be used with any other CNN models. Just modify convolution layer in my demo code.

![Preview](https://github.com/insikk/Grad-CAM-tensorflow/blob/master/image_preview.png?raw=true)

See [python notebook](https://github.com/insikk/Grad-CAM-tensorflow/blob/master/gradCAM_tensorflow_demo.ipynb) to see demo of this repository.
>To use VGG networks in this demo, the npy files for [VGG16 NPY](ftp://mi.eng.cam.ac.uk/pub/mttt2/models/vgg16.npy) has to be downloaded.

wget https://www.dropbox.com/s/8a8rei66f72um4i/vgg16.npy


**Any Contributions are Welcome**


## [Origial Paper] Grad-CAM: Gradient-weighted Class Activation Mapping

**[Grad-CAM: Why did you say that? Visual Explanations from Deep Networks via Gradient-based Localization][7]**  
Ramprasaath R. Selvaraju, Abhishek Das, Ramakrishna Vedantam, Michael Cogswell, Devi Parikh, Dhruv Batra  
[https://arxiv.org/abs/1610.02391][7]
