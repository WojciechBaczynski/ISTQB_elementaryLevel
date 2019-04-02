# Testowanie  poziom podstawowy ISTQB by Wojciech Baczyński

## 1.1 Dlaczego testowanie jest niezbędne?

##### 1.1.1 Kandydat potrafi opisać - podając przykłady - w jaki sposób usterka w oprogramowaniu może wyrządzić szkodę osobie, środowisku lub firmie.
> Oprogramowanie, które działa niepoprawnie może spowodować wiele problemów, stratę pieniędzy, czasu lub utratę reputacji biznesowej. Może nawet spowodować utratę zdrowia lub życia.

##### 1.1.2 Kandydat rozróżnia przyczynę usterki od jej skutków.
> Przyczyna usterki to najczęścniej ludzki błąd, natomiast jej skutek to oprogramowanie działające nie tak jakbyśmy tego chcieli.

##### 1.1.3 Kandydat potrafi podać powody tego, że testowanie jest niezbędne opierając się na przykładach.  
> Rygorystyczne testy systemów i dokumentacji mogą pomóc w zmniejszeniu ryzyka wystąpienia problemów podczas użytkowania oprogramowania i przyczynić się do podniesienia jakości sytemu, jeżeli znalezione usterki zostaną poprawione przed wdrożeniem systemu do użytkowania.

##### 1.1.4 Kandydat potrafi uzasadnić, że testowanie stanowi część zapewnienia jakości i podać przykłady tego, w jaki sposób testowanie przyczynia się do zwiększenia jakości. 
> Za pomocą testów można zmierzyć jakość oprogramowania wyrażoną przez ilość znalezionych usterek zarówno dla funkcjonalnych jak i niefunkcjonalnych wymagań i atrybutów oprogramowania. Testowanie może budować zaufanie do jakości oprogramowania, jeżeli osoby testujące znajdują mało usterek lub nie znajdują ich wcale.

##### 1.1.5 Kandydat potrafi wyjaśnić i porównać pojęcia pomyłka, usterka, awaria oraz odpowiadające im pojęcia błąd i pluskwa, podając przykłady. 
> Człowiek może popełnić błąd (pomyłkę), która powoduje powstanie defektu (usterki, pluskwy) w kodzie programu lub dokumencie. Jeżeli kod zawierający defekt zostaje wykonany, system nie zrobi tego co powinien (lub wykona to czego nie powinien) powodując awarię. Usterki w oprogramowaniu, systemach lub dokumentach mogą prowadzić do wystąpienia awarii, ale nie wszystkie usterki powodują awarie. 

## 1.2 Co to jest testowanie?

##### 1.2.1 Kandydat pamięta ogólne cele testowania. 
> Istnieją różne cele testowania:
> * znajdowanie usterek
> * nabieranie zaufania do poziomu jakości
> * dostarczanie informacji potrzebnych do podejmowania decyzji
> * zapobieganie defektom

##### 1.2.2 Kandydat potrafi podać przykłady celów testowania w różnych fazach cyklu życia oprogramowania.
> Różne punkty widzenia pozwalają na wzięcie pod uwagę w testach różnych celów. Na przykład w testowaniu wytwórczym (np. testowaniu modułowym, integracyjnym lub systemowym) głównym celem może być wywołanie tylu awarii, ile się da, żeby zidentyfikować i poprawić usterki występujące w oprogramowaniu. W testach akceptacyjnych głównym celem może być potwierdzenie, że system działa tak jak powinien oraz nabranie pewności, że spełnia wymagania. W niektórych przypadkach celem testowania może być ocena jakości oprogramowania (bez intencji naprawiania defektów), by dostarczyć interesariuszom informacji o ryzyku związanym z wydaniem systemu w danej chwili. Testowanie pielęgnacyjne często zawiera testy sprawdzające, czy nie wprowadzono nowych usterek podczas wykonywania zmian. Głównym celem testowania produkcyjnego może być ocena atrybutów systemu takich jak niezawodność lub dostępność.

