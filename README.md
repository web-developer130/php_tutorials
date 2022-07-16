# php_tutorials

# DAY 1 study Materials

# intorduction 1.0
1.PHP is server side scripting system <br>
2.PHP stands for "PHP: Hypertext Preprocessor" <br>
3.Syntax based on Perl, Java, and C <br>
4.Very good for creating dynamic content <br>
5.If you want to focus on one system for dynamic content, this is a good one to choose <br>

# 1.1

PHP is an open-source, interpreted, and object-oriented scripting language that can be executed at the server-side. PHP is well suited for web development. Therefore, it is used to develop web applications (an application that executes on the server and generates the dynamic page.).<br>
PHP was created by Rasmus Lerdorf in 1994 but appeared in the market in 1995.<br>
Some important points need to be noticed about PHP are as followed:<br>
PHP stands for Hypertext Preprocessor.<br>
PHP is an interpreted language, i.e., there is no need for compilation.<br>
PHP is faster than other scripting languages, for example, ASP and JSP.<br>
PHP is a server-side scripting language, which is used to manage the dynamic content of the website.<br>
PHP can be embedded into HTML.<br>
PHP is an object-oriented language.<br>
PHP is an open-source scripting language.<br>
PHP is simple and easy to learn language.<br>

# 1.2
Started as a Perl hack in 1994 by Rasmus Lerdorf (to handle his resume), developed to PHP/FI 2.0<br> <br>

By 1997 up to PHP 3.0 with a new parser engine by Zeev Suraski and Andi Gutmans
<br> <br>
Version 5.2.4 is current version, rewritten by Zend (www.zend.com) to include a number of features, such as an object model<br> <br>

php is one of the premier examples of what an open source project can be<br> <br>


# 1.3
PHP is a server-side scripting language, which is used to design the dynamic web applications with MySQL database. <br>
It handles dynamic content, database as well as session tracking for the website. <br>
You can create sessions in PHP. <br>
It can access cookies variable and also set cookies. <br>
It helps to encrypt the data and apply validation. <br>
PHP supports several protocols such as HTTP, POP3, SNMP, LDAP, IMAP, and many more. <br>
Using PHP language, you can control the user to access some pages of your website. <br>
As PHP is easy to install and set up, this is the main reason why PHP is the best language to learn. <br>
PHP can handle the forms, such as - collect the data from users using forms, save it into the database, and return useful information to the user. For example - Registration form. <br>

# 1.4

XAMPP is an abbreviation where X stands for Cross-Platform, A stands for Apache, M stands for MYSQL, and the Ps stand for PHP and Perl, respectively. It is an open-source package of web solutions that includes Apache distribution for many servers and command-line executables along with modules such as Apache server, MariaDB, PHP, and Perl.<br>
XAMPP helps a local host or server to test its website and clients via computers and laptops before releasing it to the main server. It is a platform that furnishes a suitable environment to test and verify the working of projects based on Apache, Perl, MySQL database, and PHP through the system of the host itself. Among these technologies, Perl is a programming language used for web development, PHP is a backend scripting language, and MariaDB is the most vividly used database developed by MySQL. The detailed description of these components is given below.<br>

# 1.5
As defined earlier, XAMPP is used to symbolize the classification of solutions for different technologies. It provides a base for testing of projects based on different technologies through a personal server. XAMPP is an abbreviated form of each alphabet representing each of its major components. This collection of software contains a web server named Apache, a database management system named MariaDB and scripting/ programming languages such as PHP and Perl. X denotes Cross-platform, which means that it can work on different platforms such as Windows, Linux, and macOS.<br>

WAMP for Windows <br>
LAMP for Linux<br>
MAMP for Mac<br>
SAMP for Solaris<br>
FAMP for FreeBSD<br>
XAMPP (Cross, Apache, MySQL, PHP, Perl) for Cross Platform: It includes some other components too such as FileZilla, OpenSSL, Webalizer, Mercury Mail, etc.<br>


# 1.5
Cross-Platform: Different local systems have different configurations of operating systems installed in it. The component of cross-platform has been included to increase the utility and audience for this package of Apache distributions. It supports various platforms such as packages of Windows, Linus, and MAC OS.<br>
Apache: It is an HTTP a cross-platform web server. It is used worldwide for delivering web content. The server application has made free for installation and used for the community of developers under the aegis of Apache Software Foundation. The remote server of Apache delivers the requested files, images, and other documents to the user.<br>
MariaDB: Originally, MySQL DBMS was a part of XAMPP, but now it has been replaced by MariaDB. It is one of the most widely used relational DBMS, developed by MySQL. It offers online services of data storage, manipulation, retrieval, arrangement, and deletion.<br>
PHP: It is the backend scripting language primarily used for web development. PHP allows users to create dynamic websites and applications. It can be installed on every platform and supports a variety of database management systems. It was implemented using C language. PHP stands for Hypertext Processor. It is said to be derived from Personal Home Page tools, which explains its simplicity and functionality.<br>
Perl: It is a combination of two high-level dynamic languages, namely Perl 5 and Perl 6. Perl can be applied for finding solutions for problems based on system administration, web development, and networking. Perl allows its users to program dynamic web applications. It is very flexible and robust.<br>
phpMyAdmin: It is a tool used for dealing with MariaDB. Its version 4.0.4 is currently being used in XAMPP. Administration of DBMS is its main role.
OpenSSL: It is the open-source implementation of the Secure Socket Layer Protocol and Transport Layer Protocol. Presently version 0.9.8 is a part of XAMPP.
XAMPP Control Panel: It is a panel that helps to operate and regulate upon other components of the XAMPP. Version 3.2.1 is the most recent update. A detailed description of the control panel will be done in the next section of the tutorial.<br>
Webalizer: It is a Web Analytics software solution used for User logs and provide details about the usage.<br>
Mercury: It is a mail transport system, and its latest version is 4.62. It is a mail server, which helps to manage the mails across the web.<br>
Tomcat: Version 7.0.42 is currently being used in XAMPP. It is a servlet based on JAVA to provide JAVA functionalities.<br>
Filezilla: It is a File Transfer Protocol Server, which supports and eases the transfer operations performed on files. Its recently updated version is 0.9.41.<br>

# 1.6  
# https://www.apachefriends.org/download.html
# echo
echo is a statement, which is used to display the output.<br>
echo can be used with or without parentheses.<br>
echo does not return any value.<br>
We can pass multiple strings separated by comma (,) in echo.<br>
echo is faster than print statement.<br>


# print
print is also a statement, used as an alternative to echo at many times to display the output.<br>
print can be used with or without parentheses.<br>
print always returns an integer value, which is 1.<br>
Using print, we cannot pass multiple arguments.<br>
print is slower than echo statement.<br>


# examples

/*<?php <br>
	// $val1=(int)readline("Enter an integer value");
	// $val2=(float)readline("Enter float value");
	// echo "Values are $val1 $val2";

	
	$val1=(int)readline("Enter first value");
	$val2=(int)readline("Enter second value");

	echo "Sum of two number ".($val1+$val2);
	echo "Sum of".$val1." And ".$val2." is ".($val1+$val2); <br>
?>*/

