# Ex14 Tracking the First Unique Number in a Stream using LinkedHashMap

## DATE:12.11.2025  

### Developed by
**Name:** Shanmuga Vasanth M

**Register Number:** 212223040191 

## AIM:
To implement a program that tracks the first unique (non-repeating) number in a stream of integers using a LinkedHashMap.

## Algorithm
1. Start the program.  
2. Create a `LinkedHashMap` to store numbers and their frequency counts.  
3. For each incoming number in the stream:  
   - Increment its count in the map.  
4. Iterate through the map to find the first number with a count of 1.  
5. Display the first unique number.  
6. Stop the program.  

## Program:
```java

import java.util.*;

public class FirstUniqueTracker {
    public static void main(String[] args) {
        int[] stream = {4, 5, 4, 5, 3, 2, 1};
        LinkedHashMap<Integer, Integer> map = new LinkedHashMap<>();

        for (int num : stream)
            map.put(num, map.getOrDefault(num, 0) + 1);

        System.out.println("Stream: " + Arrays.toString(stream));
        for (Map.Entry<Integer, Integer> entry : map.entrySet()) {
            if (entry.getValue() == 1) {
                System.out.println("First unique number: " + entry.getKey());
                return;
            }
        }
        System.out.println("No unique number found.");
    }
}
```
## OUTPUT

<img width="936" height="90" alt="511980426-76de0264-f97f-4409-b58b-edeec11b670a" src="https://github.com/user-attachments/assets/001a1156-1679-4ccd-bb55-2846477e1b3f" />

## RESULT
The program successfully tracks and returns the first unique number at any point in the integer stream using a LinkedHashMap.
