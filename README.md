# Metody Numeryczne - Poradnik studencki
## Motywacja powstania niniejszego przewodnika
Na wielu polskich uczelniach wykłada się przedmiot jakim są metody numeryczne, jednak często wykładowcy nie przykładają się do jego nauczania, podobnie jak studenci nie przykładają się do jego poznawania, jest to jedynie przedmiot, który trzeba zaliczyć, bo nie przyda się w życiu. Wychodząc naprzeciw oczekiwaniom tworzę niniejsze repozytorium, w którym będę zamieszczał materiały dotyczące metod numerycznych: wykłady, ćwiczenia, laboratoria, tutoriale. Znajdą się tutaj także rozwiązania zadań, projekty, sprawozdania, ale także programy i skrypty napisane w popularnych językach programowania lub utworzone przy pomocy specjalistycznego oprogramowania matematycznego: Matlab, Python, C, Octave, Scilab, Julia. Wszystko to ma na celu przybliżenie osobom zainteresowaniem tematyki metod numerycznych, a także pomóc studentom w zaliczeniu przedmiotu. W przypadku dalszych problemów służę osobistą pomocą.

Można się ze mną skontaktować drogą mailową: metody.numeryczne.korepetycje@gmail.com. Chętnie pomogę przy zagadnieniach z metod numerycznych, matematyki, informatyki, programowania. Jeśli dysponujesz ciekawymi materiałami lub informacjami również możesz napisać.

## Literatura przedmiotowa
Na polskim rynku istnieje kilka książek tłumaczących w przystępny sposób zagadnienia z dziedziny metod numerycznych. Z książek tych często korzystają wykładowcy nie tylko w celu wytłumaczenia materiału, ale również by zainspirować się przy układaniu zadań, bo zazwyczaj na końcu każdego rozdziału znajdują się zadania do samodzielnego rozwiązania, a także można się spotkać z przykładami już rozwiązanymi. Wymienię teraz najpopularniejsze i najużyteczniejsze pozycje książkowe, oraz trochę o nich opowiem.

### Analiza numeryczna - Kincaid David, Cheney Ward
Pozycja dydaktyków z Uniwersytetu Teksańskiego w Austin szczegółowo wyjaśnia większość najbardziej znanych zagadnień. Napisana nietrudnym językiem, a ponadtwo zawiera przykłady, które pomogą przy rozwiązaywaniu podobnych zadań, a także algorytmy zapisane w pseudokodzie, co pomoże przy pisaniu programów komputerowych. Omawianą książkę umieszczam na pierwszym miejscu, gdyż według mnie jest najbardziej pomocna. Sporo wykładowców ją poleca. Niestety, jeśli by ktoś chciał ją kupić to będzie musiał się trochę naszukać, a też wydać nie tak mało pieniędzy, bo jeśli już gdzieś pojawiają się oferty to jedynie takie z ceną powyżej 100 zł. Na szczęście książka ta jest łatwo dostępna w formie cyfrowej, można ją znaleźć na stronie Instytutu Matematycznego Polskiej Akademii Nauk, wystarczy wpisać w wyszukiwarkę frazę "Kincaid pdf", a jako pierwszy rezultat otrzymamy link do e-booka.

#### Przedmowa autorów
Książka powstawała przez wiele lat z notatek do wykładów z matematyki i informatyki na ostatnim roku studiów podstawowych lub na studiach magisterskich na University of Texas w Austin. Te wykłady wprowadzały studentów w dziedzinę algorytmów i metod najczęściej potrzebnych w obliczeniach naukowych. Zwracaliśmy uwagę zarówno na matematyczne podstawy tych metod, jak i na ich algorytmiczne aspekty. Słuchaczami byli studenci studiów podstawowych z matematyki, nauk technicznych lub ścisłych i informatyki oraz studenci różnych typów studiów magisterskich. Fragmenty książki stanowiły też podstawę wielu wykładów poświęconych poszczególnym działom analizy numerycznej, takim jak rozwiązywanie numeryczne równań różniczkowych, metody numeryczne algebry liniowej i teoria aproksymacji. Nasze podejście polegało zawsze na traktowaniu przedmiotu z matematycznego punktu widzenia; pokazywaliśmy szeroką paletę twierdzeń, dowodów i ciekawych pomysłów. Wynika stąd wiele procedur numerycznych i intrygujących problemów analizy numerycznej. Oczywiście, motywował nas obszar praktycznych zastosowań tej dziedziny, narzucający wybór tematów i sposób ich ujęcia. Tak na przykład, w pewnych działach bardziej pouczające jest rozważanie podstaw teoretycznych niż próba szczegółowego analizowania algorytmów. W innych przypadkach jest na odwrót i studenci wiele wynoszą, programując samodzielnie proste algorytmy i testując je; popieramy jednak bez zastrzeżeń korzystanie ze starannie sprawdzonego oprogramowania, na przykład z bibliotek programów, dotyczącego problemów wynikających z zastosowań. Treść tej książki i treść naszego bardziej elementarnego podręcznika Numerical Mathematics and Computing (wyd. 4, Brooks/Cole) częściowosię pokrywają. Jednak wymieniony podręcznik jest adresowany do studentów mających skromniejsze przygotowanie matematyczne (a często także mniej zapału do studiowania teoretycznych aspektów przedmiotu). Zestaw tematów jest tam inny, a żadnego z nich nie analizuje się zbyt głęboko. Niniejsza książka zaś jest przeznaczona do wykładu dającego bardziej akademickie ujęcie przedmiotu; pewne tematy są opisane szczegółowo. Tu i ówdzie poruszamy zagadnienia, które nie znalazły wcześniej swego miejsca w standardowych podręcznikach na tym poziomie. Do tej kategorii należą metody wielosiatkowe, procedury interpolacji funkcji wielu zmiennych, metody homotopii (lub kontynuacji), równania różniczkowe z opóźnionym argumentemi optymalizacja. Algorytmy w niniejszej książce wyrażamy w symbolice zawierającej nie tylko wzory, ale i dodatkowe elementy. Czytelnik może łatwo przetłumaczyć taki algorytm na dowolny typowy język programowania. Sądzimy, że studenci najlepiej nauczą się metod numerycznych i zrozumieją je, widząc, jak algorytmy wynikają z teoretycznych rozważań, oraz pisząc i testując programy komputerowe. Zapewne nie będą one zawierały wszystkich skomplikowanych procedur i wyszukanych sposobów kontroli, jakimi charakteryzują się programy biblioteczne. Przykłady bibliotek oprogramowania można znaleźć w dodatku A. W wielu zastosowaniach odwołanie się do tych bibliotek jest znacznie bardziej sensowne niż pisanie własnych programów. Ważną częścią składową książki (i niezbędną dla celów dydaktycznych) jest obfitość zadań do rozwiązywania przez studentów; znajdą tu oni dwa rodzaje zadań: analityczne i komputerowe. Te ostatnie z kolei dzielą się na takie, gdzie student ma napisać własny program i takie, gdzie należy zastosować istniejące oprogramowanie. Uważamy, że oba rodzaje praktyki komputerowej są konieczne. Z jednej strony, użycie cudzego programu nie zawsze jest banalnym ćwiczeniem, nawet wtedy, gdy jest on dobrze udokumentowany, jak to bywa w dużych bibliotekach czy pakietach. Z drugiej strony, studenci zdobywają głębszą wiedzę o algorytmie, jeśli go sami programują i testują, niż wtedy, gdy tylko korzystają z programu bibliotecznego. W większości przypadków zadania komputerowe wymagają stosowania arytmetyki zmiennopozycyjnej z liczbami co najmniej 32-bitowymi. Oprogramowanie opisane w książce, erratę do niej i pewne pomoce dydaktyczne można znaleźć w Internecie. Wydawca udostępnia też zbiór rozwiązań zadań wykładowcom, którzy zechcą oprzeć się na tej książce. Trzecie wydanie zawiera nowe zadania, inny jest też ich układ. Usunęliśmy wszystkie błędy zauważone w poprzednich wydaniach. Bibliografia została zaktualizowana. Stronę graficzną zaprojektowano na nowo wprowadziliśmy wiele innych ulepszeń. W szczególności w tym nowym wydaniu dodaliśmy rozdział o optymalizacji z takimi tematami, jak metody spadku, algorytmy przybliżania kwadratowego, algorytm Neldera-Meada, symulowane wyżarzanie, algorytmy genetyczne, optymalizacja Pareto i programowanie wypukłe. Standardowy wykład jednosemestralny można oprzeć na wybranych fragmentach rozdziałów 1-4 i 6-8. Wykład dwusemestralny może obejmować fragmenty rozdziałów 1-9 i dodatkowe interesujące tematy. Rozdziały 4 i 5 można uważać za niezależny od poprzednich, krótki podręcznik numerycznej algebry liniowej. Ze względu na obszerny zakres tematów lektura pewnych podrozdziałów stawia czytelnikom większe wymagania. Na ogół podrozdziały takie zamieściliśmy na końcu rozdziałów, aby na początku lektury nie zniechęcać czytelnika, który według własnego uznania może trudniejsze partie pominąć.

