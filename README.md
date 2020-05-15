# Bit Field Enum Class

A single header to provide bitwise operators for `enum class` types.

The code is derived from the [Using Enum Classes as Bitfields](https://www.justsoftwaresolutions.co.uk/cplusplus/using-enum-classes-as-bitfields.html) article by Anthony Williams.

I also found this [article](http://blog.bitwigglers.org/using-enum-classes-as-type-safe-bitmasks/) by Andre Haupt useful when reading about the subject.

## Usage

One difference between this derivative and the original is that the operators are in a namespace (`bec`).

To use them they must be brought into scope with a `using` declaration.

e.g.

```c++
using bec::operator&;
```
