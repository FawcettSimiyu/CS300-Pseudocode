# 📘 CS300-Pseudocode Guide

💡 *I can help you complete this project at an affordable price!*  
📞 Contact me via **WhatsApp** at [+254794689731](https://wa.me/254794689731)  
📧 Or email: **fawcetteugene@gmail.com**

---

## 📌 What’s Inside

This guide provides example pseudocode and runtime analysis for each CS300 milestone using different data structures:

- ✅ **Vector** implementation – Milestone 1 (with full pseudocode)
- ✅ Function signatures for **Hash Table** & **Binary Search Tree**
- ✅ Example **Big-O Runtime Analysis Chart**

---

### 🔹 Vector - Milestone 1
```cpp
void searchCourse(Vector<Course> courses, String courseNumber) {
    for all courses
        if the course is the same as courseNumber
            print out the course information
            for each prerequisite of the course
                print the prerequisite course information
}
```

---

### 🔹 Hash Table - Milestone 2
```cpp
void searchCourse(HashTable<Course> courses, String courseNumber) {
    // To be implemented
}
```

---

### 🔹 Binary Search Tree – Milestone 3
```cpp
void searchCourse(Tree<Course> courses, String courseNumber) {
    // To be implemented
}
```

---

## ⏱️ Runtime Analysis Example (Vector)

| Code                                 | Line Cost | # Times Executes | Total Cost |
|--------------------------------------|-----------|------------------|-------------|
| for all courses                      | 1         | n                | n           |
| if the course is the same            | 1         | n                | n           |
| for each prerequisite of the course | 1         | 1                | 1           |
| print the prerequisite               | 1         | n                | n           |
| **Total Cost**                       |           |                  | **4n + 1**   |
| **Runtime**                          |           |                  | **O(n)**     |

---

## 🤝 Need Help?

📲 Click the WhatsApp icon below to chat and get assistance with your CS300 Project!

[![WhatsApp](https://img.shields.io/badge/Chat%20on-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/254794689731)

---

> ⚠️ *This solution is for educational purposes. Always adhere to your academic integrity policies.*
