The synthé λ project
====================

 - Clean air (ISO class 1) [KOACH](http://www.koken-ltd.co.jp/english/koach/index.html)
 
 - The [Hydrocycler](http://www.douglasscientific.com/Products/Hydrocycler.aspx)
 
 - Nanoliter dispenser ([BioDot](https://www.biodot.com/))
   - Low-volume PCR: https://www.biodot.com/low-volume-pcr/
   - cost: ?

 - Thermocyclers with flat blocks:
   - ABI's [ProFlex](https://www.thermofisher.com/jp/en/home/life-science/pcr/thermal-cyclers-realtime-instruments/thermal-cyclers/proflex-pcr-system.html) PCR System can be equipped with flat blocks.
     - cost: a few MMM.
   - Eppendorf's [Mastercycler nexus](https://online-shop.eppendorf.com/OC-en/PCR-44553/Cyclers-44554/Mastercycler-nexus-PF-14698.html) has a "Flat" and a "Flat eco" variant with flat block.
     - cost: ?

 - [Opentrons](https://www.opentrons.com/) ?

----
Notes:

Costs indicated in MMM ([mythical man-months](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)), with _[Nosemetrical](https://fr.wikipedia.org/wiki/Wikip%C3%A9dia:Pastiches/Pifom%C3%A8tre)_ adjustment.

Not for us, but look cool:
  [miniPCR](https://www.minipcr.com/products/minipcr/) (standard 200 µL tubes only),
  [the Bento Lab](https://www.bento.bio/) (standard 200 µL tubes only),
  [On Deck Thermal Cycler](http://www.inheco.com/products/lab-automation/thermal-cycler.html) (384-well plates maximum).

Only 43 hexamers are absent from the genome sequence of the Phage λ.

```
$ Rscript -e 'sum(Biostrings::oligonucleotideFrequency(Biostrings::readDNAStringSet("lambda.fa"), 6) == 0)'
[1] 43
```
