<?php

$numbers = array(1, 2, 3, 4);

foreach ($numbers as $value) {
    echo $value;
}

function multiplication()
    echo $numbers[0] * $numbers[1] * $numbers[2] * $numbers[3];
    
multiplication();
?>
