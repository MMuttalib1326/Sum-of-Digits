# Sum-of-Digits
Python language
def sumofdigit(n):
    assert n>=0 and int(n)==n,'entre a positive integer'
    if n==0:
        return 0 
    else:
        return int(n%10)+ sumofdigit(int(n/10))
print(sumofdigit(123))
