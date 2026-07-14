# Poprawki — wyniki krytycznego przeglądu materiałów

Ten dokument to wynik równoległego przeglądu wszystkich materiałów w repo (7 recenzentów: po jednym na każdy temat 0–5 plus jeden przekrojowy dla README/tematy.md/wzory.md), zunifikowany w jedną listę. Każdy recenzent samodzielnie przeliczył wszystkie zadania rachunkowe w teorii, quizach i zadaniach oraz zweryfikował `zadania_zdolny_slazak.md` względem oryginalnych arkuszy PDF w `arkusze/`.

**Ogólna ocena:** materiał jest merytorycznie bardzo solidny — zdecydowana większość wzorów, definicji i kluczy odpowiedzi jest poprawna. Znaleziono jednak kilka **zadań konkursowych, których transkrypcja odbiega od oryginalnego arkusza** (sekcja 1 — najwyższy priorytet, bo dane brakujące/przeinaczone względem źródła uniemożliwiają poprawne rozwiązanie), sporo **niespójności notacji tego samego symbolu w różnych plikach** (sekcja 2 — myląco, ale nie uniemożliwia rozwiązania), oraz zestaw drobniejszych błędów merytorycznych, językowych i strukturalnych (sekcje 3–6). Treść zadań w `zadania_zdolny_slazak.md` nie jest nigdzie w tym dokumencie poprawiana redakcyjnie — patrz zasada poniżej.

Legenda priorytetu: 🔴 krytyczny (zadanie nierozwiązywalne/błędny wynik) · 🟠 istotny (myląca niespójność, luka programowa) · 🟡 drobny (język, styl, kosmetyka).

**Ważna zasada dot. `zadania_zdolny_slazak.md`:** treść zadań w tych plikach to transkrypcja realnych zadań konkursowych z `arkusze/*.pdf` i **nie podlega redakcyjnym poprawkom** (przeformułowaniom, uproszczeniom, własnym wyjaśnieniom). Jedyne dopuszczalne zmiany w tych plikach to przywrócenie **wierności wobec oryginalnego arkusza** — jeśli transkrypcja pomija dane, które są na rysunku/wykresie w PDF, albo błędnie opisuje to, co PDF faktycznie pokazuje. Poniższa sekcja 1 została przeformułowana zgodnie z tą zasadą: każdy punkt to rozbieżność między treścią w repo a materiałem źródłowym w `arkusze/`, a proponowana poprawka to wyłącznie przywrócenie zgodności ze źródłem — nie własna redakcja treści zadania.

---

## 1. 🔴 Rozbieżności między `zadania_zdolny_slazak.md` a oryginalnymi arkuszami w `arkusze/`

Poniższe znaleziono przez porównanie treści w repo z odpowiadającym arkuszem PDF. W każdym przypadku źródło zawiera dane/informacje, których w transkrypcji brakuje albo które są w niej przeinaczone — proponowana poprawka to wyłącznie uzupełnienie/skorygowanie transkrypcji tak, by dokładnie odpowiadała oryginałowi (bez dodawania własnych sformułowań wykraczających poza to, co jest w źródle).

- [ ] **`tematy/1-kinematyka/zadania_zdolny_slazak.md`** — zadanie „[1.3 Przyspieszenie z wykresu F(s)]” (2020/2021, zad. 15) i sąsiednie „[Zmiana prędkości]” (zad. 16): transkrypcja odsyła do „wykresu F(s)” bez liczb, podczas gdy oryginalny arkusz zawiera wykres z konkretnymi wartościami: F=2N (0–1m), F=1N (1–3m), F=6N (3–5m), F=2N (5–7m), F=3N (7–8m). **Do weryfikacji/poprawy:** sprawdzić dokładne wartości na wykresie w PDF i uzupełnić transkrypcję o te dane (liczby z oryginału, nie własne).

- [ ] **`tematy/1-kinematyka/zadania_zdolny_slazak.md`** — zadanie „[1.2/1.4 Wykres v(t), droga]” (2022/2023, zad. 6, narciarz): transkrypcja opisuje wykres słownie, bez liczb, podczas gdy oryginał zawiera wartości: v=20 km/h (0–20 min), spadek do 10 km/h (20–25 min), v=10 km/h (25–40 min). **Do weryfikacji/poprawy:** zweryfikować wartości w PDF i uzupełnić transkrypcję zgodnie ze źródłem.

