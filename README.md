# Sorting Visualizer

## Overview

The **Sorting Visualizer** is an interactive tool designed to help users visualize how different sorting algorithms work. Using HTML, CSS, and JavaScript, this web app provides a graphical representation of how various sorting algorithms sort a list of numbers.

Algorithms Included:
- **Selection Sort**
- **Merge Sort**
- **Insertion Sort**
- **Quick Sort**
- **Bubble Sort**
- **Heap Sort**

Each algorithm is visualized by showing the elements as bars that are rearranged to reflect the steps of the sorting process.

## Features

- **Visual Sorting**: Watch sorting algorithms in action as they process the array step by step.
- **Interactive Controls**: Choose the sorting algorithm you want to visualize, and control the speed of the visualization.
- **Random Array Generation**: Generate random arrays with varying sizes to test how the algorithms behave with different input.
- **Responsive Design**: The visualizer works on both desktop and mobile devices.

## Technologies & Tools Used

- **HTML**: Provides the structure of the app and the visual layout.
- **CSS**: Styles the app and its elements, ensuring an attractive and responsive design.
- **JavaScript**: The main logic of the app, where sorting algorithms are implemented and visualized.
- **Canvas (optional)**: Used for rendering the array visualization on the screen.
- **Animation**: Utilized to animate the sorting steps and make the process visually clear.

## Supported Sorting Algorithms

### 1. **Selection Sort**
Selection Sort works by repeatedly selecting the minimum element from the unsorted part of the array and swapping it with the first unsorted element. This process continues until the array is sorted.

### 2. **Merge Sort**
Merge Sort is a divide-and-conquer algorithm. It divides the array into two halves, sorts them recursively, and then merges the sorted halves.

### 3. **Insertion Sort**
Insertion Sort builds the sorted array one element at a time. It takes elements from the unsorted part of the array and places them in the correct position in the sorted part.

### 4. **Quick Sort**
Quick Sort is a divide-and-conquer algorithm. It picks an element as a pivot and partitions the array around the pivot. It then recursively sorts the subarrays.

### 5. **Bubble Sort**
Bubble Sort works by repeatedly stepping through the list, comparing adjacent elements, and swapping them if they are in the wrong order. This continues until the array is sorted.

### 6. **Heap Sort**
Heap Sort converts the array into a max-heap (or min-heap) and then repeatedly extracts the largest element, placing it in its correct position.

## Project Structure

- **index.html**: The main HTML file that contains the structure of the sorting visualizer, including input fields, buttons, and the display for the array.
- **styles.css**: The CSS file responsible for styling the sorting visualizer, including the layout, buttons, bars, and colors.
- **script.js**: The JavaScript file that implements the sorting algorithms and animates the visualization of the sorting process.

