# HALF_SUBTRACTOR
# AIM:
To simulate and synthesis Half subtractor using Vivado software.
# APPARATUS REQUIRED:
Vivado 2023.1 software.
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)
# Program:
     module Half_Subtractor(output D, Bo, input A, B);
     assign D = A ^ B;
     assign Bo = ~A & B;
     endmodule
# Elaborated Design:
<img width="960" alt="Screenshot 2024-03-25 215559" src="https://github.com/DeepanAnbazhagan/HALF_SUBTRACTOR/assets/164902865/d194f3a7-c7a6-421d-b234-22872ffabad1">

# Output:
<img width="960" alt="Screenshot 2024-03-25 215645" src="https://github.com/DeepanAnbazhagan/HALF_SUBTRACTOR/assets/164902865/7c08557b-9634-4148-8913-f0e2eb5a40af">

# RESULT:
Thus the simulate and synthesis  Half subtractor verified successfully by using Vivado software.