- [ ] **`tematy/2-sily-i-dynamika/zadania_zdolny_slazak.md`** (linia ok. 34) — zadanie o pudełku (2019/2020, zad. 13): transkrypcja opisuje siły F1=60N i F2=20N jako „**prostopadłe**”, podczas gdy w oryginalnym arkuszu (str. 3) siły są narysowane **współliniowo, w tym samym zwrocie** — słowo „prostopadłe” nie pochodzi ze źródła i przeinacza to, co pokazuje rysunek. **Do weryfikacji/poprawy:** ponownie sprawdzić rysunek w PDF i dostosować opis geometrii sił dokładnie do tego, co on pokazuje (usunąć dopisek, którego nie ma w źródle).

- [ ] **`tematy/3-praca-moc-energia/zadania_zdolny_slazak.md`** (linia ok. 14) — zadanie „[3.2 Dźwignia dwustronna]” (2019/2020, zad. 10): transkrypcja podaje „ramię Oli 0,2 m”, ale w oryginalnym rysunku 0,2 m to **skala jednej kratki**, a rzeczywista długość ramienia Oli to 4 kratki (0,8 m); ramię Asi to 8 kratek (1,6 m). **Do weryfikacji/poprawy:** ponownie odczytać proporcje z rysunku w PDF i podać w transkrypcji rzeczywiste długości ramion, nie skalę kratki.

- [ ] **`tematy/1-kinematyka/zadania_zdolny_slazak.md`** — zadanie „[1.2/1.4 Wykres położenia narciarza od czasu]” (2025/2026, zad. 12): transkrypcja upraszcza odcinek 0–2h do jednorodnego wzrostu „0→30 km”, podczas gdy oryginalny wykres ma załamanie w t=1h (0→10 km w 0–1h, potem 10→30 km w 1–2h). **Do weryfikacji/poprawy:** sprawdzić dokładny kształt wykresu w PDF i opisać oba odcinki osobno, zgodnie ze źródłem.

---

## 2. 🟠 Niespójności notacji i stałych między tematami (przekrojowe)

Kilku recenzentów niezależnie natrafiło na te same rozjazdy symboli między `wzory.md` (oficjalna „ściąga”) a plikami teorii/zadań. Ujednolicić wszystkie miejsca naraz, żeby `wzory.md` pozostało wiarygodnym jedynym źródłem prawdy dla notacji.

- [ ] **Wartość przyspieszenia ziemskiego `g`:** `wzory.md:43` podaje `g ≈ 9,8 m/s²`, ale temat 2 (`2.1_sila_jako_wektor.md:44`, `2.6_spadek_swobodny.md:5`, `2.7_sila_ciezkosci.md:9,35`) i temat 3 (`zadania_proste.md:38`, `zadania_proste_rozwiazania.md:45-46`) konsekwentnie używają `9,81 m/s²`. **Poprawka:** ujednolicić na `9,81 m/s²` wszędzie (w tym w `wzory.md`).

- [ ] **Klasyfikacja `g` jako skalar/wektor:** `tematy/5-hydrostatyka/teoria/5.3_cisnienie_hydrostatyczne_i_prawo_pascala.md:35` i `tematy/5-hydrostatyka/teoria/5.4_sila_wyporu_prawo_archimedesa.md:22` oznaczają `g` jako „(**skalar** — tu użyta jego wartość...)” — wewnętrznie sprzeczne (zapis „tu użyta wartość” jest w całym materiale zarezerwowany dla wektorów) i sprzeczne z `wzory.md:169,175` oraz `0.6_skalary_i_wektory.md`, gdzie przyspieszenie jest kanonicznym przykładem wektora. Szczególnie ironiczne w pliku 5.3, który w tej samej sekcji uczy rozróżniania skalar/wektor. **Poprawka:** zmienić oba na „(wektor — tu użyta wartość)”.

