# leap-year-or-not
n=int(input('Enter year:'))
if n%4==0 and n%100!=0:
    print('Yes')
elif n%400==0:
    print('Yes')
else:
    print('No')
