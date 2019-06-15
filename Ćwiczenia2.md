Ustawianie parametrów sieci
---------------------------

![alt text][network]

[network]: ./network.png "Logo Title Text 2"

1. na 1 z komputerów zainstaluj oprogramowanie ``http-chat`` dostępne pod adresem ``https://github.com/jkanclerz/http-chat``

Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  CentOS-7|
| IP - address  |192.168.100.5 | |
| MASKA  |255.255.255.0 | |
|   |  | |
| PC 2  | CentOS-7 | |
| IP - address  |192.168.100.4 | |
| MASKA  |255.255.255.0 | |

Weryfikacja połączenia


Polecenie


Efekt
```
```

Statyczna konfiguracja parametrów połączenia
Wejściowe parametry sieci
-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  | 192.168.10.10 | |
| MASKA  | 255.255.255.0 | |
|   |  | |
| PC 2  |  | |
| IP - address  | 172.16.100.100 | |
| MASKA  | 255.255.0.0 | |

Weryfikacja połączenia

Polecenie
```
```

Efekt
```
```

Nowa statyczna konfiguracja 

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
|   PC 1 |  
| IP - address  |  | |
| MASKA  |  | |
|   |  | |
| PC 2  |  | |
| IP - address  |  | |
| MASKA  |  | |

Weryfikacja połączenia

nmcli
ifup enp0s3

Polecenie
```
```

Efekt
```
```

Warto wiedzieć
--------------

-------------------------
| Parametr | wartość | komentarz(opcionalny) |
| ------------- |:-------------:| -----:|
| Lokalizacja pliku z konfiguracją sieci| | |
| UP -> Wyłączenie interfejsu sieciowego|ifup enp0s3 | |
| DOWN -> Włączenie interfejsu sieciowego|ifdown enp0s3 | |
| Sprawdzenie obecnych parametrów |ip a |ifconfig |
| lista wszystkich interfejsów |ip a |nmcli |
| Które interfejsy jakie porty słuchają | | |

if a
nmcli
ifup enp0s3
ifdown enp0s3
curl -X POST -d symuluje działanie przeglądaski
