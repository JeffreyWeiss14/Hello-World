# Hello-World
How to run a student loan python program

years = int(input("Number of years: "))
amt_per_year = float(input("Loan amount per year: "))
interest_rate = float(input("Interest rate (Ex. 0.045 for 4.5% annual): "))
total_owed = 0
x=0
while (x < years) :
    total_owed += amt_per_year
    total_owed *= (1 + interest_rate)
    print("Total Owed:", total_owed)
    x += 1
