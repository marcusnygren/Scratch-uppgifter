# Bug Race (tillägg)

Du har redan ett fungerande spel där du styr en skalbagge som springer runt en bana. Målet med spelet är att undvika att hamna utanför banan, då blir det Game Over. Men hur vinner du spelet?


## Tillägg 1: Mållinje för att vinna spelet

För att kunna vinna spelet behöver du en mållinje för banan och ett skript som säger att du vinner spelet när skalbaggen rör vid mållinjen. Det liknar ditt skript för att det blir Game Over när skalbaggen rör vid det gröna gräset.


  ![image alt text](image_0.jpg)

2. Skapa ett VILLKOR för skalbaggen: **om** skalbaggen rör vid färgen gul betyder det att den har nått mållinjen och **då** vinner du spelet. (Har du glömt hur du ska göra? Titta på ditt skript för Game Over.)

4. Lägg det nya i din **för alltid**-LOOP. Så här kan det se ut:

  ![image alt text](image_1.jpg)


## Tillägg 2: Flera spelare

Nu har du ett spel för en spelare. Men det kan vara roligt att spela flera – eller spela med två händer! Om banan är tillräckligt bred kan du lägga till en skalbagge eller något annat djur och låta dem tävla mot varandra om vem som kommer först i mål.

![image alt text](image_2.png)

1.  Börja med att lägga till en ny sprajt. Välj fritt i biblioteket eller KOPIERA skalbaggens sprajt om du vill att två skalbaggar tävlar mot varandra. Ändra storlek så att båda får plats på banan.

På så sätt behöver du inte skapa samma skript en gång till. Du kopierar genom att högerklicka överst på skriptet, välja kopiera, och dra till den nya sprajten.  Nu gör båda sprajtar samma sak!

  ![image alt text](image_3.jpg)

3. Du behöver ändra skripten för att styra sprajten så att inte båda ska styras med vänster- och högerpil. Välj i rullistan för **"när _ trycks ned"**, till exempel tangenterna A och D.


  ![image alt text](image_4.jpg)

  **Testa spelet!** Nu kan du styra båda sprajtar. Men vad händer när en av dem hamnar utanför banan?

5. Om du vill kunna tävla om vem som kommer först i mål, kan det inte bli Game Over när en spelare hamnar utanför banan. Istället kan du t ex välja att sprajtarna säger "Aj!" och hamnar tillbaka på sin startposition. Så här kan det se ut då:

  ![image alt text](image_5.jpg)

**Testa spelet!** Om det buggar och någon sprajt säger "Mål!" för tidigt kan det bero på att färgen gult finns i den nya sprajten. Testa att ändra färg då.


## Tillägg 3: Ändra banan till en labyrint

Eftersom skriptet för sprajtarna bara känner av om de rör sig på grön färg, och inte hur själva banan ser ut, är det enkelt att byta ut banan. Du kan till exempel göra en labyrint som bakgrund istället.

![image alt text](image_6.png)

1. Tryck på din SCEN och gå till fliken för BAKGRUNDER. Välj **Rita ny bakgrund**.


  ![image alt text](image_7.jpg)

3. Gör en labyrint genom att dra upp flera vita rektanglar på den gröna bakgrunden, eller rita själv med penseln. Tänk på att banan behöver vara tillräckligt bred för att kunna spela!


## Utmaning: Flera banor

Kan du skapa skript som **byter scenens bakgrund** när en spelare kommer i mål – så att spelet består av flera banor?