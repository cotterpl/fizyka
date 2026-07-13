# Temat 0. Pomiary fizyczne, niepewności pomiarowe i jednostki

Fizyka to nauka, która bardzo dużo mierzy — długości, masy, czasy, temperatury, siły... Żaden pomiar nie jest jednak idealny. Każdy przyrząd ma swoją dokładność, a wynik pomiaru zawsze zapisujemy tak, żeby było widać, na ile możemy mu ufać. W tym temacie nauczysz się: jak ocenić dokładność przyrządu, jak zapisać wynik pomiaru z niepewnością, czym są cyfry znaczące, jak zapisywać duże i małe liczby w notacji wykładniczej oraz jak rozpoznawać i przeliczać jednostki fizyczne.

---

## 0.1. Przyrządy pomiarowe i ich dokładność

### Najważniejsze pojęcia

- **Zakres pomiarowy** — przedział wartości, jakie przyrząd w ogóle potrafi zmierzyć (np. termometr pokojowy: od −10°C do 50°C).
- **Działka elementarna** — odległość między dwiema sąsiednimi kreskami na skali przyrządu. To najmniejsza różnica, jaką w ogóle widać na skali.
- **Niepewność pomiaru (dokładność przyrządu)** — liczba mówiąca, o ile odczytany wynik może się różnić od wartości prawdziwej.
  - Dla przyrządów **analogowych** (ze skalą i wskazówką albo słupkiem, np. termometr cieczowy, siłomierz, taśma miernicza) przyjmujemy zwykle, że niepewność pomiaru to **połowa działki elementarnej**.
  - Dla przyrządów **cyfrowych** (np. waga elektroniczna) dokładność podaje producent — to zwykle wartość najmniejszej wyświetlanej cyfry (np. ±1 g).
  - Niektóre przyrządy (barometry, mierniki elektryczne) mają podaną **klasę dokładności**.

### Klasa dokładności

Klasa dokładności to liczba (procent), która mówi, jaki maksymalny błąd może mieć przyrząd — liczony od **całego zakresu pomiarowego**, a nie od odczytanej wartości!

$$\text{niepewność} = \frac{\text{klasa dokładności}}{100} \times \text{zakres pomiarowy}$$

To ważne: taki przyrząd myli się o tyle samo (w liczbach bezwzględnych, np. w hPa), niezależnie od tego, czy wskazuje mało, czy dużo.

### Suwmiarka — skala z noniuszem

Suwmiarka ma dwie skale: główną (działka 1 mm) i dodatkową, ruchomą — **nonjusz**, dzięki której możemy odczytać wynik dokładniej niż działka główna (np. z dokładnością 0,1 mm albo 0,05 mm — producent podaje to wprost na suwmiarce).

<div align="center">

