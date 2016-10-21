Here is an example of a **function** that will multiply two numbers together and return the result to the main program.
```
function multiply(number1, number2)  //The function is given the identifier ‘multiply’ 
                                     //and the parameters to be used are enclosed in brackets. 
  product = number1 * number2        //The two numbers are multiplied and 
                                     //the result is stored in a variable named ‘product’.
  return product                     //The result stored in ‘product’ is returned to the main program.
endfunction                          //This ends the block of code defining the function.
```

Here is an example of a procedure that will multiply the numbers and print the result.
**Nothing** is returned to the main program.
```
procedure multiply(number1, number2)
  product = number1 * number2
  print(product)
endprocedure
```
The procedure prints out the result and nothing is returned to the main program.
