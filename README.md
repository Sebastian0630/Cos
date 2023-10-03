# Cos
Oto odpowiedzi do zadań:

1. Wyświetl liczby od 1 do 10:
```
for liczba in range(1, 11):
    print(liczba)
```

2. Oblicz sumę liczb od 1 do 100:
```
suma = sum(range(1, 101))
print(suma)
```

3. Wyświetl wszystkie parzyste liczby od 1 do 50:
```
for liczba in range(2, 51, 2):
    print(liczba)
```

4. Oblicz iloczyn liczb od 1 do 5:
```
iloczyn = 1
for liczba in range(1, 6):
    iloczyn *= liczba
print(iloczyn)
```

5. Wyświetl odwróconą wersję napisu "Hello World!":
```
napis = "Hello World!"
odwrocony_napis = napis[::-1]
print(odwrocony_napis)
```

6. Wyświetl wszystkie litery z podanego słowa:
```
slowo = "Przyklad"
for litera in slowo:
    print(litera)
```

7. Oblicz sumę elementów listy liczb:
```
lista = [1, 2, 3, 4, 5]
suma = sum(lista)
print(suma)
```

8. Wyświetl wszystkie liczby od 20 do 30, które są podzielne przez 3:
```
for liczba in range(20, 31):
    if liczba % 3 == 0:
        print(liczba)
```

9. Znajdź największą liczbę w liście:
```
lista = [10, 5, 8, 15, 3]
najwieksza = max(lista)
print(najwieksza)
```

10. Wyświetl wszystkie liczby od 1 do 100, które są podzielne jednocześnie przez 3 i 5:
```
for liczba in range(1, 101):
    if liczba % 3 == 0 and liczba % 5 == 0:
        print(liczba)
```

11. Oblicz średnią arytmetyczną z listy liczb:
```
lista = [10, 20, 30, 40, 50]
srednia = sum(lista) / len(lista)
print(srednia)
```

12. Wyświetl wszystkie litery z podanego zdania, pomijając spacje:
```
zdanie = "To jest przykład zdania."
for litera in zdanie:
    if litera != ' ':
        print(litera)
```

13. Oblicz silnię liczby podanej przez użytkownika:
```
import math

liczba = int(input("Podaj liczbę: "))
silnia = math.factorial(liczba)
print(silnia)
```

14. Wyświetl tabliczkę mnożenia (od 1 do 20):
```
for i in range(1, 21):
    for j in range(1, 21):
        print(i * j, end="\t")
    print()
```

15. Sprawdź, czy podane słowo jest palindromem:
```
slowo = input("Podaj słowo: ")
if slowo == slowo[::-1]:
    print("To jest palindrom.")
else:
    print("To nie jest palindrom.")
```

16. Zamień wszystkie litery w podanym napisie na wielkie litery:
```
napis = "Hello World!"
napis_wielkimi = napis.upper()
print(napis_wielkimi)
```

17. Wyświetl liczby od 1 do 10 w odwrotnej kolejności:
```
for liczba in range(10, 0, -1):
    print(liczba)
```
