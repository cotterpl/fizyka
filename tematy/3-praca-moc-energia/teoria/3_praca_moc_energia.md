# 3. Praca, moc, energia

Ten dział łączy ze sobą cztery pojęcia, które w życiu codziennym mylimy: **pracę**, **moc**, **energię** i "wysiłek". W fizyce każde z nich ma ścisłą definicję i swój wzór. Dobra wiadomość: wszystkie cztery podtematy trzymają się jednej wspólnej idei — energia nie znika i nie powstaje znikąd, tylko przechodzi z jednej postaci w drugą albo jest przekazywana od ciała do ciała właśnie *poprzez pracę*.

---

## 3.1. Praca mechaniczna i moc

### Czym jest praca mechaniczna?

W fizyce praca jest wykonywana tylko wtedy, gdy **na ciało działa siła** i **ciało pod wpływem tej siły przemieszcza się**, a siła (a przynajmniej jej część) ma zwrot zgodny z kierunkiem tego przemieszczenia.

To ważne zastrzeżenie! Jeśli pchasz ciężką szafę z całych sił, a ona ani drgnie — z punktu widzenia fizyki **nie wykonujesz żadnej pracy** (choć Twoje mięśnie się zmęczą). Podobnie tragarz niosący walizkę poziomo, idąc równym krokiem, nie wykonuje pracy nad walizką w kierunku pionowym (siła nacisku ręki jest pionowa, a przemieszczenie poziome) — pracę wykonuje jedynie siła, która pcha go do przodu.

### Wzór na pracę

Gdy siła **F** działa zgodnie z kierunkiem przemieszczenia **s** (albo dokładnie przeciwnie do niego), pracę liczymy ze wzoru:

**W = F · s**

gdzie:
- W — praca mechaniczna, jednostka: **dżul (J)**
- F — siła, jednostka: niuton (N)
- s — droga (przemieszczenie), jednostka: metr (m)

1 dżul to praca wykonana przez siłę 1 N na drodze 1 m: **1 J = 1 N · m**.

Jeśli siła jest skierowana *przeciwnie* do ruchu (np. tarcie hamujące sanki), praca tej siły jest ujemna — siła "zabiera" energię ciału, zamiast mu jej przekazywać.

### Praca z wykresu F(s)

Bardzo lubianym typem zadania konkursowego jest odczytanie pracy z wykresu zależności siły od drogi. Wtedy **praca jest równa polu powierzchni pod wykresem** F(s) (między wykresem a osią s).

<div align="center">

<svg viewBox="0 0 340 220" width="100%" style="max-width:440px" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="0" width="340" height="220" fill="white" stroke="#dcdcdc"/>
  <!-- osie -->
  <line x1="45" y1="180" x2="310" y2="180" stroke="#333" stroke-width="2"/>
  <line x1="45" y1="180" x2="45" y2="20" stroke="#333" stroke-width="2"/>
  <polygon points="310,180 300,175 300,185" fill="#333"/>
  <polygon points="45,20 40,30 50,30" fill="#333"/>
  <!-- zacieniowane pole = praca -->
  <rect x="45" y="70" width="180" height="110" fill="#a5d8ff" fill-opacity="0.65" stroke="none"/>
  <!-- linia siły F = const -->
  <line x1="45" y1="70" x2="225" y2="70" stroke="#1971c2" stroke-width="3"/>
  <line x1="225" y1="70" x2="225" y2="180" stroke="#1971c2" stroke-width="1.5" stroke-dasharray="5,4"/>
  <!-- opisy -->
  <text x="170" y="135" font-size="15" text-anchor="middle" fill="#0b4a8f" font-weight="bold">W = F·s</text>
  <text x="170" y="155" font-size="12" text-anchor="middle" fill="#0b4a8f">(pole zacieniowane)</text>
  <text x="300" y="200" font-size="13" fill="#333">s [m]</text>
  <text x="15" y="30" font-size="13" fill="#333">F [N]</text>
  <text x="222" y="197" font-size="12" fill="#333" text-anchor="middle">5</text>
  <text x="30" y="74" font-size="12" fill="#333" text-anchor="end">20</text>
  <line x1="45" y1="70" x2="40" y2="70" stroke="#333"/>
  <line x1="225" y1="180" x2="225" y2="185" stroke="#333"/>