#### Przedmowa tłumacza
Dostępne w Polsce podręczniki analizy numerycznej, jak (włączone do bibliografii) książki Ralstona, Dahlquista i Björcka, Stoera i Bulirscha oraz Dryi i Jankowskich, ukazały się ponad dwadzieścia lat temu. Nowsza jest książka Kiełbasińskiego i Schwetlicka, ale ta dotyczy tylko metod numerycznych algebry liniowej. Potem ukazywały się co najwyżej skrypty wydawane przez niektóre uczelnie i ukierunkowane głównie na dydaktykę. Tymczasem analiza numeryczna jest dziedziną matematyki nie tylko stale stosowaną, ale i rozwijającą się nieustannie, o czym świadczą chociażby coraz to nowe czasopisma naukowe jej poświęcone. Dlatego dobrze się stało, że Wydawnictwa Naukowo-Techniczne postanowiły wydać niniejszy podręcznik. Jest to przekład trzeciego wydania amerykańskiego, w którym można znaleźć – w porównaniu z podręcznikami wymienionymi wyżej - sporo nowości. Wiele tematów ujęto inaczej, na co innego położono nacisk. Jak zwykle, dobór materiału i sposób jego prezentacji wynika z indywidualnychpoglądów i zainteresowań autorów. Nawet tak obszerna książka nie może choćby w skrócie objąć wszystkich najważniejszych działów i metod analizy numerycznej. Żałuję na przykład, że teoria i praktyka przyspieszania zbieżności – tematu ważnego w całej analizie numerycznej – zasłużyły tylko na skąpe wzmianki. Mam nadzieję, że w przyszłości uda się zapełnić tę i inne luki. Na razie zaś, jako tłumacz i redaktor książki, spodziewam się, że jej lektura będzie pożyteczna i dla studentów różnych dyscyplin, i dla osób, które w swej pracy zawodowej posługują się metodami numerycznymi. Tłumacząc książkę, usunąłem bardzo dużo drobnych usterek różnego typu. Jako redaktor przekładu wprowadziłem - za zgodą autorów - sporo zmian nienaruszających oczywiście autorskiej koncepcji książki, ale mających na celu ułatwienie jej lektury i uwzględniających wiedzę polskich czytelników. Skróciłem więc lub pominąłem szczególnie elementarne rozważania, zbędne dla czytelników ze standardowym poziomem wiedzy matematycznej. Dowody kilku twierdzeń zastąpiłem prostszymi lub bardziej naturalnymi. W kilku miejscach przestawiłem fragmenty tekstu, np. poprzedziłem twierdzenie używanymi w nim lematami. Przejrzałem krytycznie listy zadań (a jest ich w książce wyjątkowo dużo!) do poszczególnych podrozdziałów, usunąłem zadania powtarzające się lub wyraźnie banalne, dostosowałem – gdzie było to wskazane – porządek zadań do kolejności wprowadzanych pojęć, metod i twierdzeń. Aby ułatwić czytelnikom lekturę, wprowadziłem w obrębie każdego podrozdziału wspólną numerację twierdzeń, wniosków, przykładów itd. Oryginalny podrozdział 6.11, dający tylko bardzo ogólnikowe wiadomości o ułamkach łańcuchowych, zastąpiłem za zgodą autorów nieco szerszym podrozdziałem o aproksymacji wymiernej, który zawiera wstępne wiadomości nie tylko o takich ułamkach, ale również o interpolacji wymiernej i aproksymacji Padégo. Bibliografia w oryginale zawiera ok. 360 pozycji niecytowanych w tekście. Usunąłem je, bo w wielu przypadkach na podstawie tytułów nie można nawet ustalić, z jakimi dziedzinami te prace się wiążą. Przed przedmową autorów umieściłem krótką listę symboli używanych dalej, a wyjaśnianych w różnych miejscach książki. W przekładzie pominąłem dodatek zawierający komentowaną listę adresów kilkudziesięciu stron z informacjami o towarzystwach naukowych, czasopismach, programach, wykładach itd. z dziedziny analizy numerycznej; informacje na ten temat zawiera przypis do przedmowy autorów. Z podobnych powodów usunąłem też z podrozdz. 2.1 fragment o hipotetycznym komputerze Marc-32, a z dalszych partii książki wszelkie wzmianki o nim (zresztą w końcowych rozdziałach były one coraz rzadsze). Tam, gdzie jest to potrzebne, czytelnicy są informowani o precyzji stosowanej arytmetyki. Jedną z najważniejszych metod numerycznych algebry liniowej jest metoda Cholesky’ego rozkładu macierzy na czynniki. Czytelnicy znający tę metodę z innych podręczników zauważyli zapewne, że nie cytuje się w nich oryginalnej pracy Cholesky’ego. Profesor Claude Brezinski uprzejmie przekazał mi wyniki swych poszukiwań w bibliotekach i archiwach. Teraz już wiadomo, kim był André Louis Cholesky oraz gdzie i kiedy opublikował swą metodę; notabene jest bardzo prawdopodobne, że pochodził on z rodziny polskich emigrantów Cholewskich, osiadłych we Francji w XIX w. Metoda ta w wielu polskich publikacjach nosi imię Tadeusza Banachiewicza, który wynalazł ją niezależnie, ale znacznie później. Profesor Krystynie Ziętak zawdzięczam wiele istotnych uwag dotyczących zarówno oryginału, jak i przekładu, głównie rozdziałów 2-5.

