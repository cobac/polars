# Basic operators

This section describes how to use basic operators (e.g. addition, subtraction) in conjunction with Expressions. We will provide various examples using different themes in the context of the following dataframe.

!!! note Operator Overloading

    In Rust and Python it is possible to use operators directly (e.g. `+ - * / < >`), as both languages allow operator overloading. For instance, using the `+` operator is equivalent to using to the `.add()` method.

{{code_block('user-guide/expressions/operators','dataframe',['DataFrame'])}}

```python exec="on" result="text" session="user-guide/operators"
--8<-- "python/user-guide/expressions/operators.py:setup"
--8<-- "python/user-guide/expressions/operators.py:dataframe"
```

### Numerical

{{code_block('user-guide/expressions/operators','numerical',['operators'])}}

```python exec="on" result="text" session="user-guide/operators"
--8<-- "python/user-guide/expressions/operators.py:numerical"
```

### Logical

{{code_block('user-guide/expressions/operators','logical',['operators'])}}

```python exec="on" result="text" session="user-guide/operators"
--8<-- "python/user-guide/expressions/operators.py:logical"
```
