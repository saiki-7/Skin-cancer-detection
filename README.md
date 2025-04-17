<h1 align="center">Skin Cancer Classification using Computer Aided Diagnosis</h1>

# Introduction

Skin cancer is a serious and growing health concern, affecting millions of people worldwide. Early detection and accurate diagnosis are crucial for improving patient outcomes, yet current diagnostic methods can be time-consuming and error-prone. This is where machine learning comes in - by leveraging large amounts of data and powerful algorithms, machine learning has the potential to revolutionize the field of skin cancer classification.

## The problem we tried to solve

_The first step to identify whether the skin lesion is malignant or benign for a dermatologist is to do a skin biopsy. In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report. This project aims to shorten the current gap to just a couple of days by providing the predictive model using **Computer-Aided Diagnosis (CAD)**. The approach uses **Convolutional Neural Network (CNN)** to classify seven types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively._

## Motivation

A dermatologist will perform a skin biopsy to determine if the skin lesion is benign or malignant (cancerous).
The dermatologist removes a portion of the skin lesion during the skin biopsy and studies it under a microscope.
Obtaining a dermatologist appointment and receiving a biopsy report currently takes around a week or more.
The goal of this research is to use computer-aided diagnosis (CAD) to provide a prediction model that will reduce the present gap to a matter of days.
The method analyses photos of outlier lesions to classify nine different forms of skin cancer using convolutional neural networks (CNN). This gap closing has the potential to favourably affect millions of individuals.
We aim to reach a high level of accuracy and generalization on unseen data, which is an important factor for clinical adoption.

## Data Set

https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000


## Steps to run this Repository
1. Download the zip folder in your system / device.
2. Download node.js from your default browser, (Node.js v22.12.01)
3. Refer this link for downloading node ("https://nodejs.org/en")
4. For detailed steps follow this link on how to install node.js ("https://nodejs.org/en/download/package-manager")
5. After downloading node.js, run the command "Get-ExecutionPolicy".
6. If output is restricted then, Open Windows Powershell as Administrator and run the command "Set-ExecutionPolicy Unrestricted". The Output for "Get-ExecutionPolicy" should change to unrestricted. For reference you can use this link ("https://youtu.be/ChRef6Z8UD4?feature=shared")
7. Extract the folder and run it in an IDE (for eg: VS Code).
8. Open a new terminal and make sure your path is correct (....\skin-cancer-classification-main)
9. In the terminal write "npm install" or "npm i". 
10. After installing dependencies if there are any issues or vulnerablities then in the terminal write "npm audit fix --force". This should resolve any issues in dependencies.
11. Making sure the path is correct again, enter command "node index.js" in the terminal
12. The server will start and you can access the web interface by going to "http://localhost:3000"
13. Click a photo of your naked hand with good lighting and upload the image to the website.
14. For sample images we have included a folder named "sample_images", you can use those or upload your own skin images to get the results.
15. Make sure you use "http", and not "https" for accessing the web as it may not function as intended.
16. You can upload images of skin lesions and get the classification result in real-time.
17. Also to assist the users we have included an FAQ section in the About Page of our website so that any common queries could be answered.              
18. Please use the page to assist yourself in using the website and how to get results by uploading images or skin lesions.               
19. If you want to access this website using mobile phone to capture realtime images use the following website link ("https://skinvision-ai.onrender.com/")

## library versions used

numpy==1.26.4        
pandas==1.5.3          
scikit-learn==1.6.0                               
torch==2.5.1+cu118            
torchvision==0.20.1+cu118             
matplotlib==3.9.2              
scipy==1.10.1             
Pillow==9.5.0               
tqdm==4.66.6                  
joblib==1.2.0                   
streamlit==1.21.0                  
flask==2.2.2                     

These are some library versions used for the project.
For a full list of dependencies, refer to `requirements.txt`.