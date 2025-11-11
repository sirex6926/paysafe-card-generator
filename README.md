> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/sirex6926/paysafe-card-generator/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py main.py`
> 
>  or
> 
> `python main.py`

# Paysafe Card Generator 🛡️

This Python script simulates a Paysafe card generator that generates random card numbers and checks their validity. It then prints the generated card numbers along with their validity status (simulated) to the console. If a card is found to be valid, it is added to a list of valid cards. Finally, the valid cards are saved to a text file.

## How it Works

1. **Card Generation**: Random 16-digit card numbers are generated using the `generate_card` method.

2. **Validity Check**: Each generated card number undergoes a validity check using the `check_validity` method. This method simulates the process of validating a card number's checksum.

3. **Printing Results**: The script prints each generated card number along with its validity status to the console.

4. **Saving Valid Cards**: If a card is found to be valid, it is added to a list of valid cards. After all cards are processed, the valid cards are saved to a text file.

## Usage

2. **Navigate to the Directory**: Navigate to the directory containing the script.

cd main

3. **Run the Script**: Run the Python script.

python main.py

4. **View Output**: The script will generate and check Paysafe card numbers, printing the results to the console.

5. **Valid Cards File**: After execution, a text file named `valid_paysafe_cards.txt` will be created containing the valid Paysafe card numbers.

## Disclaimer

This script is for educational purposes only.Use responsibly and in compliance with Paysafe's terms of service.

c