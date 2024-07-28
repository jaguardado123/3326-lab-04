# Lab Assignment 04

In this lab you will practice writing Java code to **convert data types**.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the `src/` directory and name our class accordingly and remember to make it `public`. Next, **create your main() method inside your class**.

Now let's begin!

### Numerical Type Casting

In Java, using type casting is the fastest way to convert your numerical data types. Simply write the name of the desired numerical data type in front of your variable wrapped around parenthesis ().

**Example:**
```java
int wholeNum = 5;
float realNum = (float) wholeNum;
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

&emsp;***data_type*** **num = *Data_Type*.parse*Data_Type*( "String Value" );**

**Example:**
```java
int num = Integer.parseInt("123");
```

For more information on String conversion in Java visit: https://www.w3schools.in/java/examples/convert-string-int or https://www.javatpoint.com/java-string-to-double 

## Your Assignment

### Length Converter

Write a program to prompt the user to input a length in feet, then convert the length in feet to yards.

&emsp;**$yards = 1 / 3 * feet$**

Round your output to the nearest hundredth (second) decimal place **using type conversion**.

**Expected Output:**
```
Welcome to my Feet to Yards Length Converter!

Enter a length in feet: 9.2

9.2 feet is equal to 3.07 yards.
```

## Submit your assignment

To submit your lab assignment click on the **Source Control** icon (3 circles with 2 lines) on your leftside navbar. Next, click on the **+** symbol next to **Changes** to stage your changes. Lastly, add a commit message (ex: "First commit") and click **Commit** then **Sync Changes**. And you're done!
