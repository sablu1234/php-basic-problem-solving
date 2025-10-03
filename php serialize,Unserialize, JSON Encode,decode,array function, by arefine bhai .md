<?php
// Serialize
// $student_information = [
//     'first_name' => 'Smith',
//     'last_name' => 'Copper',
//     'class' => 9,
//     'age' => 35,
// ];
// $final = serialize($student_information);
// echo $final;


// Unserialize
// $final_arr = unserialize($final);
// echo '<pre>';
// print_r($final_arr);
// echo '</pre>';
// echo $final_arr['first_name'];


// JSON Encode
// $student_information = [
//     'first_name' => 'Smith',
//     'last_name' => 'Copper',
//     'class' => 9,
//     'age' => 35,
// ];
// $final = json_encode($student_information);
// echo $final;



// JSON Encode
// $final_arr = json_decode($final,true);
// echo '<pre>';
// print_r($final_arr);
// echo '</pre>';


// Unset

// $student_information = [
//     'first_name' => 'Smith',
//     'last_name' => 'Copper',
//     'class' => 9,
//     'age' => 35,
// ];
// unset($student_information['last_name']);
// echo '<pre>';
// print_r($student_information);
// echo '</pre>';

// $a = 10;
// unset($a);
// echo $a;


// Array Utility
// array_walk(array, callback)

// $numbers = [1, 2, 3, 4, 5];
// array_walk($numbers, function($n){
//     $temp = $n*$n;
//   echo "Square root of ".$n." is: ".$temp."<br>";
// });

// $new_arr = array_map(function($n){
//   return $n*$n;
// },$numbers);
// echo '<pre>';
// print_r($new_arr);
// echo '</pre>';


// $numbers = [1, 2, 3, 4, 5];
// $new_arr = array_filter($numbers,function($n){
//   return $n%2==0;
// });
// echo '<pre>';
// print_r(array_values($new_arr));
// echo '</pre>';


// $students = ['Abir', 'Sohan', 'Sohag', 'Rubel', 'Sagir', 'jaber', 'Xubi'];
// $new_arr = array_filter($students,function($n){
//   // if($n[0]== 'S'){
//   //   return $n;
//   // }
//     if(strlen($n) == 5){
//       return $n;
//     }
// });
// echo '<pre>';
// print_r(array_values($new_arr));
// echo '</pre>';


// $numbers = [1, 2, 3, 4, 5, 6];
// $total = array_reduce($numbers, function($old, $new){
//   return $old+$new;
// });
// echo $total;

// $numbers = [33, 22, 11, 56, 88, 12];
// $final = array_reduce($numbers, function($old, $new){
//   if($new>$old){
//     $max = $new;
//   }else{
//     $max = $old;
//   }
//   return $max;
// });
// echo $final;



// Funciton
// User defined
// Built in


// function country()
// {
//   echo 'country';
// }
// country();
// country();
// country();
// country();
// country();


// function country()
// {
//   return 'Bangladesh';
// }
// echo country();


// function country($name)
// {
//   echo $name;
// }
// country("bangladesh");
// country("USA");
// country("China");


// function country($name)
// {
//   return $name;
// }
// echo country("bangladesh");


// function sum($a, $b){
//   $c = $a + $b;
//   return $c;
// }

// echo sum(10,20);
// echo sum(40,50);


// function sum($a=0, $b=0){
//   $c = $a + $b;
//   return $c;
// }

// echo sum();



/*
1
1 2
1 2 3
*/
// function pyramid($number){
//   for($i=1; $i<=$number; $i++){
//     for($j=1; $j<=$i; $j++){
//       echo $j. ' ';
//     }
//     echo '<br>';
//   }
// }
// pyramid(3);
// pyramid(7);


// Supper Global Variables

// $_POST
// $_GET
// $_REQUEST
// $_SERVER
// $_FILES
// $_SESSION

// include_once('about.php');
// include_once('about.php');

// echo "last section";




//form use

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- <form action="result.php" method="GET">
        Enter Name: <br>
        <input type="text" name="visitor_name" id=""><br><br>
        Enter Email: <br>
        <input type="text" name="visitor_email" id=""><br><br>
         <button type="submit">Submit</button>
    </form> -->
    <form action="" method="post">
        Enter Value: <br>
        <input type="text" name="number" id="" value="<?php if(isset($_POST['number'])){echo $_POST['number'];} ?>" autocomplete="off" autofocus><br><br>
         <button type="submit" >Submit</button>
    </form>

    <?php
    if(isset($_POST['number']))
    {
        echo '<br> Output :<br>';
        for($i=1; $i<=$_POST['number']; $i++){
            for($j=1; $j<=$i; $j++){
            echo $j. ' ';
            }
            echo '<br>';
        }
    }

    ?>

</body>
</html>
