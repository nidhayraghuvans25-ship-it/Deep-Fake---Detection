# Deep-Fake---Detection
r: Provides a complete end-to-end web application architecture where users upload images or video frames to get real-time deepfake confidence scores.
The project requires the following packages:

numpy
pandas
scikit-learn
tensorflow
keras
opencv-python
dlib
matplotlib
tqdm
Setup
cd deepfake_detection_model
Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required packages:
pip install -r requirements.txt
Usage
Dataset Preparation:
Open Dataset_Preparation.ipynb and run the cells to prepare the dataset.

Frame Selection and Face Alignment:
Open Frame_Selection_and_Face_Alignment.ipynb and run the cells to select frames and align faces. This is only for understanding purposes the script has been added in the Dataset Preparation Notebook

RGB Training:
Open RGB_Training.ipynb and run the cells to train the model on RGB data.

SRM Training:
Open SRM_Training.ipynb and run the cells to train the model on SRM data.

Xception Model:
Open Xception.ipynb and run the cells to use the Xception model for classification.

Acknowledgments
This project utilizes various open-source libraries and resources. Special thanks to the contributors and maintainers of these projects.
