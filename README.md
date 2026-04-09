### Informatik-projekt CO2 Måler

# Problemformulering

Hvordan kan vi være med til at måle CO2-nivueaet i vores klasse? Vi regner med, at lave en CO2-måler der kan fortælle (via en buzzlyd), når klasseværelsets CO2-niveau er for højt. Derudover vil måleren også have en skærm, der viser hvor højt CO2-niveauet er. Disse CO2-målinger skal kunne eksporteres til excel, hvor man derefter kan lave en graf over den opsamlede data. 

# Flowchart

Nedenstående har vi vedhæftet vores første iteration af flowchart:

<img width="179" height="338" alt="Skærmbillede 2026-03-12 094041" src="https://github.com/user-attachments/assets/3f23672f-7db8-4cc8-af37-2c5e62b5d98e" />

Sidste iteration (simplificering) grundet tekniske problemer samt ændringer:

<img width="214" height="326" alt="image" src="https://github.com/user-attachments/assets/6ce59764-3fb6-438f-aaf9-3d81d13cb6c6" />


# Valgte dele

Vi har valgt at benytte os af en arduino uno, co2 måler, og en lcd skærm samt nogle kabler, der kan forbinde det hele. 


# 3D-modellering og printning



# Kodeprocessen


<img width="437" height="143" alt="image" src="https://github.com/user-attachments/assets/cda5c675-1774-45c3-a1e2-345a2511b9aa" /> 1


<img width="481" height="161" alt="image" src="https://github.com/user-attachments/assets/a9da46ab-be79-4def-b893-b6f8cc7c726d" /> 2


<img width="256" height="301" alt="image" src="https://github.com/user-attachments/assets/a9b37f8d-719a-46e1-bccb-f2d336fa5efa" /> 3


<img width="137" height="98" alt="image" src="https://github.com/user-attachments/assets/f7f459e4-e116-487d-b4b6-1762449c14e2" /> 4






# Fra arduino til excel - overførsel 

Vha. "realterm" programmet, kunne vi overføre dataen til en tekstfil, da både programmet og vores arduino deler samme baud (115200).

<img width="215" height="193" alt="image" src="https://github.com/user-attachments/assets/fa73783c-1a18-4028-abb4-6bebd88f2e5c" />


der bliver opdateret måling efter måling. Hermed kunne denne tekstfil laves om til en graf:


<img width="841" height="455" alt="image" src="https://github.com/user-attachments/assets/59821fe6-1124-46ac-9bab-84452ea99e48" />





