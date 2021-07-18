# Find Your Akan Name

by *ismailpervez*

a web application that takes a user's birthday and calculates the day of the week they were born and then depending on their gender outputs their Akan Name
## Description
a web application that takes a user's birthday and calculates the day of the week they were born and then depending on their gender outputs their Akan Name.
Akan names are derived from Ghanian culture. Frequently in Ghana, children are given their first name as a 'day name' which corresponds to the day in the week they were born. Here are Ghanian day names.

### the table below has the akan names with their respective days

|Day        |  male | female|
|-----------|-------|-------|
|sunday     |Kwasi  |Akosua |
|monday     |Kwadwo |Adwoa  |
|tuesday    |Kwabena|Abenaa |
|wednesday  |Yaw    |Akua   |
|thursday   |Kofi   |Yaa    |
|friday     |Kwabena|Afua   |
|saturday   |Kwame  |Ama    |

> A child who asks questions does not become a fool. 

## How to implement this feature

Most people do know when their birthdays are, but some might not know what day of the week they were born. Luckily for us, there are ways to calculate the day of the week from a specific date. The following is one of the many methods that exist for that;

```
Day of the week (d) = ( ( (CC/4) -2*CC-1) + ((5*YY/4) ) + ((26*(MM+1)/10)) + DD ) mod 7
```

 where;

 CC - is the century digits. For example 1989 has CC = 19

 YY - is the Year digits (1989 has YY = 89)

 MM -  is the Month

 DD - is the Day of the month 

 mod - is the modulus function ( % )