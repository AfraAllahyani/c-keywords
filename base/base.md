# Base
###  he  `base`  keyword is used to access members of the base class from within a derived class:

-   Call a method on the base class that has been overridden by another method.
    
-   Specify which base-class constructor should be called when creating instances of the derived class.

A base class access is permitted only in a constructor, an instance method, or an instance property accessor.

### For example:

`public  class  DerivedClass : BaseClass { // This constructor will call BaseClass.BaseClass()  public DerivedClass() : base() { }`