</svg>

*Rysunek 1. Gdy siła F jest stała, wykres F(s) jest poziomą linią, a praca to pole prostokąta pod nią: W = 20 N · 5 m = 100 J.*

</div>

Jeśli wykres nie jest prostokątem, tylko np. trójkątem albo trapezem (siła rośnie lub maleje w miarę drogi), pole liczymy jak pole odpowiedniej figury geometrycznej — to właśnie lubi sprawdzać zDolny Ślązak.

### Moc

Moc mówi nam, **jak szybko** wykonywana jest praca — czy silnik "śpieszy się", czy nie.

**P = W / t**

gdzie:
- P — moc, jednostka: **wat (W)**
- W — praca (J)
- t — czas (s)

1 wat to moc urządzenia, które w ciągu 1 sekundy wykonuje pracę 1 dżula: **1 W = 1 J/s**.

W praktyce spotkasz też jednostki pochodne: **1 kW = 1000 W**, oraz jednostkę pracy/energii często używaną na rachunkach za prąd: **1 kWh** (kilowatogodzina) = praca wykonana przez urządzenie o mocy 1 kW w ciągu 1 godziny = 3 600 000 J.

### Przykład

**Treść zadania:** Kurier ciągnie wózek z paczkami siłą 40 N, zgodną z kierunkiem ruchu, na odcinku 15 m. Cała czynność zajęła mu 20 sekund. Oblicz pracę wykonaną przez kuriera oraz moc, z jaką pracował.

**Rozwiązanie krok po kroku:**

1. Dane: F = 40 N, s = 15 m, t = 20 s.
2. Obliczamy pracę: W = F · s = 40 N · 15 m = 600 J.
3. Obliczamy moc: P = W / t = 600 J / 20 s = 30 W.

**Odpowiedź:** Kurier wykonał pracę 600 J, pracując ze średnią mocą 30 W.

---

## 3.2. Maszyny proste: dźwignia jedno- i dwustronna, bloki, kołowrotek, równia pochyła

### Złota reguła mechaniki

Zanim omówimy poszczególne maszyny proste, poznaj najważniejszą zasadę tego rozdziału — **złotą regułę mechaniki**:

> Żadna maszyna prosta nie daje "zysku energetycznego". Ile razy maszyna zmniejsza potrzebną siłę, tyle samo razy trzeba tę siłę przyłożyć na dłuższej drodze — i odwrotnie. Praca wykonana przy użyciu maszyny prostej (pomijając tarcie) jest taka sama, jak bez niej.

To bezpośrednia konsekwencja wzoru W = F · s: skoro praca ma być taka sama, a zmniejszamy F, to musimy proporcjonalnie zwiększyć s.

### Dźwignia jednostronna i dwustronna

**Dźwignia** to sztywny pręt (belka) mogący obracać się wokół punktu podparcia zwanego **osią obrotu** (albo punktem podparcia).

- **Dźwignia dwustronna** — punkt podparcia znajduje się *między* punktami przyłożenia obu sił (np. huśtawka, waga szalkowa, nożyczki, huśtawka na placu zabaw).
- **Dźwignia jednostronna** — punkt podparcia znajduje się *na końcu*, a obie siły działają po tej samej stronie osi obrotu (np. taczka, dziadek do orzechów, otwieracz do butelek).

Warunkiem równowagi dźwigni (obu rodzajów) jest równość **momentów sił** — czyli iloczynów siły i długości jej ramienia (odległości od osi obrotu, mierzonej prostopadle do kierunku siły):

**F₁ · r₁ = F₂ · r₂**

gdzie r₁, r₂ to ramiona sił F₁ i F₂.

<div align="center">

