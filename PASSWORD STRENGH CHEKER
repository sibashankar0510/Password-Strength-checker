# Simple Password Strength Checker

password = input("Enter your password: ")

score = 0
tips = []

# 1. Check length
if len(password) >= 8:
    score += 1
else:
    tips.append("Use at least 8 characters.")

# 2. Check uppercase letter
if any(c.isupper() for c in password):
    score += 1
else:
    tips.append("Add an uppercase letter (A-Z).")

# 3. Check lowercase letter
if any(c.islower() for c in password):
    score += 1
else:
    tips.append("Add a lowercase letter (a-z).")

# 4. Check number
if any(c.isdigit() for c in password):
    score += 1
else:
    tips.append("Add a number (0-9).")

# 5. Check special character
if any(not c.isalnum() for c in password):
    score += 1
else:
    tips.append("Add a special character (@, #, $, %, *, { , }, ], [ , ],  !).")

# 6. Decide strength
if score == 5:
    strength = "Strong"
elif score >= 3:
    strength = "Medium"
else:
    strength = "Weak"

# 7. Show result
print("\nPassword Strength:", strength)

if strength != "Strong":
    print("Suggestions:")
    for tip in tips:
        print("-", tip)