#### Spis treści
1. Narzędzia matematyczne
    * 1.0. Wstęp
    * 1.1. Podstawowe pojęcia i wzór Taylora
    * 1.2. Rząd zbieżności i inne podstawowe pojęcia
    * 1.3. Równania różnicowe
2. Arytmetyka komputerowa
    * 2.0. Wstęp
    * 2.1. Arytmetyka zmiennopozycyjna
    * 2.2. Błędy bezwzględne i względne. Utrata cyfr znaczących
    * 2.3. Algorytmy stabilne i miestabilne. Uwarunkowanie
3. Rozwiązywanie równań nieliniowych
    * 3.0. Wstęp
    * 3.1. Metoda bisekcji (połowienia przedziału)
    * 3.2. Metoda Newtona
    * 3.3. Metoda siecznych
    * 3.4. Punkty stałe i metody iteracyjne
    * 3.5. Obliczanie pierwiastków wielomianów
    * 3.6. Metody homotopii i kontynuacji
4. Rozwiązywanie układów równań liniowych
    * 4.0. Wstęp
    * 4.1. Algebra macierzy
    * 4.2. Rozkłady LU
    * 4.3. Eliminacja Gaussa z wyborem elementów głównych
    * 4.4. Normy i analiza błędów
    * 4.5. Szeregi Neumanna i poprawianie iteracyjne
    * 4.6. Rozwiązywanie układów metodami iteracyjnymi
    * 4.7. Metody najszybszego spadku i sprzężonych gradientów
    * 4.8. Analiza błędów zaokrągleń w metodzie eliminacji Gaussa
5. Inne działy numerycznej algebry liniowej
    * 5.0. Przegląd podstawowych pojęć
    * 5.1. Metoda potęgowa dla zadania własnego
    * 5.2. Twierdzenia Schura i Gerszgorina
    * 5.3. Ortogonalizacja i zadanie najmniejszych kwadratów
    * 5.4. Rozkład względem wartości szczególnych i pseudoodwrotn
    * 5.5. Metoda QR obliczania wartości własnych
6. Aproksymacja funkcji
    * 6.0. Wstęp
    * 6.1. Interpolacja wielomianowa
    * 6.2. Ilorazy różnicowe
    * 6.3. Interpolacja Hermite’a
    * 6.4. Interpolujące funkcje sklejane
    * 6.5. Podstawy teorii funkcji B-sklejanych
    * 6.6. Zastosowania funkcji B-sklejanych
    * 6.7. Szeregi potęgowe
    * 6.8. Aproksymacja średniokwadratowa
    * 6.9. Aproksymacja jednostajna
    * 6.10. Interpolacja funkcji wielu zmiennych
    * 6.11. Aproksymacja wymierna
    * 6.12. Interpolacja trygonometryczna
    * 6.13. Szybkie przekształcenie Fouriera
    * 6.14. Metody adaptacyjne
7. Różniczkowanie i całkowanie numeryczne
    * 7.1. Różniczkowanie numeryczne i ekstrapolacja Richardsona
    * 7.2. Interpolacja w całkowaniu numerycznym
    * 7.3. Kwadratury Gaussa
    * 7.4. Wielomiany Bernoulliego i wzór Eulera-Maclaurina
    * 7.5. Metoda Romberga
    * 7.6. Metody adaptacyjne całkowania
    * 7.7. Teoria Sarda aproksymacji funkcjonałów
8. Rozwiązywanie numeryczne równań różniczkowych zwyczajnych
    * 8.0. Wstęp
    * 8.1. Istnienie i jednoznaczność rozwiązań
    * 8.2. Zastosowanie wzoru Taylora
    * 8.3. Metody Rungego-Kutty
    * 8.4. Metody wielokrokowe
    * 8.5. Błędy lokalne i globalne. Stabilność
    * 8.6. Układy równań. Równania wyższego rzędu
    * 8.7. Zagadnienia brzegowe
    * 8.8. Zagadnienia brzegowe: metody strzału
    * 8.9. Zagadnienia brzegowe: różnice skończone
    * 8.10. Zagadnienia brzegowe: kollokacja
    * 8.11. Układy równań różniczkowych liniowych
    * 8.12. Równania sztywne
