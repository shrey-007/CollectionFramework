![Example Image](Collections-in-Java-768.webp)

## Interfaces-:
### 1) Iterable Interface-:
This is the root interface for the entire collection framework. The collection interface extends the iterable interface. Therefore, inherently, all the interfaces and classes implement this interface. The main functionality of this interface is to provide an iterator for the collections. Therefore, this interface contains only one abstract method which is the iterator. It returns the 
```java 
Iterator iterator();
```
### 2) Collection Interface:
This interface extends the iterable interface and is implemented by all the classes in the collection framework. This interface contains all the basic methods which every collection has like adding the data into the collection, removing the data, clearing the data, etc. All these methods are implemented in this interface because these methods are implemented by all the classes irrespective of their style of implementation. Therefore, in short, we can say that this interface builds a foundation on which the collection classes are implemented.
### 3) List Interface-:
This is a child interface of the collection interface. This interface is dedicated to the data of the list type in which we can store all the ordered collections of the objects. This also allows duplicate data to be present in it. This list interface is implemented by various classes like ArrayList, LinkedList, Vector, Stack, etc.
### 4) Queue Interface-:
As the name suggests, a queue interface maintains the FIFO(First In First Out) order similar to a real-world queue line. This interface is dedicated to storing all the elements where the order of the elements matter. There are various classes like PriorityQueue, ArrayDeque, etc. 
### 5) Deque Interface-:
This is a very slight variation of the queue data structure. Deque, also known as a double-ended queue, is a data structure where we can add and remove elements from both ends of the queue. This interface extends the queue interface. The class which implements this interface is ArrayDeque. Since ArrayDeque class implements the Deque interface, we can instantiate a deque object with this class. 
### 6) Set Interface-:
A set is an unordered collection of objects in which duplicate values cannot be stored. This collection is used when we wish to avoid the duplication of the objects and wish to store only the unique objects. This set interface is implemented by various classes like HashSet, TreeSet, LinkedHashSet, etc.
### 7) Sorted Set Interface-:
This interface is very similar to the set interface. The only difference is that this interface has extra methods that maintain the ordering of the elements. The sorted set interface extends the set interface and is used to handle the data which needs to be sorted. The class which implements this interface is TreeSet.
### 8) Map Interface-:
A map is a data structure that supports the key-value pair for mapping the data. This interface doesn’t support duplicate keys because the same key cannot have multiple mappings, however, it allows duplicate values in different keys. A map is useful if there is data and we wish to perform operations on the basis of the key. This map interface is implemented by various classes like HashMap, TreeMap, etc.
### 9) Sorted Map
### 10) Navigable Map

## Classes-:
### 1) ArrayList-:
ArrayList is a class implemented using a list interface, it provides the functionality of a dynamic array where the size of the array is not fixed.
### 2) Vector-:
Vector is a Part of the collection class that implements a dynamic array that can grow or shrink its size as required.It is same as ArrayList, but it is synchronized, but arraylist is not.
### 3) Stack-:
It is not recommended to use Stack class. Instead use ArrayDeque, it can also work as Stack.
### 4) LinkedList-:
It inherits List interface as well as Deque interface
### 5) HashSet-:
   HashSet is implemented using the Hashtable data structure.It stores unique items. It offers constant time performance for the performing operations like add, remove, contains, and size.
### 6) LinkedHashSet-:
LinkedHashSet is an ordered version of HashSet that maintains a doubly-linked List across all elements. It stores the unique items in insertion ordered manner. Difference between HashSet and LinkedHashSet is given in set package. 
### 7) TreeSet-:
TreeSet class is implementations of the SortedSet interface in Java that uses a Tree for storage. It stores unique elements in sorted order using self balancing binary trees.
### 8) PriorityQueue-:
The PriorityQueue is based on the priority heap. The elements of the priority queue are ordered according to the natural ordering, or by a Comparator provided at queue construction time, depending on which constructor is used.
### 9) ArrayDeque-:
The ArrayDeque class in Java is an implementation of the Deque interface that uses a resizable array to store its elements. The ArrayDeque class provides constant-time performance for inserting and removing elements from both ends.
### 10) HashMap-:
HashMap Class is similar to HashTable but the data unsynchronized. It stores the data in (Key, Value) pairs, and you can access them by an index of another type.
### 11) EnumMap-:
EnumMap extends AbstractMap and implements the Map interface in Java.
### 12) AbstractMap-:
The AbstractMap class is a part of the Java Collection Framework. It implements the Map interface to provide a structure to it, by doing so it makes the further implementations easier.
### 13) TreeMap-:
A TreeMap is implemented using a Red-Black tree.TreeMap provides an ordered collection of key-value pairs, where the keys are ordered based on their natural order or a custom Comparator passed to the constructor.