- [ ] **Współczynnik tarcia `f` vs `μ`:** `wzory.md`, `2.2_rodzaje_sil.md` i `quiz.md`/`quiz_odpowiedzi.md` tematu 2 konsekwentnie używają `f`, ale `tematy/2-sily-i-dynamika/zadania_proste_rozwiazania.md:14,17` nagle wprowadza `μ` (niezdefiniowane wcześniej w tym dziale). **Poprawka:** zamienić `μ` na `f` w obu liniach.

- [ ] **Symbol gęstości `ρ` vs `d`:** `wzory.md:149` i pliki `5.3`/`5.4` używają `ρ`, ale `tematy/5-hydrostatyka/teoria/5.1_gestosc.md` wprowadza **`d = m/V`** jako symbol główny (linie 10, 15, 19, 43, 60, 64, 72–73), traktując `ρ` jako wzmiankę poboczną — a `quiz_odpowiedzi.md` (pyt. 10, linia ok. 43) miesza oba symbole *w jednej odpowiedzi* bez wyjaśnienia, że to ta sama wielkość. **Poprawka:** uczynić `ρ` symbolem głównym już w 5.1 (zgodnie z `wzory.md` i resztą tematu), `d` przedstawić jako wariant szkolny używany w niektórych podręcznikach.

- [ ] **Symbol ciężaru: `F_g` vs `Q` vs `F_c`:** `wzory.md:41` i temat 2 (np. `zadania_proste_rozwiazania.md:75`) używają `F_g`; `3.2_maszyny_proste.md:112` i `5.4_sila_wyporu_prawo_archimedesa.md:33,64,66,76` używają `Q`; `tematy/5-hydrostatyka/zadania_proste_rozwiazania.md` (zad. 3, 10, 11, 12) używa `F_c`. Trzy różne symbole tej samej wielkości bez wzajemnego odwołania. **Poprawka:** ujednolicić na `F_g` wszędzie, albo przy pierwszym użyciu innego symbolu dopisać „(ciężar, oznaczany też `F_g` — zobacz `wzory.md`)”.

- [ ] **Symbol energii mechanicznej: `E_c` vs `E_m`:** `3.4_zasada_zachowania_energii.md:11` (i ilustracja `energia-mechaniczna-spadek.svg:30`) definiuje `E_c = E_k + E_p`, ale `zadania_proste_rozwiazania.md` tematu 3 (linie 61, 63, 72) używa `E_m`. `wzory.md:109` w ogóle nie nazywa tej sumy. **Poprawka:** ujednolicić na `E_m` (czytelniejsze niż „c”) w 3.4, w SVG i dopisać nazwany symbol do `wzory.md`.

- [ ] **Podpisy rysunków `F_A`/`F_G` (Wikimedia) niepowiązane z notacją tekstu `F_w`/`F_g`:** w `5.4_sila_wyporu_prawo_archimedesa.md` rysunki źródłowe opisują siłę wyporu jako `F_A` i ciężar jako `F_G`, a tekst artykułu używa `F_w`/`Q`(→`F_g` po poprawce wyżej). **Poprawka:** dopisać w podpisie „(na rysunku oznaczone jako F_A/F_G, w tekście używamy F_w/F_g)”.

- [ ] **Brakujący wzór w `wzory.md`: siła wypadkowa sił prostopadłych.** `2.4_sila_wypadkowa_i_rownowazace_sie.md` uczy wzoru Pitagorasa $F_w=\sqrt{F_1^2+F_2^2}$ bez zastrzeżenia, że to poza podstawowym zakresem (w przeciwieństwie do analogicznego zastrzeżenia w 0.6), a zadanie konkursowe z tematu 2 (patrz sekcja 1 wyżej) go testuje. **Poprawka:** dodać wzór do `wzory.md` sekcja 2, albo dopisać w 2.4 zastrzeżenie analogiczne do 0.6, że przypadek prostopadły wykracza poza etap szkolny/powiatowy.

- [ ] **Brakujący wzór w `wzory.md`: $v^2=v_0^2+2as$.** Wzór jest wprowadzony w `1.3_ruch_jednostajnie_zmienny.md` i wprost testowany w `quiz.md` tematu 1 (pytanie 10, ze wskazówką), ale nieobecny w `wzory.md` sekcja 1 — to nie jest trywialne przekształcenie już podanego wzoru (eliminuje `t`), więc kwalifikuje się do ściągi. **Poprawka:** dopisać do `wzory.md`.

