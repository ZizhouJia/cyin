# cyin
cyin programing language is a python like compiling language. It's like the python with datatype and uses the arc to do the grabage collection. It is very simple and have the same performance as the C++.  
Here cyin just in design stage. Future it will be developed.
# The key features of the cyin
The cyin support five basic types: pointer, value type, reference counter, any type and remote type.  
Difference with the value type as the default type like C++, the cyin use the reference counter as the default type like the swift. the cyin has the strict constrain for using the pointer. the reference counter and the constrain for pointer make the memory safety and easy to write the code.  
arc: a=People() #object managed with the arc.  
value type: a=%People() #object created in stack.
pointer: a=unsafe_new %Poeple() #object created in heap.  
any: a=any(People()) #a is a dynamic object.  
remote: a=remote(People()) #a is in remote.  




