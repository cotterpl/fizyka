# Temat 1: Kinematyka — ruch i jego opis

Kinematyka to dział fizyki, który opisuje **jak** ciała się poruszają — nie zastanawia się jeszcze, **dlaczego** tak się poruszają (tym zajmuje się dynamika, temat 2). W tym rozdziale nauczysz się mówić o ruchu językiem fizyki: co to jest tor i droga, czym różni się prędkość od przyspieszenia, jak czytać wykresy ruchu oraz jak mierzyć i przeliczać jednostki. To fundament, na którym opiera się cała reszta mechaniki — warto go dobrze opanować przed kolejnymi tematami.

---

## 1.1. Względność ruchu, tor a droga

### Ruch jest względny

Ciało **porusza się**, jeśli zmienia swoje położenie względem innego ciała, które nazywamy **układem odniesienia** (albo punktem odniesienia). To bardzo ważne: **nie ma ruchu "samego w sobie"** — zawsze musimy powiedzieć, względem czego coś się porusza.

Klasyczny przykład: siedzisz w jadącym pociągu i czytasz książkę.
- Względem **wnętrza pociągu** (fotela, podłogi) — jesteś w spoczynku, nie zmieniasz położenia.
- Względem **peronu i torów** — poruszasz się razem z pociągiem, np. z prędkością 100 km/h.

Obie odpowiedzi są poprawne! Po prostu opisują ruch względem różnych układów odniesienia.

### Tor a droga — to nie to samo

- **Tor ruchu** — linia (krzywa) zakreślona przez poruszające się ciało w przestrzeni. Tor może być prostoliniowy (linia prosta) albo krzywoliniowy (np. łuk, okrąg, parabola).
- **Droga (s)** — długość toru, czyli jak długi "sznurek" trzeba by rozciągnąć wzdłuż całej trasy ciała. Drogę mierzymy w metrach (m), kilometrach (km) itd. Droga jest zawsze liczbą dodatnią (albo zerem) — nigdy nie jest ujemna.

Co ciekawe, **ten sam ruch może mieć różny tor w zależności od układu odniesienia** — dokładnie tak samo jak sama informacja "porusza się czy nie".

#### Ilustracja: tor tego samego ruchu w dwóch układach odniesienia

Wyobraź sobie osobę w jadącym pociągu, która upuszcza piłeczkę. Zobaczmy, jak wygląda tor lotu piłeczki dla dwóch różnych obserwatorów.

```
UKŁAD ODNIESIENIA: WNĘTRZE POCIĄGU (pasażer siedzi w wagonie)
                 
      ┌───────────────────┐
      │         o          │   o — piłeczka w chwili puszczenia
      │         |          │   
      │         |          │   TOR: linia PROSTA, pionowa
      │         |          │   (piłeczka spada "prosto w dół")
      │         ●          │
      └───────────────────┘

UKŁAD ODNIESIENIA: PERON (obserwator stoi nieruchomo obok torów)

      pociąg jedzie →→→→→→→
      ┌───────────────────┐
      │      o             │    o — start piłeczki
      │        `.          │
      │          `.        │    TOR: łuk (krzywa),
      │            `.      │    bo piłeczka leci jednocześnie
      │              ●     │    w dół i "do przodu" razem z pociągiem
      └───────────────────┘
      ══════════════════════  peron
