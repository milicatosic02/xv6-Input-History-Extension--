# xv6 Input History Extension  

This project was developed as part of the **Operating Systems 2024** course.  
The task was to extend the **xv6 operating system** by adding support for **command input history**, allowing users to navigate through and reuse previously executed commands.  

---

## Objectives  

The main objective was to implement input history in a way that integrates seamlessly with the existing xv6 system without affecting its stability or performance.  

Key goals included:  
- Displaying previously entered commands  
- Navigating through the command history  
- Selecting and executing a previously entered command  

---

## Features  

- **Command recall** – users can view earlier commands directly in the terminal  
- **History navigation** – intuitive movement through the command list  
- **Re-execution** – selected commands can be executed again without retyping  
- **System stability** – the implementation ensures that history usage does not cause crashes or performance issues  

---

## Technical Details  

- Implemented by modifying the **xv6 kernel** and shell components  
- Integrated history buffer to store and manage commands  
- Extended input handling to support navigation and command recall  
- Careful attention given to error handling and preserving system integrity  

---

## Learning Outcome  

Through this project, the following areas of operating systems were practiced:  
- Extending an existing OS with new features  
- Low-level input handling in xv6  
- Buffer and memory management for command storage  
- Ensuring backward compatibility and system reliability  

---
