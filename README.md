## Innehållshantering för jobtechdev.se via Github
### Konto
För att uppdatera innehåll på jobtechdev.se behöver du ha ett användarkonto på Github, det skapar du här: 
https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home  

Ditt konto behöver ha åtkomst till Github organisationen Jobtechdev-content, https://github.com/Jobtechdev-content), för behörighet kontakta Mats Löfstrand eller Ulrika Häggqvist  

### Vad ska jag tänka på
För att sidan ska vara enhetlig finns några få åtaganden som behöver följas. 

* Innehållet behöver finnas på både engelska och svenska. Anledningen är att vi har en stor del av våra besökare som inte är svensktalande. Det innebär alltså att det behöver finnas två .md filer
*	Innehållet behöver ha en koppling till arbetsmarknaden 
*	Använd de mallar som finns, om det finns förbättringsförslag till mallarna så tar vi gärna emot dem. 

### Skapa / ändra innehåll
Hur gör jag då för att skapa innehåll?
* Gå till https://github.com/Jobtechdev-content
*	Välj eller skapa det repo som skall innehålla texten
*	Välj develop i rulllisten
* Välj det repository vars innehåll du vill uppdatera.
* Om inte .md filen du vill uppdatera redan finns:
  *	Öppna filen Mallxxx.md genom att klicka på ikonen som ser ut som en penna och kopiera innehållet.
  *	Klicka på den gröna knappen Add a README.
  *	Klistra in innehållet från mallen, och lägg till ditt eget innehåll.
  *	Glöm inte att namnge filen, och klicka på Commit new file.
*	Om .md filen du vill uppdatera redan finns:
  *	Klicka på den fil du vill ändra i
  *	Klicka på pennan, gör de ändringar som behövs.
  *	Klicka på commit changes
*	Kontrollera din fil för att kontrollera att allt ser ok ut, behöver du ändra något så klicka på ikonen som ser ut som en penna igen.
*	När du är nöjd med innehållet, klicka på Pull request i menyraden och sedan på New pull request. Ändra base: till master och compare: till develop. Skriv in en titel och kommentar, klicka på Create pull request, klicka sedan på Merge pull request och sedan på Confirm merge.

### Lägga till bild
Hur lägger jag in bilder i mitt innehåll?

*	Om det inte redan finns en mapp för bilder i repot, behöver du börja med att skapa en. Det gör du såhär:
  *	Klicka på Add file
  *	Välj Create new file
  *	I rutan för filnamnet skriver du vad din mapp ska heta, förslagsvis Img, avsluta namnet med / 
  *	För att du skall kunna spara mappen, behöver det finnas en fil i den.  Så skriv in xx.md efter / i rutan för filnamn.
  *	Scrolla ner och se till att commit directly to the develop branch är förvalt
  *	Klicka sedan på gröna knappen Commit new file, nu finns det en mapp som heter img och innehåller en tom .md fil.

*	Nu är det dags att lägga till din bild i mappen.
  * Klicka på mappen img ( eller vad du döpte den till)
  * Klicka på Add file, välj Upload files
  * Välj din fil och klicka sedan på Commit changes

* För att din bild skall visas, behöver du lägga in följande, i det dokument där du vill ha bilden. 
  Se exempel nedan.
       
  ``![Vad bilden visar](https://github.com/Jobtechdev-content/"ditt repo"/blob/master/img/"bilden".png?raw=true)``
     
*	Klicka på commit changes
*	Kontrollera din fil för att kontrollera att allt ser ok ut, behöver du ändra något så klicka på ikonen som ser ut som en penna igen.
*	När du är nöjd med innehållet, klicka på Pull request i menyraden och sedan på New pull request. Ändra base: till master och compare: till develop. Skriv in en titel och kommentar, klicka på Create pull request, klicka sedan på Merge pull request och sedan på Confirm merge.


När nytt innehåll är skapat behöver du maila till Ulrika (perui) eller Mats (lofms) gärna båda, mailet behöver innehålla:

*	En kort beskrivning behöver finnas om det gäller ett projekt eller ett API.
Beskrivningen skall vara på både engelska och svenska.
*	Vi behöver också veta vilket ”namn” ni vill ha i vänstermenyn (projekt och APIer)
Tänk på att ha ett så kort ”namn” som möjligt








