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
