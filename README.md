/**
@author Marcelo Urbano 
*/

public class TrafficLight {

    static void MarceloMethod(String[] args) {
        
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
    }
    
}
