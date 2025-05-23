# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



## PROGRAM:
 ```
Program to implement a Packages using Java
Developed by    : Sam Israel D 
RegisterNumber  : 212222230128 
```

## Sourcecode.java:

```java
class Display
{
    synchronized void wish(String str){
        System.out.println("Welcome :: "+str);
        System.out.println("Welcome :: "+str);
        try{
            Thread.sleep(400);
        } catch(Exception e) {
            System.out.println(e);
        }
    }
}
```





## OUTPUT:

![alt text](image.png)

## RESULT:
Thus the java program for synchronization was executed successfully.

