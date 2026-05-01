# System

System NP opisuje język operacji wykonywanych na polach, liniach, punktach i strukturach.  
Jest to język formalny, w którym obraz powstaje jako wynik sekwencji działań, a nie jako rysunek tworzony ręcznie.

System składa się z pięciu warstw:

1. **Units** – elementy języka  
2. **Relations** – zasady łączenia jednostek  
3. **Transformations** – operacje zmieniające przestrzeń  
4. **Fields** – struktura pól, w których działa język  
5. **Structures** – wynik końcowy, czyli wykonany obraz

Każda warstwa jest niezależna, ale wszystkie współpracują ze sobą w jednej logice.

---

## 1. Units
Jednostki NP to podstawowe elementy języka.  
Każda jednostka ma swoją funkcję: otwiera zdanie, dzieli pole, wybiera region, rysuje linię, ustawia środek, tworzy gradient lub punkt.

Units definiują **co istnieje** w języku.

---

## 2. Relations
Relacje określają, jak jednostki łączą się w zdania i jak współpracują w ramach jednego pola.

Relations definiują **jak to się łączy**.

---

## 3. Transformations
Transformacje opisują, w jaki sposób jednostki zmieniają przestrzeń, stan lub geometrię.

Transformations definiują **jak to działa**.

---

## 4. Fields
Pola są przestrzeniami, w których wykonywane są operacje.  
Powstają przez podziały i tworzą hierarchię regionów.

Fields definiują **gdzie to działa**.

---

## 5. Structures
Struktury są końcowym rezultatem działania języka.  
To, co widzimy jako obraz, jest strukturą logiczną powstałą z pól, wypełnień, linii i punktów.

Structures definiują **co powstaje**.

---

## Logika systemu
System NP działa sekwencyjnie:

1. wybór pola (KEY)  
2. podziały (splity)  
3. dziedziczenie i wypełnienia  
4. wybór podregionu  
5. rysowanie linii, łuków, punktów  
6. powstanie struktury końcowej

Każdy krok jest deterministyczny.  
Obraz jest wynikiem programu, a nie interpretacji.

---

## Charakter systemu
System NP jest:

- **formalny** – oparty na regułach, nie na intuicji  
- **hierarchiczny** – działa w strukturze pól  
- **deterministyczny** – ten sam zapis daje ten sam wynik  
- **redukcjonistyczny** – minimalny zestaw operacji tworzy złożone struktury  
- **wizualny** – wynik jest obrazem, ale proces jest językiem  

---

## Podsumowanie
System NP to język operacji na przestrzeni.  
Units mówią *co*, Relations mówią *jak*, Transformations mówią *co się zmienia*, Fields mówią *gdzie*, a Structures mówią *co powstaje*.

Razem tworzą kompletny, spójny i formalny system generowania obrazu.
