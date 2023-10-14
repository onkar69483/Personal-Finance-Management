# Personal Finance Management System

## Overview

This C++ Personal Finance Management System is a versatile console-based application designed to help users manage their financial transactions and investments. It offers a range of features for recording income, expenses, and making investments, with built-in calculations for maturity amounts.

## Features

- **User Account**: Create an account with an initial balance.

- **Record Income and Expenses**: Keep track of income and expenses, with balance validation to prevent overspending.

- **Investments**: Invest in two types:
  - **Systematic Investment Plan (SIP)**: Set up monthly investments with calculated maturity amounts.
  - **Fixed Deposit (FD)**: Create fixed deposits with calculated maturity amounts.

- **Record Keeping**: Maintain a history of all transactions and investments.

- **Financial Information**: Check the current balance and view a detailed history of income and expenses.

- **Investment Information**: Monitor the maturity amounts and key investment details.

- **User-Friendly Menu**: Interactive menu for user-friendly operations.

## Getting Started

1. **Clone the Repository**: Clone or download the code from this repository.

2. **Compile the Code**: Use a C++ compiler to build the program.

   ```bash
   g++ main.cpp -o main
   ```

3. **Run the Program**:

   ```bash
   ./main
   ```

4. **Use the Menu**: Follow the on-screen menu to perform operations, record transactions, and make investments.

5. **Exit the Program**: Close the program when you're done.

6. **INPUT and OUTPUT**:
    ```shell-session
       ---Welcome to Finance Management System!!---
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 4
    -----------------------------------
    |        Personal Finance        |
    -----------------------------------
    
    ||--BALANCE--: 2000||
    
    --SAVINGS--:
             Amount         Description
    
    --INVESTMENTS--
             Amount       Duration                Type
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 1
    Enter amount : 35000
    Enter description : salary
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 2
    Enter amount: 5000
    Enter description: shoes
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 4
    -----------------------------------
    |        Personal Finance        |
    -----------------------------------
    
    ||--BALANCE--: 32000||
    
    --SAVINGS--:
             Amount         Description
             Income          35000              salary
        Expenditure           5000               shoes
    
    --INVESTMENTS--
             Amount       Duration                Type
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 3
    
    Which one:
    1. SIP
    2. FD
    0. Go back
    Enter your choice : 1
    Enter amount : 8000
    Enter duration in yrs : 3
    Enter monthly investment amount : 500
    
    Which one:
    1. SIP
    2. FD
    0. Go back
    Enter your choice : 2
    Enter amount : 5000
    Enter duration in yrs : 5
    
    Which one:
    1. SIP
    2. FD
    0. Go back
    Enter your choice : 0
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 3
    
    Which one:
    1. SIP
    2. FD
    0. Go back
    Enter your choice : 0
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 5
    --MATURITY AMOUNTS--||
    
    Investment 1 : 28657.8 Rs
    Info : (type,amount,duration)            SIP           8000              3Amount to be invested monthly: 500
    
    Investment 2 : 7045.59 Rs
    Info : (type,amount,duration)             FD           5000              5
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice : 4
    -----------------------------------
    |        Personal Finance        |
    -----------------------------------
    
    ||--BALANCE--: 19000||
    
    --SAVINGS--:
             Amount         Description
             Income          35000              salary
        Expenditure           5000               shoes
    
    --INVESTMENTS--
             Amount       Duration                Type            SIP           8000              3Amount to be invested monthly: 500
                 FD           5000              5
    
    --OPTIONS--
    1. Record INCOME
    2. Record EXPENDITURE
    3. Make Investment
    4. Finance Information
    5. Investment Information
    0. Exit
    Enter choice :
    
    ```

    
   


## Disclaimer

This finance management system is for educational purposes and doesn't offer real financial advice or services. The interest rates used for investment calculations are fictional. Real financial decisions should be made with professional guidance.

## Class Diagram

![Class Diagram](PersonalFinanceSystem.drawio.png)

## Authors

[Onkar Mendhapurkar](https://github.com/onkar69483)

[Mihir Hebalkar](https://github.com/mihirhebalkar)

[Sachin Mhetre](https://github.com/Sachin-Mhetre)

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to modify and use the code for personal or educational purposes.

## Acknowledgments

- This project was developed as a practical educational exercise.
- Thanks to the C++ community for support and inspiration.
