# Ex15 Value Existence Check in a TreeMap

## DATE:12.11.2025  

### Developed by
**Name:** Shanmuga Vasanth M

**Register Number:** 212223040191 

## AIM:
To write a Java program that checks whether a given value exists in a TreeMap.

## Algorithm
1. Start the program.  
2. Create a `TreeMap` and insert key–value pairs.  
3. Use the `containsValue()` method to check if a specific value exists in the map.  
4. Display whether the value is found or not.  
5. Stop the program.  

## Program:
```java

import java.util.*;

public class TreeMapValueCheck {
    public static void main(String[] args) {
        TreeMap<Integer, String> map = new TreeMap<>();
        map.put(1, "Apple");
        map.put(2, "Banana");
        map.put(3, "Cherry");
        map.put(4, "Mango");

        System.out.println("TreeMap: " + map);
        String valueToCheck = "Banana";

        if (map.containsValue(valueToCheck))
            System.out.println("The value '" + valueToCheck + "' exists in the TreeMap.");
        else
            System.out.println("The value '" + valueToCheck + "' does not exist in the TreeMap.");
    }
}
```

## OUIPUT

<img width="940" height="83" alt="511982777-e585fc8c-6505-4803-8863-ecefe234ea15" src="https://github.com/user-attachments/assets/3932ceca-cc77-4850-81b3-872c383858b4" />

## RESULT
Thus, the program successfully checks whether a specified value exists in a TreeMap using the containsValue() method.
