 namespace Quantum.HelloQ  
  {  
    // Import Quantum.Primitive  
    open Microsoft.Quantum.Primitive;  
      
    // Create an operation that adds two int and returns a total int  
    operation Add (a : Int, b : Int): (Int)  
    {  
        body  
        {  
            return (a + b);  
        }         
    }  
} 
