# php_tutorials

# DAY 1 study Materials

# intorduction 1.0
> 1.PHP is server side scripting system <br>
  2.PHP stands for "PHP: Hypertext Preprocessor" <br>
  3.Syntax based on Perl, Java, and C <br>
 4.Very good for creating dynamic content <br>
 5.If you want to focus on one system for dynamic content, this is a good one to choose <br>

# 1.1

> PHP is an open-source, interpreted, and object-oriented scripting language that can be executed at the server-side. PHP is well suited for web development. Therefore, it is used to develop web applications (an application that executes on the server and generates the dynamic page.).<br>
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
> Started as a Perl hack in 1994 by Rasmus Lerdorf (to handle his resume), developed to PHP/FI 2.0<br> <br>

By 1997 up to PHP 3.0 with a new parser engine by Zeev Suraski and Andi Gutmans
<br> <br>
Version 5.2.4 is current version, rewritten by Zend (www.zend.com) to include a number of features, such as an object model<br> <br>

php is one of the premier examples of what an open source project can be<br> <br>


# 1.3
> PHP is a server-side scripting language, which is used to design the dynamic web applications with MySQL database. <br>
It handles dynamic content, database as well as session tracking for the website. <br>
You can create sessions in PHP. <br>
It can access cookies variable and also set cookies. <br>
It helps to encrypt the data and apply validation. <br>
PHP supports several protocols such as HTTP, POP3, SNMP, LDAP, IMAP, and many more. <br>
Using PHP language, you can control the user to access some pages of your website. <br>
As PHP is easy to install and set up, this is the main reason why PHP is the best language to learn. <br>
PHP can handle the forms, such as - collect the data from users using forms, save it into the database, and return useful information to the user. For example - Registration form. <br>

# 1.4

> XAMPP is an abbreviation where X stands for Cross-Platform, A stands for Apache, M stands for MYSQL, and the Ps stand for PHP and Perl, respectively. It is an open-source package of web solutions that includes Apache distribution for many servers and command-line executables along with modules such as Apache server, MariaDB, PHP, and Perl.<br>
XAMPP helps a local host or server to test its website and clients via computers and laptops before releasing it to the main server. It is a platform that furnishes a suitable environment to test and verify the working of projects based on Apache, Perl, MySQL database, and PHP through the system of the host itself. Among these technologies, Perl is a programming language used for web development, PHP is a backend scripting language, and MariaDB is the most vividly used database developed by MySQL. The detailed description of these components is given below.<br>

# 1.5
> As defined earlier, XAMPP is used to symbolize the classification of solutions for different technologies. It provides a base for testing of projects based on different technologies through a personal server. XAMPP is an abbreviated form of each alphabet representing each of its major components. This collection of software contains a web server named Apache, a database management system named MariaDB and scripting/ programming languages such as PHP and Perl. X denotes Cross-platform, which means that it can work on different platforms such as Windows, Linux, and macOS.<br>

WAMP for Windows <br>
LAMP for Linux<br>
MAMP for Mac<br>
SAMP for Solaris<br>
FAMP for FreeBSD<br>
XAMPP (Cross, Apache, MySQL, PHP, Perl) for Cross Platform: It includes some other components too such as FileZilla, OpenSSL, Webalizer, Mercury Mail, etc.<br>


# 1.5
> Cross-Platform: Different local systems have different configurations of operating systems installed in it. The component of cross-platform has been included to increase the utility and audience for this package of Apache distributions. It supports various platforms such as packages of Windows, Linus, and MAC OS.<br>
 > Apache:It is an HTTP a cross-platform web server. It is used worldwide for delivering web content. The server application has made free for installation and used for the community of developers under the aegis of Apache Software Foundation. The remote server of Apache delivers the requested files, images, and other documents to the user.<br>
> MariaDB: Originally, MySQL DBMS was a part of XAMPP, but now it has been replaced by MariaDB. It is one of the most widely used relational DBMS, developed by MySQL. It offers online services of data storage, manipulation, retrieval, arrangement, and deletion.<br>
> PHP: It is the backend scripting language primarily used for web development. PHP allows users to create dynamic websites and applications. It can be installed on every platform and supports a variety of database management systems. It was implemented using C language. PHP stands for Hypertext Processor. It is said to be derived from Personal Home Page tools, which explains its simplicity and functionality.<br>


