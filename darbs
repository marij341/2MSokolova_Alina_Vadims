# Vienkāršs matemātikas tests

jautajumi = {
    "1. Cik ir 5 + 3? ": "8",
    "2. Cik ir 12 - 4? ": "8",
    "3. Cik ir 6 * 2? ": "12",
    "4. Cik ir 16 / 4? ": "4",
    "5. Cik ir 10 % 3? ": "1"
}

pareizas = 0

for jautajums, pareiza_atbilde in jautajumi.items():
    atbilde = input(jautajums)
    if atbilde == pareiza_atbilde:
        print("Pareizi!")
        pareizas += 1
    else:
        print(f"Nepareizi. Pareizā atbilde bija {pareiza_atbilde}.")

print(f"\nTu atbildēji pareizi uz {pareizas} no {len(jautajumi)} jautājumiem.")
