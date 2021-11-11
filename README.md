Requirements (install in order if you get stuck use the web):

Python: https://www.python.org/downloads/

Pip: type: pip install Pillow in command prompt (which comes installed just type cmd on start)

Pycharm: https://www.jetbrains.com/pycharm/download/

Django: see step 1 line 3 to 5

DB SQL: https://sqlitebrowser.org/dl/


Steps:
1. Download the project I reccomend clicking the green 'code' button and the choose 'download ZIP'
   then open Pycharm and open the project by clicking on the open option and opening the download
   where you stored this project in your files(it usually is in the downloads folder) then open a terminal
   (located at the bottom of the pycharm screen) and type: python -m pip install Django if you are on Mac/Linux/Linux
   or py -m pip install Django if you are on windows. Then open DB browser SQL which you installed and click on Open
   Database and find the location where you downloaded the project double click on the folder and then
   double click on the file that says db.

2. Then open DB browser SQL which you installed and click on Open Database and find the location 
   where you downloaded the project double click on the folder and then click on the file that says db.
   Then go back to Pycharm and in the terminal and type: python3 manage.py migrate
   if you are on Mac/Linux or if you are on Windows type: python manage.py migrate then go to DB browser SQL
   and press ctrl + R to refresh it. Then go back to your terminal and type python3 if you are on Mac/Linux 
   or python on windows and then type manage.py create superuser and fill out the details if you don't want to
   write your email leave it empty ALSO NOTE: You will not see the password on the screen as you type it but note
   IT IS TYPING.

3. Then in your terminal type: python manage.py runserver if you are on Windows or if you are on 
   Mac/Linux type: python3 manage.py runserver then You should get a link which should usually be: 127.0.0.1:8000
   sometimes a portion of it like the part 8000 will be greyed out, if so the copy the entire link 
   manually(not by right-click and copy url) and paste it in your browser. Congrats you have your own Python-Shop
   and you are the admin of it. Click on accounts and type your Name and Password which you used in step 2.
   Congratulations!🎉 You have your own Python Shop!
