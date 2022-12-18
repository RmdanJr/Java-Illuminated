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
```java
import java.util.Scanner;

class CharNumericValue {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        char c = in.next().charAt(0);
        System.out.printf("Numeric value of %c is %d.", c, Character.getNumericValue(c));
    }
}
```

66.Write a program that reads a telephone number from a dialog box; you should assume that the number is in this format: nnn-nnn-nnnn. You should output this same telephone number but with spaces instead of dashes, that is: nnn nnn nnnn.

67.Write a program that reads a sentence from a dialog box. The sentence has been encrypted as follows: only the first five even-numbered characters should be counted; all other characters should be discarded. Decrypt the sentence and output the result. For example, if the user inputs “Hiejlzl3ow”, your output should be Hello.

68.Write a program that reads a commercial website URL from a dialog box; you should expect that the URL starts with www. and ends with .com. Retrieve the name of the site and output it. For instance, if the user inputs www.yahoo.com, you should output yahoo.


## Chapter 4   Introduction to Applets and Graphics

## Chapter 5   Flow of Control, Part 1: Selection

## Chapter 6   Flow of Control, Part 2: Looping

## Chapter 7   Object-Oriented Programming, Part 2: User-Defined Classes

### Multiple Choice Exercises

1. What can you say about the name of a class?
- [ ] It must start with an uppercase letter.
- [x] The convention is to start with an uppercase letter.

2. What can you say about the name of constructors?
- [x] They must be the same name as the class name.
- [ ] They can be any name, just like other methods.

3. What is a constructor's return type?
- [ ] void
- [ ] Object
- [ ] The class name
- [x] A constructor does not have a return type.

4. It is legal to have more than one constructor in a given class.
- [x] true
- [ ] false

5. In a class, if a field is private,
- [ ] it can be accessed directly from any class.
- [x] it can be accessed directly only from inside its class.

6. In a typical class, what is the general recommendation for access modifiers?
- [ ] Instance variables are private and methods are private.
- [x] Instance variables are private and methods are public.
- [ ] Instance variables are public and methods are private.
- [ ] Instance variables are public and methods are public.

7. In a class, fields
- [ ] can only be basic data types.
- [ ] can only be basic data types or existing Java types (from existing classes).
- [x] can be basic data types, existing Java types, or user-defined types (from user-defined classes).

8. Accessors and mutators are
- [ ] instance variables of a class.
- [x] used to access and modify field variables of a class from outside the class.
- [ ] constructor methods.

9. Accessor methods typically take
- [x] no parameter.
- [ ] one parameter, of the same type as the corresponding field.

10. Mutator methods typically take
- [ ] no parameter.
- [x] one parameter, of the same type as the corresponding field.

11. Accessor methods typically
- [ ] are void methods.
- [x] return the same type as the corresponding field.

12. Mutator methods typically
- [x] are void methods.
- [ ] return the same type as the corresponding field.

13. When coding a method that performs calculations on fields of that class,
- [ ] these fields must be passed as parameters to the method.
- [x] these fields do not need to be passed as parameters to the methods because the class methods have direct access to them.

14. What is the keyword used for declaring a constant?
- [ ] static
- [x] final
- [ ] constant

15. What is the keyword used for declaring a class variable or method?
- [x] static
- [ ] final
- [ ] class

16. What can you say about enum?
- [ ] It is part of the package java.lang.
- [ ] It can be used for self-documentation, improving the readability of your code.
- [ ] An enum object is a constant object.
- [x] All of the above.

### Reading and Understanding Code

For Questions 17 and 18, consider that inside the class Sky, we have already coded the following:

image

17. Consider the following method header:

image

Is this method a constructor, mutator, or accessor?

18. Consider the following method header:

image

Is this method a constructor, mutator, or accessor?

For Questions 19 to 24, consider that the class Airplane has two methods with the following method headers; we also have a default constructor already coded.

image

19. What is the return type of method foo1?

20. What is the return type of method foo2?

21. Is method foo1 a class or instance method? Explain.

22. Is method foo2 a class or instance method? Explain.

23. Write a line or two of code to call method foo1 from a client class.

24. Write a line or two of code to call method foo2 from a client class. Assume we have instantiated an object named a1.

25. Inside method main, we see code like

image

From this, reconstruct the header of method foo3 (which belongs to the class Airplane); make appropriate assumptions if necessary.

26. Inside method main, we see code like

image

From this, reconstruct the header of method foo4 (which belongs to class Airplane).

27. If you have defined the following enum constants:

image

What is the output of the following code sequence?

image

### Fill In the Code

28. Declare two instance variables grade, which is an integer, and letterGrade, which is a char.

image

29. Declare a class field for a federal tax rate, a constant, with value .07.

image

