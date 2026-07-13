# Temat 5: Właściwości materii i hydrostatyka

Ten dział łączy dwie sprawy, które na pierwszy rzut oka wydają się różne, a w praktyce działają razem: to, **z czego** zbudowane jest ciało (jego gęstość, siły między cząsteczkami), oraz to, **jak zachowują się ciecze** — jakie ciśnienie wywierają i dlaczego niektóre przedmioty w nich pływają, a inne toną. Materiał obejmuje podtematy 5.1–5.4.

---

## 5.1. Gęstość — związek masy, gęstości i objętości

Weźmy dwa jednakowej wielkości sześciany — jeden z drewna, drugi ze stali. Mają taką samą **objętość**, ale stalowy jest dużo cięższy. Dlaczego? Bo materiały różnią się **gęstością** — czyli tym, ile masy „mieści się" w jednej jednostce objętości.

**Gęstość** to stosunek masy ciała do jego objętości:

```
d = m / V
```

gdzie:
- `d` — gęstość (czasem oznaczana grecką literą ρ, czyt. „ro")
- `m` — masa ciała
- `V` — objętość ciała

Z tego wzoru można też wyliczyć masę (`m = d · V`) albo objętość (`V = m / d`) — zależnie od tego, co jest niewiadomą w zadaniu.

**Jednostki gęstości** w układzie SI to kilogram na metr sześcienny (kg/m³), ale w praktyce (i w laboratorium) częściej używa się gram na centymetr sześcienny (g/cm³). Zależność między nimi:

```
1 g/cm³ = 1000 kg/m³
```

Przykładowe gęstości (warto je znać w przybliżeniu):

| Substancja | Gęstość [g/cm³] | Gęstość [kg/m³] |
|---|---|---|
| powietrze | 0,0012 | 1,2 |
| lód | 0,92 | 920 |
| olej jadalny | 0,92 | 920 |
| woda (4°C) | 1,00 | 1000 |
| aluminium | 2,70 | 2700 |
| żelazo / stal | 7,80–7,90 | 7800–7900 |
| miedź | 8,90 | 8900 |
| ołów | 11,3 | 11300 |
| złoto | 19,3 | 19300 |

<div align="center">

<svg width="300" height="230" viewBox="0 0 300 230" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Sześcian o krawędzi a i masie m">
  <polygon points="70,190 70,90 190,90 190,190" fill="#cfe8f3" stroke="#1b2b34" stroke-width="2"/>
  <polygon points="70,90 110,50 230,50 190,90" fill="#a9d4e6" stroke="#1b2b34" stroke-width="2"/>
  <polygon points="190,90 230,50 230,150 190,190" fill="#8bbedc" stroke="#1b2b34" stroke-width="2"/>
  <text x="118" y="148" font-size="22" font-family="sans-serif" fill="#1b2b34">m</text>
  <line x1="70" y1="75" x2="110" y2="35" stroke="#1b2b34" stroke-width="1"/>
  <text x="82" y="68" font-size="14" font-family="sans-serif" fill="#1b2b34">a</text>
  <text x="235" y="105" font-size="14" font-family="sans-serif" fill="#1b2b34">a</text>
  <text x="95" y="205" font-size="14" font-family="sans-serif" fill="#1b2b34">a</text>
</svg>
<p><em>Rys. 1. Sześcian o krawędzi <code>a</code> i masie <code>m</code>. Objętość V = a · a · a = a³, a gęstość d = m / V.</em></p>
</div>

### Przykład 1 (obliczanie masy)

**Treść zadania:** Złota kostka ma kształt sześcianu o krawędzi 2 cm. Gęstość złota wynosi 19,3 g/cm³. Oblicz masę tej kostki.

**Rozwiązanie krok po kroku:**
1. Obliczamy objętość sześcianu: `V = a³ = 2 cm × 2 cm × 2 cm = 8 cm³`.
2. Korzystamy ze wzoru na masę: `m = d · V`.
3. Podstawiamy dane: `m = 19,3 g/cm³ × 8 cm³ = 154,4 g`.

**Odpowiedź:** Kostka złota waży 154,4 g (czyli 0,1544 kg).

### Przykład 2 (wyznaczanie gęstości i rozpoznanie materiału)

**Treść zadania:** Uczeń zanurzył metalową odlewaną bryłkę w wodzie wlanej do naczynia pomiarowego. Bryłka wyparła 60 cm³ wody, a jej masa (zmierzona wcześniej na wadze) wynosi 450 g. Korzystając z tabeli gęstości powyżej, ustal, z jakiego metalu może być wykonana bryłka.

**Rozwiązanie krok po kroku:**
1. Objętość wypartej wody jest równa objętości bryłki (bo bryłka całkowicie zanurzyła się w wodzie): `V = 60 cm³`.
2. Obliczamy gęstość ze wzoru `d = m / V`.
3. Podstawiamy dane: `d = 450 g / 60 cm³ = 7,5 g/cm³`.
4. Porównujemy wynik z tabelą — najbliższa wartość to gęstość żelaza/stali (7,8–7,9 g/cm³).

**Odpowiedź:** Bryłka najprawdopodobniej jest wykonana z żelaza lub stali (wynik jest zbliżony do tabelarycznej gęstości tych metali; niewielka różnica może wynikać z niedokładności pomiaru).

---

## 5.2. Siły spójności i zjawisko napięcia powierzchniowego

Cząsteczki cieczy przyciągają się wzajemnie — to przyciąganie nazywamy **siłami spójności** (kohezji). Wewnątrz cieczy każda cząsteczka jest „ciągnięta" równomiernie ze wszystkich stron przez sąsiadki, więc siły się równoważą. Ale cząsteczka znajdująca się dokładnie **na powierzchni** cieczy ma sąsiadki tylko z boków i od spodu (nad nią jest powietrze, z którym oddziałuje dużo słabiej). W efekcie taka cząsteczka jest „wciągana" do wnętrza cieczy.

Skutkiem tego jest, że powierzchnia cieczy zachowuje się jak cienka, napięta błona, która „chce" mieć jak najmniejsze pole powierzchni. To zjawisko nazywamy **napięciem powierzchniowym**. Dlatego:
- małe krople wody (i inne krople, np. rosy) mają kształt zbliżony do kuli — kula ma najmniejsze pole powierzchni przy danej objętości,
- lekkie przedmioty (igła, spinacz, niektóre owady, np. nartnik) mogą „stać" na powierzchni wody, mimo że są gęstsze od wody — to nie wypór je utrzymuje, tylko napięta „błonka" powierzchniowa,
- dodanie mydła do wody zmniejsza jej napięcie powierzchniowe (dlatego roztwór mydlin łatwiej się rozlewa i tworzy piankę o innej strukturze).

Napięcie powierzchniowe (oznaczane σ, czyt. „sigma") to siła przypadająca na jednostkę długości linii, wzdłuż której powierzchnia cieczy styka się z ciałem lub brzegiem naczynia:

```
σ = F / l
```

gdzie `F` to siła, a `l` — długość linii styku. Jednostką σ w układzie SI jest N/m.

<div align="center">

<svg width="420" height="220" viewBox="0 0 420 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Kropla wody z napięciem powierzchniowym oraz owad na powierzchni wody">
  <defs>
    <marker id="arrow1" markerWidth="8" markerHeight="8" refX="4" refY="4" orient="auto">
      <path d="M0,0 L8,4 L0,8 Z" fill="#1b2b34"/>
    </marker>
  </defs>

  <!-- kropla -->
  <ellipse cx="105" cy="115" rx="60" ry="65" fill="#bfe3f5" stroke="#1b3a4b" stroke-width="2"/>
  <line x1="105" y1="65" x2="105" y2="90" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="105" y1="165" x2="105" y2="140" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="55" y1="115" x2="80" y2="115" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="155" y1="115" x2="130" y2="115" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="65" y1="75" x2="88" y2="95" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="145" y1="75" x2="122" y2="95" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="65" y1="155" x2="88" y2="135" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <line x1="145" y1="155" x2="122" y2="135" stroke="#1b2b34" stroke-width="2" marker-end="url(#arrow1)"/>
  <text x="60" y="205" font-size="12" font-family="sans-serif" fill="#1b2b34">siły spójności ciągną</text>
  <text x="60" y="219" font-size="12" font-family="sans-serif" fill="#1b2b34">cząsteczki do środka</text>

  <!-- owad na wodzie -->
  <path d="M240,150 Q265,145 280,155 Q295,145 320,150 Q335,145 360,150" stroke="#1b3a4b" stroke-width="2" fill="none"/>
  <line x1="360" y1="150" x2="400" y2="150" stroke="#1b3a4b" stroke-width="2"/>
  <line x1="220" y1="150" x2="240" y2="150" stroke="#1b3a4b" stroke-width="2"/>
  <ellipse cx="290" cy="120" rx="22" ry="10" fill="#8a6d3b" stroke="#1b2b34" stroke-width="1.5"/>
  <line x1="265" y1="155" x2="278" y2="128" stroke="#1b2b34" stroke-width="1.5"/>
  <line x1="290" y1="155" x2="290" y2="128" stroke="#1b2b34" stroke-width="1.5"/>
  <line x1="320" y1="150" x2="302" y2="128" stroke="#1b2b34" stroke-width="1.5"/>
  <text x="235" y="185" font-size="12" font-family="sans-serif" fill="#1b2b34">błona powierzchniowa</text>
  <text x="245" y="200" font-size="12" font-family="sans-serif" fill="#1b2b34">utrzymuje owada</text>
</svg>
<p><em>Rys. 2. Po lewej: siły spójności ciągną cząsteczki na powierzchni kropli do wnętrza, dlatego kropla przyjmuje kształt zbliżony do kuli. Po prawej: dzięki napięciu powierzchniowemu lekki owad może „stać” na wodzie, mimo że jego ciało jest gęstsze od wody.</em></p>
</div>

### Przykład (obliczanie siły napięcia powierzchniowego)

**Treść zadania:** Cienki metalowy pierścionek delikatnie kładziony na powierzchni wody ma obwód (długość linii styku z wodą) równy 8 cm. Napięcie powierzchniowe wody wynosi około 0,07 N/m. Oblicz, jaką siłę trzeba przyłożyć, aby oderwać pierścionek od powierzchni wody (pomijamy tu jego ciężar).

**Rozwiązanie krok po kroku:**
1. Zamieniamy jednostki: `l = 8 cm = 0,08 m`.
2. Korzystamy ze wzoru `F = σ · l`.
3. Podstawiamy dane: `F = 0,07 N/m × 0,08 m = 0,0056 N`.

**Odpowiedź:** Trzeba przyłożyć siłę około 0,0056 N (czyli 5,6 mN) — to bardzo mała siła, dlatego napięcie powierzchniowe łatwo zauważyć tylko przy lekkich przedmiotach.

---

## 5.3. Ciśnienie hydrostatyczne i atmosferyczne, prawo Pascala

**Ciśnienie** ogólnie to siła nacisku przypadająca na jednostkę powierzchni:

```
p = F / S
```

gdzie `F` to siła nacisku (prostopadła do powierzchni), a `S` — pole powierzchni, na które ta siła działa. Jednostką ciśnienia w SI jest paskal: `1 Pa = 1 N/m²`.

### Ciśnienie hydrostatyczne

Ciecz ma swój ciężar, więc każda głębsza warstwa cieczy jest „przygnieciona" przez warstwy leżące nad nią. To powoduje **ciśnienie hydrostatyczne** — ciśnienie wywierane przez słup cieczy na dowolne ciało (albo na ścianki naczynia) znajdujące się na danej głębokości:

```
p = ρ · g · h
```

gdzie:
- `ρ` — gęstość cieczy,
- `g` — przyspieszenie ziemskie (w zadaniach szkolnych zwykle przyjmujemy `g ≈ 10 N/kg`),
- `h` — głębokość zanurzenia (odległość od powierzchni cieczy).

**Ważne:** ciśnienie hydrostatyczne na danej głębokości **zależy tylko od gęstości cieczy i głębokości**, a nie od kształtu ani szerokości naczynia! To dlatego w dwóch naczyniach o różnym kształcie, ale takiej samej cieczy i takiej samej wysokości słupa cieczy, ciśnienie na dnie jest identyczne.

Oprócz ciśnienia hydrostatycznego na każdą ciecz (i na nas) działa też **ciśnienie atmosferyczne** — ciężar słupa powietrza w atmosferze. Ciśnienie normalne wynosi około `1013 hPa` (hektopaskali), czyli `101 300 Pa`.

### Prawo Pascala

**Prawo Pascala** mówi, że ciśnienie wywierane na ciecz (lub gaz) zamkniętą w naczyniu rozchodzi się jednakowo we wszystkich kierunkach i działa z taką samą wartością na każdą ściankę naczynia. Na tej zasadzie działają np. prasy hydrauliczne, hamulce samochodowe czy podnośniki hydrauliczne — mała siła przyłożona do małego tłoka wywołuje takie samo ciśnienie, jak duża siła na dużym tłoku:

```
p₁ = p₂     czyli     F₁ / S₁ = F₂ / S₂
```

<div align="center">

<svg width="260" height="260" viewBox="0 0 260 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Naczynie z cieczą, głębokość h i strumienie wypływające z otworów na różnych głębokościach">
  <line x1="40" y1="20" x2="40" y2="220" stroke="#1b2b34" stroke-width="2"/>
  <line x1="220" y1="20" x2="220" y2="220" stroke="#1b2b34" stroke-width="2"/>
  <line x1="40" y1="220" x2="220" y2="220" stroke="#1b2b34" stroke-width="2"/>
  <rect x="42" y="30" width="176" height="188" fill="#bfe3f5" opacity="0.8"/>
  <line x1="42" y1="30" x2="218" y2="30" stroke="#1b3a4b" stroke-width="1.5" stroke-dasharray="4,3"/>

  <!-- otwory i strumienie: krotszy = mniejsza glebokosc, dluzszy = wieksza glebokosc -->
  <circle cx="40" cy="90" r="3" fill="#1b2b34"/>
  <path d="M40,90 Q15,92 5,98" stroke="#1b3a4b" stroke-width="2" fill="none"/>
  <circle cx="40" cy="140" r="3" fill="#1b2b34"/>
  <path d="M40,140 Q5,143 -12,155" stroke="#1b3a4b" stroke-width="2" fill="none"/>
  <circle cx="40" cy="190" r="3" fill="#1b2b34"/>
  <path d="M40,190 Q0,195 -20,215" stroke="#1b3a4b" stroke-width="2" fill="none"/>

  <!-- linia glebokosci h -->
  <line x1="150" y1="30" x2="150" y2="140" stroke="#1b2b34" stroke-width="1" stroke-dasharray="3,3"/>
  <line x1="145" y1="30" x2="155" y2="30" stroke="#1b2b34" stroke-width="1"/>
  <line x1="145" y1="140" x2="155" y2="140" stroke="#1b2b34" stroke-width="1"/>
  <text x="158" y="90" font-size="14" font-family="sans-serif" fill="#1b2b34">h</text>

  <text x="70" y="245" font-size="13" font-family="sans-serif" fill="#1b2b34">p = ρ · g · h — im głębiej, tym większe ciśnienie</text>
</svg>
<p><em>Rys. 3. Naczynie z cieczą. Strumienie wypływające z otworów na większej głębokości sięgają dalej — to widoczny dowód na to, że ciśnienie hydrostatyczne rośnie wraz z głębokością.</em></p>
</div>

### Przykład 1 (ciśnienie hydrostatyczne i siła parcia na dno)

**Treść zadania:** Do prostopadłościennego naczynia o polu dna 200 cm² wlano wodę do wysokości 50 cm. Oblicz ciśnienie hydrostatyczne na dnie naczynia oraz siłę parcia wody na dno. Przyjmij ρ_wody = 1000 kg/m³, g = 10 N/kg.

**Rozwiązanie krok po kroku:**
1. Zamieniamy jednostki na SI: `h = 50 cm = 0,5 m`, `S = 200 cm² = 0,02 m²`.
2. Obliczamy ciśnienie hydrostatyczne: `p = ρ · g · h = 1000 kg/m³ × 10 N/kg × 0,5 m = 5000 Pa`.
3. Obliczamy siłę parcia na dno ze wzoru `p = F / S`, czyli `F = p · S`.
4. Podstawiamy dane: `F = 5000 Pa × 0,02 m² = 100 N`.

**Odpowiedź:** Ciśnienie hydrostatyczne na dnie wynosi 5000 Pa (5 kPa), a siła parcia wody na dno naczynia to 100 N.

### Przykład 2 (prawo Pascala — podnośnik hydrauliczny)

**Treść zadania:** W podnośniku hydraulicznym mały tłok ma pole powierzchni 6 cm², a duży tłok — 300 cm². Na mały tłok działa siła 40 N. Jaka siła powstanie na dużym tłoku?

**Rozwiązanie krok po kroku:**
1. Z prawa Pascala ciśnienie w obu miejscach jest takie samo: `p₁ = p₂`, czyli `F₁ / S₁ = F₂ / S₂`.
2. Przekształcamy wzór, aby wyznaczyć `F₂`: `F₂ = F₁ · (S₂ / S₁)`.
3. Podstawiamy dane: `F₂ = 40 N × (300 cm² / 6 cm²) = 40 N × 50 = 2000 N`.

**Odpowiedź:** Na dużym tłoku powstanie siła 2000 N — dzięki temu niewielką siłą można podnieść bardzo ciężki samochód.

---

## 5.4. Siła wyporu, prawo Archimedesa, warunki pływania ciał

Gdy zanurzamy ciało w cieczy, ciecz „napiera" na nie ze wszystkich stron. Ponieważ ciśnienie hydrostatyczne rośnie z głębokością, na spód ciała działa większe ciśnienie (a więc i większa siła) niż na jego wierzch. Różnica tych sił daje wypadkową siłę skierowaną **do góry** — nazywamy ją **siłą wyporu**.

### Prawo Archimedesa

**Prawo Archimedesa** mówi, że na ciało zanurzone w cieczy (częściowo lub całkowicie) działa siła wyporu skierowana do góry, równa co do wartości ciężarowi cieczy wypartej przez to ciało:

```
F_w = ρ_cieczy · V_zanurzone · g
```

gdzie:
- `ρ_cieczy` — gęstość cieczy, w której zanurzone jest ciało,
- `V_zanurzone` — objętość tej części ciała, która znajduje się pod powierzchnią cieczy,
- `g` — przyspieszenie ziemskie.

<div align="center">

<svg width="240" height="240" viewBox="0 0 240 240" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ciało zanurzone w cieczy z zaznaczoną siłą wyporu i ciężarem">
  <defs>
    <marker id="arrow2" markerWidth="10" markerHeight="10" refX="5" refY="5" orient="auto">
      <path d="M0,0 L10,5 L0,10 Z" fill="#1b2b34"/>
    </marker>
  </defs>
  <line x1="30" y1="20" x2="30" y2="210" stroke="#1b2b34" stroke-width="2"/>
  <line x1="210" y1="20" x2="210" y2="210" stroke="#1b2b34" stroke-width="2"/>
  <line x1="30" y1="210" x2="210" y2="210" stroke="#1b2b34" stroke-width="2"/>
  <rect x="32" y="30" width="176" height="178" fill="#bfe3f5" opacity="0.8"/>
  <line x1="32" y1="30" x2="208" y2="30" stroke="#1b3a4b" stroke-width="1.5" stroke-dasharray="4,3"/>

  <rect x="95" y="100" width="50" height="50" fill="#9a9a9a" stroke="#1b2b34" stroke-width="2"/>

  <line x1="120" y1="95" x2="120" y2="50" stroke="#0b6e2b" stroke-width="3" marker-end="url(#arrow2)"/>
  <text x="128" y="65" font-size="13" font-family="sans-serif" fill="#0b6e2b">F_w (wypór)</text>

  <line x1="120" y1="155" x2="120" y2="195" stroke="#a11414" stroke-width="3" marker-end="url(#arrow2)"/>
  <text x="128" y="190" font-size="13" font-family="sans-serif" fill="#a11414">Q (ciężar)</text>
</svg>
<p><em>Rys. 4. Ciało zanurzone w cieczy. Siła wyporu F_w skierowana jest w górę, a ciężar ciała Q — w dół. To, czy ciało tonie, pływa, czy unosi się w miejscu, zależy od tego, która z tych sił jest większa (albo czy są równe).</em></p>
</div>

### Warunki pływania ciał

Porównujemy ciężar ciała `Q = m · g = ρ_ciała · V · g` z siłą wyporu `F_w`:

- jeśli `ρ_ciała > ρ_cieczy` → ciężar jest większy od siły wyporu (nawet gdy ciało jest w pełni zanurzone) → **ciało tonie**,
- jeśli `ρ_ciała = ρ_cieczy` → ciężar równa się sile wyporu przy pełnym zanurzeniu → **ciało „zawisa” wewnątrz cieczy** (nie tonie i nie wypływa na powierzchnię),
- jeśli `ρ_ciała < ρ_cieczy` → ciało wypływa na powierzchnię i **pływa**, zanurzając się tylko częściowo — na tyle, żeby siła wyporu (od zanurzonej części) zrównoważyła cały jego ciężar.

<div align="center">

<svg width="380" height="240" viewBox="0 0 380 240" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Trzy ciała o różnej gęstości w wodzie — pływające, zawieszone i tonące">
  <line x1="20" y1="20" x2="20" y2="220" stroke="#1b2b34" stroke-width="2"/>
  <line x1="360" y1="20" x2="360" y2="220" stroke="#1b2b34" stroke-width="2"/>
  <line x1="20" y1="220" x2="360" y2="220" stroke="#1b2b34" stroke-width="2"/>
  <rect x="22" y="60" width="336" height="158" fill="#bfe3f5" opacity="0.8"/>
  <line x1="22" y1="60" x2="358" y2="60" stroke="#1b3a4b" stroke-width="1.5" stroke-dasharray="4,3"/>

  <!-- cialo A: plywa, czesciowo nad powierzchnia -->
  <rect x="60" y="40" width="60" height="45" fill="#d9c08a" stroke="#1b2b34" stroke-width="2"/>
  <text x="62" y="105" font-size="12" font-family="sans-serif" fill="#1b2b34">A: pływa</text>
  <text x="55" y="120" font-size="11" font-family="sans-serif" fill="#1b2b34">(ρ_A &lt; ρ_wody)</text>

  <!-- cialo B: zawisa w srodku cieczy -->
  <rect x="160" y="120" width="55" height="45" fill="#a8a8d8" stroke="#1b2b34" stroke-width="2"/>
  <text x="150" y="180" font-size="12" font-family="sans-serif" fill="#1b2b34">B: zawisa</text>
  <text x="148" y="195" font-size="11" font-family="sans-serif" fill="#1b2b34">(ρ_B = ρ_wody)</text>

  <!-- cialo C: lezy na dnie -->
  <rect x="270" y="180" width="55" height="40" fill="#707070" stroke="#1b2b34" stroke-width="2"/>
  <text x="270" y="235" font-size="12" font-family="sans-serif" fill="#1b2b34">C: tonie (ρ_C &gt; ρ_wody)</text>
</svg>
<p><em>Rys. 5. Trzy ciała o różnych gęstościach w tym samym naczyniu z wodą: A pływa (wystaje ponad powierzchnię), B „zawisa” wewnątrz cieczy, C leży na dnie.</em></p>
</div>

### Przykład 1 (czy ciało tonie, czy pływa?)

**Treść zadania:** Sześcian aluminiowy o krawędzi 10 cm zanurzono całkowicie w wodzie. Gęstość aluminium wynosi 2700 kg/m³, gęstość wody — 1000 kg/m³, g = 10 N/kg. Sprawdź, czy sześcian utonie, czy wypłynie na powierzchnię, obliczając siłę wyporu i ciężar sześcianu.

**Rozwiązanie krok po kroku:**
1. Obliczamy objętość sześcianu: `V = a³ = (0,1 m)³ = 0,001 m³`.
2. Obliczamy masę sześcianu: `m = ρ_Al · V = 2700 kg/m³ × 0,001 m³ = 2,7 kg`.
3. Obliczamy ciężar sześcianu: `Q = m · g = 2,7 kg × 10 N/kg = 27 N`.
4. Obliczamy siłę wyporu (sześcian jest w pełni zanurzony, więc V_zanurzone = V): `F_w = ρ_wody · V · g = 1000 kg/m³ × 0,001 m³ × 10 N/kg = 10 N`.
5. Porównujemy: `Q = 27 N > F_w = 10 N`.

**Odpowiedź:** Ponieważ ciężar sześcianu (27 N) jest większy od siły wyporu (10 N), sześcian aluminiowy utonie w wodzie.

### Przykład 2 (jaka część ciała jest zanurzona, gdy ciało pływa)

**Treść zadania:** Kawałek lodu o gęstości 920 kg/m³ pływa na powierzchni wody o gęstości 1000 kg/m³. Jaka część objętości lodu znajduje się pod wodą?

**Rozwiązanie krok po kroku:**
1. Ciało pływa, czyli jest w równowadze: siła wyporu równa się ciężarowi ciała: `F_w = Q`.
2. Zapisujemy to wzorami: `ρ_wody · V_zanurzone · g = ρ_lodu · V_całkowite · g`.
3. Skracamy `g` po obu stronach i przekształcamy: `V_zanurzone / V_całkowite = ρ_lodu / ρ_wody`.
4. Podstawiamy dane: `V_zanurzone / V_całkowite = 920 / 1000 = 0,92`.

**Odpowiedź:** Pod wodą znajduje się 92% objętości lodu (widoczne jest tylko 8% — to dlatego góry lodowe są dużo większe pod wodą, niż się wydaje znad powierzchni).

---

## Quiz

Poniższe pytania stylistycznie nawiązują do zadań konkursu „zDolny Ślązak" (etap szkolny), ale są całkowicie oryginalne.

**1.** Bryłka pewnego metalu ma masę 356 g i objętość 40 cm³. Korzystając z tabeli gęstości z rozdziału 5.1, wskaż, z jakiego metalu prawdopodobnie jest wykonana bryłka.
- [ ] A. aluminium
- [ ] B. żelazo/stal
- [ ] C. miedź
- [ ] D. ołów

**2.** Sześcian wykonany z pewnego tworzywa ma krawędź 5 cm i masę 250 g. Oblicz gęstość tego tworzywa (podaj wynik w g/cm³) i zapisz, czy tworzywo to utonie w wodzie, czy będzie pływać.

**3.** Oceń prawdziwość poniższych zdań (P/F):
   a) Napięcie powierzchniowe jest skutkiem sił spójności (przyciągania) między cząsteczkami cieczy.
   b) Kropla wody ma kształt zbliżony do kuli głównie dlatego, że działa na nią siła wyporu.
   c) Dodanie płynu do mycia naczyń zwiększa napięcie powierzchniowe wody.
   d) Dzięki napięciu powierzchniowemu niektóre lekkie przedmioty gęstsze od wody mogą utrzymać się na jej powierzchni.

