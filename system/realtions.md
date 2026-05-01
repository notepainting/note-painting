# Relations

Relacje określają, w jaki sposób jednostki NP łączą się w zdania oraz jak współpracują ze sobą w ramach jednego pola lub struktury.  
Relacje nie są operacjami — są zasadami łączenia jednostek w spójną sekwencję.

---

## 1. Relacja zdaniowa (KEY → S020)
Każde zdanie zaczyna się od jednostki kluczowej (S001–S006)  
i kończy na znaku zamknięcia (S020).

Tworzy to podstawową ramę logiczną:
- KEY otwiera kontekst,
- S020 zamyka zakres operacji.

---

## 2. Relacja sekwencyjna (od lewej do prawej)
Jednostki w zdaniu wykonują się w kolejności ich położenia w osi X.  
Kolejność przestrzenna = kolejność logiczna.

---

## 3. Relacja okien (S021)
S021 dzieli zdanie na sektory.  
Każdy sektor jest niezależnym „oknem operacji”.

Relacja:
- S021 → nowy sektor,
- operacje w sektorze działają tylko w jego zakresie.

---

## 4. Relacja zakresu (pointery S022–S027)
Pointery określają, które sektory należą do danego S006.  
Tworzą relację:  
**S006 → zakres okien → operacje w tych oknach.**

---

## 5. Relacja podziału (splity S007–S019)
Splity dzielą aktywny region na podregiony.  
Relacja:
- jednostka splitu → tworzy nowe pola,
- kolejne operacje działają w tych polach.

---

## 6. Relacja dziedziczenia (kolor, grubość, stan)
Wartości tokenów (S050, S051) dziedziczą się w dół drzewa pól.  
Relacja:
- nadrzędny region → przekazuje stan do podregionów,
- lokalny token nadpisuje stan.

---

## 7. Relacja wyboru pola (S028–S032)
Jednostki wyboru pola określają, w którym podregionie będą rysowane linie.  
Relacja:
- selector → aktywne pole → linie działają tylko tam.

---

## 8. Relacja środka (S033)
S033 ustawia punkt odniesienia dla linii i łuków.  
Relacja:
- S033 → środek pola → geometria linii.

---

## 9. Relacja rysowania (S034–S064)
Jednostki linii działają na strukturze pól utworzonej wcześniej.  
Relacja:
- struktura pól → linie nadpisują wypełnienia,
- linie zawsze rysowane są po PASS 2.

---

## 10. Relacja centralna (S005)
S005 działa w aktywnym polu i współpracuje z tokenami promieni.  
Relacja:
- pole → kształt centralny → nadpisanie wypełnienia.

---

## 11. Relacja gradientu (S067–S074)
Gradienty działają na całym aktywnym regionie.  
Relacja:
- region → gradient → jednolita transformacja wypełnienia.

---

## Podsumowanie
Relacje określają sposób łączenia jednostek w logiczne zdania i struktury.  
To one definiują kolejność, zakres, dziedziczenie i współdziałanie elementów języka NP.  
Bez relacji jednostki są tylko symbolami — relacje nadają im spójność i kierunek.
