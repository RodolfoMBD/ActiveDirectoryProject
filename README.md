# Microsoft-Active-Directory (Part_1)
![Static Badge](https://img.shields.io/badge/Active%20Directory-green?style=for-the-badge&logo=AD&logoColor=yellow&labelColor=green)

## Description

The first part of this guided lab is about serving as domain administrators for a fictitious company named Inlanefreight for a day. There are three tasks focused on helping the IT department close some work tickets, by performing actions such as adding and removing users and groups, managing group policy, and creating and deleting OU.

## Languages and Technologies Used


- <b>Windows PowerShell</b>
- <b>Windows AD Users and Computers</b>
- <b>Windows AD Group Management Console</b>
- <b>XFreeRDP</b>

## Environments Used 

- <b>Windows Server 2019</b>
- <b>Parrot OS</b>

## Program walk-through:
<p align="left">
<img width="960" src="https://github.com/user-attachments/assets/00267826-b3fd-459f-bb93-2889f506b6d0";</p>

![task1](https://github.com/user-attachments/assets/6027bcf9-22e4-46aa-961a-c2177827ef7a)

![task1-2](https://github.com/user-attachments/assets/b4973c49-df18-4ca8-8747-11dc09834c75)

![task1-3](https://github.com/user-attachments/assets/b5b445ef-58e4-4a14-9556-aea932cbe0c0)

![task1-4](https://github.com/user-attachments/assets/5234665e-a645-45a8-8c38-f6a5f547db99)

![task1-5](https://github.com/user-attachments/assets/56dedcb4-791f-4e1b-9c33-c8b52e51eb7a)

In this task I was commanded to create AD users for the new onboarding employees, then relocate those new users, and delete ones that are no longer part of the company. As part of this task, I was also told to respond to a security event, a ticket was submitted by an employee who requested a password reset and his account to be unlocked.

![Task2](https://github.com/user-attachments/assets/6c40633e-701f-4b7b-9a83-1df1450c4f37)

![Task2-2](https://github.com/user-attachments/assets/0fa7a680-114c-4056-bdf5-f09de32483cf)

For the second task, I created a new Security Group named Security Analyst, nested it under an OU of the same name, and then moved the new hires to this newly created group.


![Task3](https://github.com/user-attachments/assets/11983cba-328f-478e-aef4-58cb6e239020)

![Task3-2](https://github.com/user-attachments/assets/ba484a66-1266-4771-b2e6-220c0e357ae7)

![Task3-3](https://github.com/user-attachments/assets/8f9d9481-083f-49fb-a24e-df4a68b60e98)

![Task3-4](https://github.com/user-attachments/assets/b1db719a-013a-4674-8b3c-df4ad2f628e5)

![Task3-5](https://github.com/user-attachments/assets/bf424f3d-7d0b-4fd4-9655-acff0b793a66)

![Task3-6](https://github.com/user-attachments/assets/068fd551-1d0a-4c07-9c89-3faf3081c846)

At last, I was directed to create a new GPO named "Security Analyst Control" using the command line, linked it to the recently created OU (Security Analyst), and finally modified the logon banner and password policies.










