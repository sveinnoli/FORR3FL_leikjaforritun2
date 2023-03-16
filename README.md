# Leikjaforritun 2

## Skilaverkefni 1

### Hlutverk Animation, animator og state machine
Animation er hreyfing einhvers hlut sem gefur því "líf" t.d. að hreyfa einhvern hlut frá einu staðsetningu til aðra. 
Animator er notað í unity til að höndla animations clips og í raun og veru states og breytir milli animations eftir hvaða state það er í með færibreytum t.d. ef þú ert með karl og hann hefur states "idle", "walking", "running" og "jumping" þá er hægt að skipta milli þessi state og breyta hvaða animation er að keyrast eftir því hvað hann er að gera. Og state machine er notað til að höndla hvar hluturinn er að gera, eins og fyrri dæmið ef þú ert með karl að hlaupa þá er hægt að segja að hann er í "running" state og ef hann er að hoppa þá hefur hann í raun og veru 2 states "jumping" og "falling" það er gagnlegt til að t.d. koma fram að þú getur ekki hopað endarlaust og aðeins leyft að hoppa ef hann er ekki í "jumping" eða "falling" state.

[Myndband af virkni](https://youtu.be/TiZ071Lra0c)