# A simple Czech android choice-based campaign game developed as a high school project with Vlada Horky of [Sawdust Studios](https://github.com/sawduststudios)

POPIS SLOŽEK

Soubor pubspec.yaml slouží k importování assetů a packagů do aplikace.

Ve složce res jsou soubory s ikonou aplikace.

Složka lib:

Složka database obsahuje soubory moor_database.dart. 
Z něho se pomocí package moor automaticky generuje soubor 
moor_database.g.dart pomocí source generation.
dataStorage.dart obsahuje data aplikace, jako například rozhovory a schopnosti (ty se na začátku nahrají do databáze)

Ve složce theme_stuff jsou soubory, kde se definují a ovládají barevná schémata aplikace.

Zbylé dart soubory obsahují jednotlivé stránky aplikace a datové classy.

Ve složce images jsou images.
