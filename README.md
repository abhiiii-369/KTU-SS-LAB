# KTU-SS-LAB✨💡
**PROGRAMS THAT YOU NEED IN SS**

---

## 🧩 Program Descriptions

### 🔹 Two Pass Assembler

A two-pass assembler converts assembly language code into machine code.  
It performs:
1. **Pass One:** Generates symbol table and intermediate code.
2. **Pass Two:** Produces the final object code using the symbol table.

**Files:**
- `pass1.c` – Implementation of Pass One  
- `pass2.c` – Implementation of Pass Two

---

### 🔹 Loaders

#### **1. Absolute Loader**
Loads the object program into memory at an absolute address without relocation.  
It assumes the program starts at a fixed location.

**File:** `absolute.c`

#### **2. Relocating Loader**
Loads programs that can be placed at any memory location.  
It adjusts addresses in the object program based on the actual load address.

**File:** `relocate.c`

---



