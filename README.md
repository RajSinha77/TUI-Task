# TUI-Task
#Description :

Analyze the provided dataset for two Cruise ships (Vessel 1 and 2) and develop a narrative explaining the performance trends (e.g.: efficiency, propulsion, power generation, etc.). This analysis can pertain to the vessel as a whole or its individual components. You can also select KPIs, based on international regulatory requirements for shipping.


#Requirements
Make sure to use setup Python v3.9.13 or above, use requirements.txt to install all dependencies alternatively you can also use pipenv to setup your Python enviournment.
```bash
project/
├── Code.zip                # Contains all analysis scripts and notebooks
├── Code.html               # Contains notebook for quick analysis
├── data.zip                # Contains data for the code
├── requirements.txt        # Contains all libraries/requirements to be installed before running the code
├── schema.pdf              # Contains data column descriptions
├── Task Description.pdf    # Contains task description and objectives

```
Usage
To use this project, follow these steps:

 1. **Clone the Repository:**
   ```bash

git clone https://github.com/RajSinha77/TUI-Task
cd TUI-Task
```
2. After Cloning unzip the Code.zip, code.html & data.zip and place it in the same folder.

3. **Explore the Jupyter Notebooks:**
   - After cloning the repository,  explore the analysis by running the provided Jupyter Notebooks (code.ipynb)
   ```bash
   jupyter notebook
   ```

   
### Exporting a Jupyter Notebook
Jupyter Notebooks can be exported using `nbconvert` (`pip install nbconvert`). For example, to export the example notebook to html: `jupyter nbconvert --to html examples/code.ipynb --embed-images --output code.html`

Disclaimer: Since this Pynb file uses the Plotly library, it is interactive and creative but at the same time will be heavy. Please have patience.
For quick analysis, use code.html
