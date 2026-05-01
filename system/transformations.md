# Transformations

Transformacje opisują, w jaki sposób jednostki NP zmieniają aktywny region, jego strukturę, wypełnienie lub geometrię.  
Są to operacje, które przekształcają przestrzeń pól, ale nie tworzą nowych jednostek — działają na tym, co już istnieje.

---

## 1. Transformacje podziału (splity S007–S019)
Podziały są podstawową formą transformacji przestrzeni.

### Typy podziałów:
- pionowy (lewo/prawo),
- poziomy (góra/dół),
- podział na cztery ćwiartki,
- diagonalny (trójkąty),
- łukowy (zewnętrzny i wewnętrzny).

### Efekt transformacji:
- aktywny region zostaje zastąpiony nowymi podregionami,
- każdy podregion staje się niezależną przestrzenią operacji,
- dalsze działania dotyczą tylko wybranego podregionu.

---

## 2. Transformacje zakresu (pointery S022–S027)
Pointery nie zmieniają geometrii, ale zmieniają **zakres działania**.

### Efekt transformacji:
- określają, które sektory (okna) należą do danego S006,
- tworzą logiczny zakres operacji,
- pozwalają wykonywać transformacje w wielu oknach jednocześnie.

---

## 3. Transformacje dziedziczenia (kolor, grubość, stan)
Tokeny S050 i S051 tworzą transformacje stanu.

### Efekt transformacji:
- stan (kolor, grubość) przechodzi w dół drzewa pól,
- lokalny token nadpisuje stan nadrzędny,
- brak tokenu oznacza dziedziczenie.

To jest transformacja **logiczna**, nie geometryczna.

---

## 4. Transformacje wyboru pola (S028–S032)
Jednostki wyboru pola zmieniają aktywny kontekst dla linii.

### Efekt transformacji:
- wskazują konkretne podpole,
- przenoszą operacje rysujące do wybranego regionu,
- zmieniają punkt odniesienia dla geometrii.

---

## 5. Transformacje środka (S033)
S033 ustawia środek pola jako punkt odniesienia.

### Efekt transformacji:
- zmienia układ współrzędnych lokalnych,
- wpływa na położenie linii, łuków i punktów,
- redefiniuje geometrię w obrębie pola.

---

## 6. Transformacje wypełnienia (S051)
Tokeny koloru mogą działać jako transformacje wypełnienia.

### Efekt transformacji:
- zmieniają kolor aktywnego regionu,
- mogą działać przed lub po podziale,
- tworzą hierarchię wypełnień.

---

## 7. Transformacje gradientowe (S067–S074)
Gradienty przekształcają wypełnienie regionu w sposób ciągły.

### Efekt transformacji:
- tworzą przejścia tonalne,
- działają na całym aktywnym regionie,
- nadpisują wcześniejsze wypełnienia.

---

## 8. Transformacje punktowe (S075–S077)
Punkty i przesunięcia punktów zmieniają geometrię lokalną.

### Efekt transformacji:
- definiują położenia punktów,
- tworzą polilinie i ścieżki,
- pozwalają budować struktury oparte na punktach.

---

## 9. Transformacje rysujące (S034–S064)
Linie i łuki są transformacjami geometrycznymi na gotowej strukturze pól.

### Efekt transformacji:
- nadpisują wypełnienia,
- tworzą krawędzie, pasy i łuki,
- działają po zakończeniu transformacji pól.

---

## Podsumowanie
Transformacje są sposobem, w jaki język NP zmienia przestrzeń, stan i geometrię.  
To one nadają dynamikę strukturze: dzielą, przesuwają, nadpisują, wybierają i przekształcają.  
Transformations są drugim filarem systemu — obok Units i Relations — i prowadzą bezpośrednio do Fields i Structures.