9. Rozwiązywanie numeryczne równań różniczkowych cząstkowych
    * 9.0. Wstęp 
    * 9.1. Równania paraboliczne: metody jawne
    * 9.2. Równania paraboliczne: metody niejawne
    * 9.3. Zadania niezależne od czasu: różnice skończone
    * 9.4. Zadania niezależne od czasu: metody Galerkina
    * 9.5. Równania rzędu pierwszego: charakterystyki
    * 9.6. Równania quasi-liniowe rzędu drugiego: charakterystyki
    * 9.7. Inne metody dla zagadnień hiperbolicznych
    * 9.8. Metody wielosiatkowe
    * 9.9. Szybkie metody dla równania Poissona
10. Programowanie liniowe i pokrewne zagadnienia
    * 10.1. Wypukłość i nierówności liniowe
    * 10.2. Nierówności liniowe
    * 10.3. Programowanie liniowe
    * 10.4. Algorytm sympleks
11. Optymalizacja
    * 11.0. Wstęp
    * 11.1. Przypadek jednej zmiennej
    * 11.2. Metody spadku
    * 11.3. Analiza funkcji kwadratowych celu
    * 11.4. Algorytmy aproksymacji kwadratowej
    * 11.5. Algorytm Neldera-Meada
    * 11.6. Wyżarzanie symulowane
    * 11.7. Algorytmy genetyczne
    * 11.8. Programowanie wypukłe
    * 11.9. Minimalizacja z warunkami
    * 11.10. Optymalizacja Pareto

### Metody numeryczne - Fortuna Zenon, Macukow Bohdan, Wąsowski Janusz
Książka ta jest nawet popularniejsza od Analizy numerycznej Kincaida i Cheney'a. Jej pierwsze wydanie ukazało się w roku 1982. W roku 1993 wydana po raz drugi, gdzie poprawiono zauważone błędy i nieścisłości. Później wznawiano wydanie pięciokrotnie jednak już bez dokonywania poprawek, a można się w niej doszukać kilka błędów, np. w rozwiązaniach zadań. Tak czy inaczej samo to, że książka była wydawana wielokrotnie świadczy o tym, że cieszy się ona uznaniem wśród znawców tematyki metod numerycznych. Wykładowcy często umieszczają ją w bibliografii przedmiotowej. Oprócz dokładnego wytłumaczenia zagadnień w książce można znaleźć przykłady, zadania i odpowiedzi do niektórych zadań. Zamiast pseudokodu mamy tutaj fragmenty kodu w języku Pascal, co może być lekkim utrudnieniem zważywszy na fakt, że w obecnych czasach język ten jest rzadko używany, nawet na niewielu polskich uczelniach jest nauczany i to tych mniej uznanych, żeby nie powiedzieć słabych. Oprócz tego można też spotkać schematy blokowe algorytmów.

#### Opis wydawcy
W podręczniku podano wybrane metody stosowane przy obliczeniach komputerowych. Omówiono tu niektóre z ważniejszych metod interpolacyjnych i aproksymacyjnych, całkowanie numeryczne, metody rozwiązywania układów algebraicznych równań liniowych oraz równań różniczkowych. Zamieszczono wiele algorytmów obliczeniowych wraz z oceną ich efektywności. Materiał teoretyczny jest ilustrowany licznymi przykładami rachunkowymi, przykładami programów w językach Fortran i Pascal i ich schematów blokowych. Podręcznik jest przeznaczony dla studentów kierunków: elektronika, informatyka i telekomunikacja. Mogą z niego także korzystać studenci i inżynierowie innych specjalności.

#### Przedmowa autorów
Celem autorów niniejszej książki jest wprowadzenie Czytelnika w dział matematyki stosowanej, zwanej metodami numerycznymi. Gwałtowny rozwój techniki obliczeniowej spowodował pojawienie się istnej lawiny metod, umożliwiających rozwiązywanie różnorodnych problemów z dziedziny techniki, medycyny, ekonomii itp. przy użyciu komputerów. Należy zdawać sobie sprawę z tego, że w zasadzie każde bardziej złożone zagadnienie wymaga opracowania indywidualnej metody jego rozwiązywania na komputerze. Niekiedy jednak różnica użytej metody w stosunku do metody standardowej polega na drobnych pozornie zmianach, takich jak nietypowe operowanie pamięcią operacyjną, zastosowanie przy pewnych pomocniczych obliczeniach podwójnej precyzji, zastosowanie innych testów zatrzymań. Zmiany takie mogą przesądzić na przykład o możliwości rozwiązania danego zagadnienia za pomocą aktualnie dostępnego komputera. Bywają jednak zagadnienia, do których rozwiązania należy opracować istotnie nową metodę. Powyższe względy powodują, iż stosowanie metod numerycznych jest po trosze sztuką, wymagającą dużej wprawy. Autorzy tej książki postawili sobie za cel przedstawienie wybranych działów metod numerycznych w ten sposób, by z jednej strony umożliwić Czytelnikowi rozwiązywanie typowych zagadnień — rozwiązywanie równań różniczkowych, całkowanie, rozwiązywanie układów równań algebraicznych — z drugiej zaś strony przez dokładniejsze omówienie działu algebry liniowej umożliwić samodzielne opracowywanie bardziej wyspecjalizowanych metod. Zakładamy, że Czytelnik jest obeznany z podstawowymi działami matematyki, jak algebra, teoria funkcji, rachunek różniczkowy i całkowy. Ponadto do właściwego zrozumienia istoty większości algorytmów niezbędna jest umiejętność programowania wjęzyku Pascal (lub Fortran). W obecnym, drugim wydaniu, postaraliśmy się usunąć wszystkie dostrzeżone lub zasygnalizowane przez Czytelników błędy i niedokładności. Ponieważ od pierwszego wydania minęło ponad 10 lat, a w okresie tym nastąpiła prawdziwa rewolucja w sprzęcie komputerowym oraz dostępnym oprogramowaniu, w obecnym wydaniu większość przykładowych programów została przerobiona na język Pascal. W okresie tym ukazało się także na rynku wydawniczym kilka nowych, cennych pozycji mających charakter podręczników akademickich i książki te zamieściliśmy jako dodatkowe pozycje literatury.

