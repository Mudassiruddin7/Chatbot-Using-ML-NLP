![Chatbot](https://www.chatinbox.io/wp-content/uploads/Chatbot-animation.gif)

# _**Conversational Chatbot using ML and NLP with Front End Framework**_
Conversational Chatbot is a peer-to-peer responsive agent. So, in this project we have used a combination of NLP and Deep Learning to train the agent to answers the questions asked by the user. The tools which we have used are TensorFlow to build the neural networks, nltk to process the text and numpy for manipulating the data and converting it to array, so that we can pass it to our neural network to process the information. Finally, we have integrated entire code with Tkinter GUI where we can have an interface type front end where we can interact with our agent. 

# _**Base Paper**_
+ https://www.researchgate.net/publication/353694361_Conversational_AI_Chatbots
+ https://www.analyticsvidhya.com/blog/2021/07/build-a-simple-chatbot-using-python-and-nltk

# _**Algorithm Description**_

# **TFlearn:**
TFlearn can be defined as flexible and transparent deeplearning aspects which are used in TensorFlow framework and providesus a higher-level application programming interface. It boosts up theexperiments which are performed during these tasks. It is very easy touse and easily understandable.

![TFlearn](https://dz2cdn1.dzone.com/storage/temp/12607066-iterative-deep-learning-fig-4.png)

**Reference**

+ https://www.geeksforgeeks.org/tflearn-and-its-installation-in-tensorflow

# **Lancaster Stemmer:**
Lancaster Stemmer is the most assertive stemming algorithm. It has an edge over the stemming techniques because it offers us the functionality to add our own custom rules in this algorithm when we implement this using the NLTK package. Sometimes the results are unexpected.

![Stemmer](https://mlr.cdn-apple.com/media/Speech_Recognition_1200x630_93b499fef8.png)

**Reference**

+ https://www.geeksforgeeks.org/introduction-to-stemming

# _**How to Execute?**_
So, before execution we have some pre-requisites that we need to download or install i.e., anaconda environment, python and a code editor.
**Anaconda**: Anaconda is like a package of libraries and offers a great deal of information which allows a data engineer to create multiple environments and install required libraries easy and neat.

**Download link:**

![Anaconda](https://1.bp.blogspot.com/-UJ1Ws2zZ9V4/TtMbG2ynJiI/AAAAAAAABbM/m6t2kuEhKdY/s1600/The-biggest-anaconda-snake-3.jpg)

https://www.anaconda.com/

**Python**: Python is a most popular interpreter programming language, which is used in almost every field. Its syntax is very similar to English language and even children and learning it nowadays, due to its readability and easy syntax and large community of users to help you whenever you face any issues.

**Download link:**

![Python](https://i0.wp.com/reptileworldfacts.com/wp-content/uploads/2019/05/male-blonde-super-tiger-reticulated-python.jpg?resize=351%2C351&ssl=1)

https://www.python.org/downloads/

**Code editor**: Code editor is like a notepad for a programming language which allows user to write, run and execute program which we have written. Along with these some code editors also allows us to debug, which usually allows users to execute the code line by line and allows them to see where and how to solve the errors. But I personally feel visual code is very good to work with any programming language and makes a great deal of attachment with user.

**Download links:**

![Vs code](https://schwabencode.com/contents/logos/VS2019-Badge.png) ![Pycharm](https://i0.wp.com/scracked.com/wp-content/uploads/2020/01/PyCharm-2019.3.4-Crack.png?fit=200%2C200&ssl=1)

+ https://code.visualstudio.com/Download, 
+ https://www.jetbrains.com/pycharm/download/#section=windows

# _**How to create a new environment and configure jupyter notebook with it.**_
Let us define an environment and why we need different environments. An environment is a collection of libraries that are required to run our project. When we already have an environment with the necessary libraries, why do we need a new environment?
To avoid version mismatches, we create a new environment for each project. For example, in your previous project, you used "tf env" with tensorflow 2.4 and keras 2.4, but in your current project, you must use tensorflow 2.6 and keras 2.6. If you continue your project in the "tf env" environment, there will be a version mismatch and you will need to update tensorflow and keras, but this will cause problems with the previous project's execution. To avoid this, we create a new environment with tensorflow 2.6 and keras 2.6 and resume our project.

# _**How to create an environment in anaconda.**_
+ Type “conda create –n <<name_of_your_env>>”
example: conda create -n env
+ It will ask to proceed with the environment location, type ‘y’ and press enter.
+ When you press ‘y’, the environment will be created. To activate your environment type conda activate <<your_env_name>> . E.g., conda activate myenv.
+ You can see that the environment got changed after conda activate myenv line. It changed from “base” to “myenv” which means you are now working in “myenv” environment.
+ To install a library in your virtual environment type pip install <library_name>.
e.g., pip install pandas
+ Instead of installing libraries one by one you can even install by bunch, i.e., we have a txt file called requirements.tx which consists of all the libraries required to proceed with the project, so we can use it.
+ so, before installing requirements.txt, make sure you are in the specific path where your requirements.txt is located, basically this file is located in the folder where our executable files are located, so we need to move to that directory by following command.
**cd C:\folder_name**
+ Here A -> drive, folder name -> path where your executable file is saved
+ I go to that file path in anaconda using cd command 
1.	Go to drive where your project file is.
2.	Go to the path of your project using cd <path>
3.	Type pip install –r requirements.txt 
+ And all your required libraries will be downloaded and you can start your project.
+ But if you want to use jupyter notebook on the new environment you have to set it up for the new environment.
+ After you have installed all the libraries and created an environment, you need an editor to run the code, that is starting jupyter notebook, as soon as you enter jupyter notebook in the terminal you will definitely get this error. “Jupiter” is not recognized as an internal or external command.
So, to solve it it we have 2 commands.
1.	conda install –c conda-forge jupyterlab
2.	conda install –c anaconda python
Now you are ready to use jupyter on this environment and start with your project!

![thanks](https://media1.tenor.com/images/11ae4fcfc41bb9e66a0176fcfc38e695/tenor.gif?itemid=8486985)
  
  
# _**Steps to execute**_
**Note:** Make sure you have added path while installing the software’s.

1.	Install the prerequisites/software’s required to execute the code.
2.	Press windows key and type in anaconda prompt a terminal opens up.
3.	Before executing the code, we need to create a specific environment which allows us to install the required libraries necessary for our project.
•	Type conda create -name “env_name”, e.g.: conda create -name project_1
•	Type conda activate “env_name, e.g.: conda activate project_1
4.	Make sure you are in the correct path in your terminal, where you have saved your executable file/folder. E.g.: cd A:\project\AI\Completed\project_name, then press enter.
5.	Install necessary libraries from requirements.txt file provided.
6.	Run pip install -r requirements.txt or conda install requirements.txt (Requirements.txt is a text file consisting of all the necessary libraries required for executing this python file. If it gives any error while installing libraries, you might need to install them individually.)
7.	Run trainModel.py to train the Fully Connected Network on the dataset. You can change the number of epochs or layers accordingly, the current architecture gave good results with a ~95% accuracy on predicting tags.
8.      Run textChatbot.py for text based chatbot with GUI incorporated.
9.      Run voiceBot.py for voice recognition based chatbot.
10.	Before directly running the main.py file make sure you have trained the model with the modified dataset, which you can find in the dataset folder. 
•	Train the model again to make the chatbot use to the added intents. After training the model, the model will be saved in the model’s folder.
•	Now you can run python main.py to load and use the new model.

# _**Data Description**_
Whenever we are trying to make a chatbot we need to make a list of intents which we wanted our chatbot to follow. The intents consist of Tag, pattern, response and context set. Where tag represents What is the other person trying to ask a chatbot, Example: Greeting, Identification, Goodbye, Food, Sports, Movies etc. Pattern represents what question the person is asking, Response represents the type of response the chatbot is willing to give. As this is a simplechatbot the responses are randomly picked from the list of responses for that particular question the person is asking.

![Happy](https://media0.giphy.com/media/xT9C25UNTwfZuk85WP/giphy.gif)

 # _**Issues Faced.**_
1. We might face an issue while installing specific libraries.
2. Make sure you have the latest version of python or 3.8, since sometimes it might cause version mismatch.
3. Adding path to environment variables in order to run python files and anaconda environment in code editor, specifically in visual studio code.

# _**Note:**_
**All the required data hasn't been provided over here. Please feel free to contact me for any issues. You can also download the dataset from the given link below.**

### _**Let’s Connect**_

<a href="https://linkedin.com/in/mudassiruddin21" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="mudassiruddin21" height="30" width="40" /></a>

![Connect](https://media2.giphy.com/media/l1O6zvqu7O317887HF/source.gif)

# _**Yes, you now have more knowledge than yesterday, Keep Going.**_
![Happy](https://media.giphy.com/media/GK7grZYLG7cs0/giphy.gif)
  