##### 1.2.3 Kandydat rozróżnia testowanie od debagowania.
> Debagowanie różni się od testowania. Testowanie dynamiczne może pokazać awarie, których źródłem są usterki. Debagowanie jest czynnością programistyczną, która znajduje, analizuje i umożliwia usunięcie przyczyny awarii.

## 1.3 Siedem zasad testowania

##### 1.3.1 Kandydat potrafi wyjaśnić siedem zasad testowania. 
> 1. Testowania ujawnia usterki 
> 2. Testowanie gruntowne jest niewykonalne
> 3. Wczesne testowanie
> 4. Kumulowanie się błędów
> 5. Paradoks pestycydów - jeżeli te same testy są powtarzane bez zmian, to w końcu przestaną znajdować nowe usterki. Żeby przezwyciężyć "paradoks pestycydów", testy muszą być regularnie przeglądane i uaktualniane.
> 6. Testowanie zależy od kontekstu - testowanie wykonuje się w różny sposób w różnym kontekście. Na przykład oprogramowanie krytyczne ze względu na bezpieczeństwo testuje się inaczej niż sklep internetowy.
> 7. Mylne przekonanie o braku błędów - znajdowanie i naprawa usterek nie pomoże, jeżeli produkowany system nie nadaje się do użytkowania lub nie spełnia wymagań i oczekiwań użytkownika.

## 1.4 Podstawowy proces testowy

##### 1.4.1 Kandydat pamięta pięć podstawowych czynności testowych i odpowiadające im zadania od planowania do zamknięcia testów. 
> Podstawowy proces testowy składa się z następujących czynności:
> * planowanie i nadzór nad testami
Planowanie testów polega na zdefiniowaniu celów testowania i określeniu czynności testowych potrzebnych do wypełnienia misji i celów testowania.
> * analiza i projektowanie testów
Podczas analizy i projektowania testów ogólne cele testowania przekształcane są w konkretne warunki testowe i przypadki testowe. 
> * implementacja i wykonanie testów
Implementacja i wykonanie testów, to czynność, podczas której specyfikowane są procedury i skrypty testowe przez ustawienie przypadków testowych w konkretnej kolejności oraz dołączenie innych informacji potrzebnych do wykonania testów, konfigurowane jest środowisko testowe oraz wykonywane są testy.  
> * ocena kryteriów zakończenia i raportowanie 
Ocena spełnienia kryteriów zakończenia polega na ocenie wykonania testów zgodnie z przyjętymi celami testowania. Powinna ona być wykonywana dla każdego poziomu testowania.
> * czynności zamykające test 
W ramach czynności zamykających testy zbierane są dane z zakończonych czynności testowych, żeby utrwalić doświadczenie, testalia, fakty i liczby. Czynności zamykające testy wykonywane są przy kamieniach milowych projektu takich jak: wydanie systemu, zakończenie (lub anulowanie) projektu testowego, osiągnięcie kamienia milowego, lub zakończenie wydania serwisowego.

## 1.5	Psychologia testowania 
> Można uniknąć spięć pomiędzy testerami, a analitykami, projektantami i programistami
przez komunikowanie błędów, usterek i awarii w sposób konstruktywny. Ta zasada ma
zastosowanie zarówno do defektów znalezionych podczas przeglądów, jak i w testowaniu.
>
> Problemy z komunikacją mogą wystąpić jeżeli testerzy są postrzegani jedynie jako posłańcy
przynoszący niechciane informacje o usterkach. Istnieje kilka sposobów na poprawienie
komunikacji i relacji pomiędzy testerami i resztą zespołu:
> * zacznij od współpracy, a nie od wojny - przypomnij wszystkim, że celem jest
wyprodukowanie systemów o lepszej jakości
> * komunikuj informacje na temat produktu w sposób neutralny, skoncentrowany na
faktach bez krytykowania autora produktu, na przykład pisz obiektywne i konkretne
raporty incydentów oraz uwagi z przeglądów
> * spróbuj zrozumieć, co druga osoba czuje i dlaczego reaguje tak jak reaguje
> * upewnij się, że druga strona zrozumiała, co powiedziałeś i upewnij się, że rozumiesz
uwagi drugiej strony

