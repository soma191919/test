# test
 String i=JOptionPane.showInputDialog(null, "Enter your first name", "First name",JOptionPane.QUESTION_MESSAGE);
String j=JOptionPane.showInputDialog(null, "Enter your last name" , "Last name ",JOptionPane.QUESTION_MESSAGE);
JOptionPane.showMessageDialog(null, "welcome "+i +" "+ j +"\n Click (OK) to log in program ", "welcome", JOptionPane.INFORMATION_MESSAGE);
int x=1;
while (x==1)  {
        int a=JOptionPane.showConfirmDialog(null, "do you want check this program !! ", "tell us your opinion ", JOptionPane.YES_NO_CANCEL_OPTION);
    if(a==0){
                 int num = Integer.parseInt (JOptionPane.showInputDialog ("Enter any number equal to or between 1-12 to display the month"));
        
            switch (num){
        case 1:
            JOptionPane.showMessageDialog(null," 1/1  New years Day \n 3/1 Mawlid Al-Naby (prophet mohammads } \n 6/1 Army Day \n 22/1 Republic of Komary Kurdistan \n" ,"January" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 2:
               JOptionPane.showMessageDialog(null,"14/2  is a valantain \n 16/2 Elizabeth Peratrovich Day \n17/2  Kurdish Flag Day \n" ,"February" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 3:
               JOptionPane.showMessageDialog(null," 1/3  Woman Day \n 5/3  Uprising Day (Ranya city ) \n 7/3  Uprising Day (Hawler city ) \n 8/3  Kurdish Clothes Day \n 16/3 Halabja Chemical Attack \n20/3  Kurdish celebrate Newroz \n 21/3  first day of a  spring and Kurdish New Year Celebrate  \n " ,"March" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 4:
               JOptionPane.showMessageDialog(null," 14/4  Commemoration of Anfal Genocide campaing agaiinst kurds \n  22/4 Earth Day \n " ,"April" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 5:
               JOptionPane.showMessageDialog(null," 13/5 Mothers Day \n 28/5 Memorial Day \n" ,"May" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 6:
               JOptionPane.showMessageDialog(null,"1/6  children day \n 21/6  is a summer \n " ,"June" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 7:
               JOptionPane.showMessageDialog(null,"name of the month of numbet 7 is July \n " ,"July" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 8:
               JOptionPane.showMessageDialog(null,"22/8 Eid Al-Adha \n " ,"August" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 9:
               JOptionPane.showMessageDialog(null," \n 11/9 Islamic new year \n 20/9 Ashura Day \n 21/9 is a winter \n " ,"September" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 10:
               JOptionPane.showMessageDialog(null,"3/10 Iraqi independence Day\n " ,"October" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 11:
               JOptionPane.showMessageDialog(null," 20/11 Mawlwid Al-nabi \n " ,"November" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         case 12:
               JOptionPane.showMessageDialog(null," \n " ,"December" , JOptionPane.INFORMATION_MESSAGE );
       break;
       
         default : 
               JOptionPane.showMessageDialog(null," Error please try again \n  number of month betwen 1-12" ,"Warning" , JOptionPane.ERROR_MESSAGE );
}
    
}  

    else if (a==1){
       JOptionPane.showInputDialog(null,"please , tell us why you dont want use program ","Fedback", JOptionPane.QUESTION_MESSAGE);
       JOptionPane.showMessageDialog(null, "thank you");
    }    

    else if (a==2){
         JOptionPane.showMessageDialog(null,"please tell us your opinion dont click cancel botton !! \n Kind of Regadr", "error",JOptionPane.WARNING_MESSAGE);
        
    }
    
    else{
        
    }
         x = Integer.parseInt (JOptionPane.showInputDialog ("if you want check anthore please enter (1) or any number to log out "));

    }
    }
    
}
