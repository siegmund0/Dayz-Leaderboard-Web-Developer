# Dayz-Leaderboard-Web-Developer

//@Siegmund Oaki website developer - 2019.

//Mod Developer: @QuickZ.



## YOU NEED PYTHON BE INSTALLED
Download: https://www.python.org/

**This is _extremely_ important**
**Install python and check your windows PATH folder. You need install python PATH**
Like This:
<img src="https://i.imgur.com/qVqc34E.png" />

## NEXT
**Exectute the following command*** 
```py -m pip install mysql-connector``` 
if you don't have python path installed this command will not work



# Intructions for Leaderboard instalation:

1- You need a mysql-.json folder intermediate or just enter the json manually in Database (script.py)

2- Start Xampp or the program you use to run the database and the web

3- Copy and Paste Stats.php in Htdocs
They have to have some web mounted later prepared to accommodate the files within it. In any case, the .PHP is already configured to have a very basic website.

4- Create database with any name, within it create the tables that appear in "script.py". They have to be in the same order and be called in the same way. (you can modify it if you want)

  -You have to keep in mind to mark the option "id" as the main one. The database will accommodate the files in their corresponding rows     using the "id".

<img src="https://i.imgur.com/7o14JSC.png" />

<img src="https://i.imgur.com/cHrolv6.png" />

5- Huala... already have your player database

6-Always remember to have your script running

<img src="https://i.imgur.com/tI0iXNe.png" />

<img src="https://i.imgur.com/hRALXLJ.png" />

<img src="https://i.imgur.com/BoI3TOL.png" />

## Note: In my case I use a python-based broker. But you can find other examples based on php and Bootstrap4


### Points to consider:

The .json files are located in the "Profiles" folder of the dayzserver (or the name given to it)
The broker with the "script.py" database makes modifications every 60 seconds in case the file has changed.
The "script.py" does NOT replace the data in the database, it only updates them if they change.

enjoy!
