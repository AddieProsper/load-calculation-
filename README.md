# Smart Energy Management System (C++)

This is a console-based C++ project that manages electrical appliances and calculates energy usage and billing.

The system allows users to enter appliance details, calculate energy consumption, generate electricity bills, and save the data into a file.

---

## Project Description

The program was developed step by step. It starts with a simple Appliance class and gradually adds more features like menu system, energy calculation, billing, and file handling.

The system uses Object-Oriented Programming concepts and standard C++ libraries.

---

## Features

- Register appliances
- View all appliances
- Calculate energy consumption (kWh)
- Calculate total energy usage
- Generate electricity bill
- Save data to file
- Load saved data when program starts

---

## How Energy is Calculated

Energy (kWh) = (Power in Watts × Usage Hours per Day) / 1000

---

## How Billing is Calculated

Total Cost = Total Energy × Tariff per kWh

---

## Technologies Used

- C++
- iostream
- vector
- iomanip
- fstream

---

## File Structure

- main.cpp
- appliances.txt (created automatically after running the program)

---

## How to Compile

g++ main.cpp -o energy

## How to Run

Linux / Mac:
./energy

Windows:
energy.exe

---

## Development Progress

Part 1 – Created Appliance class  
Part 2 – Added user input  
Part 3 – Stored multiple appliances using vector  
Part 4 – Added menu system  
Part 5 – Added energy calculation  
Part 6 – Added total energy calculation  
Part 7 – Added billing system  
Part 8 – Added file saving  
Part 9 – Added file loading  
Part 10 – Final complete system  

---

## Purpose

This project was created for academic learning purposes to practice C++ programming, OOP concepts, and file handling.