<svg viewBox="0 0 360 200" width="100%" style="max-width:460px" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="0" width="360" height="200" fill="white" stroke="#dcdcdc"/>
  <!-- belka dźwigni -->
  <line x1="40" y1="100" x2="320" y2="100" stroke="#5c3a21" stroke-width="6" stroke-linecap="round"/>
  <!-- oś obrotu / trójkąt podparcia -->
  <polygon points="180,100 165,130 195,130" fill="#495057"/>
  <text x="180" y="150" font-size="11" text-anchor="middle" fill="#495057">oś obrotu</text>
  <!-- ramiona -->
  <line x1="40" y1="112" x2="178" y2="112" stroke="#868e96" stroke-width="1" stroke-dasharray="3,3"/>
  <line x1="182" y1="112" x2="320" y2="112" stroke="#868e96" stroke-width="1" stroke-dasharray="3,3"/>
  <text x="110" y="127" font-size="13" text-anchor="middle" fill="#333">r₁</text>
  <text x="250" y="127" font-size="13" text-anchor="middle" fill="#333">r₂</text>
  <!-- siły -->
  <line x1="40" y1="100" x2="40" y2="45" stroke="#e03131" stroke-width="3"/>
  <polygon points="40,45 35,55 45,55" fill="#e03131"/>
  <text x="40" y="35" font-size="14" text-anchor="middle" fill="#e03131" font-weight="bold">F₁</text>
  <line x1="320" y1="100" x2="320" y2="55" stroke="#1971c2" stroke-width="3"/>
  <polygon points="320,55 315,65 325,65" fill="#1971c2"/>
  <text x="320" y="45" font-size="14" text-anchor="middle" fill="#1971c2" font-weight="bold">F₂</text>
  <text x="180" y="20" font-size="13" text-anchor="middle" fill="#333">warunek równowagi: F₁·r₁ = F₂·r₂</text>
</svg>

*Rysunek 2. Dźwignia dwustronna — oś obrotu leży między punktami przyłożenia sił F₁ i F₂. Krótsze ramię wymaga większej siły.*

</div>

Im krótsze ramię, tym większa musi być siła, żeby "wygrać" z siłą po drugiej stronie — dlatego łatwiej jest podważyć kamień długim drągiem (długie ramię F₁) niż krótkim.

### Bloki

- **Blok stały (nieruchomy)** — kółko z rowkiem, osadzone nieruchomo (np. na maszcie flagowym). Nie zmniejsza potrzebnej siły (F = Q, gdzie Q to ciężar), a jedynie **zmienia kierunek działania siły** — wygodniej jest ciągnąć linę w dół, niż podnosić ciężar w górę gołymi rękami.
- **Blok ruchomy** — kółko zawieszone na ciężarze, które porusza się razem z nim. Zmniejsza potrzebną siłę **dwukrotnie** (F = Q/2), ale zgodnie ze złotą regułą mechaniki trzeba pociągnąć za linę na drodze **dwa razy dłuższej** niż wysokość, na jaką podnosimy ciężar.

```
blok stały:                  blok ruchomy:
      ┌─┐                         ┌─┐  (zaczep na suficie)
   ───┤O├───  (lina)              │ │
      └─┘                         │ │
       │                         ┌┴─┴┐
       │  F = Q                 │ O │  ← blok jedzie razem z ciężarem
      ┌┴┐                       └┬─┬┘
      │Q│                        │ │  F = Q/2, droga liny = 2h
      └─┘                       ┌┴─┴┐
                                 │ Q │
                                 └───┘
```

### Kołowrotek

**Kołowrotek** (np. korba studni) to walec obracający się razem z przymocowaną do niego korbą (rączką) o większym promieniu. Działa jak dźwignia „nawinięta" na oś: promień korby **R** to dłuższe ramię, a promień walca **r**, na który nawinięta jest lina z ciężarem, to krótsze ramię.

**F · R = Q · r**

Im dłuższa korba (większe R) w porównaniu do promienia walca r, tym mniejszej siły F potrzeba, by podnieść ciężar Q — kosztem tego, że trzeba nią wykonać więcej obrotów.

### Równia pochyła

**Równia pochyła** to nachylona powierzchnia (rampa, podjazd), która pozwala wciągnąć ciężar na pewną wysokość, używając mniejszej siły niż przy podnoszeniu go pionowo — kosztem dłuższej drogi.

<div align="center">

