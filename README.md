# HashTableReading

The Hashtable class implements a hash table, which maps keys to values. Any non-null object can be used as a key or as a value. To successfully store and retrieve objects from a hashtable, the objects used as keys must implement the hashCode method and the equals method.  

When the hash function generates the same index for multiple keys, there will be a conflict. It's called a hash collision.

### Using the Object Data Type
The simplest implementation is using the Object data type. This is because all non-scalar objects in JavaScript behave as associative arrays, a mapping from property keys to values. So an Object itself can behave as a basic hash table.

### Using a Map Object

The Map object was created to implement this type of associative array without some of the downsides of using a basic Object:

There are no pre-existing keys that could result in a collision
- A Map object has a size property to track its contents.
- A Map object can have keys that are any data type.
- A Map has been optimized for repeated addition and insertion of key-value pairs.

### Applications of Hash Table

Hash tables are implemented where

- constant time lookup and insertion is required
- cryptographic applications
- indexing data is required

### Good Hash Functions

A good hash function may not prevent the collisions completely however it can reduce the number of collisions.

- Division Method
- Multiplication Method
- Universal Hashing
