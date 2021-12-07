# Website design

En ferdig utviklet nettside hostet på Github Pages.

Jeg delte alle de forskjellige elementene inn i forskjellige klasser istede for å "objekt orintere de" som hadde hvert lurere hvis dette var et større prosjekt, men kom til konklusjonen at det ville ikke være nødvendige å generalisere alle classene, helle bare lage individuelle klasser for alle de forskjellige brukområdene.

noen eksempler på noe jeg gjennbrukte er:
## header
´´´html
    <header>
        <h1> <b id="purplify">JR</b> Web Design</h1>
        <ul>
            <li><a id="active" href="/løsning/index.html">HOME</a></li>
            <li><a href="/løsning/about.html">OM OSS</a></li>
            <li><a href="/løsning/services.html">TJENESTER</a></li>
        </ul>
    </header>
´´´

og
## den ekte footeren 
´´´html
    <div class="lol-got-you-footer-the-other-one-is-fake-haha">
        <p>JR Web Design. Copyright &copy; 2021</p>
    </div>
´´´

stort sett alt annet er unikt og ikke generalisert, dette er et bevist valg.


# Design
Jeg har tatt full inspirasjon etter oppgaven fordi klokken er 3 på natten og jeg er ikke alltid like kreativ all tider av døgnet.
Som kritikk til meg selv hadde jeg valgt andre farger neste gang og eventuelt satt opp en font men jeg vet ikke om det ville hvert et bonus poeng på oppgaven.

Jeg valgte å lage unike design på hver av sidene og ble generelt ganske fornøyd med sidene til tross for at klokken nå nærmer seg halv 7 på morgenen.
beholdt temaet og fargene men brukte ikke like mye bilder på alle siden, samt forsøkte jeg å holde de svært minimalistiske.

# Problemer
Jeg hadde ikke så mange problemer med designet av oppgaven, men hadde noen problemer anngående å sette opp Github Pages, spessielt fordi linkene mine må referes på annen måte i github pages fordi det må via repositoriet. 
f.eks:
### I **min** kode
\\\html
        <ul>
            <li><a href="/løsning/index.html">HOME</a></li>
            <li><a href="/løsning/about.html">OM OSS</a></li>
            <li><a href="/løsning/services.html">TJENESTER</a></li>
        </ul>
\\\

Dette går på min maskin fordi den finner filene på riktig sted. Men Github Pages må refere via et bestemt directory i Github Pages. [artikkel på det](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source)
For å løse dette måtte jeg flytte alle filene til Root directoriet på main-branchen på Github og re-refere til de riktige filene.

### sånn her
\\\html
        <ul>
            <li><a href="/website-page-design/index.html">HOME</a></li>
            <li><a href="/website-page-design/about.html">OM OSS</a></li>
            <li><a href="/website-page-design/services.html">TJENESTER</a></li>
        </ul>
\\\

Dette problemet var ikke vanskelig å løse men repositoriet ser litt mer rotete ut nå. 🤨

