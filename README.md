![Logo](https://upload.wikimedia.org/wikipedia/commons/c/cd/Boost.png)

## Boost 1.31 fix for tokenizer.hpp

```
Compilation errors:
boost_1_31_0\boost\mpl\apply.hpp:163: error: missing binary operator before token "(" #elif BOOST_PP_ITERATION_DEPTH() == 1
boost_1_31_0\boost\mpl\apply.hpp:334: error: missing binary operator before token "(" #elif BOOST_PP_ITERATION_DEPTH() == 2
```

* Make changes in `\boost\mpl\apply.hpp` from above `apply--fix.hpp`.

* For more detail answer see `pdf` from the repository.
