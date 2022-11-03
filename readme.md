![](images/partiledere.jpg)

# Valgdata 2022

Dette repo indeholder data for folketingsvalget 2022.

Data er høstet fra forskellige kilder.

### Bidrag:

Du er velkommen til at bidrage til dette repo så vi kan skabe en samlet datakilde vedrørende Folktingsvalget i 2022.

# Data

I data folderen ligger der følgende data:

### Valgresultater

`data/valgsteder.csv` indeholder valgresultaterne på valgstedsniveau.

`data/personlige.csv` indeholder kandidaternes personlige stemmetal på valgstedsniveau.

Data er skrabet fra <https://www.kmdvalg.dk/>

Begge filer er tilføjet en masse metadata fra DAWA, der gør det muligt at gruppere på forskellige geografiske niveauer.

### Meningsmålinger

`data/polls.csv` indeholder meningsmålinger for partierne tilbage fra 2010. Data er hentet fra Erik Gahners repo og masseret lidt. <https://github.com/erikgahner/polls>

### Kandidattests

`data/kandidattest.csv` indeholder kandidaternes svar på DR.dk's (der også var Altingets) og TV2.dk's kandidattest.

### Partifarver

`style/colors.R` indeholder farvekoder, der belv brugt af DR.dk for partierne.
