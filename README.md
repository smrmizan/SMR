# SMR#leap year check

year = int(input('Enter a year: '))
if year%4==0:
    print('leap year')
elif year%100==0 and year%400==0:
    print('leap year')
    
else:
        print('Not a leap Year')
        
