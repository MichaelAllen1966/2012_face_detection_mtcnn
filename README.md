# 2012_face_detection_mtcnn

Face Detection with a Multi-Task Cascaded Convolutional Neural Network (MT-CNN)

This workbook:

* Detects faces in a photo
* Outputs a list of dictionary of location of faces and features of faces
* Draws boxes around faces in the photo, and highlights face features
* Extracts faces and saves as individual files


## Requirements

* matplotlib (conda or pip install)
* mtncc (pip install)
* tensorflow (conda or pip install)

Or create a local environment using the enclosed .yml with with:

`conda env create -f environment.yml`

Activate with: 

`conda activate face`

Remove with:

`conda env remove -n face`

