## Library management using python & MySQL
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

```
Dev/Editor: Pavan Ananth Sharma & MK Akash
```
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Introduction:

This is an intermediate project which is a user-friendly library management system that allows you to:
- Add book with details
- Delete books
- View listed books
- Issue books to students/anyone
- Return books
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

> Output:

<center><img src = "https://user-images.githubusercontent.com/86551444/141800135-68801eeb-3dff-4808-b700-f1e0ce6758af.PNG"/></center>

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>Dependencies:

- tkinter
- pillow
- pymysql
- MySQL should be instaled

Code to download dependencies:
```
pip install tk
pip install pillow
pip install pymysql
```
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>_Note: we need to install tk which is tkinter and pillow which is PIL, so dont worry and install these dependencies using the above code._

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>❗ IMPORTANT STEP ❗

- Make sure you have installed MySQL for your OS, if not follow this video : ```https://www.youtube.com/watch?v=N3B3OonC2AU&t=343s ``` *Not sponcered*
- Follow the above video carefully and we recommend to use the password as ```root``` 
- After you have successfully installed and tested now you will need to run a few commands before running the ```main.py```
- Open ``` MySQL 8.0(or any version) Command Line Client``` using windows key and searching it if you use windows
- Enter the password in this case we use ```root```
- then we run ```show databases;``` to show the existing databases
- We add our data based which we will call `db` code for it : ```create database db;```
- Then we run : ```create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));```
- Last but not the least we enter: ```create table books_issued(bid varchar(20) primary key, issuedto varchar(30));```
- *So basically we created 2 tables inside a database named db with multiple access elements*
- Now to enter into the database you have created use teh code: ```use db;```
- Now to ckeck the tables you have created you can say ener : ``` show tablesl;```
- To see the elements inside the tables (for example books) code: ```select * from books;```
- Similarly to use the elements insie the table ```books_issued``` run the code: ``` select * from books_issued;```
- 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
























