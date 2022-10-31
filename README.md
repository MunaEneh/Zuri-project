# Introduction
On the 23rd of September,2022 I started the Zuri training cohort II as a Fullstack (Frontend and Python) development trainee. This repo consists of my week 3 to 5 projects during the training. 

## Projects

### Week 5

#### Django CRUD (python) Project 

We would be building a simple song CRUD application. In our models.py file inside the “musicapp” application we created, you are expected to add the following Models and Attributes.

Model: Artiste, Song, Lyric
Attributes for “Artiste” : first_name, last_name, age
Attributes for “Song” : title, date released, likes, artiste_id
Attributes for “Lyric”: content, song_id
 
As you might have guessed, there is a relationship between all three Models. An Artiste can have multiple songs, and a song can have multiple lyrics.A song must only belong to one Artiste and a lyric must only belong to a song. You are to specify the foreignkey relationship yourself.
Also, the model field attributes should be specified by you. 
Push the task to GitHub when you finish and submit the GitHub repository link 


##### TASK EXPLANATION
<li> This task was done in Vscode.</li>
<li>Before you open VScode, you create a folder in your desktop. All files would be automatically saved in this folder.</li>
<li>Make Sure that the python extension is installed in VScode.
Open a new terminal, and create a virtual environment, you can give this virtual environment any name. The name of my virtual environment in this repo is "Zuri-django-project".</li>
<li>It is in this virtual environment that you install django.</li>
<li>Open a file in your workspace and name the file requirements.txt. It is in this file that you will pin all your dependencies.The dependencies are softwares required for your django project to run or work effectively. To pin these dependencies, simply type them into your requirements.txt file and assign their version using the "==" symbol. to check if the request has been satisfied. type the code "py -m pip install -r requirements.txt".</li>
<li>This code will make sure all the required dependencies have been installed. if they have been installed, your terminal will show you that the request has already been satisfied.</li>
<li> In your "musicapp" folder. Go to "models.py", open it. In this file you will fulfill the requirements by creating three models and giving them the attributes ascribed to them. For instance , the model artiste has the attribute (first_name, last_name, age).</li>
<li> In the "songcrud" folder, go to "settings.py", under installed apps, type "musicapp". Finally, you were told to find the key relationship between the three models and use foreignkey to specify this relationship. The relationship is Many to 1, which as already been hinted at by the use of the word ""foreignkey.</li>
<li>After all this , you move to the “musicapp” folder, and click on the “admin.py”. Here, you will register all your models. My models are (Artiste, Song, Lyrics).</li> 
<li>Now, in your terminal, you have to create a superuser, it is in this super user that you will set up your login info. All the info you put here will be used to access the admin page on your django.</li>
<li>To access and see the admin page. Type “py manage.py runserver”. When you click on the link which looks like this “http://127.0.0.1:8000/”. You will see that your django is successful. Now, to see the admin add “/admin” to the link. This will give you “http://127.0.0.1:8000/admin/” . This page will be a login page.</li>
<li>Now, enter all the info that you supplied to the superuser on your terminal in VScode. This should open your admin.</li>



