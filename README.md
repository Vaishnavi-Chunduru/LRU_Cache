# LRU Cache Simulator

## Overview
The **LRU Cache Simulator** is a web-based interactive visualization tool that demonstrates how the **Least Recently Used (LRU)** cache algorithm works. It allows users to perform cache operations and observe how elements are inserted, accessed, updated, and evicted when the cache reaches its capacity.

This project is useful for understanding core **Data Structures** concepts and cache replacement policies through real-time visualization.

---

## Features
- Interactive visualization of LRU Cache operations  
- Supports **Get (Access)** and **Put (Insert/Update)** operations  
- Dynamic cache capacity selection  
- Real-time **Hit** and **Miss** counters  
- Animated highlighting for:
  - Newly accessed elements  
  - Evicted elements  
- Operation log with timestamps  
- Multiple UI themes:
  - Ocean Blue  
  - Forest Green  
  - Sunset Orange  
  - Purple Dream  
  - Dark Mode  
- Responsive and clean UI design

---

## How LRU Cache Works

**LRU (Least Recently Used)** is a cache replacement policy that removes the item that has not been used for the longest time when the cache becomes full.

### Operations

**Put(key, value)**
- Inserts a new key-value pair into the cache.
- If the key already exists, its value is updated.
- If capacity is exceeded, the least recently used element is removed.

**Get(key)**
- Returns the value if the key exists.
- Moves the accessed element to the most recently used position.
- If the key does not exist, it is counted as a cache miss.

---

## Technologies Used
- HTML5  
- CSS3 (CSS Variables for themes)  
- JavaScript (ES6)  
- Map Data Structure (for LRU implementation)

---

## Project Structure
LRU-Cache-Simulator/
│
├── index.html
└── README.md


---

## How to Run the Project
1. Download or clone the repository.
2. Open the project folder.
3. Open **index.html** in any web browser.

No additional installation or dependencies are required.

---

## Example Workflow
1. Set the cache capacity.
2. Choose an operation:
   - **Put** to insert/update values  
   - **Get** to access values
3. Execute the operation.
4. Observe:
   - Cache order (Most Recently Used → Least Recently Used)
   - Hits and Misses
   - Evicted elements
   - Operation logs

---

## Learning Objectives
This project helps in understanding:
- LRU Cache Algorithm  
- Cache Replacement Policies  
- HashMap-based implementations  
- Time complexity optimization  
- Visualization of data structures

---

## Future Improvements
- Step-by-step simulation mode  
- Doubly Linked List visualization for internal structure  
- Export logs feature  
- Support for additional cache algorithms (FIFO, LFU)  
- Backend integration for storing simulation history

---

## Author
**Vaishnavi Chunduru**  
B.Tech Computer Science Student