> Perl: It is a combination of two high-level dynamic languages, namely Perl 5 and Perl 6. Perl can be applied for finding solutions for problems based on system administration, web development, and networking. Perl allows its users to program dynamic web applications. It is very flexible and robust.<br>
> phpMyAdmin: It is a tool used for dealing with MariaDB. Its version 4.0.4 is currently being used in XAMPP. Administration of DBMS is its main role.
> OpenSSL: It is the open-source implementation of the Secure Socket Layer Protocol and Transport Layer Protocol. Presently version 0.9.8 is a part of XAMPP.
XAMPP Control Panel: It is a panel that helps to operate and regulate upon other components of the XAMPP. Version 3.2.1 is the most recent update. A detailed description of the control panel will be done in the next section of the tutorial.<br>
> Webalizer: It is a Web Analytics software solution used for User logs and provide details about the usage.<br>
> Mercury: It is a mail transport system, and its latest version is 4.62. It is a mail server, which helps to manage the mails across the web.<br>
> Tomcat: Version 7.0.42 is currently being used in XAMPP. It is a servlet based on JAVA to provide JAVA functionalities.<br>
> Filezilla: It is a File Transfer Protocol Server, which supports and eases the transfer operations performed on files. Its recently updated version is 0.9.41.<br>

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
> /*<?php <br>

	 $val1=(int)readline("Enter an integer value"); 
	$val2=(float)readline("Enter float value"); 
        echo "Values are $val1 $val2"; 
	
	$val1=(int)readline("Enter first value");
	$val2=(int)readline("Enter second value");

	echo "Sum of two number ".($val1+$val2);
	echo "Sum of".$val1." And ".$val2." is ".($val1+$val2); 
?>*/

#         example 2.0

> /*<?php
	 $val1=(int)readline("Enter an integer value"); <br>
          $val2=(float)readline("Enter float value"); <br>
	echo "Values are $val1 $val2"; <br>

	$val1=(int)readline("Enter first value"); <br>
	$val2=(int)readline("Enter second value"); <br>

	echo "Sum of two number ".($val1+$val2); <br>
	echo "\nSum of".$val1." And ".$val2." is ".($val1+$val2); <br>

	//Another method to accept value from user <br>
	echo "\nEnter two more numbers\n"; <br>
	fscanf(STDIN,"%d %d",$val1,$val2); <br>
	echo "\nSum of".$val1." And ".$val2." is ".($val1+$val2); <br>

?>*/
 # example 3 
 /*<?php 

if(isset($_POST['name'],$_POST['email'])){ <br>
    $name=htmlspecialchars($_POST['name']); <br>
    $email=htmlspecialchars($_POST['email']); <br>

    echo "Thank you user $name"; <br>
    echo "Your email id is  $email"; <br>
} <br>
else{ <br>
    echo "You need to provide details"; <br>
} <br>

?>*/




# example 4


 <form action="<?php htmlspecialchars($_SERVER['PHP_SELF']); ?>" method="POST"> <br>
            <div> <br>
                <label for="name">Name:</label> <br>
                <input type="text" name="name" required="required" placeholder="Enter Your name"/>
            </div>
            <div>
                <label for="name">Email:</label>
                <input type="email" name="email" required="required" placeholder="Enter Email id"/>
            </div>
            <button type="submit">SUBMIT</button>
  
        
            </form>
        
        
        
        
        
  # example 5

  /*<?php
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

?>*/






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
        $num1=(int)readline("Enter first number");<br>
        $num2=(int)readline("Enter second number");<br>
        
        echo "Addition of two numbers is ".($num1+$num2);<br>
    }
