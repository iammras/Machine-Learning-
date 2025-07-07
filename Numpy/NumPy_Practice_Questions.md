# 🧪 NumPy Practice Questions

These questions are designed to help reinforce your understanding of NumPy basics.

---

## ✅ Section 1: Array Creation

1. Create a 1D array of integers from 10 to 50 (inclusive) with a step of 5.
2. Create a 3x3 array filled with the number 7.
3. Create an array with 10 random integers between 1 and 100.
   - Find the min, max, and mean of that array.

---

## ✅ Section 2: Indexing and Slicing

4. Create the array `arr = np.array([10, 20, 30, 40, 50])`  
   - Print the last 3 elements using slicing.

5. Create a 4x4 array with numbers from 1 to 16.  
   - Print the 2nd row.  
   - Print the element at row 3, column 2.  
   - Slice and print a 2x2 block from bottom-right.

---

## ✅ Section 3: Reshaping and Flattening

6. Create an array of 12 elements.  
   - Reshape it to shape (3, 4)  
   - Then flatten it to 1D

7. Transpose a 2x3 matrix into 3x2 and print the result.

---

## ✅ Section 4: Array Operations

8. Create two arrays `a = [1, 2, 3]` and `b = [4, 5, 6]`  
   - Add, subtract, multiply them.  
   - Square each element of `a`.

9. Apply broadcasting: Add 10 to every element of a 3x3 matrix.

---

## ✅ Section 5: Random & Boolean Masking

10. Create a 4x4 array of random integers (1–100)  
    - Find how many elements are divisible by 5.  
    - Replace all even numbers with `-1`.

---

## ✅ Section 6: Copy vs View

11. Create `a = np.array([1, 2, 3])`  
    - Create `b = a.copy()` and `c = a.view()`  
    - Modify `b[0]` and `c[1]`, then print `a`, `b`, and `c`.  
    - Observe the differences and comment on it.

---

## ✅ Section 7: Stacking Arrays

12. Create `a = np.array([1, 2, 3])` and `b = np.array([4, 5, 6])`  
    - Stack them vertically using `vstack`  
    - Stack them horizontally using `hstack`

---

## 💡 Bonus Challenge

13. Create a 5x5 array with numbers 1 to 25  
    - Replace the center 3x3 block with zeros using slicing.

---

📝 Save your code in a Colab notebook: `NumPy_Practice_Solutions.ipynb`