# AI-ML Repository
This repository contains various AI/ML projects categorized into subdirectories. Each project is self-contained with its own dependencies and notebooks.  
## Prerequisites
Ensure you have Conda (Anaconda or Miniconda) installed on your system.
## Setup Instructions  
Follow these steps to set up and run any project within this repository.
#### 1. Navigate to the Project  
Open your terminal or command prompt and change into the directory of the project you wish to run:  
```bash
cd AI-ML/your-chosen-subdirectory
```
#### 2. Create the Conda Environment
Each directory contains an environment.yml file. Run the following command to create a new environment named env:  
```bash
conda env create -f environment.yml -n env
```  
#### 3. Activate the Environment  
Once the installation is complete, activate the environment:  
```bash
conda activate env  
```
## Launching Notebooks in the Browser  
Since Jupyter is already included in the environment, you can launch it directly from the terminal.  
#### 1. Start the Jupyter Server:  
With the env environment active, run:  
```bash
jupyter notebook
```  

#### 2. Open in Browser:  
* A browser window should open automatically.
* If it doesn't, look at the terminal output and copy the URL starting with `http://127.0.0.1:8888/tree?token=...` and paste it into your browser.  
#### 3. Select your Notebook:  
Click on the `.ipynb` file you wish to explore.  
## Summary of Common Commands
| Action                | Command                                      |
|----------------------|----------------------------------------------|
| Create Environment   | `conda env create -f environment.yml -n env` |
| Activate Environment | `conda activate env`                         |
| Launch Jupyter       | `jupyter notebook`                           |
| Deactivate           | `conda deactivate`                           |
| Remove Environment   | `conda env remove -n env`                    |
