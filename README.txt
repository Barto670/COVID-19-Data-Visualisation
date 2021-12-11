*************************************************
Packages needed for it to compile:

pip install widgetsnbextension 
pip install ipywidgets 
pip install voila
pip install pygal
pip install csv

Used to format the code correctly:
pip install autopep8
jupyter nbextension install https://github.com/kenkoooo/jupyter-autopep8/archive/master.zip


Versions of applications:

Version of Python : python3.8.3

Selected Jupyter core packages...
IPython          : 7.28.0
ipykernel        : 6.4.1
ipywidgets       : 7.6.5
jupyter_client   : 6.1.12
jupyter_core     : 4.8.1
jupyter_server   : 1.11.1
jupyterlab       : 3.1.18
nbclient         : 0.5.4
nbconvert        : 6.2.0
nbformat         : 5.1.3
notebook         : 6.4.4
traitlets        : 5.1.0

************************************************
Before doing the bottom first go to https://github.com/CSSEGISandData/COVID-19 to download the Covid-19 data and place it in the folder of the program
************************************************

1)Navigate to the folder using Command Prompt
Execute the following from 2) and 5 a)
2) jupyter notebook Covid.ipynb                   # to see the source code and run jupuyter notebook
3) http://localhost:8888/notebooks/Covid.ipynb    #Jupyter notebook will open with the code
4) Make sure that at the top of Jupyter Notebook it sais "Trusted", if not click to make it trusted
5)Do one or the other:
	5 a) voila Covid.ipynb                    # to be able to run jupyter in a web-based visualisation
	OR
	5 b) or click on Voila button at the top of the opened Jupyter notebook

6) http://localhost:8866/                         #will display the web-based visualisation

*note that jupyter has to be run first so that the notebook is trusted*