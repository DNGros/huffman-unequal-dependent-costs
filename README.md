Huffman Unequal Dependent Costs [in progress]
========
This reposity will attempt build off of Simon Lydell (@lydell) CoffeeScript/JS[n-ary huffman tree implementation](https://github.com/lydell/n-ary-huffman) with an algorithm that accomodates for more complex cases of a huffman coding. Specically it is the case where letter costs are unequal and depend on the previous node in the tree. The goal is not necessarily a completely optimal solution, but instead a "sufficiently good" solution that can run very quickly with a sizable number of leaves (> 100) and a full alphabet of conditional weighted letters (at least 26).
