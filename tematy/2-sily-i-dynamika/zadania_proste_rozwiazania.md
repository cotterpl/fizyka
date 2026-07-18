# Temat 2: Siły i dynamika — zadania proste — rozwiązania

We wszystkich obliczeniach przyjęto g = 10 m/s² (standardowe uproszczenie dla szkoły podstawowej).

---

**1.** [2.1 Siła jako wektor]
a) **Prawda.** Siła jest wielkością wektorową — pełny opis wymaga podania wartości (długości wektora), kierunku, zwrotu oraz punktu przyłożenia. Bez tych czterech elementów opis siły jest niepełny.
b) **Prawda.** Z definicji: F = m·g. Dla m = 0,1 kg (100 g) i g = 10 m/s² mamy F = 0,1 kg · 10 m/s² = 1 N. To dlatego popularnie mówi się, że "1 N to w przybliżeniu ciężar 100-gramowej tabliczki czekolady".
c) **Fałsz.** Siła jest miarą każdego oddziaływania między ciałami — opisuje nie tylko oddziaływania grawitacyjne i elektryczne, ale też np. tarcie, nacisk, sprężystość, oddziaływania magnetyczne itd.
d) **Fałsz.** To jest właśnie zaprzeczenie definicji siły jako wektora — kierunek i zwrot są integralną częścią opisu siły (siła 10 N "w prawo" i siła 10 N "w lewo" to różne siły, mimo tej samej wartości).

**2.** [2.2 Tarcie]
Dane: m = 0,5 kg, f = 0,25, g = 10 m/s².
Siła nacisku klocka na powierzchnię jest równa jego ciężarowi (klocek leży na płaskiej, poziomej powierzchni):
N = m·g = 0,5 kg · 10 m/s² = 5 N.
Siła tarcia: T = f·N = 0,25 · 5 N = **1,25 N**.

**3.** [2.2 Sprężystość]
Prawo Hooke'a: wydłużenie sprężyny jest wprost proporcjonalne do przyłożonej siły, F = k·x (k — współczynnik sprężystości, jak w `wzory.md`), czyli x = F/k.
Z danych: dla F₁ = 2 N, x₁ = 4 cm, więc stała proporcjonalności x/F = 1/k = 4 cm / 2 N = 2 cm/N.
Dla F₂ = 3 N: x₂ = (x/F) · F₂ = 2 cm/N · 3 N = **6 cm**.
(Można też ułożyć proporcję: x₁/F₁ = x₂/F₂, czyli 4/2 = x₂/3, skąd x₂ = 6 cm.)

**4.** [2.2 Opór ruchu]
Kropla spada ruchem jednostajnym (stała wartość prędkości), więc zgodnie z I zasadą dynamiki wypadkowa sił działających na nią musi być równa zeru.
1. **Prawda** — to jest właśnie warunek ruchu jednostajnego: siła oporu powietrza (do góry) równoważy siłę ciężkości (w dół).
2. **Fałsz** — gdyby opór był mniejszy od ciężaru, kropla przyspieszałaby (ruch jednostajnie przyspieszony), a nie poruszała się jednostajnie.
3. **Prawda** — to jest inne sformułowanie tego samego faktu co w punkcie 1: skoro prędkość jest stała, wypadkowa siła = 0 N.

**5.** [2.3 I zasada dynamiki]
a) **Fałsz.** To częsty błąd: siła grawitacji (skierowana w dół, pionowo) jest równoważona przez siłę reakcji podłoża (nacisku) — to jest odrębna, "pionowa" równowaga sił, niezwiązana z tym, czy samochód jedzie jednostajnie czy przyspiesza. O ruchu jednostajnym prostoliniowym w kierunku poziomym decyduje bilans sił poziomych (napędowej i oporów), nie sił pionowych.
b) **Prawda.** To jest prawidłowe zastosowanie I zasady dynamiki: gdy siła napędzająca dokładnie równoważy siłę tarcia i inne opory ruchu, wypadkowa siła pozioma wynosi zero, więc ciało (tu: samochód) porusza się ruchem jednostajnym prostoliniowym (albo pozostaje w spoczynku).
c) **Prawda.** Skoro samochód nie porusza się (jest w spoczynku), to zgodnie z I zasadą dynamiki wypadkowa działających na niego sił musi być równa zeru — siły się równoważą.

