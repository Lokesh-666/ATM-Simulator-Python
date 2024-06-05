# ATM-Simulator-Python

This is a simple ATM banking system implemented in Python. It allows users to check their balance, withdraw money, deposit money, and quit the session.

## Features

- Check account balance.
- Withdraw money from the account.
- Deposit money into the account.
- Quit the session.

## Requirements

To run this program, you need to have Python installed on your system.

## Installation

1. **Install Python:**

   Make sure you have Python installed. You can download and install Python from the official website: [Python.org](https://www.python.org/downloads/).

   To check if Python is already installed, you can run the following command in your terminal or command prompt:

   ```sh
   python --version
   ```

   or

   ```sh
   python3 --version
   ```

2. **Download the Code:**

   Clone or download this repository to your local machine.

   ```sh
   git clone https://github.com/Lokesh-666/ATM-Simulator-Python.git
   ```

   Navigate to the directory where you have saved the code.

   ```sh
   cd ATM-Simulator-Python
   ```

## How to Run the Program

1. Open your terminal or command prompt.
2. Navigate to the directory where the code is saved.
3. Run the following command to start the program:

   ```sh
   python script.py
   ```

   or

   ```sh
   python3 script.py
   ```

## Usage

1. When the program starts, it will welcome you to the ATM of Bank XYZ.
2. It will ask if you have an account at Bank XYZ. Enter 'Y' for yes or 'N' for no.
3. If you choose 'Y', the program will prompt you to enter your account number and a 4-digit PIN.
4. After successful login, you can choose from the following options:
   - **C**: Check Balance
   - **W**: Withdraw
   - **D**: Deposit
   - **Q**: Quit
5. If you choose 'N', it will provide contact information for opening an account.

## Example

```
--------------Welcome to ATM of Bank XYZ---------
Do you have an account at our Bank XYZ?(Y/N) Y
What is your bank account number?
1
What is the 4 digit pin?
1111
1. Check Balance (C)
2. Withdraw (W)
3. Deposit (D)
4. Quit (Q)
What do you choose (w/c/d/q) C
Your Bank Balance is $ 0
1. Check Balance (C)
2. Withdraw (W)
3. Deposit (D)
4. Quit (Q)
What do you choose (w/c/d/q) Q
```

## Notes

- Ensure your inputs for account number and PIN are correct.
- The program will lock for 60 seconds after three incorrect PIN attempts.

## Contributing

If you find any bugs or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License.

---
