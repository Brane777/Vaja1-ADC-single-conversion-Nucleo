# Vaja1-ADC-single-conversion-Nucleo

Zelena LED je priključena na PA5 pin. Kaj je pa priključeno na pin PA0? Potenciometer

V Analog razdelku levo od sheme mikroprocesorja ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? 3 pretvornike.

Izbrani ADC pretvornik(i) ima(jo) oznako s trikotnikom. Kaj to pomeni? da je konflikt z pini/so že zasedeni 

Kaj morate storiti, da razrešite to omejitev? Moramo postaviti vse zasedene pine v stanje RESET, tako da ni nobenega konflikta.

Koliko je vseh vhodnih kanalov (seštejte oznake INxx) 15.

Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC1_IN3

Kateri pin je to? PC2.

Preglejte, kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
10bit, od 0 do 1023,

12bit, od 0 do 4095, 

14bit, od 0 do 16383. 
 
Komentar: Vse je delovalo kot pričakovano, večjih težav ni bilo
