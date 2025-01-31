import random
contras = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
contra = (input("Introduce una contrasena: "))
pasword = ""
for i in range(contra) :
    pasword =+ random(contras)
    print("tu contra: ", pasword)
