# Lithium-ion battery charger

## Šta je litijum-jonska baterija?

Litijum-jonska baterija je vrsta punjivih baterija. Za ovaj tip baterije katoda je sačinjena od
metalnog oksida, anoda od ugljenika dok je elektrolit litijumova so u organskom topivu. Tokom
pražnjenja se litijumovi joni kreću od negativne do pozitivne elektrode, dok se tokom punjenja
kreću u suprotnom smeru.
Koje su prednosti litijum-jonske baterije?
Prednosti ove baterije u odnosu na svoje prethodnike se ogleda u:
• većoj gustini energije
• laganoj masi
• većem nominalnom naponu
• nedostaku potrebe za održavanje(periodičnim pražnjenjem)
• dugom životnom veku

## Gde se koristi litijum-jonska baterija?

Našla je najveću primenu u mobilnoj industriji. Koristi se takođe i u automobilskoj industriji.
### Traženi uslovi zadatka.
Potrebno je projektovati punjač litijum-jonske baterije sa detekcijom napunjenosti baterije.
### Dodefinisanje zadatka.
S obzirom da postoji veliki broj različitih litijum-jonskih baterija mi smo specifično projektovali
punjač koji puni litijum-jonske baterije sledećih karakteristika:
• nominalni napon baterije: 3,7 V (ovaj uslov mora da se podudara)
• kapacitet: 1000 mAh(ovaj uslov ne mora da se podudara) 
• maksimalna amplituda struje punjenja: 1 A(ovaj uslov ne mora da se podudara, ali mora
biti veći ili jednak 1 A)

## Zaštita baterije od preopterećenja.

Jedan od nedostataka litijum-jonskih baterije je njihova osetljivost na preopterećenje u vidu
„prepunjenja“ baterije. Za naš konkretan primer, baterije od 3,7 V se po pravilu puni tako da
dosegne vrednost nominalnog napona od 4,2 V. Vrlo je bitno da, kad se dostigne nominalni
napon baterije od 4,2 V, punjenje prekine. U suprotnom može doći do oštećenja baterije i u
najgorem slučaju do njenog pucanja, što može da izazove curenje baterije pa čak i eksploziju i
time da naruši bezbednost u njenoj okolini. Zato je od velikog značaja projektovati deo kola koji
će bateriju na vreme da prestane da puni.

## Zaštita baterije od prevelike struje punjenja.

Jedna od karakteristika baterije je njena maksimalna struja punjenja. Vrlo je bitno taj prag ne
prekoračiti. U praksi se preporučuje bateriju puniti na upola manjoj amplitudi od maksimalne
dozvoljene. Zato je bitno projektovati deo kola koji će ograničiti struju punjenja na određenu
vrednost.

## Detekcija napunjenosti baterije.

Radi komotnosti i s pretpostavkom da korisnik koji bude koristio uređaj nema pri ruci voltmetar
kojim može da utvrdi da se baterija napunila do kraja projektovan je deo kola koji će korisniku
jasno da da do znanja da li je baterija puna ili se i dalje puni. To je ostvareno pomoću svetleće
diode koja svetli ukoliko se baterija puni a zatim prestane da svetli kad se baterija napuni.
