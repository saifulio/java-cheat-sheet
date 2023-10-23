# HashSet

## Declaration

```java
import java.util.HashSet; // Import the HashSet class

HashSet<String> cars = new HashSet<String>();
```

## Add Items

```java
// Import the HashSet class
import java.util.HashSet;

public class Main {
  public static void main(String[] args) {
    HashSet<String> cars = new HashSet<String>();
    cars.add("Volvo");
    cars.add("BMW");
    cars.add("Ford");
    cars.add("BMW");
    cars.add("Mazda");
    System.out.println(cars);
  }
}
```

## Check If an Item Exists

```java
cars.contains("Mazda");
```

## Remove an Item

```java
cars.remove("Volvo");
// clear all items
cars.clear();
```

## HashSet Size

```java
cars.size();
```

## Loop Through a HashSet

```java
for (String i : cars) {
  System.out.println(i);
}
```
