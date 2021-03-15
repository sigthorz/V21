# Verkefni 1

- Settu upp verklega með brauðbretti og íhlutum
- Svaraðu spurningum þar sem það á við.

---
#### DHT11 og serial monitor (3%)

Skoðaðu [þessa grein](https://lastminuteengineers.com/dht11-module-arduino-tutorial/) um hita og rakaskynjarann DHT11. 

1. Útskýrðu með eigin orðum hvernig rakinn er mældur.
1. Settu upp fyrri rásina í greininni (það á ekki að setja upp rásina með LCD skjánum).

#### 7-Segment ein tala (3%)

Kynntu þér hvernig 7-Segment virkar með því að lesa [þessa grein](https://lastminuteengineers.com/seven-segment-arduino-tutorial/).

1. Hvort er þitt 7-Segment Display *common anode* eða *common cathode* og hver er munurinn á þessu tvennu?
1. Í greininni er sýnd útfærsla á teljara. Settu teljarann upp á brauðbretti og settu kóðann á Arduino tölvuna þína.
1. Þú veist að ```loop``` fallið er lykkja en í kóðadæminu er eina sem er í fallinu ```for``` lykkja. Breyttu útfærslunni á fallinu þannig að það þurfi ekki að nota "auka" lykkju.
1. Útfærðu teninginn sem er neðst í greininni en breyttu útfærslunni þannig að þú þurfir ekki "pullup" viðnámið heldur sé það leyst í kóða. Bættu líka við "debounce" á takkann.

#### 7-Segment fjórar tölur (3%)

Kynntu þér hvernig 7-Segment með fjórum tölustöfum virkar með því að lesa seinni hluta [þessarar greinar](https://www.circuitbasics.com/arduino-7-segment-display-tutorial/) (kaflinn *4 DIGIT 7-SEGMENT DISPLAYS*)

1. Settu upp fyrri rásina (sem birtir 4999) ekki á að setja upp seinni rásina.
1. Bættu inn í ```loop``` fallið einni ```delay``` skipun. Prófaðu að hafa ```delay``` í eina sekúndu (1000 ms) og svaraðu svo eftirfarandi spurningum.
   1. Hvað gerist?
   1. Af hverju gerist það?


#### 7-Segment 4 tölustafir með dht11 og takka. (5%)

Settu upp rás sem getur mælt hita og rakastig og birt það á 4 tölustafa 7-Segment skjá. Það þarf að vera hægt að skipta á milli þess hvort skjárinn sýnir hita eða raka stig með takka.

Dæmi um útfærslu:

![Hitastig - Rakastig](https://raw.githubusercontent.com/VESM2VT/Efni/main/Myndir/v1_v21.gif)

---

## Námsmat og skil
Gefið er heilt fyrir fullnægjandi lausn og svör, hálft ef ábótavant eða ekkert ef svör vantar.
Skilaðu á Innu vefslóð á **Github wiki** vefsíðu (private) sem inniheldur:

- Myndbönd af virkni úr verklegum tilraunum.
  - Passaðu að nafnið þitt og dagsetning komi fram (t.d. á miða) í öllum myndböndum.
- Kóði.
- Svör við spurningum.

<!--
#### Takki + pullup/down viðnám (%) 
- tutorial óbreyttur, tímaverkefni

1. tímaverkefni; birta tölu, teljari, teningakast.
1. Hvort er þitt 7-Segment Display *common anode* eða *common cathode* og hver er munurinn á þessu tvennu?
1. 7-Segment Display samanstendur af 8 LED, hvers vegna þarf bara eitt viðnám (en ekki átta)?
1. Útfærðu teljara (Count Up Timer) með 7 segment display þannig að hann noti ekki `for` lykkjuna.

-->
