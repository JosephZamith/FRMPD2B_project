# Readme for TurboID_MS_plot_GitHub
Overview
This repository contains the Python Jupyter notebook 'TurboID_MS_plot_GitHub.ipynb' scripts that create graphs visualizing interactions among proteins and categorize proteins based on their functions.
The proteins visualised are the one of the TurboID FRMPD2B proteomic screen

Files
MS_results.xlsx - The Mass Spectrometry (MS) results Excel file, contains information on the proteins of the screen and their associated enrichment ratios.
prot_categories.xlsx - Excel file containing protein categories in multiple sheets. Each sheet represents a specific category and lists proteins falling into that category.
string_interactions_human.xlsx - The STRING database Excel file that contains interaction information for proteins. downloaded in the STRING website https://string-db.org/ with the list of these proteins as query.
prot_functions.xlsx (Generated) - Output Excel file containing all the protein symbols and their respective categories, created by the script.
graph_String_MS.pdf (Generated) - A PDF graph representing interactions between proteins, color-coded and sized based on categories and ratios respectively.

Scripts
Script 1: Creates a new Excel file (prot_functions.xlsx) that includes all the genes from the MS results (MS_results.xlsx) and associates them with their categories from prot_categories.xlsx.

Script 2: Produces two types of visualizations:
A large network graph saved as graph_String_MS.pdf, representing interactions between proteins. 
Node sizes are based on their ratios.

Script 3:
Subplots, saved as subplots_categories.pdf, each representing the network of a particular category of proteins.
Node colors and sizes are based on their categories and ratios.

Script 4: 
Generates a size legend (legendSize.pdf) for the network graph, helping users understand the relative enrichments based on the size of the nodes in the graph.

Requirements
Python 3.x
Pandas
NumPy
NetworkX
Matplotlib
Seaborn
