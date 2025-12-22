# Sorting and Searching Algorithms

## Sorting Algorithms

| Algorithm | Best Case | Average Case | Worst Case | Space Complexity | Stable |
|-----------|-----------|--------------|------------|------------------|--------|
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) | Yes |
| Selection Sort | O(n²) | O(n²) | O(n²) | O(1) | No |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) | Yes |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) | Yes |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) | No |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) | No |
| Counting Sort | O(n + k) | O(n + k) | O(n + k) | O(k) | Yes |
| Radix Sort | O(nk) | O(nk) | O(nk) | O(n + k) | Yes |
| Bucket Sort | O(n + k) | O(n + k) | O(n²) | O(n) | Yes |
| Shell Sort | O(n log n) | O(n log² n) | O(n²) | O(1) | No |

## Searching Algorithms

| Algorithm | Best Case | Average Case | Worst Case | Space Complexity | Prerequisite |
|-----------|-----------|--------------|------------|------------------|--------------|
| Linear Search | O(1) | O(n) | O(n) | O(1) | None |
| Binary Search | O(1) | O(log n) | O(log n) | O(1) | Sorted array |
| Jump Search | O(1) | O(√n) | O(√n) | O(1) | Sorted array |
| Interpolation Search | O(1) | O(log log n) | O(n) | O(1) | Sorted & uniformly distributed |
| Exponential Search | O(1) | O(log n) | O(log n) | O(1) | Sorted array |
| Ternary Search | O(1) | O(log₃ n) | O(log₃ n) | O(1) | Sorted array |
| Fibonacci Search | O(1) | O(log n) | O(log n) | O(1) | Sorted array |

## Notes

- **k**: Range of input values
- **Stable**: Maintains relative order of equal elements
- **In-place**: Requires O(1) or O(log n) extra space
