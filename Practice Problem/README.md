# BridgeLabz Practice Problems

**Classroom**: GLA-Java-1Y-AT  
**Teacher**: Kajal Wankhede Maam  
**Assignment**: Practice Problems - "Few Problems to Start With"

Welcome to the BridgeLabz Practice Problems repository! This collection contains 10 Java programs designed to help you practice fundamental programming concepts including input/output, arithmetic operations, and mathematical formulas.

## Project Overview

This is a **living repository** for the GLA-Java-1Y-AT classroom that will be continuously updated as Kajal Wankhede Maam assigns new problems and coursework. 

**Current Status**: This repository contains the initial 10 programs from "Few Problems to Start With". As the course progresses, more problems, assignments, and learning modules will be added.

### How This Repository Evolves

- New problems will be added as they are assigned
- Solutions and implementations will be updated with each assignment
- Code will be refactored and improved as new concepts are learned
- Documentation will expand to include advanced topics and techniques

This repository is divided into two categories:
- **Assisted Problems**: Basic starter programs with guided implementations
- **Self Problems**: Intermediate programs for independent practice

## Assisted Problems

### 1. WelcomeToBridgeLabz
- **File**: `WelcomeToBridgelabz.java`
- **Description**: A simple starter program that prints "WelcomeToBridgeLabz!" to the screen
- **Concepts**: Basic output using `System.out.println()`
- **How to run**: 
  ```
  javac WelcomeToBridgelabz.java
  java WelcomeToBridgelabz
  ```

### 2. AddTwoNumbers
- **File**: `AddTwoNumbers.java`
- **Description**: Takes two numbers as input and prints their sum
- **Concepts**: User input using Scanner, arithmetic operations
- **How to run**: 
  ```
  javac AddTwoNumbers.java
  java AddTwoNumbers
  ```

### 3. CelsiusToFahrenheitConversion
- **File**: `CelsiusToFahrenheitConversion.java`
- **Description**: Converts temperature from Celsius to Fahrenheit
- **Formula**: Fahrenheit = (Celsius × 9/5) + 32
- **Concepts**: User input, arithmetic with floating-point numbers
- **How to run**: 
  ```
  javac CelsiusToFahrenheitConversion.java
  java CelsiusToFahrenheitConversion
  ```

### 4. AreaOfACircle
- **File**: `AreaOfACircle.java`
- **Description**: Calculates the area of a circle given the radius
- **Formula**: Area = π × radius²
- **Concepts**: Using Math.PI constant, mathematical operations
- **How to run**: 
  ```
  javac AreaOfACircle.java
  java AreaOfACircle
  ```

### 5. VolumeOfACylinder
- **File**: `VolumeOfACylinder.java`
- **Description**: Calculates the volume of a cylinder given radius and height
- **Formula**: Volume = π × radius² × height
- **Concepts**: Multiple inputs, complex mathematical calculations
- **How to run**: 
  ```
  javac VolumeOfACylinder.java
  java VolumeOfACylinder
  ```

## Self Problems

### 1. CalculateSimpleInterest
- **File**: `CalculateSimpleInterest.java`
- **Description**: Calculates simple interest on a principal amount
- **Formula**: Simple Interest = (Principal × Rate × Time) / 100
- **Input**: Principal, Rate (per annum), Time (in years)
- **Concepts**: Multiple inputs, percentage calculations

### 2. PerimeterOfARectangle
- **File**: `PerimeterOfARectangle.java`
- **Description**: Calculates the perimeter of a rectangle given length and width
- **Formula**: Perimeter = 2 × (length + width)
- **Concepts**: Basic geometry, arithmetic operations

### 3. PowerCalculation
- **File**: `PowerCalculation.java`
- **Description**: Calculates base raised to the power of exponent
- **Concepts**: Using Math.pow() method, exponential calculations
- **Note**: Implemented without loops or conditionals

### 4. CalculateAverageOfThreeNumbers
- **File**: `CalculateAverageOfThreeNumbers.java`
- **Description**: Calculates the average of three numbers
- **Formula**: Average = (number1 + number2 + number3) / 3
- **Concepts**: Multiple inputs, statistical calculations

### 5. ConvertKilometersToMiles
- **File**: `ConvertKilometersToMiles.java`
- **Description**: Converts distance from kilometers to miles
- **Formula**: Miles = Kilometers × 0.621371
- **Concepts**: Unit conversion, floating-point arithmetic

## Prerequisites

- Java Development Kit (JDK) installed on your system
- Basic understanding of Java syntax and command-line operations
- A text editor or IDE (VS Code, IntelliJ IDEA, Eclipse, etc.)

## How to Compile and Run

### Compile a single file:
```bash
javac FileName.java
```

### Run a compiled program:
```bash
java FileName
```

### Compile all files at once:
```bash
javac *.java
```

## File Structure

```
Practice Problem/
├── README.md
├── WelcomeToBridgelabz.java
├── AddTwoNumbers.java
├── CelsiusToFahrenheitConversion.java
├── AreaOfACircle.java
├── VolumeOfACylinder.java
├── CalculateSimpleInterest.java
├── PerimeterOfARectangle.java
├── PowerCalculation.java
├── CalculateAverageOfThreeNumbers.java
└── ConvertKilometersToMiles.java
```

## Key Concepts Covered

- **Input/Output**: Using Scanner for user input and System.out for output
- **Data Types**: Working with double, int, and other primitive types
- **Arithmetic Operations**: Basic mathematical operations and formulas
- **Mathematical Functions**: Using Math.PI and Math.pow()
- **Resource Management**: Proper closing of Scanner objects

## Tips for Learning

1. **Start with Assisted Problems**: Complete these programs first to build confidence
2. **Understand the Logic**: Don't just copy-paste; understand what each line does
3. **Experiment**: Try modifying the programs or adding new features
4. **Practice Self Problems**: After completing assisted problems, tackle self problems independently
5. **Debug**: Use print statements to track variable values if something goes wrong

## Common Errors and Solutions

| Error | Solution |
|-------|----------|
| `javac: command not found` | Ensure JDK is installed and added to system PATH |
| `InputMismatchException` | Enter the correct data type (number instead of text) |
| `NoSuchElementException` | Ensure input is provided before running the program |
| `NullPointerException` | Initialize variables before using them |

## Contributing

Feel free to modify these programs, add error handling, or enhance them with additional features!

## License

This project is created for educational purposes as part of the BridgeLabz learning program.

---

**Happy Coding!** 🚀
