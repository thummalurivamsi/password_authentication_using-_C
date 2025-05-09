# Password Authentication Program in C

This is a simple C program that demonstrates a password-protected login system. It reads a password from the user input (with hidden characters) and compares it with a stored password from a file (`password.txt`).

## 📋 Features

- Password input with masking (`*`)
- Password validation using file I/O
- Loop-back on incorrect entry
- Console screen clears before each session

> **Note:** This program is intended for learning purposes. It is not secure for real-world password management.

---

## 🛠️ Requirements

- Windows OS (uses `conio.h` and `system("cls")`)
- C compiler (like GCC or Turbo C)

---

## 📂 Files

| File Name      | Description                              |
|----------------|------------------------------------------|
| `main.c`       | Main source code file                    |
| `password.txt` | Contains the saved password (no spaces)  |

---

## 💡 How It Works

1. The screen is cleared using `system("cls")`.
2. The user is prompted to enter the password. Characters are masked using `*`.
3. The entered password is compared with the password stored in `password.txt`.
4. If the password matches:
   - `LOGIN SUCCESSFUL` message is displayed.
5. If it doesn't match:
   - The user is prompted to try again.

---

## 🔐 Example `password.txt`

630199

*Make sure there are no spaces or newlines after the password.*

---

## 🚫 Security Warnings

- This program **prints the entered and saved passwords** (used for testing only).
- Avoid doing this in a real system.
- Passwords are stored in **plain text** — not secure!

---

## ✅ Future Improvements

- Remove use of `goto` and replace with `while` loop.
- Use encryption (e.g., hashing) for password storage.
- Add user registration feature.
- Add retry limits and lockout after multiple failures.
- Make it cross-platform (remove `conio.h` and `system("cls")`).

---

## 🧑‍💻 Author

This project was created as part of learning file handling, loops, and user input handling in C.

---

## 📸 Output

![Password_authentication_output](https://github.com/user-attachments/assets/23e5db70-333b-4912-acdc-41f8b588297b)


---

## 📄 License

This project is open for educational and personal use.

