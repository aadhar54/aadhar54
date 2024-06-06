### Hi there, I'm **Aadhar** 👋 

I believe that "For a person who is ready to put in extra efforts, nothing is impossible."

<img src="https://img1.wsimg.com/isteam/stock/V5yGK9n/:/rs=w:1200,h:600,cg:true,m/cr=w:1200,h:600" height="200px"><img src="https://assets.leetcode.com/static_assets/marketing/2024-50.gif" height="200px">

DSA syntax : https://drive.google.com/file/d/1ao4ZA28zzBttDkuS6MLQI52gDs_CJZEm/view

Grokking System Design Book : https://drive.google.com/file/d/1qVYf8nbmoFh1nNtA9IrCNt_t5Dv2zkXD/view?usp=sharing

Grokking the Java Interview : https://drive.google.com/file/d/1kB8Rfc22f3m-b9wLbABRBxJBTrgGIWam/view?usp=sharing




<img src="./aadhar54.jpeg" height="200px">

Read my latest blog at https://aadhar.hashnode.dev/two-years-in-it ✅ <br/>
Please review my latest career portfolio at https://aadhar54.github.io/ ✅ 

## I'm a `prudent and motivated` Back End Developer , Teacher and self proclaimed Philosopher !!

- My dream is to spend my life `building products` and become a `Software Soldier` 🔭💛
- I believe in building long-lasting relationships that translate into high-performing teams. 
- I’m currently building projects with React and Spring Boot🔵
- I love to help people with doubts in projects ❤️
- 2021 Goals: Work to Level up my proficiency in `Typescript` 🔥
- Fun fact: I am an ardent fan of Indian Comedy Scene 🟩
- My favourite song is Iktara from Wake Up Sid 🌦️


### 📌 My technical skills include :

 - 💻 *Languages:*  <img align="center" height="30" src="https://img.icons8.com/color/144/000000/javascript.png"/> <img align="center" height="30" src="https://img.icons8.com/ultraviolet/480/000000/react.png"/>

 - 💻 *Front-End Development:* <img align="center" height="30" src="https://img.icons8.com/color/144/000000/html-5.png"/> <img align="center" height="30" src="https://img.icons8.com/color/144/000000/css3.png"/> <img align="center" height="30" src="https://img.icons8.com/color/144/000000/javascript.png"/> <img align="center" height="30" src="https://img.icons8.com/ultraviolet/480/000000/react.png"/> 

- 💻 *Work Experience:* I have worked in Tata Consultancy Services and Informatica for 3 years as a Software Engineer .I have also interned as a web developer with IIIT Hyderabad ,Utkarshini and Javatpoint  <img align="center" height="30" src="https://img.icons8.com/emoji/48/000000/rocket-emji.png"/>


### 📌 Here's a link to my [Portfolio](https://aadhar54.netlify.app/)


### 📌 Contact Me :

