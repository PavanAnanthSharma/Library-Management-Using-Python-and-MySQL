## Library management using Python & MySQL
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

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
 >Usecase / run:

```  
if you want to run the code you will need to run : main.py
```

- If you have followed all the steps correctly as soon as you run ```main.py``` the UI will popup then as as soon as you add a book by filling the information(case sensitive), you can now get to the CLI of MYSql and run: ``` select * from books;``` and this will display if you have added any book into the database.
- Similarly after you have deleted any book you can run the same code to verify if it has been deleted from the database system.
- When you issue a book then if you want to check who have you given it to enter the code: ```select * fom books_issued;``` to find the name and book ID (bid).
- After you have created a book and then issued it to anyone you can see the status of the book change by again going into the ```books_issued``` table for that we use the code: ```select * from books;``` if you have followed you shouold see the change in the status of the book(if Avail before now it would have updated to issued).
- If you have got all of them then congratulations you have done an amazing job

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------        
>Wallet: 0x592eF244F8924be9F3F8803f8d639392f465Ac51

>Instagram: pavan_ananth

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------





















