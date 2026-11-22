#  clsDate - C++ Date Library

`clsDate` is a C++ library designed to simplify working with dates. It provides a collection of functions for creating, validating, comparing, manipulating, and calculating dates.

The library also supports calendar generation, leap year calculations, business day calculations, and vacation management.

##  Features & Functions

### 1. Constructors
- `clsDate()` - Creates an object using the current system date.
- `clsDate(string Date)` - Creates a date from a string.
- `clsDate(short Day, short Month, short Year)` - Creates a date using day, month, and year.
- `clsDate(short Days, short Year)` - Creates a date using the day number and year.

### 2. Getters & Setters
- `SetDay()` / `GetDay()` - Set or get the day.
- `SetMonth()` / `GetMonth()` - Set or get the month.
- `SetYear()` / `GetYear()` - Set or get the year.

### 3. Date Validation
- `IsLeapYear()` - Checks whether a year is a leap year.
- `NumberOfDaysInMonth()` - Returns the number of days in a month.
- `IsValid()` - Checks whether a date is valid.

### 4. Date Information
- `GetNumberOfDay()` - Returns the day of the week.
- `NameOfMonth()` - Returns the name of a month.
- `GetSystemDate()` - Returns the current system date.
- `NumberOfDaysInYear()` - Returns the number of days in a year.
- `DaysFromTheBeginingOfTheYear()` - Returns the number of days from the beginning of the year.
- `NumberOfUntilDaysToEndWeek()` - Returns the remaining days until the end of the week.
- `NumberOfUntilDaysToEndMonth()` - Returns the remaining days until the end of the month.
- `NumberOfUntilDaysToEndYear()` - Returns the remaining days until the end of the year.

### 5. Calendar
- `MonthCalender()` - Displays a monthly calendar.
- `YearCalender()` - Displays a yearly calendar.

### 6. Date Conversion & Calculation
- `ConvertDaysToDate()` - Converts a day number into a date.
- `OrderOfDateUsingDays()` - Gets the date corresponding to a day number.
- `ConvertDateToDays()` - Calculates the number of days from a given date until today.
- `CalculateAgeFromDate()` - Calculates the number of days from a given date until today.
- `GetDeffirentDays()` - Calculates the difference in days between two dates.

### 7. Date Comparison
- `IsDate1BeforDate2()` - Checks whether the first date is before the second.
- `IsDate1AfterDate2()` - Checks whether the first date is after the second.
- `IsDate1EqualDate2()` - Checks whether two dates are equal.
- `CompareDates()` - Compares two dates and returns Before, Equal, or After.

### 8. Increasing Dates
- `AddDays()` - Adds a number of days to a date.
- `AddOneDay()` - Adds one day.
- `IncreaseDateByOneDay()` - Returns the next date.
- `IncreaseDateOneWeek()` - Adds one week.
- `IncreaseDateXweek()` - Adds multiple weeks.
- `IncreaseOneMonth()` - Adds one month.
- `IncreaseXmonth()` - Adds multiple months.
- `IncreaseXdays()` - Adds multiple days.
- `IncreaseOneYear()` - Adds one year.
- `IncreaseXyear()` - Adds multiple years.
- `IncreaseOneDecade()` - Adds ten years.
- `IncreaseXdecade()` - Adds multiple decades.
- `IncreaseOneCentury()` - Adds one hundred years.
- `IncreaseOneMillennium()` - Adds one thousand years.

### 9. Decreasing Dates
- `DecreaseDateOneDay()` - Subtracts one day.
- `DecreaseDateOneWeek()` - Subtracts one week.
- `DecreaseDateXweek()` - Subtracts multiple weeks.
- `DecreaseDateOneMonth()` - Subtracts one month.
- `DecreaseDateXmonth()` - Subtracts multiple months.
- `DecreaseDateXday()` - Subtracts multiple days.
- `DecreaseOneYear()` - Subtracts one year.
- `DecreaseXyear()` - Subtracts multiple years.
- `DecreaseOneDecade()` - Subtracts ten years.
- `DecreaseXdecade()` - Subtracts multiple decades.
- `DecreaseOneCentury()` - Subtracts one hundred years.
- `DecreaseOneMillennium()` - Subtracts one thousand years.

### 10. Business & Vacation
- `IsLastDayInMonth()` - Checks whether a date is the last day of its month.
- `IsLastMonthInYear()` - Checks whether a month is December.
- `IsEndOfWeek()` - Checks whether a date is at the end of the week.
- `IsBusinessDay()` - Checks whether a date is a business day.
- `CalculateBusinessDay()` - Calculates the number of business days between two dates.
- `CalculateVacationDay()` - Calculates vacation days between two dates.
- `CalculateVacationReturnDate()` - Calculates the vacation return date.

### 11. Utility
- `Print()` - Prints the date.
- `SwapTowDates()` - Swaps two date objects.



## 🎯 Purpose

This library was developed as a C++ programming practice project to demonstrate Object-Oriented Programming concepts and provide reusable functions for date management and calculations.

## 👨‍💻 Author

Developed as a C++ programming practice project.