<svg viewBox="0 0 340 220" width="100%" style="max-width:440px" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="0" width="340" height="220" fill="white" stroke="#dcdcdc"/>
  <!-- trójkąt równi -->
  <polygon points="30,190 300,190 300,60" fill="#e9ecef" stroke="#495057" stroke-width="2"/>
  <!-- blok na równi -->
  <rect x="175" y="108" width="34" height="24" fill="#f08c00" stroke="#5c3a21" stroke-width="1.5" transform="rotate(-25 192 120)"/>
  <!-- siła ciężkości mg -->
  <line x1="192" y1="120" x2="192" y2="175" stroke="#e03131" stroke-width="2.5"/>
  <polygon points="192,175 187,165 197,165" fill="#e03131"/>
  <text x="204" y="175" font-size="13" fill="#e03131" font-weight="bold">Q = mg</text>
  <!-- siła wzdłuż równi F -->
  <line x1="192" y1="120" x2="150" y2="150" stroke="#1971c2" stroke-width="2.5"/>
  <polygon points="150,150 162,148 158,158" fill="#1971c2"/>
  <text x="120" y="150" font-size="13" fill="#1971c2" font-weight="bold">F</text>
  <!-- oznaczenia s, h, kąt -->
  <text x="150" y="205" font-size="13" fill="#333">s (długość równi)</text>
  <text x="308" y="125" font-size="13" fill="#333">h</text>
  <line x1="300" y1="190" x2="300" y2="60" stroke="#868e96" stroke-width="1" stroke-dasharray="3,3"/>
  <text x="55" y="182" font-size="13" fill="#333">α</text>
</svg>

*Rysunek 3. Równia pochyła. Ciężar Q = mg da się rozłożyć na składową wzdłuż równi (którą trzeba pokonać siłą F) i składową prostopadłą do równi.*

</div>

Pomijając tarcie, warunek "opłacalności" równi (znowu złota reguła mechaniki!) to:

**F · s = Q · h**, czyli **F = Q · h / s**

gdzie:
- F — siła potrzebna do wciągnięcia ciała wzdłuż równi,
- Q — ciężar ciała (Q = m · g),
- h — wysokość równi,
- s — długość równi (drogi po skosie).

Im dłuższa i łagodniejsza równia (mniejszy kąt nachylenia α) przy tej samej wysokości h, tym mniejsza siła F wystarczy — ale trzeba pokonać dłuższą drogę s.

### Przykład

**Treść zadania (dźwignia):** Na dźwigni dwustronnej po jednej stronie osi obrotu, w odległości 60 cm od niej, działa siła 15 N. Jaka siła musi działać po drugiej stronie, w odległości 20 cm od osi obrotu, aby dźwignia pozostała w równowadze?

**Rozwiązanie krok po kroku:**

1. Dane: F₁ = 15 N, r₁ = 60 cm = 0,6 m, r₂ = 20 cm = 0,2 m.
2. Warunek równowagi: F₁ · r₁ = F₂ · r₂.
3. Przekształcamy: F₂ = (F₁ · r₁) / r₂ = (15 N · 0,6 m) / 0,2 m = 45 N.

**Odpowiedź:** Po drugiej stronie musi działać siła 45 N (krótsze ramię wymaga większej siły).

**Treść zadania (równia pochyła):** Równia pochyła ma długość 5 m i wysokość 1 m. Jaką najmniejszą siłą (pomijając tarcie) trzeba ciągnąć wzdłuż równi skrzynię o ciężarze 250 N, aby wjechała ona na szczyt równi?

**Rozwiązanie krok po kroku:**

1. Dane: s = 5 m, h = 1 m, Q = 250 N.
2. Wzór: F = Q · h / s.
3. Obliczamy: F = 250 N · 1 m / 5 m = 50 N.

**Odpowiedź:** Wystarczy siła 50 N — pięć razy mniejsza niż ciężar skrzyni, bo równia jest 5 razy dłuższa niż wysoka.

---

## 3.3. Energia kinetyczna, potencjalna grawitacji, potencjalna sprężystości

### Czym jest energia?

**Energia** to zdolność ciała do wykonania pracy. Jeśli ciało ma energię, to (bezpośrednio albo pośrednio) może tę energię przekazać innemu ciału właśnie w postaci pracy. Energię, tak jak pracę, mierzymy w **dżulach (J)**.

W mechanice wyróżniamy trzy podstawowe rodzaje energii mechanicznej.

### Energia kinetyczna (energia ruchu)

Każde poruszające się ciało ma energię kinetyczną — zależy ona od jego masy i prędkości:

**Ek = ½ · m · v²**

gdzie m — masa ciała (kg), v — prędkość ciała (m/s).

