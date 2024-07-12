# Lab Assignment 04

In this lab you will practice writing Java code to convert data types.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the src/ directory and name our class accordingly and remember to make it **public**. Next, **create your main() method inside your class**.

Now let's begin!

## Converting Data Types

### Type Casting

In Java, using type casting is the fastest way to convert your numerical data types. Simply write the name of the desired numerical data type in front of your variable wrapped around parenthesis ().

**Example:**
```java
int wholeNum = 5;
float realNum = (float) wholeNum;

// or

double decimal = 12.7856;
int no_decimal = (int) decimal;
```

For more information on type casting in Java visit: https://www.w3schools.com/java/java_type_casting.asp

### String Conversion

To convert a numerical data type to a String we can take advantage of Java's automatic type conversion to String feature.

**Example:**
```java
int num = 7;
String text = "" + num;
```

Easy peasy!

Now, to convert a String to a numerical data type we need to call upon the class of the desired data type and invoke their parse method.

[data type] num = [Data type].parse[Data type]( stringVar );

**Example:**
```java
String text = "123";
int num = Integer.parseInt(text);

// or

double realNum = Double.parseDouble(text);
```

For more information on String conversion in Java visit: https://www.w3schools.in/java/examples/convert-string-int

## Your program

**Length Converter**

Write a program to prompt the user to input a length in feet and store the value. Next, convert the length in feet into length in yards.

**yards = 1 / 3 x feet**

Round your output to the nearest hundredth (second) decimal place using type conversion.

Your output should look like:

```
Welcome to my Feet to Yards Length Converter!

Enter a length in feet: 9.2

9.2 feet is equal to 3.07 yards.
```

## Submit your assignment

To submit your lab assignment click on the source control icon (3 circles with 2 lines) on your leftside navbar. Next, click on the '+' symbol next to "Changes" to stage your changes. Lastly, add a commit message (ex: "First commit") and click "Commit" then "Push" or "Sync Changes". And you're done!