<br>
    function division($val1,$val2){<br><br>
        return (float)$val1/$val2;<br><br>
    }<br>


    function multiplication(){<br><br>
        echo "Enter two numbers\n";<br><br>
        $num1=(int)readline("Enter first number");<br><br>
        $num2=(int)readline("Enter second number");<br><br>

        return $num1*$num2;<br><br>
    }
   <br><br>
    function subtraction($val1,$val2){<br><br>
        echo "Subtraction of two numbers is ".($val1+$val2);<br><br>
    }<br><br>
    do{ <br><br>

        echo "1] Addition\n2] Subtraction\n3] Multiplication\n4] Division\n";<br><br>
        $choice=readline("Enter your choice\n");<br><br>
        switch($choice){<br><br>
            case 1:<br><br>
                addition();<br><br>
                break;<br><br>
            case 2:<br><br>
                echo "Enter two numbers\n";<br><br>
                $num1=(int)readline("Enter first number");<br><br>
                $num2=(int)readline("Enter second number");<br><br>
                
                subtraction($num1,$num2);<br><br>
                break;<br><br>

            case 3:<br><br>
                echo "Multiplication is ".multiplication();<br><br>
                break;<br><br>

            case 4:<br><br>
                echo "Enter two numbers\n";<br><br>
                $num1=(int)readline("Enter first number");<br><br>
                $num2=(int)readline("Enter second number");<br><br>

                echo "Division is ".division($num1,$num2);<br><br>

            default :<br><br>
                echo "\nInvalid choice\n\n";<br><br>
        }
        echo "\nDo you want to continue\n";<br><br>
    }while(fgetc(STDIN)!='n');<br><br>

<br><br>
?>






# examples

<?php <br>
    //Function 1 <br>
    function sayHello(){ <br>
        echo "Hello from sayHello method"; <br><br><br>
    }<br><br>
    sayHello(); <br>

    //Function 2 <br>
    function sumOfValues($val1, $val2){ <br><br><br>
        echo "\n\nSum is ".($val1+$val2); <br>
    }
    sumOfValues(10,20); <br>

    //function 3 <br>
    function getValue(){ <br>
        return 100; <br>
    }

    echo "\nThe returned value is ".getValue(); <br><br><br>

    //function 4 <br>
<br><br>
    function addition($val1, $val2){ <br>
        return $val1+$val2; <br><br><br>
    }<br><br>

    echo "\nThe addition is  ".addition(44,45); <br>
    


    
    //call by reference <br>

    function changeValue(&$str2){ <br>
        $str2="Good night"; <br>
    }<br><br>

    $str="Good morning"; <br>
    echo "\nBefore passing value is".$str; <br>
    changeValue($str); <br><br><br>
    echo "\nAfter passing value is".$str; <br>
<br><br>
    
    
    
    

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

 
  #    DAY 2 SESSION	  
  # =======================================================================================
  
	  # Day 2 cotaints
	  
	  
	  
	  # Example 2.1
	  
	  <?php<br><br>

    //include "Employee.php";<br><br>
    include "SalesEmployee.php";<br><br>

    $sa1=new SalesEmployees(101,"EShan",100000,4000);<br><br>
    $sa1->showSalesEmployeesDetails();<br><br>


    //$s1=new SalesEmployee(101,"EShan",100000,50000);<br><br>

    


    // $emp1=new Employee(101,"EShan",100000);<br><br>
    // $emp1->showEmployeeDeatils();<br><br>


// $emp1=new Employee(101,"EShan",100000);<br><br>
// $emp1->showEmployeeDeatils();<br><br>


    // $empRecords=array(<br><br>
    //     new Employee(101,"EShan",100000),<br><br>
    //     new Employee(102,"tanish",20000),<br><br>
    //     new Employee(103,"Suha",400000),<br><br>
    //     new Employee(104,"Kranti",50000),<br><br>
    //     new Employee(105,"Paresh",300000)<br><br>
    // );<br><br>


    // foreach($empRecords as $rec){<br><br>
    //     //print_r($rec);<br><br>
    //     $rec->showEmployeeDeatils();<br><br>
    // }<br><br>

?>


# example 2.2


<?php
class Employee
{
    private $empId ;
    private $empName;
    private $salary;


    function __construct( $empId, $empName, $salary)    {
        echo "<br>Parameterised constructor of Employee is called";
        $this->empId = $empId;
        $this->empName = $empName;
        $this->salary = $salary;
    }

  

    function calculateSalary(){
        echo "<br> calculateSalary is called";
    }

