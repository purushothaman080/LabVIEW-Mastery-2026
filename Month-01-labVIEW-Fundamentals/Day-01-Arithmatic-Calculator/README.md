Day 01 – Arithmetic Calculator Using LabVIEW

Project Overview

Developed a four-operation arithmetic calculator using NI LabVIEW 2026.0.

The application performs addition, subtraction, multiplication and division with Enum-based operation selection and division-by-zero error handling.

Software Used

- NI LabVIEW 2026.0

Features

- Addition
- Subtraction
- Multiplication
- Division
- Enum-based operation selection
- Case Structure for operation execution
- Division-by-zero detection
- Custom Error Cluster generation
- Centralized Error Cluster indicator
- Default If Unwired tunnel configuration

Concepts Practised

1. Front Panel and Block Diagram
2. Numeric Controls and Indicators
3. Enum Control
4. Case Structure
5. Comparison Functions
6. Select Function
7. Error Cluster
8. Custom Error Generation
9. Case Structure output tunnels

Error Handling

A denominator validation condition detects division by zero.

When the denominator is zero:

- Status: TRUE
- Error Code: 505
- Source: ERROR: DIVISION BY ZERO

The Error Cluster indicator is placed outside the main Case Structure. The output tunnel uses Default If Unwired to provide the default no-error cluster for cases where it is not wired.

Test Cases

Input A| Input B| Operation| Expected Output
10| 5| ADD| 15
10| 5| SUB| 5
10| 5| MUL| 50
10| 5| DIV| 2
10| 0| DIV| Error 505

Screenshots

Front Panel

"Front Panel" (Screenshots/Front_Panel.png)

Block Diagram

"Block Diagram" (Screenshots/Block_Diagram.png)

Learning Outcome

Practised LabVIEW graphical programming, arithmetic operations, conditional execution, Enum selection and basic error handling.

Status: Completed
Learning Journey: Six-Month LabVIEW Mastery – Day 01