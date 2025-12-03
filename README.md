 DodatkoweTesty
musi być 

test 1 
Zakłócenie działania drukarki paragonów przy nieudanej wysyłce e-paragonu 
scenariusz: 
1. Nabiajmy paragon 
2. Kończymy wybieramy e-paragon email 
3. wpisujemy adres e-mail czekamy na dialog nieudanej wysyłki 
4. wyłączamy drukarke klikamy wydrukuj pokaze ze nie powiązało połączenie z drukarką 
5. wychodzimy z dialogu będą zablokowane przyciski zakończ i anuluj mozna będzie zamknąć aplikacje i przy ponownym otwarciu "podpis dokumentu nie jest zgodny z poprzednim dokumentem" 


test 2 
praca z terminalem na paragonie niepoprawnie wyświetla się reszta 
1. otwieramy paragon
3. dajemy płatność 3 linii gotowka eur karta 
4. dzielimy w losowy sposób ilość do zapłaty między nimi 
5. po sukcesywnej zapłacie na terminalu cofamy strałką i jeszcze raz płacimy 

test3 
eksport bazy towarowej 
scenariusz: 
1. programijemy towary na Kasie o nazwach towar.b,towar_b, towar%b, towar/b
2. ustawienia eksport danych -> towarów i usług zapisujemy ten plik na PC 
3. zmieniamy z poziomu konsoli typ licencji na drukarka 
4. emintyjemy paragon z takim samym towarem który wcześniej był zaprogromowany na licencji kasy.

test4 
działanie ze skanerem 
scenariusz: 
1. licencja kasa połączyć skaner po bluetooth 
2. zaprogramować produkt z kodem kreskowym 
3. zeskanowac z widoku "sprzedaż" 
4. klinąć zakończ -> e-paragon email -> nieudana wysyłka przy zepsutych certyfikatach 
5. czekamy dopóki skaner nie wejdzie w stan śpiący wtedy zresetuje się dialog można będzie wyjść i modyf  ikować paragon 
  
sprawdzić: |ч
filtry z ekranu sprzedazy

napisać skrypt z postman do tworzenia bazy towarowej 




notatki 
1: spróbowac zamknąc apke nawi ✅

wypisać zadanie na "wydrukuj" moze dwa razy otworzyć dialog + e-paragon 

w pole linii płatności czasami trzeba usuwać metode zeby wpisać ponownie(nagrać filmik) 


tekst w rejestr zmian konf przy zmianie czytniku piszę ze drukarka

zaciemnia przy dodaniu produktu z skanera

sprawdzic w eksporcie inne opcje 

nie ma walidacji na produktach (plu barcode number)✅

------
zapytać czemu ustawienie naglówka linia 1 mam wpisane null a przy eksporcie nadal się wyświetla grupa ABS 

przekazuje czas z kasy a nie z urządzenia, jest ok?

statystyki sprzedazy wysyłka danych zakończona niepowodzeniem 

raport fiskalizacji się nie pojawia jezeli nie ustawiony filtr :)

cash change log jest pusty chociaz 

============ATTEMP 2===
setting.txt pusta tablica 

test case 1 sprawdzić przez protokol + przetestować flagi i czy zwrócony jpk jest zgodny z tym co będzie wysłane do repo i JWS/JPKe-paragonu 

sprawdzić z jws e-paragonu 

opcje GUM popsuć podpis paragonu i czy zmieni się w eksporcie???? 



sprawdzic w eksporcie appchecksum - zacząć aktualizacje i po zainstalowaniu eksportować sume kontrolną i jezeli będzie nowa to niepoprawnie 

w trybie szkoleniowym czy jest opcja dostępna 

sprawdzić currentTime jezeli ustawić na dzień wczorajszy 

jezeli zmienić w licencji Nazwe podatnika przed/po fiskslizacja czy podmieniają się dane i czy wczytuje to przy eksporcie

sprawdzić czy jest dokumnt nefiskalny terminalu przy eksporcie dokumnetów niefiskalncych 













