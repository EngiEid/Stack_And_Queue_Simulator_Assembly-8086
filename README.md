# 📌 Stack & Queue Simulator – Assembly x86  
A **Stack & Queue simulator** implemented in **8086 Assembly**.  
The program provides an interactive console interface allowing the user to perform fundamental operations on Stack and Queue data structures.

---

## 📂 **Project Structure**
The project contains three main files:

| File | Description |
|------|-------------|
| **SANDQ.ASM** | Main Assembly source code (x86) |
| **SANDQ.OBJ** | Compiled object file |
| **SANDQ.EXE** | Final executable program |

---

## 👥 **Team Members**
- Engy Eid Abdelfatah  
- Engy Alaa Fikry  
- Basma Nabil Mohammed  

---

## 🔧 **Features & Operations**
### **Main Menu**
Users can select between:
- **Stack**
- **Queue**
- **Exit**

---

## 🧱 **Stack Operations**
- **PUSH** – Add an element  
- **POP** – Remove the Top element  
- **LENGTH** – Display current number of elements  
- **DISPLAY** – Show all elements in the stack  
- **MIN** – Display minimum value  
- **MAX** – Display maximum value  
- **SUM** – Calculate total sum of elements  
- **Back / Exit**

---

## 📬 **Queue Operations**
- **ENQUEUE** – Add an element  
- **DEQUEUE** – Remove the first element  
- **LENGTH** – Display current number of elements  
- **DISPLAY** – Show all elements in the queue in order  
- **MIN** – Display minimum value  
- **MAX** – Display maximum value  
- **SUM** – Calculate total sum of elements  
- **Back / Exit**

---

## 💾 **Data Structures Used**
- `STACK_ARRAY` — array of 100 elements  
- `QUEUE_ARRAY` — array of 100 elements  
- Counters:  
  - `STACK_COUNT`  
  - `QUEUE_COUNT`  
  - `QUEUE_HEAD`  
  - `QUEUE_TAIL`  
- `DS_TYPE` to determine which data structure is currently active (Stack or Queue)

---

## 📝 **Program Flow**
- Displays the team members  
- Waits for user input to start  
- Shows the Main Menu  
- User selects Stack or Queue  
- Displays the corresponding operations menu  
- Executes operations with success or error messages (e.g., Overflow, Underflow)  
- Returns to menu until exit is selected  

---

## ⭐ **Highlights**
- Simple and clear CLI interface  
- Full support for arithmetic operations (Min – Max – Sum)  
- Queue handled using Head/Tail pointers  
- Input validation for incorrect entries  
- Well-structured code with modular procedures  

