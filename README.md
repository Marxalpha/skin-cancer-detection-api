# Skin Cancer Detection App's Api

This is the backend for the Skin Cancer Detection App
Check it out here => [A web application for automated detection of skin cancer lesions using deep learning](https://github.com/saketh-pallempati/skin-cancer-detection-frontend).

## Features

- Upload skin lesion images for analysis
- Train and compare multiple machine learning models:
  - CNN
  - VGG16
  - VGG19
  - ResNet50
- Interactive visualization of model performance
- LIME explanations for model predictions
- User authentication system
- Admin panel for model management

## Tech Stack

- **Backend**: FastAPI, TensorFlow, SQLAlchemy
- **Frontend**: React, CSS
- **Database**: SQLite
- **ML Models**: CNN, VGG16, VGG19, ResNet50

## Setup and Installation

### Backend

```bash
cd backend
pip install -r [requirements.txt](http://_vscodecontentref_/0)
uvicorn app.main:app --reload
```
