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


Kõike on võimalik ka koodina näha failides: 3-TF-IDF.ipynb

- Importisin Stanfordi ülikooli poolt tehtud glove mudeli, mis sisaldab sõnu vektoresituses
- Arvutasin välja koosinussarnasuse glove mudeli vektoresituses sõnade vahel
- Eelprotsessisin dokumendid(börsitekst) ja minu ESG sõnad
-  puhastasin
-  sõnestasin
-  eemaldasin stopp sõnad
- Ehitasin hõreda maatriksi, mis sisaldab sarnasusi
- Mudel väljastab sarnasusskoorid dokumendi ja ESG päringu vahel

# Uurimisküsimused: mida me tahame teada?
Magistritöös uuritakse, kas tekstikaeve tehnikate rakendamine vähemstruktureeritumate
ettevõtete aruannetele on mõistlik meetod börsil noteeritud ettevõtete keskkonna-,
sotsiaal- ja ühingujuhtimisega(ESG) seotud tegevuste/näidikute hindamiseks.