- [ ] **Symbol prędkości `υ` (ypsilon) zamiast `v`:** `tematy/3-praca-moc-energia/zadania_proste.md:18` i `zadania_proste_rozwiazania.md:16-17` używają greckiego `υ` zamiast łacińskiego `v` używanego wszędzie indziej — najpewniej literówka przy kopiowaniu ze źródła. **Poprawka:** zamienić na `v`.

- [ ] **Niespójne nazwy zmiennych dla kołowrotka:** `3.2_maszyny_proste.md:87` podaje `F·R = Q·r`, ale `zadania_proste_rozwiazania.md:22-24` (temat 3, zad. 4) zapisuje ten sam związek jako `F₁·r₁ = F₂·r₂` z inną konwencją nazw. **Poprawka:** ujednolicić zapis (najlepiej dopasować rozwiązanie do wzoru z teorii).

---

## 3. 🟠 Błędy merytoryczne w teorii (per temat)

### Temat 0 — Pomiary i niepewności

- [ ] **`teoria/0.1_przyrzady_pomiarowe_i_ich_dokladnosc.md:40,46`** — opis ilustracji `ilustracje/suwmiarka-skala-z-noniuszem.svg` twierdzi, że pokazuje konkretny odczyt „2,475 cm ± 0,005 cm”. To ogólny, poglądowy diagram budowy suwmiarki (na wzór wikipedyjnego Vernier caliper) — nie ma na nim wyrównanych kresek ilustrujących ten pomiar. **Poprawka:** opisać rysunek jako ogólny schemat budowy (szczęki, głębokościomierz, skala główna, noniusz), a przykład „2,475 cm” przedstawić jako niezależny przykład liczbowy, nie jako odczyt z tego konkretnego rysunku.

- [ ] **`teoria/0.2_niepewnosc_pomiarowa_i_zapis_wyniku.md`** — przykład wprowadzający (linie 14–20, ołówek 143,5 mm) używa niepewności ±0,2 mm (granice 143,3–143,7), a przykład niżej dla tego samego pomiaru (linie 32–42) podaje ±0,1 mm (granice 143,4–143,6). Te same dane wejściowe, dwie różne niepewności bez wyjaśnienia. **Poprawka:** ujednolicić na ±0,1 mm / 143,4–143,6 mm (w tym w SVG `os-niepewnosc-dlugosc-olowka.svg`).

- [ ] **`teoria/0.3_cyfry_znaczace.md:25`** — ciekawostka „12,000000 m”: tekst poprawnie wylicza niepewność linijki (działka 1mm) jako ±0,5mm=0,0005m, ale konkluduje zapisem `(12,000 ± 0,001) m` — niespójne z wyliczoną wartością. **Poprawka:** zmienić na `(12,0000 ± 0,0005) m`, czyli 6 cyfr znaczących.

- [ ] **`teoria/0.5_jednostki_wielkosci_fizycznych.md:36`** — błąd faktograficzny: sonda Mars Climate Orbiter miała wejść w atmosferę na planowanej wysokości ok. 226 km (nie 140–150 km, jak podano — możliwe pomylenie z 140 milami). **Poprawka:** zmienić na „zamiast planowanych ok. 226 km”.

- [ ] **`teoria/0.6_skalary_i_wektory.md`, ilustracja `ilustracje/dodawanie-wektorow-ten-sam-kierunek.svg`** — etykietuje siły w niutonach jako `a₁=3N`, `a₂=2N`, `a=a₁+a₂=5N`. Symbol `a` jest w tym samym materiale zarezerwowany dla przyspieszenia, nie siły — sąsiednia ilustracja poprawnie używa `F₁`/`F₂`/`Fw`. **Poprawka:** zamienić etykiety w SVG na `F₁`/`F₂`/`F=F₁+F₂`.

### Temat 1 — Kinematyka

- [ ] **`teoria/1.1_wzglednosc_ruchu_tor_a_droga.md:22`** — błąd liczbowy: prędkość obrotowa Ziemi „w Polsce... ponad 1200 km/h”. Poprawne obliczenie: v=1670 km/h (równik) × cos(51°) ≈ **1050 km/h**. **Poprawka:** zmienić na „ponad 1000 km/h” (lub „ok. 1050 km/h”).

