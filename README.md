# FACTORIAL-OF-A-NUMBER-USING-8051-KEIL

**AIM:**

To write and execute Assembly language Program to perform factorial of a number using 8051 keil.
APPARATUS REQUIRED: Personal computer with Keil software

**ALGORITHM:**

• Start  

• Input: Read the number n.  

• Initialize:  

•Set factorial to 1.  

•Set i to 1.  

• Loop: While i is less than or equal to n:  

•Multiply factorial by i.  

•Increment i by 1.  

• Output: Store or print the value of factorial.  

• End

**FLOW CHART:**
<img width="261" height="308" alt="image" src="https://github.com/user-attachments/assets/bffe89f6-3ba9-4294-b817-8b545f680e66" />

**Program:**

ORG 0000H   

MOV A,#04H  

MOV R0,A  

ACALL FACTORIAL  

MOV 40H,A  

SJMP THIN  

FACTORIAL:DEC R0  

CJNE R0,#01H,PRODUCT  

SJMP THICK   

PRODUCT:MOV B,R0  

MUL AB  

ACALL FACTORIAL  

THICK: RET  

THIN:  

END

**Output:**  

<img width="2560" height="1600" alt="Screenshot 2025-09-26 092037" src="https://github.com/user-attachments/assets/a4fe268b-3e43-4c2d-a4b7-b5800a8c4d21" />




**Manual Calculations:**  


![WhatsApp Image 2025-10-27 at 20 57 47_d5b1cd1a](https://github.com/user-attachments/assets/e522b130-9f7d-4c87-8a97-3e527428f4b1)





**Result:**

Thus the factorial of a number using 8051 keil was calculated and shown the output.
