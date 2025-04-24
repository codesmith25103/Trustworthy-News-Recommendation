# How to Run This Project

Follow the steps below to set up and run this project in a virtual environment.

------------------------------------------------------------
1. Make sure Python is installed (Python 3.6 or above recommended)
------------------------------------------------------------

Check if Python is installed:
    python --version

If not installed, download from:
    https://www.python.org/downloads/

------------------------------------------------------------
2. Create a Virtual Environment
------------------------------------------------------------

On Windows:
    python -m venv venv

On Mac/Linux:
    python3 -m venv venv

------------------------------------------------------------
3. Activate the Virtual Environment
------------------------------------------------------------

On Windows (Command Prompt):
    venv\Scripts\activate

On Windows (PowerShell):
    .\venv\Scripts\Activate.ps1

On Mac/Linux:
    source venv/bin/activate

------------------------------------------------------------
4. Install Required Packages
------------------------------------------------------------

Make sure you are in the same directory as the requirements.txt file, then run:

    pip install -r requirements.txt

------------------------------------------------------------
5. Run the Project
------------------------------------------------------------

Use the following command (example shown — replace with your actual main file):

    python main.py

------------------------------------------------------------
6. Deactivate the Virtual Environment (optional)
------------------------------------------------------------

To exit the virtual environment:

    deactivate
