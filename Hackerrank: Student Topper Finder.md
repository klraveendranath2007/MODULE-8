# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:
      student_marks = {
          'Alice': [87, 94, 92, 88, 94],
          'Bob': [87, 67, 78, 75, 83],
          'Eve': [91, 93, 85, 86, 81]
      }
      
      total_marks = {name: sum(marks) for name, marks in student_marks.items()}
      topper = max(total_marks, key=total_marks.get)
      top_score = total_marks[topper]
      
      print(total_marks)
      print("Topper is:", topper, "with marks =", top_score)

## OUTPUT
![image](https://github.com/user-attachments/assets/cf952c7a-b67e-4561-8a5f-887230b269a4)


## RESULT
Thus, the program has been execueted successfully.
