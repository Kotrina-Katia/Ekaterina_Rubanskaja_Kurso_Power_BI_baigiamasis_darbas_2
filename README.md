# Ekaterina Rubanskaja Kurso Power BI baigiamasis darbas 2

Šioje ataskaitoje analizuojami 2021 m. „Best Furniture“ duomenys. Ji atspindi įmonės veiklos rezultatus.

## 	Darbo užduotis

  Reikia paruošti įmonės „Best Furniture“ metinės ataskaitos dašbordą.
	Išnagrinėję verslo procesus su įmonės vadovybe, suformulavome šiuos ataskaitų srities reikalavimus:
- Dašbordą sudaro trys lapai:
  1. Tiekėjai ir asortimentas,
  2. Pateikti užsakymai dinamikoje
  3. Užsakymai iš mūsų klientų;
- Palaiko kryžminį filtravimą visuose lapuose, o tai reiškia, kad pasirinkus duomenų dalį viename grafike, kiti bus pertvarkyti;
- Visi grafikai turi aiškius pavadinimus, duomenų žymas ir (pageidautina) legendą;
- Papildomai: lapas su navigacija ir lapas su išvadomis.

	**Tikslas:** Naudojant ataskaitą, nustatyti dažniausias užsakymų atšaukimo priežastis. Yra hipotezė, kad tai prekių trūkumas sandėlyje.

  ---

  Darbas padarytas su Power BI Desktop pagalba. Iš pradžių buvo atsisiųsti ir apdoroti duomenys iš įvairių šaltinių. Į kai kurias lenteles buvo pridėta papildomų stulpelių, o kitos buvo visiškai sukurtos.
	Duomenys pateikiami įvairiais pjūviais, histogramomis, medžio diagramomis, skritulinėmis diagramomis, matricomis, sklaidos diagramomis ir daugiaeilėmis kortelėmis. Kiekviename puslapyje pateikiama navigacija, kad būtų lengviau naršyti.
	Ataskaitoje yra šie puslapiai: "Navigacija", "Tiekėjai ir asortimentas", "Pateikti užsakymai dinamikoje", "Klientų užsakymai" ir "Išvados".

  **Išvados:**

  Tikslas buvo naudojant ataskaitą nustatyti dažniausias užsakymų atšaukimo priežastis. Buvo manoma, kad tai lėmė sandėlio trūkumas.
  
  Norint atsakyti į šį klausimą, buvo sukurtas ataskaitų suvestinė. Puslapyje „Tiekėjai ir asortimentas“ esančioje skritulinėje diagramoje „Dėl atšaukimo atšauktų prekių skaičius“ pateikiamos užsakymų atšaukimo priežastys. Matome, kad dažniausia užsakymų atšaukimo priežastis (62,71 %) buvo prekių trūkumas sandėlyje. Taigi hipotezė buvo patvirtinta. Be to, didelė užsakymų atšaukimo dalis (25,08 %) buvo dėl prastos prekių kokybės. Iš viso to galima daryti išvadą, kad sandėliai turi turėti didesnį atsargų kiekį ir stebėti produktų kokybę.
Remiantis puslapyje „Tiekėjai ir asortimentas“ esančia matrica „Pristatytų ir atšauktų prekių skaičius pagal surinkimą, produktų kategoriją ir atskirą produktą“, maždaug vienas iš trijų užsakymų buvo atšauktas. Tai reikšmingas skaičius. Todėl aukščiau pateikta išvada yra labai aktuali.

  Remiantis tame pačiame puslapyje „Tiekėjai ir produktų asortimentas“ esančia histograma „Pristatytų prekių skaičius pagal tiekėją“, daugiausia užsakymų pateikė tiekėjas „Mebel RU“ (490 užsakymų).
„Tiekėjų ir prekių asortimento“ puslapio „Pristatytų prekių skaičius pagal kolekciją ir kategoriją“ histograma rodo, kad fotelių užsakoma daugiau nei sofų. Atitinkamai 744 užsakymai, palyginti su 614. Populiariausios yra dvi kolekcijos – „Dins“ (379 užsakymai) ir „Space“ (367 užsakymai). Pirmauja „Dins“ sofa (230 užsakymų) ir „Space“ fotelis (208 užsakymai).
„Pajamų pagal pardavimo kanalą“ histograma puslapyje „Pateikti užsakymai dinamikoje“ rodo, kad sėkmingiausias yra nuosavas kanalas best_mebel.ru (13 mln. rublių). Tačiau ir kiti kanalai yra gana veiksmingi.

  Tame pačiame puslapyje „Pristatyti užsakymai pagal laiką“ esančioje histogramoje „Pajamos pagal miestą“ matyti, kad pajamos Maskvoje (27 mln. rublių) yra gerokai didesnės nei Sankt Peterburge (11 mln. rublių).
  
  Tame pačiame puslapyje esančios medžio histogramos „Savaitgalių ir darbo dienų dalis“ ir „Pajamos pagal savaitgalį ir darbo dieną“ rodo, kad pajamos praktiškai nepriklauso nuo to, ar užsakymas buvo pateiktas savaitgalį, ar darbo dieną.
  
  Jungtinėje histogramoje „Prekių nominalios vertės užsakymuose palyginimas su pajamomis dinamikoje pagal mėnesį“ tame pačiame puslapyje „Pateikti užsakymai dinamikoje“ rodo, kad bendra nominali prekių vertė užsakymuose per mėnesį yra didesnė už bendras pajamas ir turi tendenciją didėti. Šį skirtumą galima paaiškinti nuolaidomis ir tuo, kad ne visos užsakytos prekės buvo nupirktos.

  Sudėtinė histograma „Užsakymų skaičius pagal lytį ir amžiaus grupę“ ir sklaidos diagrama „Užsakymų skaičius pagal vyrų ir moterų amžių grupę“ puslapyje „Užsakymai iš mūsų klientų“ rodo, kad moterys vidutiniškai užsako dažniau nei vyrai. Tai taip pat akivaizdu iš medžio histogramos „Užsakymų pasiskirstymas pagal lytį“ tame pačiame puslapyje. Moterys turi 709 užsakymus, o vyrai – 438. Taip pat matyti, kad vyresni nei 30 metų asmenys užsako dažniau nei kiti.
  
  Daugiaeilės kortelės tame pačiame puslapyje „Užsakymai iš mūsų klientų“ rodo, kad medianinės pajamos nuo moterius (29 990 rublių) yra didesnės nei medianinės pajamos nuo vyrus (27 490 rublių). 

  Visos išvados taip pat pilnai ir išsamiai pateikti puslapyje „Išvados“.
