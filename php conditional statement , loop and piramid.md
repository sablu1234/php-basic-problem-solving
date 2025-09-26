<?php

// conditional statement 

// if else elseif 

// if: endif;

// $num1 =100;
// $num2 = 50;

// if($num1==100){
//     echo "it is 100";
// }elseif($num1 == 200){
//     echo "It is 200";
// }
// else{
//     echo "It is something that is not 100 and 200";
// }

// $mark = 52;

// if($mark>= 80){
//     echo "A+";
// } elseif($mark >= 75 && $mark<80){
//     echo "A-";
// }elseif($mark >= 70 && $mark < 75){
//     echo "A-";
// }elseif($mark >= 65 && $mark < 70){
//     echo "B+";
// }elseif($mark >= 60 && $mark < 65){
//     echo "B";
// }elseif($mark >= 55 && $mark < 60){
//     echo "B-";
// }elseif($mark >= 50 && $mark < 55){
//     echo "C+";
// }elseif($mark >= 45 && $mark < 50){
//     echo "C";
// }elseif($mark >= 40 && $mark < 45){
//     echo "D";
// }else{
//     echo "F";
// }


// $num1 =40;

// if($num1==100) :
//     echo "it is 100";
// elseif($num1 >= 40 && $num1 < 45) :
//     echo "D";
// else:
//     echo "F";
// endif;


// $a = 90;
// $b = 100;
// $c = 110;
// if($a>$b){
//     if($a>$c){
//         echo "a is larger";
//     }else{
//         echo "c is larger";
//     }
// }else{
//     if($b>$c){
//         echo "b is larger";
//     }else{
//         echo "C is larger";
//     }
// }


// Switch statement
// $country = "Austrilia";

// switch($country){
//     case "Bangladesh":
//         echo "i am in bangladesh";
//         break;
//     case "Austrilia" :
//         echo "I am in Austrilia";
//         break;
//     default:
//     echo "I am not in the earth";
// }


// $marks = 70;
// switch(true){
//     case ($marks >= 80):
//         echo "A+";
//         break;
//     case ($marks >= 70 && $marks < 80) :
//         echo "B+";
//         break;
//     default:
//     echo "F";
// }



// $country = "Bangladesh";

// switch($country){
//     case "Bangladesh":
//     case "japan":
//         echo "i am in Asian country";
//         break;
//     case "USA" :
//     case "Colombia" :
//         echo "I am in American country";
//         break;
//     default:
//     echo "Unknown";
// }


// Loop
// for, while, dowhile, foreach
// Normal / Nested Loop

// for loop
// itetation

// for(initialization; condition; increament/decreatement) {

// }


// for(initialization; condition; increament/decreatement) :

// forend;


// i++;
// $i = $i + ;
// $i += 1;

// for($i=1; $i<=5; $i++){
//     echo $i." Bangladesh <br>";
// }

// $m= 0;
// for($i=1; $i<=1000; $i++){
//     $m++;
//     echo $m." ";
// }


// summation of numbers that start from 1 to 10
// 1+2+3+4+5

// $total= 0;
// for($i=1; $i<=5; $i++){
//      $total =$total+ $i;
// }
// echo $total;

// 0 + 1 = 1
// 1 + 2 = 3
// 3 + 3 = 6
// 6 + 4 = 10
// 10 + 5 = 15

// for(;;){

// }


// $total= 0;
// $i=1;
// while( $i<=5){
//      $total =$total+ $i;
//      $i++;
// }
// echo $total;


// $total= 0;
// $i=1;
// while(1){
//      $total =$total+ $i;
//      $i++;

//      if($i<=100){
//         break;
//      }
// }
// echo $total;



// $total= 0;
// $i=1;
// do{
//     $total =$total+ $i;
//     $i++;
// }while($i<=5);
// echo $total;



// for($i=1; $i<=100; $i++){
//      if($i>5){
//         break;
//      }
//      echo "bangladesh <br>";

// }

// for($i=1; $i<=5; $i++){
//      if($i==2){
//         continue;
//      }
//      echo $i.' ';

// }


// for($i=1; $i<=3; $i++)
// {
//     echo "Team ". $i." = ";

//     for ($j=1; $j<=5; $j++){
//         echo $j." ";
//     }
//     echo "<br>";
// }


/*
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5


1
2 2
3 3 3
4 4 4 4
5 5 5 5 5

1
2 1
3 2 1
4 3 2 1
5 4 3 2 1

1
2 3
4 5 6
7 8 9 10

         1
       2 1 2
     3 2 1 2 3
   4 3 2 1 2 3 4

*/

/*
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
*/

// for($i=1; $i<=5; $i++){
//     for($j=1; $j<=$i; $j++){
//         echo $j." ";
//     }
//     echo "<br>";
// }

// for($i=5; $i>=1; $i--){
//     echo "Bangladesh<br>";
// }


/*
1
2 2
3 3 3
4 4 4 4
5 5 5 5 5
*/
// for($i=1; $i<=5; $i++){
//     for($j=1; $j<=$i; $j++){
//         echo $i." ";
//     }
//     echo "<br>";
// }


/*
1
2 1
3 2 1
4 3 2 1
5 4 3 2 1
*/

// for($i=1; $i<=5; $i++){
//     for($j=$i; $j>=1; $j--){
//         echo $j." ";
//     }
//     echo "<br>";
// }


/*
1
2 3
4 5 6
7 8 9 10
*/

// $count=1;
// for($i=1; $i<=4; $i++){
//     for($j=1; $j<=$i; $j++){
//         echo $count." ";
//         $count++;
//     }
//     echo "<br>";
// }


/*

         1
       2 1 2
     3 2 1 2 3
   4 3 2 1 2 3 4
*/

for($i=1; $i<=4; $i++)
{
    for($j=3; $j>=$i; $j--){
        echo "&nbsp;&nbsp;&nbsp;";
    }

    for($k=$i; $k>=1; $k--){
        echo $k." ";
    }

    for($m=2; $m<=$i; $m++){
        echo $m." ";
    }
    echo "<br>";
}