<svg width="420" height="150" viewBox="0 0 420 150" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skala suwmiarki z zaznaczoną działką elementarną">
  <rect x="0" y="0" width="420" height="150" fill="#f6f6f2" stroke="#bbb" />
  <!-- główna linia skali -->
  <line x1="20" y1="60" x2="400" y2="60" stroke="#222" stroke-width="2" />
  <!-- ticki co 1 mm (co 10px), duże co 1 cm (co 50px) -->
  <g stroke="#222" stroke-width="1.5">
    <line x1="20" y1="60" x2="20" y2="90" stroke-width="2.5" />
    <line x1="30" y1="60" x2="30" y2="72" />
    <line x1="40" y1="60" x2="40" y2="72" />
    <line x1="50" y1="60" x2="50" y2="72" />
    <line x1="60" y1="60" x2="60" y2="72" />
    <line x1="70" y1="60" x2="70" y2="90" stroke-width="2.5" />
    <line x1="80" y1="60" x2="80" y2="72" />
    <line x1="90" y1="60" x2="90" y2="72" />
    <line x1="100" y1="60" x2="100" y2="72" />
    <line x1="110" y1="60" x2="110" y2="72" />
    <line x1="120" y1="60" x2="120" y2="90" stroke-width="2.5" />
    <line x1="130" y1="60" x2="130" y2="72" />
    <line x1="140" y1="60" x2="140" y2="72" />
    <line x1="150" y1="60" x2="150" y2="72" />
    <line x1="160" y1="60" x2="160" y2="72" />
    <line x1="170" y1="60" x2="170" y2="90" stroke-width="2.5" />
  </g>
  <text x="20" y="105" font-size="12" text-anchor="middle">0 cm</text>
  <text x="70" y="105" font-size="12" text-anchor="middle">1 cm</text>
  <text x="120" y="105" font-size="12" text-anchor="middle">2 cm</text>
  <text x="170" y="105" font-size="12" text-anchor="middle">3 cm</text>
  <!-- callout na działkę elementarną -->
  <line x1="30" y1="60" x2="30" y2="30" stroke="#c0392b" stroke-width="1" stroke-dasharray="3,2" />
  <line x1="40" y1="60" x2="40" y2="30" stroke="#c0392b" stroke-width="1" stroke-dasharray="3,2" />
  <line x1="30" y1="30" x2="40" y2="30" stroke="#c0392b" stroke-width="1.5" />
  <text x="35" y="20" font-size="12" fill="#c0392b" text-anchor="middle">działka elementarna = 1 mm</text>
  <text x="210" y="60" font-size="12" fill="#555">← skala główna suwmiarki (mm) →</text>
  <text x="20" y="130" font-size="11" fill="#555">Odległość między sąsiednimi kreskami (np. tu: od 1,0 cm do 1,1 cm) to właśnie działka elementarna.</text>
</svg>

</div>

### Przegląd typowych przyrządów

| Przyrząd | Do czego służy | Typowa działka elementarna | Jak liczymy niepewność |
|---|---|---|---|
| Waga (elektroniczna) | masa | np. 1 g | podana przez producenta |
| Suwmiarka | długość (małe przedmioty) | 1 mm (główna), z noniuszem 0,1 mm lub 0,05 mm | podana przez producenta |
| Termometr cieczowy | temperatura | np. 1°C lub 2°C | połowa działki elementarnej |
| Barometr | ciśnienie | zależnie od modelu | z klasy dokładności |
| Taśma miernicza | długość (duże odległości) | 1 mm lub 1 cm | z klasy dokładności lub połowa działki |
| Siłomierz | siła | np. 0,1 N | połowa działki elementarnej |

### Przykład

**Treść:** Barometr ma zakres pomiarowy 0–1050 hPa i klasę dokładności 1,0. Jaka jest niepewność pomiaru ciśnienia tym barometrem?

**Rozwiązanie:**
1. Ze wzoru: niepewność = (klasa/100) × zakres pomiarowy.
2. Podstawiamy: niepewność = (1,0/100) × 1050 hPa = 10,5 hPa.

**Odpowiedź:** Niepewność pomiaru tym barometrem wynosi ±10,5 hPa — i to niezależnie od tego, czy przyrząd wskazuje 990 hPa, czy 1040 hPa.

---

## 0.2. Niepewność pomiarowa i zapis wyniku pomiaru

Skoro wiemy już, że każdy przyrząd ma swoją dokładność, to wynik pomiaru musimy zapisać tak, by było jasne, w jakich granicach mieści się wartość prawdziwa. Robimy to w postaci:

$$x = x_{\text{odczyt}} \pm \Delta x \quad [\text{jednostka}]$$

gdzie:
- $x_{\text{odczyt}}$ — wartość, którą odczytaliśmy na przyrządzie,
- $\Delta x$ — niepewność pomiaru (zawsze dodatnia, w tej samej jednostce co wynik).

Taki zapis oznacza: **wartość prawdziwa mieści się gdzieś w przedziale od $(x_{\text{odczyt}} - \Delta x)$ do $(x_{\text{odczyt}} + \Delta x)$.** Nie wiemy dokładnie, gdzie w tym przedziale — wiemy tylko, że gdzieś tam jest.

