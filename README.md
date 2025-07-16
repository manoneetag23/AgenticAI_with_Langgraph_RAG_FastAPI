# Project Setup
This project setup provides instructions to set up your project environment, including setting up a Python virtual environment using Pipenv, pip, or conda.

### Create virtual environment
python -m venv myvenv

### Activate virtual environment
source venv/bin/activate

### Install all the requirements/dependencies
pip install -r requirements.txt

## Using Conda Environement Setup

### Create new conda environemnt 
conda create --venv myenv python=3.13

### Activate conda environment 
conda activate myenv

# Project Steps with Python Commands
Project consists of 3 major steps and three differents files were created using VS code
### Step 1: Cretaing AI agent
python ai_agent.py

### Step 2: Create Backend with FastAPI
python backend.py

### Step 3: Crete Frontend using Streamlit
python frontend.py
