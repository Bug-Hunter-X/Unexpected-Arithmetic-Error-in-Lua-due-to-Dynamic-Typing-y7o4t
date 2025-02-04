# Lua Dynamic Typing Bug

This repository demonstrates a common error in Lua programming that arises from its dynamic typing system.  The bug showcases how performing arithmetic operations on incompatible types (e.g., adding a number to a string) leads to runtime errors. The solution provides a way to handle such errors using type checking.

## Bug Description

In Lua, the `+` operator can be used for both numeric addition and string concatenation. If the operands are not of the same type, this can result in unexpected behavior.  The code in `bug.lua` illustrates this by attempting to add a number to a string, causing an error.

## Solution

The `bugSolution.lua` file shows a solution that involves explicitly checking the type of variables before performing arithmetic operations. This makes the code more robust and prevents unexpected runtime errors.