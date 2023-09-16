# CodeClause_Project-1


# Random Password Generator in Python

This Python script generates a random password using a combination of uppercase letters, lowercase letters, special characters, and numbers.

## Features

- Generates a random and secure password.
- Allows specifying the desired password length.
- Utilizes a variety of character types to enhance security.

## Usage

1. Ensure you have Python 3.8 or a newer version installed.

2. **Install Required Modules**

   Open your terminal or command prompt and run the following commands to install the required modules:

   ```bash
   pip install tkinter
   ```

   For working with SQLite:

   ```bash
   pip install sqlite3
   ```

3. Run the script using `python your_file_name.py`.

4. Follow the on-screen instructions to input a username and desired password length.

5. Click "GENERATE PASSWORD" to create a password.

6. Click "ACCEPT" to store the generated password along with the username in a SQLite database.

7. Click "RESET" to clear the input fields and generated password.

## Code Sample

```python
import string
import random
from tkinter import *
from tkinter import messagebox
import re
import sqlite3

```

## Author

- Saif Ali ([GitHub](https://github.com/Saifali9628))


---
