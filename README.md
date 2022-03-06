# e-vinjete #
Elektronski vinjetni cestninski sistem (E-Vinjete) pri predmetu ITA

## Predstavitev domene ##
Obveznost plačila cestnine pri cestninjenju glede na določen čas uporabe cestninskih cest nastane z vstopom vozila do 3.500 kg največje dovoljene mase na cestninsko cesto.
Cestnino plača cestninski zavezanec tako, da pred vstopom na cestninsko cesto kupi evinjeto za ustrezen cestninski razred.

E-vinjeta je na registrsko označbo in državo registracije vozila, katerega največja dovoljena masa ne presega 3.500 kg, ne glede na največjo dovoljeno maso priklopnega
vozila, vezana časovno omejena pravica do uporabe cestninske ceste.

### Izdaja e-vinjet ###
E-vinjete se izdajo za različne cestninske razrede in za dvanajst zaporednih mesecev (letna e-vinjeta), šest zaporednih mesecev (polletna e-vinjeta), en mesec (mesečna evinjeta) ali sedem zaporednih dni (tedenska e-vinjeta).
Za enosledna vozila se lahko uporablja letna, polletna ali tedenska e-vinjeta, za dvosledna vozila pa letna, mesečna ali tedenska e-vinjeta.

# Predstavitev mikrostoritev #
Sistem deluje po treh glavnih mikrostoritvah:
- [Avtentikacija uporabnika (prijava v sistem)](https://github.com/NJersic/e-vinjete/tree/main/microservices/authentication "Avtentikacija uporabnika (prijava v sistem)") ,
- [Nakup in plačilo e-vinjete](https://github.com/NJersic/e-vinjete/tree/main/microservices/nakup "Nakup in plačilo e-vinjete") in
- [Preverjanje veljavnosti e-vinjete](https://github.com/NJersic/e-vinjete/tree/main/microservices/veljavnost "Preverjanje veljavnosti e-vinjete").


