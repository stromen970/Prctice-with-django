<h2>How to print hello world by using djago framework</h2>
<h2>These are the steps to follow for good programming</h2>
<ul>
  <li>
    Step1: Start project with this command "Django-admin startproject 'projectname'"
    Project name will be given by yourself.
    After creating projectname you want change directory from django envirnment to 
    project environment by using "cd" command
  </li>
  <li>step:2 Start your app by using this command "py manage.py startapp your app name"</li>
  <li>
    step:3 Go to settings.py file in inside inner project.
    In settings.py we have 'INSTALLED_APPS' is their we are adding your app inside installed_apps
  </li>
  <li>
    Step:4 Go to views.py file in inside your app and write your codes or logics in this views file
  </li>
  <li>
    Step:5 Go to urls.py file in inside your inner project.
    Here we want to import our app views and inside urlpatterns you are given your urls
  </li>
  <li>Step:6 Go to terminal type this command 'py manage.py runserver'</li>
  <li>step:7 Django generates one link like this 'http://127.0.0.1:8000/' click on this link.</li>
  <li>Step:8 Send request</li>
</ul>
