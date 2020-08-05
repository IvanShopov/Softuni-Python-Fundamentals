def password_validator(password):
    checks = []
    isValid = True
    if not 6 <= len(password) <= 10:
        checks.append("Password must be between 6 and 10 characters")
        isValid = False
    for symbol in password:
        if not symbol.isalnum():
            checks.append("Password must consist only of letters and digits")
            isValid = False
            break
    counter_of_digits = 0
    for symbol in password:
        if symbol.isdigit():
            counter_of_digits += 1
    if counter_of_digits < 2:
        isValid = False
        checks.append("Password must have at least 2 digits")
    if isValid:
        print("Password is valid")
    else:
        for message in checks:
            print(f"{message}")


password = input()
password_validator(password)
