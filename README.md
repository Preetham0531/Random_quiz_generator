# Quiz Generator Application

This repository contains a simple quiz generator application built using Python, with HTML templates for the web interface.

## Project Structure
- `app.py`: The main application script.
- `QuizGenerator.ipynb`: A notebook for quiz generation logic.
- `requirements.txt`: Python dependencies for the project.
- `Test1 - NLP.txt` and `Test2 - Universe.txt`: Sample quiz files.
- `templates/`: Folder containing HTML templates (`index.html` and `results.html`).

## Prerequisites
- Python 3.8 or higher
- [Git](https://git-scm.com/) for cloning the repository

## Installation and Setup

Follow these steps to clone the repository, create a virtual environment, install dependencies, and run the application:

### Step 1: Clone the Repository
1. Open a terminal.
2. Run the following command to clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/QuizGeneratorApp.git
```
Navigate to the project folder:
```bash
cd QuizGeneratorApp
```
### Step 2: Create a Virtual Environment
Create a virtual environment:

```bash
python3 -m venv venv
```
Activate the virtual environment:

macOS/Linux:
```bash
source venv/bin/activate
```
### Step 3: Install Dependencies
Once the virtual environment is activated, install the required dependencies with:

```bash
pip install -r requirements.txt
```
### Step 4: Run the Application
Run the application using:

```bash
python app.py
```
Open a browser and go to http://127.0.0.1:5000 to view the app.
