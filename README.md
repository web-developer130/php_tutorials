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
#           example 1.0 
/*<?php <br>

	 $val1=(int)readline("Enter an integer value"); 
	$val2=(float)readline("Enter float value"); 
        echo "Values are $val1 $val2"; 
	
	$val1=(int)readline("Enter first value");
	$val2=(int)readline("Enter second value");

	echo "Sum of two number ".($val1+$val2);
	echo "Sum of".$val1." And ".$val2." is ".($val1+$val2); 
?>*/

#         example 2.0

/*<?php
	 $val1=(int)readline("Enter an integer value");
          $val2=(float)readline("Enter float value");
	echo "Values are $val1 $val2";

	$val1=(int)readline("Enter first value");
	$val2=(int)readline("Enter second value");

	echo "Sum of two number ".($val1+$val2);
	echo "\nSum of".$val1." And ".$val2." is ".($val1+$val2);

	//Another method to accept value from user <br>
	echo "\nEnter two more numbers\n";
	fscanf(STDIN,"%d %d",$val1,$val2);
	echo "\nSum of".$val1." And ".$val2." is ".($val1+$val2);

?>*/
 ** example 3 **
/*<?php

if(isset($_POST['name'],$_POST['email'])){
    $name=htmlspecialchars($_POST['name']);
    $email=htmlspecialchars($_POST['email']);

    echo "Thank you user $name";
    echo "Your email id is  $email";
}
else{
    echo "You need to provide details";
}

?>*/




** example 4 **


<form action="<?php htmlspecialchars($_SERVER['PHP_SELF']); ?>" method="POST">
            <div>
                <label for="name">Name:</label>
                <input type="text" name="name" required="required" placeholder="Enter Your name"/>
            </div>
            <div>
                <label for="name">Email:</label>
                <input type="email" name="email" required="required" placeholder="Enter Email id"/>
            </div>
            <button type="submit">SUBMIT</button>
  
        
            </form>
        
        
        
        
        
  # example 5

<?php
    require __DIR__ . './Header.php';

    $request_mathod=strtoupper($_SERVER['REQUEST_METHOD']);
    echo $request_mathod;

    if($request_mathod=='GET'){
        require __DIR__ . './get.php';
    }
    else{
        require __DIR__ . './post.php';
    }

    echo "Main part of index.php";


    require __DIR__ . './Footer.php';

?>






# example 6 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
  <main>
    <h1>HEADER File</h1>
	  
	  
# example 7

<h1>FOOTER PAGE</h1>
</main>
    
</body>
</html>




**********************************


   # example 8 

<?php
    require __DIR__ . './Header.php';


    echo "Main part of index.php";

    
    require __DIR__ . './Footer.php';

?>









<h1>FOOTER PAGE</h1>
</main>
    
</body>
</html>











<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
  <main>
    <h1>HEADER File</h1>
    
    
    


















<!DOCTYPE html>
<html lang="en">
<head>
     <title>Document</title>
</head>
<body>
    <main>
        <?php if($_SERVER['REQUEST_METHOD'] == 'GET'):?>

            <form action="<?php htmlspecialchars($_SERVER['PHP_SELF']); ?>" method="POST">

            <div>
                <label for="name">Name:</label>
                <input type="text" name="name" required="required" placeholder="Enter Your name"/>
            </div>

            <div>
                <label for="name">Email:</label>
                <input type="email" name="email" required="required" placeholder="Enter Email id"/>
            </div>

            <button type="submit">SUBMIT</button>
            
        
            </form>


        <?php else : ?> <br>
            <?php <br>

                if(isset($_POST['name'],$_POST['email'])){
                    $name=htmlspecialchars($_POST['name']);
                    $email=htmlspecialchars($_POST['email']);

                    echo "Thank you user $name";
                    echo "Your email id is  $email";
                }
                else{
                    echo "You need to provide details";
                }

            ?>

        <?php endif; ?>

    </main>
    
</body>
</html>


# description
	  

1] Accept a number and print like <br>
   4567 <br>
   
   display sum of digits along with format specified below<br>

    4000 + 500 + 60 + 7  = 4567<br>
    Sum of digits = 22<br>

    use simple / % and without using loop <br>


