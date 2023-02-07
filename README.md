<h1>TASK 1</h1>

<h2>Subtask 1</h2>
5/10

<h2>Subtask 3</h2>
Zdecydowałam się na udział w portfolio challenge, bo nie jestem całkowicie zadowolona ze swojej obecnej pracy i dalej szukam potenjalnego zawodu, który da mi jednocześnie dobre pieniądze i przyjemność czy satysfakcję. Skończyłam studia związane z IT, ale nigdy nie wiedziałam, w którą stronę iść. Ostatnio stwierdziłam, że może QA, bo lubię zauważać szczegóły i poprawiać to, co ktoś zrobił źle.

<h2>Subtask 4</h2>
W testowanej aplikacji można przeglądać listę i informacji o zawodnikach piłki nożnej, a także dodawać nowych zawodników. Są to jedyne funkcjonalności, jakie znalazłam, ale design aplikacji jest dość nieuporządkowany, więc nie jestem pewna, czy można w niej zrobić coś jeszcze. Przede wszystkim położenie przycisku "dodaj gracza" jest bardzo nieintuicyjne, znajdje się właściwie na samym środku strony głównej, w czym nie widzę żadnej logiki.
Nagłówek "linki pomocnicze" też nie ma według mnie sensu - sugeruje, że jest to coś dodatkowego, podczas gdy jest to główna funkcjonalność aplikacji.
Oprócz tego w aplikacji nie ładuje się favicon - widoczny jest error 404.
Znaleźć też można błędy językowe - "gracze", "mecze", "raporty" i "akcje" są policzalne, więc powinno się z nimi używać słowa "liczba", nie "ilość".
Na plus doceniam dodatkowe funkcjonalności dotyczące listy graczy - można np. pobrać listę albo ją filtrować. Przy najeżdżaniu na ikony pokazują się jednak nazwy akcji w języku angielskim, podczas gdy cała aplikacja jest po polsku - potrzebne jest tłumaczenie. Podobnie z paskiem wyszukiwania - potrzebne tłumaczenie słowa "search" na polski.
<h4>Podczas dodawania gracza:</h4>
Potrzebny regex dla maila - można tam wpisać cokolwiek, niekoniecznie w formacie adresu mailowego.
To samo z numerem telefonu, który przyjmuje też litery.
Jako datę urodzenia można wybrać datę, która jeszcze się nie wydarzyła.
Wystąpił komunikat o błędzie o treści "nie udało się dodać gracza" - potrzebny bardziej konkretny komunikat, sprecyzowany powód błędu i co trzeba poprawić.

<h1>TASK 2</h1>

<h2>Subtask 1&2</h2>

<https://drive.google.com/drive/folders/1pG9n1V_DkdCyHkMc7IYygyLAZD64oENQ?usp=sharing>

<h2>Subtask 3</h2>

The test cases are important for multiple reasons:
1. When we compare the test cases with the app requirements, we know which requierments have been fulfilled and tested.
2. Thanks to the list of test cases, we know which modules have been tested, which are stable, which need to be reworked, etc., and can assess the app's progress.
3. Test cases makes the testing process more efficient, because the tester knows, which scenarios have been already covered.
4. Test cases make it possible to smoothly come back to the testing process after a longer break or to reassign testing to another tester.

<h1>TASK 4</h1>

<h2>Subtask 1&2</h2>

<https://docs.google.com/spreadsheets/d/1UyO8hYkqh6QDBM8RKKbpH6hGcqsFG8iG1OpZLDm3UcU/edit?usp=sharing>

<h2>Subtask 3</h2>

1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?

Aplikacja OLX.pl służy przede wszystkim do publikowania i korzystania z ogłoszeń sprzedażowych. Użytkownik może kupić różnego rodzaju produkty, które inni użytkownicy chcą sprzedać. W aplikacji można też przeglądać i publikować oferty pracy. Dostępna jest również kategoria "Dla Ukrainy", gdzie potrzebujące osoby dotknięte wojną w Ukrainie mogą znaleźć darmowe oferty różnego rodzaju produktów oraz nieruchomości.
Niezalogowany użytkownik może przeglądać ogłoszenia. Zalogowany użytkownik również może przeglądać ogłoszenia, a oprócz tego może dodać ogłoszenia do obserwowanych, wysyłać wiadomości do autorów ogłoszeń oraz dodawać swoje ogłoszenia.

2. Kto ma być użytkownikiem końcowym aplikacji?

Użytkownikami aplikacji są osoby, które chcą sprzedać lub oddać posiadane produkty, a także osoby, które szukają produktów z drugiej ręki.
Kolejnymi grupami użytkowników są osoby, które oferują pracę i osoby, które szukają pracy.
Dodatkową grupą użytkowników są osoby, które chcą oddać przedmioty osobom dotkniętym wojną w Ukrainie, a także osoby dotknięte wojną w Ukrainie, które potrzebują tego typu pomocy materialnej.

3. Czy według Ciebie aplikacja jest user-friendly?

Aplikacja jest umiarkowanie user-friendly - pojawiają się mniejsze błędy w zakresie UX, na przykład błędy językowe w miejscach, które nie są kluczowe dla poprawnego funkcjonowania aplikacji. Najważniejsze elementy są przejrzyszte i zrozumiałe. W większości przypadków nie ma też potrzeby wykonywania nadmiarowych kliknięć.

4. Jak byś usprawniła aplikację? Co byś w niej poprawiła. Czy masz jakiś pomysł na dodatkową funkcjonalność?

Zmieniłabym nazwę strony "Szukaj" na "Główna", "Przeglądaj" lub coś innego o podobnym znaczeniu do angielskiego "Home" lub "Main". Powodem jest to, że na tej stronie wyświetlają się proponowane oferty, a oprócz tego użytkownik może oczekiwać, że stroną główną jest właśnie coś w rodzaju "Home" - poprawiłoby to więc UX. Strona "Szukaj" znajdowałaby obok głównej w dolnej nawigacji i zawierała przede wszystkm dostępne kategorie produktów oraz pasek wyszukiwania. Oprócz tego poprawiłabym wspomniane błędy językowe i inne bugi związane designem interfejsu użytkownika. Dodatkową funkcjonalnością mogłaby być zmiana języka aplikacji na ukraiński (ponieważ fragmenty aplikacji są przeznaczone właśnie dla osób z Ukrainy), a także na angielski (język, który najprawdopodobniej zna duża część osób, które nie mówią po polsku, a miałyby powód, żeby korzystać z polskiej aplikacji).

5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?

Aplikacja natywna jest bardziej "zamknięta", w tym sensie, że najważniejsze funkcjonalności powinny być dostępne bez przechodzenia z aplikacji do przeglądarki i całej reszty internetu. Podczas testowania aplikacji natywnej warto więc zwrócić na to uwagę. W aplikacji internetowej, która otwiera się w przeglądarce, linki do podstron i stron zewnętrznych nie są tak problematyczne, ponieważ użytkownik wciąż znajduje się w jednej "aplikacji", którą jest przeglądarka internetowa.
