# Pihu
Blinel draft one
def calculate_monthly_savings(income, expenses):
savings = income - expenses
return savings

monthly_income = float(input("enter your monthly income: "))
monthly_expenses = float(input('enter your monthly expenses: "))

Monthly_savings = calculate_monthly_savings(monthly_income, Monthly_expenses)
print(f"your monthly savings are: ${monthly_savings:.2f}")
