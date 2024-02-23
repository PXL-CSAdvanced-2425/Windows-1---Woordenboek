# Woordenboek

![Afbeelding met tekst, schermopname, Lettertype, nummer Automatisch
gegenereerde beschrijving](./images/media/image1.png){width="2.2875in"
height="2.1930555555555555in"}Schrijf een toepassing om de Nederlandse
vertaling van Engelse specifieke technische ICT-benamingen op te slaan
en op te zoeken en eventueel zelf te vertalen. De vertaling wordt in een
tekstbestand bijgehouden. Voeg eventueel zelf een tekstfile toe in je
toepassing.

![Afbeelding met tekst, schermopname, software, scherm Automatisch
gegenereerde
beschrijving](./images/media/image2.png){width="3.896382327209099in"
height="2.7040004374453193in"}

De toepassing omvat 3 vensters en een statische klasse.

**1 Klasse Wachtwoorden.cs**

De statische klasse omvat 2 publieke List\<\> waar respectievelijk de
Nederlandstalige termen en de Engelstalige termen in worden bijgehouden.
Je kan ook kiezen voor een dictionary.

**2 WindowsWoordenboek**

Met de opdrachtknop *btnToevoegen* kan je een specifieke benaming in het
Engels en de corresponderend Nederlandstalige term toevoegen. De lijst
van toegevoegde woorden worden links in een listbox *LbxWoorden*
toegevoegd (ook aan je List\<\>).

Met de opdrachtknop *btnVerwijderen* worden de termen uit de Listbox en
de List\<\> verwijderd.

![Afbeelding met tekst, schermopname, software, scherm Automatisch
gegenereerde
beschrijving](./images/media/image3.png){width="4.771829615048119in"
height="2.689623797025372in"}

**3 WindowsZoeken**

Het menu bestaat uit *Bestand:* *Zoeken* (idem opdrachtknop Zoeken) -
*Sluiten* (sluit het venster) en *Info.*

De opdrachtknop *BtnZoeken* geeft random een Engelse benaming*.* Geef de
vertaling in het tekstvak *TxtNederlands* en met de opdrachtknop
*BtnControle* wordt gecontroleerd of de Nederlandse vertaling correct
is.

![Afbeelding met tekst, schermopname, scherm, software Automatisch
gegenereerde
beschrijving](./images/media/image4.png){width="4.209946412948382in"
height="3.1313648293963254in"}

![Afbeelding met tekst, schermopname, Lettertype, lijn Automatisch
gegenereerde
beschrijving](./images/media/image5.png){width="3.167361111111111in"
height="1.4368055555555554in"}

![Afbeelding met tekst, schermopname, Lettertype, lijn Automatisch
gegenereerde
beschrijving](./images/media/image6.png){width="1.5416666666666667in"
height="1.3854166666666667in"}

**4 WindowsOver**

Gebruik de informatie uit je bestand AssemblyInfo.cs (zie Project
Properties) om je infovenster te voorzien van:

-   Productname

-   Version

-   Copyright

-   Companyname

-   Description.

![Afbeelding met tekst, schermopname, Lettertype, software Automatisch
gegenereerde beschrijving](./images/media/image7.png){width="6.3in"
height="3.5506944444444444in"}