Zwróć uwagę: energia kinetyczna rośnie z **kwadratem** prędkości! Jadąc dwa razy szybciej, masz aż **cztery razy** więcej energii kinetycznej — to dlatego podwojenie prędkości samochodu tak drastycznie wydłuża drogę hamowania.

### Energia potencjalna grawitacji

Ciało uniesione nad powierzchnią Ziemi (albo nad innym poziomem odniesienia) ma energię potencjalną grawitacji — "zmagazynowaną" dzięki jego położeniu w polu grawitacyjnym:

**Ep = m · g · h**

gdzie m — masa ciała (kg), g — przyspieszenie grawitacyjne (na Ziemi ok. 10 m/s² — tej wartości używamy w zadaniach szkolnych), h — wysokość nad poziomem odniesienia (m).

Poziom odniesienia (h = 0) możemy wybrać sami — np. podłogę, parter budynku albo powierzchnię stołu — ważne jest tylko, żeby konsekwentnie liczyć wysokości względem tego samego poziomu.

### Energia potencjalna sprężystości

Odkształcone ciało sprężyste (np. rozciągnięta lub ściśnięta sprężyna, napięta cięciwa łuku) magazynuje energię potencjalną sprężystości:

**Esp = ½ · k · x²**

gdzie k — współczynnik sprężystości sprężyny (N/m), x — wielkość odkształcenia (rozciągnięcia lub ściśnięcia) względem długości swobodnej (m).

Podobnie jak przy energii kinetycznej, tutaj też liczy się **kwadrat** — rozciągnięcie sprężyny dwa razy mocniej daje **cztery razy** więcej zmagazynowanej energii.

### Przykład

**Treść zadania:** Piłka o masie 0,5 kg leży na półce na wysokości 2 m nad podłogą, a następnie zostaje popchnięta i spada, uzyskując tuż przed podłogą prędkość 6 m/s. Oblicz: a) energię potencjalną grawitacji piłki, gdy leżała na półce (g = 10 m/s²), b) energię kinetyczną piłki tuż przed uderzeniem o podłogę.

**Rozwiązanie krok po kroku:**

1. Dane: m = 0,5 kg, h = 2 m, v = 6 m/s, g = 10 m/s².
2. a) Ep = m · g · h = 0,5 kg · 10 m/s² · 2 m = 10 J.
3. b) Ek = ½ · m · v² = ½ · 0,5 kg · (6 m/s)² = 0,25 kg · 36 m²/s² = 9 J.

**Odpowiedź:** Na półce piłka miała energię potencjalną 10 J, a tuż przed podłogą energię kinetyczną 9 J (różnica to energia stracona np. na opór powietrza).

---

## 3.4. Zasada zachowania energii mechanicznej

### Treść zasady

**Energia mechaniczna** ciała to suma jego energii kinetycznej i energii potencjalnej (grawitacji i/lub sprężystości):

**Ec = Ek + Ep**

Jeżeli na ciało nie działają siły tarcia ani opory ruchu (mówimy wtedy o **układzie zamkniętym** albo **braku strat energii**), to zachodzi **zasada zachowania energii mechanicznej**:

> Całkowita energia mechaniczna ciała pozostaje stała — energia kinetyczna może zamieniać się w potencjalną i odwrotnie, ale ich suma się nie zmienia.

**Ek + Ep = const**, czyli np. dla ciała spadającego swobodnie: **Ek₁ + Ep₁ = Ek₂ + Ep₂**

To jedno z najczęściej sprawdzanych praw na konkursie zDolny Ślązak — zwłaszcza w wersji "co się dzieje z energią piłki w locie" albo "co się dzieje z energią sanek zjeżdżających z górki".

<div align="center">