**4.** Które z poniższych zjawisk NIE da się wyjaśnić napięciem powierzchniowym?
- [ ] A. Utrzymywanie się nartnika (owada) na powierzchni stawu.
- [ ] B. Kulisty kształt małych kropli rosy na liściu.
- [ ] C. Wznoszenie się wody w wąskiej rurce włoskowatej (kapilarze).
- [ ] D. Wzrost temperatury wody podgrzewanej w czajniku.

**5.** Na wykresie zależności ciśnienia hydrostatycznego wody od głębokości zanurzenia zauważono, że na głębokości 20 cm ciśnienie wynosi 2000 Pa. Jakie będzie ciśnienie hydrostatyczne na głębokości 50 cm (przyjmij, że zależność jest liniowa, tak jak wynika ze wzoru p = ρgh)?
- [ ] A. 800 Pa
- [ ] B. 2000 Pa
- [ ] C. 5000 Pa
- [ ] D. 8000 Pa

**6.** Do dwóch naczyń o różnych kształtach (jedno węższe, drugie szersze) nalano tę samą wodę do tej samej wysokości, licząc od dna. Wpisz odpowiedni znak (>, =, <) pomiędzy: ciśnienie hydrostatyczne na dnie węższego naczynia `……` ciśnienie hydrostatyczne na dnie szerszego naczynia.

