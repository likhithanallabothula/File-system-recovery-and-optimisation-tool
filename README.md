# 🗂️ File System Recovery & Optimization Tool  
### Operating Systems Project – CSE316  
### Lovely Professional University  

---

## 📌 Overview  
This project is a **web-based simulation tool** that demonstrates how file systems recover from damage and optimize storage layout after failures such as disk crashes or block corruption.

The system visually simulates:
- Free-space management  
- Directory reconstruction  
- Block recovery  
- File access mechanism behavior  
- Optimization techniques such as **defragmentation**, **compaction**, and **journaling replay**

This tool helps users understand how real-world operating systems handle **recovery**, **repair**, and **performance optimization** after file system corruption.

---

## 🎯 Project Objectives
1. Simulate file system failures and recovery mechanisms  
2. Reconstruct damaged or corrupted blocks using multiple strategies  
3. Demonstrate free-space redistribution after crashes  
4. Optimize storage layout to improve read/write speed  
5. Provide interactive visualization of the recovery process  
6. Show performance metrics clearly and intuitively  

---

## 🧩 Features

### 🔹 **1. Input Configuration Panel**
Users can enter:
- File blocks  
- Corrupted file blocks  
- Recovery mechanism  
- Optimization modes to apply  

### 🔹 **2. Recovery Techniques Implemented**
The tool supports three major recovery methods:
- **Linked List Allocation Recovery**  
- **Indexed Allocation Recovery**  
- **FAT Table Recovery**  

These help visualize how different file systems rebuild damaged structures.

### 🔹 **3. Optimization Techniques**
The user may enable:
- ✔ **Defragmentation** – reorganizing blocks to reduce fragmentation  
- ✔ **Space Compaction** – grouping free spaces for better allocation  
- ✔ **Journaling Replay** – simulating crash logs to restore file system  

### 🔹 **4. Visualization**
Uses Chart.js to display:
- Recovery graph  
- Block behavior during simulation  
- Impact of optimization  

### 🔹 **5. Metrics Dashboard**
Shows:
- Technique used  
- Blocks recovered  
- Errors remaining  
- Optimization score  

This helps compare the effectiveness of recovery strategies.

---

## 🌐 Technologies Used

### **Frontend**
- HTML5  
- CSS3 (custom gradient theme, glassmorphism UI)  
- JavaScript  

### **Libraries**
- Chart.js (for visualization)

### **Tools**
- GitHub (revision tracking)  
- VS Code / Browser Developer Tools  

---

## 🛠️ How It Works

### **1. User Input Layer**
- Reads block list  
- Identifies corrupted blocks  
- Selects recovery technique  
- Selects optimization techniques  

### **2. Recovery Engine (Simulation Layer)**
The engine simulates recovery based on selected method:
- Linked list reconstruction  
- Indexed lookup restoration  
- FAT entry rebuilding  

### **3. Optimization Engine**
Performs:
- Logical defragmentation  
- Space compaction  
- Journaling-based consistency repair  

### **4. Visualization & Metrics Layer**
Displays:
- Line graph of block values  
- Recovered vs failed blocks  
- Recovery/optimization score  

---

## 📊 Output

Your tool generates:
- A recovery visualization graph  
- Recovery technique name  
- Count of successfully recovered blocks  
- Remaining corrupted blocks  
- Optimization score (higher = better)

---

http://127.0.0.1:3000/code.html?serverWindowId=6f06fefa-ff28-4f99-a7b7-551cf07a09e4
