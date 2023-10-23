# Collection Sorting

## Using compareTo() Method

```java
PriorityQueue<Integer> pq = new PriorityQueue<>((o1, o2) -> o2.compareTo(o1));
```

## Using compare() Method

```java
PriorityQueue<Integer> pq = new PriorityQueue<>((x, y) -> Integer.compare(y, x));
```

## Using Custom Comparator Method

```java
PriorityQueue<Integer> pq = new PriorityQueue<>(new CustomIntegerComparator());

    static class CustomIntegerComparator implements Comparator<Integer> {

        @Override
        public int compare(Integer o1, Integer o2) {
            return o1 < o2 ? 1 : -1;
        }
    }
```

## Using Collection Method

```java
PriorityQueue<Integer> pq= new PriorityQueue<>(Collections.reverseOrder());
```

## Using Arrow(Lambda expression) Function

```java
PriorityQueue<Integer> pq= new PriorityQueue<>((a, b) -> b - a);
```

## Using Custom Comparator Method (via Difference)

```java
PriorityQueue<Integer> pq = new PriorityQueue<> (new Comparator<Integer> ()
{
public int compare(Integer a, Integer b)
{
return b - a;
}
});
```