```

Dla pasażera tor jest prostą pionową linią. Dla obserwatora na peronie — łukiem (krzywą), bo piłeczka porusza się jednocześnie w dół i do przodu (razem z pociągiem). **Oba opisy są prawdziwe** — różnią się tylko układem odniesienia.

> **Uwaga na zadania konkursowe:** W zadaniach zDolny Ślązak bardzo często pojawia się pytanie o to, czy ktoś (np. konduktor idący przez wagon) porusza się względem torów tak samo, jak porusza się względem pociągu. Zawsze czytaj uważnie, **względem czego** pytanie dotyczy ruchu!

### Przykład

**Treść zadania:** Marek jedzie na deskorolce po prostym, płaskim chodniku od ławki do latarni (5 m), a potem zawraca i wraca do ławki. Jaka jest droga przebyta przez Marka? Czy jego tor jest linią prostą?

**Rozwiązanie krok po kroku:**
1. Droga w jedną stronę (ławka → latarnia) wynosi 5 m.
2. Droga w drugą stronę (latarnia → ławka) też wynosi 5 m, bo to ta sama trasa.
3. Całkowita droga to suma: s = 5 m + 5 m = 10 m.
4. Tor — Marek cały czas porusza się po tej samej linii (chodnik jest prosty), więc tor jest odcinkiem prostej — mimo że Marek zawrócił!

**Odpowiedź:** Marek przejechał drogę s = 10 m, a jego tor jest linią prostą (choć przemierzoną "w dwie strony").

*(Warto zauważyć różnicę względem tzw. przemieszczenia — wielkości wektorowej opisującej, o ile i w którym kierunku zmieniło się położenie na końcu ruchu. W tym przykładzie przemieszczenie Marka wynosi 0, bo wrócił do punktu startu, mimo że droga wynosi 10 m. W szkole podstawowej skupiamy się głównie na drodze.)*

---

## 1.2. Ruch jednostajny: droga, prędkość

### Co to jest ruch jednostajny?

**Ruch jednostajny prostoliniowy** to ruch, w którym ciało porusza się po linii prostej i w **równych odstępach czasu pokonuje jednakowe odcinki drogi**. Innymi słowy — wartość prędkości się nie zmienia (jest stała).

### Prędkość

**Prędkość (v)** mówi nam, jak szybko zmienia się droga w czasie. Dla ruchu jednostajnego:

$$v = \frac{s}{t}$$

gdzie:
- $v$ — prędkość (m/s lub km/h)
- $s$ — droga (m lub km)
- $t$ — czas (s, min, h)

Z tego wzoru można też wyznaczyć drogę i czas:

$$s = v \cdot t \qquad\qquad t = \frac{s}{v}$$

### Prędkość średnia

Jeśli ciało nie porusza się jednostajnie (raz szybciej, raz wolniej), możemy policzyć jego **prędkość średnią** — czyli tak, jakby całą drogę pokonało jednostajnie w tym samym czasie:

$$v_{śr} = \frac{s_{całkowite}}{t_{całkowite}}$$

To bardzo częsty typ zadania na konkursach — **prędkość średnia to zawsze cała droga podzielona przez cały czas**, a nie średnia arytmetyczna prędkości cząstkowych!

#### Ilustracja: wykres drogi od czasu s(t) dla ruchu jednostajnego

```
 s [m]
 20 |                        ●
    |                   ╱
 15 |              ╱
    |         ╱
 10 |    ╱
    | ╱
  5 |●
    |
  0 +----+----+----+----+----+----  t [s]
    0    1    2    3    4    5

  Wykres s(t) jest LINIĄ PROSTĄ — to znak rozpoznawczy ruchu jednostajnego!
  Nachylenie (stromość) tej prostej to właśnie wartość prędkości.
