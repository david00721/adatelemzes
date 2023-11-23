
# University Data Analysis Project

his repository contains the necessary environment dependencies and source files for the project. I've used Poetry to manage the project's dependencies.

## Setting Up the Environment with Poetry

### Prerequisites

Before you begin, make sure you have the following installed:

1.  **Visual Studio Code (VS Code):**
    
    -   If you don't have VS Code installed, you can download it from [here](https://code.visualstudio.com/).
2.  **Poetry:**
    
    -   If Poetry is not installed, you can install it using the following command:
		> pip install poetry

### Steps to Set Up the Environment

1.  **Clone the Repository:**
    
2.  **Install Dependencies with Poetry:**
   
    `poetry install` 
    
    This command reads the `pyproject.toml` file and installs the project's dependencies.
    
3.  **Activate the Virtual Environment:**
    
    `poetry shell` 
    
    Activating the virtual environment ensures that you are working in an isolated environment with the project's dependencies.
    
4.  **Open the Project in VS Code:**
    
    `code .` 
    
    This command opens the project in Visual Studio Code.
    
5.  **Set the Virtual Environment as Default Python Interpreter:**
    
    -   Open the command palette in VS Code (press `Ctrl + Shift + P` or `Cmd + Shift + P` on macOS).
    -   Type "Python: Select Interpreter" and select it.
    -   Choose the virtual environment created by Poetry (it should be in the project's `.venv` directory).
    -   VS Code will now use this virtual environment as the default Python interpreter for the project.