##### 1.5.1 Kandydat pamięta czynniki psychologiczne, od których zależy sukces testowania.
> Można uniknąć spięć pomiędzy testerami, a analitykami, projektantami i programistami
przez komunikowanie błędów, usterek i awarii w sposób konstruktywny. Ta zasada ma
zastosowanie zarówno do defektów znalezionych podczas przeglądów, jak i w testowaniu.

##### 1.5.2 Kandydat potrafi pokazać różnice w nastawieniu testera i programisty.
> Sposób myślenia stosowany podczas testowania i przeglądania różni się od stosowanego
podczas rozwoju oprogramowania. Programiści posiadający odpowiednie nastawienie są w
stanie testować swój kod, ale zwykle odpowiedzialność za testowanie przekazuje się
testerom żeby wzmocnić koncentrację wysiłków oraz uzyskać dodatkowe korzyści, takie jak
niezależne spojrzenie wyszkolonych, zawodowych testerów. Testowanie niezależne może
być wykonywane na dowolnym poziomie testów.

## 2.1 Modele wytwarzania oprogramowania

##### 2.1.1 Kandydat potrafi wyjaśnić powiązania pomiędzy rozwojem oprogramowania, czynnościami testowymi oraz produktami w cyklu życia oprogramowania i podać przykłady na podstawie cech projektu i produktu oraz kontekstu.
> Cztery poziomy testowania to:
> * testy modułowe (jednostkowe)
> * testy integracyjne
> * testy systemowe
> * testy akceptacyjne
>
> Produkty związane z wytwarzaniem oprogramowania (takie jak scenariusze biznesowe lub
przypadki użycia, wymagania, projekt i kod źródłowy) są często podstawą do testowania na
jednym lub wielu poziomach.

##### 2.1.2 Kandydat akceptuje fakt, że modele wytwarzania oprogramowania muszą zostać zaadaptowane do cech projektu i produktu.
> Iteracyjno-przyrostowe wytwarzanie oprogramowania to proces zbierania wymagań,
projektowania, budowania oraz testowania systemu zorganizowany w krótsze cykle
rozwojowe. System wyprodukowany według takiego modelu może być przetestowany
na kilku poziomach w każdej iteracji.  Każdy przyrost
może podlegać zarówno weryfikacji jak i walidacji.

##### 2.1.3 Kandydat pamięta atrybuty dobrego testowania mające zastosowanie w każdym z modeli życia oprogramowania.
> W każdym modelu rozwoju oprogramowania dobre testowanie posiada kilka niezmiennych
cech:
> * dla każdej czynności związanej z wytworzeniem oprogramowania istnieją
odpowiadające jej czynności związane z testowaniem
> * każdy poziom testowania ma zdefiniowane cele
> * analiza i projektowanie testów dla danego poziomu powinny rozpoczynać się już
podczas odpowiadającej im fazy wytwarzania
> * testerzy powinni uczestniczyć w przeglądach już od wczesnych wersji dokumentacji
tworzonej podczas wytwarzania

## 2.2 Poziomy testów  

##### 2.2.1 Kandydat potrafi porównać różne poziomy testów: główne cele, typowe przedmioty testów, typowe cele testowania (np. strukturalne lub funkcjonalne) i związane z nimi produkty, testerów, typy usterek i awarii do znalezienia.

