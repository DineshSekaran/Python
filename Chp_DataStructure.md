# Data Structure

data structures such as tuples, lists, dictionaries, and sets

variable, data structures are alsoused to store a value and collection of various formats.

data structures are divided into array, list and file and to store complex data.

data structures store sequences of objects (floats, integers, strings, etc.).

# Array
Array as a container that can hold a fixed number of data values of the same type.

An Array consist of Element and Index

Array Import

Accessing Array Element

Updating and Removing Array Element 

Array opeartion have reverse,append,pop

# Tuples

hold multiple values within them separated by commas.

allows storing values of different types together. Tuples are immutable.

sequence of elements that are accessed via unpacking or indexing

It is a datatype, creating tuple using () and without () like 1,2,3.

Accessing tuple elements

Concatenating Tuples

Creating tuples with different data types.

tupl = (1, 'a', 2.5)

Tuple methods--> index and count

# Lists

Holds an ordered collections of items.store a sequence of items in a list.

placing all items within square brackets [] separated by comma

Store different data types.

lists are mutable.

## append(element) method adds a single element to the end of the list.
It does not return the new list, just modifies the original list.

It will add as new element
## extend(list2) method adds the elements in list2 to the end of the
list.

## List Manipulation

Insert

Remove

pop

count

index

sort

reverse

it will extend in existing list


# Stacks and Queues
LIFO      FIFO

To add an item to the top of the stack, we use the append()

to retrieve an item from the top of the stack, we use the pop()

stack = [1, 5, 6]


# Import 'deque' module from the 'collections' package

Append LIFO (Last In First out)

POP FIFO (First in First out)


# Dictionaries

A dictionary can be created either using the curly brackets {} or the method dict().

unordered collection of items. It stores data in key-value pairs

e.g dictionary = {key1 : value1, key2 : value2, key3 : value3}

 Values of a dictionary can be either mutable or immutable objects. Dictionaries that we create are instances 
 of the dict class and they are unordered.
 
 Creating and accessing dictionaries
 
 ## Dictionary Methods
 len
 
 del,copy,clear

 items,keys,values
 
 update
 
 # Sets
 
   A set is an unordered and unindexed collection of items. It is a collection data type which is mutable, iterable and contains no duplicate values.
   
   Add,Remove,Update,len,discard,clear,len 
   
   
  ## Methods
  
  union,Intersection,difference,issubset etc
 
## Set Methods Boolean

issubset()
isdisjoint()
issuperset()