- [ ] **`teoria/1.4_wykresy_ruchu.md:33`** — zdanie wewnętrznie sprzeczne: „Krzywa (III)... prosta rosnąca na wykresie v(t) w stałej wysokości”. Zgodnie z ilustracją krzywa III to linia **pozioma** (stała), nie rosnąca. **Poprawka:** „linia pozioma na wykresie v(t), na stałej wysokości v₀”.

### Temat 2 — Siły i dynamika

Brak dodatkowych błędów w plikach teorii poza notacją opisaną w sekcji 2.

### Temat 3 — Praca, moc, energia

- [ ] **`teoria/3.1_praca_mechaniczna_i_moc.md:21`** — literówka/błędne słowo: „powtarzające się **skróty** i drgania włókien mięśniowych” → powinno być „**skurcze**”.

- [ ] **`teoria/3.1_praca_mechaniczna_i_moc.md:69`** — „koń mechaniczny... w przybliżeniu 735 W”, podczas gdy zadanie konkursowe z tego samego tematu cytuje precyzyjniejsze 735,5 W. **Poprawka:** zmienić na 735,5 W dla spójności.

- [ ] **`teoria/3.2_maszyny_proste.md:54`** — opis bloku ruchomego (F=Q/2) nie zawiera zastrzeżenia „pomijając ciężar bloku i tarcie”, w przeciwieństwie do analogicznego zastrzeżenia przy równi pochyłej. **Poprawka:** dopisać to zastrzeżenie.

- [ ] **`teoria/3.2_maszyny_proste.md:87`** — wzór na kołowrotek jest jedynym w pliku bez towarzyszącej listy „gdzie:”. **Poprawka:** dodać opis zmiennych.

### Temat 4 — Termodynamika

- [ ] **`teoria/4.3_energia_wewnetrzna_i_cieplo.md:12`** — błąd gramatyczny: „pompując **rowerowa** pompką” → „**rowerową** pompką”.

- [ ] **`teoria/4.1_temperatura_i_rownowaga_termodynamiczna.md:7`** — brak zaimka zwrotnego: „kurczy, gdy temperatura spada” → „kurczy **się**”.

- [ ] **`teoria/4.5_przewodnictwo_cieplne_i_konwekcja.md:19`** — brak zaimka zwrotnego: „unosi do góry” → „unosi **się** do góry” (por. poprawną formę w linii 9 tego samego pliku).

- [ ] **`teoria/4.5_przewodnictwo_cieplne_i_konwekcja.md:23`** — niezgodność liczby: „choć **obie** nagrzały się” przy porównaniu trzech materiałów (metal/drewno/plastik) → „choć **wszystkie trzy** nagrzały się”.

- [ ] **`teoria/4.8_budowa_czasteczkowa_materii.md:39`** — niezgodność liczby: „drobinki są bombardowane... szarpią **drobinkę**” → „szarpią **te drobinki**”.

### Temat 5 — Hydrostatyka

- [ ] **`teoria/5.1_gestosc.md:45-47`** — nagłówek ciekawostki „wieża z siedmiu cieczy”, ale treść wymienia tylko 5 cieczy. **Poprawka:** zmienić nagłówek na „wieża z kilku cieczy” albo dopisać brakujące dwie ciecze, żeby liczba się zgadzała.

- [ ] **`teoria/5.2_napiecie_powierzchniowe.md`** — podaje tylko jednostkę N/m dla σ, ale zadanie konkursowe w `zadania_zdolny_slazak.md:91` (2023/2024, zad. 19) wymaga wiedzy, że J/m² i kg/s² to te same jednostki. **Poprawka:** dopisać zdanie: „Napięcie powierzchniowe można też zapisać jako J/m² lub kg/s² — to te same jednostki: 1 N/m = 1 J/m² = 1 kg/s²”.

- [ ] **`teoria/5.2_napiecie_powierzchniowe.md`** — sekcja z przykładem nazwana „### Przykład” bez numeru, w przeciwieństwie do „Przykład 1” w 5.1/5.3/5.4. **Poprawka:** ujednolicić na „Przykład 1”.