    function setSalary($newSalary){
        echo "setSalary is called";
        $this->salary = $newSalary;
    }

    function getSalary(){
        echo "getSalary is called";
        return $this->salary;
    }

    function showEmployeeDeatils(){
        echo "<br>Employee Deatils : ".$this->empId." Name :- ".$this->empName." Salary".$this->salary;
        
    }

    function __destruct(){
        echo "<br> Employee Destructor is called";
    }
}
?>



# example 2.3

<?php
include 'Employee.php';

class SalesEmployees extends Employee{
    private $sales;
    private $commissions;
    private $netSalary;

    function __construct($empId,$empName,$salary,$sales){
        parent::__construct($empId,$empName,$salary);  //calling base class Employee constructor    
        echo "<br>Parameterised constructor of SalesEmployees is called";
 
        $this->sales = $sales;
        $this->commissions = 0;
        $this->netSalary = 0;
    }


    public function showSalesEmployeesDetails(){
        echo "<br>Sales Employee ".$this->sales." ".$this->commissions." ".$this->netSalary;
        parent::showEmployeeDeatils();

    }


    public function __destruct(){
        echo "<br>Sales Employee __destruct is called";
    }


}


?>



# example 2.3


<?php

    class Calculation{


        function __call($name_of_function,$arguments){

            echo $name_of_function;
            print_r($arguments);
            // if($name_of_function=='add'){
            //     // echo count($arguments);
            //     switch(count($arguments)){
            //         case 1:
            //             return $arguments[0];
            //             break;
            //         case 2:
            //             return $arguments[0]+$arguments[1];            
            //             break;
            //     }
            // }
        }
    }


    $obj1=new Calculation();

  //  echo $obj1->add(10,20);

  $obj1->abc(100);
  $obj1->xyz(100,200);




    // $obj1->add(100,200);


    // class Message{
    //     function formatMessage($message){
    //         return printf("<i>%s</i>", $message);
    //     }
    // }


    // class BoldMessage extends Message{
    //     function formatMessage($message){
    //         return printf("<b>%s</b>", $message);
    //     }
    // }



    // $msg=new Message();
    // $msg->formatMessage("PHP is good");

    // $msg=new BoldMessage();
    // $msg->formatMessage("PHP is good");



    // class A{
    //     function show(){
    //         echo "<br>show method from A class ";
    //     }
    // }

    // class B extends A{
    //     function show(){
    //         echo "<br>show method from B class ";
    //     }

    // }

    // class C extends B{
    //     function show(){
    //         echo "<br>show method from C class ";
    //     }

    //     function call(){
    //         $this->show(); ///current class
    //         parent::show(); //base class show method 
    //         A::show(); //grand Parent show method

    //     }
    // }


    // $cObj=new C();
    // $cObj->call();







?>
# example 2.4


<?php
    class Complex
    {
        public $real;
        public $imag;

        //Constructor

        function __construct($real=0, $imag=0){
            echo "Parameterised constructor is called<br>";
            $this->real = $real;
            $this->imag = $imag;
        }

        //Descructor
        function __destruct(){
            echo "Destructor is called<br>";
        }

      
    }

    $c1=new Complex();
    $c2=new Complex();
    // unset($c1);
    // unset($c2);
     



?>



# example 2.5




<?php
class Employee
{
    private $empId ;
    private $empName;
    private $salary;


    function __construct( $empId, $empName, $salary)    {
        echo "<br>Parameterised constructor of Employee is called";
        $this->empId = $empId;
        $this->empName = $empName;
        $this->salary = $salary;
    }

  

    function calculateSalary(){
        echo "<br> calculateSalary is called";
    }

    function setSalary($newSalary){
        echo "setSalary is called";
        $this->salary = $newSalary;
    }

    function getSalary(){
        echo "getSalary is called";
        return $this->salary;
    }

    function showEmployeeDeatils(){
        echo "<br>Employee Deatils : ".$this->empId." Name :- ".$this->empName." Salary".$this->salary;
        
    }

    function __destruct(){
        echo "<br> Employee Destructor is called";
    }
}

$emp=new Employee(101,"Tanish",1000);
$emp->showEmployeeDeatils();