```

Im bardziej stroma prosta, tym większa prędkość. Prosta pozioma (nachylenie = 0) oznaczałaby, że ciało stoi w miejscu.

### Przykład

**Treść zadania:** Pociąg towarowy porusza się ruchem jednostajnym z prędkością 72 km/h. Jaką drogę przejedzie w ciągu 15 minut? Podaj wynik w kilometrach.

**Rozwiązanie krok po kroku:**
1. Zamieniamy jednostki tak, by były spójne. Prędkość: 72 km/h. Czas: 15 minut = 0,25 h (bo 15 min : 60 min = 0,25).
2. Korzystamy ze wzoru: $s = v \cdot t$.
3. Podstawiamy dane: $s = 72\ \text{km/h} \cdot 0{,}25\ \text{h} = 18\ \text{km}$.

**Odpowiedź:** Pociąg przejedzie 18 km.

---

## 1.3. Ruch jednostajnie zmienny (przyspieszony, opóźniony): przyspieszenie

### Kiedy prędkość się zmienia

W realnym życiu prędkość rzadko jest stała — samochód rusza z miejsca, rowerzysta hamuje przed skrzyżowaniem. Gdy **prędkość zmienia się o taką samą wartość w każdej sekundzie**, mówimy o **ruchu jednostajnie zmiennym**:

- **ruch jednostajnie przyspieszony** — wartość prędkości rośnie (np. auto przyspiesza),
- **ruch jednostajnie opóźniony** — wartość prędkości maleje (np. auto hamuje).

### Przyspieszenie

**Przyspieszenie (a)** mówi nam, o ile zmienia się prędkość w jednostce czasu:

$$a = \frac{\Delta v}{\Delta t} = \frac{v - v_0}{t}$$

gdzie:
- $a$ — przyspieszenie (m/s²)
- $v_0$ — prędkość początkowa
- $v$ — prędkość końcowa
- $t$ — czas, w którym nastąpiła ta zmiana

Jeśli prędkość rośnie, przyspieszenie jest dodatnie (ruch przyspieszony). Jeśli prędkość maleje, mówimy, że ciało ma **opóźnienie** (czasem zapisywane jako przyspieszenie ujemne względem kierunku ruchu).

Przekształcając wzór, możemy obliczyć prędkość po czasie t, znając przyspieszenie:

$$v = v_0 + a \cdot t$$

Drogę w ruchu jednostajnie przyspieszonym (startującym z $v_0 = 0$) liczymy wzorem:

$$s = \frac{a \cdot t^2}{2}$$

Gdy prędkość początkowa nie jest zerowa, wzór ogólny na drogę to $s = v_0 \cdot t + \frac{a \cdot t^2}{2}$. Łącząc go ze wzorem $v = v_0 + at$ (i eliminując czas t), otrzymujemy przydatny wzór bez czasu, wiążący prędkości i drogę bezpośrednio:

$$v^2 = v_0^2 + 2as$$

(dla ruchu opóźnionego przyspieszenie $a$ wstawiamy ze znakiem minus, np. $v^2 = v_0^2 - 2as$).

### Jednostka przyspieszenia

Przyspieszenie wyrażamy w **metrach na sekundę do kwadratu (m/s²)**. Oznacza to: "o ile metrów na sekundę zmienia się prędkość w ciągu jednej sekundy". Np. $a = 2\ \text{m/s}^2$ znaczy, że co sekundę prędkość rośnie o 2 m/s.

#### Ilustracja: wykres prędkości od czasu v(t) — pole pod wykresem to droga!

```
 v [m/s]
 8 |                          ●
   |                     ╱▓▓▓│
   |                ╱▓▓▓▓▓▓▓│
 4 |           ╱▓▓▓▓▓▓▓▓▓▓▓▓│
   |      ╱▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓│
 0 ●▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓+----  t [s]
   0      1      2      3      4

  Zakreskowane (▓) pole trójkąta pod prostą v(t) = DROGA przebyta w tym czasie!
  Pole trójkąta = 1/2 · podstawa · wysokość = 1/2 · 4 s · 8 m/s = 16 m