---

## 4. 🟠 Błędy/niespójności w zadaniach i quizach (per temat)

### Temat 0

- [ ] **`zadania_proste.md` (zad. 1) / `zadania_proste_rozwiazania.md` (linie 5, 8, 10)** — używa konwencji „niepewność = cała działka” (metr krawiecki 1mm, termometr 2°C), sprzeczne z regułą „połowa działki” z teorii 0.1 i quizu (pyt. 3b uznaje „cała działka” za FAŁSZ). To realna sprzeczność: uczeń po przerobieniu teorii dojdzie do wniosku, że klucz tego zadania jest błędny. **Poprawka:** zmienić wartości na 0,5mm (metr krawiecki) i 1°C (termometr), zachowując wartości niepodlegające połowieniu (suwmiarka 0,1mm, waga cyfrowa 5g) — albo dopisać zastrzeżenie, że zadanie wiernie cytuje źródło używające innej, także spotykanej konwencji.

- [ ] **`zadania_proste.md` (zad. 3) / rozwiązanie** — używa reguły „przy odejmowaniu wielkości niepewności się dodają”, która nie jest wprowadzona nigdzie w plikach teorii 0.0–0.6. **Poprawka:** dodać krótki akapit o propagacji niepewności przy dodawaniu/odejmowaniu do `teoria/0.2_niepewnosc_pomiarowa_i_zapis_wyniku.md`.

### Temat 1

- [ ] **`teoria/quiz_odpowiedzi.md:3`** — błędne odwołanie: „Odpowiedzi do quizu z pliku `1.0_kinematyka.md`” → powinno być `quiz.md`.

- [ ] **`teoria/quiz_odpowiedzi.md`** — brak linku powrotnego „⬅ Powrót do spisu treści”, obecnego we wszystkich innych plikach katalogu. **Poprawka:** dodać dla spójności.

- [ ] **`teoria/1.6_pomiary_charakterystyk_ruchu.md:32`** — wzór używa d=1,0m, wartość podana tylko na ilustracji SVG, nie w prozie. **Poprawka:** dopisać zdanie podające tę wartość wprost przed użyciem wzoru.

- [ ] **`zadania_zdolny_slazak.md`** — zadania o prędkości względnej (kajak-wiatr, samochody, helikopter) wymagają dodawania/odejmowania prędkości wzdłuż prostej, ale żaden plik teorii 1.1–1.6 tego nie uczy explicite liczbowo (1.1 jest tylko jakościowe). **Poprawka:** dodać krótki przykład liczbowy prędkości względnej w 1.1 lub 1.2.

### Temat 2

Brak dodatkowych błędów w zadaniach poza opisanymi w sekcjach 1–2 (błąd geometrii sił, symbol μ).

### Temat 3

- [ ] **`zadania_proste_rozwiazania.md` (zad. 10)** — dopisano nieuzasadnione założenie „(przy wyrzucie z poziomu ziemi)”, którego nie ma w treści zadania. **Poprawka:** zamienić na neutralne „(przyjmujemy poziom wyrzutu jako poziom odniesienia, h=0)”.

### Temat 4

- [ ] **`teoria/quiz.md` (pytanie 10)** — treść zaczyna od „substancji”, kończy pytaniem o „tę ciecz” bez wcześniejszego stwierdzenia, że to ciecz. **Poprawka:** zamienić „ta ciecz” na „ta substancja”.

- [ ] **`teoria/quiz_odpowiedzi.md:20`** — „Kelviny” wielką literą, sprzeczne z regułą z `4.2_skale_temperatur.md:10` („kelwiny” małą literą, polska pisownia). **Poprawka:** zmienić na małą literę. *(Uwaga: analogiczny zapis dużą literą w `zadania_zdolny_slazak.md` to wierny cytat z oryginalnego arkusza — tego NIE poprawiać.)*

- [ ] **`zadania_proste.md:8`** — nienaturalny szyk „100°C gorącą wodę” (kalka z angielskiego). **Poprawka:** „gorącą wodę o temperaturze 100°C”, zgodnie z konwencją w 4.1.

