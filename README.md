# Selection Sort Visualization 🎨

A graphical demonstration of the **Selection Sort** algorithm using `graphics.h` in C++.

## 📸 Screenshots

<p float="left">
  
## Visualization:

Input Visualization: 
![image](https://github.com/user-attachments/assets/7a7ccb88-0e9d-4831-b244-074632e3f12d)
Unsorted Array

Output Visualization:
![image](https://github.com/user-attachments/assets/1c8ea38d-d934-4fb7-b037-0606b681f3dd)
Sorted Array
</p>

## 📋 Description

This project visualizes how **Selection Sort** works by drawing vertical lines to represent array elements and highlighting transitions in color:

- White lines: array elements (height = value)
- Green lines: currently selected minimum element
- Real-time swapping animations using `swap_colors()` function

## 🧠 Algorithm Logic

Selection Sort repeatedly:
1. Finds the minimum element in the unsorted section
2. Swaps it with the first unsorted element
3. Updates the visualization on every change

## 🛠️ Tools & Libraries

- **C++**
- **graphics.h** (Turbo C++ or WinBGIm)

## ▶️ How to Run

1. Install Turbo C++ or any `graphics.h` compatible environment (like WinBGIm)
2. Compile using:
   ```bash
   g++ selection_sort.cpp -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