2] Accept a number and print in reverse without using loop <br>
     
3] Accept three number and check the greate number from three numbers<br>


4] Accept a number of terms and print fibonacci series <br>
   0 1 1 2 3 5 8 13....<br>

5] Accept a string and print the characters <br>

6] write a program to create a directory with name mydir also create a text file <br>
   
7] Write a program to print even numbers and odd numbers <br>

8] Write a program to find factorial number <br>

9] Accept a string and print each character in asc order <br>

10] Accept two number and swap without using third variable using function and passby reference <br>

11] Write a program to calculate area of circle , area of rectangle, area of peripheral using function ans switch <br>

12] Accept student details using html form like <br>
    name,age,dob,sub1 marks,sub2 marks, sub3 marks, <br>

    calculate total and average along with student details in ta <br>










    
    
# description    

Welcome User 
<?php 
    echo $_POST['fname']; 
?><br>
AGE <?php echo $_POST['age']; ?><br>







# description 
	  
<!DOCTYPE html>
<html lang="en">

<head>

    <title>Document</title>
</head>

<body>
    <form action="details.php" method="post">

        Name : <input name="fname" type="text" />
        <br> Age: <input name="age" type="text" />

        <input type="submit" value="SUBMIT">

    </form>

</body>

</html>







# description
	  
A constant is a name or an identifier for a fixed value. Constant are like variables, except that once they are defined, they cannot be undefined or changed