```

To bardzo ważna zasada, wykorzystywana w wielu zadaniach konkursowych: **pole powierzchni pod wykresem v(t) (między wykresem a osią czasu) zawsze jest równe drodze przebytej w danym przedziale czasu** — niezależnie od tego, czy ruch jest jednostajny, przyspieszony, czy opóźniony.

### Przykład

**Treść zadania:** Rowerzysta rusza z miejsca (czyli $v_0 = 0$) i porusza się ruchem jednostajnie przyspieszonym. Po 4 sekundach jego prędkość wynosi 8 m/s. Oblicz przyspieszenie roweru oraz drogę przebytą w ciągu tych 4 sekund.

**Rozwiązanie krok po kroku:**
1. Dane: $v_0 = 0$, $v = 8$ m/s, $t = 4$ s.
2. Przyspieszenie: $a = \dfrac{v - v_0}{t} = \dfrac{8\ \text{m/s} - 0}{4\ \text{s}} = 2\ \text{m/s}^2$.
3. Droga (start z $v_0=0$): $s = \dfrac{a \cdot t^2}{2} = \dfrac{2\ \text{m/s}^2 \cdot (4\ \text{s})^2}{2} = \dfrac{2 \cdot 16}{2} = 16$ m.
4. Możemy to sprawdzić polem pod wykresem trójkąta v(t): $s = \frac12 \cdot 4\,\text{s} \cdot 8\,\text{m/s} = 16$ m — zgadza się!

**Odpowiedź:** Przyspieszenie rowerzysty wynosi 2 m/s², a przebyta droga to 16 m.

---

## 1.4. Wykresy zależności drogi, prędkości i przyspieszenia od czasu

Wykresy to "język", którym fizycy opisują ruch bez słów. Warto znać, jak wyglądają dla trzech podstawowych rodzajów ruchu.

| Rodzaj ruchu | wykres s(t) | wykres v(t) | wykres a(t) |
|---|---|---|---|
| Spoczynek (brak ruchu) | linia pozioma | linia pozioma na poziomie 0 | linia pozioma na poziomie 0 |
| Ruch jednostajny | linia prosta ukośna | linia pozioma (stała wartość) | linia pozioma na poziomie 0 |
| Ruch jednostajnie przyspieszony | krzywa (parabola), coraz bardziej stroma | linia prosta ukośna, rosnąca | linia pozioma (stała wartość > 0) |
| Ruch jednostajnie opóźniony | krzywa, coraz mniej stroma | linia prosta ukośna, malejąca | linia pozioma (stała wartość < 0) |

#### Ilustracja: trzy wykresy obok siebie dla ruchu jednostajnie przyspieszonego

```
     s(t)                    v(t)                    a(t)
  s |                      v |                      a |
    |                 ●      |              ●         |
    |             ●          |         ●               |________●________
    |         ●              |    ●                    |
    |     ●                  |●                        |
    | ●                      |                          |
    +------------ t          +------------ t            +------------ t

  droga rośnie coraz          prędkość rośnie            przyspieszenie
  szybciej — krzywa           liniowo — linia prosta      stałe — linia pozioma
  (parabola)                  (nachylona)                 (na wysokości a)