Jednostkę zapisujemy zawsze po całym wyrażeniu, np. $l = (143{,}5 \pm 0{,}2)\ \text{mm}$ — nigdy osobno przy każdej liczbie.

<div align="center">

```
Niepewność pomiaru długości ołówka: l = (143,5 ± 0,2) mm

              Δl = 0,2 mm         Δl = 0,2 mm
           |‹───────────›|‹───────────›|
      ─────┼─────────────┼─────────────┼─────►  długość [mm]
         143,3         143,5         143,7
                          ▲
                   odczytany wynik l

  Wartość PRAWDZIWA długości ołówka na pewno leży gdzieś
  w przedziale od 143,3 mm do 143,7 mm — po prostu nie wiemy,
  w którym dokładnie miejscu tego przedziału.
```

</div>

### Przykład

**Treść:** Mierzysz długość ołówka suwmiarką o dokładności 0,1 mm. Odczytany wynik to 143,5 mm. Zapisz wynik pomiaru z niepewnością oraz podaj, w jakich granicach na pewno mieści się prawdziwa długość ołówka.

**Rozwiązanie:**
1. Niepewność suwmiarki wynosi Δl = 0,1 mm (podana przez producenta).
2. Zapis wyniku: $l = (143{,}5 \pm 0{,}1)\ \text{mm}$.
3. Granice przedziału: dolna = 143,5 − 0,1 = 143,4 mm; górna = 143,5 + 0,1 = 143,6 mm.

**Odpowiedź:** $l = (143{,}5 \pm 0{,}1)\ \text{mm}$. Prawdziwa długość ołówka mieści się między 143,4 mm a 143,6 mm.

---

## 0.3. Cyfry znaczące

**Cyfry znaczące** to cyfry w zapisie liczby, które niosą rzeczywistą informację o dokładności pomiaru. Im więcej cyfr znaczących podajemy, tym bardziej "precyzyjny" wydaje się wynik — dlatego trzeba umieć je poprawnie liczyć i zaokrąglać.

### Zasady liczenia cyfr znaczących

1. Każda cyfra różna od zera jest znacząca (np. w liczbie 7,42 są 3 cyfry znaczące).
2. Zera **pomiędzy** cyframi niezerowymi są znaczące (np. 1,05 — 3 cyfry znaczące).
3. Zera **na początku** liczby (przed pierwszą cyfrą niezerową) NIE są znaczące — to tylko "wypełniacz" pokazujący rząd wielkości (np. 0,0037 — tylko 2 cyfry znaczące: 3 i 7).
4. Zera **na końcu**, po przecinku, SĄ znaczące (np. 2,500 — 4 cyfry znaczące).
5. Zera na końcu liczby całkowitej bez przecinka (np. 3600) są niejednoznaczne — najlepiej wtedy użyć notacji wykładniczej (patrz 0.4), żeby było jasne, ile cyfr jest znaczących.

### Zaokrąglanie do zadanej liczby cyfr znaczących

Zaokrąglamy tak jak zwykle w matematyce (cyfra 5 i więcej — w górę), ale liczymy cyfry znaczące, a nie miejsca po przecinku!

### Przykład

**Treść:** W doświadczeniu otrzymano wynik gęstości substancji równy 2,4873 g/cm³. Zaokrąglij ten wynik do 3 cyfr znaczących.

**Rozwiązanie:**
1. Liczymy cyfry znaczące od lewej: 2 (1.), 4 (2.), 8 (3.), 7 (4.), 3 (5.).
2. Chcemy zostawić tylko 3 pierwsze: "2,48" — patrzymy na kolejną cyfrę (7), żeby wiedzieć, czy zaokrąglić w górę.
3. Cyfra 7 ≥ 5, więc ostatnią zostawioną cyfrę (8) zaokrąglamy w górę do 9.

