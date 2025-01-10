This repository demonstrates an uncommon bug in Lua related to the `pairs` iterator and recursive table traversal. The bug occurs when a table is modified during iteration using `pairs`, potentially leading to elements being skipped. The `bug.lua` file contains the problematic code, while `bugSolution.lua` provides a corrected version using a safer iteration technique.