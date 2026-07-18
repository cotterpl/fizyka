# CLAUDE.md

Wytyczne dla pracy w tym repozytorium — materiały do nauki fizyki (kl. 7–8 szkoły podstawowej) przygotowujące ucznia do Dolnośląskiego Konkursu Fizycznego **zDolny Ślązak** (etap szkolny/powiatowy; etap wojewódzki obejmuje też punkty 9–10 zakresu z `tematy.md`, czyli materiał liceum — poza głównym zakresem tego repo).

## Struktura repozytorium

```
tematy/<N>-<nazwa-tematu>/
  teoria/
    N.0_<temat>.md              — wprowadzenie / spis podtematów
    N.1_<podtemat>.md ... N.k_  — kolejne podtematy
    quiz.md, quiz_odpowiedzi.md — 10 pytań podsumowujących cały temat
    ilustracje/*.svg (+.jpg)    — wykresy i diagramy
  zadania_proste.md             — zadania rozgrzewkowe z realnych, sprawdzonych źródeł (linki)
  zadania_proste_odpowiedzi.md  — same odpowiedzi (bez toku rozwiązania)
  zadania_proste_rozwiazania.md — pełne rozwiązania krok po kroku
  zadania_zdolny_slazak.md      — zadania konkursowe, transkrybowane z arkuszy w arkusze/
tematy/inne/zadania_zdolny_slazak.md — zadania konkursowe niepasujące do żadnego tematu 0–5
arkusze/*.pdf                   — oryginalne arkusze szkolnego etapu konkursu (źródło prawdy dla zadania_zdolny_slazak.md)
README.md    — spis treści całego repo + info o konkursie (zasady, terminy, korzyści)
tematy.md    — pełny zakres materiału wg regulaminu konkursu (etap szkolny/powiatowy vs wojewódzki)
wzory.md     — ściąga ze wzorami bazowymi z tematów 0–5, JEDYNE oficjalne źródło notacji symboli
```

Tematy 0–5 (zakres etapu szkolnego/powiatowego): 0. Pomiary i niepewności, 1. Kinematyka, 2. Siły i dynamika, 3. Praca/moc/energia, 4. Termodynamika, 5. Właściwości materii i hydrostatyka. Tematy 6–10 z `tematy.md` (elektrostatyka, prąd, magnetyzm, drgania/fale, optyka) to zakres etapu wojewódzkiego — obecnie **nie mają jeszcze plików** w `tematy/`; jeśli powstaną, powinny zachować identyczną strukturę katalogów jak 0–5.

## Konwencje, których należy bezwzględnie przestrzegać

### 1. `wzory.md` jest jedynym źródłem prawdy dla notacji symboli i wartości stałych

Każdy symbol i każda wartość liczbowa stałej (np. `g`) użyta w plikach teorii/zadań musi być identyczna z tym, co podaje `wzory.md`. Jeśli dodajesz nowy wzór w teorii, sprawdź najpierw, czy analogiczny wzór już istnieje w `wzory.md` — użyj tam zdefiniowanego symbolu, nie wprowadzaj nowego. Ustalone konwencje symboli (po korektach z `poprawki.md`):

