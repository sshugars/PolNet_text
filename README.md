# PolNet 2022
Materials for PolNet 2022 Workshop on Text "Methods at the Intersection of Network and Text Analysis" led by Sarah Shugars. This repository includes all slides, code, and dataset used for the workshop. Below are instructions on how to use the included code yourself. There are two options depending on your comfort with Python:
1. If you are new to Python/don't have Python installed locally, you can use [Google Colab](https://drive.google.com/drive/folders/1SyKkUETUvmWZbpzYxn2aTKvZvWyWCyi3?usp=sharing) to run this code. This requires a Google account and is fully integrated with Google Docs.

2. If you have have your own Python set up, you are welcome to download and run this code on your own machine.


# Getting started with Google Colab
First, go to this workshop's [Google Drive Folder](https://drive.google.com/drive/folders/1SyKkUETUvmWZbpzYxn2aTKvZvWyWCyi3?usp=sharing). This folder includes all the same material as this GitHub Repo. 

By default, this folder will be added to the "Shared with me" portion of your Google Drive. In order for Google Colab to be able to access the included data you will need to add it to your Drive. You can do that from within Google Drive by navigating to "Shared with me" in the left menu and finding the folder `PolNet_TextNetworks`. Left click on the folder to bring up the options menu and select "Add shortcut to Drive." In the following menu, click "Add Shortcut" to add this link to "My Drive".

Once the shortcut is added, click back into the `PolNet_TextNetworks` folder. Now, double click to open the code file `PolNetWorkbook.ipynb`. This will automatically open in Google Colab and provide an interface you can use to run code and interact with the data.

Note that this folder is **read only** meaning that you will not be able to save any changes you make. You may want to save your own copy of the notebook as you follow along.

# Running this code locally
If you already have Python installed on your machine. you may want to run this code locally. Click on the green "Code" button in the upper right to download a .zip file with all these materials. `requirements.txt` includes all the packages and their dependencies needed to run this code. Specifically, you will need to have `juptyerlab` installed along with the following packages:
* beautifulsoup4
* matplotlib
* networkx
* numpy
* sklearn
* spacy

You will also need to download SpaCy's small English language model. This can be done from the terminal using: 
```
python -m spacy download en_core_web_sm
```

See the [SpaCy Documentation](https://spacy.io/models/en) for more information.


# Getting started with Python
If you do not already have a Python environment set up on your computer, but would like to, you can start by installing Anaconda by going to https://docs.anaconda.com/anaconda/install/ and following the instructions for your operating system. 

Once Anaconda is installed, you can launch Jupyter Notebook by following the instructions here: 
 https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html.
