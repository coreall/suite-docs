---
description: 'tabela: aos_contracts'
---

# Zamówienia \(aos\_contracts\)

## Pola wspólne

* id \| varchar \(36\) 
* name \| nvarchar \(255\) 
* date\_entered \| datetime \(NULL\) 
* date\_modified \| datetime \(NULL\) 
* modified\_user\_id \| varchar \(36\) 
* created\_by \| varchar \(36\) 
* description \| nvarchar \(-1\) 
* deleted \| bit \(NULL\) 
* assigned\_user\_id \| varchar \(36\) 

### reference\_code \| nvarchar \(255\) 

Pole nieużywane

### start\_date \| datetime \(NULL\) 

Data rozpoczęcia kontraktu

### end\_date \| datetime \(NULL\) 

Data zakończenia kontraktu

### total\_contract\_value \| decimal \(NULL\) 

Całkowita wartość kontraktu

### total\_contract\_value\_usdollar \| decimal \(NULL\) 

Całkowita wartość kontraktu w dolarach

### currency\_id \| varchar \(36\) 

Identyfikator płatności

{% hint style="info" %}
Identyikator -99 odnosi się do waluty domyślnej
{% endhint %}

### status \| nvarchar \(100\) 

Lista rozwijalna - przyjmuje jedną z trzech wartości



* customer\_signed\_date \| datetime \(NULL\) 
* company\_signed\_date \| datetime \(NULL\) 
* renewal\_reminder\_date \| datetime \(NULL\) 
* contract\_type \| nvarchar \(100\) 
* contract\_account\_id \| varchar \(36\) 
* opportunity\_id \| varchar \(36\) 
* contact\_id \| varchar \(36\) 
* call\_id \| varchar \(36\) 
* total\_amt \| decimal \(NULL\) 
* total\_amt\_usdollar \| decimal \(NULL\) 
* subtotal\_amount \| decimal \(NULL\) 
* subtotal\_amount\_usdollar \| decimal \(NULL\) 
* discount\_amount \| decimal \(NULL\) 
* discount\_amount\_usdollar \| decimal \(NULL\) 
* tax\_amount \| decimal \(NULL\) 
* tax\_amount\_usdollar \| decimal \(NULL\) 
* shipping\_amount \| decimal \(NULL\) 
* shipping\_amount\_usdollar \| decimal \(NULL\) 
* shipping\_tax \| nvarchar \(100\) 
* shipping\_tax\_amt \| decimal \(NULL\) 
* shipping\_tax\_amt\_usdollar \| decimal \(NULL\) 
* total\_amount \| decimal \(NULL\) 
* total\_amount\_usdollar \| decimal \(NULL\) 
* quote\_id \| varchar \(36\)

### 

