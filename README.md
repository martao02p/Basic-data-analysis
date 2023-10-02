# Analiza eksploracyjna i test statystyczny

**Autor:** Marta Szymańska

## Opis zbioru danych

Muzykoterapia, znana także jako MT, polega na wykorzystaniu muzyki do redukcji stresu, poprawy nastroju i ogólnego stanu zdrowia psychicznego danej osoby. Jest to praktyka oparta na dowodach naukowych, wykorzystująca muzykę jako katalizator do uwalniania "szczęśliwych" hormonów, takich jak oksytocyna. Muzykoterapia wykorzystuje szeroki zakres różnych gatunków muzycznych.

Ten zbiór danych ma na celu zrozumienie, jakie korelacje istnieją między indywidualnym gustem muzycznym a stanem zdrowia psychicznego zgłaszanym przez badanych. Potencjalne odkrycia mogą pomóc w lepszym zrozumieniu wpływu muzyki na zdrowie psychiczne lub dostarczyć interesujących wglądów w funkcjonowanie umysłu.

Zbiór danych został pozyskany z platformy Kaggle i jest dostępny pod adresem: [MXMH Survey Results](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results).

## Charakterystyka zbioru danych

- Liczba obserwacji: 736
- Badani nie byli ograniczeni wiekiem ani lokalizacją.
- Ankieta była przeprowadzana wśród różnych osób, głównie za pośrednictwem platform takich jak Discord, Reddit i inne media społecznościowe. Plakaty i ulotki były również wykorzystywane do promocji ankiety w bibliotekach, parkach i innych miejscach publicznych.

### 1: Gatunki muzyczne
- Respondenci oceniali, jak często słuchają 16 różnych gatunków muzycznych, wybierając jedną z opcji:
  - Nigdy
  - Rzadko
  - Czasami
  - Bardzo często

### 2: Zdrowie psychiczne
- Respondenci oceniali swoje doświadczenia związane z lękiem, depresją, bezsennością i zaburzeniami obsesyjno-kompulsyjnymi na skali od 0 do 10, gdzie:
  - 0 - nie doświadczam tego
  - 10 - Doświadczam tego regularnie, stale lub w skrajnym stopniu

### Lista atrybutów w zbiorze danych:

1. Timestamp - Typ danych: Jakościowe
2. Age - Typ danych: Ilościowe
3. Primary streaming service - Typ danych: Jakościowe
4. Hours per day - Typ danych: Ilościowe
5. While working - Typ danych: Jakościowe
6. Instrumentalist - Typ danych: Jakościowe
7. Composer - Typ danych: Jakościowe
8. Fav genre - Typ danych: Jakościowe
9. Exploratory - Typ danych: Jakościowe
10. Foreign languages - Typ danych: Jakościowe
11. BPM - Typ danych: Ilościowe
12. Frequency [Classical] - Typ danych: Jakościowe
13. Frequency [Country] - Typ danych: Jakościowe
14. Frequency [EDM] - Typ danych: Jakościowe
15. Frequency [Folk] - Typ danych: Jakościowe
16. Frequency [Gospel] - Typ danych: Jakościowe
17. Frequency [Hip hop] - Typ danych: Jakościowe
18. Frequency [Jazz] - Typ danych: Jakościowe
19. Frequency [K pop] - Typ danych: Jakościowe
20. Frequency [Latin] - Typ danych: Jakościowe
21. Frequency [Lofi] - Typ danych: Jakościowe
22. Frequency [Metal] - Typ danych: Jakościowe
23. Frequency [Pop] - Typ danych: Jakościowe
24. Frequency [R&B] - Typ danych: Jakościowe
25. Frequency [Rap] - Typ danych: Jakościowe
26. Frequency [Rock] - Typ danych: Jakościowe
27. Frequency [Video game music] - Typ danych: Jakościowe
28. Anxiety - Typ danych: Ilościowe
29. Depression - Typ danych: Ilościowe
30. Insomnia - Typ danych: Ilościowe
31. OCD - Typ danych: Ilościowe
32. Music effects - Typ danych: Jakościowe
33. Permissions - Typ danych: Jakościowe
