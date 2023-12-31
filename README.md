# Wordlist Generator

This repository includes scripts to generate random passwords based on specified criteria, available in both command-line interface (CLI) and graphical user interface (GUI) versions.

## Usage

### Prerequisites
- [Python 3.x](https://www.python.org/downloads/) installed
- Required packages: `argparse`, `os`, `random`, `string`, `tarfile`

### Running the Scripts

1. **Clone the repository:**
    ```bash
    git clone https://github.com/laisoJs/wordlistGen.git
    ```

2. **Navigate to the directory:**
    ```bash
    cd wordlistGen
    ```

3. **Run the CLI script with required arguments:**
    ```bash
    python wordlistGenCLI.py [-h] [-l LENGTH] [-u] [-w] [-n] [-s] [-q QUANTITY] [-o OUTPUT] [--sep SEP] [-z]
    ```
    #### Arguments
    - `-h`, `--help`: Show help message and exit.
    - `-l LENGTH`, `--length LENGTH`: Length of the password (default: 8).
    - `-u`, `--upper`: Include uppercase letters.
    - `-w`, `--lower`: Include lowercase letters.
    - `-n`, `--numbers`: Include numbers.
    - `-s`, `--symbols`: Include symbols.
    - `-q QUANTITY`, `--quantity QUANTITY`: Number of passwords to generate (default: 1).
    - `-o OUTPUT`, `--output OUTPUT`: Output file name (default: passwords.txt).
    - `--sep SEP`: Number of files to create (default: 1).
    - `-z`, `--zip`: Create a .tar.gz file.

### Running the GUI

To run the GUI version (`wordlistGenGUI.py`), execute the following command:

```bash
python wordlistGenGUI.py
```
This project is licensed under the [MIT](https://en.wikipedia.org/wiki/MIT_License) License - see the LICENSE file for details