```

**Jak czytać takie wykresy w zadaniach:**
- Z wykresu **s(t)**: prędkość odpowiada nachyleniu (stromości) krzywej w danym momencie.
- Z wykresu **v(t)**: droga to pole powierzchni pod wykresem, a przyspieszenie to nachylenie prostej.
- Z wykresu **a(t)**: pole pod wykresem to zmiana prędkości ($\Delta v$).

### Przykład

**Treść zadania:** Na wykresie v(t) rowerzysta w ciągu pierwszych 3 sekund przyspiesza jednostajnie od 0 do 6 m/s, a potem przez kolejne 5 sekund jedzie ze stałą prędkością 6 m/s. Jaką drogę przejechał w ciągu tych 8 sekund łącznie?

**Rozwiązanie krok po kroku:**
1. Dzielimy wykres na dwa fragmenty i liczymy pole pod każdym z nich osobno.
2. Fragment I (0–3 s, trójkąt): $s_1 = \frac12 \cdot 3\,\text{s} \cdot 6\,\text{m/s} = 9$ m.
3. Fragment II (3–8 s, prostokąt, bo prędkość stała): $s_2 = 6\,\text{m/s} \cdot 5\,\text{s} = 30$ m.
4. Droga całkowita: $s = s_1 + s_2 = 9\,\text{m} + 30\,\text{m} = 39$ m.

**Odpowiedź:** Rowerzysta przejechał łącznie 39 m.

---

## 1.5. Przeliczanie jednostek (droga, prędkość, przyspieszenie, czas)

### Jednostki drogi (długości)

Podstawowa jednostka w układzie SI to **metr (m)**. Najczęściej spotykane przeliczenia:

| Jednostka | Ile metrów |
|---|---|
| 1 km | 1000 m |
| 1 dm | 0,1 m |
| 1 cm | 0,01 m |
| 1 mm | 0,001 m |

### Jednostki czasu

| Jednostka | Ile sekund |
|---|---|
| 1 min | 60 s |
| 1 h (godzina) | 3600 s |
| 1 h | 60 min |

### Jednostki prędkości — najważniejsze przeliczenie w zadaniach!

Najczęściej spotykasz prędkość w **km/h** (np. na drogowskazach) albo w **m/s** (jednostka układu SI). Przelicznik:

$$1\ \text{km/h} = \frac{1000\ \text{m}}{3600\ \text{s}} = \frac{1}{3{,}6}\ \text{m/s} \approx 0{,}278\ \text{m/s}$$

W praktyce zapamiętaj prostą regułę:

- **z km/h na m/s → dziel przez 3,6**
- **z m/s na km/h → mnóż przez 3,6**

To jeden z najczęściej sprawdzanych "odruchów" na konkursie zDolny Ślązak — warto wykonać ją tak szybko, jak dodawanie!

### Jednostki przyspieszenia

Przyspieszenie to prędkość podzielona przez czas, więc jego jednostka to **jednostka prędkości podzielona przez jednostkę czasu**: $\dfrac{\text{m/s}}{\text{s}} = \text{m/s}^2$.

Jeśli mamy przyspieszenie np. w cm/s², żeby zamienić na m/s² dzielimy przez 100 (bo 1 m = 100 cm), pamiętając, że jednostka czasu (s²) się nie zmienia.

### Przykład

**Treść zadania:** Samochód porusza się z prędkością 90 km/h. Wyraź tę prędkość w m/s. Następnie oblicz, ile metrów przejedzie samochód w ciągu 1 sekundy.

**Rozwiązanie krok po kroku:**
1. Przeliczamy prędkość z km/h na m/s, dzieląc przez 3,6:
   $v = \dfrac{90}{3{,}6}\ \text{m/s} = 25\ \text{m/s}$.
2. Droga w ciągu 1 sekundy przy prędkości stałej: $s = v \cdot t = 25\ \text{m/s} \cdot 1\ \text{s} = 25$ m.

**Odpowiedź:** 90 km/h to 25 m/s, a w ciągu 1 sekundy samochód przejeżdża 25 metrów. (To użyteczna wskazówka np. do zadań o czasie reakcji kierowcy!)

---

## 1.6. Pomiary charakterystyk ruchu

### Czym mierzymy ruch?

Żeby opisać ruch liczbowo, potrzebujemy zmierzyć dwie podstawowe wielkości: **drogę** i **czas** (z nich obliczamy prędkość i przyspieszenie).

- **Drogę** mierzymy np. taśmą mierniczą, linijką, przymiarem, a na dłuższych odcinkach — np. licznikiem obrotów koła roweru albo licznikiem kilometrów w samochodzie (drogomierz, ang. odometer).
- **Czas** mierzymy stoperem (ręcznym lub w telefonie), a w bardziej precyzyjnych eksperymentach — **bramkami fotokomórkowymi** połączonymi z elektronicznym licznikiem czasu, który reaguje na przecięcie promienia światła przez poruszający się obiekt.

### Prędkość chwilowa a prędkość średnia — jak je zmierzyć?

- **Prędkość średnia** na odcinku wyznaczamy, mierząc całą drogę i cały czas jej pokonania, a potem dzieląc: $v_{śr} = s/t$.
- **Prędkość chwilową** (w danym momencie) najprościej zmierzyć, biorąc **bardzo krótki** odcinek drogi i bardzo krótki czas jego pokonania — im krótszy odcinek, tym dokładniej opisujemy prędkość "w tym jednym momencie". W praktyce szkolnej prędkościomierz roweru czy samochodu robi dokładnie to — mierzy bardzo mały odcinek drogi w bardzo małym czasie i pokazuje wynik na bieżąco.

### Jak zmierzyć przyspieszenie w prostym doświadczeniu?

Typowe doświadczenie: puszczamy wózek (albo kulkę) na równi pochyłej i mierzymy czas przejazdu między dwiema bramkami fotokomórkowymi ustawionymi w znanej odległości od siebie. Znając odległość między bramkami oraz zmierzony czas, możemy policzyć prędkość średnią na tym odcinku; robiąc pomiar na kilku kolejnych odcinkach, możemy sprawdzić, czy (i jak) prędkość rośnie — a stąd wyznaczyć przyspieszenie.

#### Ilustracja: pomiar prędkości za pomocą bramek fotokomórkowych

```
Tor pomiarowy (równia pochyła) z dwiema bramkami fotokomórkowymi F1 i F2:

  START                    F1                          F2
    |                       |                             |
    |------ d = 1,0 m ------|------- d = 1,0 m -----------|
    |                       |                             |
  wózek  ▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶▶

  Elektroniczny stoper zatrzymany przez wiązkę światła zmierzył:
     chwila przejścia przez F1: t1 = 1,0 s (licząc od startu)
     chwila przejścia przez F2: t2 = 1,4 s (licząc od startu)

  Czas między bramkami: Δt = t2 − t1 = 0,4 s
  Prędkość średnia między F1 a F2: v = d / Δt = 1,0 m / 0,4 s = 2,5 m/s
