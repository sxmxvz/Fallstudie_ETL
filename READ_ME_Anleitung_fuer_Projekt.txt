

1. XAMPP installieren auf C:\

2. ETL_Project von GitHub herunterladen

3. Pfad öffnen C:\xampp\mysql\data

4. ETL_Project in C:\xampp\mysql\data verschieben (siehe Screenshot bei Unsicherheit)

5. VSCode installieren

6. ETL_Project in VSCode öffnen (rechtsklick auf Ordner -> öffnen mit...)

7. alle nötigen Bibs installieren, falls nicht vorhanden

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

8. .data_generator_project.ipynb per VSCODE ausführen 

9. per XAMPP MYSQL Server starten

10. .ETL.ipynb per VSCODE ausführen

11. Prozess laufen lassen (kann mehrere Stunden dauer, da große Datenmenge)

12. Datenbank aufrufen z.B. per MYSQL Workbench und folgende Befehle in die Query eingeben

	use firma;

	select * from abteilung;
	select * from mitarbeiter;
	select * from projekt;
	select * from projektmitarbeiter;