**6.** [2.3 II zasada dynamiki]
Dane: m₁ = 1,5 kg, a = 5 m/s², m₂ = 2 kg (po nasiąknięciu wodą).
a) Z II zasady dynamiki: F = m·a = 1,5 kg · 5 m/s² = **7,5 N**.
b) Aby cięższej piłce (m₂ = 2 kg) nadać to samo przyspieszenie a = 5 m/s², potrzebna jest siła:
F₂ = m₂·a = 2 kg · 5 m/s² = 10 N.
Różnica: F₂ − F₁ = 10 N − 7,5 N = **2,5 N większej siły**.
(Uwaga na typowy błąd: nie należy mylić masy z ciężarem — tu cały czas liczymy tylko z II zasadą dynamiki F=ma, a nie z ciężarem piłki.)

**7.** [2.3 III zasada dynamiki]
a) **Prawda.** To jest wzorcowe zastosowanie III zasady dynamiki (zasady akcji i reakcji): jeśli ciało A działa na ciało B siłą F, to ciało B działa na ciało A siłą o tej samej wartości i kierunku, ale przeciwnym zwrocie.
b) **Fałsz — to bardzo częsty błąd.** Siły akcji i reakcji (III zasada dynamiki) nigdy się nie "równoważą" w sensie fizycznym, ponieważ działają na **dwa różne ciała** (siła na pięść i siła na ścianę) — nie mają więc wspólnej wypadkowej. Równoważenie się sił (I zasada dynamiki, siła wypadkowa = 0) dotyczy wyłącznie sił działających na **to samo ciało**. To jest jedna z najczęstszych pułapek w tym dziale fizyki.
c) **Prawda.** To kolejny przykład III zasady dynamiki: pływak odpycha wodę do tyłu (akcja), a woda odpycha pływaka do przodu (reakcja) — dzięki temu pływak może się poruszać.

**8.** [2.4 Siła wypadkowa]
Dane: F_napędowa = 2000 N, F_oporów = 500 N, a = 1 m/s².
Siła wypadkowa (działająca wzdłuż ruchu) to różnica siły napędowej i sił oporu, bo działają one w przeciwnych kierunkach:
F_wyp = 2000 N − 500 N = 1500 N.
Z II zasady dynamiki: F_wyp = m·a, stąd m = F_wyp / a = 1500 N / 1 m/s² = **1500 kg**.

**9.** [2.5 Masa a bezwładność ciał]
Gdy autobus zaczyna hamować, na niezamocowane przedmioty i pasażerów (jeśli nie trzymają się poręczy) nie działa żadna siła, która zmusiłaby ich do równie szybkiego zwolnienia jak autobus. Zgodnie z I zasadą dynamiki (zasadą bezwładności) ciała "starają się" zachować swoją dotychczasową prędkość. Skutek: pasażerowie i przedmioty przesuwają się względem wnętrza autobusu **do przodu** — w stronę, w którą autobus wcześniej jechał — bo nadal poruszają się z prędkością, jaką miał autobus przed hamowaniem, podczas gdy sam autobus (dzięki sile tarcia hamulców) już zwalnia.
Masa jest miarą bezwładności ciała: im większa masa, tym trudniej zmienić prędkość ciała (potrzeba większej siły, by je zatrzymać lub rozpędzić w tym samym czasie) — dlatego cięższe przedmioty "silniej opierają się" próbie ich zatrzymania.

