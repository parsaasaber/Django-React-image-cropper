# Introduction
Welcome to the Django-React Image Cropper project! This repository provides a seamless solution for integrating image cropping functionality into your web applications using Django and React. Whether you’re building a content management system, a photo gallery, or any application that requires precise image manipulation, this project has you covered.

## Installation

### Backend Setup

1. Clone Repository: 
```
git clone https://github.com/parsaasaber/Django-React-image-cropper.git


cd Django-React-image-cropper
```

2. Create venv and activate it:
```
python -m venv .venv
source .venv/bin/activate  # On Windows use `.\.venv\Scripts\activate`
```

3. Install the required Python packages, which are already included as a "req.txt" file in this project:
```
pip install -r req.txt
```

4. Run the Django migrations:
```
python manage.py makemigrations
```
and then:
```
python manage.py migrate
```

### Frontend

1. Open a new terminal in command line and navigate to `front` directory:
```
cd front
```

2. Install the required npm packages, which are included in `package.json`. You just have to run the command below in the terminal:
```
npm install
```

### Run the project:
1. Navigate to `Backend` directory and run the project:
```
python manage.py runserver
```
2. In the other terminal, navigate to the `frontend` directory and start the application:
```
npm start
```