**7.** Oceń prawdziwość poniższych zdań o prawie Pascala (P/F):
   a) Ciśnienie wywołane siłą działającą na ciecz zamkniętą w naczyniu rozchodzi się jednakowo we wszystkich kierunkach.
   b) W podnośniku hydraulicznym mniejsza siła na małym tłoku może wytworzyć większą siłę na dużym tłoku, ponieważ ciśnienia po obu stronach są sobie równe.
   c) Prawo Pascala dotyczy wyłącznie cieczy, nigdy gazów.

**8.** Kulka o objętości 10 cm³ i masie 12 g zanurzona jest całkowicie w oleju o gęstości 0,92 g/cm³. Jaka siła wyporu działa na kulkę? (przyjmij g = 10 N/kg; wynik podaj w niutonach)
- [ ] A. 0,092 N
- [ ] B. 0,12 N
- [ ] C. 0,92 N
- [ ] D. 9,2 N

**9.** Balonik wypełniony helem, puszczony wolno, wznosi się do góry zamiast opadać na ziemię. Które zdanie najlepiej to wyjaśnia?
- [ ] A. Hel nie ma masy, więc grawitacja na niego nie działa.
- [ ] B. Gęstość helu jest mniejsza od gęstości powietrza, więc siła wyporu działająca na balonik jest większa niż jego ciężar.
- [ ] C. Balonik unosi się, ponieważ napięcie powierzchniowe odpycha go od ziemi.
- [ ] D. Gęstość helu jest większa od gęstości powietrza, ale ciśnienie atmosferyczne pcha balonik w górę.

**10.** Drewniana kostka o krawędzi 4 cm i masie 51,2 g pływa spokojnie na powierzchni wody (przyjmij g = 10 N/kg, ρ_wody = 1000 kg/m³). Oblicz:
   a) siłę wyporu działającą na kostkę,
   b) jaka część objętości kostki znajduje się pod wodą.