**Odpowiedź:** 2,4873 g/cm³ ≈ **2,49 g/cm³** (3 cyfry znaczące).

---

## 0.4. Notacja wykładnicza

Notacja wykładnicza (inaczej: postać naukowa) pozwala krótko zapisywać bardzo duże i bardzo małe liczby, a przy okazji bardzo ułatwia przeliczanie jednostek.

$$a \times 10^{n}, \quad \text{gdzie } 1 \le a < 10, \ n \in \mathbb{Z}$$

- Jeśli przesuwamy przecinek **w lewo** o $n$ miejsc — mnożymy przez $10^{n}$ (liczba duża, $n$ dodatnie).
- Jeśli przesuwamy przecinek **w prawo** o $n$ miejsc — mnożymy przez $10^{-n}$ (liczba mała, wykładnik ujemny).

### Przedrostki jednostek SI — tabela przeliczeniowa

<div align="center">

```
+---------------+--------+-----------+----------------------------+
|  Przedrostek  | Symbol |  Mnożnik  |         Przykład           |
+---------------+--------+-----------+----------------------------+
|  giga         |   G    |   10⁹     |  1 GW = 1 000 000 000 W    |
|  mega         |   M    |   10⁶     |  1 MW =     1 000 000 W    |
|  kilo         |   k    |   10³     |  1 km =         1 000 m    |
|  hekto        |   h    |   10²     |  1 hPa =          100 Pa   |
|  (brak)       |   —    |   10⁰     |  1 m, 1 g, 1 s              |
|  decy         |   d    |   10⁻¹    |  1 dm =           0,1 m     |
|  centy        |   c    |   10⁻²    |  1 cm =          0,01 m     |
|  mili         |   m    |   10⁻³    |  1 mm =         0,001 m     |
|  mikro        |   µ    |   10⁻⁶    |  1 µm =     0,000 001 m     |
+---------------+--------+-----------+----------------------------+
```

</div>

### Przykład

**Treść:** Zamień 4 250 000 mm na kilometry i zapisz wynik w notacji wykładniczej (w metrach).

**Rozwiązanie:**
1. Zamieniamy mm na m: 1 mm = 10⁻³ m, więc 4 250 000 mm = 4 250 000 × 10⁻³ m = 4250 m.
2. Zapisujemy 4250 w notacji wykładniczej: przesuwamy przecinek o 3 miejsca w lewo → 4250 = 4,25 × 10³.
3. Dla porównania w kilometrach: 4250 m = 4,25 km (bo 1 km = 10³ m).

**Odpowiedź:** 4 250 000 mm = 4,25 × 10³ m = 4,25 km.

---

## 0.5. Jednostki wielkości fizycznych — rozpoznawanie i przeliczanie

### Siedem jednostek podstawowych układu SI

| Wielkość | Jednostka podstawowa | Symbol |
|---|---|---|
| długość | metr | m |
| masa | kilogram | kg |
| czas | sekunda | s |
| natężenie prądu elektrycznego | amper | A |
| temperatura | kelwin | K |
| ilość materii | mol | mol |
| światłość źródła światła | kandela | cd |

### Jednostki pochodne (zbudowane z podstawowych)

| Wielkość | Jednostka | Symbol | Zapisana przez jednostki podstawowe |
|---|---|---|---|
| siła | niuton | N | kg·m/s² |
| praca, energia | dżul | J | N·m = kg·m²/s² |
| moc | wat | W | J/s = kg·m²/s³ |
| ciśnienie | paskal | Pa | N/m² = kg/(m·s²) |
| częstotliwość | herc | Hz | 1/s |
| ładunek elektryczny | kulomb | C | A·s |

Warto zapamiętać: jeśli widzisz jednostkę w postaci ułamka, np. **N/kg** albo **kg/m³**, to zwykle jest to jednostka jakiejś *innej* wielkości fizycznej niż te, z których się składa (np. N/kg to jednostka natężenia pola grawitacyjnego, a kg/m³ to jednostka gęstości).

