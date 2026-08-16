# Nihal Abdullahi - E-Portfolio

**Civilingenjörsstudent i Informationsteknik | KTH**  
*Kontakt:* [Din e-postadress] | [Länk till din LinkedIn]

---

## Om mig
Jag studerar mitt tredje år på civilingenjörsprogrammet i Informationsteknik vid KTH. Jag har ett starkt intresse för inbyggda system, hårdvarunära programmering och IT-säkerhet. Genom mina studier har jag byggt en solid teknisk grund inom C, Java, SQL samt systemarkitektur och nätverk.

---

## Utvalda Projekt

### Embedded Traffic Light System (Inbyggda System & Hårdvara)
**Typ:** Projekt i datorteknik / inbyggda system vid KTH  
**Tekniker:** C, STM32 (Nucleo-L476RG), STM32CubeIDE (HAL), SPI, GPIO, ADC, PWM, FSM (Tillståndsmaskiner)

#### Beskrivning
Projektet är ett inbyggt styrsystem för en korsning med trafik- och övergångsställssignaler, utvecklat på ett STM32 Nucleo-L476RG-kort tillsammans med en Traffic Light Shield. Systemet simulerar realistiskt trafikflöde för både bilar och fotgängare med visuell återkoppling i realtid via LED-lampor och en OLED-display.

#### Teknisk genomförande & Arkitektur
* **Systemlogik:** Implementerade tillståndsmaskiner (Finite State Machines, FSM) i C för att hantera sekvenser och regler för trafikljusen.
* **Hårdvarukontroll & Drivrutiner:** Utvecklade moduluppbyggda drivrutiner med C och STM32 HAL-bibliotek.
* **Kommunikationsprotokoll:** Använde SPI-kommunikation för att styra kaskadkopplade 74HC595 shift-register samt OLED-skärmen.
* **Sensorer & Inputs:** Använde GPIO för knappar och bil-detektorer, samt ADC och PWM för att justera LED-lampornas ljusstyrka via potentiometer.

#### Min roll & Reflektion
I detta projekt fick jag tillämpa teoretisk kunskap om datorteknik i ett praktiskt hårdvarunära sammanhang. Jag ansvarade för att strukturerat bygga mjukvarulager som separerar hårdvarustyrning från systemlogiken. Projektet utvecklade min förmåga att felsöka hårdvarunära C-kod, förstå mikrokontrollers periferienheter samt strukturera koden på ett modulärt och säkert sätt.

---

## Färdigheter & Kompetenser
* **Programmeringsspråk:** C, Java, SQL
* **Hårdvara & Inbyggda system:** STM32, Microcontrollers, SPI, GPIO, ADC, PWM, FSM
* **Verktyg:** STM32CubeIDE, Git, VS Code, Linux
* **Erfarenheter:** Grupparbete, strukturerad problemlösning, kommunikation och kundservice.
