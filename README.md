# Notes
Repository used for taking notes, and storing small bits of code that don't apply directly to current projects. 

To list .Net runtimes in the .Net CLI:  
```powershell
dotnet --list-runtimes
```

***Python Datetime format examples

```Python
from datetime import datetime

dt = datetime.now()

print(dt)
print('\nDirectives\n--------------')
print(dt.strftime('Weekday short version : %a'))
print(dt.strftime('Weekday full version  : %A'))
print(dt.strftime('Weekday as a number   : %w'))
print(dt.strftime('Day of month          : %d'))
print(dt.strftime('Month Name short ver  : %d'))
print(dt.strftime('Month Name full ver   : %b'))
print(dt.strftime('Month as a number     : %m'))
print(dt.strftime('Year short version    : %y'))
print(dt.strftime('Year full version     : %Y'))
print(dt.strftime('Hour (00-23)          : %H'))
print(dt.strftime('Hour (00-11)          : %I'))
print(dt.strftime('AM/PM                 : %p'))
print(dt.strftime('Minute                : %M'))
print(dt.strftime('Second                : %S'))


print('\nFormatted Date Strings\n--------------')
print(dt.strftime('%a %d-%m-%Y'))
print(dt.strftime('%a %d/%m/%Y'))
print(dt.strftime('%a %d/%m/%y'))
print(dt.strftime('%A %d-%m-%Y, %H:%M:%S'))
print(dt.strftime('%X %x'))

2021-10-04 21:38:43.939054

Directives
--------------
Weekday short version : Mon
Weekday full version  : Monday
Weekday as a number   : 1
Day of month          : 04
Month Name short ver  : 04
Month Name full ver   : Oct
Month as a number     : 10
Year short version    : 21
Year full version     : 2021
Hour (00-23)          : 21
Hour (00-11)          : 09
AM/PM                 : PM
Minute                : 38
Second                : 43

Formatted Date Strings
--------------
Mon 04-10-2021
Mon 04/10/2021
Mon 04/10/21
Monday 04-10-2021, 21:38:43
21:38:43 10/04/21
```
