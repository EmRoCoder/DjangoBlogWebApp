# DjangoBlogWebApp
A web application for a blog using django

This blog web application was created using the web framework django on pycharm using python, html and a little css.

The app was conceived following the django documentation from https://docs.djangoproject.com/en/3.1/.
Building the app was also made mostly from following steps displayed on Corey Schafer's series of youtube tutorial named
"Django Tutorials" (2019) 

https://www.youtube.com/playlist?list=PL-osiE80TeTtoQCKZ03TU5fNfx2UY6U4p,

and on rare occasions using some of the code snippets from the GitHub code of the series 

https://github.com/CoreyMSchafer/code_snippets/tree/master/Django_Blog

Nevertheless, the blog was made very personal by chosing different layout options (like colours or title names) or content and users.

A lot of the code is based on classic django functions, shortcuts and synthax that may not be easy to understand to people not 
familiar with the framework. However, it was deliberately chosen to keep the code relatively scarcely commented to avoid it being
overcrowded with comments that might hinder general comprehension with too many details. For people not familiar with django and its usages,
it would be best to either get familiar with the django documentation or refer to Corey Shafer's series for a more detailed understanding.

Nonetheless, to better naviguate through this project, here are the main steps undertaken to complete the coding:

Create a new django project on PyCharm, run the project server with "$ python manage.py runserver" on the terminal and create applications 
within the project with "$ python manage.py startapp" followed by the app name on terminal (e.g. here $ python manage.py startapp Blog 
and $ python manage.py startapp Users). It is important to remember to add the created application to the project applications in settings.py

A second step is the creation different routes, i.e. url patterns to access different views for our web-application to have different
sections (e.g. home, about, admin, etc.).

Another step is the creation of diverse templates for our applications and the various pages it utilises. The creation of html templates greatly 
helps having efficient code and not copy-pasting all the time, mostly through our base.html template which will be used for most pages and can be elaborated
using different available nice-looking sample codes present online for nice layout. Both the base.html file and the static main.css file used code
from another source to have a nicer layout. The sample for both files are the same used in the series "Django Tutorials" mentioned above, with subsequent
slight modifications.

This provided a strong base for our blog web application. Most of the following steps were related to refine the utilisation possibilities and looks of the
website. Configurating the admin page and different users and profiles (also using python shell), but also refining routes and url patterns accordingly.
In the same idea, user registration, login, logout and creation of new post or change of password functions were created to ameliorate user experience,
also making the necessary modifications and additions to our code, e.g. by creating new templates, new routes, changing existing html files, updating database
and migrations, etc. Pagination was also implemented to give a nicer look to the web application. These new functionalities are nice in themselves, but also
provide good opportunities for further web development. Adding all of this generated a lot of new code that may seem overwhelming at first, however, 
names of classes, functions, templates, etc. were chosen as to remain as clear as possible and to conform to django common usage.
The code will therefore be clear to people used to the django framework.


Ps: The content and profiles of the app are deliberately silly both to give a sense of real content and for my own amusement


