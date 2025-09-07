# Lab 04

In this lab you will practice writing Java code to **convert data types**.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the `src/` directory and name our class accordingly and remember to make it `public`. Next, **create your main() method inside your class**.

Now let's begin!

### Numerical Type Casting

In Java, using type casting is the fastest way to convert your numerical data types. Simply write the name of the desired numerical data type in front of your variable wrapped around parenthesis ().

**Example:**
```cpp
int wholeNum = 5;
float realNum = (float) wholeNum;
```

For more information on type casting in Java visit: https://www.w3schools.com/java/java_type_casting.asp

### String Conversion

To convert a numerical data type to a String we can take advantage of Java's automatic type conversion to String feature.

**Example:**
```cpp
int num = 7;
String text = "" + num;
```

Easy peasy!

Now, to convert a String to a numerical data type we need to call upon the class of the desired data type and invoke their parse method.

| Method | Description |
| --- | --- |
| Integer.parseInt( *string_value* ) | Converts a string value into an integer value and returns it. |
| Long.parseLong( *string_value* ) | Converts a string value into a long value and returns it. |
| Float.parseFloat( *string_value* ) | Converts a string value into a float value and returns it. |
| Double.parseDouble( *string_value* ) | Converts a string value into a double value and returns it. |

**Example:**
```cpp
int num = Integer.parseInt("123");
```

For more information on String conversion in Java visit: https://www.w3schools.in/java/examples/convert-string-int or https://www.javatpoint.com/java-string-to-double 

## Your Assignment

### Data Type Convertion

For this assignment you will practice the various conversion methods covered in lecture.

Copy the code snippet below and paste it inside your **main() method** in your java file.

```cpp
// Problem 1. Convert the string inside prob1 into a float literal and store inside prob1_sol.
String prob1 = "374.25";
float prob1_sol; // store solution here

// Problem 2. Convert the string inside prob2 into an integer literal and store inside prob2_sol.
String prob2 = "1250";
int prob2_sol; // store solution here

// Problem 3. Convert the float literal inside prob3 into an integer literal and store inside prob3_sol.
float prob3 = 56.715f;
int prob3_sol; // store solution here

// Problem 4. Convert the integer literal inside prob4 into a float literal and store inside prob4_sol.
int prob4 = 1500;
float prob4_sol; // store solution here

// Problem 5. Convert the double literal inside prob5 into a float literal and store inside prob5_sol.
double prob5 = 3.14159265;
float prob5_sol; // store solution here

// Problem 6. Convert the double literal inside prob6 into a string and store inside prob6_sol.
double prob6 = 214.68952356;
String prob6_sol; // store solution here
```

Convert the values stored inside the variables according to the comments. Assign the converted values into the specified variables.

You don't need to output any messages for this lab.

<br>

**Grading Criteria:**
| Criteria | Points |
|---|---|
| All data types are converted to their assigned data type | 70 |
| File and class are named Converter | 20 |
| Class is public | 10 |

[How to Submit Assignments to GitHub](https://joselitoguardado.dev/3326/How_to_Submit_Assignments_to_GitHub.pdf)