/*<?php
// Defining constant <br>
define("SITE_URL", "https://www.google.com/");
 
// Using constant <br>
echo 'Thank you for visiting - ' . SITE_URL;
?>







# description 
<?php

    function addition(){ <br>
        echo "Enter two numbers\n"; <br>
        $num1=(int)readline("Enter first number");
        $num2=(int)readline("Enter second number");
        
        echo "Addition of two numbers is ".($num1+$num2);
    }

    function division($val1,$val2){
        return (float)$val1/$val2;
    }


    function multiplication(){
        echo "Enter two numbers\n";
        $num1=(int)readline("Enter first number");
        $num2=(int)readline("Enter second number");

        return $num1*$num2;
    }
   
    function subtraction($val1,$val2){
        echo "Subtraction of two numbers is ".($val1+$val2);
    }
    do{ 

        echo "1] Addition\n2] Subtraction\n3] Multiplication\n4] Division\n";
        $choice=readline("Enter your choice\n");
        switch($choice){
            case 1:
                addition();
                break;
            case 2:
                echo "Enter two numbers\n";
                $num1=(int)readline("Enter first number");
                $num2=(int)readline("Enter second number");
                
                subtraction($num1,$num2);
                break;

            case 3:
                echo "Multiplication is ".multiplication();
                break;

            case 4:
                echo "Enter two numbers\n";
                $num1=(int)readline("Enter first number");
                $num2=(int)readline("Enter second number");

                echo "Division is ".division($num1,$num2);

            default :
                echo "\nInvalid choice\n\n";
        }
        echo "\nDo you want to continue\n";
    }while(fgetc(STDIN)!='n');


?>






# examples

<?php <br>
    //Function 1 <br>
    function sayHello(){ <br>
        echo "Hello from sayHello method"; <br>
    }
    sayHello(); <br>

    //Function 2 <br>
    function sumOfValues($val1, $val2){ <br>
        echo "\n\nSum is ".($val1+$val2); <br>
    }
    sumOfValues(10,20); <br>

    //function 3 <br>
    function getValue(){ <br>
        return 100; <br>
    }

    echo "\nThe returned value is ".getValue(); <br>

    //function 4 <br>

    function addition($val1, $val2){ <br>
        return $val1+$val2; <br>
    }

    echo "\nThe addition is  ".addition(44,45); <br>
    


    
    //call by reference <br>

    function changeValue(&$str2){ <br>
        $str2="Good night"; <br>
    }

    $str="Good morning"; <br>
    echo "\nBefore passing value is".$str; <br>
    changeValue($str); <br>
    echo "\nAfter passing value is".$str; <br>

    
    
    
    

?>








1] Accept a number and print like  <br>
   4567  <br>
   
   display sum of digits along with format specified below <br>

    4000 + 500 + 60 + 7  = 4567 <br>
    Sum of digits = 22 <br>

    use simple / % and without using loop  <br>


2] Accept a number and print in reverse without using loop  <br>
     
3] Accept three number and check the greate number from three numbers <br>


4] Accept a number of terms and print fibonacci series  <br>
   0 1 1 2 3 5 8 13.... <br>

5] Accept a string and print the characters  <br>

6] write a program to create a directory with name mydir also create a text file  <br>
   
7] Write a program to print even numbers and odd numbers <br>

8] Write a program to find factorial number <br>

9] Accept a string and print each character in asc order <br>






# examples









  for($i = 0; $i <=5;$i++){
        for($j = 0; $j<=$i;$j++){
            echo "$";
        }
        echo "\n";
    }

    // for($i = 0; $i <10;$i++) { <br>
    //     $product=10*$i; <br>
    //     echo "The product 10 * $i is $product \n"; <br>
    // }

    
    
    
    
    
    
# examples


    // echo shell_exec('dir'); <br>
    //OR <br>
    exec('dir',$commands);  <br>
    print_r($commands); <br>
    
    
    
    
# examples

echo php_uname(); <br>
    $cmd='set'; <br>
    if(substr(php_uname(),0,7)=="Windows"){ <br>
        // pclose(popen("start /B".$cmd,"r")); <br>
        // exec('c:\WINDOWS\system32\cmd.exe'); <br>
        // echo `dir`; <br>
        
        echo "<pre>".shell_exec($cmd)."</pre>"; <br>
    }
    
    
    
    
    
    
    
# examples

echo php_uname(); <br>
    if(substr(php_uname(),0,7)=="Windows"){ <br>
        // pclose(popen("start /B".$cmd,"r")); <br>
        // exec('c:\WINDOWS\system32\cmd.exe'); <br>
        echo `dir`; <br>
    } <br>
    
    
    
    
    
 # examples   

$commands=null; <br>
    $retval=null; <br>
    exec("dir",$commands,$retval); <br>
    // echo $commands[0]; <br>
    print_r($commands); <br>
    echo("RETURN VALUE ".$retval); <br>
    
    
    
    
    
    
    


do{ <br>

        echo "1] Smile\n2] Expression\n3] Sadness\n4] Joy\nEnter your choice\n"; <br>
        $choice=(int)readline("Enter your choice"); <br>
        switch($choice){ <br>
            case 1: <br>
                echo "Smile please"; <br>
                break; <br>
            default:  <br>
                echo "Invalid choice"; <br>

        }

        echo "Do you want to continue?"; <br>
        $input=fgetc(STDIN); <br>
        echo $input; <br>
    }while($input=='y' || $input=='Y'); <br>


    
    
# examples
    
    
    


<?php

    //while loop example

    // $i=1;
    // while($i<=10){ <br>
    //     echo "\nValue is".$i."\n"; <br>
    //     $i++; <br>
    // } <br>

    //do while loop example <br>
    $i=1; <br>
    do{ <br>
        echo "Value is ".$i."\n"; <br>
        $i++; <br>
    }while($i<=10); <br>
    
    
    //For loop example <br>
    for($i=1;$i<=10;$i++){ <br>
        echo "Value is ".$i."\n"; <br>
    } <br>

       $values=array("one", "two", "three", "four", "five", "six", "seven", "eight", "nine", "ten"); <br>
    foreach($values as $temp){ <br>
        echo $temp."\n"; <br>
    } <br> <br>
?> <br>
 

# examples n-6





    $num1=(int)readline("Enter first number\n"); <br>
    $num2=(int)readline("Enter Second number\n"); <br>

    echo "\n1] Addition\n2] Subtraction\n3] Multiplication\n4] Division\n\nEnter your choice\n"; <br>
    $choice=(int)readline("Enter your choice\n"); <br>

    switch ($choice){ <br>

        case 1: <br>
            echo "Addition of two number ".($num1+$num2) . "\n"; <br>
            break; <br>
        case 2: <br>
            echo "Subraction of two number ".($num1-$num2) . "\n"; <br>
            break; <br>
        case 3: <br>
            echo "Multiplication of two number ".($num1*$num2) . "\n"; <br>
            break; <br>
        case 4: <br>
            echo "Division of two number ".(float)($num1/$num2) . "\n"; <br>
            break; <br>
        default: <br>
            echo "Invalied Choice"; <br>
            
                                                
    }
    
    
    
    
    
    
 # examples n-5


<?php
    $technology=readline("Enter a technology"); <br>
    switch($technology){ <br>
        case "c++": <br>
            echo "I would like to work with C++"; <br>
            break; <br>
        case "java": <br>
            echo "I would like to work with java"; <br>
            break; <br>
       case "php": <br>
            echo "I would like to work with php"; <br>
            break; <br>
        case "angular": <br>
            echo "I would like to work with Angular"; <br>
            break; <br>
        default: <br>
            echo "No Choice for input"; <br>

                                

    }

?>



# examples n-4



/*<?php
    $num=(int)readline("Enter a numbers");<br>
    switch($num){ <br>
        case 1: <br>
            echo "Number 1"; <br>
            break; <br>
        case 2: <br>
            echo "Number 2"; <br>
            break; <br>
       case 3: <br>
            echo "Number 3"; <br>
            break; <br>
        case 4: <br>
            echo "Number 4"; <br>
            break; <br>
        default: <br>
            echo "No Choice for number"; <br>

                                

    } <br>

?> */ <br>