#### Spis treści
0. Wstępne uwagi o obliczeniach numerycznych
    * 0.1. Własności zapisu zmiennopozycyjnego
    * 0.2. Błędy obliczeń
    * 0.3. Oszacowania błędów zaokrągleń
    * 0.4. Uwarunkowanie zadania i stabilność algorytmów
1. Interpolacja
    * 1.1. Sformułowanie zagadnienia interpolacji
    * 1.2. Interpolacja za pomocą wielomianów
        * 1.2.1. Wzór interpolacyjny Lagrange’a
        * 1.2.2. Oszacowanie błędu wzoru interpolacyjnego
        * 1.2.3. Problem optymalnego doboru węzłów interpolacji
        * 1.2.4. Wzór interpolacyjny Newtona dla nierównych odstępów argumentu
        * 1.2.5. Różnice progresywne i różnice wsteczne
        * 1.2.6. Wzory interpolacyjne Newtona dla równoodległych wartości argumentu
        * 1.2.7. Zbieżność procesów interpolacyjnych
        * 1.2.8. Uwagi końcowe
    * 1.3. Interpolacja za pomocą funkcji sklejanych
        * 1.3.1. Określenie funkcji sklejanych
        * 1.3.2. Interpolacyjne funkcje sklejane stopnia trzeciego
2. Aproksymacja
    * 2.1. Wstęp
    * 2.2. Aproksymacja średniokwadratowa
        * 2.2.1. Aproksymacja wielomianowa
        * 2.2.2. Aproksymacja za pomocą wielomianów ortogonalnych
        * 2.2.3. Aproksymacja trygonometryczna
        * 2.2.4. Szybka transformacja Fouriera
        * 2.2.5. Aproksymacja za pomocą funkcji sklejanych
    * 2.3. Aproksymacja jednostajna
        * 2.3.1. Metoda szeregów potęgowych
        * 2.3.2. Przybliżenia Padego
        * 2.3.3. Szeregi Czebyszewa
    * 2.4. Uwagi końcowe
3. Przybliżone rozwiązywanie równań nieliniowych i ich układów
    * 3.1. Jedno równanie z jedną niewiadomą
        * 3.1.1. Metoda połowienia
        * 3.1.2. Reguła falsi i metoda siecznych
        * 3.1.3. Metoda Newtona. Metody zmodyfikowane dla pierwiastków wielokrotnych
    * 3.2. Metody poszukiwania zer wielomianów
        * 3.2.1. Liczba pierwiastków rzeczywistych
        * 3.2.2. Lokalizacja zer rzeczywistych
        * 3.2.3. Metody przybliżonego obliczania zer rzeczywistych wielomianu
        * 3.2.4. Lokalizacja zer zespolonych
        * 3.2.5. Metody przybliżonego obliczania zer zespolonych wielomian
    * 3.3. Uwagi o efektywności metod przybliżonego obliczania pierwiastków
    * 3.4. Układy równań nieliniowych
        * 3.4.1. Ogólne metody iteracyjne
        * 3.4.2. Metoda Newtona
        * 3.4.3. Metoda siecznych
    * 3.5. Poszukiwanie minimów funkcji jednej zmiennej
        * 3.5.1. Metody podziału
        * 3.5.2. Metoda optymalnych podziałów
        * 3.5.3. Metoda złotego podziału
4. Całkowanie numeryczne
    * 4.1. Wstęp
        * 4.1.1. Uwagi ogólne o całkowaniu numerycznym
        * 4.1.2. Ogólny wzór całkowania numerycznego
    * 4.2. Kwadratury z ustalonymi węzłami
        * 4.2.1. Kwadratury Newtona-Cotesa
        * 4.2.2. Kwadratury złożone Newtona-Cotesa
        * 4.2.3. Metoda Romberga
    * 4.3. Kwadratury Gaussa i kwadratury złożone Gaussa
        * 4.3.1. Kwadratury Gaussa
        * 4.3.2. Kwadratury złożone Gaussa
    * 4.4. Uwagi końcowe
5. Rozwiązywanie układów algebraicznych równań liniowych
    * 5.1. Wstęp
    * 5.2. Pojęcia podstawowe
    * 5.3. Metody dokładne
        * 5.3.1. Analiza błędów rozwiązywania
        * 5.3.2. Układy równań z macierzą trójkątną
        * 5.3.3. Metoda eliminacji Gaussa
        * 5.3.4. Metoda eliminacji Jordana
        * 5.3.5. Układy z macierzą symetryczną. Rozkłady LDLT i LLT
        * 5.3.6. Układy z macierzą trójdiagonalną
        * 5.3.7. Układy równań z macierzą zbliżoną do trójdiagonalnej
        * 5.3.8. Obliczanie wyznacznika i odwracanie macierzy
        * 5.3.9. Iteracyjne poprawianie rozwiązania
    * 5.4. Metody iteracyjne
        * 5.4.1. Metoda Jacobiego
        * 5.4.2. Metoda Gaussa-Seidla
        * 5.4.3. Metoda Czebyszewa
        * 5.4.4. Nakład obliczeń i testy stopu
    * 5.5. Układy równań z macierzami rzadkimi
        * 5.5.1. Organizacja pamięci
        * 5.5.2. Metody dokładne dla układów z macierzami rzadkimi
        * 5.5.3. Metody iteracyjne
        * 5.5.4. Metody blokowe
6. Obliczanie wartości własnych i wektorów własnych macierzy
    * 6.1. Wstęp
    * 6.2. Pojęcia podstawowe
    * 6.3. Zaburzenia wartości i wektorów własnych
    * 6.4. Macierze o elementach rzeczywistych — metody ogólne
        * 6.4.1. Lokalizacja wartości własnych
        * 6.4.2. Znajdowanie wartości własnych przy użyciu wielomianu charakterystycznego
        * 6.4.3. Metoda potęgowa
        * 6.4.4. Algorytm QR dla macierzy Hessenberga
        * 6.4.5. Sprowadzanie macierzy do postaci Hessenberga
        * 6.4.6. Obliczanie wektorów własnych
        * 6.4.7. Algorytm rozkładu macierzy na iloczyn QR
    * 6.5. Macierze symetryczne
        * 6.5.1. Macierz trójdiagonalna symetryczna
        * 6.5.2. Sprowadzanie macierzy symetrycznej do postaci trójdiagonalnej
    * 6.6. Macierze wstęgowe
