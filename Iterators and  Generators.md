# Iterators

Its primary purpose is to return all of its elements.

__iter__() method which returns the iterator object itself and is used while using the for and in keywords.

 __next__() method returns the next value. It also returns StopIteration error once all the objects have been traversed.
 
 # enumerate() function
 
 enumerate object which consists of pairs containing an element of an original iterable along with their index


Iterators:

that an iterator object can be used only once. It means once we have traversed through all elements of an iterator, and it has raised
StopIteration, it will keep raising the same exception. So, if we run the above for loop again, Python will not provide us with any output. Internally it will keep raising the StopIteration error. This can be verified using the next() method.


# Generators

generator gives us an easier way to create iterators
