# Hawaii Climate
<p>This repository contains a Python project that implements a Flask API that retrieve climate information from Hawaii area that helps to perform climate analysis.
The current implementation implements the following objectives:
- USe Python and SQLAlchemy to perform basic climate analysis and data exploration of a climate database.
- Implement a Flask API to retrieve the climate observations and the daily normals for a give time range. 
## Data
[Hawaii Climate Data](https://github.com/aidinhass/bbbioboard/blob/master/bbbioboard/data/int/hawaii.sqlite)

## Report

## Requirements
- flask 1.0.2 
 
## Directory Structure
```
.
├── docs                <- Documents related to this project.
├── images              <- Images for README.md files.
├── notebooks           <- Ipythoon Notebook files
├── reports             <- Generated analysis as HTML, PDF, Latex, etc.
│   ├── figures         <- Generated graphics and figures used in reporting.
│   └── logs            <- Generated log files.  
└── bbbioboard
    ├── conf
    ├── data            <- data utilized in this project.
    │   ├── ext
    │   ├── int
    │   └── raw
    ├── src             <- Source files used in this project.
    ├── static          <- CSS files.
    └── templates       <- Flask templates 
```
## Installation
Install python dependencies from  `requirements.txt` using conda.
```bash
conda install --yes --file requirements.txt
```

Or create a new conda environment `<new-env-name>` by importing a copy of a working conda environment at the project root directory :`bbbioboard.yml`.
```bash
conda env create --name <new-env-name> -f bbbioboard.yml
```
## Usage
```bash
python run.py

```
## References

## To Do

## License
MIT License 

