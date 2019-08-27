# Metody Numeryczne - Rozwiązania zadań
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
0.1. Własności zapisu zmiennopozycyjnego
0.2. Błędy obliczeń
0.3. Oszacowania błędów zaokrągleń
0.4. Uwarunkowanie zadania i stabilność algorytmów
1. Interpolacja
1.1. Sformułowanie zagadnienia interpolacji
1.2. Interpolacja za pomocą wielomianów
1.2.1. Wzór interpolacyjny Lagranjge’a
1.2.2. Oszacowanie błędu wzoru interpolacyjnego
1.2.3. Problem optymalnego doboru węzłów interpolacji
1.2.4. Wzór interpolacyjny Newtona dla nierównych odstępów argumentu
1.2.5. Różnice progresywne i różnice wsteczne
1.2.6. Wzory interpolacyjne Newtona dla równoodległych wartości argumentu
1.2.7. Zbieżność procesów interpolacyjnych
1.2.8. Uwagi końcowe
1.3. Interpolacja za pomocą funkcji sklejanych
1.3.1. Określenie funkcji sklejanych
1.3.2. Interpolacyjne funkcje sklejane stopnia trzeciego
2. Aproksymacja
2.1. Wstęp
2.2. Aproksymacja średniokwadratowa
2.2.1. Aproksymacja wielomianowa
2.2.2. Aproksymacja za pomocą wielomianów ortogonalnych
2.2.3. Aproksymacja trygonometryczna
2.2.4. Szybka transformacja Fouriera
2.2.5. Aproksymacja za pomocą funkcji sklejanych
2.3. Aproksymacja jednostajna
2.3.1. Metoda szeregów potęgowych
2.3.2. Przybliżenia Padego
2.3.3. Szeregi Czebyszewa
2.4. Uwagi końcowe
3. Przybliżone rozwiązywanie równań nieliniowych i ich układów
3.1. Jedno równanie z jedną niewiadomą
3.1.1. Metoda połowienia
3.1.2. Reguła falsi i metoda siecznych
3.1.3. Metoda Newtona. Metody zmodyfikowane dla pierwiastków wielokrotnych
3.2. Metody poszukiwania zer wielomianów
3.2.1. Liczba pierwiastków rzeczywistych
3.2.2. Lokalizacja zer rzeczywistych
3.2.3. Metody przybliżonego obliczania zer rzeczywistych wielomianu
3.2.4. Lokalizacja zer zespolonych
3.2.5. Metody przybliżonego obliczania zer zespolonych wielomian
3.3. Uwagi o efektywności metod przybliżonego obliczania pierwiastków
3.4. Układy równań nieliniowych
3.4.1. Ogólne metody iteracyjne
3.4.2. Metoda Newtona
3.4.3. Metoda siecznych
3.5. Poszukiwanie minimów funkcji jednej zmiennej
3.5.1. Metody podziału
3.5.2. Metoda optymalnych podziałów
3.5.3. Metoda złotego podziału
4. Całkowanie numeryczne
4.1. Wstęp
4.1.1. Uwagi ogólne o całkowaniu numerycznym
4.1.2. Ogólny wzór całkowania numerycznego
4.2. Kwadratury z ustalonymi węzłami
4.2.1. Kwadratury Newtona-Cotesa
4.2.2. Kwadratury złożone Newtona-Cotesa
4.2.3. Metoda Romberga
4.3. Kwadratury Gaussa i kwadratury złożone Gaussa
4.3.1. Kwadratury Gaussa
4.3.2. Kwadratury złożone Gaussa
4.4. Uwagi końcowe
5. Rozwiązywanie układów algebraicznych równań liniowych
5.1. Wstęp
5.2. Pojęcia podstawowe
5.3. Metody dokładne
5.3.1. Analiza błędów rozwiązywania
5.3.2. Układy równań z macierzą trójkątną
5.3.3. Metoda eliminacji Gaussa
5.3.4. Metoda eliminacji Jordana
5.3.5. Układy z macierzą symetryczną. Rozkłady LDLT i LLT
5.3.6. Układy z macierzą trójdiagonalną
5.3.7. Układy równań z macierzą zbliżoną do trójdiagonalnej
5.3.8. Obliczanie wyznacznika i odwracanie macierzy
5.3.9. Iteracyjne poprawianie rozwiązania
5.4. Metody iteracyjne
5.4.1. Metoda Jacobiego
5.4.2. Metoda Gaussa-Seidla
5.4.3. Metoda Czebyszewa
5.4.4. Nakład obliczeń i testy stopu
5.5. Układy równań z macierzami rzadkimi
5.5.1. Organizacja pamięci
5.5.2. Metody dokładne dla układów z macierzami rzadkimi
5.5.3. Metody iteracyjne
5.5.4. Metody blokowe
6. Obliczanie wartości własnych i wektorów własnych macierzy
6.1. Wstęp
6.2. Pojęcia podstawowe
6.3. Zaburzenia wartości i wektorów własnych
6.4. Macierze o elementach rzeczywistych — metody ogólne
6.4.1. Lokalizacja wartości własnych
6.4.2. Znajdowanie wartości własnych przy użyciu wielomianu charakterystycznego
6.4.3. Metoda potęgowa
6.4.4. Algorytm QR dla macierzy Hessenberga
6.4.5. Sprowadzanie macierzy do postaci Hessenberga
6.4.6. Obliczanie wektorów własnych
6.4.7. Algorytm rozkładu macierzy na iloczyn QR
6.5. Macierze symetryczne
6.5.1. Macierz trójdiagonalna symetryczna
6.5.2. Sprowadzanie macierzy symetrycznej do postaci trójdiagonalnej
6.6. Macierze wstęgowe
7. Metody rozwiązywania zagadnień początkowych dla równań różniczkowych zwyczajnych
7.1. Wstęp
7.2. Metoda Eulera
7.3. Metody różnicowe
7.3.1. Ogólny wzór różnicowy
7.3.2. Równanie dla błędu
7.3.3. Stabilność i zbieżność
7.3.4. Wyznaczanie praktyczne przydatnych wzorów różnicowych
7.4. Metody typu Rungego-Kutty
7.4.1. Wzór ogólny
7.4.2. Stabilność metod Rungego-Kutty
7.4.3. Metody rzędu czwartego
7.4.4. Wybór kroku całkowania
7.5. Metody ekstrapolacyjno-interpolacyjne
7.5.1. Metody Hamminga
7.5.2. Metoda Geara dla układów typu stiff
8.  Metody rozwiązywania zagadnień brzegowych dla równań różniczkowych cząstkowych
8.1. Metoda różnicowa dla równania przewodnictwa cieplnego
8.1.1. Postawienie zagadnienia
8.1.2. Aproksymacja różnicowa
8.1.3. Stabilność i zbieżność
8.1.4. Przykład obliczeniowy
8.1.5. Schemat blokowy
8.2. Metoda różnicowa dla równania drgań struny
8.2.1. Postawienie zagadnienia
8.2.2. Aproksymacja różnicowa
8.3. Metoda różnicowa dla równania Poissona
8.3.1. Postawienie zagadnienia
8.3.2. Aproksymacje różnicowe równania Poissona
8.3.3. Aproksymacja różnicowa zagadnienia Dirichleta
8.3.4. Jednostajna zbieżność rozwiązania różnicowego
8.4. Metoda prostych dla równania przewodnictwa cieplnego
8.5. Metoda prostych dla równania drgań struny
D. Metoda elementu skończonego
D.1. Pojęcia wstępne
D.2. Metoda elementu skończonego
