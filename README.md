# Java Illuminated, 3rd Edition Solutions

## Chapter 1   Introduction to Programming and the Java Language
### Multiple Choice Exercises

1. Which one of these is not an operating system?
- [ ] Linux
- [x] Java
- [ ] Windows
- [ ] Unix

2. Which one of these is not an application?
- [ ] Word
- [ ] Internet Explorer
- [x] Linux
- [ ] Excel

3. How many bits are in three bytes?
- [ ] 3
- [ ] 8
- [x] 24
- [ ] 0

4. In a network, the computers providing services to the other computers are called
- [ ] clients.
- [x] servers.
- [ ] laptops.

5. A binary number ending with a 0
- [x] is even.
- [ ] is odd.
- [ ] cannot tell.

6. A binary number ending with a 1
- [ ] is even.
- [x] is odd.
- [ ] cannot tell.

7. A binary number ending with two 0s
- [x] is a multiple of 4.
- [ ] is not a multiple of 4.
- [ ] cannot tell.

8. Using four bits, the largest positive binary number we can represent is 1111.
- [x] true
- [ ] false

9. Which one of these is not a programming language?
- [ ] C++
- [ ] Java
- [x] Windows
- [ ] Fortran

10. Which one of these is not an object-oriented programming language?
- [x] C
- [ ] Java
- [ ] C++
- [ ] Smalltalk

11. What is the file extension for a Java source code file?
- [x] .java
- [ ] .exe
- [ ] .class

12. What is the file extension of a compiled Java program?
- [ ] .java
- [ ] .exe
- [x] .class

13. In order to compile a program named Hello.java, what do you type at the command line?
- [ ] java Hello
- [ ] java Hello.java
- [ ] javac Hello
- [x] javac Hello.java

14. You have successfully compiled Hello.java into Hello.class. What do you type at the command line in order to run the application?
- [ ] java Hello.class
- [x] java Hello
- [ ] javac Hello
- [ ] javac Hello.class

### Converting Numbers

15. Convert the decimal number 67 into binary.
<br/>Answer: 1000011

16. Convert the decimal number 1,564 into binary.
<br/>Answer: 11000011100

17. Convert the binary number 00010101 into decimal.
<br/>Answer: 21

18. Convert the binary number 110101010101 into decimal.
<br/>Answer: 3413

19. Convert the binary number 00010101 into hexadecimal.
<br/>Answer: 15

20. Convert the hexadecimal number D8F into binary.
<br/>Answer: 110110001111

### General Questions

21. A RAM chip is organized as × 8 memory, i.e., each unit contains 8 bits, or a byte. There are 7 address pins on the chip. How many bytes does that memory chip contain?
<br/>Answer: 128 bytes.

22. If a CPU is rated at 1.5 GHz, how many instructions per second can the CPU execute?
<br/>Answer: 1.5 billion.

23. If a CPU can execute 1.2 billion instructions per second, what is the rating of the CPU in MHz?
<br/>Answer: 1.2 trillion.

24. Suppose we are using binary encoding to represent colors. For example, a black-and-white color system has only two colors and therefore needs only 1 bit to encode the color system as follows:
<br/> Bit    Color
<br/> 0    black
<br/> 1    white <br/>
<br/> With 2 bits, we can encode four colors as follows:
<br/> Bit    pattern Color
<br/> 00    black
<br/> 01    red
<br/> 10    blue
<br/> 11    white <br/><br/>
With 5 bits, how many colors can we encode?
With n bits (n being a positive integer), how many colors can we encode? (Express your answer as a function of n.)
<br/>Answer: 32 colors, `f(n) = 2 ^ n`

25. In HTML, a color can be coded in the following hexadecimal notation: #rrggbb, where
<br/>rr represents the amount of red in the color
<br/>gg represents the amount of green in the color
<br/>bb represents the amount of blue in the color
<br/>rr, gg, and bb vary between 00 and FF in hexadecimal notation, i.e., 0 and 255 in decimal equivalent notation. Give the decimal values of the red, green, and blue values in the color #33AB12.
<br/>Answer: red = 51, green = 171, blue = 18

26. RGB is a color system representing colors: R stands for red, G for green, and B for blue. A color can be coded as rgb where r is a number between 0 and 255 representing how much red there is in the color, gis a number between 0 and 255 representing how much green there is in the color, and b is a number between 0 and 255 representing how much blue there is in the color. The color gray is created by using the same value for r, g, and b. How many shades of gray are there?
<br/>Answer: 256

27. List three benefits of the Java programming language.
<br/>Answer: object-oriented, robust, platform independent.

