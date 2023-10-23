# HashMap

```java
import java.util.HashMap; // import the HashMap class

HashMap<String, String> capitalCities = new HashMap<String, String>();
```

## Add Items

```java
HashMap<String, String> capitalCities = new HashMap<String, String>();

    // Add keys and values (Country, City)
    capitalCities.put("England", "London");
```

## Access an Item

```java
capitalCities.get("England");
```

## Remove an Item

```java
capitalCities.remove("England");
// to remove all items
capitalCities.clear();
```

## Check if an item exists

```java
capitalCities.containsKey("England");
```

## HashMap size

```java
capitalCities.size();
```

## Loop through HashMap

```java
// Print Keys
for (String i : capitalCities.keySet()) {
    System.out.println(i);
}

// Print values
for (String i : capitalCities.values()) {
  System.out.println(i);
}

// Print keys and values
for (String i : capitalCities.keySet()) {
  System.out.println("key: " + i + " value: " + capitalCities.get(i));
}
```
