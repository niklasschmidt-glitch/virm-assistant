# VIRM Assistant

VIRM Assistant er en uofficiel browserudvidelse til Virtual Manager, som tilføjer værktøjer direkte på spillets sider.

## Funktioner

- **Træningsmodul:** Planlæg eller generér et træningsprogram, og indstil automatisk overførsel til Virtual Manager.
- **Taktikrotation:** Fordel automatisk taktikker mellem sæsonens kampe ud fra dine egne kriterier.
- **Potentialepoint, karrierepoint og spillerprognose:** Få en dybdegående analyse af en spillers potentiale og potentialeudnyttelse.

VIRM Assistant er udviklet uafhængigt og er ikke tilknyttet, godkendt eller understøttet af Virtual Manager eller spillets udviklere.

## Safari

Safari-udgaven installeres som et userscript ved hjælp af den gratis Userscripts-app.

**[Se installationsguiden og hent den nyeste Safari-udgave](INSTALLATION.md)**

Der findes særskilte versioner til:

- iPhone og iPad
- Safari på Mac

## Support

Fejl, spørgsmål og forslag kan oprettes under [Issues](https://github.com/niklasschmidt-glitch/virm-assistant/issues).

---

# Privatlivspolitik for VIRM Assistant

Senest opdateret: 31. august 2026

## Om VIRM Assistant

VIRM Assistant er en uofficiel browserudvidelse til Virtual Manager. Udvidelsen tilføjer værktøjer til blandt andet træningsplanlægning, taktikrotation og analyse af spillerudvikling direkte på Virtual Managers sider.

VIRM Assistant er udviklet uafhængigt og er ikke tilknyttet, godkendt eller understøttet af Virtual Manager eller spillets udviklere.

## Lokalt gemte data

VIRM Assistant gemmer indstillinger, træningsprogrammer, taktikrotationer, analyser og midlertidige arbejdsdata lokalt i brugerens browser. Disse oplysninger bruges til at levere udvidelsens funktioner og bevare brugerens opsætning mellem sidevisninger og browsergenstarter.

De lokalt gemte oplysninger sendes ikke til VIRM Assistants server.

Når brugeren aktivt anvender en funktion, der foretager ændringer i Virtual Manager, kommunikerer udvidelsen direkte med Virtual Managers servere. Denne kommunikation er nødvendig for at udføre den handling, brugeren har valgt, og er underlagt Virtual Managers egne vilkår og privatlivspolitik.

## Aktivitetssignal

Når mindst én Virtual Manager-side er åben, kan VIRM Assistant sende et aktivitetssignal til VIRM Assistants server. Signalet sendes højst én gang hvert femte minut og kun mellem kl. 08.00 og 00.00 dansk tid.

Aktivitetssignalet indeholder kun:

- et tilfældigt sessions-id
- VIRM Assistants versionsnummer
- den anvendte platform, eksempelvis Chrome eller Safari

Sessions-id'et er ikke knyttet til brugerens Virtual Manager-konto og nulstilles, når Chrome genstartes.

Aktivitetssignalet indeholder ikke brugerens navn, mailadresse, loginoplysninger, Virtual Manager-konto, klub, spillere, sideadresse eller andet indhold fra Virtual Manager.

Oplysningerne bruges udelukkende til at beregne anonymiseret statistik over antallet af aktive VIRM-installationer samt fordelingen på versioner og platforme.

## Teknisk behandling

Aktivitetssignalet sendes krypteret via HTTPS til en tjeneste, der hostes hos Cloudflare. Som ved anden internetkommunikation kan Cloudflare behandle tekniske forbindelsesoplysninger, herunder IP-adresse og tidspunkt, med henblik på levering og sikkerhed. IP-adressen indgår ikke i VIRM Assistants aktivitetssignal og bruges ikke af VIRM Assistant til at identificere brugeren.

Aktive sessions-id'er bruges kun til at beregne antallet af aktive installationer. Historiske målinger kan gemmes som aggregeret statistik uden oplysninger om Virtual Manager-konti eller identificerede personer.

## Deling og anvendelse

VIRM Assistant:

- sælger ikke brugerdata
- anvender ikke brugerdata til annoncering
- anvender ikke brugerdata til kreditvurdering eller långivning
- overfører ikke brugerdata til uvedkommende tredjeparter
- anvender kun oplysningerne til udvidelsens beskrevne funktioner og driftsstatistik

Cloudflare fungerer som teknisk tjenesteudbyder for aktivitetssignalet.

VIRM Assistants brug og overførsel af brugerdata overholder Chrome Web Stores politik for brugerdata, herunder kravene om begrænset anvendelse.

## Sletning

Lokalt gemte data kan slettes ved at fjerne VIRM Assistant fra browseren eller rydde udvidelsens lagrede data.

Da aktivitetssignalet ikke er knyttet til en konto eller identificeret person, kan historiske, aggregerede målinger ikke henføres til eller udleveres for en bestemt bruger.

## Kontakt

Spørgsmål om denne privatlivspolitik kan oprettes som en sag på:

https://github.com/niklasschmidt-glitch/virm-assistant/issues
