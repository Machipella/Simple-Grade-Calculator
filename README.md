# Simple-Grade-Calculator
A simple python script that calculates grades.
print("Grade Calculator")
subject = input("Enter the subject name: ")
score = float(input("Enter your score (0-100): "))
if score >= 90:
    grade = 'A'
elif score >= 80:
    grade = 'B'
elif score >= 70:
    grade = 'C'
elif score >= 60:
    grade = 'D'
else:
    grade = 'F'
print(f"Your grade in {subject} is: {grade}")



