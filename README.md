# Project README

## Project Overview
Welcome to the python_tourism_chatbot. This project is built using Python and Flask, a lightweight web framework. 
To ensure the project runs seamlessly and dependencies are managed properly,
it is recommended to run the application within a virtual environment.

## Prerequisites
Before getting started, ensure you have the following installed on your system:
- Python (version [specific version, e.g., 3.8+])
- pip (Python's package manager)

## Setting Up a Virtual Environment
Follow these steps to create and activate a virtual environment for this project:

### Step 1: Clone the Repository
First, clone the repository to your local machine using:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Step 2: Create a Virtual Environment
Create a virtual environment using the `venv` module:
```bash
python -m venv venv
```
This command will create a directory named `venv` in your project folder, containing the virtual environment.

### Step 3: Activate the Virtual Environment
Activate the virtual environment based on your operating system:

- **Windows**:
  ```bash
  venv\Scripts\activate
  ```

- **macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

Once activated, you should see the virtual environment's name (e.g., `venv`) in your terminal prompt.

### Step 4: Install Dependencies
With the virtual environment activated, install the required dependencies:
```bash
pip install -r requirements.txt
```

This command will install all the necessary packages specified in the `requirements.txt` file.

### Step 5: Run the Application
Start the Flask application using:
```bash
flask run
```

The application should now be running, and you can access it by navigating to `http://127.0.0.1:5000/` in your web browser.

## Deactivating the Virtual Environment
When you are done working on the project, deactivate the virtual environment by running:
```bash
deactivate
```

## Additional Notes
- Ensure that any new dependencies installed during development are added to the `requirements.txt` file using:
  ```bash
  pip freeze > requirements.txt
  ```

Feel free to reach out with any questions or issues while setting up or running the project. Happy coding! 🎉
