<?php
// Tinh tong tu 1 den 100
$i = 0;
$tong = 0;
for($i = 0 ;$i <= 100;$i++){ 
    if($i > 50) ;
    $tong += $i;
}
echo "i:$i <br>";
echo " Tong: $tong";

echo '<br>';
$i = 0;
$tong = 0;
for($i = 0 ;$i <= 100;$i++){ 
    if($i > 50) break ;
    $tong += $i;
}
echo "i:$i <br>";
echo " Tong: $tong";

echo '<br>';
$i = 0;
$tong = 0;
for($i = 0 ;$i <= 100;$i++){ 
    if($i > 50) continue ;
    $tong += $i;
}
echo "i:$i <br>";
echo " Tong: $tong";

echo '<br>';
$colors = array('red','green','blue','yellow');
foreach($colors as $value){
    echo "$value <br>";
}

for($i = 0 ;$i < count($colors) ;$i++){
    echo " $colors[$i] <br> ";
}
?>
