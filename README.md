python-matters

# Foydalanuvchidan ikki son kiritshni so'rab, 
# kiritilgan sonlarning yig'indisi, ayirmasi, 
# Foydalanuvchidan ikki son kiritshni so'rab,
# kiritilgan sonlarning yig'indisi, ayirmasi,
# ko'paytmasi va bo'linmasini chiqaruvchi dastur
a = int(input("Birinchi sonni kiriting: "))
b = int(input("Ikkinchi sonni kiriting: "))
print(f"{a}+{b}=", a+b)
print(f"{a}-{b}=", a-b)
print(f"{a}x{b}=", a*b)
print(f"{a}/{b}=", a/b)
 
#2
a = int(input("birinchi raqamni kiriting: "))
b = int(input("ikkinchi sonni kiriting: "))
c = int(input("uchinchi sonni kiriting: "))
print(f"{a}+{b}+{c}=", a+b+c)
print(f"{a}-{b}+{c}=", a-b+c)
print(f"{a}+{b}-{c}=", a+b-c)
print(f"{a}-{b}-{c}=", a-b-c)
print(f"{a}x{b}x{c}=", a*b*c)
print(f"{a}x{b}:{c}=", a*b/c)
print(f"{a}:{b}:{c}=", a/b/c)
print(f"{a}:{b}x{c}=", a/b*c)

#3
a = int(input("birinchi sonni kiriting: "))
b = int(input("darajani kiriting: "))
print(f'{a} ning {b} inchi darajasi= ', a**b  )

#4
a = int(input("a tomonni kiriting: "))
b = int(input("b tomonni kiriting: "))
c = int(input("c tomonni kiriting: "))
p = print(f" uchburchak perimetri: P={a}+{b}+{c}=", a+b+c)