For Questions 30 to 37, we will assume that class TelevisionChannel has three fields: name, a String; number, an integer; and cable, a boolean, which represents whether the channel is a cable channel.

30. Code a default constructor for that class: initialize the fields to an empty string, 0, and false, respectively.

image

31. Code a constructor for that class that takes three parameters.

image

32. Code the three accessors for that class.

image

33. Code the three mutators for that class.

image

34. Code the toString method.

image

35. Code the equals method.

image

36. Code a method returning the number of digits in the channel number. For instance, if the channel number is 21, the method returns 2; if the channel number is 412, the method returns 3.

image

37. Code a method returning the word cable if the current object represents a cable channel and returning the word network if the current object does not represent a cable channel.

image

7.18.4 Identifying Errors in Code

For Questions 38 to 45, consider that inside the class Gift, we have already coded the following:

image

image

38. We are coding the following inside the class Gift; where is the error?

image

39. We are coding the following inside the class Gift; where is the error?

image

40. We are coding the following inside the class Gift; where is the error?

image

41. We are coding the following inside the class Gift; where is the error?

image

42. We are coding the following inside the class Gift; where is the error?

image

43. We are coding the following inside the class Gift; where is the error?

image

44. We are coding the following in the main method inside the class GiftClient; where is the error?

image

45. We are coding the following in the main method inside the class GiftClient; where is the error?

image

46. Where are the errors in the following statement?

image

7.18.5 Debugging Area—Using Messages from the Java Compilerand Java JVM

For Questions 47 and 48, consider the following class Grade:

image

47. In the main method of the class GradeClient, you have coded

image

When you compile, you get the following message:

image

Explain what the problem is and how to fix it.

48. In the main method of the class GradeClient, you have coded

image

When you compile, you get the following message:

image

Explain what the problem is and how to fix it.

49. You coded the following definition for the class Grade :

image

When you compile, you get the following message:

image

Explain what the problem is and how to fix it.

50. You coded the following definition for the class Grade :

image

image

When you compile, you get the following message:

image

Explain what the problem is and how to fix it.

51. You coded the following definition for the class Grade :

image

When you compile, you get the following message:

image

Explain what the problem is and how to fix it.

52. You coded the following definition for the class Grade :

image

In the main method of the class GradeClient, you have coded:

image

The code compiles properly and runs, but the result is not what you expected.

The client's output is a space, not an A.

Explain what the problem is and how to fix it.

53. You have defined the following enum constants:

image

In the main method of the class Test, you have coded:

image

Explain what the problem is and how to fix it.

54. You have defined the following enum constants:

image

In the main method of the class Test, you have coded

image

When you compile, you get the following message:

image

Explain what the problem is and how to fix it.

### Write a Short Program

55. Write a class encapsulating the concept of a team (for example, “Orioles”), assuming a team has only one attribute: the team name. Include a constructor, the accessor and mutator, and methods toString and equals. Write a client class to test all the methods in your class.
```java
public class Team {
    private String name;
    public Team() {
        this.name = "";
    }
    public Team(String name) {
        this.name = name;
    }
    public String getName() {
        return this.name;
    }
    public void setName(String name) {
        this.name = name;
    }
    public String toString() {
        if(this.name.trim().compareTo("") == 0)
            return "Team name isn't set yet.";
        return "Team name: " + this.name;
    }
    public boolean equals(Team team) {
        return team.name == this.name; 
    }
}
```

57. Write a class encapsulating the concept of a television set, assuming a television set has the following attributes: a brand and a price. Include a constructor, the accessors and mutators, and methods toString and equals. Write a client class to test all the methods in your class.
```java
public class TelevisionSet {
    private String brand;
    private double price;
    public TelevisionSet() {
        this.brand = "";
        this.price = 0;
    }
    public TelevisionSet(String brand, double price) {
        this.brand = brand;
        this.price = price;
    }
    public String getBrand() {
        return brand;
    }
    public void setBrand(String brand) {
        this.brand = brand;
    }
    public double getPrice() {
        return price;
    }
    public void setPrice(double price) {
        this.price = price;
    }
    @Override
    public String toString() {
        return "TelevisionSet{" +
                "brand='" + brand + '\'' +
                ", price=" + price +
                '}';
    }
    @Override
    public boolean equals(Object o) {
        if (this == o) return true;
        if (o == null || getClass() != o.getClass()) return false;
        TelevisionSet that = (TelevisionSet) o;
        return Double.compare(that.price, price) == 0 && brand.equals(that.brand);
    }
}
```

