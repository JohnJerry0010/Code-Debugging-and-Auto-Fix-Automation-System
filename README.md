# Code-Debugging-and-Auto-Fix-Automation-System
This project uses AI to make finding and fixing bugs in code faster and smarter. It combines powerful models like CodeBERT to detect bugs and DeepSeek to suggest fixes. Instead of relying on manual debugging or rule-based tools, this system learns from real examples of code to understand and fix issues more accurately. 


#  Code Debugging and Auto-Fix Automation System

A Flask-based web application that allows users to upload Python code files and automatically detects and fixes bugs using AI models.

---

##  Getting Started

Follow these steps to get the project up and running on your local machine.

---

###  1. Unzip the File

Unzip the downloaded file:

- **Windows**: Right-click > "Extract All"
- **Mac/Linux**: Right-click > "Extract Here" or use terminal:
  ```bash
  unzip Bug-Detection.zip




###  2. Navigate to the Project Folder
cd Bug-Detection


### 3. Project Folder Structure

Bug-Detection/
├── app/
│   ├── models/
│   ├── routes/
│   ├── static/
│   └── templates/
├── config/
├── run.py
├── .env
├── requirements.txt
└── README.md


### 4.  Set Up Python Environment
Open terminal or CMD and navigate to the project folder:

cd path/to/Bug-Detection
(Optional but recommended) create a virtual environment:


python -m venv venv
Activate the virtual environment:

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate


### 5. Install Requirements
Install the required Python packages:

pip install -r requirements.txt

### 6. Create a .env File
Create a .env file in the project root folder with the following content:

HUGGINGFACE_TOKEN=your_huggingface_token_here
Replace your_huggingface_token_here with your actual token.

### 7. Run the Flask App
In the project root folder, run:


python run.py
Visit the app in your browser at:


http://127.0.0.1:5000
 ### 8. Done!
You can now upload .py files to detect and auto-fix bugs.

Optional
To stop the server:
CTRL + C
