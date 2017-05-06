# syntax

# Definitions
**modifier** - reserved keywords that follow the "dot" notation after an object or variable

**conditionally supported** - program construct that is not required by the language and its implementation is platform agnostic.
# Value Types
## Primitive Types
### Booleans

`.bool` is a type that denote true or false, but not both at the same time.

Booleans can be assigned the values of true, false, 0, or any non zero number. 
### Integers

`.int8` is used for 8 bits of storage

`.int16` is used for 16 bits of storage

`.int32` is used for 32 bits of storage

`.int64` is used for 64 bits of storage.

Integer size is *conditionally supported*. Compilers will throw *Error:1* when the user trys to use a value that exceeds the specified targets register size.

The term *integer* will refer to all `.int#` modifiers.

All integers will follow the rules and syntax listed in this document regardless of its register size.
### Floating Point
### Characters
### Strings
### Pointers
### Auto
## Composite Types
### Enumerations
### Union
### Arrays
### Lists
Lists are a collection of integral types of differing kinds within the same object.

Lists are static by default. This can be changed using `.list.static = false`.

`.dylist` which stands for "dynamic list", is a list which can grow in size at run time.

### Vectors
### Class
## Variables
### Naming Conventions

