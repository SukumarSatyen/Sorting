# Sorting Algorithms Comparison

Bubble Sort has a time complexity of \(O(n^2)\) and a space complexity of \(O(1)\), which is not optimal for large datasets. Here are a few alternative sorting algorithms with better time complexity:

## 1. Merge Sort

- **Time Complexity**: \(O(n \log n)\)
- **Space Complexity**: \(O(n)\)

Merge Sort is a stable, divide-and-conquer algorithm that works by recursively dividing the array into halves, sorting each half, and then merging the sorted halves.

## 2. Quick Sort

- **Time Complexity**: \(O(n \log n)\) on average; \(O(n^2)\) in the worst case
- **Space Complexity**: \(O(\log n)\) for the recursive stack space

Quick Sort is also a divide-and-conquer algorithm that works by selecting a 'pivot' element, partitioning the array around the pivot, and then recursively sorting the partitions.

## 3. Heap Sort

- **Time Complexity**: \(O(n \log n)\)
- **Space Complexity**: \(O(1)\)

Heap Sort converts the array into a binary heap and then extracts the maximum element one by one, resulting in a sorted array.
