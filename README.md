# Enable Customization

Go to Settings>Interface Customization... then tick the "Enable customization" checkbox. If you skip this step, QGISCUSTOMIZATION3.ini will not exist.


# Access QGISCUSTOMIZATION3.ini

To access the file, go to Settings>User profiles>Open Active Profile Folder. The file is located at ``./QGIS/QGISCUSTOMIZATION3.ini``


# Edit QGISCUSTOMIZATION3.ini

Add a key named "***splashpath***" in the ini file, which points to a folder which contains an image called "***splash.png***" (mandatory name and extension).

```splashpath=home/asus/qgis/qgis3/profiles/default/```

Replace Slashes with Backslashes and escape each if using Windows, like so:

```splashpath=C:\\Users\\ASUS\\AppData\\Roaming\\QGIS\\QGIS3\\profiles\\default\\```
