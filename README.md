
# Brightwind Tutorial
Tutorial, demonstrating how to download open-access wind resource datasets from Brighthub and use the Brightwind Python library to plot essential wind assessment charts.

The tutorial will follow a workflow, utilising a software stack that all Python developers should be familiar with - downloading a repository from Github, initiating a virtual environment, pip installing requirements and running a Jupyter notebook.

## Prerequisites
Before you begin, ensure you have met the following requirements:

### Python 3+
To check that you have Python 3 installed, open a terminal (Bash or Command Prompt) and enter:

```bash
python --version 
# or try python3 --version
```

### Git
Git is used to clone the repository from Github. 
To check that you have Git installed, open a terminal (Bash or Command Prompt) and enter:

```bash
python --version 
# or try python3 --version
```
If you don't have Git installed, you can download it from [git-scm.com](git-scm.com).



## Getting Started

### Clone Repo

Clone the repo (Or download and `unzip` the repo from the [github repo](https://github.com/dancasey-ie/brightwind-tutorial)):
```bash
git clone https://github.com/dancasey-ie/brightwind-tutorial
```

### Activate Virtual Environment
```bash
cd brighthub-notebooks
python -m venv ./venv
venv\Scripts\activate # Windows CMD
# source venv/Scripts/activate # Windows Bash
# source venv/bin/activate # Mac/Linux
```

### Install Dependencies

#### Option 1: From requirements.txt file

```bash
pip install -r requirements.txt
```

#### Option 2: Independently
```bash
pip install notebook
pip install brightwind
```
### Downloaded Data
Data for this tutorial is included in the [./data](./data) folder.

Demo Station data downloaded from [Brighthub - Demo Station](https://brighthub.io/measurement-location/9344e576-6d5a-45f0-9750-2a7528ebfa14/general)
- [./data/Demo_Station_measurement_data.csv](./data/Demo_Station_measurement_data.csv)
- [./data/Demo_Station_cleaning_log.csv](./data/Demo_Station_cleaning_log.csv)
- [./data/Demo_Station_data_model.json](./data/Demo_Station_data_model.json)

MERRA-2 reanalysis data downloaded from [Brightdata](https://brightdata.brightwindanalysis.com/)

- [./data/2697_MERRA-2_53.5N_-6.25E_1996-01-01_2023-11-30.csv](./data/2697_MERRA-2_53.5N_-6.25E_1996-01-01_2023-11-30.csv)

### Run Notebook

Run notebook and open in browser:

```bash
jupyter notebook
```

Navigate to notebooks/tutorial_1.ipynb