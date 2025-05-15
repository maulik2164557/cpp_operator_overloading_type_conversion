# Operator Overloading – Type Conversion in C++
### 📊 An Advanced Study of Implicit & Explicit Conversions via Operator Overloading

👨‍💻 Author: Maulik N. Patoliya  
🎓 Branch: Computer Engineering | Semester: 02  
📘 Subject: Operator Overloading – Type Conversion 

📍 Material: <a href="https://github.com/maulik2164557/cpp_operator_overloading_type_conversion_study/blob/7f4739e2f679d580a7e1038e0ae89dfaa4c8cb24/Operator%20Overloading%20-%20Type%20Conversion_.pdf">[Operator_Overloading - Type_Conversion]</a>

---

### 🔍 Overview

This repository explores **complex type conversion and operator overloading in C++**, using a real-world analogy: **currency conversion between INR and USD** and **distance conversion between meters and feet**.

💡 This study examines:
- Conversion constructor vs conversion operator (`operator TYPE()`)
- Overloaded arithmetic and type-casting operations
- Implicit vs explicit conversion priorities
- Ambiguities caused by multiple valid conversions
- Use of cartesian ↔ polar coordinate systems

---

### 📂 Topics + Examples Covered

✅ INR & USD conversion logic  ( INR - Indian Currency & USD - US Currency )

✅ Arithmetic overloading with conversion  
✅ Ambiguity due to multiple valid conversions  
✅ Solution techniques (`constructor`, `operator`, overload resolution)  
✅ Cartesian & Polar coordinate interaction  

---

### 📌 Key Insights

🔄 Feature	Summary

operator TYPE()	                -   Used for implicit/explicit casting between user-defined types

Conversion Constructor	        -   Helps create a target type from a source, e.g., USD(INR)

Multiple Valid Conversions	    -   Can lead to ambiguity — constructor vs conversion operator

Best Practice	                  -   Use only one method of conversion at a time to avoid ambiguity


---

### ✅ Conclusion
- Use conversion constructors when you want the destination class to control how conversion happens.

- Use operator TYPE() only when required, as it adds implicit conversion power, which may cause ambiguity.

- Avoid defining both conversion constructor and conversion operator in same direction unless necessary.

- Explicit conversions with static_cast<TYPE>(obj) improve clarity.

