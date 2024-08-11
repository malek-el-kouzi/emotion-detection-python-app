# Emotion Detection App

This project is an emotion detection application built using Django. It utilizes machine learning techniques to classify emotions from input data.

## Getting Started

Follow these steps to set up and run the application:

### 1. Create a Virtual Environment

Create a virtual environment to manage your project dependencies.

```bash
python -m venv myenv
```

Activate the virtual environment:

- **Windows:**
  ```bash
  myenv\Scripts\activate
  ```
- **Mac/Linux:**
  ```bash
  source myenv/bin/activate
  ```

### 2. Install Django

Install Django version 3.2.0 using pip:

```bash
pip install django==3.2.0
```


### 3. Install Project Dependencies

Ensure you have a `requirements.txt` file listing all necessary packages. Install the dependencies:

```bash
pip install -r requirements.txt
```

### 4. Create a Django App

Create a new Django app within your project:

```bash
python manage.py startapp <app_name>
```

### 5. Configure `settings.py`

Update the `settings.py` file inside your project directory to configure your app and database settings.

### 6. Initialize Database Tables

Run the following command to create the necessary database tables:

```bash
python manage.py migrate
```

### 7. Run the Development Server

Start the development server with:

```bash
python manage.py runserver
```

Your application should now be running at `http://127.0.0.1:8000/`.


## Acknowledgements

- Django Documentation
- Emotion Detection Algorithms


