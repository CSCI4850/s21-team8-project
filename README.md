# s21-team8-project 

# Chatbot Group 
### Members: Brooke Bound, David Brugger, Jake Hagenow, Lorenzo McDaniel and Paula Pamplona Ramirez


## Motivation
Our goal was to successfully train and build a chatbot that would accurately be able to answer predetermined questions users would give it.
Our inspiration for this project was based on previous Chatbots such as [Heek](https://techcrunch.com/2016/10/03/heek-is-a-chatbot-that-can-build-you-a-website/), [Amtrack's Julie bot](https://www.amtrak.com/about-julie-amtrak-virtual-travel-assistant), and [Hazel](https://www.chiefmarketer.com/hgtv-developed-hazel-new-chatbot/). After building and training the chatbot, we built an instant message like application where a user can interact with the chatbot. We designed our chatbot, Todd to be a Bakery Store Clerk. Our chatbot can respond to questions about the bakery, or even engage in small talk such as gossip or telling jokes. With the techniques we used building this application you can easily change the [intents](https://www.helpshift.com/glossary/intent-in-chatbot/) file to tailor the chatbot to wide variety of applications such as a discord bot or customer service.



![readme_images](https://github.com/CSCI4850/s21-team8-project/blob/main/readme_images/chatbot_demo.gif)

### Requirements:

- [Anaconda](https://www.anaconda.com/products/individual)

- [TensorFlow](https://www.tensorflow.org/) *( will need to install this package on your version of Anaconda)*


## Installation:

### Download repository files 
 
- You can click this link to download the files: <a  href="https://github.com/CSCI4850/s21-team8-project/archive/HEAD.zip"> Download Project </a> 

- After the download is complete, navigate to the file and unzip the contents.


### Install Anaconda

You will need to install [Anaconda](https://www.anaconda.com/products/individual) on your system.

*Anaconda is a python and R distribution. It aims to provide everything you need (python wise) for data science tasks.
Anaconda includes packages such as Scipy, Numpy, Pandas along with all their dependencies.*


### Launch Anaconda

Once Anaconda is installed on your computer, Anaconda will show up in your program files as Anaconda Navigator.
- Launch the application when it opens up you will see a multitude of different applications.
- Select **Jupyter Notebook** from the list of applications on the homepage.
- Upon launching jupyter notebooks, the program attempt to load up in your web browser. Once Jupyter notebooks is successfully loaded, a listing of your computers file system on should appear in your web browser. 


### Install TensorFlow 

Before you can launch the demo, you will need to install tensor flow for your version of anaconda.
Within a new notebook do the following: 
- To create a new notebook, in the Jupyter toolbar go to New and select Notebook - Python 3
- Inside this new notebook, click within the cell and type "pip install tensorflow". After running this cell, you will have to wait for the files to finish downloading to your system. 

- You can test that TensorFlow is properly installed by importing the TensorFlow package.
Within a new cell you can type the command "import tensorflow" or "import tensorflow as tf". If no errors occur after running one of these commands, then you have successfully installed TensorFlow on your version of Anaconda!

**Note** *You may need to restart the notebook/kernel for the changes to take effect.*


### Demo the Chatbot

- Inside Jupyter Notebook, navigate to the directory where you downloaded this repository's files.
- Navigate once more to the Demo directory, this is where you will find all the files needed to run the chatbot Demo.


- if you want to run demo with **pretrained model** select the notebook titled **"chatbot_PreTrained_Demo.ipynb"** or if you want to run demo with **added training** select the notebook titled **"Chatbot_Train_Demo_Combined.ipynb"**

- Once either notebook is open, in the notebook's toolbar, click the run command to run through the cells in the notebook. After running through either selected notebook, our 
chatbot gui will appear for demonstration.

Helpful Resources: 
- https://docs.anaconda.com/anaconda/user-guide/getting-started/
- https://www.codecademy.com/articles/how-to-use-jupyter-notebooks


