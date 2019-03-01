Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?
   O(n) - Because it traverses every node in the tree.

2. What is the space complexity of your `depth_first_for_each` function?
   O(1) - Nothing is added.

3. What is the runtime complexity of your `breadth_first_for_each` method?
   O(n) - It traverses every node.

4. What is the space complexity of your `breadth_first_for_each` method?
   O(n) - Nodes get added to the queue.

5) What is the runtime complexity of the provided code in `names.py`?
   O(n^4) - Due to there being 4 nested loops, multiplied by each nested loop.

6) What is the space complexity of the provided code in `names.py`?
   O(n) - Size grows with the amount of inputs (n).

7) What is the runtime complexity of your optimized code in `names.py`?
   O(1) - Used python's `set`, which has on average runtime complexity of O(1) and worse case of O(n). It uses hash tables.

8) What is the space complexity of your optimized code in `names.py`?
   O(n) - The dictionary is used as a hash table, which goes up in space by the amount of keys and elements (n).
