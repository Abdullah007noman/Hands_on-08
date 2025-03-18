This repository contains a Python implementation of the quicksort algorithm and the i-th order statistic using the Quickselect method. The code demonstrates how to leverage quicksort to determine the i-th smallest element in an array efficiently.

## Features
Quicksort Algorithm: A recursive sorting algorithm that uses divide-and-conquer.

Quickselect Algorithm: A variation of quicksort to find the i-th smallest element without fully sorting the array.

## How It Works
Quicksort: The array is recursively partitioned around a pivot, sorting the array in ascending order.

i-th Order Statistic (Quickselect):

Instead of sorting the entire array, Quickselect focuses on finding the desired element by partially partitioning the array.

This reduces unnecessary computation and improves efficiency.

## Example Usage
The script includes an example to demonstrate its functionality. For an input array [3, 6, 8,nd i = 4, the program finds the element that would be at index 4` if the array were sorted.
