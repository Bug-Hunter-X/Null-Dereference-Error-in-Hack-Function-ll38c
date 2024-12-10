# Hack Null Dereference Bug

This repository demonstrates a common error in Hack: attempting to perform an arithmetic operation on a nullable integer without proper null checking.

The `foo` function takes a nullable integer (`?int`) as input.  If `x` is null, adding 1 to it will result in a runtime error.

The solution shows how to safely handle the null case using either null coalescing or an explicit check.