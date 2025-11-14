# Ex11 Convert HashSet to ArrayList in Java

## DATE:12.11.2025  

### Developed by
**Name:** Shanmuga Vasanth M

**Register Number:** 212223040191 

## AIM:
To convert a collection of distinct integers stored in a HashSet into an ArrayList and display its contents.

## Algorithm
1. Start the program.  
2. Create a `HashSet` and add distinct integer elements to it.  
3. Use the `ArrayList` constructor to convert the `HashSet` into an `ArrayList`.  
4. Display the elements of both the `HashSet` and the `ArrayList`.  
5. Stop the program.  

## Program:
```java

import java.util.*;

public class HashSetToArrayList {
    public static void main(String[] args) {
        HashSet<Integer> set = new HashSet<>();
        set.add(10);
        set.add(20);
        set.add(30);
        set.add(40);
        set.add(50);

        System.out.println("HashSet: " + set);

        ArrayList<Integer> list = new ArrayList<>(set);
        System.out.println("ArrayList: " + list);
    }
}
```
## OUTPUT 

<img width="946" height="94" alt="511974471-647e442e-033d-4082-aea2-db80a1d86e16" src="https://github.com/user-attachments/assets/3fd85f1c-0976-485b-bd58-f005f1dccd69" />

## RESULT
The program successfully converts a collection of distinct integers stored in a HashSet into an ArrayList.
