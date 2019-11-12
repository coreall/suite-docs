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

industry \| nvarchar \(100\)

annual\_revenue \| nvarchar \(100\)

phone\_fax \| nvarchar \(100\)

billing\_address\_street \| nvarchar \(150\)

billing\_address\_city \| nvarchar \(100\)

billing\_address\_state \| nvarchar \(100\)

billing\_address\_postalcode \| nvarchar \(20\)

billing\_address\_country \| nvarchar \(255\)

rating \| nvarchar \(100\)

phone\_office \| nvarchar \(100\)

phone\_alternate \| nvarchar \(100\)

website \| nvarchar \(255\)

ownership \| nvarchar \(100\)

employees \| nvarchar \(10\)

ticker\_symbol \| nvarchar \(10\)

shipping\_address\_street \| nvarchar \(150\)

shipping\_address\_city \| nvarchar \(100\)

shipping\_address\_state \| nvarchar \(100\)

shipping\_address\_postalcode \| nvarchar \(20\)

shipping\_address\_country \| nvarchar \(255\)

parent\_id \| varchar \(36\)

sic\_code \| nvarchar \(10\)

campaign\_id \| varchar \(36\)

billing\_address\_region \| nvarchar \(255\)

shipping\_address\_region \| nvarchar \(255\)

id\_c \| varchar \(36\)

jjwg\_maps\_lng\_c \| real \(NULL\)

jjwg\_maps\_lat\_c \| real \(NULL\)

jjwg\_maps\_geocode\_status\_c \| nvarchar \(255\)

jjwg\_maps\_address\_c \| nvarchar \(255\)

forma\_po\_fin\_c \| nvarchar \(255\)

skala\_dzialani\_c \| nvarchar \(255\)

inf\_nat\_zatru\_c \| nvarchar \(255\)

rekrutacje\_c \| nvarchar \(255\)

aktualna\_sytuacja\_c \| nvarchar \(255\)

obecna\_technologia\_c \| nvarchar \(255\)

przebieg\_produkcji\_c \| nvarchar \(-1\)

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

cutting\_room\_c \| nvarchar \(100\)

notes\_itcube\_c \| nvarchar \(-1\)

reccomendation\_c \| nvarchar \(100\)

reference\_visit\_c \| nvarchar \(100\)

reference\_c \| nvarchar \(100\)

earlier\_assigned\_to\_c \| nvarchar \(255\)

internal\_path\_c \| nvarchar \(255\)