57. Write a class encapsulating the concept of a course grade, assuming a course grade has the following attributes: a course name and a letter grade. Include a constructor, the accessors and mutators, and methods toString and equals. Write a client class to test all the methods in your class.
```java
public class CourseGrade {
    private String courseName;
    private char letterGrade;

    public CourseGrade() {
        this.courseName = "";
        this.letterGrade = '\0';
    }

    public CourseGrade(String courseName, char letterGrade) {
        this.courseName = courseName;
        this.letterGrade = letterGrade;
    }

    public String getCourseName() {
        return courseName;
    }

    public void setCourseName(String courseName) {
        this.courseName = courseName;
    }

    public char getLetterGrade() {
        return letterGrade;
    }

    public void setLetterGrade(char letterGrade) {
        this.letterGrade = letterGrade;
    }

    @Override
    public String toString() {
        return "CourseGrade{" +
                "courseName='" + courseName + '\'' +
                ", letterGrade=" + letterGrade +
                '}';
    }

    @Override
    public boolean equals(Object o) {
        if (this == o) return true;
        if (o == null || getClass() != o.getClass()) return false;
        CourseGrade that = (CourseGrade) o;
        return letterGrade == that.letterGrade && courseName.equals(that.courseName);
    }
}

```

58. Write a class encapsulating the concept of a course, assuming a course has the following attributes: a code (for instance, CS1), a description, and a number of credits (for instance, 3). Include a constructor, the accessors and mutators, and methods toString and equals. Write a client class to test all the methods in your class.
```java
import java.util.Objects;

public class Course {
    private String code;
    private String description;
    private int creditsNum;

    public String getCode() {
        return code;
    }

    public void setCode(String code) {
        this.code = code;
    }

    public String getDescription() {
        return description;
    }

    public void setDescription(String description) {
        this.description = description;
    }

    public int getCreditsNum() {
        return creditsNum;
    }

    public void setCreditsNum(int creditsNum) {
        this.creditsNum = creditsNum;
    }

    @Override
    public String toString() {
        return "Course{" +
                "code='" + code + '\'' +
                ", description='" + description + '\'' +
                ", creditsNum=" + creditsNum +
                '}';
    }

    @Override
    public boolean equals(Object o) {
        if (this == o) return true;
        if (!(o instanceof Course)) return false;
        Course course = (Course) o;
        return getCreditsNum() == course.getCreditsNum() && getCode().equals(course.getCode()) && getDescription().equals(course.getDescription());
    }
}
```

59. Write a class encapsulating the concept of a student, assuming a student has the following attributes: a name, a social security number, and a GPA (for instance, 3.5). Include a constructor, the accessors and mutators, and methods toString and equals. Write a client class to test all the methods in your class.

60. Write a class encapsulating the concept of website statistics, assuming website statistics have the following attributes: number of visitors and type of site (commercial, government, etc.). Include a constructor, the accessors and mutators, and methods toString and equals. Write a client class to test all the methods in your class.

61. Write a class encapsulating the concept of a corporate name (for example, “IBM”), assuming a corporate name has only one attribute: the corporate name itself. Include a constructor, the accessors and mutators, and methods toString and equals. Also include a method returning a potential domain name by adding www. at the beginning and .com at the end of the corporate name (for instance, if the corporate name is IBM, that method should return www.ibm.com). Write a client class to test all the methods in your class.

62. Write a class encapsulating the concept of a file, assuming a file has only a single attribute: the name of the file. Include a constructor, the accessors and mutators, and methods toString and equals. Also, code a method returning the extension of the file, that is, the letters after the last dot in the file (for instance, if the file name is Test.java, then the method should return java); if there is no dot in the file name, then the method should return “unknown extension.” Write a client class to test all the methods in your class.

7.18.7 Programming Projects

63. Write a class encapsulating the concept of the weather forecast, assuming that it has the following attributes: the temperature and the sky conditions, which could be sunny, snowy, cloudy, or rainy. Include a constructor, the accessors and mutators, and methods toString and equals. Temperature, in Fahrenheit, should be between –50 and + 150; the default value is 70, if needed. The default sky condition is sunny. Include a method that converts Fahrenheit to Celsius. Celsius temperature = (Fahrenheit temperature – 32) * 5 / 9. Also include a method that checks whether the weather attributes are consistent (there are two cases where they are not consistent: when the temperature is below 32 and it is not snowy, and when the temperature is above 100 and it is not sunny). Write a client class to test all the methods in your class.

64. Write a class encapsulating the concept of a domain name, assuming a domain name has a single attribute: the domain name itself (for instance, www.yahoo.com). Include a constructor, the accessors and mutators, and methods toString and equals. Also include the following methods: one returning whether or not the domain name starts with www; another returning the extension of the domain name (i.e., the letters after the last dot, for instance com, gov, or edu; if there is no dot in the domain name, then you should return “unknown’); and another returning the name itself (which will be the characters between www and the extension; for instance, yahoo if the domain is www.yahoo.com—if there are fewer than two dots in the domain name, then your method should return “unknown’). Write a client class to test all the methods in your class.