- `g = 9,81 m/s²` (nie 9,8 — literatura źródłowa w temacie 2 i 3 używa 9,81)
- gęstość: `ρ` (nie `d`)
- współczynnik tarcia: `f` (nie `μ`)
- ciężar: `F_g` (nie `Q`, nie `F_c`)
- energia mechaniczna: `E_m` (nie `E_c`)
- prędkość: `v` łacińskie (nie `υ` greckie ypsilon)
- wartość prędkości: „wartość prędkości" (nie „szybkość" — dopuszczalna tylko jako wzmianka „potocznie nazywana szybkością")
- maszyna prosta z korbą: „kołowrót" (nie „kołowrotek"), z wałem (nie „walcem")
- niepewność pomiaru przyrządem analogowym: **cała działka elementarna** (polska konwencja szkolna, zgodna z zpe.gov.pl i podręcznikami SP; konwencja „pół działki" to tradycja anglosaska/akademicka — wzmiankowana wyłącznie jako jawnie oznaczone rozszerzenie w `0.1`)

Jeśli zadanie źródłowe (podręcznik, arkusz konkursowy) używa innego symbolu niż ustalony w `wzory.md`, **przekonwertuj notację** w naszym pliku albo dopisz wprost „(oznaczane też jako X — zobacz `wzory.md`)”. Nie zostawiaj cichej rozbieżności.

`wzory.md` celowo pomija trywialne przekształcenia już podanego wzoru (zamianę zmiennej) — ale NIE pomijaj wzoru, który eliminuje inną zmienną (np. $v^2=v_0^2+2as$ eliminuje czas) albo obejmuje inny przypadek geometryczny (np. $F_w=\sqrt{F_1^2+F_2^2}$ dla sił prostopadłych) — jeśli taki wzór jest używany w quizie/zadaniach, musi być w ściądze.

### 2. Konwencja skalar/wektor (patrz `tematy/0-pomiary-i-niepewnosci/teoria/0.6_skalary_i_wektory.md`)

- Wzór ze strzałkami (np. $\vec{F}=m\vec{a}$) = prawdziwe równanie wektorowe, obowiązujące niezależnie od kierunku.
- Wzór bez strzałek = liczy tylko wartość (moduł); przy KAŻDYM symbolu w opisie „gdzie:” dopisz `(skalar)` albo `(wektor — tu użyta wartość)`.
- Częste pułapki, na które już natrafiono w przeglądzie: `g` (przyspieszenie ziemskie) to zawsze **wektor**, nawet gdy wzór liczy tylko jego wartość — nigdy nie oznaczaj go jako `(skalar)`. Ciśnienie, praca, energia, ciepło, gęstość są zawsze skalarami.
- Dodawanie/odejmowanie wektorów pod kątem (metoda równoległoboku, Pitagoras) jest **poza podstawowym zakresem** — jeśli wprowadzasz taki wzór w teorii, dopisz wyraźne zastrzeżenie o tym (wzorem z `0.6`), żeby uczeń wiedział, że to rozszerzenie.

### 3. Poziom trudności

Docelowy odbiorca: uczeń kl. 7/8, etap szkolny/powiatowy konkursu (NIE olimpiada fizyczna dla liceum). Przy dodawaniu nowych zadań/teorii:
- Unikaj wielostopniowych zadań łączących >2 zjawiska naraz (np. bilans cieplny z kilkoma przemianami fazowymi jednocześnie), chyba że to wierny cytat z realnego arkusza konkursowego.
- Unikaj wymagania rachunku różniczkowego/całkowego czy zaawansowanej trygonometrii.
- Materiał rozszerzający poza zakres regulaminu (np. `0.6`, przypadek sił pod kątem) musi być jawnie oznaczony jako rozszerzenie.

### 4. Zadania z `arkusze/*.pdf` muszą być transkrybowane wiernie i kompletnie

`zadania_zdolny_slazak.md` w każdym temacie to transkrypcja realnych zadań z arkuszy PDF. Przy dodawaniu/edycji takiego zadania:
- **Zawsze zawrzyj wszystkie dane liczbowe potrzebne do rozwiązania w samej treści** (nie tylko „patrz wykres” bez wartości) — przegląd znalazł kilka zadań nierozwiązywalnych właśnie z tego powodu, bo dane były tylko na rysunku w PDF, którego uczeń tutaj nie widzi.
- Jeśli zadanie odwołuje się do rysunku z siłami/kątami/proporcjami (np. dźwignia z podziałką w kratkę), **zweryfikuj rysunek w oryginalnym PDF** (nie zgaduj z samego tekstu) i przepisz dokładne wartości/proporcje do treści.
- Zachowaj format cytowania: `Rok: ... | Zadanie ... | Źródło: ...`, spójny we wszystkich plikach `zadania_zdolny_slazak.md`.
- Wierne błędy/konwencje oryginalnego arkusza (np. „Kelvin” wielką literą, jeśli tak jest w PDF) **zostają nietknięte** w cytacie — to nie jest błąd do poprawienia, bo zmieniłoby to wierność transkrypcji. Błędy poprawiamy tylko w tekstach, które są własną twórczością tego repo (teoria, quiz, jego odpowiedzi).

### 5. Przy dodawaniu/edycji dowolnego zadania rachunkowego

**Zawsze przelicz odpowiedź samodzielnie przed zapisaniem klucza** — nie ufaj bezkrytycznie źródłu ani wcześniejszej wersji pliku. Sprawdź spójność między trójką plików `zadania_proste.md` / `_odpowiedzi.md` / `_rozwiazania.md` (te same liczby, ta sama metoda). Nie dodawaj w rozwiązaniu założeń, których nie ma w treści zadania (np. „przy wyrzucie z poziomu ziemi”, gdy treść tego nie mówi) — jeśli trzeba przyjąć założenie, dopisz je też do treści zadania, nie tylko do rozwiązania.

### 6. LaTeX i Markdown na GitHub

- GitHub **nie renderuje LaTeX-a wewnątrz blockquote** (linie zaczynające się od `>`). Nigdy nie umieszczaj `$...$` ani `$$...$$` w cytacie blockquote — wyciągnij wzór poza blockquote albo zapisz go zwykłym tekstem (np. `v = s/t` bez `$`).
- Sprawdzaj parzystość znaczników `$`/`$$` przy każdej edycji wzoru.
- Ilustracje generowane własnoręcznie (SVG) powinny mieć w podpisie dopisek „*Ilustracja własna*” z krótkim uzasadnieniem, jeśli nie znaleziono gotowego obrazka z tymi samymi liczbami — zobacz `1.4_wykresy_ruchu.md`/quiz temat 1 jako wzór.
- Każdy plik teorii kończy się linkiem `[⬅ Powrót do spisu treści](N.0_...md)` — zachowaj to przy nowych plikach.

### 7. Nagłówki i spójność strukturalna

- Nagłówek pliku `N.0_*.md` (wprowadzenie tematu) powinien mieć format `# Temat N: <nazwa>` (dwukropek, ze słowem „Temat”) — ujednolicone po korektach z `poprawki.md`.
- Każdy nowy plik `.md` pod `tematy/` musi być dodany do spisu treści w `README.md` (link do teorii, quizu, zadań) oraz uwzględniony w `tematy.md`, jeśli wprowadza nowy podtemat z regulaminu konkursu.
- Każdy link względny (do innego pliku `.md`, ilustracji, PDF-u) musi wskazywać na istniejący plik — po każdej zmianie nazwy/lokalizacji pliku przeszukaj repo pod kątem odwołań doń.

## Jak weryfikować zmiany przed zakończeniem pracy

1. Jeśli edytujesz wzór/definicję w teorii — sprawdź `wzory.md` i zaktualizuj oba miejsca razem.
2. Jeśli dodajesz/zmieniasz zadanie rachunkowe — przelicz je samodzielnie i zweryfikuj klucz odpowiedzi.
3. Jeśli edytujesz `zadania_zdolny_slazak.md` — zweryfikuj treść względem oryginalnego PDF w `arkusze/`.
4. Sprawdź, czy nie wprowadziłeś LaTeX-a wewnątrz blockquote.
5. Sprawdź linki względne do zmienionych/przeniesionych plików.
6. Zobacz `poprawki.md` — pełną listę znanych problemów (część może wciąż czekać na naprawę); nie wprowadzaj nowych regresji tego samego typu.

## Język i styl

Cały materiał jest po polsku. Zachowuj naturalny szyk zdania polskiego (nie kalki z angielskiego typu „100°C gorącą wodę” — poprawnie: „wodę o temperaturze 100°C”). Liczby dziesiętne zapisuj przecinkiem (`9,81`, nie `9.81`) poza kodem/wzorami LaTeX, gdzie używana jest notacja `{,}` (np. `9{,}81` wewnątrz `$...$`, żeby przecinek nie kolidował ze składnią LaTeX).
