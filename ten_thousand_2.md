# Python Scopes

## Understanding Scope

- There are two main types of scopes.

### 1. Global Scope

- It is the top scope in Python. This scope would contain the values defined in the top level of the program.

- The program's main script is automatically in global scope and turns into a module called __main__. the name of this module is the main global scope.
Also, it's the same reason why most of the time it's seen as __name__ = __main__

___

### 2. Local Scope

- The local scope contains the names and values given on a local scale and visible only within that specific function.

___

## nonlocal

- nonlocal names can be accessed from inside the nested functions but can't be modifierd or updated from there.

- if you want to modifiy them. then you need to use a nonlocal staement.

- the nonlocal statements consist of a list of the nonlocal names.
