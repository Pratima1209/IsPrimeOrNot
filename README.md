#  IsPrimeOrNot


num=int(input("Enter the number to see weather it is Prime or Not"))
if num>1:
  for i in range(2,n):
    if (num%i)==0:
      print("It is not Prime Number")
      break
  else:
    print("It is Prime Number")
else:
  print("It is not Prime Number")

