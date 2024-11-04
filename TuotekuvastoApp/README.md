ASP.NET Core -pohjainen tuotekuvasto sovellus


Keskeisinä komponentteina:

"HomeController.cs", jossa tapahtuu sovelluksen päätoiminta eli hakee tuotetiedot ja näyttää ne käyttäjälle.
"products.json", jossa on tuotetiedot JSON-muodossa.
"Product.cshtml", jossa muutetaan tuotetiedot HTML-muotoon käyttäjän nähtäväksi.


Vuorovaikutus:

"HomeController.cs" hakee tuotetiedot "products.json" -tiedostostaja, purkaa ne metodin avulla (GetProducts). 
Tämän jälkeen nämä haetut tiedot lähetetään "Product.cshtml" view:iin joka muuttaa tuotetiedot HTML-muotoon 
käyttäen eri HTML-elementtejä kuten kuvia, otsikoita ja kuvauksia, jolloin käyttäjä näkee ne selkeästi.