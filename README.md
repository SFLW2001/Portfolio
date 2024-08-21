In deze README kunt u de toelichting van elk project dat in deze github repository staat vinden.
Al deze programmas zijn in python geschreven.

**Chat_program**:
Dit programma heb ik voor de lol voor mijn huis geschreven. Ik heb dit gedaan omdat ik meer wilde leren over hoe servers en clients met elkaar communiceerde.
Het server gedeelte van dit programma stond altijd aan op een raspberry pi met wifi. Het client gedeelte van het programma had iedereen op zijn computer staan, dit gedeelte is geschreven met tkinter om het een simpele maar handige interface te geven.
Tijdens dit project heb ik niet alleen geleerd hoe ik kan zorgen dat clients met elkaar kunnen communiceren via een server maar ook threading mogelijkheden van python waardoor er een wereld voor me open ging. Uiteindelijk is gebleken dat dit programma
toch redeleijk praktisch is geweest omdat iedereen dit toch altijd open had op zijn computer en niet iedereen had altijd zijn telefoon bij de hand waardoor naar iedereen gecommuniceerd kon worden dat het eten klaar was waar het uiteindelijk ook het meeste voor gebruikt is

**IQIP automation project**:
Tijdens het 3e jaar van mijn opleiding heb ik samen met een groepje een project moeten doen voor een bedrijf dat IQIP heet, dit bedrijf houd zich bezig met het maken van 'hydrohammers', heipalen voor het aanleggen van bijvoorbeeld wind molens op zee.
We moesten voor dit bedrijf hun calibratie systeem dat kan meten hoe veel energie er vrij komt tijdens elke slag van de heipaal, dit doen ze door middel van 2 sensoren die precies 35mm +- 0.2mm uit elkaar staan. Er moest dus tijdens de calibratie gezorgd worden dat 
de sensoren ook daadwerkelijk op deze afstand van elkaar zaten. Ik was tijdens dit project verantwoordelijk voor het programmeren van de elektronica en een interface die de data kon aflezen op de computer. Helaas kan ik de code van het eerste, de programma's van de
elektronica hier niet uploaden omdat dit niet mag van IQIP maar zal ik hier toelichten wat het programma ongeveer was. Het systeem bestond uit de 2 inductieve sensoren, een steppermotor die vast zat aan tandwielen en een controlbox, al deze componenten waren aangesloten
op een raspberry pi pico die weer was aangesloten op een computer met de interface die u kunt vinden in deze repository. Wanneer de start knop werd ingedrukt begon de stepper motor een metalen blok aan te drijven die langs de sensoren ging. Wanneer deze sensoren een
hoog signaal aangaven werd de tijd wanneer dit gebeurde geregistreerd, hetzelfde gebeurde daarna bij de tweede sensor waarna de tijd tussen de 2 activaties berekend werd. Samen met de tijd, het aantal rotaties van de steppermotor en de tandwiel verhoudingen werd dan de
afstand tussen deze 2 sensoren berekend en doorgevoerd naar de computer waar het gelezen kon worden door de interface. Ditzelfde process was ook mogelijk voor een setup van vier sensoren.
Ik heb tijdens dit project veel geleerd over het aansturen van elektronica via python en het ontvangen van data en dit weer omzetten tot iets leesbaars om te laten zien op de computer of the exporteren naar een extern bestand.

**Turff namaak**:
Vrienden van mij hadden geen turff tablet in huis voor het bijhouden van hun bierconsumptie en hadden ook geen zin om hier geld voor te betalen, buiten dat waren ze ook niet technisch. Toen kwam ik met het idee om het turff systeem voor ze na te maken zodat ze het toch
nog thuis konden gebruiken. Het ziet er natuurlijk niet zo mooi uit als het echte turff systeem maar het werkt vrijwel hetzelfde. Tijdens dit project kon ik mijn kennis van classes in python ook echt toepassen in een project en heb ik ook het gevoel dat ik hier erg veel
van geleerd heb. Daarnaast heb ik tijdens dit project ook veel geleerd over het gebruiken van mySQL en hoe dit goed geintegreerd kan worden in python. Ik had voor dit project al wat kennis van mySQL maar ik heb het gevoel dat ik het door dit project helemaal onder de knie
heb gekregen. Naast dat het een leuk project was om te maken hebben mijn vrienden nog steeds een raspberry pi in hun huis hangen met dit programma er op en hebben ze er erg veel aan gehad zonder het geld voor de turff uit te geven.

**Verdere ervaring**:
Tijdens mijn stage bij Inholland applied sciences lab heb ik een systeem gecreëerd die de data van verschillende sensoren in de Inholland wind tunnel kan lezen. Om dit te doen zijn alle sensoren aangesloten aan een arduino uno waar de data werd omgezet in een leesbaar
formaat voor de computer. Daarna werd deze data doorgestuurd naar een labview programma op de computer waar alle data makkelijk in grafieken af te lezen was en waar het ook opgeslagen kon worden in excel bestanden. Helaas staan deze bestanden op de servers van de
hogeschool waar ik op dit moment niet bij kan in verband met de vakantie. Dit is het enige project waar ik ook andere talen zoals C++ en labview heb gebruikt en ik zou kunnen zeggen dat ik redelijk comfortabel ben in deze talen maar natuurlijk niet zo goed als ik in 
python ben
