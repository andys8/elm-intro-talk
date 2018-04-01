# Elm

![Elm Logo](assets/elm-logo.png)

+++

## A delightful language for reliable webapps

Generate JavaScript with great **performance** and **no runtime exceptions**.

+++

**Functional** and **statically typed**

+++

Compiles to

![Javascript](assets/javascript.png)

Note:
* Webpack and JS build steps can be used
* Javascript integration

+++

## Compile time static type checks

```elm
result =
    1 + 2 + "three"
```

+++

```shell
TYPE MISMATCH

The right side of (+) is causing a type mismatch.

(+) is expecting the right side to be a:
number

But the right side is:
String

Hint: To append strings in Elm, you need to use the (++) operator, not (+). http://package.elm-lang.org/packages/elm-lang/core/latest/Basics#++

Hint: With operators like (+) I always check the left side first. If it seems fine, I assume it is correct and check the right side. So the problem may be in how the left and right arguments interact.
```
