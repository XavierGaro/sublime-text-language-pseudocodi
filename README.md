Aquests fitxers afegeix el ressaltador del llenguatge Pseudocodi amb la definició empreada per la UOC pel editor Sublime Text 3.

## Instal·lació

### Manual (OS X)

Descarrega el fitxer zip de aquest repositori, descomprimeix-lo i copia els fitxers Pseudocodi.tmLanguage i Miscellanoeus.tmPreferences a la carpeta:

    ~/Library/Application Support/Sublime Text 3/Packages/User
    
### Amb Package Control
Si no tens instal·lat el Package Control al Sublime Text 3 instal·la-ho seguint les instrucciós d'aquest enllaç: https://packagecontrol.io/installation i despres segueix aquests pasos:

1. A la barra de menus selecciona *Tools->Command Palette** i cerca *Package Control - Add Repository*
2. Copia la url d'aquest repositori al quadre de text que apareix a la part inferior del editor: https://github.com/XavierGaro/sublime-text-language-pseudocodi/
3. A la barra de menus selecciona **Tools->Command Palette** i cerca *Pacakge Control - Install Pacakge*
4. Cerca a la caixa sublime-text-language-pseudocodi.

Una vegada instal·lat estarà llest per fer-se servir.

##Us
Crea un fitxer buit amb extensió *.pseudocodi* o sel·lecciona'l al menú  View->Syntax->Pseudocodi.

Automàticament s'aplicarà el ressaltat de sintaxi i s'aplicará el sagnat positiu i negatiu quan calgui, amb algunes excepcions:

* En un bloc *si - llavors*, *sino*, *fsi* el *sino* no aplica el sagnat.
* En la definició de tuples en el llibre s'aplica un sagnat doble i el tancament del sagnat no es fa respecte a la variable on es declara si no respecte a la posició on apareix la declaració de la tupla. Aquí he aplicat un sagnat sencill de manera que el tancament es queda al mateix nivell que la declaració de la variable on es declara la tupla.

## Contingut
El fitxer PSeudocodi.YAML-tmLanguage conté les regles per aplicar els colors, i el Miscellaneous.tmPreferences conté les regles per afegir o eliminar el sangrat.
