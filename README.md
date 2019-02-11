# Calendar

    step 1: write a main() function to get the year and month from the user.
            call print_month() to print the top part of the calendar defined in step 2
            call month_body() function to print the calendar body which defined in step3
    step 2:	write a print_month() function to display the top part of the calendar. 
            For example, the user input ‘January’ and ‘2019’, the function will print 
                  ‘January 2019’ 
                  '------------'
                  'S M T W T F S'
            in the top of the calendar.
    step 3:	write month_body() function to print the calendar body for specific year and month. 
            Pad proper space before the first day of the month
    step 4:	write getStartDay() function to get the first day of the calendar which is ‘1/1/1800’. 
            call the isLeapyear() function which defined in step 6 to check if the year is leap year or not. 
            Then get the total days from 1/1/1800 to 1/1/year. 
            Get the total days from 1/1/year to month/1/year. 
            Then get the weekday of the day
    step 5:	write getNumberOfDaysInMonth() function to return the number of days in that month
    step 6:	write isLeapyear() function to check if it’s a leap year or not

