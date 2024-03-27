<a name="readme-top"></a>

<h3 align="center">Object-Detection-Model</h3>

  <p align="center">
   Object Detection Model using ResNet-18 Backbone
    <br />
    <a href="https://github.com/sagi-vaknin/Object-Detection"><strong>Explore the docs »</strong></a>
  </p>
</div>

## About The Project
This project demonstrates the implementation of an object detection model utilizing the ResNet18 backbone. It begins by showcasing the inference capabilities of the ResNet18 backbone on the provided dataset. Several examples from the test set, post-transformations, are displayed to illustrate its functionality.

Subsequently, a custom dataset representing each split (test, train, val) is created. Each image undergoes transformation, and bounding box calculations are performed according to their new shape.

The object detector itself is then constructed, utilizing a ResNet18 backbone model and two new custom heads: a classification head for the task of cat vs. dog classification and a bounding box regressor designed to determine bounding box coordinates.

The model is trained, validated, and tested, and a selection of random examples is presented to demonstrate its capabilities. The entire project is documented within a Jupyter Notebook (ipynb).


<p align="right">(<a href="#readme-top">back to top</a>)</p>

### File Structure
* object_detection_resnet18.ipynb: Jupyter Notebook containing the entire project.

### Built With
* Python
* PyTorch
* OpenCV
* Roboflow Oxford-Pets-2 Dataset
* NumPy
* PIL

## Contact

Sagi Vaknin - sagivak1@gmail.com<br>
LinkedIn  - https://www.linkedin.com/in/sagi-vaknin-sv <br>
Project Link: [https://github.com/sagi-vaknin/Object-Detection](https://github.com/sagi-vaknin/Object-Detection)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


