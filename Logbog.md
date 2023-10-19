# RoA2023

# 22-08-2023
Lærte at C++ kun compiler én gang, hvilket betyder at du skal deklarere funktioner i toppen, for at kunne bruge dem.
ALDRIG (med undtagelse af ekstremt simple programmer) brug delay(x), da det stopper alt i 'x' antal millisekunder.

# 30-08-2023
Vi fik lavet studypoint opgave med lyskryds vha. en enum samt switchcase. Stepmotoren fik vi til at virke ved at følge guiden Tobias viste os.


# 19-09-2023
Gennemgået interface på JavaCSG og printet nogle test dele ud.

# 22-09-2023
Idag fik vi lavet første del af vores projekt, som går ud på at lave en holder til en maskindel. Dette gjorde vi vha. “hull” metoden i CSG-librariet og 2 cirkler i forlængelse af en rektangel der havde fraktrukket 4 mm for at tildele dem til diameteren på cirklen. Vi fandt ud af, at vi bliver nødt til at lave de 2 nederste cylinder-lignende dele til en adskilt genstand, da vi så kan lægge den på højkant og få vores cylinderform på vores cirkler når vi extruder dem til 3d. Vi har dog en klar idé om hvordan vi vil gøre det nu, hvilket hjælper til næste gang. Derudover fik jeg lavet et repository som vi kan sidde og teste på løbende.

# 26-09-2023
Vi sad på Discord i dag, hvor vi fik extruded vores main body. Vi målte også og fik lavet hængslen i toppen. Målene vi har brugt i dag er grove da de er målt med en tommelstok, og nærmere/mere præcise mål vil blive taget i skolen. 

# 29-09-2023
Endnu en dag med Discord. Vi fik lavet den nederste halvdel af motoren, hvor vi bestemte os for at en rektangel ville give mest mening, i stedet for 2 "cirkler" (pga. plastik beskyttelsen). Derudover fik vi tilføjet de 2 kroge på siden (ved at lave 2 firkanter - 1 på hver side), som plastik beskyttelsen sidder fast på.

# 03-10-2023
Vi sad på Discord igen i dag. Super produktiv dag. Vi fik finpudset den nederste halvdel af vores model, således at den fik afrundede sider frem for at være 100% rektangulære. Dertil fik vi tilføjet motorarmene til figuren. Vi fandt derudover ud af hvordan man kan se en udhulet version af modellen, via "View Wireframe (F11)", hvilket hjælper på mere præcise mål i fremtiden frem for konstante udregninger.

# 06-10-2023
Vi tog over på skolen idag for at få rettet på målene, samt diskutere hvordan vi skal få lavet den nedre del, således at boksen har plads til plastikken. Undervejs fandt vi ud af, at det ville give bedst mening at forskyde "main box". Plastikken er dog stadigt ikke lavet, og ville derfor give mening at lave i weekenden, så vi har tid til at lave boksen + noget kode som hører med til motoren.

# 13-10-2023
Vi startede med at researche omkring motorstyring og forbindelsen af motorer til vores NodeMCU. Efter at have fundet nok viden om driveren og motorerne, gik vi i gang med at implementere styring af vores motorer. Først arbejdede vi med en enkelt motor for at accelerere op og ned i hastighed samt skifte retning, og derefter gentog vi processen for den anden motor.

# 16-10-2023
I dag fik jeg lavet det sidste på vores projekt. Jeg lavede beholderen til motoren ved at lave 4 kugler, hvorefter jeg brugte 'hull' metoden for at få skabt en semi-rektangulær, men samtidigt afrundet boks. Derefter diffede jeg beholderen med et rektangel på tykkelsen 1 mm, for at den skal kunne åbnes. Til sidst upscalede jeg vores motor med 2%, for at den skal få plads, samt diffede den fra beholderen. Der mangler umiddelbart et kliksystem til beholderen på nuværende tidspunkt.
