Meetme - SEGFAULT!
===================
I'll get through the setup process. Let's get started. 

Setup - [Django + PyCharm]
-------
 - Download [PyCharm Professional Edition](https://www.jetbrains.com/student/). Its free for students. So create an account with you asu.edu ids and download the professional edition. It will serve as out Django IDE.
 - Inside PyChram, hit **[CTRL + ALT + S]** to getting to <i class="icon-cog"></i> **Settings** dialog. In that select project interpreter as Anaconda and below that use the <i class="icon-plus"></i> icon to search for django and install the package. 
  
	>**Note:**
	>  Django version has to be **1.8.x**. Otherwise, it will lead to compatibility issues. 
 - After installing django framework, restart the IDE. Use this PyCharm tutorial for [Git Integration](https://www.jetbrains.com/pycharm/help/using-github-integration.html) .
 - Clone the [repository](https://github.com/tharun93/MeetMe-Segfault.git).
 - Open **manage.py** and click **[CTRL + ALT + R]** to open the **manage.py@Meetme_Segfault** terminal. This is where you will execute your django commands. [Commands in [django documentation](https://docs.djangoproject.com/en/1.8/topics/auth/default/), that are like `python manage.py runserver` is run in this terminal as `runserver`]

 

	> **Tips** 
> 
 >- All modules like login/signup will be created as an app.   I haven't
   explored the built-in templates.   You can create an app using
   command: `startapp <appname>`. Files will be automatically generated.
   >- `model.py`is the file where you will define your databases.
   >- [Django with MongoDB Engine](https://django-mongodb-engine.readthedocs.org/en/latest/tutorial.html) is very useful, since Django does not come bundled with Engine for MongoDB.
  
Let's do this! :)