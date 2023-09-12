# Read Class 30: Hash Tables

## What is a Hashtable?
Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Terminology:
Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array. Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs. Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

Used For
Hold unique values
Dictionary
Library

## Internal Methods
```
Add()

Find()

Contains()

GetHash()
```
## Collision resolution techniques

1. Separate Chaining (Open Hashing):

* Uses linked lists to handle collisions.
* Each element in the hash table is a linked list.
* New elements with the same hash index are inserted into the corresponding linked list.

2. Linear Probing (Open Addressing or Closed Hashing):

* Stores all entry records directly in the array itself.
* When a collision occurs, it linearly probes through the array to find the next available slot.

3. Quadratic Probing:

* Similar to linear probing but uses a quadratic function to determine the interval between successive probes.
* Helps reduce clustering compared to linear probing.

4. Double Hashing:

* Uses two hash functions to compute the interval between successive probes.
* Combines the benefits of open addressing with improved key distribution.
