# Regular Expression Matching in Java (Beginner Friendly)

This repository contains a simple and easy-to-understand Java solution for
**Regular Expression Matching** (LeetCode Problem #10).

---

## 📌 Problem Statement

Given a string `s` and a pattern `p`, determine if the pattern matches
the entire string.

Pattern rules:
- `.` matches any single character
- `*` matches zero or more of the preceding character

---

## 🧠 Approach Used

- Recursion
- Memoization (Dynamic Programming)
- Beginner-friendly logic
- Clean Java implementation

---

## 🧮 Algorithm

1. Start matching characters from index 0
2. If the pattern ends, string must also end
3. Check if characters match (same or `.`)
4. If `*` appears:
   - Skip the `x*`
   - OR match one character and continue
5. Store results to avoid repeated work

---

## ☕ Language Used
- Java

---

## 🧪 Example

**Input**
