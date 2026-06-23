# 📓 My DSA Diary

A personal diary of my daily Data Structures & Algorithms practice. Every day, at least one problem — solved, understood, and committed.

---

## 🎯 Goal

To build consistency and sharpen problem-solving skills by tackling DSA problems daily, with a focus on LeetCode. This repo serves as a living record of my progress over time.

---

## 🛠️ Language

All solutions are written in **Python**.

---

## 📂 Structure

```
my_dsa_diary/
├── arrays/
├── strings/
├── linked_lists/
├── trees/
├── graphs/
├── dynamic_programming/
├── sorting_and_searching/
├── stack_and_queue/
└── ...
```

Each file is named descriptively, e.g. `two_sum.py`, `longest_substring_without_repeating.py`, and includes:
- Problem link (LeetCode)
- Difficulty (Easy / Medium / Hard)
- Approach / thought process (in comments)
- Time & space complexity

---

## 📌 Example File Format

```python
# Problem: Two Sum
# Link: https://leetcode.com/problems/two-sum/
# Difficulty: Easy
#
# Approach:
# Use a hashmap to store seen numbers and their indices.
# For each number, check if its complement exists in the map.
#
# Time Complexity: O(n)
# Space Complexity: O(n)

def twoSum(nums, target):
    seen = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in seen:
            return [seen[complement], i]
        seen[num] = i
```

---

## 📈 Progress

| Date | Problem | Difficulty | Topic |
|------|---------|------------|-------|
| — | — | — | — |



---

## 🙋 About Me

- 🎓 Master's in Computer Science — Lakehead University (2026)
- 💼 Actively exploring roles in ML Engineering, Data Engineering & Software Engineering
- 🐍 Python enthusiast with a strong background in ML/AI
- 🔗 [LinkedIn](https://linkedin.com/in/aviral-nautiyal)

---

## ⭐ Why This Repo?

Consistency beats intensity. This repo is my commitment to show up every day, think through problems carefully, and get better — one problem at a time.
