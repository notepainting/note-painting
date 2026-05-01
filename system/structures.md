# Structures

Struktury są końcowym rezultatem działania języka NP.  
Powstają z połączenia pól, relacji, transformacji i operacji rysujących.  
Structure to nie pojedynczy element — to układ, który wyłania się z sekwencji działań.

---

## 1. Struktura jako wynik zdania
Każde zdanie tworzy własną strukturę.  
Struktura zdania składa się z:

- drzewa pól,
- wypełnień,
- linii,
- łuków,
- kształtów centralnych,
- gradientów,
- punktów.

Struktura jest zawsze wynikiem **kolejności operacji**.

---

## 2. Struktura pól (region tree)
Podstawą każdej struktury jest drzewo pól.

Drzewo pól określa:
- podział przestrzeni,
- hierarchię regionów,
- dziedziczenie stanu,
- kontekst operacji.

To jest szkielet struktury.

---

## 3. Struktura wypełnień
Wypełnienia tworzą warstwę kolorystyczną struktury.

Źródła:
- kolor (S051),
- gradient (S067–S074),
- dziedziczenie.

Wypełnienia są nakładane **przed** liniami.

---

## 4. Struktura linii
Linie i łuki tworzą warstwę geometryczną.

Elementy:
- linie pionowe i poziome,
- linie krawędziowe,
- łuki górne, dolne, lewe, prawe,
- krzyże,
- segmenty.

Linie są rysowane **po** wypełnieniach i nadpisują je.

---

## 5. Struktura centralna
S005 tworzy element centralny pola:

- koło,
- okrąg,
- elipsę.

Może współpracować z tokenami promieni (S092/S093).  
Struktura centralna jest częścią kompozycji pola.

---

## 6. Struktura punktowa
Punkty i polilinie (S075–S077) tworzą strukturę opartą na:

- punktach,
- ścieżkach,
- przesunięciach.

To jest warstwa precyzyjnej geometrii.

---

## 7. Struktura wielowarstwowa
Struktura końcowa jest sumą warstw:

1. **pola** (geometria przestrzeni)  
2. **wypełnienia** (kolor, gradient)  
3. **linie** (geometria rysunku)  
4. **kształty centralne**  
5. **punkty i ścieżki**  

Każda warstwa nadpisuje poprzednią zgodnie z logiką NP.

---

## 8. Struktura jako obraz
Końcowa struktura jest obrazem, który:

- powstaje deterministycznie,
- wynika z kolejności operacji,
- jest zbudowany z pól i relacji,
- jest wynikiem działania języka, nie ręcznego rysowania.

Struktura = **wykonany program NP**.

---

## Podsumowanie
Structures to finalna forma języka NP — rezultat działania jednostek, relacji, transformacji i pól.  
To, co widzimy jako obraz, jest strukturą logiczną, a nie grafiką.  
Structures zamykają cały system: Units → Relations → Transformations → Fields → Structures.
