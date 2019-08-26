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

### amount\_usdollar \| float \(NULL\) 

### currency\_id \| varchar \(36\) 

### date\_closed \| datetime \(NULL\) 

### next\_step \| nvarchar \(100\) 

### sales\_stage \| nvarchar \(255\) 

### probability \| float \(NULL\) 

### account\_id \| varchar \(36\) 

### quote\_id \| varchar \(36\) 

### contract\_id \| varchar \(36\) 

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

