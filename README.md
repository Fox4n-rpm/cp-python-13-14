#13

def quadraticFormula1(a, b, c):
    discriminant = b**2 - 4*a*c
    if discriminant < 0:
        return "none"
    elif discriminant == 0:
        return "1 root"
    else:
        return "2 roots"

def quadraticFormula2(a, b, c):
    discriminant = b**2 - 4*a*c
    if discriminant > 0:
        return "2 roots"
    elif discriminant == 0:
        return "1 root"
    else:
        return "none"
    
print(quadraticFormula1(1, 4, 2))
print(quadraticFormula2(2, 5, 9))

# 14

def bio(name, age, pronoun):
    age = 2024 - age
    print(f"{name.capitalize()} was born in {age}.")
    print(f"{pronoun.capitalize()} is {age} years old.")
    print(f"We are pleased to know {pronoun.lower()}")

bio("stephen", 1984, "he")
bio("mary", 1990, "she")
bio("jane", 2000, "she")

quit()





