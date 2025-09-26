<?php
// var_dump();
$test= 'hello world';
// echo $test;

// Data type -string

$str1 = "Bangladesh";
$str2 = "bangladesh is a country";


// Data type - integer
$num = 10;

// var_dump($num);

// echo PHP_INT_MAX; 
// echo PHP_INT_MIN;

// echo var_dump(is_int($num));

// Data type - float

// type Casting

$a = (int)20.33;


// echo $a;

// $date = "2025-03-12";

// echo substr($date,0,4);

//  echo str_repeat("bangladesh ",10);

//  echo str_word_count("bangladesh is a country");

// echo strrev("hasan");

// echo strpos("bangladesh is a country","country");

// echo strip_tags("<script>alert('hacked!')</script>");

// echo sqrt(144);

// $a= 12.4;

// echo var_dump(is_numeric($a));

//  sqrt(-12);
// echo var_dump(is_nan(sqrt(-12)));

// echo pi();

// echo min(10,11,3,5);

// echo abs(-65465);

// echo round(12.5967,2);
// echo rand();
// echo rand(100,200);
// echo ceil(12.22);
// echo floor(66.33);
// echo decbin(5);
// echo bindec(1100);

// constant

// define("admin_name","Morshedul Arefin");
// echo admin_name;

// const admin_name = "Morshedul Arefin";
// echo admin_name;


//operator = + - %
// operand = a,b

// expression
// arithmatic expression
// $a = (2+3)*8;

// comparison expression
// $age = 20;
// $test = ($age>=20);
// echo $test;


// arithmatic operator
//operator = + - %
// operand = a,b

// $a=5;
// $b =3;

// echo ($a**$b);
// echo pow($a,$b);


// assignment operator
// $a=5;
// $b =3;

// // $a = $a + $b;
// $a +=$b;
// echo $a;

// $a=5;
// $b ="5";

// var_dump($a === $b);


$city = "Khulna";
echo $city = $city ?? "Dhaka";
