<html> 
 <body> 
 <form method="post">  

Enter First Number:  
<input type="number" name="number1" /><br><br>  
Enter Second Number:  
<input type="number" name="number2" /><br><br>  
<input  type="submit" name="submit" value="Add">  \\
</form>  
<?php                                           \\ php code start here
    if(isset($_POST['submit']))     \\define result 
    {  
        $number1 = $_POST['number1'];  \\ accept first number
        $number2 = $_POST['number2'];  

\\ accept second  number
        $sum =  $number1+$number2;     \\ Add above 2 numbers
echo "The sum of above two number is: ".$sum;    \\ display sum of 2 numbers
}  
?>  \\ php code end
</body>  
</html>
