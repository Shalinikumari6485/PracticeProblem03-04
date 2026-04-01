# PracticeProblem03-04

## **🚀 Algorithm Practice – Sorting & Searching Systems**

This repository contains 6 real-world problem implementations using fundamental Sorting and Searching Algorithms in Java.
Each problem demonstrates how algorithms are applied in domains like banking, trading, risk analysis, and auditing.

### 🎯 Objective

To understand and implement core algorithms (Bubble, Insertion, Merge, Quick, Linear, Binary Search)
To analyze time complexity and performance
To apply algorithms in real-world scenarios
To improve problem-solving skills for placements and exams

**📌 Problem 1: Transaction Fee Sorting**

📖 Description
Sort banking transactions based on fee for audit compliance using Bubble and Insertion Sort.

🔄 Flow of Program
Create transaction list (id, fee, timestamp)
Apply Bubble Sort (ascending by fee)
Apply Insertion Sort (fee + timestamp)
Detect high-fee outliers (>50)

**📌 Problem 2: Client Risk Score Ranking**

📖 Description
Sort clients based on risk score for priority review in financial systems.

🔄 Flow of Program
Create client array (riskScore, balance)
Apply Bubble Sort (ascending)
Apply Insertion Sort (descending + balance)
Display top risky clients

**📌 Problem 3: Trade Volume Analysis**

📖 Description
Analyze trading data by sorting trade volumes for market insights.

🔄 Flow of Program
Create trade dataset
Apply Merge Sort (ascending)
Apply Quick Sort (descending)
Merge datasets and calculate total volume

**📌 Problem 4: Portfolio Return Sorting**

📖 Description
Sort investment assets based on return rates for portfolio optimization.

🔄 Flow of Program
Create asset list (returnRate, volatility)
Apply Merge Sort (stable ascending)
Apply Quick Sort (descending + volatility)

**📌 Problem 5: Account ID Lookup**

📖 Description
Search transaction logs for account IDs using Linear and Binary Search.

🔄 Flow of Program
Create account ID array
Perform Linear Search (first & last occurrence)
Sort data
Apply Binary Search
Count duplicates

**📌 Problem 6: Risk Threshold Lookup**

📖 Description
Find risk thresholds using Binary Search techniques.

🔄 Flow of Program
Input sorted risk values
Perform Linear Search
Apply Binary Search
Find floor & ceiling values
Determine insertion position

**⚙️ Technologies Used**

Java (Core)
Arrays & ArrayList
Sorting Algorithms
Searching Algorithms

**📊 Algorithms Covered**

Bubble Sort – O(n²)
Insertion Sort – O(n²)
Merge Sort – O(n log n)
Quick Sort – O(n log n)
Linear Search – O(n)
Binary Search – O(log n)