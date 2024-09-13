# boiler130924

```bash
npm run dev
```

Uppgift för fredagens "Boiler Room" session:
Fortsätta på ert grupprojekt

1. Implementera Local och GitHub strategy:
   ○ Använd Passport.js för att sätta upp både Local och GitHub authentication
   ○ Basera implementationen på veckans code-alongs
2. Lägg till lösenords hashing:
   ○ Implementera bcrypt för säker lösenordshantering i Local strategy
   ○ Uppdatera relevanta delar av koden för att hantera hashade lösenord
3. Implementera SessionStore med connect-pg-simple:
   ○ Installera och konfigurera connect-pg-simple
   ○ Använd PostgreSQL för att lagra sessioner
   ○ Uppdatera er Express-konfiguration för att använda den nya session store
4. Uppdatera användarmodellen:
   ○ Lägg till en email-kolumn i er användardatabastabell
   ○ Uppdatera all relaterad kod för att hantera den nya
   email-fältet
   ○ Säkerställ att CRUD-operationer fungerar korrekt med den uppdaterade
   modellen
5. Implementera validering med express-validator:
   ○ Lägg till validering på all inkommande data i era routes, inklusive det nya e-
   postfältet
   ○ Säkerställ att användarinput är korrekt formaterad och säker
# Boiler-09-13
