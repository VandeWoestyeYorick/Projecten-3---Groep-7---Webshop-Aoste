# Welkom bij de git repo van Groep 7 voor projecten 3 E-business.


## Clonen van het project
Voor het volgende stappen plan word verondersteld dat je met Acquia dev desktop werkt.

 1. Clone de repository op een plaats waar je het kan terug winden
 2. In de  folder van de repo staat de mysql dump als "backup.mysql.gz".
 3. Gebruik deze dump om in acquia dev een nieuwe site te importeren op basis van local codebase( de git repo) en het starten van een dump file.
 4. Eens de site aangemaakt is in acquia dev, gebruik de drush console om composer install uit te voeren in de local codebase folder, hiermee worden de core modules van drupal geïnstalleerd( dit kan een tijd duren)
 5. In de sites\default map hernoem  "default.settings.php" naar "settings.php". pas nu in de "settings.php" de de hash salt aan. $settings['hash_salt']  Zonder de Salt zal de site niet werken en met een verkeerde salt kan je niet inloggen. De salt is om veligheids redenen terug te vinden in het "gevoelige gegevens" bestand van de ingediende opdracht zip.
 6. start de site op en zie of dat het werkt
 7. gebruik de login gegevens die geïncludeerd werden in de ingediende opdracht zip om op /user/login in te loggen.

## De afbeeldingen importeren
de afbeeldingen werden niet toegevoegd aan GitHub omdat de sites\default\files folder vol word gezet met andere lokaal gegeneerde bestanden

 1. vind De "files" zip die toegevoegd werd aan de opdracht zip.
 2. pak deze uit zodat de inhoud terecht komt in sites\default\files 
 3. de volgende mappen en bestanden zouden nu in sites\default\files moeten staan:
    \2020-11, \2020-12, \Coupons, aoste_logo_0.png,favicon-32x32_0.png

Het kan zijn dat je een 'drush cr' uit te voeren om de miniaturen en dergelijke van de afbeldingen te genereren op de site.

### Bijkomende hulp
neem contact om met eckhart.arents@student.hogent.be voor technische bijstand om de repo aan de praat te krijgen