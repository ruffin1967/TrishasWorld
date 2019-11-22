# TrishasWorld
practice coding
import java.util.Scanner; 
public class ScannerDemo1 
{ 
    public static void main(String[] args) 
    { 
    	Scanner scanner = new Scanner("1 2 3 4 5");
    	
    	 
    	while (scanner.hasNext()) {
    	    System.out.println(scanner.next());
    	}
    	
      scanner.close();   
      
      
    
    } 
} 
