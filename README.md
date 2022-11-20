# Object Detection and Identification using Yolov7



## Training Notebook 

**Training and Evaluvation steps on custom Dataset** <a href="https://colab.research.google.com/github/GouthamVicky/ObjectDetectionYoloV5/blob/main/ObjectDetectionNotebook.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

## Model File Link 

[`best.pt`](https://github.com/GouthamVicky/ObjectDetectionYoloV7/blob/main/modelWeightsFolder/best.pt)

## Detection Notebook

**Inference steps on custom Dataset** <a href="https://github.com/GouthamVicky/ObjectDetectionYoloV7/blob/main/inferenceObjectDetection.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

<div align="center">
    <a href="./">
        <img src="front-left-side-47inference.jpg" width="59%"/>
    </a>
</div>

## **Download Dataset** 
* To Download Open vechicle image dataset directly from roboflow using API key.
    ```
    !pip install roboflow

    from roboflow import Roboflow
    rf = Roboflow(api_key="0P7SHkCBabGSiZ1zyi4O")
    project = rf.workspace("jacob-solawetz").project("vehicles-openimages-archived")
    dataset = project.version(1).download("yolov7")
    ``` 
