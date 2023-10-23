# PriorityQueue

## Declaration and simple access

```java
// Java program to demonstrate the
// working of PriorityQueue
import java.util.*;

class PriorityQueueDemo {

      // Main Method
    public static void main(String args[])
    {
        // Creating empty priority queue
        PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();

        // Adding items to the pQueue using add()
        pQueue.add(10);
        pQueue.add(20);
        pQueue.add(15);

        // Printing the top element of PriorityQueue
        System.out.println(pQueue.peek());

        // Printing the top element and removing it
        // from the PriorityQueue container
        System.out.println(pQueue.poll());

        // Printing the top element again
        System.out.println(pQueue.peek());
    }
}
```

## Declaring

```java
// Another way
List<Integer> ints = Arrays.asList(222, 555, 666, 333, 111, 888, 777, 444);
Queue<Integer> pq = new PriorityQueue<>(Collections.reverseOrder());
pq.addAll(ints);
```

## Add Item

```java

    PriorityQueue<Integer> pq = new PriorityQueue<>();
    for(int i=0;i<3;i++){
        pq.add(i);
        pq.add(1);
    }

```

## Removing Elements:

```java
import java.util.*;
import java.io.*;

public class PriorityQueueDemo {

    public static void main(String args[])
    {
        PriorityQueue<String> pq = new PriorityQueue<>();

        pq.add("Geeks");
        pq.add("For");
        pq.add("Geeks");

        System.out.println("Initial PriorityQueue " + pq);

          // using the method
        pq.remove("Geeks");

        System.out.println("After Remove - " + pq);

        System.out.println("Poll Method - " + pq.poll());

        System.out.println("Final PriorityQueue - " + pq);
    }
}
```

## Accessing the elements:

```java
// Creating a priority queue
        PriorityQueue<String> pq = new PriorityQueue<>();
        pq.add("Geeks");
        pq.add("For");
        pq.add("Geeks");
        System.out.println("PriorityQueue: " + pq);

        // Using the peek() method
        String element = pq.peek();
```