7. Metody rozwiązywania zagadnień początkowych dla równań różniczkowych zwyczajnych
    * 7.1. Wstęp
    * 7.2. Metoda Eulera
    * 7.3. Metody różnicowe
        * 7.3.1. Ogólny wzór różnicowy
        * 7.3.2. Równanie dla błędu
        * 7.3.3. Stabilność i zbieżność
        * 7.3.4. Wyznaczanie praktyczne przydatnych wzorów różnicowych
    * 7.4. Metody typu Rungego-Kutty
        * 7.4.1. Wzór ogólny
        * 7.4.2. Stabilność metod Rungego-Kutty
        * 7.4.3. Metody rzędu czwartego
        * 7.4.4. Wybór kroku całkowania
    * 7.5. Metody ekstrapolacyjno-interpolacyjne
        * 7.5.1. Metody Hamminga
        * 7.5.2. Metoda Geara dla układów typu stiff
8.  Metody rozwiązywania zagadnień brzegowych dla równań różniczkowych cząstkowych
    * 8.1. Metoda różnicowa dla równania przewodnictwa cieplnego
        * 8.1.1. Postawienie zagadnienia
        * 8.1.2. Aproksymacja różnicowa
        * 8.1.3. Stabilność i zbieżność
        * 8.1.4. Przykład obliczeniowy
        * 8.1.5. Schemat blokowy
    * 8.2. Metoda różnicowa dla równania drgań struny
        * 8.2.1. Postawienie zagadnienia
        * 8.2.2. Aproksymacja różnicowa
    * 8.3. Metoda różnicowa dla równania Poissona
        * 8.3.1. Postawienie zagadnienia
        * 8.3.2. Aproksymacje różnicowe równania Poissona
        * 8.3.3. Aproksymacja różnicowa zagadnienia Dirichleta
        * 8.3.4. Jednostajna zbieżność rozwiązania różnicowego
    * 8.4. Metoda prostych dla równania przewodnictwa cieplnego
    * 8.5. Metoda prostych dla równania drgań struny
9. Dodatek: Metoda elementu skończonego
    * D.1. Pojęcia wstępne
    * D.2. Metoda elementu skończonego

### Metody numeryczne - Bjorck Ake, Dahlquist Germund
Kolejny klasyk, z którego warto korzystać, choć wg mnie nie jest to pozycja tak przystępna jak dwie poprzednie, jednak znajdziemy tu objaśnienia zagadnień, których nie ma właśnie w dwóch poprzednio omawianych. Książka zawiera również omówienia przykładów, zadania i odpowiedzi do nich.

#### Opis wydawcy
Książka zawiera bardzo dobrze opracowany i wyłożony materiał z klasycznych dzialów metod numerycznych, a także metody optymalizacji, aproksymacji, symulację numeryczną, szybkie transformacje Fouriera, informacje o funkcjach sklejonych, metodę elementu skończonego i inne. Jest przeznaczona nie tylko dla matematyków, ale także dla inżynierów mających do czynienia z metodami numerycznymi w swej pracy.

#### Przedmowa autorów
Książka ta jest rozszerzonym i unowocześnionym przekładem podręcznika opublikowanego w języku szwedzkim przez wydawnictwo CWK Gleerup Co. w 1969 roku. Lektura książki wymaga na ogół tylko znajomości podstawowych działów matematyki (w tym analizy i algebry liniowej), a także problemowo zorientowanego języka programowania. Można się go uczyć studiując równocześnie trzy pierwsze rozdziały książki. Pewne jej fragmenty są trudniejsze. Spodziewamy się, że wykładowcy, korzystający z tego podręcznika, z łatwością wskażą słuchaczom konkretnego wykładu, jak głęboko mają wnikać w poszczególne części książki. Próbowaliśmy wybrać metody istotne w poważnych obliczeniach, a także techniki użyteczne w nieskomplikowanych rachunkach wykonywanych za pomocą prostych narzędzi. Byłoby dobrze, gdyby czytelnik, zaznajamiając się z pewnymi algorytmami, miał dostęp do systemu pracującego w podziale czasu, ale w większości przypadków wystarczy kalkulator kieszonkowy lub nawet suwak logarytmiczny i tablice matematyczne. Mamy nadzieję, że książka będzie użyteczna jako podręcznik metod numerycznych stosowanych w nauce i technice. Ostatni rozdział zawiera wyczerpującą bibliografię i listę opublikowanych algorytmów. Ogólne idee i pojęcia obliczeń naukowych wprowadzono w pierwszym rozdziale. Drugi rozdział jest poświęcony analizie błędów. Tu i wszędzie indziej próbujemy podkreślić te aspekty, które są ważne w projektowaniu algorytmów. W przeciwieństwie do przeglądowego stylu dwóch pierwszych rozdziałów reszta książki polega głównie na rozważaniu poszczególnych klas zagadnień. Najważniejszą różnicą między tą książką a jej szwedzkim wydaniem jest zwiększona liczba ćwiczeń.

#### Spis treści
1. Ogólne zasady obliczeń numerycznych
    * 1.1. Wstęp
    * 1.2. Ogólne idee i pojęcia w metodach numerycznych
    * 1.3. Zadania i algorytmy numeryczne
        * 1.3.1. Definicje
        * 1.3.2. Wzory rekurencyjne. Schemat Homera
        * 1.3.3. Przykład niestabilności numerycznej