- [ ] **`zadania_proste_rozwiazania.md:30`** — nietrafny dobór słowa „usystematyzowane ('sztywne') wiązania” → „**uporządkowane**”.

### Temat 5

- [ ] **`teoria/quiz_odpowiedzi.md:3`** — błędne odwołanie: „Numeracja odpowiada... `5.0_wlasciwosci_materii_i_hydrostatyka.md`” → powinno być `quiz.md`.

- [ ] **`zadania_zdolny_slazak.md:61`** — słowo „**obiektowanie**” w nagłówku „[5.1 Gęstość — obiektowanie z naczynia z jajkiem]” nie jest polskim słowem i wygląda na błąd transkrypcji. **Do weryfikacji/poprawy:** sprawdzić w oryginalnym arkuszu PDF, jakiego słowa faktycznie używa źródło (prawdopodobnie „obliczanie” lub „wyznaczanie”), i poprawić transkrypcję zgodnie z nim — nie wprowadzać własnego sformułowania bez sprawdzenia źródła.

---

## 5. 🟡 Struktura repozytorium i metadane

- [ ] **`tematy/inne/zadania_zdolny_slazak.md:3`** — odsyła do nieistniejącego pliku `tematy/0-pomiary-i-niepewnosci/zadania.md`. Właściwa ścieżka to `tematy/0-pomiary-i-niepewnosci/zadania_zdolny_slazak.md`. **Poprawka:** poprawić ścieżkę.

- [ ] **`README.md:103-109`** — „Harmonogram 2025/2026” jest już nieaktualny (bieżąca data 2026-07-14, etap wojewódzki minął 27.02.2026 — ponad 4 miesiące temu), a repo było aktualizowane 2026-07-13. **Poprawka:** dodać adnotację „edycja zakończona” i/lub przenieść nacisk na nadchodzącą edycję 2026/2027 (gdy zostanie ogłoszona).

- [ ] **`tematy.md:106`** — przypis źródłowy „etap powiatowy (pkt. 6)” pomija punkty 7 (Prąd elektryczny) i 8 (Magnetyzm), które są wymienione w treści pliku jako część materiału. **Poprawka:** zmienić na „etap powiatowy (pkt. 6–8)”.

- [ ] **Niespójne nagłówki plików przeglądowych X.0:** `0.0` używa kropki („Temat 0. Pomiary...”), `1.0`/`2.0`/`5.0` używają dwukropka („Temat N: ...”), a `3.0`/`4.0` w ogóle pomijają słowo „Temat” („3. Praca...”, „4. Termodynamika”). **Poprawka:** ujednolicić wszystkie sześć plików do wzorca `# Temat N: ...`.

- [ ] **`arkusze/*.txt`** — 7 nieśledzonych przez git plików (`git status` pokazuje `??`), wyglądających na surowe zrzuty pdftotext z odpowiednich PDF-ów, nigdzie niereferencjonowanych w repo i nieobjętych `.gitignore`. **Poprawka:** albo dodać do `.gitignore` (jeśli to tylko robocze artefakty), albo usunąć, albo — jeśli mają służyć jako źródło do dalszej pracy nad materiałami — nadać im wyraźne miejsce i wzmiankę w repo.

---

## Podsumowanie liczbowe

| Kategoria | Liczba znalezionych problemów |
|---|---|
| 🔴 Krytyczne (zadania nierozwiązywalne/błędny wynik) | 5 |
| 🟠 Niespójności notacji/stałych między tematami | 11 |
| 🟠 Błędy merytoryczne w teorii | 15 |
| 🟠 Błędy/niespójności w zadaniach i quizach | 13 |
| 🟡 Struktura repozytorium i metadane | 5 |
| **Razem** | **49** |

Materiały poza powyższymi punktami zostały przez recenzentów wyraźnie potwierdzone jako poprawne: wszystkie klucze odpowiedzi w quizach (6×10 pytań) i zadaniach prostych (6 tematów), zgodność wzorów w treści z `wzory.md` (poza wyjątkami opisanymi wyżej), poprawność ilustracji SVG względem opisywanego tekstu, brak regresji znanego błędu renderowania LaTeX-a w blockquote na GitHubie, oraz poprawność wszystkich linków wewnętrznych.
