# JAVA_15
## Set

Set in Java
Last Updated: 26-06-2020
The set interface present in the java.util package and extends the Collection interface is an unordered collection of objects in which duplicate values cannot be stored. It is an interface which implements the mathematical set. This interface contains the methods inherited from the Collection interface and adds a feature which restricts the insertion of the duplicate elements. There are two interfaces which extend the set implementation namely SortedSet and NavigableSet.

citation: https://www.geeksforgeeks.org/set-in-java/

## Iterator
An Iterator is an object that can be used to loop through collections, like ArrayList and HashSet. It is called an "iterator" because "iterating" is the technical term for looping.

To use an Iterator, you must import it from the java.util package.

citation: https://www.w3schools.com/java/java_iterator.asp

## HashSet

The HashSet class implements the Set interface, backed by a hash table which is actually a HashMap instance. No guarantee is made as to the iteration order of the set which means that the class does not guarantee the constant order of elements over time. This class permits the null element. The class also offers constant time performance for the basic operations like add, remove, contains and size assuming the hash function disperses the elements properly among the buckets, which we shall see further in the article.

citation: https://www.geeksforgeeks.org/hashset-in-java/