**10.** [2.6 Spadek swobodny]
Wzory: h = ½·g·t² (droga spadku), v = g·t (prędkość w chwili t), stąd t = √(2h/g).
Dla h₁ = 5 m: t₁ = √(2·5 m / 10 m/s²) = √(1 s²) = **1 s**; v₁ = g·t₁ = 10 m/s² · 1 s = **10 m/s**.
Dla h₂ = 20 m: t₂ = √(2·20 m / 10 m/s²) = √(4 s²) = **2 s**; v₂ = g·t₂ = 10 m/s² · 2 s = **20 m/s**.
(Ciało spadające z wysokości 4 razy większej potrzebuje 2 razy więcej czasu i osiąga 2 razy większą prędkość — to konsekwencja tego, że w ruchu jednostajnie przyspieszonym h jest proporcjonalne do t², a v do t.)

**11.** [2.7 Siła ciężkości]
a) Dane: m = 2,5 g = 0,0025 kg.
F_g = m·g = 0,0025 kg · 10 m/s² = **0,025 N**.
b) Waga w punkcie kontroli pojazdów mierzy siłę nacisku (czyli ciężar), a nie bezpośrednio masę — tu wynik 200 kN to **siła** (ciężar), nie masa!
F_g = 200 kN = 200 000 N.
Z Fg = m·g: m = Fg / g = 200 000 N / 10 m/s² = **20 000 kg = 20 t**.
(Uwaga na typowy błąd: nie wolno "podstawić" 200 pod masę w tonach — jednostka kN jednoznacznie wskazuje, że to siła, więc trzeba ją najpierw podzielić przez g, aby otrzymać masę.)

**12.** [2.7 Siła ciężkości na innych planetach]
Masa człowieka jest taka sama na Ziemi i na Księżycu (masa nie zależy od miejsca w przestrzeni) — zmienia się natomiast przyspieszenie grawitacyjne g.
Ciężar: Fg = m·g. Skoro g_Księżyc ≈ g_Ziemia / 6, to:
Fg,Księżyc = m · (g_Ziemia/6) = (m·g_Ziemia)/6 = Fg,Ziemia / 6.
Odpowiedź: ciężar na Księżycu jest **6 razy mniejszy** niż na Ziemi.
(Uwaga na typowy błąd: to ciężar, a nie masa, jest 6 razy mniejszy — masa człowieka na Księżycu pozostaje bez zmian.)

**13.** [2.8 Doświadczenie — pomiar ciężaru człowieka]
Waga sprężynowa (łazienkowa) nie mierzy bezpośrednio masy — mierzy siłę nacisku wywieraną na jej szalkę/platformę w danym momencie.
- Gdy energicznie podnosisz ręce z ciężarkami **do góry**, nadajesz im (i częściowo swojemu ciału) przyspieszenie skierowane w górę. Zgodnie z II zasadą dynamiki potrzebna jest do tego dodatkowa siła skierowana w górę, którą Twoje ręce działają na ciężarki — a zgodnie z III zasadą dynamiki ciężarki działają wtedy na Twoje ręce siłą o tej samej wartości, skierowaną w dół. W efekcie stopy naciskają na wagę chwilowo **mocniej**. Wskazanie wagi **rośnie**.
- Gdy energicznie opuszczasz ręce **w dół**, przyspieszenie (a więc i potrzebna siła) jest skierowane w dół, więc chwilowo "odciążasz" wagę. Wskazanie wagi **maleje**.
- Gdy poruszasz rękami **w bok** (poziomo), przyspieszenie ma składową pionową równą (praktycznie) zeru, więc siła nacisku na wagę w kierunku pionowym nie zmienia się. Wskazanie wagi **nie zmienia się**.
Masa Twojego ciała **nie zmienia się** w żadnym z tych przypadków — ilość materii, z której się składasz, jest stała. Zmienia się jedynie chwilowa siła nacisku na wagę, którą czasem błędnie nazywamy "ciężarem" — w rzeczywistości to, co wskazuje waga, zależy nie tylko od masy i g, ale też od chwilowego przyspieszenia ciała.
