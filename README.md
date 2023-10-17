# <p align="center">𝐌𝐞𝐗𝐄𝐄-402_𝐌𝐄𝐗𝐄-4101_𝐆𝐑𝐎𝐔𝐏-3_𝐌𝐈𝐃𝐓𝐄𝐑𝐌-𝐄𝐗𝐀𝐌𝐈𝐍𝐀𝐓𝐈𝐎𝐍</p>

# <p align="center">🕵️ 𝕾𝖈𝖍𝖔𝖔𝖑 𝕾𝖍𝖔𝖔𝖙𝖎𝖓𝖌𝖘</p>

# 𝕿𝖆𝖇𝖑𝖊 𝖔𝖋 𝕮𝖔𝖓𝖙𝖊𝖓𝖙𝖘✍
- [Description](#description)
- [About the Dataset](#about-the-dataset)
- [Category](#category)
- [Contents](#contents)
  - [Text Functions](#text-functions)
  - [Math Functions](#math-functions)
  - [Logical Functions](#logical-functions)
  - [Information Functions](#information-functions)
  - [Date and Time Functions](#date-and-time-functions)
  - [Lookup Functions](#lookup-functions)
- [Authors](#authors)

# 📚 𝑨𝒃𝒐𝒖𝒕 𝒕𝒉𝒆 𝑫𝒂𝒕𝒂𝒔𝒆𝒕

**Title:** School Shootings

**Author/Publisher:** JOAKIM ARVIDSSON

# 𝑶𝒗𝒆𝒓𝒗𝒊𝒆𝒘
The **School Shootings** dataset is a comprehensive researched project conducted by **The Washington Post**. 
🕵️‍♂️ This year-long investigation goes beyond the mere count of those killed or injured in school shootings, offering a profound understanding of the impact on children's lives.

The investigation primarily focuses on incidents at primary and secondary schools during school hours since the tragic 1999 Columbine High massacre. 🕒 To ensure accuracy, the data was sourced from various reliable channels, including news articles, databases, law enforcement reports, school websites, and direct communication with schools and police. Over 1,000 incidents were reviewed, with a stringent filtering process: only shootings occurring on school campuses before, during, or immediately after classes were included. Incidents involving after-hours events, non-injurious accidental discharges, and private suicides that didn't threaten others were meticulously excluded. Furthermore, shootings at colleges and universities were not part of this dataset.

The Washington Post diligently organized more than 200 qualifying incidents into a comprehensive database for analysis. 📊 They also relied on enrollment and demographic data from the U.S. Education Department to calculate how many children were exposed to gunfire during each school shooting. Importantly, the dataset is maintained and updated regularly to stay current with newly reported school shootings. The creators actively seek assistance to make it as comprehensive as possible and welcome contributions from the community. 🤝

**Contact Information:** If you have information that fits their definition of school shootings since Columbine, you can contribute to this important project by contacting them at [schoolshootings@washpost.com](mailto:schoolshootings@washpost.com). 📧

This dataset is a valuable resource for researchers, policymakers, and anyone interested in understanding the full scope and impact of school shootings on our society. 📈📢

# Category
🏫 School / Students

# Contents

## ➤ _**Text Functions**_
📝Text functions are designed to manipulate and analyze text data. They can be used for tasks such as extracting substrings, converting text to uppercase or lowercase, and finding specific characters or words within a text.

**LEN Function**
- **Description:** Returns the length of the specified string.
- **Syntax:** `=LEN(text)`

**TRIM Function**
- **Description:** Returns a text value with leading and trailing spaces removed.
- **Syntax:** `=TRIM(text)`

**UPPER Function**
- **Description:** Allows you to convert text to all uppercase.
- **Syntax:** `=UPPER(text)`

**LOWER Function**
- **Description:** Allows you to convert text to all lowercase.
- **Syntax:** `=LOWER(text)`

**PROPER Function**
- **Description:** Sets the first character in each word to uppercase and the rest to lowercase.
- **Syntax:** `=PROPER(text)`

**SUBSTITUTE Function**
- **Description:** Replaces a set of characters with another.
- **Syntax:** `=SUBSTITUTE(text, old_text, new_text, [nth_appearance])`
- **Parameters:**
  - `text` - The original string to use for substitution.
  - `old_text` - The existing characters to replace.
  - `new_text` - The new characters to replace `old_text` with.
  - `nth_appearance` - (Optional) The nth appearance of `old_text` to replace. If omitted, all occurrences are replaced.

**REPLACE Function**
- **Description:** Replaces a sequence of characters in a string with another set of characters.
- **Syntax:** `=REPLACE(old_text, start, number_of_chars, new_text)`
- **Parameters:**
  - `old_text` - The original string value.
  - `start` - The position in `old_text` to begin replacing characters.
  - `number_of_chars` - The number of characters to replace in `old_text`.
  - `new_text` - The replacement set of characters.

**FIND Function**
- **Description:** Returns the location of a substring in a string (case-sensitive).
- **Syntax:** `=FIND(substring, string, [start_position])`
- **Parameters:**
  - `substring` - The substring you want to find.
  - `string` - The string to search within.
  - `start_position` - (Optional) The position in the string where the search will start. Default is the beginning.

**LEFT Function**
- **Description:** Allows you to extract a substring from a string, starting from the leftmost character.
- **Syntax:** `=LEFT(text, [number_of_characters])`
- **Parameters:**
  - `text` - The string you wish to extract from it.
  - `number_of_characters` - (Optional) Number of characters to extract from the left. Default is 1.

**RIGHT Function**
- **Description:** Returns the last character(s) in a text string based on the number of characters you specify.
- **Syntax:** `=RIGHT(text, [number_of_characters])`
- **Parameters:**
  - `text` - The string you wish to extract from it.
  - `number_of_characters` - (Optional) Number of characters to extract from the right. Default is 1.

**MID Function**
- **Description:** Extracts a substring from a string, starting at any position.
- **Syntax:** `=MID(text, start_position, number_of_characters)`
- **Parameters:**
  - `text` - The string you wish to extract from it.
  - `start_position` - The position to begin extraction (1-based index).
  - `number_of_characters` - Number of characters to extract (mandatory in worksheet function, optional in VBA).

**CONCATENATE Function**
- **Description:** Allows you to join 2 or more strings together.
- **Syntax:** `=CONCATENATE(text1, [text2, ... text_n])`

## ➤ _**Math Functions**_
🔢Math functions provide a range of mathematical operations, including basic arithmetic (addition, subtraction, multiplication, and division), exponentiation, rounding, and more. These functions are essential for performing numerical computations.

**ABS Function**
- **Description:** Returns the absolute value (modulus) of a supplied number.
- **Syntax:** `ABS(number)`
- **Note:** It removes the minus sign (-) from a negative number.

**SIGN Function**
- **Description:** Returns the sign (+1, -1, or 0) of a supplied number.
- **Syntax:** `SIGN(number)`
- **Note:** 
  - If the number is greater than zero, the SIGN function returns 1.
  - If the number is equal to zero, the SIGN function returns 0.
  - If the number is less than zero, the SIGN function returns -1.

**GCD Function**
- **Description:** Returns the Greatest Common Divisor of two or more supplied numbers.
- **Syntax:** `GCD(number1, number2, ...)`
- **Note:** It's used to find the largest positive integer that divides the numbers without a remainder.

**LCM Function**
- **Description:** Returns the Least Common Multiple of two or more supplied numbers.
- **Syntax:** `LCM(number1, number2, ...)`
- **Note:** It calculates the smallest integer that can be divided by all the provided numbers.

**SUM Function**
- **Description:** Returns the sum of a supplied list of numbers.
- **Syntax:** `SUM(number1, number2, ...)`

**PRODUCT Function**
- **Description:** Returns the product of a supplied list of numbers.
- **Syntax:** `PRODUCT(number1, number2, ...)`

**POWER Function**
- **Description:** Returns the result of a given number raised to a supplied power.
- **Syntax:** `POWER(number, power)`
- **Note:** Works like an exponent in a standard math equation.

**SQRT Function**
- **Description:** Returns the positive square root of a given number.
- **Syntax:** `SQRT(number`
- **Note:** Returns an error if the number is negative.

**QUOTIENT Function**
- **Description:** Returns the integer portion of a division between two supplied numbers.
- **Syntax:** `QUOTIENT(numerator, denominator)`

**MOD Function**
- **Description:** Returns the remainder from a division between two supplied numbers.
- **Syntax:** `MOD(number, divisor)`
- **Note:** The result of MOD carries the same sign as the divisor.

**AGGREGATE Function**
- **Description:** Performs a specified calculation (e.g., sum, product, average, etc.) for a list or database, with the option to ignore hidden rows and error values.
- **Syntax:** `AGGREGATE(function_num, options, range)`
- **List of AGGREGATE Functions:**
  - Average, Count, Counta, Countblank, Min, Max, Sum, Median, Large, Small, Product

**AVERAGE Function**
- **Description:** Calculates the average (arithmetic mean) of supplied numbers.
- **Syntax:** `AVERAGE(number1, number2, ...)`

**SUBTOTAL Function**
- **Description:** Performs a specified calculation (e.g., sum, product, average, etc.) for a supplied set of values.
- **Syntax:** `SUBTOTAL(function_num, range)`

**COUNT Function**
- **Description:** Returns the count of values that are numbers.
- **Syntax:** `COUNT(value1, value2, ...)`
- **Note:** Values can be constants, cell references, or ranges.

**COUNTA Function**
- **Description:** Returns the count of cells that contain numbers, text, logical values, error values, and empty text (" ").
- **Syntax:** `COUNTA(value1, value2, ...)`
- **Note:** Does not count empty cells.

**COUNTBLANK Function**
- **Description:** Returns a count of empty cells in a range. Cells that contain text, numbers, errors, etc., are not counted. Formulas that return empty text are counted.
- **Syntax:** `COUNTBLANK(range)`

**MIN Function**
- **Description:** Returns the smallest value from a set of data.
- **Syntax:** `MIN(number1, number2, ...)`

**MAX Function**
- **Description:** Returns the largest value from a supplied set of numeric values.
- **Syntax:** `MAX(number1, number2, ...)`

**MEDIAN Function**
- **Description:** Returns the middle value in a group of numbers.
- **Syntax:** `MEDIAN(number1, number2, ...)`
- **Note:** Handles odd and even numbers of values.

**LARGE Function**
- **Description:** Returns numeric values based on their position in a list when sorted by value. It can retrieve "nth largest" values.
- **Syntax:** `LARGE(range, k)`

**SMALL Function**
- **Description:** Returns numeric values based on their position in a list ranked by value. It can retrieve "nth smallest" values.
- **Syntax:** `SMALL(range, k)`

**PRODUCT Function**
- **Description:** Returns the product of numbers provided as arguments.
- **Syntax:** `PRODUCT(number1, number2, ...)`

**SUBTOTAL Function**
- **Description:** Returns an aggregate result for supplied values. Can return a SUM, AVERAGE, COUNT, MAX, and others. Can either include or exclude values in hidden rows.
- **Syntax:** `SUBTOTAL(function_num, range)`

**CEILING Function**
- **Description:** Rounds a number away from zero to a multiple of significance.
- **Syntax:** `CEILING(number, significance)`

**FLOOR Function**
- **Description:** Rounds a number towards zero to a multiple of significance.
- **Syntax:** `FLOOR(number, significance)`

**EVEN Function**
- **Description:** Rounds a number away from zero to the next even number.
- **Syntax:** `EVEN(number)`

**ODD Function**
- **Description:** Rounds a number away from zero to the next odd number.
- **Syntax:** `ODD(number)`

**ROUND Function**
- **Description:** Rounds a number up or down to a given number of digits.
- **Syntax:** `ROUND(number, num_digits)`

**TRUNC Function**
- **Description:** Truncates a number towards zero to the nearest integer.
- **Syntax:** `TRUNC(number, [num_digits])`

## ➤ _**Logical Functions**_
❓Logical functions enable you to make decisions and perform comparisons in your code. They include functions like IF, AND, OR, and NOT, which help evaluate conditions and determine the flow of your program based on true or false outcomes.

**IF Function**
- **Description:** Returns one value if the condition is TRUE, or another value if the condition is FALSE.
- **Syntax:** `IF(condition, value_if_true, [value_if_false])`

**AND Function**
- **Description:** Returns TRUE if all arguments evaluate to TRUE; otherwise, it returns FALSE.
- **Syntax:** `AND(condition1, [condition2], ...)`

**OR Function**
- **Description:** Returns TRUE if any of the conditions are true and returns FALSE if all conditions are false.
- **Syntax:** `OR(condition1, [condition2, ...condition_n])`

**NOT Function**
- **Description:** Checks if one value is not equal to another. Returns TRUE if the input is FALSE and vice versa.
- **Syntax:** `NOT(logical)`

**XOR Function**
- **Description:** Introduced in Excel 2013, it's a logical "exclusive OR" function.
- **Syntax:** `XOR(logical1, [logical2], ...)`
- **Note:** Returns TRUE if one of the statements is true and FALSE if both statements are true. If neither statement is true, it also returns FALSE.

**ISBLANK Function**
- **Description:** Returns one value if the condition is TRUE, or another value if the condition is FALSE.
- **Syntax:** `IF(condition, value_if_true, [value_if_false])`

**IFERROR Function**
- **Description:** Returns an alternate value if a formula results in an error.
- **Syntax:** `IFERROR(value, value_if_error)`
- **Note:** Checks for errors like #N/A, #VALUE!, #REF!, #DIV/0!, #NUM!, #NAME?, or #.

**SUMIF Function**
- **Description:** Sums the values in a range that meet specified criteria.
- **Syntax:** `SUMIF(range, criteria, [sum_range])`
- **Parameters:**
  - `range` - The range of cells to evaluate by criteria.
  - `criteria` - A number, expression, cell reference, text, or function defining which cells to add.

**COUNTIF Function**
- **Description:** Counts the number of cells that meet a given criterion.
- **Syntax:** `COUNTIF(range, criteria)`
- **Note:** Specify where to look and what to look for.

**IFNA Function**
- **Description:** Returns an alternate value if a formula results in a #N/A error.
- **Syntax:** `IFNA(value, value_if_na)`

## ➤ _**Information Functions**_
📋Information functions are used to extract information about various aspects of your data or system. This can include functions for retrieving file or cell information, counting items, and determining the type of data in a cell.

**ISERROR Function**
- **Description:** Returns TRUE for any error type generated by Excel, including #N/A, #VALUE!, #REF!, #DIV/0!, #NUM!, #NAME?, or #NULL.
- **Syntax:** `ISERROR(value)`

**ISERR Function**
- **Description:** Returns TRUE for any error type except the #N/A error.
- **Syntax:** `ISERR(value)`

**ISNA Function**
- **Description:** Returns TRUE when a cell contains the #N/A error and FALSE for any other value or error type.
- **Syntax:** `ISNA(value)`

**ERROR.TYPE Function**
- **Description:** Returns a number corresponding to a specific error value. Useful for testing specific kinds of errors. If no error exists, ERROR.TYPE returns #N/A.
- **Syntax:** `ERROR.TYPE(value)`

**ISNUMBER Function**
- **Description:** Returns TRUE when a cell contains a number and FALSE if not.
- **Syntax:** `ISNUMBER(value)`

**ISEVEN Function**
- **Description:** Returns TRUE when a numeric value is even and FALSE for odd numbers. It returns a #VALUE error when the value is not numeric.
- **Syntax:** `ISEVEN(value)`

**ISODD Function**
- **Description:** Returns TRUE when a numeric value is odd and FALSE for even numbers. It returns a #VALUE error when the value is not numeric.
- **Syntax:** `ISODD(value)`

**ISBLANK Function**
- **Description:** Returns TRUE when a cell is empty and FALSE when it's not.
- **Syntax:** `ISBLANK(value)`

**ISLOGICAL Function**
- **Description:** Returns TRUE when a cell contains the logical values TRUE or FALSE and returns FALSE for cells with any other value, including empty cells.
- **Syntax:** `ISLOGICAL(value)`

**ISTEXT Function**
- **Description:** Returns TRUE when a cell contains text and FALSE if not.
- **Syntax:** `ISTEXT(value)`

**ISNONTEXT Function**
- **Description:** Returns TRUE for non-text values, such as numbers, dates, times, etc. It also returns TRUE for blank cells and cells with formulas that return non-text results.
- **Syntax:** `ISNONTEXT(value)`

**ISREF Function**
- **Description:** Returns TRUE when a cell contains a reference or space and FALSE if not. Useful for checking if a cell contains a valid reference.
- **Syntax:** `ISREF(value)` 

**ISFORMULA Function**
- **Description:** Returns TRUE when a cell contains a formula and FALSE if not. It considers the presence of a formula, regardless of its output or error conditions.
- **Syntax:** `ISFORMULA(value)`

**TYPE Function**
- **Description:** Returns a numeric code representing the "type" in 5 categories: number (1), text (2), logical (4), error (16), and array (64). Useful when a formula's operation depends on the type of value in a particular cell.
- **Syntax:** `TYPE(value)`

## ➤ _**Date and Time Functions**_
📅Date and time functions are crucial for working with temporary data. They allow you to calculate time differences, format dates, extract components like days or months, and perform data-based calculations.

**DATE Function**
- **Description:** Creates a valid date from year, month, and day components.
- **Syntax:** `DATE(year, month, day)`

**TIME Function**
- **Description:** Creates a time with hour, minute, and second components.
- **Syntax:** `TIME(hour, minute, second)`

**DATEVALUE Function**
- **Description:** Converts text in a recognized format (e.g., a number, date, or time format) into a numeric value.
- **Syntax:** `DATEVALUE("year-month-day")`

**TIMEVALUE Function**
- **Description:** Converts a time represented as text into a proper Excel time.
- **Syntax:** `TIMEVALUE("time_text")`

**NOW Function**
- **Description:** Returns the current date and time, updated continuously when a worksheet is changed or opened.
- **Syntax:** `NOW()`

**TODAY Function**
- **Description:** Returns the current date, updated continuously when a worksheet is changed or opened.
- **Syntax:** `TODAY()`

**HOUR Function**
- **Description:** Returns the hour component of a time as a number between 0 and 23.
- **Syntax:** `HOUR(serial_number)`

**MINUTE Function**
- **Description:** Extracts the minute component of a time as a number between 0 and 59.
- **Syntax:** `MINUTE(serial_number)`

**SECOND Function**
- **Description:** Returns the second component of a time as a number between 0 and 59.
- **Syntax:** `SECOND(serial_number)`

**DAY Function**
- **Description:** Returns the day of the month as a number between 1 and 31 from a given date.
- **Syntax:** `DAY(serial_number)`

**MONTH Function**
- **Description:** Extracts the month from a given date as a number between 1 and 12.
- **Syntax:** `MONTH(serial_number)`

**YEAR Function**
- **Description:** Returns the year component of a date as a 4-digit number.
- **Syntax:** `YEAR(serial_number)`

**WEEKNUM Function**
- **Description:** Takes a date and returns a week number (1 to 54) that corresponds to the week of the year, starting with the week containing January 1.
- **Syntax:** `WEEKNUM(serial_number)`

**WEEKDAY Function**
- **Description:** Takes a date and returns a number between 1 and 7, representing the day of the week. By default, it counts Sunday as 1 and Saturday as 7.
- **Syntax:** `WEEKDAY(serial_number, [return_type])`

**EDATE Function**
- **Description:** Returns a date on the same day of the month, n months in the past or future.
- **Syntax:** `EDATE(start_date, months)`

**EOMONTH Function**
- **Description:** Returns the last day of the month.
- **Syntax:** `EOMONTH(start_date, months)`

**WORKDAY Function**
- **Description:** Takes a date and returns the nearest working day in the future or past. Useful for calculating ship dates, delivery dates, and completion dates.
- **Syntax:** `WORKDAY(start_date, days, [holidays])`

**WORKDAY.INTL Function**
- **Description:** Similar to WORKDAY but allows customization of weekend days. You can specify which days are considered weekends.
- **Syntax:** `WORKDAY.INTL(start_date, days, [weekend], [holidays])`

**DAYS Function**
- **Description:** Returns the number of days between two dates.
- **Syntax:** `DAYS(end_date, start_date)`

## ➤ _**Lookup Functions**_
🔍Lookup functions are used to search for specific values in a data set. They can be used to search for values within tables, arrays, or lists and return related information or values based on the search criteria.
  
## Authors
🤓 **Angela Heizel Abraham**

🤓 **Jhodielen Marabi**

🤓 **Nikkita Andrea Roxas**
