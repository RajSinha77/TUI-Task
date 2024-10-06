# TUI-Task

Make sure to use setup Python v3.9.13 or above, use requirements.txt to install all dependencies alternatively you can also use pipenv to setup your Python enviournment.
```bash
project/
├── TUI_Cruises_task.pynb       -- Contains Analysis & Code
├── requirements.txt         -- Contains all libraries/requirements to be pre installed before running code
├── data.csv	            -- contains data for this task
├──schema.pdf            -- Contains data columns descriptions
├──Task Description.pdf            -- Contains task description 
```
Usage
To use this project, follow these steps:

 1. **Clone the Repository:**
   ```bash

git clone https://github.com/RajSinha77/TUI-Task
cd TUI-Task
```

2. **Explore the Jupyter Notebooks:**
   - After cloning the repository,  explore the analysis by running the provided Jupyter Notebooks (TUI_Cruises_task.ipynb)
   ```bash
   jupyter notebook
   ```

   
### Exporting a Jupyter Notebook
Jupyter Notebooks can be exported using `nbconvert` (`pip install nbconvert`). For example, to export the example notebook to html: `jupyter nbconvert --to html examples/TUI_Cruises_task.ipynb --embed-images --output TUI_Cruises_task.html`

Disclaimer: Since this Pynb file uses the Plotly library, it is interactive and creative but at the same time will be heavy. Please have patience.
