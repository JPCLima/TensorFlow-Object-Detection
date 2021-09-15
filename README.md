# TensorFlow-Object-Detection

On this repository there is the necessary files to create a custom object detection with TensorFlow Object Detection.

1. Image Preprocessing - place to prepere the data to be trained
2. Training Model - place where the model will be trained (can be on the local machine or the fastes way on Google Colab)
3. Detections - Using OpenCv and Tensorflow object detections its possible to have a live detection of the objects.
4. TF Lite Converter - Notebook to convert the model to TFLite

## How to install?

1. Clone the repo

```bash
git clone https://github.com/JPCLima/TensorFlow-Object-Detection.git
```

2. Create a virtual env

```
python -m venv env
```

3. Activate virtual env

```
env\Scripts\activate
```

4. Install kernel and notebook (name is the the virtual environment)

```bash
pip install ipykernel notebook
python -m ipykernel install --user --name=env
```
