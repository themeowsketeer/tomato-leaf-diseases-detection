## Instruction for testing the data with our pre-trained model:
1. Access the notebook through file Training_Tomato.ipynb.
2. Login to Colab with a Google account.
3. Press "Connect to a hosted runtime". Preferably use T4 GPU as the hardware.
   ![image](https://github.com/themeowsketeer/tomato-leaf-diseases-detection/assets/76997829/1b8e10a1-c79c-43d2-8244-33d605b67388)
4. After connect, access the session explorer through the white cirlce below. For every time the cell is run, press the button on yellow circle to refresh the directory.
   ![image](https://github.com/themeowsketeer/tomato-leaf-diseases-detection/assets/76997829/2f111a7b-e3e8-4e51-95ea-bb5c6a1227cb)
5. Run the "Begin cloning the project's repository and install necessary files listed in requirements.txt." to clone this github as well as the data file.
### Training and validating the data
6. Run the "Perform training operation" to begin the training operation.
7. Access the following directory by default to view results: tomato-leaf-diseases-detection/runs/train/exp.
### Testing the data
6. Run the "Unzip pasted dataset zip file from local machine to Colab session" to unzip the zip file containing testing image.
7. Run the "Perform detecting operation" to begin detecting operation.
8. Access the following directory by default to view results: tomato-leaf-diseases-detection/runs/detect/exp.

## Jupyter Notebook file for demonstration
- [Training_Tomato.ipynb](Training_Tomato.ipynb)
## labelImg's source folder for image labeling
- [Source folder](labelImg)
- [Original repository](https://github.com/HumanSignal/labelImg)
## Dataset folder
- [sample_16_12_2023](sample_16_12_2023)
## Path file to dataset folder directory
- [path.yaml](path.yaml)
## Trained weight for demonstration
- [Pre-trained Weight](weightsDemo/weight_5_classes)
## Project report
- [Final Report](<Tomato Leaf Disease Detection Using YOLOv5 Model - Project report.pdf>)
