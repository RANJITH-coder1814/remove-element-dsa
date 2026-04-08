# 🧹 Remove Element (C++)

This repository contains a solution for **LeetCode 27: Remove Element** using an efficient in-place approach.

---

## 🚀 Problem Statement

Given an integer array `nums` and an integer `val`, remove all occurrences of `val` **in-place**.

- The order of elements may change
- Return the number of elements not equal to `val` (denoted as `k`)
- The first `k` elements of `nums` should contain valid elements

---

## 🧠 Approach (Two Pointer)

- Use a pointer `k` to track position of valid elements
- Traverse the array:
  - If `nums[i] != val`, assign it to `nums[k]`
  - Increment `k`
- Return `k`

---


        return k;
    }
};
