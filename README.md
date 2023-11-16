def persamaan_linier(a, b):
    if a == 0:
        print("Bukan persamaan linier.")
        return None
    return -b / a

# Contoh penggunaan:
a = 2
b = -3
solusi = persamaan_linier(a, b)

if solusi is not None:
    print(f"Solusi dari persamaan {a}x + {b} = 0 adalah x = {solusi}")
