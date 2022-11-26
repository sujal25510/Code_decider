def prime_check(n):
    for i in range(2,n):
        if(n%i==0):
            return 0
            break
    return 1
def palindrome_check(n):
    temp=n
    new=0
    while(temp!=0):
        d=temp%10
        new=(new*10)+d
        temp=temp//10
    if(new==n):
        return 1
    else:
        return 0
n=int(input("give the value of n for the nth prime palindrome number:"))
count=0
i=1
while(True):
    if(prime_check(i) and palindrome_check(i)):
        count+=1
        i+=1
        if(count==n):
            print("the nth prime palindrome number is-->",i-1)
            break
    else:
        i+=1
