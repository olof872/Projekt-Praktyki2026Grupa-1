# Projekt-Praktyki2026Grupa-1
Nasz projekt na praktyki 2026 

Filip Rozbicki
05.10.2026 - Szkolenie z Zakresu BHP, lekcja Organizacyjno-zapoznawcza.
06.10.2026 - Zapozannie  sie z wymaganiami glownego projektu, analiza zalozen projektu oraz okreslanie jego funkcjonalnosci i zakresu prac 
07.10.2026 - Zapoznanie sie z naredziem Ollama oraz sposobem wykorzystywania API do komunikacji z modelami jezykowymi. Poznanie podstaw dzialania LLM i mozliwosci ich zastosowania w aplikacjach.
08.10.2026 - Instalacja i konfiguracja srodowiska ollama oraz przygotowanie modelu jezykowego do testu. Przygotowanie i konfiguracja technologii oraz narzedzi programistycznych niezbednych do realizacji projektu.
09.10.2026 - Pierwsze zadanie strona do podgladu plikow TXT i PDF, przydzielenie  kazdemu czlonkowi zespolu odpowiedniego zadania wspolna narada na temat kierunku poczatkowego projektu.
12.10.2026 - Zapoznanie z technologiami ktore wykorzystamy na stronie, przygotowanie srodowisk pracy i wstepne rozpoczecie projektu
13.10.2026 - Tworzenie struktury stron internetowych w HTML, Formatowanie tresci i elementow strony, Tworzenie skryptow w jezyku PHP, Obsluga formularzy i przetwarzanie danych
14.10.2026 - Finalizowanie projektu, polaczenie pracy zespolu w jednosc wspolna debata na temat napotkanych problemow, wspolne rozwiazanie bledow wystepujacych w kodzie jako zespol.
15.10.2026 - Poprawki i polaczenie kodu, stworzenie dokumentacji na temat projektu. Nadzor koncowych testow i podsumowanie projektu o stronie do podgladu plikow TXT i pdf. Zapoznanie sie ze sposobami integracji Ollama API z jezykiem PHP oraz poznanie metod wysylania zapytan i odbierania odpowiedzi z modelu jezykowego.
16.10.2026 - Analiza wymagań projektu i zaplanowanie nowych funkcji aplikacji, Przygotowanie obsługi plików TXT i PDF z wykorzystaniem PHP oraz JavaScript. Planowanie funkcji i podział zadań. Zaplanowanie mechanizmu wykrywania określonych ciągów znaków w tekście: aaa, yy oraz ee.
19.10.2026 - Implementacja mechanizmu wyszukiwania wskazanych ciągów znaków. Dodanie podglądu wykrytych fragmentów i kontekstu tekstowego. 
20.10.2026 - Podzieliłem zadania w zespole i ustaliłem strukturę projektu oraz technologie (PHP, JavaScript, Ollama), Napisałem backend ollama.php, który komunikuje się z lokalnym serwerem Ollama przez cURL. Zaimplementowałem sprawdzanie połączenia z Ollamą i obecności modelu Bielik. Napisałem obsługę wgrywania plików w PHP: kontrola formatu, rozmiaru i typu MIME.
21.10.2026 - Stworzyłem funkcję analizy języka: wysyłanie zdań do modelu i odbiór wyników w formacie JSON. Zabezpieczyłem backend: walidacja danych wejściowych, limity długości, obsługa błędów, ochrona przed prompt injection. 
22.10.2026 - Połączyłem pracę frontendu z backendem i odebrałem poprawki od testera. Zaprogramowałem w JavaScript wykrywanie powtórzonych liter (regex) i dzielenie tekstu na zdania. Zakonczylem projektowanie dokumentacji
23.10.2026 -Przeanalizowałem wymagania dotyczące stenogramu i zaplanowałem potok: tekst, model, lista ustaleń, drugi model, JSON
26.10.2026 - Napisałem akcję protocol_extract w ollama.php: prompt wyciągający tematy, decyzje, zadania i otwarte pytania, razem z korektą błędów rozpoznawania mowy.
27.10.2026 - Dodałem akcję protocol_merge, regułę „nie zmyślaj“ w promptach i czyszczenie wyniku z pustych punktorów i tabulatorów.
28.10.2026 -  Opracowanie i ukończenie dokumentacji technicznej projektu, przygotowanie oraz przekazanie gotowej paczki ZIP z aplikacją do testera w celu weryfikacji poprawności działania. Udział w dyskusji zespołowej dotyczącej przebiegu prac, napotkanych problemów, zastosowanych rozwiązań oraz możliwości dalszego rozwoju projektu
29.10.2026 -
30.10.2026 -



