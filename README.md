# Experiment - 4 

-> Introduction (Set & Frozenset in Python):

A set in Python is an unordered collection of unique elements. Sets are used to store multiple items in a single variable and are especially useful when duplicate values are not allowed. Python also provides frozenset, which is an immutable version of a set where elements cannot be added or removed after creation.

-> Theory (Brief Points):

-Sets are created using curly braces {}.

-Sets do not allow duplicate elements.

-Sets are unordered, so the output order may change.

-The values True and 1 are treated as the same element in a set.

-Membership can be checked using the in keyword.

-Once a set is created, existing elements cannot be replaced, but new elements can be added.

-Elements can be removed using methods like remove().

-A frozenset is an immutable set, meaning its elements cannot be modified.

-Frozensets are useful when a fixed collection of unique elements is required.

-> Algorithm: Set Operations in Python

-Step 1: Start the program.
-Step 2: Create two sets A and B with given elements.
-Step 3: Perform Union operation using A | B to get all unique elements from both sets.
-Step 4: Perform Intersection operation using A & B to get common elements between the sets.
-Step 5: Perform Difference (A − B) using A - B to get elements present in A but not in B.
-Step 6: Perform Difference (B − A) using B - A to get elements present in B but not in A.
-Step 7: Perform Symmetric Difference using A ^ B to get elements present in either A or B but not in both.
-Step 8: Display the results of all set operations.
-Step 9: Stop the program.

