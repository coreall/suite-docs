# Kontrahenci

### Pola wspólne

* id \| varchar \(36\)
* name \| nvarchar \(150\)
* date\_entered \| datetime \(NULL\)
* date\_modified \| datetime \(NULL\)
* modified\_user\_id \| varchar \(36\)
* created\_by \| varchar \(36\)
* description \| nvarchar \(-1\)
* deleted \| bit \(NULL\)
* assigned\_user\_id \| varchar \(36\)

### account\_type \| nvarchar \(100\)

Typ kontrahenta

{% hint style="info" %}
Lista rozwijalna. Przyjmuje jedną z wartości:

* Dealer 
* Dousu 
* Competitor 
* Prospekt 
* Customer 
* Partner\_Handlowy 
* Konkurencja\_Producent 
* Partner\_Handlowy\_Autoryzowany 
* Other
{% endhint %}

### industry \| nvarchar \(100\)

Branża przedsiębiorcy 

{% hint style="info" %}
Lista wielokrotnego wyboru przyjmuje wartości:

* ^Automotive^
* ^Biuro\_konstrukcyjne^
* ^Government^
* ^Homedecor^
* ^Homedecor^,^Obuwie^
* ^Kompozyty^
* ^Machinery^
* ^Meblarska^
* ^Meblarska^,^Obuwie^
* ^Not For Profit^
* ^Odziez^
* ^Pozostali^
* ^Technologies^
* ^Utilities^
* ^Zabawki^
{% endhint %}

### phone\_fax \| nvarchar \(100\)

Numer fax

### billing\_address\_street \| nvarchar \(150\)

Adres kontrahenta - ulica

### billing\_address\_city \| nvarchar \(100\)

Adres kontrahenta - miasto

### billing\_address\_state \| nvarchar \(100\)

Adres kontrahenta - województwo

### billing\_address\_postalcode \| nvarchar \(20\)

Adres kontrahenta - kod pocztowy

### billing\_address\_country \| nvarchar \(255\)

Adres kontrahenta - państwo

### rating \| nvarchar \(100\)

W tym polu jest zapisywany numer NIP

### phone\_office \| nvarchar \(100\)

Telefon do biura

### phone\_alternate \| nvarchar \(100\)

Dodatkowy numer telefonu

### website \| nvarchar \(255\)

Strona internetowa

### ownership \| nvarchar \(100\)

Pole nieużywane

### employees \| nvarchar \(10\)

Pole nieużywane

### ticker\_symbol \| nvarchar \(10\)

Pole nieużywane

### shipping\_address\_street \| nvarchar \(150\)

Adres dostawy - ulica

### shipping\_address\_city \| nvarchar \(100\)

Adres dostawy - miasto

### shipping\_address\_state \| nvarchar \(100\)

Adres dostawy - województwo

### shipping\_address\_postalcode \| nvarchar \(20\)

Adres dostawy - kod pocztowy

### shipping\_address\_country \| nvarchar \(255\)

Adres dostawy - państwo

### parent\_id \| varchar \(36\)

{% hint style="info" %}
Klucz obcy tabeli accounts
{% endhint %}

### sic\_code \| nvarchar \(10\)

Pole nieużywane.

### campaign\_id \| varchar \(36\)

{% hint style="info" %}
Identyfikator powiązanej kampanii
{% endhint %}

### billing\_address\_region \| nvarchar \(255\)

Pole nieużywane

### shipping\_address\_region \| nvarchar \(255\)

Pole nieużywane

### id\_c \| varchar \(36\)

{% hint style="info" %}
Klucz obcy tabeli accounts
{% endhint %}

### jjwg\_maps\_lng\_c \| real \(NULL\)

Pole nieużywane

### jjwg\_maps\_lat\_c \| real \(NULL\)

Pole nieużywane

### jjwg\_maps\_geocode\_status\_c \| nvarchar \(255\)

Pole nieużywane

### jjwg\_maps\_address\_c \| nvarchar \(255\)

Pole nieużywane.

### forma\_po\_fin\_c \| nvarchar \(255\)

Pole nieużywane

### skala\_dzialani\_c \| nvarchar \(255\)

Pole nieużywane

### inf\_nat\_zatru\_c \| nvarchar \(255\)

Pole nieużywane

### rekrutacje\_c \| nvarchar \(255\)

Pole nieużywane

### aktualna\_sytuacja\_c \| nvarchar \(255\)

Pole nieużywane

### obecna\_technologia\_c \| nvarchar \(255\)

Pole nieużywane

### przebieg\_produkcji\_c \| nvarchar \(-1\)



plany\_c \| nvarchar \(-1\)

przyczyny\_inwestycji\_c \| nvarchar \(-1\)

wspolne\_ustalenia\_c \| nvarchar \(-1\)

wiedza\_c \| nvarchar \(-1\)

segmentacja\_c \| nvarchar \(100\)

pozyskanie\_c \| nvarchar \(100\)

formaw\_c \| nvarchar \(255\)

ukladw\_c \| nvarchar \(255\)

test\_c \| nvarchar \(-1\)

payment\_c \| nvarchar \(255\)

region\_c \| nvarchar \(255\)

nip\_zagraniczny\_c \| nvarchar \(255\)

telefon\_do\_biura\_2\_c \| nvarchar \(255\)

liczba\_pracownikow\_c \| nvarchar \(100\)

ko\_c \| nvarchar \(-1\)

liczba\_pracownikow\_konk\_c \| nvarchar \(100\)

forma\_dzialanosci\_c \| nvarchar \(-1\)

mocne\_strony\_c \| nvarchar \(-1\)

slabe\_strony\_c \| nvarchar \(-1\)

produkty\_c \| nvarchar \(-1\)

payment\_capability\_c \| nvarchar \(100\)

has\_products\_c \| nvarchar \(-1\)

features\_old\_c \| nvarchar \(-1\)

categories\_old\_c \| nvarchar \(-1\)

cutter\_room\_c \| bit \(NULL\)

ownership\_form\_list\_c \| nvarchar \(100\)

gain\_c \| decimal \(NULL\)

### cutting\_room\_c \| nvarchar \(100\)

Informacja czy kontrahent posiada krojownię.

### notes\_itcube\_c \| nvarchar \(-1\)

Stare notatki z ITCUBE

### reccomendation\_c \| nvarchar \(100\)

Rekomendacja

### reference\_visit\_c \| nvarchar \(100\)

Wizyta referencyjna

### reference\_c \| nvarchar \(100\)

Referencje 

### earlier\_assigned\_to\_c \| nvarchar \(255\)

Wcześniej przypisane do

{% hint style="warning" %}
Pole aktualizowane na nakładką JS
{% endhint %}

### internal\_path\_c \| nvarchar \(255\)

Ścieżka do katalogu w domenie

