def calculate_future_value(principal, annual_rate, years):
    
rate = annual_rate / 100
    
   
future_value = principal * (1 + rate)**years
    
return future_value
principal_amount = float(input("Enter the principal amount: "))
annual_interest_rate = float(input("Enter the annual interest rate (in %): "))
investment_period = int(input("Enter the number of years: "))

result = calculate_future_value(principal_amount, annual_interest_rate, investment_period)
print(f"The future value of your investment will be: ${result:.2f}")


