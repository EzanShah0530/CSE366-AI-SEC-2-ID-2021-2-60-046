# CSE 366 AI Lab Tasks 

## Overview
This repository contains Python based  lab tasks for AI and file handling and so on.

### Task 1: Student Selection for Viva
A program to select students randomly for viva.

#### Instructions
1. **Load Student IDs**: Reads student IDs from `student_ids.txt`, where each ID follows the format `YYYY-N-MM-xxx`.
2. **Manage List**: Keeps track of students who haven’t been selected.
3. **Random Selection**: Picks a student for viva, removes them from the list, and repeats until all students are chosen.
4. **Reset**: Once all students are picked, the list resets to include everyone again.

#### Additional Notes
- Error handling for missing or misformatted files.
- Includes a "Viva #" counter to track the selection order.

---

### Task 2: Trading Agent for Smartphone Inventory Management
An AI-based trading agent that manages smartphone inventory based on price and stock levels.

#### Key Features
- **Percepts**: 
  - **Price**: Current price of a smartphone model.
  - **Stock Level**: Number of units available.
- **Decision Rules**:
  - Orders more units if there is a 20% price drop.
  - Reorders if stock falls below 10 units.
  - No order if neither condition is met.

#### Actions
- If conditions are met, the agent orders additional units as specified.

#### Output
The task generates a graph showing the agent’s decisions based on price and stock level changes.

---
