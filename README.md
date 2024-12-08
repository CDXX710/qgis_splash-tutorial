# English

## Enable Customization
Go to Settings>Interface Customization... then tick the "Enable customization" checkbox. If you skip this step, QGISCUSTOMIZATION3.ini will not exist.


## Access QGISCUSTOMIZATION3.ini
To access the file, go to Settings>User profiles>Open Active Profile Folder. The file is located at ``./QGIS/QGISCUSTOMIZATION3.ini``


## Edit QGISCUSTOMIZATION3.ini
Add a key named "***splashpath***" in the ini file, which points to a folder which contains an image called "***splash.png***" (name and extension are mandatory || PNG should be 600x300).

> Linux syntax: {for png located in ``default``)
```splashpath=home/asus/qgis/qgis3/profiles/default/```

> Windows syntax: (for png located in ``default``)
```splashpath=C:\\Users\\ASUS\\AppData\\Roaming\\QGIS\\QGIS3\\profiles\\default\\```


# Français

## Activer la les options de customisations
Aller dans Préférences>Interface... Puis cocher la case autorisant les modifications. Sans cette étape, le fichier QGISCUSTOMIZATION3.INI n'existera pas.


## Accéder à QGISCUSTOMIZATION3.ini
Pour pouvoir modifier le fichier, aller dans Préférences>Profile>Ouvrir le répértoire du profile actif. Le fichier se situe à ```./QGIS/QGISCUSTOMIZATION3.ini```

## Modifier QGISCUSTOMIZATION3.ini
Ajouter une clé nommée "***splashpath***" dans le fichier ini, celle-ci doit pointer vers un dossier contenant une image nommée "***splash.png***" (nom et extension obligatoire || l'image doit mesurer 600x300).

> Syntaxe Linux: (pour une image située dans le dossier ``default``)
```splashpath=home/asus/qgis/qgis3/profiles/default/```

> Syntaxe Windows: (pour une image située dans le dossier ``default``)
```splashpath=C:\\Users\\ASUS\\AppData\\Roaming\\QGIS\\QGIS3\\profiles\\default\\```
