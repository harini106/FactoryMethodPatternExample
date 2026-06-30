# Factory Method Pattern Example

## Overview

This project demonstrates the Factory Method Design Pattern in Java.

The Factory Method Pattern defines an interface for creating objects while allowing subclasses to decide which class to instantiate. In this example, different factories create different types of documents such as Word, PDF, and Excel.

## Project Structure

```
FactoryMethodPatternExample/
│── Document.java
│── WordDocument.java
│── PdfDocument.java
│── ExcelDocument.java
│── DocumentFactory.java
│── WordDocumentFactory.java
│── PdfDocumentFactory.java
│── ExcelDocumentFactory.java
│── FactoryMethodTest.java
└── README.md
```

## Features

- Factory Method Design Pattern
- Abstract Factory Class
- Multiple Concrete Factories
- Interface-based Design
- Loose Coupling

## Compile

```bash
javac *.java
```

## Run

```bash
java FactoryMethodTest
```

## Expected Output

```
Opening Word Document...
Opening PDF Document...
Opening Excel Document...
```

## Author

Harini