2. Jak otrzymać i szacować dokładność w obliczeniach numerycznych?
    * 2.1. Podstawowe pojęcia w szacowaniu błędów
        * 2.1.1. Wstęp
        * 2.1.2. Źródła błędu
        * 2.1.3. Błędy bezwzględne i względne
        * 2.1.4. Zaokrąglanie i ucinanie
    * 2.2. Przenoszenie się błędów
        * 2.2.1. Proste przykłady analizy błędów
        * 2.2.2. Ogólny wzór dla przenoszenia się błędów. Błąd maksymalny i błąd standardowy
        * 2.2.3. Praktyczne zastosowania szacowania błędu
        * 2.2.4. Zastosowanie eksperymentalnych zaburzeń
        * 2.2.5. Automatyczna kontrola dokładności
    * 2.3. Układy pozycyjne. Reprezentacja stałopozycyjna i zmiennopozycyjna
        * 2.3.1. Układy pozycyjne
        * 2.3.2. Reprezentacja zmiennopozycyjna i stałopozycyjna
        * 2.3.3. Reprezentacja zmiennopozycyjna dziesiętna
        * 2.3.4. Reprezentacja stałopozycyjna dziesiętna
        * 2.3.5. Błędy zaokrągleń w obliczeniach zmiennopozycyjnych
    * 2.4. Analiza pozornych zaburzeń. Wskaźniki uwarunkowania
        * 2.4.1. Analiza pozornych zaburzeń
        * 2.4.2. Wskaźniki uwarunkowania dla zadań i algorytmów
        * 2.4.3. ilustracja geometryczna analizy błędu
3. Zastosowania numeryczne szeregów
    * 3.1. Elementarne zastosowania szeregów
        * 3.1.1. Proste przykłady
        * 3.1.2. Szacowanie reszty
        * 3.1.3. Szeregi potęgowe   
    * 3.2. Przyspieszanie zbieżności
        * 3.2.1. Wolno zbieżne szeregi przemienne
        * 3.2.2. Szeregi wolno zbieżne o dodatnich skladnikach
        * 3.2.3. Inne proste sposoby przyspieszania zbieżności
        * 3.2.4. Szeregi źle uwarunkowane
        * 3.2.5 Zastosowanie numeryczne szeregu rozbieżnego
4. Aproksymacja funkcji
    * 4.1. Podstawowe pojęcia aproksymacji
        * 4.1.1. Wstęp
        * 4.1.2. Pojęcie przestrzeni funkcyjnej
        * 4.1.3. Normy i seminormy
        * 4.1.4. Aproksymacja funkcji jako zagadnienie geometryczne w przestrzeni funkcji
    * 4.2. Aproksymacja średniokwadratowa funkcji
        * 4.2.1. Sformułowanie zadania
        * 4.2.2. Układy ortogonalne
        * 4.2.3. Rozwiązanie zadania aproksymacyjnego
    * 4.3. Wielomiany
        * 4.3.1. Podstawowa terminologia. Twierdzenie aproksymacyjne Weierstrassa
        * 4.3.2. Rodziny trójkątne wielomianów
        * 4.3.3. Pewna rodzina trójkątna i jej zastosowanie w interpolacji
        * 4.3.4. Węzły równoodległe i zjawisko Rungego
    * 4.4. Wielomiany ortogonalne i ich zastosowania
        * 4.4.1. Wielomiany Czebyszewa
        * 4.4.2. Interpolacja i wygładzanie z węzłami Czebyszewa
        * 4.4.3. Ogólna teoria wielomianów ortogonalnych
        * 4.4.4. Wielomiany Legendre'a i wielomiany Grama
    * 4.5. Uzupelniające wiadomości o aproksymacji wielomianowej
        * 4.5.1. Zastosowania wielomianów
        * 4.5.2. Nierówności dla En(f) i ich zastosowanie do obliczania funkcjonałów liniowych
        * 4.5.3. Aproksymacja jednostajna
        * 4.5.4. Zwijanie szeregów potęgowych. Funkcje standardowe
        * 4.5.5. Pewne aspekty statystyczne aproksymacji średniokwadratowej
    * 4.6. Funkcje sklejane
5. Metody numeryczne algebry liniowej
    * 5.1. Wstęp
    * 5.2. Podstawowe pojęcia algebry liniowej
        * 5.2.1. Główne definicje
        * 5.2.2. Macierze blokowe
        * 5.2.3. Przestrzenie liniowe wektorowe
        * 5.2.4. Wartości własne i przekształcanie przez podobieństwo
        * 5.2.5. Rozkład według wartości osobliwych. Pseudoodwrotność
    * 5.3. Metody bezpośrednie rozwiązywania układów równan liniowych
        * 5.3.1. Układy trójkątne
        * 5.3.2. Eliminacja Gaussa
        * 5.3.3. Strategie wyboru elementów głównych
        * 5.3.4. Rozkład trójkątny
        * 5.3.5. Schematy zwarte eliminacji Gaussa
        * 5.3.6. Macierze odwrotne
    * 5.4. Specjalne macierze
        * 5.4.1. Macierze symetryczne dodatnio określone
        * 5.4.2. Macierze wstęgowe
        * 5.4.3. Wielkie układy liniowe
        * 5.4.4. Inne macierze rzadkie
    * 5.5. Analiza błędów dla układów liniowych
        * 5.5.1. Przykład złego uwarunkowania
        * 5.5.2. Normy wektorów i macierzy
        * 5.5.3. Analiza zaburzeń
        * 5.5.4. Błędy zaokrąglenia w eliminacji Gaussa
        * 5.5.5. Skalowanie układów liniowych
        * 3.5.6. Ulepszanie iteracyjne rozwiązania
    * 5.6. Metody iteracyjne
    * 5.7. Układy liniowe nadokreślone
        * 5.7.1. Równania normalne
        * 5.7.2. Metody ortogonalizacji
        * 5.7.3. Ulepszanie rozwiązań średniokwadratowych
        * 5.7.4. Zadania sredniokwadratowe z ograniczeniami liniowymi
    * 5.8. Obliczanie wartości własnych i wektorów własnych
        * 5.8.1. Metoda potęgowa
        * 5.8.2. Metody oparte na przekształceniach przez podobieństwo
        * 5.8.3. Obliczanie wartości własnych z równania charakterystycznego
        * 5.8.4. Algorytm QR
