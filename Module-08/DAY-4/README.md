# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
Program to implement a Buffer Input/Output Stream using Java
Developed by    : Sam Israel D 
RegisterNumber  : 212222230128 
```

## Sourcecode.java:

```java
FileInputStream fi = new FileInputStream("sample.txt");
BufferedInputStream bi = new BufferedInputStream(fi);
Scanner sc=new Scanner(System.in);
int sk=sc.nextInt();
bi.skip(sk);
System.out.println("Contents after skipping "+sk+" bytes:");
int a = 0;
while((a=bi.read()) != -1)
    System.out.print((char)a);
bi.close();
fi.close();
       
```






## OUTPUT:

![alt text](image.png)

## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