Daniil Vorotynskyj
• 05.10.2026 - Szkolenie z Zakresu BHP, lekcja Organizacyjno-zapoznawcza.
• 06.10.2026 - Zapozannie sie z wymaganiami glownego projektu, analiza zalozen projektu oraz okreslanie jego funkcjonalnosci i zakresu prac
• 07.10.2026 - Analizowanie dokumentacji technicznej narzędzia Ollama pod kątem prezentacji danych na stronie. Badanie wymagań dotyczących interfejsu użytkownika przy współpracy z modelami językowymi (LLM).
• 08.10.2026 - Zapoznawanie się z funkcjami wyświetlania odpowiedzi z Ollama oraz przygotowanie stanowiska pracy. Konfiguracja lokalnego środowiska programistycznego i edytora kodu pod tworzenie stylów CSS i struktury HTML.
• 09.10.2026 - Udział w zespołowym planowaniu projektu i podziale zadań. Przydzielenie mi odpowiedzialności wyłącznie za warstwę frontendową (wygląd aplikacji w CSS i strukturę HTML). Omawianie makiety strony do podglądu plików TXT i PDF.
• 12.10.2026 - Dobór nowoczesnej palety barw i stworzenie zmiennych w CSS (:root) pod ciemny motyw aplikacji (kolory tła, paneli, obramowań oraz akcentów). Przygotowanie struktury plików arkuszy stylów oraz resetowanie domyślnych marginesów przeglądarki (box-sizing).
• 13.10.2026 - Kodowanie układu graficznego strony w HTML i CSS. Implementacja siatki .cards z użyciem technologii CSS Grid do równego rozmieszczenia paneli, projektowanie wyglądu strefy przeciągania plików (.drop-zone) z przerywaną ramką oraz tworzenie stylów dla okna podglądu tekstu .preview z użyciem czcionki o stałej szerokości znaków (Monospace).
• 14.10.2026 - Integracja gotowych stylów CSS i struktury HTML z kodem backendowym reszty zespołu. Praca nad wizualnymi stanami przycisków (:hover) i strefy upuszczania plików (.drop-zone.active) po wykryciu pliku. Wspólne usuwanie błędów z nachodzeniem na siebie elementów i debugowanie układu frontendu.
• 15.10.2026 - Implementacja stylów dla odtwarzacza plików PDF (#pdfPreview) oraz sekcji komunikatów o błędach (.error). Napisanie reguł responsywnych (@media (max-width: 700px)) zapewniających płynne działanie strony i układ jednokolumnowy na telefonach komórkowych. Przygotowanie dokumentacji kodu CSS.
• 16.10.2026 - Analiza wymagań projektu i zaplanowanie nowych funkcji aplikacji 
• 19.10.2026 - Przygotowanie opcji ręcznego zatwierdzania zmian: „Usuń” i „Zostaw”. Dodanie nawigacji pomiędzy wykryciami za pomocą przycisków „Back” i „Next”
• 20.10.2026 - Dokończenie implementacji panelu kontrolnego (przycisków „Usuń”, „Zostaw”, „Back”, „Next”) i powiązanie ich z widokiem kontekstu tekstowego. Ostylowanie podświetleń (highlighting) wykrytych fraz aaa, yy oraz ee w oknie podglądu.
• 21.10.2026 - Zaprojektowałem układ strony głównej w HTML i CSS: nagłówek, dwie karty (wybór pliku i przeciąganie) oraz sekcję podglądu. Ostylowałem strefę drag & drop, w tym efekt podświetlenia przy przeciąganiu pliku (.drop-zone.active).
Stworzyłem wspólny arkusz stylów dla trzech podstron: pasek nawigacji, przyciski i kolory.
• 22.10.2026 -  Zrobiłem stylowanie panelu przeglądania wyników: licznik, etykieta wykrytego języka, pole z kontekstem zdania. Dodałem style komunikatów (sukces, błąd, status połączenia) w różnych kolorach.
Dostosowałem stronę do telefonów za pomocą media queries. Połączyłem ze sobą podstrony (przyciski „Stutter Checker →" i „Language Checker →").
23.10.2026 - Pracowałem nad frontendem. Przejrzałem kod HTML i CSS wszystkich podstron, sprawdziłem wygląd w przeglądarce i poprawiłem style, żeby strony wyglądały spójnie.
26.10.2026 - Przygotowałem strukturę HTML podstrony protokołu: wybór pliku, pole komunikatów, panel z wynikiem i przyciski pobierania.
27.10.2026 - Ostylowałem w CSS panel protokołu i tabelę zadań. Dodałem style do wydruku (@media print) i linki do nowej podstrony w menu.
• 28.10.2026 - Testowanie kodu HTML/CSS, porządkowanie plików projektu i podsumowanie prac frontendowych.
• 29.10.2026 -
• 30.10.2026 -



Wiktor Sachanowicz
05.10.2026-Szkolenie z zakresu BHP, lekcja organizacyjno-zapoznawcza.
06.10.2026-Zapoznanie się z wymaganiami projektu, analiza założeń projektu oraz określanie jego funkcjonalności i zakresu prac.
07.10.2026-Zapoznanie się z technologiami potrzebnymi do wykonania projektu LLM-y ollama oraz wybieranie technologii która dobrze komunikuje się z ollama
08.10.2026- Zainstalowanie środowiska ollama oraz środowiska zarzadzajacego pakietami PHP composer przeszkolenie w zakresie łączenia biblioteki  PHP z ollamą
09.10.2026- Otrzymanie pierwszego zadania od opiekuna praktyk czyli stworzenie strony pozwalającej na podgląd plikow txt oraz pdf przydzielenie zadań przez lidera projektu otrzymane zadanie testera i koordynatora wyników pracy nad frontendem i backendem strony wykonywanej przez resztę grupy oraz poprawianie ewentualnych błędow projektu.
12.10.2026- Przygotowywanie stanowiska do rozpoczęcia projektu.
13.10.2026-Tworzenie struktury stron internetowych w HTML, Formatowanie tresci i elementow strony, Tworzenie skryptow w jezyku PHP, Obsluga formularzy i przetwarzanie danych
14.10.2026-konczenie pracy nad kodem strony, wspolna praca zespołu na rozmowie rozmawianie o napotkanych bledach przy pisaniu kodu, pierwszy test strony i naprawa bledow.
15.10.2026 Ostatnie poprawki i testy w kodzie strony wyswietlajacej pliki txt i pdf oraz  przygotowanie i uzupełnienie dokumentacji projektu grupy.
 16.10.2026 - Analiza wymagań projektu i zaplanowanie nowych funkcji aplikacji 
19.10.2026 -• utworzenie przypisów i scenariuszy testowych dla wyszukiwarki ciągów znaków oraz walidatora błędów

20.10.2026 -analiza specyfikacji i makiet projektu pod kątem niespójności logicznych w wyszukiwarce
21.10.2026 -przygotowanie bazy tekstów z trudnymi przypadkami (znaki arabskie, emotikony, kropki nienawiści, brak spacji, kody HTML, testowanie front endu
22.10.2026 -testowanie pełnej strony naprawa połączenia z ollamą wypełnienie dokumentacji w zakresie testow projektu.
23.10.2026 -Brak możliwosci pracy ze wzgledu na pólmetek.
 26.10.2026 -26.10.2026 - Przygotowanie plikow testowych (stenogram z błędami ASR, tekst bez decyzji, pusty plik, PDF) i przeprowadził pierwsze testy generowania protokołu. (byly znalezione bledy i przekazane liderowi projektu 
 27.10.2026 -Testowanie aplikację w przeglądarce i zgłaszanie zespołowi błedow naprawa połączenia bielika w generowaniu protokołu.
28.10.2026 -Ostatnie testy projektu, Udział w dyskusji zespołowej dotyczącej przebiegu prac, napotkanych problemów, zastosowanych rozwiązań oraz możliwości dalszego rozwoju projektu.
 29.10.2026 -
 30.10.2026 -

