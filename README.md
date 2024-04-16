
In Python 3.6 and earlier, dictionaries are unordered. This means that the order of the items in a dictionary is not guaranteed. When you iterate over a dictionary, the items will be returned in an arbitrary order.
In Python 3.7 and later, dictionaries are ordered. This means that the order of the items in a dictionary is guaranteed to be the same as the order in which they were added to the dictionary.
If you need to create an ordered dictionary in Python 3.6 or earlier, you can use the collections.OrderedDict class. This class provides all of the same methods as the regular dict class, but it also guarantees that the order of the items will be preserved.
