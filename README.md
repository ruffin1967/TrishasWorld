# TrishasWorld
practice coding
import java.util.Scanner; 
public class ScannerDemo1 
{ 
    public static void main(String[] args) 
    { 
    	Scanner scanner = new Scanner("H E L L O");
    	
    	 
    	while (scanner.hasNext()) {
    	    System.out.println(scanner.next());
    	}
    	
      scanner.close();   
      
      
    
    } 
} 
