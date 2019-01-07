# SISTEM DE ILUMINAT

Acesta poate fi uitilizat pentru economisirea energiei.

LED-ul se aprinde daca sunt indeplinite urmatoarele doua conditii:
 - spatiul este neiluminat;
 - prezenta miscarii.

Componente folosite:

Microcontroller ATmega328p-PU;
Tranzistor NPN de Putere TIP41C;
LED de Putere Verde de 1 W cu Radiator;
Fotorezistor (tip 5528);
Modul Senzor PIR HC-SR501 (Senzor de Miscare);


Senzorul de miscare detecteaza razele infrarosii iar fotorezistorul isi schimba rezistenta in functie de intensitatea luminii. Cu cat lumina este mai puternica cu atat rezistenta acestuia scade si invers.

Daca cele doua conditii sunt satisfacute microcontrolerul trimite semnal catre tranzistorul NPN. Acesta se deschide si permite aprinderea LED-ului.

Pentru programarea acestuia am folosit programatorul USBasp si software-ul AtmelStudio.
