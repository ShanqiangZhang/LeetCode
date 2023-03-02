- [LeetCode](#leetcode)
- [1.多指针](#1多指针)
  - [1.1 链表](#11-链表)
    - [1.1.1 遍历和模拟](#111-遍历和模拟)
    - [1.1.2 快慢指针](#112-快慢指针)
    - [1.1.3 merge list](#113-merge-list)
    - [1.1.4 操作node](#114-操作node)
    - [1.1.5 链表环](#115-链表环)
    - [1.1.6 深度copy链表](#116-深度copy链表)
  - [1.2 滑动窗口](#12-滑动窗口)
  - [1.3 字符回文](#13-字符回文)
  - [1.4 贪心](#14-贪心)
  - [1.5 数组](#15-数组)
  - [1.6 前项和](#16-前项和)
  - [1.7 和差问题](#17-和差问题)
  - [1.8 区间](#18-区间)


# LeetCode

# 1.多指针

## 1.1 链表

### 1.1.1 遍历和模拟

| 题目               | link                                           | 代码                                                                   |
| ------------------ | ---------------------------------------------- | ---------------------------------------------------------------------- |
| 2. Add Two Numbers | https://leetcode.com/problems/add-two-numbers/ | https://leetcode.com/problems/add-two-numbers/solutions/3249259/topic/ |

### 1.1.2 快慢指针

| 题目                                           | link                                                                     | 代码 |
| ---------------------------------------------- | ------------------------------------------------------------------------ | ---- |
| 876. Middle of the Linked List                 | https://leetcode.com/problems/middle-of-the-linked-list/                 |      |
| 19. Remove Nth Node From End of List           | https://leetcode.com/problems/remove-nth-node-from-end-of-list/          |      |
| 109. Convert Sorted List to Binary Search Tree | https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/ |      |

### 1.1.3 merge list

| 题目                       | link                                                  | 代码 |
| -------------------------- | ----------------------------------------------------- | ---- |
| 21. Merge Two Sorted Lists | https://leetcode.com/problems/merge-two-sorted-lists/ |      |

### 1.1.4 操作node

**(1) swap**

| 题目                    | link                                               | 代码                                                                      |
| ----------------------- | -------------------------------------------------- | ------------------------------------------------------------------------- |
| 24. Swap Nodes in Pairs | https://leetcode.com/problems/swap-nodes-in-pairs/ | https://leetcode.com/problems/swap-nodes-in-pairs/solutions/3245119/swap/ |

**(2) reverse**

| 题目                         | link                                                    | 代码 |
| ---------------------------- | ------------------------------------------------------- | ---- |
| 206. Reverse Linked List     | https://leetcode.com/problems/reverse-linked-list/      |      |
| 92. Reverse Linked List II   | https://leetcode.com/problems/reverse-linked-list-ii/   |      |
| 25. Reverse Nodes in k-Group | https://leetcode.com/problems/reverse-nodes-in-k-group/ |      |
| 234. Palindrome Linked List  | https://leetcode.com/problems/palindrome-linked-list/   |      |

**(3) rotate**

| 题目            | link                                       | 代码 |
| --------------- | ------------------------------------------ | ---- |
| 61. Rotate List | https://leetcode.com/problems/rotate-list/ |      |

**(4) remove/move**   

| 题目                                      | link                                                                 | 代码 |
| ----------------------------------------- | -------------------------------------------------------------------- | ---- |
| 82. Remove Duplicates from Sorted List II | https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/ |      |
| 83. Remove Duplicates from Sorted List    | https://leetcode.com/problems/remove-duplicates-from-sorted-list/    |      |
| 86. Partition List                        | https://leetcode.com/problems/partition-list/                        |      |
| 328. Odd Even Linked List                 | https://leetcode.com/problems/odd-even-linked-list/                  |      |

### 1.1.5 链表环

| 题目                                  | link                                                            | 代码 |
| ------------------------------------- | --------------------------------------------------------------- | ---- |
| 141. Linked List Cycle                | https://leetcode.com/problems/linked-list-cycle/                |      |
| 142. Linked List Cycle II             | https://leetcode.com/problems/linked-list-cycle-ii/             |      |
| 160. Intersection of Two Linked Lists | https://leetcode.com/problems/intersection-of-two-linked-lists/ |      |

### 1.1.6 深度copy链表

copy链表用HashMap<oldNode, newNode> 来建立对应关系, 每次copy都要去map中找复制的新node, 不然复制过程会产生交叉

| 题目                               | link                                                         | 代码 |
| ---------------------------------- | ------------------------------------------------------------ | ---- |
| 138. Copy List with Random Pointer | https://leetcode.com/problems/copy-list-with-random-pointer/ |      |

## 1.2 滑动窗口

## 1.3 字符回文

## 1.4 贪心

## 1.5 数组

## 1.6 前项和

## 1.7 和差问题

## 1.8 区间