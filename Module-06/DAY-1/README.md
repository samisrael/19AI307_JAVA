# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End






## PROGRAM:
 ```
Program to implement a Inner Class using Java
Developed by    : Sam Israel D 
RegisterNumber  : 21222230128 
```

## Sourcecode.java:

```java
class Name{
    String value = "Johnson";
    void display(){
        class Inner{
            void print(){
                System.out.println("Name given in Outer Class is "+value);
            }
        }
        Inner in = new Inner();
        in.print();
    }
}
public class Main{
    public static void main(String[] args){
        Name nam = new Name();
        nam.display();
    }
}
```





## OUTPUT:

![alt text](image.png)

## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

