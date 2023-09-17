# Translate Colab Jupyter Notebooks
Colab Jupyter notebook to translate Jupyter notebooks 

Jupyter notebooks are very practical because they consist of text in Markdown cells and code cells, usually Python code, which can be run inside the document in the browser. This makes them interactive documents. But for translating Jupyter notebooks into a different language, the usual services, like DeepL, don't work. Examples are my Climate Change Calculated and Corona Computation Jupyter notebooks.

The presented Colab jupyter notbook takes on this task, using translation from txtai (https://pythonrepo.com/repo/neuml-txtai-python-indexing-and-performing-search-queries-on-data) to translate the markdown cells.

As input it takes a Jupyter notebook from Google Drive, and writes the translated version into the same directory.

To run it, open "translate_jupyter_gs.ipynb" in Colab (using the button), and then run the first cell to install txtai. This may take a while. Then run the 2nd cell to mount Google Drive, give access to your drive, including write permission. Then select the desired input Jupyter notebook file on the left pane of Colab, copy its path there, and paste it in the "filename" field of the 3rd cell. Below that, select the target language. Let the cell run and check if input and output file names are correct.

Then let the 4th cell run to do the actual translation. This might again take some time. The output file has the abbreviation of the target language appended to its base name in the same directory as the input file. The translation is usually not perfect, and needs some fixing.
For long documents, a high ram setting might be needed.

For long documents, "translate_jupyter_notebooks.ipynb" seems to work better,
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TUIlmenauAMS/TranslateColabJupyterNotebooks/blob/main/translate_jupyter_notebooks.ipynb)


Many greetings,
  Gerald Schuller, January 2022, updated September 2023