###### Testy modułowe
> Podstawa testów:
> * wymagania na moduły
> * projekt szczegółowy
> * kod
>
> Typowe obiekty testów:
> * moduły
> * programy
> * programy do konwersji lub migracji danych
> * moduły bazodanowe
>
> Testy modułowe polegają na wyszukiwaniu błędów i weryfikacji funkcjonalności
oprogramowania (np. modułów, programów, obiektów, klas), które można testować
oddzielnie. Może być wykonywane w izolacji od reszty systemu, w zależności od kontekstu
cyklu rozwoju oprogramowania i od samego systemu. Można podczas nich użyć zaślepek,
sterowników testowych oraz symulatorów.

###### Testy integracyjne
> Podstawa testów:
> * projekt oprogramowania i systemu
> * architektura
> * przepływy procesów
> * przypadki użycia 
>
> Typowe obiekty testów:
> * implementacja baz danych podsystemów
> * infrastruktura
> * interfejsy
> * konfiguracja systemu i dane konfiguracyjne
>
> Testy integracyjne sprawdzają interfejsy pomiędzy modułami, interakcje z innymi częściami
systemu (takimi jak system operacyjny, system plików i sprzęt) oraz interfejsy pomiędzy
systemami.

###### Testy systemowe
> Podstawa testów:
> * wymagania na system i oprogramowanie
> * przypadki użycia
> * specyfikacja funkcjonalna
> * raporty z analizy ryzyka
>
> Typowe obiekty testów:
> * podręczniki systemowe, użytkownika i operacyjne
> * konfiguracje systemu i dane konfiguracyjne
>
> Testy systemowe zajmują się zachowaniem systemu/produktu. Zakres testów powinien być
jasno określony w głównym planie testów oraz w planach testów poszczególnych poziomów.

###### Testy akceptacyjne
> Podstawa testów:
> * wymagania użytkownika
> * wymagania systemowe
> * przypadki użycia
> * procesy biznesowe
> * raporty z analizy ryzyka
>
> Typowe obiekty testów:
> * proces biznesowy na systemie w pełni zintegrowanym
> * procesy utrzymania i obsługi
> * procedury pracy użytkowników
> * formularze
> * raporty
> * dane konfiguracyjne
>
> Odpowiedzialność za testy akceptacyjne leży często po stronie klientów lub użytkowników
systemu. Mogą w nie być zaangażowani również inni interesariusze.

## 2.3 Typy testów  

##### 2.3.1 Kandydat potrafi porównać podając przykłady cztery typy testów (funkcjonalne, niefunkcjonalne, strukturalne oraz związane ze zmianami).

###### Testowanie funkcji (testowanie funkcjonalne)
> Funkcje, jakie ma pełnić system, podsystem lub moduł, mogą być opisane w produktach
takich jak specyfikacja wymagań, przypadki użycia lub specyfikacja funkcjonalna. Mogą też
być nieudokumentowane. Funkcje są tym "co" system robi.
>
> Testy funkcjonalne dotyczą funkcji lub innych cech(opisanych w dokumentach lub
domniemanych przez testerów) oraz ich współdziałania z innymi systemami. Można je
wykonywać na wszystkich poziomach (np. testy modułowe mogą bazować na specyfikacji
modułów).

###### Testowanie atrybutów niefunkcjonalnych (testowanie niefunkcjonalne)
> Testowanie niefunkcjonalne obejmuje następujące (ale nie tylko te) typy testów: testowanie
wydajnościowe, testowanie obciążeniowe, testowanie przeciążeniowe, testowanie
użyteczności, testowanie pielęgnowalności, testowanie niezawodności oraz testowanie
przenaszalności. Testowanie niefunkcjonalne polega na sprawdzeniu "jak" system działa.
>
> Testowanie niefunkcjonalne może być wykonywane na wszystkich poziomach testów.
Termin testy niefunkcjonalne oznacza testy wymagane do zmierzenia właściwości systemów
i oprogramowania, które mogą zostać określone ilościowo na zmiennej skali, takich jak czasy
odpowiedzi w testach wydajnościowych.

