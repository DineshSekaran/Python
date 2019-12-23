# Iterators

Its primary purpose is to return all of its elements.

__iter__() method which returns the iterator object itself and is used while using the for and in keywords.

 __next__() method returns the next value. It also returns StopIteration error once all the objects have been traversed.
 
 Iterables
When you create a list, you can read its items one by one, and it’s called iteration:

>>> mylist = [1, 2, 3]
>>> for i in mylist:
...    print(i)
1
2
3
 
 # enumerate() function
 
 enumerate object which consists of pairs containing an element of an original iterable along with their index


Iterators:

that an iterator object can be used only once. It means once we have traversed through all elements of an iterator, and it has raised
StopIteration, it will keep raising the same exception. So, if we run the above for loop again, Python will not provide us with any output. Internally it will keep raising the StopIteration error. This can be verified using the next() method.


# Generators

generator gives us an easier way to create iterators

Generators
Generators are iterators, but you can only iterate over them once. It’s because they do not store all the values in memory, they generate the values on the fly:

>>> mygenerator = (x*x for x in range(3))
>>> for i in mygenerator:
...    print(i)
0
1
4

# Yield 
Yield is a keyword that is used like return, except the function will return a generator.

>>> def createGenerator():
...    mylist = range(3)
...    for i in mylist:
...        yield i*i
...
>>> mygenerator = createGenerator() # create a generator
>>> print(mygenerator) # mygenerator is an object!
<generator object createGenerator at 0xb7555c34>
>>> for i in mygenerator:
...     print(i)
0
1
4
