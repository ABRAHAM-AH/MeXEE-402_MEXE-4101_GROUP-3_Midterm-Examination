# <p align="center">MeXEE-402_MEXE-4101_GROUP-3_MIDTERM-EXAMINATION</p>

# <p align="center">🕵️ School Shootings</p>

**Table of Contents**
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

# 📚 About the Dataset

**Title:** School Shootings

**Author/Publisher:** JOAKIM ARVIDSSON

## Overview
The **School Shootings** dataset is a comprehensive and meticulously researched project conducted by **The Washington Post**. 
🕵️‍♂️ This year-long investigation goes beyond the mere count of those killed or injured in school shootings, offering a profound understanding of the impact on children's lives.

The investigation primarily focuses on incidents at primary and secondary schools during school hours since the tragic 1999 Columbine High massacre. 🕒 To ensure accuracy, the data was sourced from various reliable channels, including news articles, databases, law enforcement reports, school websites, and direct communication with schools and police. Over 1,000 incidents were reviewed, with a stringent filtering process: only shootings occurring on school campuses before, during, or immediately after classes were included. Incidents involving after-hours events, non-injurious accidental discharges, and private suicides that didn't threaten others were meticulously excluded. Furthermore, shootings at colleges and universities were not part of this dataset.

The Washington Post diligently organized more than 200 qualifying incidents into a comprehensive database for analysis. 📊 They also relied on enrollment and demographic data from the U.S. Education Department to calculate how many children were exposed to gunfire during each school shooting. Importantly, the dataset is maintained and updated regularly to stay current with newly reported school shootings. The creators actively seek assistance to make it as comprehensive as possible and welcome contributions from the community. 🤝

**Contact Information:** If you have information that fits their definition of school shootings since Columbine, you can contribute to this important project by contacting them at [schoolshootings@washpost.com](mailto:schoolshootings@washpost.com). 📧

This dataset is a valuable resource for researchers, policymakers, and anyone interested in understanding the full scope and impact of school shootings on our society. 📈📢

## Category
🏫 School / Students

## Contents
  ➤ _**Text Functions**_
 
  📝Text functions are designed to manipulate and analyze text data. They can be used for tasks such as extracting substrings, converting text to uppercase or lowercase, and finding specific characters or words within a text.

## LEN Function
- **Description:** Returns the length of the specified string.
- **Syntax:** `=LEN(text)`

## TRIM Function
- **Description:** Returns a text value with leading and trailing spaces removed.
- **Syntax:** `=TRIM(text)`

## UPPER Function
- **Description:** Allows you to convert text to all uppercase.
- **Syntax:** `=UPPER(text)`

## LOWER Function
- **Description:** Allows you to convert text to all lowercase.
- **Syntax:** `=LOWER(text)`

## PROPER Function
- **Description:** Sets the first character in each word to uppercase and the rest to lowercase.
- **Syntax:** `=PROPER(text)`

## SUBSTITUTE Function
- **Description:** Replaces a set of characters with another.
- **Syntax:** `=SUBSTITUTE(text, old_text, new_text, [nth_appearance])`
- **Parameters:**
  - `text` - The original string to use for substitution.
  - `old_text` - The existing characters to replace.
  - `new_text` - The new characters to replace `old_text` with.
  - `nth_appearance` - (Optional) The nth appearance of `old_text` to replace. If omitted, all occurrences are replaced.

## REPLACE Function
- **Description:** Replaces a sequence of characters in a string with another set of characters.
- **Syntax:** `=REPLACE(old_text, start, number_of_chars, new_text)`
- **Parameters:**
  - `old_text` - The original string value.
  - `start` - The position in `old_text` to begin replacing characters.
  - `number_of_chars` - The number of characters to replace in `old_text`.
  - `new_text` - The replacement set of characters.

## FIND Function
- **Description:** Returns the location of a substring in a string (case-sensitive).
- **Syntax:** `=FIND(substring, string, [start_position])`
- **Parameters:**
  - `substring` - The substring you want to find.
  - `string` - The string to search within.
  - `start_position` - (Optional) The position in the string where the search will start. Default is the beginning.

## LEFT Function
- **Description:** Allows you to extract a substring from a string, starting from the leftmost character.
- **Syntax:** `=LEFT(text, [number_of_characters])`
- **Parameters:**
  - `text` - The string you wish to extract from it.
  - `number_of_characters` - (Optional) Number of characters to extract from the left. Default is 1.

## RIGHT Function
- **Description:** Returns the last character(s) in a text string based on the number of characters you specify.
- **Syntax:** `=RIGHT(text, [number_of_characters])`
- **Parameters:**
  - `text` - The string you wish to extract from it.
  - `number_of_characters` - (Optional) Number of characters to extract from the right. Default is 1.

## MID Function
- **Description:** Extracts a substring from a string, starting at any position.
- **Syntax:** `=MID(text, start_position, number_of_characters)`
- **Parameters:**
  - `text` - The string you wish to extract from it.
  - `start_position` - The position to begin extraction (1-based index).
  - `number_of_characters` - Number of characters to extract (mandatory in worksheet function, optional in VBA).

## CONCATENATE Function
- **Description:** Allows you to join 2 or more strings together.
- **Syntax:** `=CONCATENATE(text1, [text2, ... text_n])`

  ➤ _**Math Functions**_
  
  🔢Math functions provide a range of mathematical operations, including basic arithmetic (addition, subtraction, multiplication, and division), exponentiation, rounding, and more. These functions are essential for performing numerical computations.
  
  ➤ _**Logical Functions**_
  
  ❓Logical functions enable you to make decisions and perform comparisons in your code. They include functions like IF, AND, OR, and NOT, which help evaluate conditions and determine the flow of your program based on true or false outcomes.
  
  ➤ _**Information Functions**_
 
  📋Information functions are used to extract information about various aspects of your data or system. This can include functions for retrieving file or cell information, counting items, and determining the type of data in a cell.
  
  ➤ _**Date and Time Functions**_
 
  📅Date and time functions are crucial for working with temporary data. They allow you to calculate time differences, format dates, extract components like days or months, and perform data-based calculations.
  
  ➤ _**Lookup Functions**_
 
  🔍Lookup functions are used to search for specific values in a data set. They can be used to search for values within tables, arrays, or lists and return related information or values based on the search criteria.
  
## Authors
🤓 **Angela Heizel Abraham**

🤓 **Jhodielen Marabi**

🤓 **Nikkita Andrea Roxas**
