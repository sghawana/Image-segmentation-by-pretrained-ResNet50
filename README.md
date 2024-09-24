## Semantic Segmentation
This project demonstrates the use of a pretrained ResNet50 model for semantic image segmentation. The goal is to identify and separate different objects or regions within an image by applying a segmentation model.

---

### Dataset
Dataset Link: https://drive.google.com/file/d/1xrQK9pLB2UiWy0pxdXU-WWbrSZI2A-s4/view


**Example image**

![mask](./utils/mask.png)

---

### Architecture 
It utilizes a **ResNet50** model **pre-trained on ImageNet** and fine-tuned for semantic segmentation using a **U-net**. 



The model is tested on a dataset of images, and segmentation masks are predicted to classify different regions of the images.

![segm](./utils/segm.jpg)


---
### Results

Please refer to report.pdf for detailed results and analysis

Some sample **model predictions**

![res1](./utils/result1.png)
<br>
![res2](./utils/result2.png)

---

