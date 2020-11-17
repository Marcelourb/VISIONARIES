# VISIONARIES

That is our group repository


/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package methods;

/**
 *
 * @author kcfke
 */
public class Methods {

    static void KeithMethod() {
        System.out.println("This is Keith example");
        System.out.println("This is my main program");
       
    
    
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
  
    
    
    
    
    
    static int numMethod(int x, int y){
        /*
        *
        @keithMethod
        */
        
           
        return x + y; 
        
    }
    
    
   public static void main(String[] args){
       
       KeithMethod();
       int sum = numMethod(9, 8);
       System.out.println("Sum= " + sum);
       
       LucasMethods();
   }
}





