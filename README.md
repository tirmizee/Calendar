# Calendar
    //Determing if February (28,or 29)  
     if (month == 1){
        if ( (year%100!=0) && (year%4==0) || (year%400==0)){
          FebNumberOfDays = 29;
        }else{
          FebNumberOfDays = 28;
        }
     }
