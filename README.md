# IO-Lab
A project made for Software Engineering course. Half of the course was about UML, the other half about writing clean code and tests etc. 

### Historia użtkownika
Dwóch współwłaścicieli sieci aptek zostało zmuszonych zakończyć współpracę. Ze względu na burzliwy koniec wspólnej działalności, wszystkie dane dotyczące asortymentu i zależności występujących między sprzedawanymi lekami oraz wystawionych recept, a także zrealizowanych recept uległy zniszczeniu. Po ochłodzeniu emocji, jeden z nich zrozumiał, że został pozbawiony źródła utrzymania. Z ostatnich oszczędności postanowił wykupić pozostałe udziały w firmie i zacząć wszystko od początku. Baza będzie wykorzystywana do obsługi systemu aptecznego przez aptekarza. Zadaniem aptekarza ma być wydawanie leków i wykonywanie czynności z nim związanymi - realizowaniem recept, zmianą stanu zasobów apteki, zamawianiem leków, sprawdzaniem ich dostępności w innych aptekach. Klient obsługiwany przez aptekarza będzie mógł także sam uprzednio sprawdzać listę leków zamieszczoną w recepcie oraz dostępność poszukiwanych leków w aptece i stan zrealizowania recepty. Apteka będzie zaopatrywana przez dostawcę weryfikującego stan realizowanego zamówienia.

### Przypadki użycia

- sprawdzenie, czy przepisane leki nie kolidują ze sobą dla aktorów "lekarz" i "aptekarz"
- wyszukiwanie leków po nazwach handlowych, międzynarodowych i danej jednostce chorobowej dla aktora "aptekarz"
- wystawienie erecept dla aktora "lekarz"
- badanie stanu liczbowego poszczególnych leków dla aktora "aptekarz"
- dodawanie leków przy dostawie dla aktora "dostawca"
- dodawanie do listy zamówień z magazynu dla aktora "aptekarz"
- usuwanie już dostarczonych leków z listy zamówionych dla aktora "dostawca"
-  w przypadku braku dostępności leku sprawdzanie czy lek jest dostępny w innej aptece dla aktora "aptekarz"
- usuwanie sprzedanych leków z listy zasobów dla aktora "aptekarz"
- w przypadku braku dostępności leku sprawdzanie zamienników które mogą być na stanie dla aktora "aptekarz"
- sprawdzanie jakie leki jeszcze są do wydania na erecepcie dla aktora "aptekarz"
- zaznaczanie leków jako już wydanych (całościowo albo część dawki) na erecepcie dla aktora "aptekarz"
- sprawdzanie listy leków łagodzących konkretne dolegliwości dla aktora "aptekarz"
- wyszukiwanie dostępnych leków w aptece dla aktora "klient"
- sprawdzanie zawartości swojej erecepty dla aktora "klient"
- sprawdzanie ile jeszcze leków zostało do wydania z erecepty dla aktora "klient"
- dodawanie informacji o wydaniu leku na receptę Rpw do książki narkotycznej dla aktora "aptekarz"