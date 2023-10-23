# DeQueue

## Declering

```java
import java.util.ArrayDeque;
import java.util.Deque;

public class Example {
  public static void main(String[] args) {
    Deque<Integer> deque = new ArrayDeque<>();
    deque.addFirst(1);
    deque.addLast(2);
    int first = deque.removeFirst();
    int last = deque.removeLast();
    System.out.println("First: " + first + ", Last: " + last);
  }
}
```

## Methods

```java
deque.add(Element e);	// The method inserts a particular element at the end of the deque.

deque.addAll​(Collection<? extends E> c)	// Adds all of the elements in the specified collection at the end of this deque, as if by calling addLast(E) on each one, in the order that they are returned by the collection’s iterator.

deque.addFirst(Element e)	// The method inserts particular element at the start of the deque.

deque.addLast(Element e) 	// The method inserts a particular element at the end of the deque. It is similar to the add() method

deque.clear() // The method removes all deque elements.

deque.clone() // The method copies the deque.

deque.contains(Obj)	// The method checks whether a deque contains the element or not

deque.element() // The method returns element at the head of the deque

forEach​(Consumer<? super E> action)	// Performs the given action for each element of the Iterable until all elements have been processed or the action throws an exception.

deque.getFirst() // The method returns first element of the deque

deque.getLast()	// The method returns last element of the deque

deque.isEmpty()	// The method checks whether the deque is empty or not.

deque.iterator() // Returns an iterator over the elements in this deque.

deque.offer(Element e) // The method inserts element at the end of deque.

deque.offerFirst(Element e) // The method inserts element at the front of deque.

deque.offerLast(Element e) // The method inserts element at the end of the deque.

deque.peek() // The method returns head element without removing it.

deque.poll() // The method returns head element and also removes it

deque.pop()	// The method pops out an element for stack represented by deque

deque.push(Element e) // The method pushes an element onto stack represented by deque

deque.remove() // The method returns head element and also removes it

deque.remove​(Object o)	// Removes a single instance of the specified element from this deque.

deque.removeAll​(Collection<?> c) // Removes all of this collection’s elements that are also contained in the specified collection (optional operation).

deque.removeFirst()	// The method returns the first element and also removes it

deque.removeFirstOccurrence​(Object o) // Removes the first occurrence of the specified element in this deque (when traversing the deque from head to tail).
deque.removeIf​(Predicate<? super Element> filter) // Removes all of the elements of this collection that satisfy the given predicate.

deque.removeLast() // The method returns the last element and also removes it

deque.removeLastOccurrence​(Object o) // Removes the last occurrence of the specified element in this deque (when traversing the deque from head to tail).

deque.retainAll​(Collection<?> c) // Retains only the elements in this collection that are contained in the specified collection (optional operation).

deque.size() // Returns the number of elements in this deque.

deque.spliterator()	// Creates a late-binding and fail-fast Spliterator over the elements in this deque.

deque.toArray()	// Returns an array containing all of the elements in this deque in proper sequence (from first to the last element).

deque.toArray​(T[] a)	// Returns an array containing all of the elements in this deque in proper sequence (from first to the last element); the runtime type of the returned array is that of the specified array.
```
