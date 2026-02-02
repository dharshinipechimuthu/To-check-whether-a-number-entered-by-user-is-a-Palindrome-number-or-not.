# To-check-whether-a-number-entered-by-user-is-a-Palindrome-number-or-not.
print("Enter the Number: ")
num = int(input())
rev = 0
temp = num
while temp>0:
    rem = temp%10
    rev = rem + (rev*10)
    temp = int(temp/10)
if rev==num:
    print("\nIt is a Palindrome Number")
else:
    print("\nIt is not a Palindrome Number")

OUTPUT:

1.
Enter the Number: 
555

It is a Palindrome Number

2.
Enter the Number: 
5432

It is not a Palindrome Number


