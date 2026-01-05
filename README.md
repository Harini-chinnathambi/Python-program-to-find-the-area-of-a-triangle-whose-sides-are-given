pROGRAM


import math
a = float(input("Enter the length of side a: "))
b = float(input("Enter the length of side b: "))
c = float(input("Enter the length of side c: "))
s = (a+b+c)/2
area = math.sqrt(s*(s-a)*(s-b)*(s-c))


print(" Area of the triangle is: ", area)


OUTPUT:

Enter the length of side a: 19
Enter the length of side b: 31
Enter the length of side c: 20
 Area of the triangle is:  183.3030277982336
