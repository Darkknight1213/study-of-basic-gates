
# Study of Basic Logic Gates

### **AIM**
To study and verify the truth table of logic gates in **Quartus II** using **Verilog programming**.

---

### **Equipment Required**
- **Software:** Quartus Prime

---

### **Theory**

Logic gates are the basic building blocks of any digital system. They are electronic circuits that operate on one or more input signals to produce a single output based on logical relationships. The fundamental logic gates are:

- AND gate  
- OR gate  
- NOT gate  
- NAND gate  
- NOR gate  
- EX-OR (Exclusive-OR) gate  
- EX-NOR (Exclusive-NOR) gate  

---

### **Logic Gates Description**

#### **1. AND Gate**
- **Logic:** Output is HIGH only when all inputs are HIGH.  
- **Expression:** `Y = A · B`

#### **2. OR Gate**
- **Logic:** Output is HIGH if one or more inputs are HIGH.  
- **Expression:** `Y = A + B`

#### **3. NOT Gate**
- **Logic:** Produces the logical inversion of the input.  
- **Expression:** `Y = A'`

#### **4. NAND Gate**
- **Logic:** Output is the negation of the AND output.  
- **Expression:** `Y = (A · B)'`

#### **5. NOR Gate**
- **Logic:** Output is the negation of the OR output.  
- **Expression:** `Y = (A + B)'`

#### **6. EX-OR (Exclusive-OR) Gate**
- **Logic:** Output is HIGH if the inputs are different.  
- **Expression:** `Y = A ⊕ B`

#### **7. EX-NOR (Exclusive-NOR) Gate**
- **Logic:** Output is HIGH if the inputs are the same.  
- **Expression:** `Y = (A ⊕ B)'`

---

### **Procedure**

1. Type the following Verilog program in **Quartus Prime**.  
2. Compile and run the program.  
3. Generate the **RTL schematic** and save the logic diagram.  
4. Create nodes for the inputs and outputs to generate a **timing diagram**.  
5. Verify the output for all possible input combinations.

---

### **Verilog Program**
```
module exp1(a, b, c, d, e, x, y, z);
input a, b;
output c, d, e, x, y, z;
assign c = a & b;    // AND gate
assign d = a | b;    // OR gate
assign e = a ^ b;    // XOR gate
assign x = ~(a & b); // NAND gate
assign y = ~(a | b); // NOR gate
assign z = ~(a ^ b); // XNOR gate
endmodule
```

**Program Developed by:** Mohamed Riyaz Ahamed  
**Register Number:** 212224240092

---

### **Logic Symbol & Truth Table**
![Logic Symbol & Truth Table](https://github.com/user-attachments/assets/177baa8d-a0a6-4bd2-a6e7-be5fbd7d89a9)

---

### **RTL Realization Output**
![RTL Realization Output](https://github.com/user-attachments/assets/85958f0f-0a4d-46e5-ae66-aff8c898d204)

---

### **RTL Schematic**
![RTL Schematic](https://github.com/user-attachments/assets/6b9bfad1-6361-41d2-83ef-5b32cc5627fd)

---

### **Result**
The truth tables of **AND, OR, NOT, NAND, NOR, XOR, and XNOR** gates were successfully implemented and verified using **Verilog programming** in **Quartus II**.

---
