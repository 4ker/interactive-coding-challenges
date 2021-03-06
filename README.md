使用方法:

0. 安装依赖: pip3 install -r requirements.txt
1. 在本文件夹 `jupyter notebook`
2. 打开 README.ipython
3. 点击相应 challenge 和 solution 进入

## Index

### Challenges Categories

**Format**: Challenge Category - Number of Challenges

* [Arrays and Strings](#arrays-and-strings) - 10
* [Linked Lists](#linked-lists) - 8
* [Stacks and Queues](#stacks-and-queues) - 8
* [Graphs and Trees](#graphs-and-trees) - 21
* [Sorting](#sorting) - 10
* [Recursion and Dynamic Programming](#recursion-and-dynamic-programming) - 17
* [Mathematics and Probability](#mathematics-and-probability) - 6
* [Bit Manipulation](#bit-manipulation) - 8
* [Online Judges](#online-judges) - 16
* [System Design](https://github.com/donnemartin/system-design-primer#system-design-interview-questions-with-solutions) - 8
* [Object Oriented Design](https://github.com/donnemartin/system-design-primer#object-oriented-design-interview-questions-with-solutions) - 8

**Total number of challenges: 120**

### Reference Implementations: Data Structures

Unit tested, fully functional implementations of the following data structures:

* [Linked List](linked_lists/linked_list/linked_list_solution.ipynb)
* [Stack](stacks_queues/stack/stack_solution.ipynb)
* [Queue](stacks_queues/queue_list/queue_list_solution.ipynb)
* [Binary Search Tree](graphs_trees/bst/bst_solution.ipynb)
* [Graph](graphs_trees/graph/graph_solution.ipynb)
* [Min Heap](graphs_trees/min_heap/min_heap_solution.ipynb)
* [Trie](graphs_trees/trie/trie_solution.ipynb)
* [Priority Queue](arrays_strings/priority_queue/priority_queue_solution.ipynb)
* [Hash Map](arrays_strings/hash_map/hash_map_solution.ipynb)

### Reference Implementations: Algorithms

Unit tested, fully functional implementations of the following algorithms:

* [Selection Sort](sorting_searching/selection_sort/selection_sort_solution.ipynb)
* [Insertion Sort](sorting_searching/insertion_sort/insertion_sort_solution.ipynb)
* [Quick Sort](sorting_searching/quick_sort/quick_sort_solution.ipynb)
* [Merge Sort](sorting_searching/merge_sort/merge_sort_solution.ipynb)
* [Radix Sort](sorting_searching/radix_sort/radix_sort_solution.ipynb)
* [Topological Sort](graphs_trees/graph_build_order/build_order_solution.ipynb)
* [Tree Depth-First Search (Pre-, In-, Post-Order)](graphs_trees/tree_dfs/dfs_solution.ipynb)
* [Tree Breadth-First Search](graphs_trees/tree_bfs/bfs_solution.ipynb)
* [Graph Depth-First Search](graphs_trees/graph_dfs/dfs_solution.ipynb)
* [Graph Breadth-First Search](graphs_trees/graph_bfs/bfs_solution.ipynb)
* [Dijkstra's Shortest Path](graphs_trees/graph_shortest_path/graph_shortest_path_solution.ipynb)
* [Unweighted Graph Shortest Path](graphs_trees/graph_shortest_path_unweighted/shortest_path_solution.ipynb)
* [Knapsack 0/1](recursion_dynamic/knapsack_01/knapsack_solution.ipynb)
* [Knapsack Unbounded](recursion_dynamic/knapsack_unbounded/knapsack_unbounded_solution.ipynb)
* [Sieve of Eratosthenes](math_probability/generate_primes/check_prime_solution.ipynb)

### Reference Implementations: TODO

* [A*](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Bellman-Ford](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Bloom Filter](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Convex Hull](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Fisher-Yates Shuffle](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Kruskal's](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Max Flow](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Prim's](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Rabin-Karp](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Traveling Salesman](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Union Find](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)

### Installing and Running Challenges

* [Repo Structure](#repo-structure)
* [Notebook Installation](#notebook-installation)
    * [Nose Installation](#nose-installation)
* [Running Challenges](#running-challenges)

### Misc

* [Contributing](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)
* [Credits](#credits)
* [Contact Info](#contact-info)
* [License](#license)

## Challenges

[Image Credits](#credits)

<br/>
<p>
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/arrays_nltk.png">
</p>
<br/>

### Arrays and Strings

| Challenge | Static Notebook |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| DONE - Determine if a string contains unique characters | [Challenge](arrays_strings/unique_chars/unique_chars_challenge.ipynb)│[Solution](arrays_strings/unique_chars/unique_chars_solution.ipynb) |
| DONE - Determine if a string is a permutation of another | [Challenge](arrays_strings/permutation/permutation_challenge.ipynb)│[Solution](arrays_strings/permutation/permutation_solution.ipynb) |
| DONE - Determine if a string is a rotation of another | [Challenge](arrays_strings/rotation/rotation_challenge.ipynb)│[Solution](arrays_strings/rotation/rotation_solution.ipynb) |
| DONE - Compress a string | [Challenge](arrays_strings/compress/compress_challenge.ipynb)│[Solution](arrays_strings/compress/compress_solution.ipynb) |
| Reverse characters in a string | [Challenge](arrays_strings/reverse_string/reverse_string_challenge.ipynb)│[Solution](arrays_strings/reverse_string/reverse_string_solution.ipynb) |
| Given two strings, find the single different char | [Challenge](arrays_strings/str_diff/str_diff_challenge.ipynb)│[Solution](arrays_strings/str_diff/str_diff_solution.ipynb) |
| Find two indices that sum to a specific value | [Challenge](arrays_strings/two_sum/two_sum_challenge.ipynb)│[Solution](arrays_strings/two_sum/two_sum_solution.ipynb) |
| Implement a hash table | [Challenge](arrays_strings/hash_map/hash_map_challenge.ipynb)│[Solution](arrays_strings/hash_map/hash_map_solution.ipynb) |
| Implement fizz buzz | [Challenge](arrays_strings/fizz_buzz/fizz_buzz_challenge.ipynb)│[Solution](arrays_strings/fizz_buzz/fizz_buzz_solution.ipynb) |
| Find the first non-repeated character in a string | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Remove specified characters in a string | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Reverse words in a string | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Convert a string to an integer | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Convert an integer to a string | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/linked_lists_wikipedia.png">
</p>
<br/>

### Linked Lists

| Challenge | Static Notebook |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| DONE - Remove duplicates from a linked list | [Challenge](linked_lists/remove_duplicates/remove_duplicates_challenge.ipynb)│[Solution](linked_lists/remove_duplicates/remove_duplicates_solution.ipynb) |
| DONE - Find the kth to last element of a linked list | [Challenge](linked_lists/kth_to_last_elem/kth_to_last_elem_challenge.ipynb)│[Solution](linked_lists/kth_to_last_elem/kth_to_last_elem_solution.ipynb) |
| Delete a node in the middle of a linked list | [Challenge](linked_lists/delete_mid/delete_mid_challenge.ipynb)│[Solution](linked_lists/delete_mid/delete_mid_solution.ipynb) |
| Partition a linked list around a given value | [Challenge](linked_lists/partition/partition_challenge.ipynb)│[Solution](linked_lists/partition/partition_solution.ipynb) |
| Add two numbers whose digits are stored in a linked list | [Challenge](linked_lists/add_reverse/add_reverse_challenge.ipynb)│[Solution](linked_lists/add_reverse/add_reverse_solution.ipynb) |
| Find the start of a linked list loop | [Challenge](http://nbviewer.jupyter.org/github/donnemartin/interactive-coding-challenges/blob/master/linked_lists/find_loop_start/find_loop_start_challenge.ipynb)│[Solution](linked_lists/find_loop_start/find_loop_start_solution.ipynb) |
| Determine if a linked list is a palindrome | [Challenge](linked_lists/palindrome/palindrome_challenge.ipynb)│[Solution](linked_lists/palindrome/palindrome_solution.ipynb) |
| Implement a linked list | [Challenge](linked_lists/linked_list/linked_list_challenge.ipynb)│[Solution](linked_lists/linked_list/linked_list_solution.ipynb) |
| Determine if a list is cyclic or acyclic | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/stack_queue_wikipedia.png">
</p>
<br/>

### Stacks and Queues

| Challenge | Static Notebook |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Implement n stacks using a single array | [Challenge](stacks_queues/n_stacks/n_stacks_challenge.ipynb)│[Solution](stacks_queues/n_stacks/n_stacks_solution.ipynb) |
| Implement a stack that keeps track of its minimum element | [Challenge](stacks_queues/stack_min/stack_min_challenge.ipynb)│[Solution](stacks_queues/stack_min/stack_min_solution.ipynb) |
| Implement a set of stacks class that wraps a list of capacity-bounded stacks | [Challenge]()│[Solution](stacks_queues/set_of_stacks/set_of_stacks_solution.ipynb) |
| Implement a queue using two stacks | [Challenge](stacks_queues/queue_from_stacks/queue_from_stacks_challenge.ipynb)│[Solution](stacks_queues/queue_from_stacks/queue_from_stacks_solution.ipynb) |
| Sort a stack using another stack as a buffer | [Challenge](stacks_queues/sort_stack/sort_stack_challenge.ipynb)│[Solution](stacks_queues/sort_stack/sort_stack_solution.ipynb) |
| Implement a stack | [Challenge](stacks_queues/stack/stack_challenge.ipynb)│[Solution](stacks_queues/stack/stack_solution.ipynb) |
| Implement a queue | [Challenge](stacks_queues/queue_list/queue_list_challenge.ipynb)│[Solution](stacks_queues/queue_list/queue_list_solution.ipynb) |
| Implement a priority queue backed by an array | [Challenge](arrays_strings/priority_queue/priority_queue_challenge.ipynb)│[Solution](arrays_strings/priority_queue/priority_queue_solution.ipynb) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/binary_tree_wikipedia.png">
</p>
<br/>

### Graphs and Trees

| Challenge | Static Notebooks |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Implement depth-first search (pre-, in-, post-order) on a tree |  [Challenge](graphs_trees/tree_dfs/dfs_challenge.ipynb)│[Solution](graphs_trees/tree_dfs/dfs_solution.ipynb) |
| Implement breadth-first search on a tree | [Challenge](graphs_trees/tree_bfs/bfs_challenge.ipynb)│[Solution](graphs_trees/tree_bfs/bfs_solution.ipynb) |
| Determine the height of a tree | [Challenge](graphs_trees/tree_height/height_challenge.ipynb)│[Solution](graphs_trees/tree_height/height_solution.ipynb) |
| Create a binary search tree with minimal height from a sorted array | [Challenge](graphs_trees/bst_min/bst_min_challenge.ipynb)│[Solution](graphs_trees/bst_min/bst_min_solution.ipynb) |
| Create a linked list for each level of a binary tree | [Challenge](graphs_trees/tree_level_lists/tree_level_lists_challenge.ipynb)│[Solution](graphs_trees/tree_level_lists/tree_level_lists_solution.ipynb) |
| Check if a binary tree is balanced | [Challenge](graphs_trees/check_balance/check_balance_challenge.ipynb)│[Solution](graphs_trees/check_balance/check_balance_solution.ipynb) |
| Determine if a tree is a valid binary search tree | [Challenge](graphs_trees/bst_validate/bst_validate_challenge.ipynb)│[Solution](graphs_trees/bst_validate/bst_validate_solution.ipynb) |
| Find the in-order successor of a given node in a binary search tree | [Challenge](graphs_trees/bst_successor/bst_successor_challenge.ipynb)│[Solution](graphs_trees/bst_successor/bst_successor_solution.ipynb) |
| Find the second largest node in a binary search tree | [Challenge](graphs_trees/bst_second_largest/bst_second_largest_challenge.ipynb)│[Solution](graphs_trees/bst_second_largest/bst_second_largest_solution.ipynb) |
| Find the lowest common ancestor | [Challenge](graphs_trees/tree_lca/tree_lca_challenge.ipynb)│[Solution](graphs_trees/tree_lca/tree_lca_solution.ipynb) |
| Invert a binary tree | [Challenge](graphs_trees/invert_tree/invert_tree_challenge.ipynb)│[Solution](graphs_trees/invert_tree/invert_tree_solution.ipynb) |
| Implement a binary search tree | [Challenge](graphs_trees/bst/bst_challenge.ipynb)│[Solution](graphs_trees/bst/bst_solution.ipynb) |
| Implement a min heap | [Challenge](graphs_trees/min_heap/min_heap_challenge.ipynb)│[Solution](graphs_trees/min_heap/min_heap_solution.ipynb) |
| Implement a trie | [Challenge](graphs_trees/trie/trie_challenge.ipynb)│[Solution](graphs_trees/trie/trie_solution.ipynb) |
| Implement depth-first search on a graph |  [Challenge](graphs_trees/graph_dfs/dfs_challenge.ipynb)│[Solution](graphs_trees/graph_dfs/dfs_solution.ipynb) |
| Implement breadth-first search on a graph | [Challenge](graphs_trees/graph_bfs/bfs_challenge.ipynb)│[Solution](graphs_trees/graph_bfs/bfs_solution.ipynb) |
| Determine if there is a path between two nodes in a graph | [Challenge](graphs_trees/graph_path_exists/path_exists_challenge.ipynb)│[Solution](graphs_trees/graph_path_exists/path_exists_solution.ipynb) |
| Implement a graph | [Challenge](graphs_trees/graph/graph_challenge.ipynb)│[Solution](graphs_trees/graph/graph_solution.ipynb) |
| Find a build order given a list of projects and dependencies. |  [Challenge](graphs_trees/graph_build_order/build_order_challenge.ipynb)│[Solution](graphs_trees/graph_build_order/build_order_solution.ipynb) |
| Find the shortest path in a weighted graph. |  [Challenge](graphs_trees/graph_shortest_path/graph_shortest_path_challenge.ipynb)│[Solution](graphs_trees/graph_shortest_path/graph_shortest_path_solution.ipynb) |
| Find the shortest path in an unweighted graph. |  [Challenge](graphs_trees/graph_shortest_path_unweighted/shortest_path_challenge.ipynb)│[Solution](graphs_trees/graph_shortest_path_unweighted/shortest_path_solution.ipynb) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif">
</p>
<br/>

### Sorting

| Challenge | Static Notebooks |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Implement selection sort | [Challenge](sorting_searching/selection_sort/selection_sort_challenge.ipynb)│[Solution](sorting_searching/selection_sort/selection_sort_solution.ipynb) |
| Implement insertion sort | [Challenge](sorting_searching/insertion_sort/insertion_sort_challenge.ipynb)│[Solution](sorting_searching/insertion_sort/insertion_sort_solution.ipynb) |
| Implement quick sort | [Challenge](sorting_searching/quick_sort/quick_sort_challenge.ipynb)│[Solution](sorting_searching/quick_sort/quick_sort_solution.ipynb) |
| Implement merge sort | [Challenge](sorting_searching/merge_sort/merge_sort_challenge.ipynb)│[Solution](sorting_searching/merge_sort/merge_sort_solution.ipynb) |
| Implement radix sort | [Challenge](sorting_searching/radix_sort/radix_sort_challenge.ipynb)│[Solution](sorting_searching/radix_sort/radix_sort_solution.ipynb) |
| Sort an array of strings so all anagrams are next to each other | [Challenge](sorting_searching/anagrams/anagrams_challenge.ipynb)│[Solution](sorting_searching/anagrams/anagrams_solution.ipynb) |
| Find an item in a sorted, rotated array | [Challenge](sorting_searching/rotated_array_search/rotated_array_search_challenge.ipynb)│[Solution](sorting_searching/rotated_array_search/rotated_array_search_solution.ipynb) |
| Search a sorted matrix for an item | [Challenge](sorting_searching/search_sorted_matrix/search_sorted_matrix_challenge.ipynb)│[Solution](sorting_searching/search_sorted_matrix/search_sorted_matrix_solution.ipynb) |
| Find an int not in an input of n integers | [Challenge](sorting_searching/new_int/new_int_challenge.ipynb)│[Solution](sorting_searching/new_int/new_int_solution.ipynb) |
|  Given sorted arrays A, B, merge B into A in sorted order | [Challenge](sorting_searching/merge_into/merge_into_challenge.ipynb)│[Solution](sorting_searching/merge_into/merge_into_solution.ipynb) |
| Implement a stable selection sort | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Make an unstable sort stable | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Implement an efficient, in-place version of quicksort | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Given two sorted arrays, merge one into the other in sorted order | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Find an element in a rotated and sorted array of integers | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/fibonacci_wikipedia.png">
</p>
<br/>

### Recursion and Dynamic Programming

| Challenge | Static Notebooks |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Implement fibonacci recursively, dynamically, and iteratively | [Challenge](recursion_dynamic/fibonacci/fibonacci_challenge.ipynb)│[Solution](recursion_dynamic/fibonacci/fibonacci_solution.ipynb) |
| Maximize items placed in a knapsack | [Challenge](recursion_dynamic/knapsack_01/knapsack_challenge.ipynb)│[Solution](recursion_dynamic/knapsack_01/knapsack_solution.ipynb) |
| Maximize unbounded items placed in a knapsack | [Challenge](recursion_dynamic/knapsack_unbounded/knapsack_unbounded_challenge.ipynb)│[Solution](recursion_dynamic/knapsack_unbounded/knapsack_unbounded_solution.ipynb) |
| Find the longest common subsequence | [Challenge](recursion_dynamic/longest_common_subsequence/longest_common_subseq_challenge.ipynb)│[Solution](recursion_dynamic/longest_common_subsequence/longest_common_subseq_solution.ipynb) |
| Find the longest increasing subsequence | [Challenge](recursion_dynamic/longest_inc_subseq/longest_inc_subseq_challenge.ipynb)│[Solution](recursion_dynamic/longest_inc_subseq/longest_inc_subseq_solution.ipynb) |
| Minimize the cost of matrix multiplication | [Challenge](recursion_dynamic/matrix_mult/find_min_cost_challenge.ipynb)│[Solution](recursion_dynamic/matrix_mult/find_min_cost_solution.ipynb) |
| Maximize stock prices given k transactions | [Challenge](recursion_dynamic/max_profit_k/max_profit_challenge.ipynb)│[Solution](recursion_dynamic/max_profit_k/max_profit_solution.ipynb) |
| Find the minimum number of ways to represent n cents given an array of coins | [Challenge](recursion_dynamic/coin_change_min/coin_change_min_challenge.ipynb)│[Solution](recursion_dynamic/coin_change_min/coin_change_min_solution.ipynb) |
| Find the unique number of ways to represent n cents given an array of coins | [Challenge](recursion_dynamic/coin_change/coin_change_challenge.ipynb)│[Solution](recursion_dynamic/coin_change/coin_change_solution.ipynb) |
| Print all valid combinations of n-pairs of parentheses | [Challenge](recursion_dynamic/n_pairs_parentheses/n_pairs_parentheses_challenge.ipynb)│[Solution](recursion_dynamic/n_pairs_parentheses/n_pairs_parentheses_solution.ipynb) |
| Navigate a maze | [Challenge](recursion_dynamic/grid_path/grid_path_challenge.ipynb)│[Solution](recursion_dynamic/grid_path/grid_path_solution.ipynb) |
| Print all subsets of a set | [Challenge](recursion_dynamic/power_set/power_set_challenge.ipynb)│[Solution](recursion_dynamic/power_set/power_set_solution.ipynb) |
| Print all permutations of a string | [Challenge](recursion_dynamic/permutations/permutations_challenge.ipynb)│[Solution](recursion_dynamic/permutations/permutations_solution.ipynb) |
| Find the magic index in an array | [Challenge](recursion_dynamic/magic_index/magic_index_challenge.ipynb)│[Solution](recursion_dynamic/magic_index/magic_index_solution.ipynb) |
| Find the number of ways to run up n steps | [Challenge](recursion_dynamic/steps/steps_challenge.ipynb)│[Solution](recursion_dynamic/steps/steps_solution.ipynb) |
| Implement the Towers of Hanoi with 3 towers and N disks | [Challenge](recursion_dynamic/hanoi/hanoi_challenge.ipynb)│[Solution](recursion_dynamic/hanoi/hanoi_solution.ipynb) |
| Implement factorial recursively, dynamically, and iteratively | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Perform a binary search on a sorted array of integers | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Print all combinations of a string | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Implement a paint fill function | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Find all permutations to represent n cents, given 1, 5, 10, 25 cent coins | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/probability_distribution_wikipedia.png">
</p>
<br/>

### Mathematics and Probability

| Challenge | Static Notebooks |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Generate a list of primes | [Challenge](math_probability/generate_primes/check_prime_challenge.ipynb)│[Solution](math_probability/generate_primes/check_prime_solution.ipynb) |
| Find the digital root | [Challenge](math_probability/add_digits/add_digits_challenge.ipynb)│[Solution](math_probability/add_digits/add_digits_solution.ipynb) |
| Create a class supporting insert, max, min, mean, mode in O(1) | [Challenge](math_probability/math_ops/math_ops_challenge.ipynb)│[Solution](math_probability/math_ops/math_ops_solution.ipynb) |
| Determine if a number is a power of two | [Challenge](math_probability/power_two/power_two_challenge.ipynb)│[Solution](math_probability/power_two/power_two_solution.ipynb) |
| Add two numbers without the + or - sign | [Challenge](math_probability/sum_two/sum_two_challenge.ipynb)│[Solution](math_probability/sum_two/sum_two_solution.ipynb) |
| Subtract two numbers without the + or - sign | [Challenge](math_probability/sub_two/sub_two_challenge.ipynb)│[Solution](math_probability/sub_two/sub_two_solution.ipynb) |
| Check if a number is prime | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Determine if two lines on a Cartesian plane intersect | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Using only add, implement multiply, subtract, and divide for ints | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Find the kth number such that the only prime factors are 3, 5, and 7 | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/bit_manipulation_wikipedia.png">
</p>
<br/>

### Bit Manipulation

| Challenge | Static Notebooks |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Implement common bit manipulation operations | [Challenge](bit_manipulation/bit/bit_challenge.ipynb)│[Solution](bit_manipulation/bit/bit_solution.ipynb) |
| Determine number of bits to flip to convert a into b | [Challenge](bit_manipulation/bits_to_flip/bits_to_flip_challenge.ipynb)│[Solution](bit_manipulation/bits_to_flip/bits_to_flip_solution.ipynb) |
| Draw a line on a screen | [Challenge](bit_manipulation/draw_line/draw_line_challenge.ipynb)│[Solution](bit_manipulation/draw_line/draw_line_solution.ipynb) |
| Flip a bit to maximize the longest sequence of 1s | [Challenge](bit_manipulation/flip_bit/flip_bit_challenge.ipynb)│[Solution](bit_manipulation/flip_bit/flip_bit_solution.ipynb) |
| Get the next largest and next smallest numbers | [Challenge](bit_manipulation/get_next/get_next_challenge.ipynb)│[Solution](bit_manipulation/get_next/get_next_solution.ipynb) |
| Merge two binary numbers | [Challenge](bit_manipulation/insert_m_into_n/insert_m_into_n_challenge.ipynb)│[Solution](bit_manipulation/insert_m_into_n/insert_m_into_n_solution.ipynb) |
| Swap odd and even bits in an integer | [Challenge](bit_manipulation/pairwise_swap/pairwise_swap_challenge.ipynb)│[Solution](bit_manipulation/pairwise_swap/pairwise_swap_solution.ipynb) |
| Print the binary representation of a number between 0 and 1 | [Challenge](bit_manipulation/print_binary/print_binary_challenge.ipynb)│[Solution](bit_manipulation/print_binary/print_binary_solution.ipynb) |
| Determine the number of 1s in the binary representation of a given integer | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/interactive-coding-challenges/master/images/logo_topcoder.png">
</p>
<br/>

### Online Judges

| Challenge | Static Notebooks |
|--------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Find the longest substring with at most k distinct chars | [Challenge](online_judges/longest_substr_k_distinct/longest_substr_challenge.ipynb)│[Solution](online_judges/longest_substr_k_distinct/longest_substr_solution.ipynb) |
| Find the highest product of three numbers | [Challenge](online_judges/prod_three/prod_three_challenge.ipynb)│[Solution](online_judges/prod_three/prod_three_solution.ipynb) |
| Maximize stocks profit from 1 buy and 1 sell | [Challenge](online_judges/max_profit/max_profit_challenge.ipynb)│[Solution](online_judges/max_profit/max_profit_solution.ipynb) |
| Move all zeroes in a list to the end | [Challenge](online_judges/move_zeroes/move_zeroes_challenge.ipynb)│[Solution](online_judges/move_zeroes/move_zeroes_solution.ipynb) |
| Find the products of every other int | [Challenge](online_judges/mult_other_numbers/mult_other_numbers_challenge.ipynb)│[Solution](online_judges/mult_other_numbers/mult_other_numbers_solution.ipynb) |
| Given a list of entries and exits, find the busiest period | [Challenge](online_judges/busiest_period/busiest_period_challenge.ipynb)│[Solution](online_judges/busiest_period/busiest_period_solution.ipynb) |
| Determine an island's perimeter | [Challenge](online_judges/island_perimeter/island_perimeter_challenge.ipynb)│[Solution](online_judges/island_perimeter/island_perimeter_solution.ipynb) |
| Format license keys | [Challenge](online_judges/license_key/format_license_key_challenge.ipynb)│[Solution](online_judges/license_key/format_license_key_solution.ipynb) |
| Find the longest absolute file path | [Challenge](online_judges/longest_abs_file_path/longest_path_challenge.ipynb)│[Solution](online_judges/longest_abs_file_path/longest_path_solution.ipynb) |
| Merge tuple ranges | [Challenge](online_judges/merge_ranges/merge_ranges_challenge.ipynb)│[Solution](online_judges/merge_ranges/merge_ranges_solution.ipynb) |
| Assign cookies | [Challenge](online_judges/assign_cookies/assign_cookies_challenge.ipynb)│[Solution](online_judges/assign_cookies/assign_cookies_solution.ipynb) |
| Determine if you can win in Nim | [Challenge](online_judges/nim/nim_challenge.ipynb)│[Solution](online_judges/nim/nim_solution.ipynb) |
| Check if a magazine could have been used to create a ransom note | [Challenge](online_judges/ransom_note/ransom_note_challenge.ipynb)│[Solution](online_judges/ransom_note/ransom_note_solution.ipynb) |
| Find the number of times a sentence can fit on a screen | [Challenge](online_judges/sentence_screen_fit/sentence_screen_fit_challenge.ipynb)│[Solution](online_judges/sentence_screen_fit/sentence_screen_fit_solution.ipynb) |
| Utopian tree | [Challenge](online_judges/utopian_tree/utopian_tree_challenge.ipynb)│[Solution](online_judges/utopian_tree/utopian_tree_solution.ipynb) |
| Maximizing xor | [Challenge](online_judges/maximizing_xor/maximizing_xor_challenge.ipynb)│[Solution](online_judges/maximizing_xor/maximizing_xor_solution.ipynb) |
| Add a challenge | [Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md)│[Contribute](https://github.com/donnemartin/interactive-coding-challenges/blob/master/CONTRIBUTING.md) |