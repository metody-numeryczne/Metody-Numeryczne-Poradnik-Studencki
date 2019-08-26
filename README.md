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
