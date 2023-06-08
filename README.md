# Text-Generator

1. Getting started

First you need to download stories.txt and .ipynb file into your google drive

Then change
'''
data = pathlib.Path('/content/drive/MyDrive/stories.txt') 
'''
to path where stories.txt located in your drive

Optional you can tnable GPU acceleration to execute this notebook faster. 
In Colab: Runtime > Change runtime type > Hardware accelerator > GPU.

2. Running Colab

First you need to download some libraries

'''
!pip install anvil-uplink
'''

Then you need to run entire Colab Notebook
After traing model can be used in web application

3. Web Application

Application is already ready on Anvil server, you just need to go to link

https://glamorous-tremendous-badger.anvil.app/

Then you just need to write your prompt in text box and push the button "GENERATE"
