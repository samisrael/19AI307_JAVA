# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Student class given below that initializes the name and department as class field with the string "Antony” and "AIML".

Call the getName() method and getDept() in the main method of the Sample class  and store the values in the variable, and print the value.
## ALGORITHM :

1.	Start the program.  
2.	Define a class `Student`:  
    a.	Declare two string variables: `name` and `department`.  
3.	Create a parameterized constructor in `Student`:  
    a.	Accept two parameters: `name` and `department`.  
    b.	Assign the parameters to the class fields using `this` keyword.  
4.	Define two getter methods in the `Student` class:  
    a.	`getName()` – returns the value of `name`.  
    b.	`getDept()` – returns the value of `department`.  
5.	Define a class `Sample` with the `main` method.  
6.	Inside the `main` method:  
    a.	Create an object of `Student` using the constructor and pass `"Antony"` and `"AIML"` as arguments.  
    b.	Call `getName()` and print the returned value.  
    c.	Call `getDept()` and print the returned value.  
7.	End the program.  




## PROGRAM:
 ```
Program to implement a Parameterized Constructor Using Java
Developed by    : Sam Israel D 
RegisterNumber  : 21222230128 
```

## Sourcecode.java:


```java
class Student {
    String name;
    String department;
    Student(String name, String department) {
        this.name = name;
        this.department = department;
    }
    public String getName() {
        return name;
    }
    public String getDept() {
        return department;
    }
}

public class Sample {
    public static void main(String[] args) {
        Student student = new Student("Antony", "AIML");
        System.out.println(student.getName());
        System.out.println(student.getDept());
    }
}

```




## OUTPUT:

![alt text](image.png)

## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