?>


# example 2.6




<?php

    class Complex{
        var $real;
        var $imag;

        //Member methods setters
        function setReal($real){
            $this->real = $real;
        }
        function setImag($imag){
            $this->imag = $imag;
        }

        //getters 

        function getReal(){
            return $this->real;
        }

        function getImag(){
            return $this->imag;
        }

    }

    $emp1=new Complex;
    $emp1->setReal(100);
    $emp1->setImag(200);

    echo $emp1->getReal();
    echo $emp1->getImag();

?>



# example 2.7

>Class − This is a programmer-defined data type, which includes local functions as well as local data. You can think of a class as a template for making many instances of the same kind (or class) of object.<br><br>
Object − An individual instance of the data structure defined by a class. You define a class once and then make many objects that belong to it. Objects are also known as instance.<br><br>
Member Variable − These are the variables defined inside a class. This data will be invisible to the outside of the class and can be accessed via member functions. These variables are called attribute of the object once an object is created.<br><br>
Member function − These are the function defined inside a class and are used to access object data.<br><br>
Inheritance − When a class is defined by inheriting existing function of a parent class then it is called inheritance. Here child class will inherit all or few member functions and variables of a parent class.<br><br>
Parent class − A class that is inherited from by another class. This is also called a base class or super class.<br><br>
Child Class − A class that inherits from another class. This is also called a subclass or derived class.<br><br>
Polymorphism − This is an object oriented concept where same function can be used for different purposes. For example function name will remain same but it take different number of arguments and can do different task.<br><br>
Overloading − a type of polymorphism in which some or all of operators have different implementations depending on the types of their arguments. Similarly functions can also be overloaded with different implementation.<br><br>
Data Abstraction − Any representation of data in which the implementation details are hidden (abstracted).<br><br>
Encapsulation − refers to a concept where we encapsulate all the data and member functions together to form an object.<br><br>
Constructor − refers to a special type of function which will be called automatically whenever there is an object formation from a class.<br><br>
Destructor − refers to a special type of function which will be called automatically whenever an object is deleted or goes out of scope.<br><br>





# example 2.8

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script>

function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the button that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

    </script>
    <style>
        .tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons that are used to open the tab content */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}

        </style>
</head>
<body>

    <!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">Create Database </button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Create Table</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Show Records</button>
</div>

<!-- Tab content -->
<div id="London" class="tabcontent">
  <form action="createDatabase.php" method="post">
    Enter database Name <input type="text" name="create_database"></br>
    <input type="submit" value="Create database"/>


  </form>
</div>

<div id="Paris" class="tabcontent">
  <h3>Create table</h3>
  <?php
        
  ?>
  <select name="list_of_databases">
  <?php
    $conn=mysqli_connect("localhost","root","");
    while($databases=mysqli_fetch_array($all_databases,MYSQLI_ASSOC)){ ?>
        <option value=" <?php echo $databases ?>"></option>
    <?php
    
    }
    ?>
  ?>
  </select>
  <form action="createTable.php" method="post">

    Enter Table Name <input type="text" name="create_table"></br>
    <input type="submit" value="Create Table"/>
  </form>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Show Records</h3>
    <table border='5px'>
       <tr>
        <th>FirstName</th>
        <th>LastName</th>
        <th>Age</th>

       </tr>

    </table>
</div>
    
</body>
</html>


# example 2.9 

<?php

$conn=mysqli_connect("localhost","root","");
if(!$conn){
    die("Couldn't connect to database");
}
else{
    echo "Connecting to database";
    if(mysqli_query($conn,"CREATE DATABASE IF NOT EXISTS $_POST[create_database]")){
        echo "Database created successfully";
    }else{
        echo "Database not created successfully";
    }
    }

?>




# example 2.10



<?php

$conn=mysqli_connect("localhost","root","");
if(!$conn){
    die("Couldn't connect to database");
}
else{
    $table_name=$_POST['create_table'];
    mysqli_select_db($conn,"testdb");
    $sql="CREATE TABLE $table_name(FirstName varchar(15),LastName varchar(15), Age int);";

    //EXECUTE QUERY
    mysqli_query($conn,$sql);
    echo "Table is created successfully";
    }

