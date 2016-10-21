Sub programs are **called** from the main program and their code is then executed.
```
//This is the function
function multiply(number1, number2)	 
  product = number1 * number2	
endfunction	

//This is the main program
firstNumber = input(“Please enter the first number.)  
//The user is asked to enter the numbers.
secondNumber = input(“Please enter the second number.)
result = multiply(firstNumber, secondNumber)
//The function is called and the two numbers are passed to it. 
//These are called arguments.
print(result)
```

In the main program the variables storing the two numbers have different identifiers to the parameters. The ones used in the main program are called **global variables** as they can be used anywhere in the main program and are not restricted to just one function.
Also in the main program the variable storing the result of the multiplication has a different identifier than the one in the function.

It is a good idea to use different identifiers for the local and global variables as it is very easy to become confused as to which one is being referred to.
