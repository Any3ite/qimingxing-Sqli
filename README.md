# qimingxing-Sqli



# qimingxing exam SQL injection - en



## 1_)	about



```

Qixing examination system can be used as a non rigorous examination system in schools and companies. It is easy to generate test papers by adding test questions. System features include:

(1) Support complex mathematical formulas.

(2) Support word to import test questions.

(3) It supports test paper copying. Student introduction, etc.

Please use the system ASP.NET +MSSQL development can be used not only as the teaching of school teachers, but also as the internal staff training and examination system.

Note: software requires. Net4.5.1 or higher

Download Link http://down.chinaz.com/soft/39649.htm

```



##  2_)	Vulnerability analysis



`In the code, the user's input is not filtered and brought in directly` **SQL** `Statement, thus forming a SQL injection vulnerability.`



## 3_)	Analysis process



Build locally after downloading source code



First, use dnspy to load the **DLL** used by all programsÿThen check the source code of the ASPX file and find the method used in dnspy



![image-20200610110025160](D:\git\qimingxing\README.assets\image-20200610110025160.png)



The **activeid**inside the red box is not filtered. Construct a URL to test![image-20200610110157480](D:\git\qimingxing\README.assets\image-20200610110157480.png)



![image-20200610110204447](D:\git\qimingxing\README.assets\image-20200610110204447.png)



Error reported successfully, **incomplete single quotation mark**



![image-20200610110243986](D:\git\qimingxing\README.assets\image-20200610110243986.png)



payload `http://192.168.71.170/tech/pages.aspx?activeid=1+and+1=@@version--`



## 4_)	Risk level



<font color=red>High</font>



## 5_)	Bug fix



- Filter user input



- Force conversion of user input or form values
