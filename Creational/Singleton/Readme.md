**Problem Given:**
Suppose you want to create a class for which only a single instance (or object) should be created and that single object can be used by all other classes.

**Solution:**
Singleton design pattern is the best solution of above specific problem. 

Singleton Pattern says that just"define a class that has only one instance and provides a global point of access to it".

In other words, a class must ensure that only single instance should be created and single object can be used by all other classes.

**There are two forms of singleton design pattern**

**Early Instantiation**: creation of instance at load time.

**Lazy Instantiation**: creation of instance when required.

**Advantage of Singleton design pattern**
Saves memory because object is not created at each request. Only single instance is reused again and again.

**Usage of Singleton design pattern**
Singleton pattern is mostly used in multi-threaded and database applications. It is used in logging, caching, thread pools, configuration settings etc.

**How to create Singleton design pattern?**

**Static member**: It gets memory only once because of static, itcontains the instance of the Singleton class.

**Private constructor**: It will prevent to instantiate the Singleton class from outside the class.

**Static factory method**: This provides the global point of access to the Singleton object and returns the instance to the caller.
