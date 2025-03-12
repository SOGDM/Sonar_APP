# Sonar_APP
noise reduction in Sonar target Detection
Using Streamlit, I developed a small application based on DnCNN and Deformable DETR for denoising and object detection in sonar images. However, the detection performance is not very good, as the model was trained using only one-fifth of the original dataset and half of the intended epochs. The dataset can be found online ( https://openi.pcl.ac.cn/OpenOrcinus_orca ).

To run the application, enter the environment in the terminal and execute:
bash
streamlit run ./TD.py
