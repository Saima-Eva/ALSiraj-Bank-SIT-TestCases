This repository contains **System Integration Testing (SIT)** test cases for **ALSiraj Bank**.  

The test cases are designed to validate the **integration and functionality** of two key modules:  

1. **Customer Module**  
   - Conditions to create a new customer (e.g., mandatory fields like Name, Date of Birth, Address, National ID/Passport, Contact Information).  
   - Validation of customer information format and uniqueness (e.g., duplicate National ID not allowed).  
   - Rules for customer modification and deactivation.  
   - How customer details are linked with other modules (such as Account).  

2. **Account Module**  
   - Conditions to open an account (e.g., valid and active customer ID, minimum opening balance, account type selection).  
   - Validation of account number generation and linkage with the customer record.  
   - Rules for account transactions (deposit, withdrawal, transfer) and closure.  
   - Integration checks with the customer profile (account cannot exist without an active customer).  

---

### 🎯 Purpose
These test cases ensure that:
- A **customer must be created successfully** before opening any account.  
- **Business rules and conditions** for both customer and account modules are properly validated.  
- The **integration between Customer and Account modules** works as expected during SIT execution.  