###### Testowanie struktury/architektury oprogramowania (testowanie strukturalne)
> Testy strukturalne (białoskrzynkowe) można wykonywać na każdym poziomie testowania.
Technik strukturalnych najlepiej użyć po technikach opartych na specyfikacji, po to by
zmierzyć dokładność testowania przez ocenę stopnia pokrycia wybranego typu struktury.
>
> Pokrycie, to stopień, w jakim struktura została przetestowana przez zestaw testów wyrażony
jako odsetek pokrytych elementów. Jeżeli pokrycie jest niższe niż 100%, można
zaprojektować więcej testów, żeby przetestować te elementy, które zostały pominięte, i w
ten sposób zwiększyć pokrycie.

###### Testowanie związane ze zmianami: testowanie potwierdzające oraz regresywne
> Po wykryciu i naprawieniu defektu, powinien zostać wykonany retest, żeby potwierdzić
usunięcie usterki. Takie testy nazywane są testami potwierdzającymi. Debagowanie
(lokalizacja oraz poprawianie usterek) jest czynnością programistyczną, a nie testową.
>
> Testowanie regresywne, to powtórzenie testów na już przetestowanym programie
wykonywane po modyfikacjach żeby wykryć nowe usterki lub usterki odsłonięte na skutek
wykonanych zmian. Usterki te mogą występować w testowanym oprogramowaniu, jak
również w innych powiązanych lub niepowiązanych modułach. Testy regresywne wykonuje
się po zmianach w oprogramowaniu, a także po zmianach w jego środowisku. Zakres testów
regresywnych wynika z ryzyka nieznalezienia usterek w oprogramowaniu, które poprzednio
działało poprawnie.

##### 2.3.2 Kandydat uznaje, że testy funkcjonalne i strukturalne występują na każdym poziomie testów.
> Testy funkcjonalne dotyczą funkcji lub innych cech(opisanych w dokumentach lub
domniemanych przez testerów) oraz ich współdziałania z innymi systemami. Można je
wykonywać na wszystkich poziomach (np. testy modułowe mogą bazować na specyfikacji
modułów). Testy strukturalne (białoskrzynkowe) można wykonywać na każdym poziomie testowania.
Technik strukturalnych najlepiej użyć po technikach opartych na specyfikacji, po to by
zmierzyć dokładność testowania przez ocenę stopnia pokrycia wybranego typu struktury.  

##### 2.3.3 Kandydat potrafi wymienić i opisać różne typy testów niefunkcjonalnych bazujących na wymaganiach niefunkcjonalnych.
> Termin testy niefunkcjonalne oznacza testy wymagane do zmierzenia właściwości systemów
i oprogramowania, które mogą zostać określone ilościowo na zmiennej skali, takich jak czasy
odpowiedzi w testach wydajnościowych. Testy te mogą zostać odniesione do modelu jakości
oprogramowania. Testy niefunkcjonalne zajmują się zewnętrznym zachowaniem oprogramowania i w większości wypadków wykorzystują techniki czarnoskrzynkowe.

##### 2.3.4 Kandydat potrafi wymienić i opisać typy testów bazujące na analizie struktury lub architektury systemu.
> Testy strukturalne (białoskrzynkowe) można wykonywać na każdym poziomie testowania.
Technik strukturalnych najlepiej użyć po technikach opartych na specyfikacji, po to by
zmierzyć dokładność testowania przez ocenę stopnia pokrycia wybranego typu struktury.
Pokrycie, to stopień, w jakim struktura została przetestowana przez zestaw testów wyrażony
jako odsetek pokrytych elementów. Jeżeli pokrycie jest niższe niż 100%, można
zaprojektować więcej testów, żeby przetestować te elementy, które zostały pominięte, i w
ten sposób zwiększyć pokrycie. Techniki oparte na pokryciu opisane są w rozdziale 4.
Do pomiaru pokrycia (na przykład decyzji lub instrukcji) na wszystkich poziomach, ale
szczególnie na poziomie testów modułowych i poziomie testów integracji modułów, mogą
zostać użyte narzędzia. Testowanie strukturalne może zostać oparte na architekturze
systemu, na przykład hierarchii wywołań.  

