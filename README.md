# Alla Faktiskt.se faktagranskningar

Sammanställning av 121 stycken faktagranskningar genomförda 2018 av DN, SVD, SR och SVT på sajten [Faktiskt.se](https://faktiskt.se/).

## Datastruktur: `faktiskt.csv` 

Kolumn | Beskrivning | Datatyp
:------- | :----------  | :----------
`verdict` | Omdöme satt av Faktiskt.se (`ingen` representerar inget omdöme satt) | Lista med ett av följande strängvärden: `helt fel`, `fel`, `mestadels fel`, `delvis sant`, `helt sant`, `oklart`, `helt fel/delvis sant`, `ingen`
`direction` | Riktningen på omdömet | Lista med ett av följande strängvärden: `false`, `true`, `unknown`
`url` | Webbadress till faktagranskningen hos DN, SVD, SR eller SVT | Textsträng

## Vad är Faktiskt.se?

Saxat från hemsidan [Faktiskt.se](https://faktiskt.se/) under juli 2020:

> Faktiskt.se startades med ambitionen att med ett branschöverskridande samarbete motverka desinformation och höja medvetenheten om källkritik under valrörelsen 2018. Vid årsskiftet 2018-2019 lade vi som planerat ned sajten, men granskningarna finns kvar. För att ta del av de artiklar som publicerades i Faktiskt-samarbetet hänvisar vi till våra respektive sajter.
> 
> https://www.dn.se/om/faktiskt/
> https://www.svd.se/om/faktiskt
> https://www.sverigesradio.se/faktiskt
> https://www.svt.se/nyheter/inrikes/17565278
> Tack för alla tips och engagerade kommentarer kring faktakollarna under året!
> 
> Martin Jönsson, Dagens Nyheter
> Fredric Karén, Svenska Dagbladet
> Olle Zachrison, Sveriges Radio Ekot
> Kristian Lindquist, Sveriges Television