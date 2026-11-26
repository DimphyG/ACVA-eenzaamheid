# Leefbaarheid en eenzaamheid in Amsterdam Zuid en Zuidoost

Groepsonderzoek voor Academische Vaardigheden en Onderzoekspracticum (AcVa deel 2), Doorstroomminor Sociaalwetenschappelijk Onderzoek, Hogeschool van Amsterdam, 2026-2027.

**Groep:** Ali, Dimphy, Monica Hoekstra, Tim van Wissen
**Docent:** Chantal Schouwenaar

## Onderzoeksvraag

In hoeverre hangt de leefbaarheid van een buurt samen met het percentage eenzame volwassenen, in de stadsdelen Amsterdam-Zuid en Amsterdam-Zuidoost?

| Rol | Variabele | Bron |
|----|----|----|
| Afhankelijke variabele | Eenzaamheid: % eenzame volwassenen per buurt, 2024 | Gezondheidsmonitor Volwassenen en Ouderen 2024 (GGD'en/CBS/RIVM), CBS-tabel 50150NED |
| Onafhankelijke variabele | Leefbaarheidsscore per buurt, 2024 | Leefbaarometer 3.0, meting 2024 (ministerie van BZK) |
| Controlevariabele | Gemiddelde WOZ-waarde van woningen per buurt, 2024 | CBS, Kerncijfers wijken en buurten 2024 |

Eenheid van analyse: de buurt. In de analyse zitten 102 buurten (64 in Zuid, 38 in Zuidoost).

## Aan de slag

1. Open `RBasisDataInladen.Rproj` in RStudio.
2. Installeer de pakketten (één keer per computer), in de Console:

   ``` r
   install.packages(c("tidyverse", "readxl", "rmarkdown"))
   ```

3. Open `analyse.Rmd` en kies **Run → Run All**, of knit het bestand met Cmd/Ctrl + Shift + K.

## Bestanden

| Bestand | Wat is het |
|----|----|
| `analyse.Rmd` | Alle code: inladen, koppelen, grafieken, tabellen en toetsen |
| `analyse.html` | Het geknitte resultaat van `analyse.Rmd`: download en open in je browser |
| `data/50150NED_UntypedDataSet_20261119121801.csv` | Eenzaamheid per buurt (CBS StatLine, gedownload 19-11-2026) |
| `data/leefbaarometer_buurten_2002_2024.csv` | Leefbaarheidsscores per buurt (Leefbaarometer, gedownload 25-11-2026) |
| `data/kwb2024.xlsx` | Kerncijfers wijken en buurten 2024 met de WOZ-waarde (CBS, gedownload 25-11-2026) |

De overige bestanden (kittens, midwest, `Toetsen_t_en_z.Rmd`, `Basis_Data_Inladen.Rmd`, `Les 1 R- test.R`) zijn lesmateriaal van Statistiek 2 en horen niet bij het onderzoek.

De volledige Leefbaarometer-download (`open-data-leefbaarometer-meting-2024.zip`, 511 MB) staat niet op GitHub omdat hij te groot is. Hij is te downloaden via leefbaarometer.nl.

## Software

R 4.6.2 met de pakketten tidyverse en readxl.
