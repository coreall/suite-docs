# Oferty

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

### approval\_issue \| nvarchar \(-1\)

### billing\_account\_id \| varchar \(36\)

Klucz obcy tabeli accounts

### billing\_contact\_id \| varchar \(36\)



### billing\_address\_street \| nvarchar \(150\)

billing\_address\_city \| nvarchar \(100\)

billing\_address\_state \| nvarchar \(100\)

billing\_address\_postalcode \| nvarchar \(20\)

billing\_address\_country \| nvarchar \(255\)

shipping\_address\_street \| nvarchar \(150\)

shipping\_address\_city \| nvarchar \(100\)

shipping\_address\_state \| nvarchar \(100\)

shipping\_address\_postalcode \| nvarchar \(20\)

shipping\_address\_country \| nvarchar \(255\)

expiration \| datetime \(NULL\)

number \| int \(NULL\)

opportunity\_id \| varchar \(36\)

template\_ddown\_c \| nvarchar \(-1\)

total\_amt \| decimal \(NULL\)

total\_amt\_usdollar \| decimal \(NULL\)

subtotal\_amount \| decimal \(NULL\)

subtotal\_amount\_usdollar \| decimal \(NULL\)

discount\_amount \| decimal \(NULL\)

discount\_amount\_usdollar \| decimal \(NULL\)

tax\_amount \| decimal \(NULL\)

tax\_amount\_usdollar \| decimal \(NULL\)

shipping\_amount \| decimal \(NULL\)

shipping\_amount\_usdollar \| decimal \(NULL\)

shipping\_tax \| nvarchar \(100\)

shipping\_tax\_amt \| decimal \(NULL\)

shipping\_tax\_amt\_usdollar \| decimal \(NULL\)

total\_amount \| decimal \(NULL\)

total\_amount\_usdollar \| decimal \(NULL\)

currency\_id \| varchar \(36\)

stage \| nvarchar \(100\)

term \| nvarchar \(100\)

terms\_c \| nvarchar \(-1\)

approval\_status \| nvarchar \(100\)

invoice\_status \| nvarchar \(100\)

subtotal\_tax\_amount \| decimal \(NULL\)

subtotal\_tax\_amount\_usdollar \| decimal \(NULL\)

billing\_address\_region \| nvarchar \(255\)

shipping\_address\_region \| nvarchar \(255\)

nr\_oferty \| nvarchar \(255\)

id\_c \| varchar \(36\)

werfyfikacja\_techniczna\_c \| nvarchar \(100\)

warunki\_c \| nvarchar \(-1\)

warunkig\_c \| nvarchar \(-1\)

przyczyna\_porazki\_c \| nvarchar \(255\)

przyczyna\_wygranej\_c \| nvarchar \(-1\)

account\_id\_c \| varchar \(36\)

typ\_maszyny\_c \| nvarchar \(255\)

typ\_oferty\_c \| nvarchar \(100\)

akceptacja\_dyrekcja\_c \| bit \(NULL\)

akceptacja\_handlowiec\_c \| bit \(NULL\)

akceptacja\_finansowa\_c \| bit \(NULL\)

akceptacja\_inz\_prod\_c \| bit \(NULL\)

weryfikacja\_finansowa\_c \| nvarchar \(100\)

weryfikacja\_inz\_c \| nvarchar \(100\)

typ\_produktu\_c \| nvarchar \(100\)

akceptacja\_techniczna\_c \| bit \(NULL\)

powiadom\_dyrekcje\_c \| nvarchar \(1\)

date\_sent\_quote\_c \| datetime \(NULL\)

installation\_date\_c \| datetime \(NULL\)

closed\_won\_probability\_c \| nvarchar \(100\)

