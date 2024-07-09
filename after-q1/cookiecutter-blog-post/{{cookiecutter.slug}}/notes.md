# Notes - {{cookiecutter.title}}

"canonical" members

## How is it Implemented?

> Even though we can use class syntax to create Enums, Enums are not normal Python classes.

https://docs.python.org/3/library/enum.html

### Relevant Modules, Classes, Functions

* `enum`: The module of the Python Standard Library.
* `EnumType`: The metaclass. It can be subclassed.
* `Enum`: Base class.

## Terminology

* An `Enum` has members.
* `Enum` members have `name` and `value`.

## Sources

Reference docs

{{cookiecutter.reference_docs}}

HOWTO docs

{{cookiecutter.howto_docs}}

Example with string name as alias

https://www.notinventedhere.org/articles/python/how-to-use-strings-as-name-aliases-in-python-enums.html
