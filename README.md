# JS
JavaScript
HackerRank Code
Day 1 Functions


function factorial(n){
   var fact;
    if(n==0 || n==1){
        fact=1;
    }
    else{
     fact=n*factorial(n-1);
      
    }
   return fact
}
