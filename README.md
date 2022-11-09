# Python-Programs
from datetime import date
birth_day = int(input("Enter Your Day of birth :"))
birth_month = int(input("Enter your Month of birth :"))
birth_yr = int(input("Enetr your year of birth :"))

age_day  = date.today().day - birth_day
age_month = date.today().month - birth_month
age_year = date.today().year - birth_yr

print(f"Your age is - {age_year} years {age_month} months {age_day} day")
