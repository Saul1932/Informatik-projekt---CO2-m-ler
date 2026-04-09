### Informatik-projekt CO2 Måler

# Problemformulering

Hvordan kan vi være med til at måle CO2-nivueaet i vores klasse? Vi regner med, at lave en CO2-måler der kan fortælle (via en buzzlyd), når klasseværelsets CO2-niveau er for højt. Derudover vil måleren også have en skærm, der viser hvor højt CO2-niveauet er. Disse CO2-målinger skal kunne eksporteres til excel, hvor man derefter kan lave en graf over den opsamlede data. 

# Flowchart

Nedenstående har vi vedhæftet vores flowchart:

<img width="179" height="338" alt="Skærmbillede 2026-03-12 094041" src="https://github.com/user-attachments/assets/3f23672f-7db8-4cc8-af37-2c5e62b5d98e" />

# Valgte dele

Vi har valgt at benytte os af en arduino uno, co2 måler, knap, og en lcd skærm samt nogle kabler, der kan forbinde det hele. 


### 08-04-2026
vi har finpusset på vores kode den er utrolig tæt på at være færdig
vi har yderligere lavet og printet boxen til vores arduino


# Fra arduino til excel - overføresel 

Vha. "realterm" programmet, kunne vi overføre dataen til en tekstfil, da både programmet og vores arduino deler samme baud.

<img width="215" height="193" alt="image" src="https://github.com/user-attachments/assets/fa73783c-1a18-4028-abb4-6bebd88f2e5c" />


der bliver opdateret måling efter måling. Hermed kunne denne tekstfil laves om til en graf:


<img width="841" height="455" alt="image" src="https://github.com/user-attachments/assets/59821fe6-1124-46ac-9bab-84452ea99e48" />





