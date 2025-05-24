# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to display the added elements from the Dequeue using offerfirst method in java collections.
## ALGORITHM :

1. **Start the Program.**
2. **Import** `java.util.*`
3. **Define `DeQueueDemo` class with `main` method**:
   - a) Create `Scanner` object to read input.
   - b) Initialize a `Deque<String>` named `dq` using `ArrayDeque`.
4. **Read an integer `size` for number of elements.**
5. **Loop `size` times**:
   - a) Read a `String` and add it to `dq`.
6. **Print** `"Display the element of Dequeue:"`
   - a) Print the current content of `dq`.
7. **Insert `"SEC"` at the front of the Deque using `offerFirst`.**
8. **Print the updated content of `dq`.**
9. **End**

## PROGRAM:
 ```
Program to implement a JAVA DEQUEUE
Developed by    : Sam Israel D
RegisterNumber  : 212222230128
```

## Sourcecode.java:

```java
import java.util.*;

public class DeQueueDemo {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        Deque<String> dq = new ArrayDeque<String>();

        int size = sc.nextInt();
        for (int i = 0; i < size; i++) {
            dq.add(sc.next());
        }

        System.out.println("Display the element of Dequeue:");
        System.out.println(dq);

        dq.offerFirst("SEC");
        System.out.println(dq);
    }
}
```





## OUTPUT:

![alt text](image.png)

## RESULT:

Thus the java program successfully demonstrates how to display the added elements from the Dequeue using offerfirst method in java collections.


