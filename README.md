# FibonacciSeries
Program to generate Fibonacci Series.
## Explanation:
The code defines a package named org.javainterview. A package is used to organize related classes.

The Fibonacci class is declared within the package. This class is responsible for generating a Fibonacci series.

The class has three instance variables declared: a, b, and c. These variables are used to store the values in the Fibonacci series.

The num method is declared private, which means it can only be accessed within the Fibonacci class.

Inside the num method, a Scanner object named scan is created to read input from the user.

The code prompts the user to enter the number of times they want the Fibonacci series to be generated.

The user's input is stored in the variable num.

A for loop is used to iterate num times. The loop variable i starts from 0 and goes up to num.

Within the loop, the values of a, b, and c are updated to calculate the next number in the Fibonacci series. a is assigned the value of b, b is assigned the value of c, and c is assigned the sum of a and b.

The value of a is then printed using System.out.println(a), which displays the current number in the Fibonacci series.

The main method is declared as a public static void. It is the entry point of the program.

Within the main method, an instance of the Fibonacci class named info is created.

The num method is invoked on the info object using the dot operator (info.num()). This starts the process of generating the Fibonacci series based on user input.
