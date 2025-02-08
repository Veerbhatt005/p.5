def is leap_year (year):

if (year % 4== 0 and year % 100 != 0) or (year % 400 == 0):

return True

else:

return False

input year int (input("Enter a year: "))

if input_year <= 0:

raise ValueError("Please enter a valid positive year.")

if is leap year (input year):

print("{} is a leap year.".format(input_year))

else:

print("{} is not a leap year.".format(input_year))
