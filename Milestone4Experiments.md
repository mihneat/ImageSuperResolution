
TEORIE: Rularea pe imagini foarte mari nu ofera imbunatatiri asa mari, de-aia PSNRurile sunt asa apropiate. Am rulat ESPCN de pe GitHub pe imaginile din Set5 si am obtinut valori PSNR f apropiate de cele de pe GitHub, foarte mari (in medie 32.84), dar pozele din Set5 sunt foarte mici

Ce am facut pt acest sprint:
- am antrenat manual ESPCN asa cum e in paper
- am incercat sa antrenez ESPCN pe patch-uri RGB in loc de luminanta
- pot sa incerc sa maresc nr de epoci si sa mai schimb learning rates, sau sa mai modific modelul
- urmeaza sa testez o alta functie de loss (VGG19? combo de mai multe loss functions? o sa mai dea bine metrica PSNR sau trebuie sa gasesc alta metrica?)