?>







# example 2.11

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script>

function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the button that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

    </script>
    <style>
        .tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons that are used to open the tab content */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}

        </style>
</head>
<body>

    <!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">Create Database </button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Create Table</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Show Records</button>
</div>

<!-- Tab content -->
<div id="London" class="tabcontent">
  <form action="createDatabase.php" method="post">
    Enter database Name <input type="text" name="create_database"></br>
    <input type="submit" value="Create database"/>


  </form>
</div>

<div id="Paris" class="tabcontent">
  <h3>Create table</h3>
  <form action="createTable.php" method="post">

    Enter Table Name <input type="text" name="create_table"></br>
    <input type="submit" value="Create Table"/>
  </form>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>
    
</body>
</html>







# example 2.12








<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <script>

function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the button that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

    </script>
    <style>
        .tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons that are used to open the tab content */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}

        </style>
</head>
<body>

    <!-- Tab links -->
<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')">London</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">Paris</button>
  <button class="tablinks" onclick="openCity(event, 'Tokyo')">Tokyo</button>
</div>

<!-- Tab content -->
<div id="London" class="tabcontent">
  <h3>London</h3>
  <p>London is the capital city of England.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Paris</h3>
  <p>Paris is the capital of France.</p>
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>
    
</body>
</html>


# example 2.13



<?php
    $conn=mysqli_connect("localhost","root","");
    if(!$conn){
        die("Couldn't connect to database");
    }
    mysqli_select_db($conn,"mydb");

    $result=mysqli_query($conn,"SELECT * FROM persons");
    // print_r($result);

    // while($row=mysqli_fetch_array($result)){
    //     echo $row['FirstName']." ".$row['LastName']." ".$row['Age']."\n";
    // }

    echo "<table border='1'>
        <tr>
        <th>First Name</th><th>LastName</th><th>Age</th></tr>
        </table>";
    while($row=mysqli_fetch_array($result)){
        echo "<tr>";
            echo "<td>".$row['FirstName']."</td>";
            echo "<td>".$row['LastName']."</td>";
            echo "<td>".$row['Age']."</td>";
        echo "</tr>";
    }

    mysqli_close($conn);

?>



   # example 2.14 


<?php
    $conn=mysqli_connect("localhost","root","");
    if(!$conn){
        die("Couldn't connect to database");
    }
    mysqli_select_db($conn,"mydb");

    $result=mysqli_query($conn,"SELECT * FROM persons");
    print_r($result);

    while($row=mysqli_fetch_array($result)){
        echo $row['FirstName']." ".$row['LastName']." ".$row['Age']."\n";
    }


    mysqli_close($conn);

?>







# example 2.15








<?php
    $conn=mysqli_connect("localhost","root","");
    if(!$conn){
        die("Couldn't connect to database");
    }
    
    mysqli_select_db($conn,"mydb");
    $sql="INSERT INTO persons(FirstName,LastName,age) values('$_POST[firstname]','$_POST[lastname]','$_POST[age]')";
    echo $sql;

    if(!mysqli_query($conn,$sql)){
        die("Couldn't insert values into persons");
    }
    else{
        echo "1 record inserted into persons";
    }

    mysqli_close($conn);
?>


# example 2.16



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="insert.php" method="post">
        FirstName <input type="text" name="firstname"/><br>
        LastName <input type="text" name="lastname"/><br>
        Age <input type="text" name="age"/><br>

        <input type="submit" value="SUBMIT">


    </form>
</body>
</html>








# example 2.17


<?php
    // echo phpinfo();
    $conn=mysqli_connect("localhost","root","");
    if(!$conn){
        die("Couldn't connect to database");
    }
    else{
        echo "Connecting to database";
        // if(mysqli_query($conn,"CREATE DATABASE IF NOT EXISTS mydb")){
        //     echo "Database created successfully";
        // }else{
        //     echo "Database not created successfully";
        // }


        //CREATE TABLE inside any particular database

        mysqli_select_db($conn,"mydb");
        $sql="CREATE TABLE Persons(FirstName varchar(15),LastName varchar(15), Age int);";

        //EXECUTE QUERY
        mysqli_query($conn,$sql);
        
        echo "Table is created successfully";
    }

    mysqli_close($conn);

