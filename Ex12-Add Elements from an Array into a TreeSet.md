# Ex12 Add Elements from an Array into a TreeSet

## DATE:12.11.2025  

### Developed by
**Name:** Shanmuga Vasanth M

**Register Number:** 212223040191 

## AIM:
To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.

## Algorithm
1. Start the program.  
2. Initialize an array with integer elements.  
3. Create an empty `TreeSet`.  
4. Add all elements from the array into the `TreeSet`.  
5. Display the elements of the `TreeSet` (which are automatically sorted).  
6. Stop the program.  

## Program:
```java

import java.util.*;

public class ArrayToTreeSet {
    public static void main(String[] args) {
        Integer[] arr = {50, 20, 40, 10, 30};

        TreeSet<Integer> set = new TreeSet<>(Arrays.asList(arr));

        System.out.println("Array elements: " + Arrays.toString(arr));
        System.out.println("TreeSet elements (sorted): " + set);
    }
}

```
## OUTPUT 

<img width="925" height="78" alt="511976713-22d8f7fe-02ed-49a6-8a2f-9e819ed1eaaf" src="https://github.com/user-attachments/assets/f7e14224-53b2-4859-b3dd-0293219f89f5" />

## RESULT
The program successfully adds elements from an array into a TreeSet and displays them in sorted order.
