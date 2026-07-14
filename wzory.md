# Wzory — ściąga do konkursu zDolny Ślązak

Zbiór wzorów bazowych z tematów 0–5 (zakres etapu szkolnego i powiatowego). Pominięto wzory, które są tylko trywialnym przekształceniem (zamianą zmiennej) wzoru już podanego — np. jeśli podano $v = s/t$, nie powtarzamy $s = v \cdot t$ czy $t = s/v$.

**Skalar czy wektor?** Przy każdej wielkości w opisach "gdzie:" znajdziesz dopisek `(skalar)` albo `(wektor)`. Zobacz temat `0.6_skalary_i_wektory.md` po pełne wyjaśnienie tego rozróżnienia. Krótko: jeśli wzór jest prawdziwym równaniem wektorowym (obowiązuje niezależnie od kierunku), piszemy go ze strzałką, np. $\vec{F} = m\vec{a}$. Jeśli wzór w praktyce liczy tylko wartość (modu) danej wielkości, piszemy go bez strzałki, a przy symbolu zaznaczamy `(wektor — tu użyta wartość)`.

---

## 0. Pomiary fizyczne, niepewności pomiarowe i jednostki

**Niepewność pomiaru z klasy dokładności przyrządu:**

$$\text{niepewność} = \frac{\text{klasa dokładności}}{100} \times \text{zakres pomiarowy}$$

---

## 1. Kinematyka

**Ruch jednostajnie zmienny (obejmuje jako przypadek szczególny ruch jednostajny, gdy $a=0$, oraz spadek swobodny, gdy $a=g$, $v_0=0$):**

$$s(t) = v_0 \cdot t + \frac{a \cdot t^2}{2}$$

$$v(t) = v_0 + a \cdot t$$

$$a(t) = a \quad (\text{stałe})$$

gdzie: $s$ — droga (skalar), $v_0$ — prędkość początkowa (wektor — tu użyta wartość), $v$ — prędkość w chwili $t$ (wektor — tu użyta wartość), $a$ — przyspieszenie (wektor — tu użyta wartość), $t$ — czas (skalar). Prędkość i przyspieszenie są z natury wektorami, ale skoro `s` to droga (skalar), te wzory liczą tylko ich wartości — zobacz temat `0.6_skalary_i_wektory.md`.

**Wzór bez czasu** (eliminuje $t$ z powyższych wzorów; przydatny, gdy czas nie jest dany):

$$v^2 = v_0^2 + 2as$$

gdzie symbole jak wyżej (dla ruchu opóźnionego $a$ wstawiamy ze znakiem minus).

---

## 2. Siły i dynamika

**II zasada dynamiki Newtona** (prawdziwe równanie wektorowe):

$$\vec{F} = m\vec{a}$$

gdzie: $\vec{F}$ — siła wypadkowa działająca na ciało (wektor), $m$ — masa ciała (skalar), $\vec{a}$ — przyspieszenie, jakie ta siła nadaje ciału (wektor).

**Siła ciężkości (ciężar)** (prawdziwe równanie wektorowe — zwrot zawsze do środka Ziemi):

$$\vec{F_g} = m\vec{g}$$

gdzie: $m$ — masa ciała (skalar), $\vec{g}$ — przyspieszenie ziemskie (wektor; w przybliżeniu $9{,}81\ \text{m/s}^2$, w zadaniach często zaokrąglane do $10\ \text{m/s}^2$), $\vec{F_g}$ — ciężar (wektor).

**Siła tarcia** ($f$ — współczynnik tarcia [skalar], $N$ — siła nacisku/reakcji podłoża [wektor — tu użyta wartość]):

$$T = f \cdot N$$

