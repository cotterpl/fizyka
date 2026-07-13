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

Suwmiarka ma dwie skale: główną (działka 1 mm) i dodatkową, ruchomą — **noniusz**, dzięki której możemy odczytać wynik dokładniej niż działka główna (np. z dokładnością 0,1 mm albo 0,05 mm — producent podaje to wprost na suwmiarce).

<div align="center">

![Suwmiarka ze skalą główną i noniuszem — pomiar 2,475 cm ± 0,005 cm](ilustracje/suwmiarka-skala-z-noniuszem.svg)

*Źródło: Joaquim Alves Gaspar (edycje: ed g2s, Anasofiapaixao), Wikimedia Commons, CC BY-SA 3.0 / CC BY 2.5 / GFDL — [File:Vernier caliper.svg](https://commons.wikimedia.org/wiki/File:Vernier_caliper.svg)*

</div>

Na rysunku widać skalę główną (w centymetrach i calach) oraz przesuwny noniusz — dzięki wyrównaniu kresek noniusza ze skalą główną można odczytać wynik dokładniej niż z samej działki głównej (tu: 2,475 cm, z niepewnością ±0,005 cm).

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

<svg width="520" height="190" viewBox="0 0 520 190" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Oś liczbowa z zaznaczonym przedziałem niepewności pomiaru długości ołówka">
  <defs>
    <marker id="dwStart" viewBox="0 0 10 10" refX="1" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 9 0 L 1 5 L 9 10" fill="none" stroke="#c0392b" stroke-width="1.5" />
    </marker>
    <marker id="dwEnd" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 9 0 L 1 5 L 9 10" fill="none" stroke="#c0392b" stroke-width="1.5" />
    </marker>
    <marker id="axisArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#222" />
    </marker>
  </defs>

  <rect x="0" y="0" width="520" height="190" fill="#f6f6f2" stroke="#bbb" />

  <text x="260" y="20" font-size="13" text-anchor="middle" fill="#222">Niepewność pomiaru długości ołówka: l = (143,5 ± 0,2) mm</text>

  <!-- nawiasy podwójne pokazujące Δl = 0,2 mm po obu stronach -->
  <line x1="120" y1="60" x2="280" y2="60" stroke="#c0392b" stroke-width="1.5" marker-start="url(#dwStart)" marker-end="url(#dwEnd)" />
  <line x1="280" y1="60" x2="440" y2="60" stroke="#c0392b" stroke-width="1.5" marker-start="url(#dwStart)" marker-end="url(#dwEnd)" />
  <text x="200" y="48" font-size="12" text-anchor="middle" fill="#c0392b">Δl = 0,2 mm</text>
  <text x="360" y="48" font-size="12" text-anchor="middle" fill="#c0392b">Δl = 0,2 mm</text>

  <!-- łączniki od nawiasów do kresek na osi -->
  <g stroke="#c0392b" stroke-width="1" stroke-dasharray="2,2">
    <line x1="120" y1="60" x2="120" y2="100" />
    <line x1="280" y1="60" x2="280" y2="100" />
    <line x1="440" y1="60" x2="440" y2="100" />
  </g>

  <!-- główna oś liczbowa -->
  <line x1="60" y1="110" x2="480" y2="110" stroke="#222" stroke-width="2" marker-end="url(#axisArrow)" />
  <g stroke="#222" stroke-width="2">
    <line x1="120" y1="100" x2="120" y2="120" />
    <line x1="280" y1="100" x2="280" y2="120" />
    <line x1="440" y1="100" x2="440" y2="120" />
  </g>

  <text x="120" y="138" font-size="12" text-anchor="middle" fill="#222">143,3</text>
  <text x="280" y="138" font-size="12" text-anchor="middle" fill="#222">143,5</text>
  <text x="440" y="138" font-size="12" text-anchor="middle" fill="#222">143,7</text>
  <text x="495" y="114" font-size="12" fill="#222">długość [mm]</text>

  <!-- znacznik odczytanego wyniku -->
  <polygon points="280,150 274,162 286,162" fill="#2471a3" />
  <line x1="280" y1="150" x2="280" y2="120" stroke="#2471a3" stroke-width="1" stroke-dasharray="2,2" />
  <text x="280" y="178" font-size="12" text-anchor="middle" fill="#2471a3">odczytany wynik l</text>
</svg>

*Ilustracja własna (nie znaleziono gotowego, licencjonowanego obrazka pasującego dokładnie do tego przykładu liczbowego 143,5 mm ± 0,2 mm).*

Wartość PRAWDZIWA długości ołówka na pewno leży gdzieś w przedziale od 143,3 mm do 143,7 mm — po prostu nie wiemy, w którym dokładnie miejscu tego przedziału.

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

| Przedrostek | Symbol | Mnożnik | Przykład |
|---|---|---|---|
| giga | G | 10⁹ | 1 GW = 1 000 000 000 W |
| mega | M | 10⁶ | 1 MW = 1 000 000 W |
| kilo | k | 10³ | 1 km = 1 000 m |
| hekto | h | 10² | 1 hPa = 100 Pa |
| (brak) | — | 10⁰ | 1 m, 1 g, 1 s |
| decy | d | 10⁻¹ | 1 dm = 0,1 m |
| centy | c | 10⁻² | 1 cm = 0,01 m |
| mili | m | 10⁻³ | 1 mm = 0,001 m |
| mikro | µ | 10⁻⁶ | 1 µm = 0,000 001 m |

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