65. Write a class encapsulating the concept of an HTML page, assuming an HTML statement has only a single attribute: the HTML code for the page. Include a constructor, the accessors and mutators, and methods toString and equals. Include the following methods: one checking that there is a > character following each < character, one counting how many images are on the page (i.e., the number of IMG tags), and one counting how many links are on the page (i.e., the number of times we have “A HREF”). Write a client class to test all the methods in your class.

66. Write a class encapsulating the concept of coins, assuming that coins have the following attributes: a number of quarters, a number of dimes, a number of nickels, and a number of pennies. Include a constructor, the accessors and mutators, and methods toString and equals.Also code the following methods: one returning the total amount of money in dollar notation with two significant digits after the decimal point, and others returning the money in quarters (for instance, 0.75 if there are three quarters), in dimes, in nickels, and in pennies. Write a client class to test all the methods in your class.

67. Write a class encapsulating the concept of a user-defined double,assuming a user-defined double has only a single attribute: a double. Include a constructor, the accessor and mutator, and methods toString and equals. Add a method, taking one parameter specifying how many significant digits we want to have, and returning a doublerepresenting the original double truncated so that it includes the specified number of significant digits after the decimal point (for instance, if the original double is 6.9872 and the argument of the method is 2, this method will return 6.98). Write a client class to test all the methods in your class.

68. Write a class encapsulating the concept of a circle, assuming a circle has the following attributes: a Point representing the center of the circle, and the radius of the circle, an integer. Include a constructor, the accessors and mutators, and methods toString and equals. Also include methods returning the perimeter (2 * π * radius) and area (π * radius2) of the circle. Write a client class to test all the methods in your class.

69. Write a class encapsulating the concept of a rational number, assuming a rational number has the following attributes: an integer representing the numerator of the rational number, and another integer representing the denominator of the rational number. Include a constructor, the accessors and mutators, and methods toString and equals.You should not allow the denominator to be equal to 0; you should give it the default value 1 in case the corresponding argument of the constructor or a method is 0. Also include methods performing multiplication of a rational number by another and addition of a rational number to another, returning the resulting rational number in both cases. Write a client class to test all the methods in your class.

70. Write a class encapsulating the concept of an investment, assuming the investment has the following attributes: the amount of the investment, and the interest rate at which the investment will be compounded. Include a constructor, the accessors and mutators, and methods toString and equals. Also include a method returning the future value of the investment depending on how many years we hold it before selling it, which can be calculated using the formula:

image

We will assume that the interest rate is compounded annually. Write a client class to test all the methods in your class.

71. Write a class encapsulating the concept of a telephone number, assuming a telephone number has only a single attribute: a String representing the telephone number. Include a constructor, the accessor and mutator, and methods toString and equals. Also include methods returning the area code (the first three digits/characters of the phone number; if there are fewer than three characters in the phone number or if the first three characters are not digits, then this method should return “unknown area code”). Write a client class to test all the methods in your class.

7.18.8 Technical Writing

72. An advantage of object-oriented programming is code reuse, not just by the programmer who wrote the class, but by other programmers. Describe the importance of proper documentation and how you would document a class so that other programmers can use it easily.

73. Java has a number of naming conventions for classes, methods, and field variables. Is this important? Why is it good to respect these conventions?

7.18.9 Group Project (for a group of 1, 2, or 3 students)

74. Write a program that solves a quadratic equation in all cases, including when both roots are complex numbers. For this, you need to set up the following classes:

Complex, which encapsulates a complex number

ComplexPair, which encapsulates a pair of complex numbers

Quadratic, which encapsulates a quadratic equation

SolveEquation, which contains the main method

Along with the usual constructors, accessors, and mutators, you will need to code additional methods:

In the Complex class, a method that determines whether a complex object is real

In the ComplexPair class, a method that determines whether both complex numbers are identical

In the Quadratic class, a method to solve the quadratic equation and return a ComplexPair object

Additionally, you need to include code in the main method to solve several examples of quadratic equations input from the keyboard. Your output should make comments as to what type of roots we get (double real root, distinct real roots, distinct complex roots). You should check that your code works in all four basic cases:

image The quadratic equation is actually a linear equation.

image Both roots are complex.

image There is a double real root.

image There are two distinct real roots.

## Chapter 8   Single-Dimensional Arrays

## Chapter 9   Multidimensional Arrays and the ArrayList Class

## Chapter 10   Object-Oriented Programming, Part 3: Inheritance, Polymorphism, and Interfaces

## Chapter 11   Exceptions and Input/Output Operations

## Chapter 12   Graphical User Interfaces

## Chapter 13   Recursion

## Chapter 14   An Introduction to Data Structures

## Chapter 15   Running Time Analysis