28. What is the name of the Java compiler?
<br/>Answer: javac.

29. Write the pseudocode for a program that finds the product of two numbers.
```py
number1 = input()
number2 = input()
output(number1 * number2)
```

30. Write the pseudocode for a program that finds the sums of the numbers input that are greater than or equal to 10 and the numbers input that are less than 10.
```py
numbers = input().split(' ')
sumL = 0, sumG = 0
for(each number in numbers)
  if(number >= 10)
    sumG = sumG + number
  else
    sumL = sumL + number
output(sumL, sumG)
```

### Technical Writing

31. List the benefits of having a Local Area Network versus standalone computer systems.
![AdvNetworks](https://user-images.githubusercontent.com/51521033/207507660-3f50689b-3757-499e-a475-06c555eb91e3.gif)

32. For one day, keep a diary of the computer applications that you use. Also note any features of the applications that you think should be improved or any features you'd like to see added. ✔️

33. You are looking at two computers with the following specifications, everything else being equal:<br/>
<br/>PC # 1    PC # 2
<br/>2.6-GHz CPU    2.5-GHz CPU
<br/>2 GB L2 cache    2 GB L2 cache
<br/>1 GB RAM    4 GB RAM
<br/>500-GB Hard drive    500-GB Hard drive
<br/>$699    $699
<br/>Which PC would you buy? Explain the reasoning behind your selection.
<br/> Answer: PC # 2, more capabilities with the same price. 

34. Go to Oracle's Java site (www.oracle.com/technetwork/java). Explain what resources are available there for someone who wants to learn Java.
<br/> Answer: https://dev.java/learn/

### Group Project (for a group of 1, 2, or 3 students)

35. In the octal system, numbers are represented using digits from 0 to 7; a 0 is placed in front of the octal number to indicate that the octal system is being used. For instance, here are some examples of the equivalent of some octal numbers in the decimal system:<br/>
<br/>Octal    Decimal
<br/>000    0
<br/>001    1
<br/>007    7
<br/>010    8
<br/>011    9<br/>
<br/>In the hexadecimal system, numbers are represented using digits from 0 to 9 and letters A to F; 0x is placed in front of the hexadecimal number to indicate that the hexadecimal system is being used. For instance, here are some examples of the decimal equivalents of some hexadecimal numbers:<br/>
<br/>Hexadecimal    Decimal
<br/>0x0    0
<br/>0x1    1
<br/>0x9    9
<br/>0xA    10
<br/>0xB    11
<br/>0xF    15
<br/>0x10    16
<br/>0x11    17
<br/>0x1C    28<br/>
<br/>1. Convert 0xC3E (in hexadecimal notation) into an octal number.
<br/> Answer: 6076
<br/>2. Convert 0377 (in octal notation) into a hexadecimal number.
<br/> Answer: FF
<br/>3. Discuss how, in general, you would convert a hexadecimal number into an octal number and an octal number into a hexadecimal number.
<br/> Answer: I convert the hex/octal number to its decimal/binary notation then convert it to octal/hex. 

## Chapter 2   Programming Building Blocks—Java Basics

## Chapter 3   Object-Oriented Programming, Part 1: Using Classes

### Multiple Choice Exercises

1. If you want to use an existing class from the Java class library in your program, what keyword should you use?
- [ ] use
- [x] import
- [ ] export
- [ ] include

2. A constructor has the same name as the class name.
- [x] true
- [ ] false

3. A given class can have more than one constructor.
- [x] true
- [ ] false

4. What is the keyword used to instantiate an object in Java?
- [ ] make
- [ ] construct
- [x] new
- [ ] static

5. In a given class named Quiz, there can be only one method with the name Quiz.
- [x] true
- [ ] false

6. A static method is
- [x] a class method.
- [ ] an instance method.

7. In the Quiz class, the foo method has the following API:<br/>
![164_1a](https://user-images.githubusercontent.com/51521033/207510897-22c743cf-f494-4949-8971-9c8e838d140f.jpg)
<br/>What can you say about foo?
- [ ] It is an instance method.
- [ ] It is a class field.
- [x] It is a class method.
- [ ] It is an instance variable.

8. In the Quiz class, the foo method has the following API:<br/>
![165_1a](https://user-images.githubusercontent.com/51521033/207510951-43a7830a-19ff-47e7-8cbf-948c70400bf1.jpg)
<br/>How would you call that method?<br/>
![165_2a](https://user-images.githubusercontent.com/51521033/207510996-8ad92f61-07d0-43a4-80f3-6547ac3c1b10.jpg)
<br/>Answer: `Quiz.foo();`
 

9. In the Quiz class, the foo method has the following API:<br/>
![165_3a](https://user-images.githubusercontent.com/51521033/207511027-24df2a32-060b-4962-92a0-419acddc1bc2.jpg)
<br/>How many arguments does foo take?
- [ ] 0
- [ ] 1
- [ ] 2
- [x] 3

10. In the Quiz class, the foo method has the following API:<br/>
![165_4a](https://user-images.githubusercontent.com/51521033/207511042-24a0aa84-6bcc-4d2f-9a4b-4948b336899d.jpg)
<br/>What is the return type of method foo?
- [x] double
- [ ] int
- [ ] char
- [ ] String

11. String is a primitive data type in Java.
- [ ] true
- [x] false

12. Which one of the following is not an existing wrapper class?
- [ ] Integer
- [x] Char
- [ ] Float
- [ ] Double

13. What is the proper way of accessing the constant E of the Math class?
- [ ] Math.E( );
- [x] Math.E;
- [ ] E;
- [ ] Math( E );

### Reading and Understanding Code

14. What is the output of this code sequence?<br/>
![166_1a](https://user-images.githubusercontent.com/51521033/207513301-f5378a8b-89fa-4aef-8afe-e786c020029d.jpg)
<br/>Answer: HI

15. What is the output of this code sequence?<br/>
![166_2a](https://user-images.githubusercontent.com/51521033/207513555-8086c248-1603-496e-9c11-e555930060ff.jpg)
<br/>Answer: ABCDEFGHIJ

16. What is the output of this code sequence?<br/>
![166_3a](https://user-images.githubusercontent.com/51521033/207513687-878b3e86-1794-40d4-8c92-4f00fdb5e78c.jpg)
<br/>Answer: hello


17. What is the output of this code sequence?<br/>
![166_4a](https://user-images.githubusercontent.com/51521033/207513884-e42fe447-2acc-4252-9ac8-e89529a3d8d7.jpg)
<br/>Answer: 5

18. What is the output of this code sequence?<br/>
![166_5a](https://user-images.githubusercontent.com/51521033/207513907-80790e99-8b98-4b7b-92cd-15a73f08047b.jpg)
<br/>Answer: 2.0

19. What is the output of this code sequence? (You will need to actually compile this code and run it in order to have the correct output.)<br/>
![166_6a](https://user-images.githubusercontent.com/51521033/207513987-8195ad63-c1a8-47f3-98ab-09f250eecfb2.jpg)
<br/>Answer: 3.14159

20. What is the output of this code sequence?<br/>
![166_7a](https://user-images.githubusercontent.com/51521033/207514048-22184f39-fa26-4b16-8597-fc2bd333866b.jpg)
<br/>Answer: 6

21. What is the output of this code sequence?<br/>
![167_1a](https://user-images.githubusercontent.com/51521033/207547508-9407d70c-aae4-4d72-a1a2-f5a6e9c711df.jpg)
<br/>Answer: 4.0

22. What is the output of this code sequence? (You will need to actually compile this code and run it in order to have the correct output.)<br/>
![167_2a](https://user-images.githubusercontent.com/51521033/207547458-c139f434-c90b-4386-9524-2d86a5ed686d.jpg)
<br/>Answer: 8

23. What is the output of this code sequence?<br/>
![167_3a](https://user-images.githubusercontent.com/51521033/207547412-f29970bc-cf8e-4b66-b47f-d69a7c5fde32.jpg)
<br/>Answer: 8.0

### Write a Short Program

50.Write a program that reads two words representing passwords from the Java console and outputs the number of characters in the smaller of the two. For example, if the two words are open and sesame, then the output should be 4, the length of the shorter word, open.
```java
import java.util.Scanner;

public class SmallestPassword {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        String password1 = in.next(), password2 = in.next();
        int minLen = Math.min(password1.length(), password2.length());
        System.out.println(minLen);
    }
}
```

51.Write a program that reads a name that represents a domain name from the Java console. Your program should then concatenate that name with www. and .com in order to form an Internet domain name and output the result. For instance, if the name entered by the user is yahoo, then the output will be www.yahoo.com.
```java
import java.util.Scanner;

public class DomainGenerator {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        String domainName = in.next();
        String domain = "www." + domainName + ".com";
        System.out.println(domain);
    }
}
```

52.Write a program that reads a word from the Java console. Your program should then output the same word, output the word in uppercase letters only, output that word in lowercase letters only, and then, at the end, output the original word.
```java
import java.util.Scanner;

public class WordCases {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        String word = in.next();
        System.out.println("Lowercase Version: " + word.toLowerCase());
        System.out.println("Uppercase Version: " + word.toUpperCase());
        System.out.println("Original Word: " + word);
    }
}
```

53.Write a program that generates two random numbers between 0 and 100 and prints the smaller of the two numbers.
```java
import java.util.Random;

public class MinRandomNumber {
    public static void main(String args[]) {
        Random rand = new Random();
        int upperbound = 100;
        int randNum1 = rand.nextInt(upperbound);
        int randNum2 = rand.nextInt(upperbound);
        int minNum = Math.min(randNum1, randNum2);
        System.out.println(minNum);
    }
}
```

54.Write a program that takes a double as an input from the Java console, then computes and outputs the cube of that number.
```java
import java.util.Scanner;

public class NumberCube {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        double num = in.nextDouble();
        System.out.println(Math.pow(num, 3));
    }
}
```

55.Write a program that reads a file name from a dialog box. You should expect that the file name has one. (dot) character in it, separating the file name from the file extension. Retrieve the file extension and output it. For instance, if the user inputs index.html, you should output html; if the user inputs MyClass.java, you should output java.

56.Write a program that reads a full name (first name and last name) from a dialog box; you should expect the first name and the last name to be separated by a space. Retrieve the first name and output it.

### Programming Projects

57.Write a program that reads three integer values from the Java console representing, respectively, a number of quarters, dimes, and nickels. Convert the total coin amount to dollars and output the result with a dollar notation.
```java
import java.util.Scanner;

public class DollarsCalc {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        int quarters = in.nextInt();
        int dimes = in.nextInt();
        int nickels = in.nextInt();
        int cents = quarters * 25 + dimes * 10 + nickels * 5;
        double dollars = cents / 100.0;
        System.out.printf("$%.2f", dollars);
    }
}
```

58.Write a program that reads from the Java console the radius of a circle. Calculate and output the area and the perimeter of that circle. You can use the following formulas: area = π* r2, perimeter = 2 * π* r
```java
import java.util.Scanner;

public class CircleInfo {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        double radius = in.nextDouble();
        double area = Math.PI * Math.pow(radius, 2);
        double perimeter = 2 * Math.PI * radius;
        System.out.printf("Area: %.2f%nPerimeter: %.2f", area, perimeter);
    }
}
```

59.Write a program that generates five random integers between 60 and 100 and calculates the smallest of the five numbers.
```java
import java.util.Random;

public class MinRandomNumber {
    public static void main(String args[]) {
        Random rand = new Random();
        int n = 5;
        int lowerbound = 60;
        int upperbound = 100;
        int[] randomNums = new int[n];
        int minNum = Integer.MAX_VALUE;
        for(int i = 0; i < n; i++) {
            randomNums[i] = lowerbound + rand.nextInt(upperbound - lowerbound);
            minNum = Math.min(minNum, randomNums[i]);
        }
        System.out.println(minNum);
    }
}
```

60.Write a program that generates three random integers between 0 and 50, calculates the average, and prints the result.
```java
import java.util.Random;

public class AvgRandomNumbers {
    public static void main(String args[]) {
        Random rand = new Random();
        int n = 3;
        int upperbound = 50;
        int[] randomNums = new int[n];
        double sum = 0;
        for(int i = 0; i < n; i++) {
            randomNums[i] = rand.nextInt(upperbound);
            sum += randomNums[i];
        }
        double avg = sum / n;
        System.out.println(avg);
    }
}
```

61.Write a program that reads two integers from the Java console: one representing the number of shots taken by a basketball player, the other representing the number of shots made by the same player.
Calculate the shooting percentage and output it with the percent notation.
```java
import java.util.Scanner;

public class ShootingPercentage {
    public static void main(String args[]) {
      Scanner in = new Scanner(System.in);
      int shotsTaken = in.nextInt();
      int shotsMade = in.nextInt();
      double percentage = ((double)shotsMade / (shotsMade + shotsTaken)) * 100;
      System.out.printf("%.2f%%", percentage);
    }
}
```
62.Write a program that takes three double numbers from the Java console representing, respectively, the three coefficients a, b, and c of a quadratic equation. Solve the equation using the following formulas:

x1 = ( —b + square root (b2 —4 ac)) / (2a)

x2 = (—b —square root (b2 —4 ac)) / (2a)

Run your program on the following sample values:

a = 1.0, b = 3.0, c = 2.0

a = 0.5, b = 0.5, c = 0.125

a = 1.0, b = 3.0, c = 10.0

Discuss the results for each program run, in particular what happens in the last case.
```java
import java.util.Scanner;

public class QuadraticEquation {
    public static void main(String args[]) {
        Scanner in = new Scanner(System.in);
        double a = in.nextDouble(), b = in.nextDouble(), c = in.nextDouble();
        try {
            double m = Math.sqrt(Math.pow(b, 2) - 4 * a * c);
            if(Double.isNaN(m) || a == 0) {
                throw new ArithmeticException("There's no solution in real numbers.");
            }
            double x1 = (-b + m) / (2 * a);
            double x2 = (-b - m) / (2 * a);
            System.out.printf("possible x values: %.2f, %.2f", x1, x2);
        }
        catch(ArithmeticException e) {
            System.out.println(e.getMessage());
        }
    }
}
```
Answer: In the last case, excepration evaluates to NaN because negative numbers doesn't have real square roots since a square is either positive or 0.

63.Write a program that takes two numbers from the Java console representing, respectively, an investment and an interest rate (you will expect the user to enter a number such as .065 for the interest rate, representing a 6.5% interest rate). Your program should calculate and output (in $ notation) the future value of the investment in 5,10, and 20 years using the following formula:

future value = investment * ( 1 + interest rate )year

We will assume that the interest rate is an annual rate and is compounded annually.
```java
import java.util.Scanner;

class FutureValueCalc {
    public static void main(String[] args) {
        double futureVal5Years = 0, futureVal10Years = 0, futureVal20Years = 0;
        Scanner in = new Scanner(System.in);
        double investment = in.nextDouble();
        double interestRate = in.nextDouble();
        double currentValue = investment;
        for(int yrs = 1; yrs <= 20; yrs++) {
            currentValue = (1 + interestRate) * currentValue;
            if(yrs == 5)
                futureVal5Years = currentValue;
            else if(yrs == 10)
                futureVal10Years = currentValue;
            else if(yrs == 20)
                futureVal20Years = currentValue;
        }
        System.out.printf("Future value after 5 years: %.2f, after 10 years: %.2f, and after 20 years: %.2f.", futureVal5Years, futureVal10Years, futureVal20Years);
    }
}
```

64.Write a program that reads from the Java console the (x,y) coordinates for two points in the plane. You can assume that all numbers are integers. Using the Point class from Java (you may need to look it up on the Web), instantiate two Point objects with your input data, then output the data for both Point objects.
```java
import java.util.Scanner;
import java.awt.Point;

class PointsManipulation {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int x1 = in.nextInt();
        int y1 = in.nextInt();
        Point p1 = new Point(x1, y1);
        int x2 = in.nextInt();
        int y2 = in.nextInt();
        Point p2 = new Point(x2, y2);
        System.out.printf("Point 1: %s%nPoint 2: %s.", p1.toString(), p2.toString());
    }
}
```

65.Write a program that reads a char from the Java console. Look up the Character class on the Web, in particular the method getNumeric-Value. Using the getNumericValue method, find the corresponding Unicode encoding number and output the character along with its corresponding Unicode value. Find all the Unicode values for characters a to z and A to Z.


66.Write a program that reads a telephone number from a dialog box; you should assume that the number is in this format: nnn-nnn-nnnn. You should output this same telephone number but with spaces instead of dashes, that is: nnn nnn nnnn.

67.Write a program that reads a sentence from a dialog box. The sentence has been encrypted as follows: only the first five even-numbered characters should be counted; all other characters should be discarded. Decrypt the sentence and output the result. For example, if the user inputs “Hiejlzl3ow”, your output should be Hello.

68.Write a program that reads a commercial website URL from a dialog box; you should expect that the URL starts with www. and ends with .com. Retrieve the name of the site and output it. For instance, if the user inputs www.yahoo.com, you should output yahoo.


## Chapter 4   Introduction to Applets and Graphics

## Chapter 5   Flow of Control, Part 1: Selection

## Chapter 6   Flow of Control, Part 2: Looping

## Chapter 7   Object-Oriented Programming, Part 2: User-Defined Classes

## Chapter 8   Single-Dimensional Arrays

## Chapter 9   Multidimensional Arrays and the ArrayList Class

## Chapter 10   Object-Oriented Programming, Part 3: Inheritance, Polymorphism, and Interfaces

## Chapter 11   Exceptions and Input/Output Operations

## Chapter 12   Graphical User Interfaces

## Chapter 13   Recursion

## Chapter 14   An Introduction to Data Structures

## Chapter 15   Running Time Analysis