##### 2.3.5 Kandydat potrafi opisać cel wykonywania testów potwierdzających i regresywnych.
> Po wykryciu i naprawieniu defektu, powinien zostać wykonany retest, żeby potwierdzić
usunięcie usterki. Takie testy nazywane są testami potwierdzającymi. Debagowanie
(lokalizacja oraz poprawianie usterek) jest czynnością programistyczną, a nie testową.
Testowanie regresywne, to powtórzenie testów na już przetestowanym programie
wykonywane po modyfikacjach żeby wykryć nowe usterki lub usterki odsłonięte na skutek
wykonanych zmian. Usterki te mogą występować w testowanym oprogramowaniu, jak
również w innych powiązanych lub niepowiązanych modułach. Testy regresywne wykonuje
się po zmianach w oprogramowaniu, a także po zmianach w jego środowisku. Zakres testów
regresywnych wynika z ryzyka nieznalezienia usterek w oprogramowaniu, które poprzednio
działało poprawnie.
Testy, które mają być stosowane w testowaniu potwierdzającym i regresywnym muszą być
powtarzalne.

## 2.4 Testowanie pielęgnacyjne  

##### 2.4.1 Kandydat potrafi porównać testy pielęgnacyjne (testowanie istniejącego systemu) do testowania nowej aplikacji uwzględniając typy testów, powody rozpoczęcia testowania oraz ilość testów.
> Testy pielęgnacyjne, oprócz przetestowania tego co zostało zmienione, zawierają testy
regresywne tych części systemu, które się nie zmieniły. Zakres testów pielęgnacyjnych zależy
od ryzyka zmian, wielkości istniejącego systemu oraz zakresu zmian. W zależności od zmian,
testowanie pielęgnacyjne może być wykonane na niektórych lub wszystkich poziomach
testowania oraz dla wybranych lub wszystkich typów testów.

##### 2.4.2 Kandydat potrafi wymienić powody wykonywania testów pielęgnacyjnych (zmiany, migracja i wycofanie systemu).
> Wdrożony system często musi działać przez lata lub dekady. W tym czasie system, jego dane
konfiguracyjne i jego środowisko są często poprawianie, zmieniane i rozszerzane. Dla
dobrego testowania pielęgnacyjnego krytyczne jest planowanie wydań z wyprzedzeniem.
Konieczne jest rozróżnianie pomiędzy planowanymi wydaniami i szybkimi poprawkami.
Testowanie pielęgnacyjne wykonuje się na działającym systemie na skutek modyfikacji,
migracji lub złomowania oprogramowania lub systemu.
Modyfikacjami mogą być planowane ulepszenia (np. według planowych wydań), poprawki
lub naprawy awaryjne oraz zmiany środowiska, takie jak planowane podniesienia wersji
systemu operacyjnego, bazy danych lub oprogramowania z półki albo łaty zabezpieczeń
systemu operacyjnego.
Testy pielęgnacyjne migracji oprogramowania (np. z jednej platformy na inną) powinny,
oprócz testów zmian w oprogramowaniu, uwzględniać również testy produkcyjne nowego
środowiska. Testy migracji (testowanie konwersji) są również potrzebne, gdy dane z innej
aplikacji są migrowane do utrzymywanego systemu. 

##### 2.4.3 Kandydat potrafi opisać rolę testów regresywnych i analizy wpływu w utrzymaniu.
> Określenie, jaki wpływ na istniejący system mogą mieć zmiany, nazywamy analizą wpływu.
Stosuje się ją, aby ustalić zakres testów regresywnych. Analiza wpływu może zostać użyta do
wybrania zestawu testów regresyjnych.
Testowanie pielęgnacyjne może być trudne do wykonania, jeżeli specyfikacja
oprogramowania jest przestarzała lub gdy jej brak, lub gdy nie są dostępni testerzy
posiadający wiedzę dziedzinową.