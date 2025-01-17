
## Verkefni 2

- Settu upp verklega með brauðbretti og íhlutum
- Svaraðu spurningum þar sem það á við.

---

#### 1. Að vinna með hliðræn gildi (4%)

1. Notaðu [LDR](https://create.arduino.cc/projecthub/tarantula3/using-an-ldr-sensor-with-arduino-807b1c) ljósnema til að stýra birtustigi og litum á [RGB LED](https://learn.adafruit.com/adafruit-arduino-lesson-3-rgb-leds/overview). Þegar það verður minni birta í umhverfinu þá eykst birtan smám saman (fade in) á RGB LED á móti með mismunandi litablæbrigðum og svo öfugt þegar birtan eykst í umhverfinu.
    1. Hvað er átt við með *duty cycle* í PWM? 
    1. Afhverju skilar analogRead() heiltölu á bilinu 0-1023?
       
---

#### 2. HC-SR04 Ultrasonic Sensor (4%)
1. Kynntu þér hvernig HC-SR04 Ultrasonic Sensor virkar með því að lesa [þessa grein](https://lastminuteengineers.com/arduino-sr04-ultrasonic-sensor-tutorial/). 
    1. Hversu nákvæmar eru mælingarnar með Ultrasonic Sensor?
1. Tengdu HC-SR04 við Arduino Uno og skoðaðu eftirfarandi [kóðasbút](https://github.com/VESM2VT/Efni/blob/main/Kodi/sonic.ino). Bættu við kóðann eftirfarandi:
   1. hann birtir fjarlægðir í cm í Serial monitor.
   2. ef fjarlægð er meiri en 4 metrar þá prentast á Serial monitor "Out of range". 
   
   
---

#### 3. LCD (4%)
1. Kynntu þér hvernig 16×2 Character LCD virkar með því að lesa [þessa grein](https://lastminuteengineers.com/arduino-1602-character-lcd-tutorial/) og svaraðu eftirfarandi spurningum:
   1. Afhverju er R/W tengt í GND?
   1. Ahverju þarf að stýra LCD1602 með nokkrum pinnum (4 eða 8) á sama tíma? útskýrðu!
1. Settu upp [Halló heimur](https://lastminuteengineers.com/arduino-1602-character-lcd-tutorial/#arduino-code) en breyttu kóðanum þannig að nafnið þitt birtist í efri línunni á skjánum, einn stafur í einu. Í neðri línunni á að standa Tolvubraut. Skoðaðu aðferðir í [LiquidCrystal Library](https://www.arduino.cc/en/Reference/LiquidCrystal).
 
 

![lcd nafn](https://raw.githubusercontent.com/VESM2VT/Efni/main/Myndir/lcd_verkefni2.gif)

---

#### 4. Ultrasonic og LCD (2%)

1. Fylgdu eftir [Contactless Distance Finder + LCD + LCDBarGraph](https://lastminuteengineers.com/arduino-sr04-ultrasonic-sensor-tutorial/#arduino-project-contactless-distance-finder) og settu upp verklega.
   1. Hvernig getur hitastig og raki úti haft áhrif á fjarlægðarmælingar með HC-SR04?

---

## Námsmat og skil
Gefið er heilt fyrir fullnægjandi lausn og svör, hálft ef ábótavant eða ekkert ef svör vantar.
Skilaðu á Innu vefslóð á **Github wiki** vefsíðu (private) sem inniheldur:

- Myndbönd af virkni úr verklegum tilraunum.
  - Passaðu að nafnið þitt og dagsetning komi fram (t.d. á miða) í öllum myndböndum.
- Kóði.
- Svör við spurningum.