### Przykład

**Treść:** Sprawdź rachunkiem jednostek (analiza wymiarowa), czy 1 dżul (J) rzeczywiście równa się 1 kg·m²/s², korzystając z definicji J = N·m oraz N = kg·m/s².

**Rozwiązanie:**
1. Zaczynamy od: 1 J = 1 N·m.
2. Podstawiamy definicję niutona: 1 N = 1 kg·m/s².
3. Więc: 1 J = 1 (kg·m/s²)·m = 1 kg·m²/s².

**Odpowiedź:** Tak, 1 J = 1 kg·m²/s² — to potwierdza, że dżul jest jednostką pochodną, zbudowaną z jednostek podstawowych SI.

---

## Quiz

Odpowiedz na poniższe pytania samodzielnie, a potem sprawdź się w pliku z odpowiedziami.

**1.** Cyfrowa waga kuchenna wyświetla wyniki z dokładnością do ±5 g. Wskazanie na wadze wynosi 640 g. Rzeczywista masa ważonego produktu może być równa:
- [ ] A. 64,5 mg
- [ ] B. 6,45 dag
- [ ] C. 0,645 kg
- [ ] D. 6,45 kg

**2.** Siłomierz ma zakres pomiarowy 0–20 N i klasę dokładności 2,5. Niepewność pomiaru wykonanego tym siłomierzem wynosi:
- [ ] A. 0,25 N
- [ ] B. 0,5 N
- [ ] C. 2,5 N
- [ ] D. 5 N

**3.** Oceń, czy poniższe zdania są prawdziwe (P) czy fałszywe (F):
a) Działka elementarna to najmniejsza odległość między dwiema sąsiednimi kreskami na skali przyrządu.
b) Dla typowego przyrządu analogowego niepewność pomiaru przyjmujemy jako całą działkę elementarną (a nie jej połowę).
c) Zakres pomiarowy to przedział wartości, jakie dany przyrząd w ogóle jest w stanie zmierzyć.
d) Wynik każdego pomiaru fizycznego jest zawsze dokładny co do jednego atomu — pomiar nigdy nie ma niepewności.

**4.** Wynik pomiaru masy jabłka zapisano jako $m = (152 \pm 3)\ \text{g}$. Uzupełnij zdanie: rzeczywista masa jabłka na pewno mieści się w przedziale od ……… g do ……… g.

**5.** Liczba 0,004080 ma:
- [ ] A. 3 cyfry znaczące
- [ ] B. 4 cyfry znaczące
- [ ] C. 5 cyfr znaczących
- [ ] D. 6 cyfr znaczących

**6.** Zaokrąglij liczbę 3,14159 do 3 cyfr znaczących:
- [ ] A. 3,14
- [ ] B. 3,15
- [ ] C. 3,141
- [ ] D. 3,1

**7.** Uzupełnij: liczbę 0,000067 m zapisaną w notacji wykładniczej $a \times 10^{n}$ opisują wartości: a = ……… oraz n = ……… .

**8.** Odległość 3,2 × 10⁵ cm wyrażona w metrach to:
- [ ] A. 3,2 × 10² m
- [ ] B. 3,2 × 10³ m
- [ ] C. 3,2 × 10⁴ m
- [ ] D. 3,2 × 10⁷ m

**9.** Oceń, czy poniższe zdania są prawdziwe (P) czy fałszywe (F):
a) Kelwin (K) jest podstawową jednostką SI temperatury.
b) Jednostką siły w układzie SI jest dżul (J).
c) 1 herc (Hz) to jednostka pochodna, równa 1/s.
d) Amper (A) jest jednostką pochodną, zbudowaną z metra i kilograma.

**10.** Uzupełnij zdanie nazwami wielkości fizycznych: paskal (Pa) jest jednostką ………, a wat (W) jest jednostką ……… .
