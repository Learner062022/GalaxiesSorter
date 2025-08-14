# GalaxiesSorter


## Person 1: Algorithm Lead

- Time allocated: 30-45 minutes

- Focus: Implementing sorting algorithms and writing core loops

**Deliverables:**

- ``` yml
  my_mutating_sort(items)
  ```
  function in `sorting.py` (in-place sort)
  
- `my_immutable_sort(items)` function in `sorting.py` (returns new sorted sequence)
  
- `galaxy_sorting_method(galaxies)` function in `sorting.py` (returns galaxies in the required order)
    
**Responsibilities:**

- Choose algorithms for sorting

- Write core loops for sorting

- Ensure correct implementation and testing of sorting functions

## Person 2: Comparator Owner

- Focus: Implementing Galaxy dunder methods

**Deliverables:**

- `Galaxy` class in `galaxy.py` with comparison dunders (`__eq__`, `__lt__`, etc.) and `__hash__ __repr__/__str__` method for `Galaxy` class
- 
**Responsibilities:**
  
- Design and implement Galaxy dunder methods

- Ensure correct implementation and testing of Galaxy class

### Shared responsibilities

- Both persons will work together to ensure that the sorting functions are correctly implemented and tested.

- They will also work together to write unit tests in tests/test_sorting.py to cover ordering, in-place vs immutable behavior, and correctness on small and medium datasets.

### Additional tasks

- The Coordinator/Writer (not assigned to a person yet) will:
  - Keep track of time and record decisions
  - Write the final README with chosen algorithms, complexity, stability, and contributions from each member