```

Taki pomiar jest dużo dokładniejszy niż mierzenie stoperem "ręcznie", bo bramka reaguje na promień światła w ułamku sekundy, a reakcja człowieka na stoperze trwa zwykle 0,2–0,3 sekundy (i to jest źródło niepewności pomiaru!).

### Niepewność pomiaru w kinematyce

Każdy pomiar ma pewną niepewność (patrz też temat 0). W pomiarach ruchu najważniejsze źródła niepewności to:
- czas reakcji osoby obsługującej stoper,
- dokładność przyrządu do mierzenia długości (np. działka elementarna taśmy mierniczej),
- to, czy ruch faktycznie jest jednostajny (a nie tylko "w przybliżeniu" jednostajny).

### Przykład

**Treść zadania:** Uczniowie mierzą prędkość kulki tocznej z równi. Kulka pokonuje odcinek 2,4 m w czasie zmierzonym stoperem: 3 pomiary dały wyniki 1,9 s, 2,1 s i 2,0 s. Oblicz prędkość średnią kulki, korzystając ze średniej arytmetycznej z pomiarów czasu.

**Rozwiązanie krok po kroku:**
1. Liczymy średni czas z trzech pomiarów: $t_{śr} = \dfrac{1{,}9 + 2{,}1 + 2{,}0}{3}\ \text{s} = \dfrac{6{,}0}{3}\ \text{s} = 2{,}0$ s.
2. Korzystamy ze wzoru na prędkość: $v = \dfrac{s}{t_{śr}} = \dfrac{2{,}4\ \text{m}}{2{,}0\ \text{s}} = 1{,}2\ \text{m/s}$.

**Odpowiedź:** Prędkość średnia kulki wynosi 1,2 m/s. (Dlatego w doświadczeniach zawsze warto powtórzyć pomiar kilka razy i uśrednić wynik — pojedynczy pomiar czasu stoperem obarczony jest sporym błędem reakcji!)

---

## Quiz

Poniższe 10 pytań sprawdza znajomość całego tematu 1 (podtematy 1.1–1.6). Część pytań to pytania jednokrotnego wyboru (A–D), część to ocena prawda/fałsz kilku zdań, a część wymaga odczytu z wykresu — dokładnie tak, jak na etapie szkolnym konkursu zDolny Ślązak. Powodzenia!

**1.** Rowerzysta porusza się ruchem jednostajnym prostoliniowym z prędkością 5 m/s. Jaką drogę przejedzie w ciągu 2 minut?

- [ ] A. 10 m
- [ ] B. 100 m
- [ ] C. 300 m
- [ ] D. 600 m

**2.** Pasażer siedzący w jadącym po prostych torach pociągu upuszcza długopis, który spada prosto na podłogę wagonu (dokładnie pod miejscem, z którego spadł — względem podłogi wagonu). Obserwator stojący nieruchomo na peronie zobaczy, że tor lotu długopisu jest:

- [ ] A. taki sam jak dla pasażera — pionową linią prostą
- [ ] B. krzywą (łukiem), bo pociąg porusza się względem peronu
- [ ] C. poziomą linią prostą
- [ ] D. długopis w ogóle się nie porusza względem peronu

**3.** Rowerzysta rusza z miejsca (v₀ = 0) i porusza się ruchem jednostajnie przyspieszonym ze stałym przyspieszeniem a = 2 m/s². Oceń prawdziwość poniższych zdań (P/F):

- [ ] A. Po upływie 1 sekundy jego prędkość wynosi 2 m/s.
- [ ] B. W ciągu pierwszych 3 sekund ruchu rowerzysta przejechał 9 m.
- [ ] C. Wartość przyspieszenia rowerzysty rośnie z upływem czasu.
- [ ] D. Po upływie 5 sekund jego prędkość wynosi 10 m/s.

**4.** Na wykresie poniżej przedstawiono zależność drogi od czasu s(t) dla pewnego ciała:

```
 s [m]
 20 |        _______________
    |       /
    |      /
    |     /
    |    /
  0 +---+----+----+----+----+---- t [s]
    0   2    3    4    5    6
