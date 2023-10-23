# ArrayList

## Declaring ArrayList

```java
import java.util.ArrayList; // import the ArrayList class

ArrayList<String> cars = new ArrayList<String>(); // Create an ArrayList object
```

## Add Items

```java
import java.util.ArrayList;

public class Main {
  public static void main(String[] args) {
    ArrayList<String> cars = new ArrayList<String>();
    cars.add("Volvo");
    cars.add("BMW");
    cars.add("Ford");
    cars.add("Mazda");
    System.out.println(cars);
  }
}
```

## Access an Item

```java
cars.get(0);
```

## Change an Item

```java
cars.set(0, "Opel");
```

## Remove an Item

```java
cars.remove(0);
// To remove all the elements in the ArrayList, use the clear() method:
cars.clear();
```

## ArrayList Size

```java
cars.size();
```

## Loop Through an ArrayList

```java
public class Main {
  public static void main(String[] args) {
    ArrayList<String> cars = new ArrayList<String>();
    cars.add("Volvo");
    cars.add("BMW");
    cars.add("Ford");
    cars.add("Mazda");
    for (int i = 0; i < cars.size(); i++) {
      System.out.println(cars.get(i));
    }
    // or
    for (String i : cars) {
      System.out.println(i);
    }
  }
}
```

## Sort an ArrayList

```java
ArrayList<String> cars = new ArrayList<String>();
    cars.add("Volvo");
    cars.add("BMW");
    cars.add("Ford");
    cars.add("Mazda");
    Collections.sort(cars);  // Sort cars
    for (String i : cars) {
      System.out.println(i);
    }
```
