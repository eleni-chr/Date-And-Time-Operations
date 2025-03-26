# Date-And-Time-Operations

Functions handling date calculations, differences, and calendar-related puzzles.

Functions writted by Dr Eleni Christoforidou in MATLAB.

**day_diff:** The function takes four scalar positive integer inputs. These represent the birthdays of two children who were born in 2015. The function returns a positive integer scalar that is equal to the difference between the ages of the two children in days. If any of the input is invalid, it returns -1.

**day_counter:** The function returns the number of Mondays that fell on the first day of the month in a given year since 1776. The input is the requested year and it can be any year from 1776 onwards. The input must be a positive integer scalar. Note that a leap year occurs on any year evenly divisible by 4, but not on a century unless it is divisible by 400.

**centuries:** The function takes a positive integer smaller than or equal to 3000 representing a year as its input and returns a character array with the
century the given year falls into. If the input is invalid, the function returns the empty character array ''. Centuries are specified using roman numerals (using the shortest legal roman number). Note that a century goes from year 1 to 100, so for example, the XXth century ended on December 31st, 2000.

**year2016:** The function returns a row vector of structs whose elements correspond to the days of a month in 2016 as specified by the input argument. The input argument must be an integer between 1 and 12. If the input is not an integer between 1 and 12, the function returns an empty array. Each struct contains three fields with field names “month”, “date”, and “day”. The month field contains a string with the name of the month. The date field contains a scalar specifying the day of the month. The day field contains the three-letter abbreviation of the day.

**holiday:** The function takes two input arguments that are scalar integers representing a month (1-12) and a day (1-31). The function returns a
logical true if the specified date is a holiday; if not, it returns false. For this funtion, the following dates are considered holidays: January 1st, July 4th, December 25th, and December 31st.
