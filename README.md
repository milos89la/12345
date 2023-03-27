# 12345
12345

function print_cudan($b){
    for($i=0;$i<$b;$i++){
        for($j=0;$j<$b;$j++){
            if(($i+$j+1)>$b){
                echo ($i+$j+1)%$b." ";

            }
            else{
                echo ($i+$j+1)." ";
            }
           
        }
        echo '<br>' ;

    }
}
print_cudan(5); 