<svg viewBox="0 0 380 260" width="100%" style="max-width:480px" xmlns="http://www.w3.org/2000/svg">
  <rect x="0" y="0" width="380" height="260" fill="white" stroke="#dcdcdc"/>
  <!-- tor spadania -->
  <circle cx="60" cy="35" r="10" fill="#f08c00"/>
  <circle cx="60" cy="120" r="10" fill="#f08c00"/>
  <circle cx="60" cy="205" r="10" fill="#f08c00"/>
  <line x1="60" y1="45" x2="60" y2="110" stroke="#adb5bd" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="60" y1="130" x2="60" y2="195" stroke="#adb5bd" stroke-width="1.5" stroke-dasharray="4,3"/>
  <line x1="20" y1="215" x2="340" y2="215" stroke="#495057" stroke-width="2"/>
  <text x="30" y="35" font-size="12" text-anchor="end" fill="#333">A</text>
  <text x="30" y="120" font-size="12" text-anchor="end" fill="#333">B</text>
  <text x="30" y="205" font-size="12" text-anchor="end" fill="#333">C</text>
  <!-- słupki energii dla A -->
  <rect x="150" y="15" width="24" height="40" fill="#4dabf7"/>
  <rect x="150" y="15" width="24" height="0" fill="#fa5252"/>
  <text x="162" y="65" font-size="10" text-anchor="middle" fill="#333">Ep=100%</text>
  <text x="162" y="77" font-size="10" text-anchor="middle" fill="#333">Ek=0%</text>
  <!-- słupki energii dla B -->
  <rect x="230" y="35" width="24" height="20" fill="#4dabf7"/>
  <rect x="230" y="55" width="24" height="20" fill="#fa5252"/>
  <text x="242" y="85" font-size="10" text-anchor="middle" fill="#333">Ep=50%</text>
  <text x="242" y="97" font-size="10" text-anchor="middle" fill="#333">Ek=50%</text>
  <!-- słupki energii dla C -->
  <rect x="310" y="55" width="24" height="0" fill="#4dabf7"/>
  <rect x="310" y="15" width="24" height="40" fill="#fa5252"/>
  <text x="322" y="65" font-size="10" text-anchor="middle" fill="#333">Ep=0%</text>
  <text x="322" y="77" font-size="10" text-anchor="middle" fill="#333">Ek=100%</text>
  <line x1="150" y1="55" x2="174" y2="55" stroke="none"/>
  <text x="60" y="240" font-size="12" fill="#333" text-anchor="middle">spadające ciało</text>
  <text x="242" y="240" font-size="12" fill="#333" text-anchor="middle">energia w punktach A, B, C (Ec = Ek + Ep = const)</text>
  <rect x="150" y="112" width="12" height="12" fill="#4dabf7"/>
  <text x="168" y="122" font-size="11" fill="#333">Ep (potencjalna)</text>
  <rect x="150" y="130" width="12" height="12" fill="#fa5252"/>
  <text x="168" y="140" font-size="11" fill="#333">Ek (kinetyczna)</text>
</svg>

*Rysunek 4. Ciało spadające swobodnie z punktu A do C. Suma słupków Ep + Ek (czyli energia mechaniczna) jest w każdym punkcie taka sama — zmienia się tylko proporcja między nimi.*

</div>

Gdy pojawia się tarcie lub opór powietrza, energia mechaniczna **nie jest** zachowana — część zamienia się w energię wewnętrzną (ciepło), o czym dowiesz się więcej w dziale o termodynamice. Wtedy energia mechaniczna na końcu ruchu jest mniejsza niż na początku.

### Przykład

**Treść zadania:** Kamień o masie 0,2 kg spada swobodnie (bez oporów powietrza) z wysokości 5 m nad ziemią. Korzystając z zasady zachowania energii mechanicznej, oblicz prędkość kamienia tuż przed uderzeniem o ziemię (g = 10 m/s²).

**Rozwiązanie krok po kroku:**

1. Dane: m = 0,2 kg, h = 5 m, g = 10 m/s², v_początkowe = 0 (kamień spada "z ręki", bez prędkości początkowej).
2. Na początku (na wysokości h) cała energia mechaniczna to energia potencjalna: Ec = Ep = m · g · h.
3. Tuż przed ziemią (h = 0) cała energia mechaniczna to energia kinetyczna: Ec = Ek = ½ · m · v².
4. Z zasady zachowania energii: m · g · h = ½ · m · v². Masa m upraszcza się po obu stronach!
5. g · h = ½ · v², czyli v² = 2 · g · h = 2 · 10 m/s² · 5 m = 100 m²/s².
6. v = √100 m²/s² = 10 m/s.

**Odpowiedź:** Kamień uderzy o ziemię z prędkością 10 m/s — i zauważ, że wynik w ogóle nie zależy od masy kamienia!

---

## Quiz