```

(odcinek 0–2 s: droga rośnie liniowo od 0 do 20 m; odcinek 2–6 s: droga pozostaje stała na poziomie 20 m)

W którym przedziale czasu prędkość ciała była równa zeru?

- [ ] A. 0–2 s
- [ ] B. 2–6 s
- [ ] C. Prędkość nigdy nie była równa zeru
- [ ] D. Nie da się tego stwierdzić na podstawie wykresu s(t)

**5.** Samochód zwiększa swoją prędkość jednostajnie od 10 m/s do 25 m/s w ciągu 5 sekund. Jaka jest wartość przyspieszenia samochodu?

- [ ] A. 2 m/s²
- [ ] B. 3 m/s²
- [ ] C. 5 m/s²
- [ ] D. 7,5 m/s²

**6.** Oceń prawdziwość poniższych zdań dotyczących przeliczania jednostek (P/F):

- [ ] A. 54 km/h to dokładnie 15 m/s.
- [ ] B. 2 m/s to 0,72 km/h.
- [ ] C. 1500 m to 1,5 km.
- [ ] D. Pół godziny to 1800 sekund.

**7.** Na wykresie poniżej przedstawiono zależność prędkości od czasu v(t) dla ciała poruszającego się przez 12 sekund:

```
 v [m/s]
 8 |          _______________
   |         /                \
   |        /                  \
   |       /                    \
 0 +---+--+----+----+----+---+---+--- t [s]
   0   4      6    8   10  12
```

(odcinek 0–4 s: prędkość rośnie liniowo od 0 do 8 m/s; odcinek 4–10 s: prędkość stała 8 m/s; odcinek 10–12 s: prędkość maleje liniowo do 0)

Jaką całkowitą drogę przebyło to ciało w ciągu całych 12 sekund ruchu?

- [ ] A. 48 m
- [ ] B. 64 m
- [ ] C. 72 m
- [ ] D. 96 m

**8.** Przyspieszenie pewnego ciała wynosi 500 cm/s². Ile to jest wyrażone w m/s²?

- [ ] A. 0,5 m/s²
- [ ] B. 5 m/s²
- [ ] C. 50 m/s²
- [ ] D. 5000 m/s²

**9.** Uczennica idzie do szkoły. Pierwsze 600 m pokonuje w ciągu 10 minut ruchem jednostajnym, a następnie ostatnie 200 m przebiega w ciągu 1 minuty (też w przybliżeniu ruchem jednostajnym, bo biegnie ze stałym tempem). Oceń prawdziwość poniższych zdań (P/F):

- [ ] A. Prędkość uczennicy podczas chodu wynosiła 1 m/s.
- [ ] B. Prędkość uczennicy podczas biegu była większa niż podczas chodu.
- [ ] C. Średnia prędkość na całej trasie (800 m w 11 minut) wynosi około 1,2 m/s.
- [ ] D. Cała droga pokonana przez uczennicę wynosi 900 m.

**10.** Rowerzysta jadący z prędkością 12 m/s zaczyna hamować ruchem jednostajnie opóźnionym i zatrzymuje się dokładnie po przejechaniu 18 m. Jaka była wartość przyspieszenia (opóźnienia) podczas hamowania? (Wskazówka: skorzystaj ze wzoru $v^2 = v_0^2 - 2as$, gdzie v to prędkość końcowa, tutaj równa 0).

- [ ] A. 2 m/s²
- [ ] B. 3 m/s²
- [ ] C. 4 m/s²
- [ ] D. 6 m/s²
