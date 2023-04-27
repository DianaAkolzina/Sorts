Sorting Algorithms Visualization
This repository contains two Python programs that demonstrate the implementation and visualization of 10 sorting algorithms:

Bubble Sort
Selection Sort
Insertion Sort
Merge Sort
Quick Sort
Heap Sort
Counting Sort
Radix Sort
Shell Sort
Tim Sort (Python's built-in sort)
sorting_algorithms.py
This file contains the implementation of 10 sorting algorithms. The primary function of this module is to sort arrays of integers using various algorithms.

Usage
python
Copy code
from sorting_algorithms import bubble_sort, quick_sort, tim_sort, ...

sorted_array = bubble_sort(unsorted_array)
sorting_visualization.py
This file uses the sorting algorithms implemented in sorting_algorithms.py and visualizes the sorting process for each algorithm using the matplotlib library.

Dependencies
matplotlib
You can install the required dependency using pip:

bash
Copy code
pip install matplotlib
Usage
Simply run the sorting_visualization.py script:

bash
Copy code
python sorting_visualization.py
The script will generate a random array of integers and visualize the sorting process for each algorithm in separate windows.
