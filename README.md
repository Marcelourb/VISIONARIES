# VISIONARIES

That is our group repository


/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package methods;


public class Methods {
   
   static void gabrielMethods(){
        Scanner sc = new Scanner (System.in);
        
        int x;
        
        System.out.println("Enter a number");
        x = sc.nextInt();
       
        
        if (x % 2 == 0){
         
            System.out.println("The numer is odd!");
        }
               
        else {
      
            System.out.println("The numer is even!");
    }  
    }

 /**
 @author Marcelo Urbano
 */


static void MarceloMethod() {

public static void main(String[] args) {
    
BufferedReader myKB = new BufferedReader (new InputStreamReader (System.in))

        System.out.println("What colour is the Traffic Light?");

     try {
  
          String lightColour = myKB.readLine();
          
          lightColour = lightColour.toUpperCase();
          
          switch (lightColour) {
             
              case "RED":
                  
                  System.out.println("Stop!");
                  break;
               
              case "ORANGE":
                  
                  System.out.println("Slow Down!");
                  break;
                  
              case "GREEN":
                  
                  System.out.println("Keep Going!");
                  break;
                  
              default 
                  
                  System.out.println("This is not a traffic light colour")
         }
     }
     
     catch (Exception e) {
         System.out.Println("This is not correct");
     }
}
}



 static void fabioramosMethods(){
 
              /**
              * @author FabioRamos
              */

             Scanner input = new Scanner (System.in);// 
       
            int age ;//variable age
            try{// i used try and catch to gets some error 
               
            System.out.println("Hello, enter your age.");// ask the user
            age = input.nextInt();// gets the input 
       
            if((age < 0) || (age >100)){// logical the has to put just 0 to 100 
            System.out.println("It is not age");
           }
             else if((age >= 1)&&(age <=17)){
            System.out.println("Sorry,Too young to vote");
           }    
             else if((age >=18) &&(age <=65)){
             System.out.println("Working hard?");
           }
             else if((age >=66)&&(age <=100)){
            System.out.println("Enjoy Retirement");
           }
            
          }
           catch(Exception e){
            System.out.println("It is not age");// 
          }
                   
          }
    
    
    
    
    
    
          /**
         * @author Ronaldo
         */
        static void RonaldoMethods(){
        int first = 10;
        int second = 10;
        int sum = first + second;
        System.out.println("first="+first+"second="+second);
        System.out.println("The sum of the first and second number is"+sum);
        // TODO code application logic here
        }


        static void KeithMethod() {
    
    
        /**
       *
       * @author keith
       */  
    
        System.out.println("This is Keith example");
        System.out.println("This is my main program");
        
        static int numMethod(int x, int y){
        /*
        *
        @keithMethod
        */
        
        return x + y;    
    }
    
    
    static void LucasMethods() {
    
        Scanner myKB = new Scanner(System.in);
         String pword;
         int numAttemts =0;
         int maxAttemts =5;
        
          do{      
            
         //Ask the user for password at least once!
         System.out.println("Enter the password.You have " + (maxAttemts - numAttemts ) + " attemps remaining ");
         pword = myKB.nextLine();
         numAttemts++;
         //repeat if the password is wrong
            
     }while(   (!pword.equals("Password")) && (numAttemts<maxAttemts));  
            
             
        if (pword.equals("Password")){
            System.out.println("Access Granted");
   
        }else {
            System.out.println("You are locked out of your account");
        }
   
}
   
   public static void main(String[] args){
       
       gabrielMethods();
       MarceloMethods();
       fabioramosMethods();
       RonaldoMethods();
       KeithMethod();
       int sum = numMethod(9, 8);
       System.out.println("Sum= " + sum);
       
      LucasMethods();
   }
}