**Siła sprężystości (prawo Hooke'a)** ($k$ — współczynnik sprężystości [skalar], $x$ — odkształcenie [skalar]):

$$F_s = k \cdot x$$

**Siła wypadkowa sił działających wzdłuż jednej prostej** (uproszczony przypadek 1D — pełne dodawanie wektorów pod kątem wymaga metody równoległoboku, zobacz temat 0.6):

$$F_w = F_1 + F_2 \quad (\text{zgodne zwroty})$$

$$F_w = |F_1 - F_2| \quad (\text{przeciwne zwroty})$$

gdzie: $F_w$, $F_1$, $F_2$ — wartości sił składowych działających wzdłuż tej samej prostej (wektor — tu użyta wartość).

---

## 3. Praca, moc, energia

**Praca mechaniczna** (dla siły $F$ równoległej do przemieszczenia $s$). Praca `W` jest SKALAREM, mimo że oblicza się ją z dwóch wektorów (siły i przemieszczenia) — we wzorze używamy ich wartości:

$$W = F \cdot s$$

gdzie: $W$ — praca (skalar), $F$ — siła (wektor — tu użyta wartość), $s$ — droga (skalar).

**Moc** (skalar/skalar = skalar):

$$P = \frac{W}{t}$$

gdzie: $P$ — moc (skalar), $W$ — praca wykonana w czasie $t$ (skalar), $t$ — czas (skalar).

**Energia kinetyczna** (energia jest zawsze skalarem):

$$E_k = \frac{1}{2} m v^2$$

gdzie: $E_k$ — energia kinetyczna (skalar), $m$ — masa ciała (skalar), $v$ — prędkość (wektor — tu użyta wartość, do kwadratu, więc kierunek nie ma znaczenia).

**Energia potencjalna grawitacji:**

$$E_p = m \cdot g \cdot h$$

gdzie: $E_p$ — energia potencjalna (skalar), $h$ — wysokość ciała nad przyjętym poziomem odniesienia (skalar), $m$ i $g$ jak w sekcji 2. powyżej (tu użyte jako skalar i wartość wektora).

**Energia potencjalna sprężystości:**

$$E_{sp} = \frac{1}{2} k x^2$$

gdzie: $E_{sp}$ — energia potencjalna sprężystości (skalar), $k$ i $x$ jak przy sile sprężystości w sekcji 2. powyżej (oba skalary).

**Złota reguła mechaniki** (praca włożona = praca uzyskana w idealnej maszynie prostej, bez tarcia — dotyczy bloków, kołowrotka i równi pochyłej, które są zastosowaniami tej reguły; wzór na wartościach, bez strzałek):

$$F_1 \cdot s_1 = F_2 \cdot s_2$$

gdzie: $F_1$ — siła włożona (np. ta, którą ciągniemy linę; wektor — tu wartość), $s_1$ — droga jej przyłożenia (skalar), $F_2$ — siła uzyskana (np. ciężar podnoszony; wektor — tu wartość), $s_2$ — odpowiadająca jej droga (skalar).

**Warunek równowagi dźwigni** (zasada momentów sił — dotyczy też kołowrotka, który jest dźwignią "nawiniętą" na oś; wzór na wartościach, bez strzałek):

$$F_1 \cdot r_1 = F_2 \cdot r_2$$

gdzie: $F_1$, $F_2$ — siły działające na ramiona dźwigni (wektor — tu wartość), $r_1$, $r_2$ — długości tych ramion (skalar; odległości punktów przyłożenia sił od punktu podparcia).

**Energia mechaniczna** (suma dwóch skalarów) **i zasada jej zachowania**:

$$E_m = E_k + E_p = \text{const}$$

gdzie: $E_m$ — energia mechaniczna (skalar).

---

## 4. Termodynamika

W termodynamice WSZYSTKIE wielkości są skalarami (temperatura, ciepło, energia wewnętrzna, praca w sensie termodynamicznym) — nie ma tu żadnych wektorów, zobacz temat 0.6.

**Przeliczanie skal temperatur:**

$$T[K] = t[°C] + 273{,}15$$

$$t[°F] = t[°C] \cdot \frac{9}{5} + 32$$

gdzie: $T$ — temperatura wyrażona w kelwinach (K) (skalar), $t$ — ta sama temperatura wyrażona w stopniach Celsjusza (°C) lub Fahrenheita (°F) (skalar).

**I zasada termodynamiki:**

$$\Delta U = Q + W$$

gdzie: $\Delta U$ — zmiana energii wewnętrznej ciała (skalar), $Q$ — ciepło dostarczone do ciała (dodatnie) lub oddane przez ciało (ujemne) (skalar), $W$ — praca wykonana nad ciałem (dodatnia) lub wykonana przez ciało (ujemna) (skalar).

**Ciepło potrzebne do zmiany temperatury** ($c$ — ciepło właściwe, skalar):

$$Q = c \cdot m \cdot \Delta T$$

gdzie: $Q$ — ciepło (skalar), $m$ — masa ogrzewanego/chłodzonego ciała (skalar), $\Delta T$ — zmiana temperatury (skalar; różnica temperatury końcowej i początkowej).

**Ciepło przemiany fazowej** ($L$ — ciepło właściwe przemiany fazowej, skalar, np. topnienia lub parowania):

$$Q = L \cdot m$$

gdzie: $Q$ — ciepło przemiany fazowej (skalar), $m$ — masa substancji zmieniającej stan skupienia (skalar).

---

## 5. Właściwości materii i hydrostatyka

**Gęstość:**

$$\rho = \frac{m}{V}$$

gdzie: $\rho$ — gęstość (skalar), $m$ — masa ciała (lub cieczy) (skalar), $V$ — jego objętość (skalar).

**Napięcie powierzchniowe** ($l$ — długość linii brzegowej powierzchni cieczy, skalar):

$$\sigma = \frac{F}{l}$$

gdzie: $\sigma$ — napięcie powierzchniowe (skalar), $F$ — siła spójności (powierzchniowa) działająca wzdłuż tej linii brzegowej (wektor — tu użyta wartość), $l$ — długość linii brzegowej (skalar).

**Ciśnienie** — UWAGA, częsty błąd: ciśnienie jest SKALAREM, mimo że "kojarzy się z naciskiem w jakąś stronę". To siła (wektor) ma kierunek — ciśnienie to tylko liczba (zobacz temat 0.6 i 5.3):

$$p = \frac{F}{S}$$

gdzie: $p$ — ciśnienie (skalar), $F$ — siła nacisku (parcia) działająca prostopadle do powierzchni (wektor — tu użyta wartość), $S$ — pole tej powierzchni (skalar).

**Ciśnienie hydrostatyczne:**

$$p = \rho \cdot g \cdot h$$

gdzie: $p$ — ciśnienie (skalar), $\rho$ — gęstość cieczy (skalar), $g$ — przyspieszenie ziemskie (wektor — tu użyta wartość), $h$ — głębokość (skalar; wysokość słupa cieczy nad rozpatrywanym punktem).

**Siła wyporu (prawo Archimedesa)** — $F_w$ jako wektor jest zawsze skierowana do góry, ale wzór liczy tylko jej wartość:

$$F_w = \rho_{\text{cieczy}} \cdot V_{\text{zanurzone}} \cdot g$$

gdzie: $F_w$ — siła wyporu (wektor — tu użyta wartość), $\rho_{\text{cieczy}}$ — gęstość cieczy, w której zanurzone jest ciało (skalar), $V_{\text{zanurzone}}$ — objętość zanurzonej części ciała (skalar), $g$ — przyspieszenie ziemskie (wektor — tu użyta wartość).
