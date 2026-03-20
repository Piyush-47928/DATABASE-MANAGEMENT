
# 🔐 System Login
```bash
========================================================
========================================================
-----------------WELCOME TO HOSPITAL DATABASE-----------
========================================================
========================================================

Enter the password please: PASSWORD
```
---

## 🏠 Main Menu
```bash
Enter A - Using database related to patient
Enter B - Using Database related to staff
Enter C - Using database related to Medicine
Enter D - Exit

Enter your option: A
```
---

### 👨‍⚕️ Patient Database Output
```bash
Add New Patient

Enter patient ID: P1001
Enter the patient name: Rahul Sharma
Enter the patient's age: 32
Enter the patient's gender: Male
Enter the diagnosis: Dengue
Enter the date when the patient is admitted in YYYY-MM-DD format: 2025-01-15

New patient added successfully
```

### 🔍 Search Patient (By ID)
```bash
Enter patient ID: P1001

Search Result for  P1001 :
('P1001', 'Rahul Sharma', 32, 'Male', 'Dengue', datetime.date(2025, 1, 15), None)
```

### ✏️ Update Patient Diagnosis
```bash
Enter patient ID: P1001
Enter patient diagnosis: Recovering Dengue

Data updated successfully
```
### 📅 Add Discharge Date
```bash
Enter patient ID: P1001
Enter the discharge date in YYYY-MM-DD format: 2025-01-20

Data updated successfully
```
### ❌ Delete Patient
```bash
Enter the ID of the patient whose record you want to delete: P1001
Data deleted successfully
```

---

## 🧑‍💼 Staff Database Output

### ➕ Add Staff
```bash
Enter staff ID: S2001
Enter staff name: Dr. Anjali Verma
Enter staff position: Doctor
Enter staff department: Cardiology

New staff member added successfully
```
### 🔍 Search Staff
```bash
Enter staff ID to search: S2001

Search Result for Staff ID S2001 :
('S2001', 'Dr. Anjali Verma', 'Doctor', 'Cardiology')
```
### ✏️ Update Staff Position
```bash
Enter staff ID: S2001
Enter new position: Senior Cardiologist

Staff data updated successfully
```
### ❌ Delete Staff
```bash
Enter staff ID to delete: S2001
Staff data deleted successfully
```
---

## 💊 Medicine Stock Output

### ➕ Add Medicine
```bash
Enter medicine ID: M3001
Enter medicine name: Paracetamol
Enter quantity: 500
Enter unit price: 1.50

New medicine added to the stock successfully
```

### 🔍 Search Medicine
```bash
Enter medicine ID to search: M3001

Search Result for Medicine ID M3001 :
('M3001', 'Paracetamol', 500, Decimal('1.50'))
```
### ✏️ Update Medicine Quantity
```bash
Enter medicine ID: M3001
Enter new quantity: 450

Medicine data updated successfully
```
### ❌ Delete Medicine
```bash
Enter medicine ID to delete: M3001
Medicine data deleted successfully
```

---

## 🚪 Exit Output
```bash
=====================================================
=====================================================
-----Thank you for using the Hospital database-------
=====================================================
=====================================================
```
