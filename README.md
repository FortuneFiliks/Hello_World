<?php
declare(strict_types = 1);

$year = date("Y");
if($year < 2024){
	echo "Welcome to a new year";
}

function cleaning_My_Room(){
    $chemical_A = "ammonia";
    $chemical_B = "bleach";
    If (($chemical_A == "ammonia") ^ ($chemical_B == "bleach")){
         Return "CHEMICAL HAZARD ALERT!!!!";
    }else{
         echo "I cleaned my room with bleach and water only, as including ammonia results in a chemical hazard";
    }
}

cleaning_My_Room();


$exam_Score = 50;
echo ($exam_Score >= 18) ? "I passed the course" : "I failed the course";

$status = ($exam_Score >= 18) ? "PASS" : "FAIL";
$jamb_Score = 185;

?>
