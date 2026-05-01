# Units

Jednostki NP to elementy języka, które wykonują operacje na polach, liniach, punktach i strukturach.  
Każda jednostka należy do jednej z klas funkcjonalnych i pełni określoną rolę w zdaniu.

---

## 1. Jednostki kluczowe (S001–S006)
Otwierają zdanie i wybierają region, w którym działa program.  
Określają punkt startowy i zakres obowiązywania operacji.

---

## 2. Jednostki podziału (S007–S019)
Dzielą aktywny region na części:
- podział pionowy (lewo/prawo),
- podział poziomy (góra/dół),
- podział na cztery ćwiartki,
- podziały diagonalne (trójkąty),
- podziały łukowe (zewnętrzne i wewnętrzne).

Tworzą strukturę pól, w których wykonywane są dalsze operacje.

---

## 3. Jednostki sterujące (S020–S027)
Kontrolują przebieg zdania:
- zamknięcie zdania,
- podział na sektory w osi X,
- wskaźniki zakresu (pointery).

Ustalają kolejność i logikę wykonania.

---

## 4. Jednostki wyboru pola linii (S028–S032)
Wskazują pole lub podpole, w którym będą rysowane linie.  
Przygotowują kontekst dla operatorów linii.

---

## 5. Jednostki środka (S033)
Ustawiają środek pola jako punkt odniesienia dla linii, łuków i punktów.  
Definiują lokalny układ odniesienia.

---

## 6. Jednostki linii (S034–S064)
Rysują:
- linie pionowe i poziome,
- linie na krawędziach pola,
- łuki górne, dolne, lewe i prawe,
- segmenty i pasy.

Operują na gotowej strukturze pól i nadpisują wypełnienia.

---

## 7. Jednostka centralna (S005)
Rysuje kształt centralny pola:
- koło,
- okrąg,
- elipsę.

Może współpracować z tokenami promieni (S092/S093).

---

## 8. Jednostki gradientu (S067–S074)
Tworzą gradienty:
- pionowe,
- poziome,
- diagonalne.

Wypełniają region zgodnie z kierunkiem i zakresem.

---

## 9. Jednostki punktowe (S075–S077)
Definiują:
- punkty,
- polilinie,
- przesunięcia punktów.

Pozwalają budować geometrię punktową i ścieżki.

---

## Podsumowanie
Zestaw jednostek NP tworzy pełny słownik języka.  
Każda jednostka ma określoną funkcję i działa w ramach struktury pól, zdań i regionów.  
Units są fundamentem całego systemu NP — to z nich powstają relacje, transformacje, pola i struktury.

