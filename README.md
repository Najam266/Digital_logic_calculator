# Calculator Processor (DLD Project)

## Project Description
This project involves designing a processor for a calculator using digital logic. The processor performs basic operations such as displaying values, input handling, and arithmetic operations based on predefined commands.

## Features
- Display values of A and B
- Accept input for A and B
- Perform arithmetic operations: Addition and Assignment
- Command-based execution using control signals

## File Structure
- `LogicWorks5.zip`: Contains the project files. Extract it to access the LogicWorks design.
- `Project Code File`: The main code implementation for the processor.
- `Project Details.jpg`: An image describing the project details.
- `README.md`: This file with setup and usage instructions.

## Running the Project
1. **Download and Extract**
   - Download the `LogicWorks5.zip` file from the repository.
   - Extract the contents to a desired directory.

2. **Open the Project**
   - Open the extracted folder and locate the main project file.
   - Run the project using **LogicWorks 5**.

## Inputs & Outputs
### **Inputs:**
- **Clock Pulse (CP):** Controls the execution cycle.
- **Command Available (CA):** Indicates when a command is ready.
- **Command (C0...C2):** 3-bit command input defining the operation.
- **Input Data (A0...A3):** 4-bit input data.

### **Outputs:**
- **Output Available (OA):** Signals when output is ready.
- **Output Data (D0...D3):** 4-bit result output.

## Commands
| Command | Function |
|---------|----------|
| 000     | Display A |
| 001     | Display B |
| 010     | Input A |
| 011     | Input B |
| 100     | A = A + B |
| 101     | B = A + B |
| 110     | A = B |
| 111     | B = A |

## Tools Used
- **LogicWorks 5** (Digital Logic Design Software)
- **Digital Logic Circuit Design Principles**

## License
This project is for educational purposes. Feel free to use and modify it as needed.

---
### If you find this project helpful, consider starring the repository! ⭐