?>



# example 2.18




<?php
    $user = "username";
    $pass = "password";
    $host = "host";
    $dbdb = "database";
    
$conn = new mysqli($host, $user, $pass, $dbdb);
   if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
} 
?>




# example 2.19


extension=php_mysqli.dll





; Directory in which the loadable extensions (modules) reside.
; http://php.net/extension-dir
; extension_dir = "./"
; On windows:
; extension_dir = "ext"

extension_dir = "ext"

;extension=php_gmp.dll
;extension=php_intl.dll
;extension=php_imap.dll
;extension=php_interbase.dll
;extension=php_ldap.dll
;extension=php_mbstring.dll
;extension=php_exif.dll      ; Must be after mbstring as it depends on it

extension=php_mysqli.dll

;extension=php_oci8_12c.dll  ; Use with Oracle Database 12c Instant Client
;extension=php_openssl.dll








# example 2.20






echo phpinfo();






<?php

    $conn=mysqli_connect("localhost","root","");
    if(!$conn){
        die("Couldn't connect to database");
    }
    else{
        echo "Connecting to database";
        if(mysqli_query($conn,"CREATE DATABASE IF NOT EXISTS mydb")){
            echo "Database created successfully";
        }else{
            echo "Database not created successfully";
        }
    }

    mysqli_close($conn);

?>




# example 2.20

<?php

    $conn=mysqli_connect("localhost","root","");
    if(!$conn){
        die("Couldn't connect to database");
    }
    else{
        echo "Connecting to database";
    }

    mysqli_close($conn);

?>




# example 2.21

<?php
function ascendingOrder($arr){

    sort($arr);
    print_r($arr);

}

?>






# example 2.22 

<?php

require __DIR__ . './AscendingOrder.php';

$values=array(56,76,45,65,76,87,44,3,54,12,5);


do{ 

    echo "a] Asc\n
    b] Desc\n
    c] Reverse\n
    d] Find even nos\n
    e] Find odd nos\n
    f] sum of all elements\n
    \n";
    $choice=readline("Enter your choice\n");
    switch($choice){
        case 1:
            ascendingOrder($values);
            break;
       
    
        default :
            echo "\nInvalid choice\n\n";
    }
    echo "\nDo you want to continue\n";
    }while(fgetc(STDIN)!='n');

?>












# example 2.23


>1] Create an associative array to declare months and its number of days in that month

2] Declare number array and pass to an function to print in asc order


a] Asc
b] Desc
c] Reverse
d] Find even nos
e] Find odd nos
f] sum of all elements








# example 2.24



<?php

    function averageMarks($arr){
        $total=0;
        foreach($arr as $values){
            $total+=$values;
        }

        return $total/count($arr);

    }

    $marks=array(56,76,45,65,76,87,44);


    echo "Average of marks is ".averageMarks($marks);



?>





# example 2.25
    // $friends = array("Tanish","Anish","Manish","Danish","Kanish");

    // //1 Array method
    // echo count($friends);

    //2 Array method Array_walk() method

    // function showValues($val,$k){
    //     echo $k. " value is".$val."\n";
    // }

    // $my_collections = array("1"=>"ONE", "2"=>"TWO", "3"=>"THREE", "4"=>"FOUR", "5"=>"FIVE");
    // array_walk($my_collections,"showValues");



    $friends = array("Tanish","Anish","Manish","Danish","Kanish");
    // $val=readline("Enter the value to search in array");
    // if(in_array($val,$friends)){
    //     echo "Value is present in array";
    // }
    // else{
    //     echo "Value is not present in array";
    // }
        

    array_push($friends,"Amisha","Sania","Aravind","Kunal");

    // print_r($friends);


    // echo array_shift($friends);
    // print_r($friends);

    // array_unshift($friends,"Rupesh");
    // print_r($friends);


    print_r(array_reverse($friends));


        

    # example 2.26    
        
        
        

array_push($friends,"Amisha","Sania","Aravind","Kunal");

    print_r($friends);


    echo array_shift($friends);
    print_r($friends);

    array_unshift($friends,"Rupesh");
    print_r($friends);


    
    # example 2.27
    


