Jag valde TOTP istället för SMS eftersom koden aldrig lämnar telefonen, den skapas direkt i appen.
SMS skickas istället över mobilnätet, vilket gör det sårbart om någon SIM-kapar mitt nummer eller avlyssnar trafiken.TOTP har inte dom svagheterna.
Men mot phishing är TOTP inte bättre, skriver jag in koden på en falsk sida spelar det ingen roll varifrån den kom.
Ändå är TOTP ett bättre val än SMS, och SMS är bättre än att sakna en andra faktor helt.

Jag valde fem försök eftersom en användare ibland klantar till sig, det har hänt mig också, så två försök hade varit för lite.
Samtidigt hade fler än fem försök gett en angripare för många chanser att gissa sig till lösenordet. Fem är en vanlig kompromiss som sätter stopp för gissningar utan att straffa vanliga misstag för hårt.

Femton minuter kändes rimligt av samma anledning. För kort tid gör att en angripare bara väntar ut låsningen och testar igen.
För lång tid kan missbrukas, en angripare kan skriva fel lösenord med flit på någon annans konto bara för att låsa ute den riktiga användaren.
Femton minuter är kort nog att inte vara jobbigt för en vanlig användare, men lång nog för att stoppa brute force.