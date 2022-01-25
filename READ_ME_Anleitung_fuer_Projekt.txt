

1. XAMPP installieren auf C:\

2. ETL_Project von GitHub herunterladen

3. Pfad öffnen C:\xampp\mysql\data

4. ETL_Project in C:\xampp\mysql\data verschieben (siehe Screenshot bei Unsicherheit)

5. Ordner in C:\xampp\mysql\data\ETL_Project erstellen namens: "ETL Daten"  (Github lädt keine leeren Ordner hoch)

6. VSCode installieren

7. ETL_Project in VSCode öffnen (rechtsklick auf Ordner -> öffnen mit...)

8. alle nötigen Bibs installieren, falls nicht vorhanden

	from faker import Faker
	from faker.providers import DynamicProvider
	from faker_vehicle import VehicleProvider
	from collections import defaultdict
	import pandas as pd
	import random
	from dateutil import parser
	import mysql
	import mysql.connector
	import csv

9. .data_generator_project.ipynb per VSCODE ausführen 

10. per XAMPP MYSQL Server starten

11. .ETL.ipynb per VSCODE ausführen

12. Prozess laufen lassen (kann mehrere Stunden dauer, da große Datenmenge)

13. Datenbank aufrufen z.B. per MYSQL Workbench und folgende Befehle in die Query eingeben

	use firma;

	select * from abteilung;
	select * from mitarbeiter;
	select * from projekt;
	select * from projektmitarbeiter;




