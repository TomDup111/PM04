# Payroll System – Mzansi Tech Contractors
## Overview  
This program is a C# WinForms application that calculates contractor salaries. It takes inputs (name, hours worked, dependents) and shows gross pay, deductions, and net pay.
## What It Does  
- **Gross Pay**: Hours × hourly rate (R950).  
- **UIF**: 1% of gross pay.  
- **PAYE**: 25% tax, reduced by dependents.  
- **Membership Fee**: 13% of gross pay.  
- **Total Deduction**: UIF + PAYE + Membership.  
- **Net Pay**: Gross Pay – Total Deduction.  
- Buttons: **Calculate**, **Reset**, **Exit**.
## Testing  
- Unit tests written with **MSTest**.  
- Tests follow the **AAA pattern (Arrange, Act, Assert)**.  
- All payroll formulas tested and passed.
## Validation  
- No empty contractor names.  
- No negative or non‑numeric inputs.  
- Dependents limited to 10.  
- Clear error messages guide the user.
## Files  
- `PayrollCalculator.cs` Payroll formulas.  
- `Form1.cs` User interface and buttons.  
- `PayrollTests.cs` Unit tests.