6. Równania nieliniowe
    * 6.1. Wstęp
    * 6.2. Przybliżenia początkowe. Metody stanu
        * 6.2.1. Wstęp
        * 6.2.2. Metoda bisekcji
    * 6.3. Metoda Newtona
    * 6.4. Metoda siecznych
        * 6.4.1. Opis metody
        * 6.4.2. Analiza błędów dla metody siecznych
        * 6.4.3. Regula falsi
        * 6.4.4. Inne podobne metody
    * 6.5. Ogólna teoria metod iteracyjnych
    * 6.6. Szacowanie błędu i osiągalna dokładność w metodach iteracyjnych
        * 6.6.1. Szacowanie błędu
        * 6.6.2. Osiągalna dokladność. Kryteria zakończenia
    * 6.7. Pierwiastki wielokrotne
    * 6.8. Równania algebraiczne
        * 6.8.1. Wstęp
        * 6.8.2. Deflacja
        * 6.8.3. Źle uwarunkowane równania algebraiczne
    * 6.9. Układy równań nieliniowych
        * 6.9.1. Iteracje
        * 6.9.2. Metoda Newtona i jej modyfikacje
        * 6.9.3. Inne metody
7. Różnice skończone w całkowania i różniczkowaniu numerycznym oraz interpolacji
    * 7.1. Operatory różnicowe i ich najprostsze własności
    * 7.2. Proste metody konstrukcji wzorów przybliżonych i oszacowań błędu
        * 7.2.1. Sformułowanie zadań i typowe przykłady
        * 7.2.2. Ekstrapolacja iterowana Richardsona
    * 7.3. Interpolacja
        * 7.3.1. Wstęp
        * 7.3.2. Kiedy interpolacja liniowa jest wystarczająca?
        * 7.3.3. Wzór interpolacyjny Newtona
        * 7.3.4. Wzory dla interpolacji z węzłami rownoodległymi
        * 7.3.5. Dodatkowe uwagi o interpolacji
        * 7.3.6. Wzór interpolacyjny Lagrange'a
        * 7.3.7. Interpolacja Hermite'a
        * 7.3.8. Interpolacja odwrotna
    * 7.4. Całkowanie numeryczne
        * 7.4.1. Wzór prostokątów, wzór trapezów i metoda Romberga
        * 7.4.2. Błąd obcięcia dla wzoru trapezów
        * 7.4.3. Pewne trudności i możliwości w całkowaniu numerycznym
        * 7.4.4. Wzór sumacyjny Eulera-Maclaurina
        * 7.4.5. Zastosowania wzoru Eulera-Maclaurina
        * 7.4.6. Inne metody całkowania numerycznego
    * 7.5. Różniczkowanie numeryczne
    * 7.6. Rachunek operatorów
        * 7.6.1. Algebra operatorów
        * 7.6.2. Szeregi operatorowe i ich zastosowania
    * 7.7. Funkcje wielu zmiennych
        * 7.7.1. Całki iterowane
        * 7.7.2. Siatki prostokątne
        * 7.7.3. Nieregularne siatki trójkątne
8. Równania różniczkowe
    * 8.1. Podstawy teoretyczne
        * 8.1.1. Zagadnienia początkowe dla równań różniczkowych zwyczajnych
        * 8.1.2. Przenoszenie się błędów
        * 8.1.3. Inne zagadnienia różniczkowe
    * 8.2. Metoda Eulera z ekstrapolacją iterowaną Richardsona
    * 8.3. Inne metody rozwiązywania zagadnień początkowych dla równań różniczkowych zwyczajnych
        * 8.3.1. Zmodyfikowana metoda punktu środkowego
        * 8.3.2. Metoda szeregów potęgowych
        * 8.3.3. Metody Rungego-Kutty
        * 8.3.4. Metody niejawne
        * 8.3.5. Zadania sztywne
        * 8.3.6. Sterowanie długością kroku
        * 8.3.7. Metoda różnicowa dla równania rzędu drugiego
    * 8.4. Szkic metod rozwiązywania zagadnień brzegowych i własnych dla równań różniczkowych zwyczajnych
        * 8.4.1. Wstęp
        * 8.4.2. Metoda strzałów
        * 8.4.3. Metoda macierzy wstęgowej
        * 8.4.4. Przykład numeryczny zagadnienia własnego
    * 8.5. Równania różnicowe
        * 8.5.1. Liniowe jednorodne równania różnicowe o stałych współczynnikach
        * 8.5.2. Dowolne liniowe równania różnicowe
        * 8.5.3. Badanie metody numerycznej za pomocą zadania testowego
        * 8.5.4. Liniowe metody wielokrokowe
    * 8.6. Równania różniczkowe cząstkowe
        * 8.6.1. Wstęp
        * 8.6.2. Przykład zagadnienia początkowego
        * 8.6.3. Przykład zagadnienia brzegowego
        * 8.6.4. Metody współczynników nieoznaczonych i metody wariacyjne
        * 8.6.5. Metoda elementu skończonego
        * 8.6.6. Równania całkowe
9. Metody Fouriera
    * 9.1. Wstęp
    * 9.2. Podstawowe wzory i twierdzenia analizy Fouriera
        * 9.2.1. Funkcje jednej zmiennej
        * 9.2.2. Funkcje wielu zmiennych
    * 9.3. Szybka analiza Fouriera
        * 9.3.1. Ważny przypadek szczególny
        * 9.3.2. Przypadek ogólny
    * 9.4. Przedłużanie okresowe funkcji nieokresowej
    * 9.5. Twierdzenie całkowe Fouriera
10. Optymalizacja
    * 10.1. Sformułowanie zadania, definicje i postać normalna
    * 10.2. Metoda sympleks
    * 10.3. Dualność
    * 10.4. Zadanie transportowe i niektóre inne zadania antyrealizacyjne
    * 10.5. Nieliniowe zadania optymalizacji
        * 10.5.1. Podstawowe pojęcia i najprostsze przykłady
        * 10.5.2. Poszukiwanie wzdłuż prostej
        * 10.5.3. Algorytmy optymalizacji bezwarunkowej
        * 10.5.4. Nadokreślone układy nieliniowe
        * 10.5.5. Optymalizacja warunkowa
11. Metoda Monte Carlo i symulacja
    * 11.1. Wstęp
    * 11.2. Cyfry i liczby losowe
    * 11.3. Zastosowania. Redukcja wariancji
    * 11.4. Liczby pseudolosowe
12. Rozwiązania zadań