Poniższe zadania są w stylu konkursu zDolny Ślązak (etap szkolny). Powodzenia!

**1.** Które z poniższych zdań o pracy mechanicznej jest prawdziwe?
- [ ] A. Praca jest wykonywana zawsze, gdy na ciało działa jakakolwiek siła.
- [ ] B. Praca jest wykonywana tylko wtedy, gdy ciało się przemieszcza pod działaniem siły mającej składową zgodną z kierunkiem tego przemieszczenia.
- [ ] C. Praca zależy wyłącznie od wartości siły, a nie zależy od przebytej drogi.
- [ ] D. Jednostką pracy mechanicznej w układzie SI jest wat.

**2.** Magazynier ciągnie skrzynię siłą 50 N, skierowaną zgodnie z kierunkiem ruchu, na drodze 6 m. Cała czynność trwała 15 sekund. Oblicz pracę wykonaną przez magazyniera oraz moc, z jaką pracował.

**3.** Które stwierdzenie o bloku stałym (nieruchomym) jest prawdziwe?
- [ ] A. Zmniejsza dwukrotnie siłę potrzebną do podniesienia ciężaru.
- [ ] B. Zwiększa drogę, jaką trzeba przeciągnąć linę, w porównaniu z wysokością podnoszenia.
- [ ] C. Zmienia jedynie kierunek działania siły, nie zmieniając jej wartości.
- [ ] D. Jest przykładem równi pochyłej o bardzo dużym kącie nachylenia.

**4.** Oceń prawdziwość poniższych zdań (P/F) dotyczących maszyn prostych:
   a) Blok ruchomy pozwala podnieść ciężar siłą o połowę mniejszą od ciężaru, kosztem dwukrotnie dłuższej drogi przeciągania liny.
   b) W kołowrotku, aby zmniejszyć siłę potrzebną do podniesienia ciężaru, należy zwiększyć promień korby względem promienia walca, na który nawija się lina.
   c) Równia pochyła o mniejszym kącie nachylenia (przy tej samej wysokości) wymaga *większej* siły do wciągnięcia ciała na szczyt niż równia o większym kącie nachylenia.

**5.** Na dźwigni dwustronnej znajdującej się w równowadze, siła 25 N działa w odległości 0,4 m od osi obrotu. Jaka siła działa po drugiej stronie dźwigni, w odległości 1,0 m od osi obrotu?

**6.** Ciała A i B poruszają się i mają jednakową energię kinetyczną. Masa ciała A jest 4 razy większa od masy ciała B. Ile razy prędkość ciała B jest większa od prędkości ciała A?
- [ ] A. 2 razy
- [ ] B. 4 razy
- [ ] C. 8 razy
- [ ] D. 16 razy

**7.** Winda podnosi osobę o masie 70 kg na wysokość 12 m ponad parter. Oblicz przyrost energii potencjalnej grawitacji tej osoby (g = 10 m/s²). Podaj wynik w dżulach i w kilodżulach.

**8.** Tę samą sprężynę rozciągnięto dwukrotnie mocniej niż poprzednio (współczynnik sprężystości k pozostaje bez zmian). Jak zmieniła się energia potencjalna sprężystości zgromadzona w sprężynie?
- [ ] A. Wzrosła 2 razy.
- [ ] B. Wzrosła 4 razy.
- [ ] C. Zmalała 2 razy.
- [ ] D. Nie zmieniła się.

**9.** Kamień wyrzucono pionowo w górę. Pomijając opór powietrza, oceń prawdziwość poniższych zdań (P/F):
   a) W najwyższym punkcie toru lotu energia kinetyczna kamienia jest równa zero.
   b) Suma energii kinetycznej i energii potencjalnej grawitacji kamienia jest taka sama w każdym punkcie jego lotu (w górę i w dół).
   c) Podczas wznoszenia się kamienia jego energia potencjalna grawitacji maleje, a energia kinetyczna rośnie.

**10.** Kulka o masie 0,5 kg spada swobodnie (bez oporów powietrza) z wysokości 4 m nad podłożem. Korzystając z zasady zachowania energii mechanicznej, oblicz prędkość kulki tuż przed uderzeniem o podłoże (g = 10 m/s²). Wynik podaj z dokładnością do dwóch cyfr znaczących.
