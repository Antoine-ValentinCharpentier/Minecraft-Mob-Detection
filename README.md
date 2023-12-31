# Minecraft-Mob-Detection

## Description
This project aims to develop a classification model using TensorFlow and Convolutional Neural Networks (CNN) to distinguish between hostile and passive creatures of the game Minecraft.


## Dataset

The dataset can be obtained from : https://universe.roboflow.com/minecraft-object-detection/minecraft-mob-detection/dataset/10

After downloading the dataset, extract it and place the three folders (train, valid, test) inside the data directory. The workspace structure should resemble the following :
```
data
 |- train
 |- valid
 |- test
```

## Setup the Project

0. Ensure you have Python installed on your system. 

1. Clone the repository:
    ```bash
    git clone git@github.com:Antoine-ValentinCharpentier/Minecraft-Mob-Detection.git
    cd Minecraft-Mob-Detection
    ```
2. Initialise the venv:
    ```bash
    python -m venv .venv
    .venv\Scripts\activate OU source .venv/bin/activate
    pip install -r requirements.txt
    ```

3. Execute the script ``cnn.ipynb``