$friends = array("Tanish","Anish","Manish","Danish","Kanish");
    $val=readline("Enter the value to search in array");
    if(in_array($val,$friends)){
        echo "Value is present in array";
    }
    else{
        echo "Value is not present in array";
    }
    
    
    
    
 # example 2.27   


// $friends = array("Tanish","Anish","Manish","Danish","Kanish");

    // //1 Array method
    // echo count($friends);

    //2 Array method Array_walk() method

    function showValues($val,$k){
        echo $k. " value is".$val."\n";
    }

    $my_collections = array("1"=>"ONE", "2"=>"TWO", "3"=>"THREE", "4"=>"FOUR", "5"=>"FIVE");
    array_walk($my_collections,"showValues");

    
    
    
    
    
 # example 2.28   
    
    
    


$employee_records = array(
        array("empId"=>"101","name"=>"Tanish","salary"=>"100000"),
        array("empId"=>"102","name"=>"Anish","salary"=>"200000"),
        array("empId"=>"103","name"=>"Manish","salary"=>"300000"),
        array("empId"=>"104","name"=>"Vanish","salary"=>"400000"),
        array("empId"=>"105","name"=>"Kanish","salary"=>"500000"),
    );


    // print_r($employee_records[0]["name"]);
    $keys=array_keys($employee_records);
    for($i=0;$i<count($employee_records);$i++){
        // echo $keys[$i];
        foreach($employee_records[$keys[$i]] as $key=>$value){
            echo $key."=".$value." ";
        }
        echo "\n";
    }

    
   # example 2.29 
    
    
    
    


$employee_records = array(
        array("empId"=>"101","name"=>"Tanish","salary"=>"100000"),
        array("empId"=>"102","name"=>"Anish","salary"=>"200000"),
        array("empId"=>"103","name"=>"Manish","salary"=>"300000"),
        array("empId"=>"104","name"=>"Vanish","salary"=>"400000"),
        array("empId"=>"105","name"=>"Kanish","salary"=>"500000"),
    );


    print_r($employee_records[0]["name"]);



    
    
    
    
    # example 2.30
    


$my_collections = array("1"=>"ONE", "2"=>"TWO", "3"=>"THREE", "4"=>"FOUR", "5"=>"FIVE");

    echo $my_collections["1"]."\n";


    foreach($my_collections as $values=>$val_values){
        echo "Key is " . $values." Value is " . $val_values."\n";
    }

    $keys=array_keys($my_collections);
    print_r($keys);
    for($i=1;$i<(count($my_collections));++$i) {
        echo "Key is " . $keys[$i]." Value is " . $my_collections[$keys[$i]]."\n";
    }
    
    
    
    








# example 2.31



$my_collections = array("1"=>"ONE", "2"=>"TWO", "3"=>"THREE", "4"=>"FOUR", "5"=>"FIVE");

    echo $my_collections["1"]."\n";


    foreach($my_collections as $values=>$val_values){
        echo "Key is " . $values." Value is " . $val_values."\n";
    }
    
    
    
    
    


$my_collections = array("1"=>"ONE", "2"=>"TWO", "3"=>"THREE", "4"=>"FOUR", "5"=>"FIVE");

    echo $my_collections["1"];
    
    
   # example 2.32 
    

//apply php open closed tage <br><br>

    $values=array("C++","JAVA","PHP","SQL","SQL Server","Perl");

    //First way to print values<br><br>
    print_r($values);

    //second way to print values

    foreach($values as $val){
        echo $val."\n";
    }

    //Third way to print values<br><br>

    for($n=0;$n<count($values);$n++){
        echo $values[$n]." ";
    }






# example 2.33


>The include() function
This function is used to copy all the contents of a file called within the function, text wise into a file from which it is called. This happens before the server executes the code
The require() function
The require() function performs same as the include() function. It also takes the file that is required and copies the whole code into the file from where the require() function is called. 

The only difference is — the include() statement will only generate a PHP warning but allow script execution to continue if the file to be included can't be found, whereas the require() statement will generate a fatal error and stops the script execution.
	  
        
        
