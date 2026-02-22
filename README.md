# Alzheimer-s-Disease-Detection-System
Alzheimer's Disease Detection System is a Django-based web platform for early AD diagnosis. It integrates patient registration, appointment scheduling, medical record management etc. It uses a pre-trained EfficientNetB0 CNN model to classify MRI scans into NonDemented, VeryMildDemented, MildDemented &amp; ModerateDemented stages with ≥90% accuracy.

A web-based healthcare platform that enables **early detection of Alzheimer's Disease (AD)** using deep learning on MRI brain scans, combined with full patient & hospital management features.

## Project Overview

This system uses a **pre-trained EfficientNetB0 CNN model** (with transfer learning) to classify MRI images into four stages:

- NonDemented
- VeryMildDemented
- MildDemented
- ModerateDemented

Achieves **≥90% prediction accuracy** on the Kaggle Alzheimer's Dataset.

The Django backend provides secure user management, appointment booking, payments, referrals, prescriptions, and online report access — making it useful for patients, doctors, hospitals, and admins.

## Key Features

- Secure user authentication & role-based access (Admin, Doctor, Patient, Hospital Staff)
- Patient registration & profile management
- Online appointment scheduling & doctor availability
- MRI upload → Real-time Alzheimer's stage prediction
- Medical records, prescriptions & referral system
- Responsive UI with Tailwind CSS
- Scalable: supports up to 500 concurrent users @ 99.9% uptime

## Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, Tailwind CSS, JavaScript
- **Database**: SQLite3 
- **Machine Learning**: TensorFlow, Keras, EfficientNetB0 (transfer learning)
- **Image Processing**: OpenCV, NumPy, Pandas
- **Other**: Pillow (image handling)

  
## Install dependencies
pip install -r requirements.txt

## Run the server
python manage.py runserver

## SCREENSHOTS

<img width="880" height="551" alt="image" src="https://github.com/user-attachments/assets/b29a00c4-5600-4422-84ab-e8c69a4f8b7d" />
<img width="880" height="516" alt="image" src="https://github.com/user-attachments/assets/d9f3352a-bc24-4280-aee4-a996ef0d8812" />
<img width="880" height="537" alt="image" src="https://github.com/user-attachments/assets/a273f803-d273-4bcf-b1b1-d429457f090d" />


