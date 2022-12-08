#  tutorial-Coercion-and-Type-Conversion-in-JavaScript
   1?
 ***Type coercion*** is the process of converting value from one type to another (such as string to number, object to boolean, and so on).
 
 
 
  so , this is Three types of conversion:
      The first rule to know is there are only three types of conversion in JavaScript:
    
  * to string
           
               //  Number to String Conversion
                // The Number 10 is converted to
                // string '10' and then '+'
               // concatenates both strings  
                   var x = 10 + '20';
                   var y = '20' + 10;
 
              // The Boolean value true is converted
              // to string 'true' and then '+'
              // concatenates both the strings
                   var z = true + '10';
 
                console.log(x);
                console.log("<br>");
                console.log(y);
                console.log("<br>");
                console.log(z);
      
      
 OutPut :
     
     1020
     <br>
     2010
     <br>
     true10
      
      
      

  * to boolean
  
        // The Boolean value true is
        // converted to number 1 and
        // then operation is performed
        var x = true + 2;
 
        // The Boolean value false is
        // converted to number 0 and
        // then operation is performed
        var y = false + 2;
 
         console.log(x);
         console.log("<br>")
         console.log(y); 
         
      
 OutPut :
     
     3
     <br>
     2
     
      
      
      
 * to number
  
        // The string '5' is converted
        // to number 5 in all cases
        // implicitly
            var w = 10 - '5';
            var x = 10 * '5';
            var y = 10 / '5';
            var z = 10 % '5';
            console.log(w);
            console.log("<br>")
            console.log(x);
            console.log("<br>")
            console.log(y);
            console.log("<br>")
            console.log(z); 
      
        
 OutPut :
     
     5
     <br>
     50
     <br>
     2
     <br>
     0
      
      
 #  Implicit vs. explicit coercion
 Type coercion can be explicit and implicit.

When a developer expresses the intention to convert between types by writing the appropriate code, like Number(value), it’s called ***explicit type coercion (or type casting)***.

Since JavaScript is a weakly-typed language, values can also be converted between different types automatically, and it is called ***implicit type coercion***.
   
      
      
  
  
  
      