# examples n-3


1] Accept a number and print like  <br>
   4567  <br>
   
   display sum of digits along with format specified below  <br>

    4000 + 500 + 60 + 7  = 4567 <br>
    Sum of digits = 22 <br>

    use simple / % and without using loop  <br>


2] Accept a number and print in reverse without using loop  <br>
     
3] Accept three number and check the greate number from three numbers <br>



# examples n-2


<?php
    //If conditional statement <br>
    $d=date('D'); <br>
    echo $d; <br>

    if($d=='Fri')  <br>
        echo "Lets have party tonight\n"; <br>
    else  <br>
        echo "Lets go back to work\n"; <br>


    //Netsted if else <br>

    $a=10; <br>
    $b=20; <br>
    if($a>$b) <br>
        echo "\n".$a." is greater than ".$b; <br>
    elseif($a<$b) <br>
        echo "\n".$a." is smaller than ".$b; <br>
    else <br>
        echo "\nBoth are equal."; <br>


    //Sample student information <br>

    $name=readline("\nEnter your name"); <br>
    $age=(int)readline("\nEnter your age"); <br>
    $marks=(int)readline("\nEnter your marks"); <br>

    if($marks<33) <br>
        echo "\nFail"; <br>
    else if ($marks>=33 && $marks<50) <br>
        echo "\n D Grade"; <br>
    else if ($marks>=50 && $marks<65) <br>
        echo "\n C Grade"; <br>
    else if ($marks>=65 && $marks<80) <br>
        echo "\n B Grade"; <br>
    else if ($marks>=80 && $marks<90) <br>
        echo "\n A Grade"; <br>
    else if ($marks>=90) <br>
        echo "\n A+ Grade"; <br>
    else <br>
        echo "Invalied input"; <br>



?> <br>


# examples n-1


<?php <br>
    //If conditional statement  <br>
    $d=date('D');  <br>
    echo $d; <br>

    if($d=='Fri')  <br>
        echo "Lets have party tonight\n"; <br>
    else  <br>
        echo "Lets go back to work\n"; <br>


    //Netsted if else  <br>

    $a=10; <br>
    $b=20; <br>
    if($a>$b) <br>
        echo "\n".$a." is greater than ".$b; <br>
    elseif($a<$b) <br>
        echo "\n".$a." is smaller than ".$b; <br>
    else <br>
        echo "\nBoth are equal."; <br>
?> <br>




# examples 1.n





  PHP server <br>
  PHP Unterlephense <br>
  settings <br>
  file.associations <br>
  *.module  value: php <br>

        
        
        
        
