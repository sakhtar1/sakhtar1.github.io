---
layout: post
title:      "Object Instantiation"
date:       2018-02-28 23:28:30 -0500
permalink:  object_instantiation
---


Instantiation is creating an instance of a class. Once an instance of a class is created we call that instance an object. Objects are instantiated by using the class name, then a dot, then the word new.  In general, this usually means allocating memory for the new object and calling the constructor. 

For instance let's say we have the following:
```

**class Book
end**
```

We can instantiate this class, and create an actual, real book instance (object) from it:

*`*Book.new **`


As one can see, whenever you call the method new on a class, as in Book.new, the class will create a new instance of itself. 

Let's break it down a bit further. What is .new?

.new is a ruby class method that:

(1) allocates space for the object 
(2)Assigns instance variables their intial values
(3)Returns the instance of that class.

Thus, .new is called the constructor. 

To simply put, the phrase "instantiating a class" means the same thing as "creating an object." When you create an object, you are creating an "instance" of a class, therefore "instantiating" a class. 
When we create a new instance of a class by the way of calling the method new on that class, we also say that we “instantiate” that object: By calling Book.new we instantiate a new book object.

Let's take it a step further.

```
**class Books
  def initialize(title)
  end
end**
```

Internally the method initialize will be called on the new object from Book.new. Therefore, the arguments that will be passed to new will be passed on to the initialize method. Initialize is an instance method that is used to assign instance variables.

`**Book.new("Charlotte's Web")**`

When we call new on the class Book, and pass the string "Charlotte's Web" , the method new will create a new instance of the class, and call initialize on it, passing "Charlotte's Web" string on it as well. "Charlotte's Web" string will therefore be assigned to the variable title. 