[<img align="center" height="40" src="https://img.icons8.com/color/48/000000/hot-article.png"/>](https://hashnode.com/@aadhar54)
[<img align="center" height="40" src="https://img.icons8.com/color/144/000000/linkedin.png"/>](https://www.linkedin.com/in/thebtechviral/)
[<img align="center" height="40" src="https://img.icons8.com/fluent/144/000000/twitter.png"/>](https://twitter.com/aadhar54)
[<img align="center" height="40" src="https://img.icons8.com/fluent/144/000000/instagram-new.png"/>](https://aadhar54.github.io/)

====
====
 
Querying Data with SQL in MariaDB 


SELECT CURDATE(); 
The script above is used to generate the current date in a string format. How would you generate it in a numeric format?
SELECT CURDATE() + 0;

 You are working on a table named Student that contains three columns: Name, Subject, and Marks. How would you describe the result of the SQL statement given below? 
 Result would be incorrect and mismatched.

You are working on a table named Marks that has four columns: Id, Math, Science, and Arts. How would you get Id and Math where items in Math are in ascending order?
SELECTS Id, Math FROM Marks ORDER BY Math;


You are required to create a stored procedure that retrieves outdated records from master data tables. For inactive records, a column named ActiveInd is set to 0 in every master data table. How would you create this stored procedure?
CREATE PROCEDURE FetchInactive ( param CHAR(100))
 BEGIN
 SELECT * FROM param WHERE ActiveInd = 0;
 END 
 
 You are working on tables A and B. The definitions of the tables are the same. You want to know the data records present in both tables. How would you find this information?
 (SELECT * FROM A) INTERSECT (SELECT * FROM B);


You have executed several SQL statements, but the changes are not reflected. You discover that auto-commit is disabled. How can you enable it?
SET autocommit = 1;

What is the default order of the SELECT query?
Your choice: correct -
No order

You are working on a table named Donations that contains columns Id (text), Prefix (numeric), and Suffix (text). There is a script to retrieve data which throws an error. 
SELECT Id, Prefix + Suffix AS Donation FROM Donations;
==>SELECT Id, CAST(Prefix AS CHAR(20)) + Suffix AS Donation FROM Donations;

You are working on two tables named Vendor and Customer that both require their columns to be updated to IsCustomer and IsVendor respectively. By default, the columns IsCustomer and IsVendor are set to 0. How can you update the respective columns for the records that are present in both tables by comparing the Id column of both tables?
UPDATE Vendor, Customer SET Vendor.IsCustomer = 1 , Customer.IsVendor = 1 WHERE Vendor.Id = Customer.Id;


 What is the difference between CURRENT_USER() and USER()?
USER() returns the username and hostname given when authenticating MariaDB, while CURRENT_USER returns the username and hostname from the MariaDB account that the server used to authenticate the current client.

 
What would be the result of the given script?
SELECT CASE BINARY 'B' WHEN 'a' THEN 1 WHEN 'b' THEN 2 END; 
NULL


 A coalesce script is given below:

 COALESCE(NULL, 1, NULL, 2, NULL, 3, NULL, 4);What is the output of the script?
 1
 
You are required to create a procedure that counts the number of rows of any table passed as an argument and store it in an output argument. How would you create this procedure?
CREATE PROCEDURE FetchData (IN param1 CHAR(100), OUT param2 INT)
 BEGIN 
 SELECT COUNT(*) INTO param2 FROM param1;
 END;


1. What would be the result of the given script? 
SELECT CASE BINARY 'B' WHEN 'a' THEN 1 WHEN 'b' THEN 2 END; 
 
        NULL 
 
2. How can you change the parameters of a stored procedure? 
 
        By dropping and replace the stored procedure 
 
3. A stored procedure calls CURRENT_USER(). What is the output of the call? 
 
        Owner of the procedure 
 
4. You are working on a table named "MaterialDiscount" that contains three columns: Product, Price, and 
Discount, where Discount is a ratio. How would you retrieve all data from the table, with an additional column 
calculating price after discount? 
 
        SELECT Product, Price, Discount, Price - Price*Discount AS 'Price after discount' FROM 
MaterialDiscount; 
 
5. The script SELECT 50/(5-5); throws an error:  ERROR_ON_DIVISION_BY_ZERO What could be the 
reason? 
 
        SQL mode is used. 
 
6. Which of the following is true about alias in a query? 
 
        It is a correlation name 
 
7. What is the difference between CURRENT_USER() and USER()? 
 
        USER() returns the username and hostname given when authenticating MariaDB, while 
CURRENT_USER returns the username and hostname from the MariaDB account that the server used to 
authenticate the current client. 
 
8. You are working on a table named Donations that contains columns Id (text), Prefix (numeric), and Suffix 
(text). There is a script to retrieve data which throws an error. 
SELECT Id, Prefix + Suffix AS Donation FROM Donations; 
How would you fix the error? 
 
        SELECT Id, CAST(Prefix AS CHAR(20)) + Suffix AS Donation FROM Donations; 
 
9. What is the default order of the SELECT query? 
 
        No order 
 
10. Which of the following is a numeric data type? 
 
        BOOLEAN 
 
11. You are working with four SQL queries given below: 
SELECT * FROM USER; 
SHOW AUTHORS; 
SHOW COLUMNS FROM USER; 
RENAME USER STAT TO STANLEY; 
How many of the above queries are DQL? 
 
        3 
 
12. What is true for the ALTER PROCEDURE statement? 
 
        It can be used to change the characteristics of a stored procedure. 
 
13. Which command will execute a stored procedure? 
 
        CALL 
 
14. You are required to create a stored procedure that retrieves outdated records from master data tables. For 
inactive records, a column named ActiveInd is set to 0 in every master data table. How would you create this 
stored procedure? 
 
        CREATE PROCEDURE FetchInactive ( param CHAR(100)) 
         BEGIN 
         SELECT * FROM param WHERE ActiveInd = 0; 
         END 
 
15. You created a stored procedure "Changemap" that has security characteristics set as definer. It deletes 
some data while executing. How would you ALTER the procedure so that everyone cannot use the procedure 
to delete data? 
 
        ALTER PROCEDURE Changemap SQL SECURITY INVOKER; 
 
16. Which of the following privileges are required to delete a procedure? 
 
        ALTER ROUTINE 
 
17. You are working on a table named Student that contains three columns: Name, Subject, and Marks. How 
would you describe the result of the SQL statement given below? 
SELECT Name, Subject, AVG(Marks) FROM Student; 
 
        Result would be incorrect and mismatched. 
 
18. You are working on a data-set named Flight that contains two columns: Origin and Destination. You are 
required to create a recursive common table expression that selects all the destinations one can reach from 
origin "London". Which code would do the job? 
 
        WITH RECURSIVE Route AS ( 
        SELECT Origin AS Destination FROM Flight WHERE Origin = "London" 
        UNION 
        SELECT Flight.Destination FROM Flight, Route WHERE Route.Destination = Flight.Origin 
        ) 
 
19. You are working on concatenating two variables VAR1 and VAR2 with the script given below. Either of the 
variables may contain a NULL value. 
 
CONCAT(VAR1, VAR2); 
 
The script results in a NULL. How can you handle the expected NULL value? 
 
        CONCAT(IFNULL(VAR1, " "), IFNULL(VAR2, " ")); 
 
20. You are working on a table named Marks that has four columns: Id, Math, Science, and Arts. How would 
you get Id and Math where items in Math are in ascending order? 
 
        SELECTS Id, Math FROM Marks ORDER BY Math; 
 
21. Which of the following is NOT a select expression? 
 
        Database_name.* 
 
22. What does the window function do? 
 
        Calculates an aggregate value based on a group of rows and returns multiple rows for each group 
 
23. You are working on a stored procedure named InventoryBuckets and there is a confirmed requirement to 
tweak the logic of the body. What do you need to do first considering you have backup of code and now need 
to update the stored procedure with same name? 
 
        DROP PROCEDURE InventoryBuckets; 
 
24. You are working on two tables named Vendor and Customer that both require their columns to be updated 
to IsCustomer and IsVendor respectively. By default, the columns IsCustomer and IsVendor are set to 0. How 
can you update the respective columns for the records that are present in both tables by comparing the Id 
column of both tables? 
 
        UPDATE Vendor, Customer SET Vendor.IsCustomer = 1 , Customer.IsVendor = 1 WHERE Vendor.Id = 
Customer.Id; 
 
25. Which command will NOT return a current user? 
 
        DEFAULT_USER 
 
26. How would you create a stored procedure to retrieve all data from a table named 'Sales'? 
 
        CREATE PROCEDURE Retrieve_Sales  BEGIN SELECT * FROM Sales; END; 
 
27. What is the range of the unsigned tinyint data type? 
 
        0 to 255 
 
28. 
SELECT CURDATE(); 
The script above is used to generate the current date in a string format. How would you generate it in a numeric 
format? 
 
        SELECT CURDATE() + 0; 
 
29. You are working on a table named Inventory with four columns: Product, Price, Discount, and Stock, where 
the discount is a percentage (whole number). How would you calculate the total amount and the amount given 
as a discount? 
 
        SELECT SUM(Price*Stock) AS 'Total Amount', SUM(Price*Stock*Discount)/100 AS 'Total Discount' FROM 
Inventory; 
 
30. How many columns can be concatenated using CONCAT? 
 
        255 
 
21. You are working on a table named Marks that has four columns: Id, Math, Science, and Arts. How would 
you get Id, Math, and Science, where Math marks are in ascending order and Science marks are in descending 
order? 
 
        SELECTS Id, Math, Science FROM Marks ORDER BY Math ASC, Science DESC; 
 
26. What is the default type of the parameter in a stored procedure? 
 
        IN 
 
27. What is the difference between SELECT and TRUNCATE? 
 
        SELECT is a DQL statement, while TRUNCATE is a DDL statement. 
 
24. You create a stored procedure and want to change its characteristics. What would happen if you tried to 
alter the procedure? 
 
        The procedure would be altered without an error. 
 
28. You are required to create a procedure that counts the number of rows of any table passed as an argument 
and store it in an output argument. How would you create this procedure? 
 
        CREATE PROCEDURE FetchData (IN param1 CHAR(100), OUT param2 INT) 
 BEGIN 
 SELECT COUNT(*) INTO param2 FROM param1; 
 END; 
 

====
====

---

[website]: https://aadhar.bio.link/
[twitter]: https://twitter.com/aadhar54
[youtube]: https://www.youtube.com/c/AADHAR451
[instagram]: https://aadhar54.github.io/
[linkedin]: https://linkedin.com/in/thebtechviral/

# "There is only one thing more important than helping others is helping others to be able to help others ."
