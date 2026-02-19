# Grocery-Billing-System_Shaurya_Jakhmola_202501100700212

# Grocery Store Billing System 🛒

## 📖 Problem Statement
A grocery store wants to calculate the total cost of items purchased by a customer.  
The system should:
- Accept price input for 3 different items  
- Calculate the total cost  
- Apply a **10% discount** if the total exceeds $50  
- Display the **Original Total, Discount (if applicable), and Final Amount Payable**  

This case study demonstrates how Python can be used to implement a simple billing system with conditional logic and formatted output.

---

## 🛠️ Approach
1. **Input Handling**  
   - The program prompts the user to enter the price of three items.  
   - Inputs are converted to floating‑point numbers to handle decimal values.  

2. **Total Calculation**  
   - The sum of all three item prices is computed as the **Original Total**.  

3. **Discount Logic**  
   - If the total exceeds $50, a 10% discount is applied.  
   - Otherwise, no discount is given.  

4. **Final Amount**  
   - The discount (if any) is subtracted from the original total.  
   - The program displays the billing summary with proper formatting (`:.2f` for currency style).  

5. **Code Quality**  
   - Proper indentation and comments are included for readability.  
   - Output is structured clearly for user understanding.  

---

## 📊 Sample Output
**Input:**
Enter price of Item 1: 20 
Enter price of Item 2: 15
Enter price of Item 3: 25


**Output:**
--- Billing Summary --- 
Original Total: $60.00 
Discount: $6.00
Final Amount Payable: $54.00



---

## 🎯 Conclusion
This project highlights how Python can be applied to real‑world scenarios like billing systems. It is beginner‑friendly, easy to extend, and serves as a foundation for more advanced applications such as tax calculations, multiple item handling, or database integration.









