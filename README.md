# NLP

# Mis on tehtud?
Kõike on võimalik ka koodina näha failides: 1-Data-Scraping-&-Cleaning.ipynb
- Laen alla data vastavalt Nasdaqi veebilehelt kahe parameetri järgi(ISIN ja kuupäev) kasutades veebikraapimist(võib olla ükskõik milline börsifirma)
- Muudan PDFid .txt failideks lokaalselt
- Moodustan dataframe ja lisan dataframe teksti sisse(tekstifailide tekst)
- Puhastan teksti(2 meetodit on sellejaoks)
- Moodustan document-term-maatriksi ja näen sõnasagedusi.
- picklen ehk salvestan .pkl formaadis andmed, et saaks edaspidi kiiremini kätte

Kõike on võimalik ka koodina näha failides: 2-Exploratory-Data-Analysis.ipynb

- top 15 sõna tekstides
- millised on unikaalsed sõnad ja kui palju neid on.
- Defineerisin ESG sõnad ära (nt G ehk government iseloomustavad sõnad G =['advocacy', 'bribery', 'compensation', 'competitive', 'corruption', 'divestment', 'fraud', 'gri', 'independent', 'justice', 'stability', 'stewardship', 'transparency']

Kõike on võimalik ka koodina näha failides: 3-Topic-Modelling.ipynb

- LDA mudeli kasutamine ja topicu modelleerimine
- sõnade elimineerimine ja proovimine LDA mudeli tuunimist - 2 topicuga, 3 topicuga.

Kõike on võimalik ka koodina näha failides: 4-TF-IDF.ipynb

-Importisin Stanfordi ülikooli poolt tehtud glove mudeli, mis sisaldab sõnu vektoresituses ja nad on semantilises sarnasuses omavahel(sõnade vaheline kaugus)
-Koosinuse põhjal arvutasin välja kõikide vektoride sarnasused. Kahe vektori sarnasus on siis üks punkt kahe vektori vahel(arvutus käib koosinuse nurga põhjal.
-Eelprotsessisin dokumendid(börsitekst) ja minu ESG sõnad
-puhastasin
-tokeniseerisin
-Ehitasin TF-IDF mudeli, mis arvutab sarnasusskoorid antud tekstidele ja etteantud ESG sõnadele ning väljastab ka kõige sarnasemad sõnad

# Uurimisküsimused: mida me tahame teada?
Magistritöös uuritakse, kas tekstikaeve tehnikate rakendamine vähemstruktureeritumate
ettevõtete aruannetele on mõistlik meetod börsil noteeritud ettevõtete keskkonna-,
sotsiaal- ja ühingujuhtimisega(ESG) seotud tegevuste/näidikute hindamiseks.
## Alam-uurimisküsimused:
- Millised võtmesõnad on aruandes, mis toetavad ESG?
- Kui efektiivne on börsi ettevõtete aruannete slaidiesitluste analüüs kasutades
tekstikaevet?
# Uurimisobjekt
Uurimistöö keskmes on börsiettevõtete vähemstruktureeritumad aruanded. Millised on
aruandes võtmesõnad, ESG suuremad indikaatorid ning kuidas need mõjutavad ettevõtte
käekäiku.

Keskkonna-, sotsiaal- ja ühingujuhtimine viitab kolmele keskmisele tegurile ettevõttesse või
ettevõttesse tehtud investeeringu jätkusuutlikkuse ja ühiskondliku mõju mõõtmisel. Need
kriteeriumid aitavad paremini kindlaks määrata ettevõtete tulevast finantstulemust.

# Töö eesmärk

Töö eesmärk on aru saada, kas ja kuidas on võimalik tekstikaevet rakendada ESG
näidikute/tegevuste tuvastamisel/analüüsimisel ettevõtete vähemstruktureeritud
aruannetele.

# Töö ülesehitus

Magistritöö on jagatud neljaks suuremaks osaks.
Esimeses osas kirjeldatakse kasutatavaid tööriistu ja mudeleid.
- Fundamentaalteooria ja kirjanduse analüüs
Teises osas kirjeldame andmeid.
Magistritöö kolmandas osas rakendame mudelid antud andmetele ja kirjeldame mudelite
tehnikaid, parameetreid, arhitektuuri.
- Metodoloogia rakendamine
o Andmete kogumine
o Andmete eeltöötlus
o Mudeli(te) ehitamine ja treenimine
Neljandas osas kirjeldatakse töö tulemusi ja analüüsitakse vastavalt.
- Tulemuste presentatsioon ja valideerimine 
