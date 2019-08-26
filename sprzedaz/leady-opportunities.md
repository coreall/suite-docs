---
description: 'tabela: opportunities'
---

# Leady \(opportunities\)

### Pola wspólne \([link](https://app.gitbook.com/@pio-skro/s/dokumentacja-crm/~/drafts/-Lmo1Xvz8Q5J3wfhFDSw/primary/pola-wspolne)\)

* id \| varchar \(36\)
* name \| nvarchar \(50\) 
* date\_entered \| datetime \(NULL\) 
* date\_modified \| datetime \(NULL\) 
* modified\_user\_id \| varchar \(36\) 
* created\_by \| varchar \(36\) 
* description \| nvarchar \(-1\) 
* deleted \| bit \(NULL\) 
* assigned\_user\_id \| varchar \(36\) 
* currency\_id \| varchar \(36\) 

### opportunity\_type \| nvarchar \(255\) 

> Pole niewidoczne w SuiteCRM

{% hint style="info" %}
Lista rozwijalna. Może przyjąć wartości _\[Wartość zapisywana w DB\]_

* Wynika z istniejący umów _\[Existing Business\]_
* Nowo wypracowana _\[Nowo wypracowana\]_
{% endhint %}

### campaign\_id \| varchar \(36\) 

{% hint style="warning" %}
Klucz obcy tabeli campaigns
{% endhint %}

### lead\_source \| nvarchar \(100\) 

{% hint style="info" %}
Lista rozwijalna. 

* -czysto- \[-czysto-\] 
* Cold Call \[Cold Calling\] 
* Dealer \[Dealer\] 
* Self Generated \[Inicjatywa Własna Handlowca\] 
* Employee \[Z polecenia pracownika Allcomp\] 
* Partner \[Partner\] 
* Public Relations \[Public Relations\] 
* Web Site \[Formularz www\] 
* Word of mouth 
* \[Z polecenia klienta\] 
* Email \[Z emaila\] 
* Targi \[Targi\] 
* Phone \[Telefon\] 
* Press \[Prasa\] 
* Databases \[Z baz\] 
* Socialmedia \[Z social media\] 
* Internet \[Z internetu\] 
* Networking \[Networking\] 
* Ankieta \[Badanie Satysfakcji Klienta\]
{% endhint %}

### amount \| float \(NULL\) 

Pole określające wartość Leada netto.

{% hint style="success" %}
Na późniejszych etapach procesu sprzedaży wartość ta jest aktualizowana za pomocą 

1. Workflows w SuiteCRm
2. Cleanerów uruchamianych cyklicznie w aplikacji CoreA.
{% endhint %}

### amount\_usdollar \| float \(NULL\) 

> Pole nieużywane

### date\_closed \| datetime \(NULL\) 

Data zakończenia danego etapu 

> Pole widoczne w module Leady. Nie było nigdy jednak zwracane w żadnym z raportów.

### next\_step \| nvarchar \(100\) 

> Pole nieużywane

### sales\_stage \| nvarchar \(255\) 

Etap Leada

{% hint style="info" %}
Lista rozwijalna

* LeadNKrp \[LN\] 
* LNU \[LN - Anulowany\] 
* LeadKW \[LK Wycena\] 
* LeadKWof \[LK Oferta Wysłana\] 
* Closed Won \[LK Zakończony sukcesem\] 
* Closed Lost \[LK Zakończony porażką\] 
* LeadUn \[LK Unieważniony\] 
* Kontrakt\_Podpisany \[LK Zaliczka wpłynęła\]
{% endhint %}

### probability \| float \(NULL\) 

Prawdopodobieństwo. Za wyjątkiem gdy etap Leada jest równy LN prawdopodobieńtwo jest aktualizowane przez aplikację CoreA raz dziennie na podstawie zależności. 

```text
/*
 * LN - 2%
 * LK Wycena - 10%
 * LK Oferta wysłana
 *      Oferta 20% - Lead 20%
 *      Oferta 40% - Lead 30%
 *      Oferta 60% - Lead 50%
 *      Oferta 80% - Lead 70%
 *      Oferta 100% - Lead 80%
 * LK Podpisany kontrakt - 90%
 * LK Zaliczka wpłtynęła - 100%
 */
```

### account\_id \| varchar \(36\) 

{% hint style="warning" %}
Klucz obcy tabeli accounts

**UWAGA!** Pole dodane zewnętrznie do tabeli opportunities, aby zoptymalizować raportowanie i wiązanie z tabelą. Natywnie w SuiteCRM tabele opportunities oraz accounts są powiazane relacją wiele-do-wielu zapośrednioczoną przez tabelę accounts\_opportunities. 

_Aktualizacja tego pola dokonuje się za pośrednictwem aplikacji CoreA_
{% endhint %}

### quote\_id \| varchar \(36\) 

{% hint style="warning" %}
Klucz obcy tabeli łączący z jedną ofertą \(Ofertą Estymowaną\).

**UWAGA!** Pole dodane zewnętrznie do tabeli opportunities, aby zoptymalizować raportowanie i wiązanie z tabelą quotes. Natywnie w SuiteCRM tabele opportunities oraz quotes są powiazane relacją jeden-do-wielu \(jeden lead ma wiele ofert\). 

_Aktualizacja tego pola dokonuje się za pośrednictwem aplikacji CoreA_
{% endhint %}

### contract\_id \| varchar \(36\)

###  

### tax \| float \(NULL\) 

### id\_c \| varchar \(36\) 

### jjwg\_maps\_lng\_c \| real \(NULL\) 

### jjwg\_maps\_lat\_c \| real \(NULL\) 

### jjwg\_maps\_geocode\_status\_c \| nvarchar \(255\) 

### jjwg\_maps\_address\_c \| nvarchar \(255\) 

### data\_zamkniecia\_c \| datetime \(NULL\) 

### wymagania\_konwersja\_c \| nvarchar \(-1\) 

### okreslenieleada\_c \| nvarchar \(-1\) 

### przyczyna\_porazki\_c \| nvarchar \(255\) 

### przyczyna\_wygranej\_c \| nvarchar \(-1\) 

### account\_id\_c \| varchar \(36\) 

### typ\_maszyny\_c \| nvarchar \(255\) 

### nr\_lead\_c \| nvarchar \(255\) 

### nr\_kolejny\_c \| int \(NULL\) 

### cancel\_category\_c \| nvarchar \(100\) 

### installation\_date\_c \| datetime \(NULL\)

### 

