# ✨ Login Validation Script ✨

This Python script validates a user's login credentials (username and password). It provides user-friendly messages and includes debug statements to help trace the program's execution for debugging purposes. 🔧

## 🔹 Features
- ✅ Verifies username and password against predefined values.
- ❓ Provides specific error messages for incorrect username, incorrect password, or both.
- 🔧 Includes debug statements to trace inputs and decision-making steps.
- 🌟 Uses emoji to enhance user feedback.

## 🔹 How It Works
1. 🔑 The script defines the correct credentials:
   - **Username**: `samar`
   - **Password**: `sarfraz`

2. ⌨️ It prompts the user to enter their username and password.

3. 🔒 The script validates the input:
   - If both username and password are incorrect, it displays an appropriate error message.
   - If only the username is incorrect, it informs the user to check their username.
   - If only the password is incorrect, it prompts the user to check their password.
   - If both are correct, it welcomes the user with a success message.

4. 🔧 Debug statements are included for developers to trace the execution flow and user inputs.

## 🔹 Example Output
### ❌ Invalid Credentials:
```
Please enter your username: test
Please enter your password: wrongpass
🚨❌ Both username and password are incorrect. Please try again. ⚫
[DEBUG] Both username and password did not match the expected values.
```

### ✅ Successful Login:
```
Please enter your username: samar
Please enter your password: sarfraz
🌐 Login successful! Welcome back! 👋😊
You now have access to all the features: 🎉🥳🎈🎁
Welcome, samar! 🎉🥳👋
[DEBUG] User successfully logged in with correct credentials.
```

## 🔹 How to Run
1. 🔧 Ensure you have Python installed on your system.
2. 🗑️ Save the script as `login_validation.py`.
3. 💻 Open a terminal and navigate to the script's location.
4. 🛠️ Run the script using the command:
   ```
   python login_validation.py
   ```

## 🔹 Customization
You can modify the following variables to customize the script:
- **`correct_username`**: Update this variable to change the expected username.
- **`correct_password`**: Update this variable to change the expected password.

## 🔹 Debugging
The script includes `[DEBUG]` print statements to assist in understanding the program's behavior. These statements:
- 🔎 Display the received username and a masked version of the password.
- 🔐 Indicate which validation check failed.
- 🌟 Confirm successful login when credentials are correct.

## ⚖️ License
This project is open-source and available under the **MIT License**.

