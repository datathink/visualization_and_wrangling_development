# Visualization and Wrangling Development
A Quarto version of J Hathaway's M335 Data Wrangling and Visualization course, condensed for DataThink onboarding/training/development.

The main reason this was done for easier editing and future development for datathink purposes. 

# Folder Structure
`_quarto.yml` Is a configuration file and Any document rendered within the project directory will automatically inherit the metadata defined at the project level. Meaning this file is where you specify layout, themes, and navigation links.

`index.qmd` Is the home page of our website and when previewed or rendered in vscode will render the whole website updated any changes you made on a project level. 

`qmd_files` Are the files that you actually edit. Inside this folder, there is other folders representing the pages of our website

`docs` Contains the output of the qmd_files as .html files readable by github pages. 

Note: the .yml file contains instructions that when index.qmd is rendered it outputs all .html files to the docs folder to be read by github. 
