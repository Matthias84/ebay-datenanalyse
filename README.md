# ebay-datenanalyse
Jupyter Notebook, das die Datenauskunft von eBay darstellen kann (python3 pandas)
> sudo apt install jupyter-notebook
> pip3 install maxminddb-geolite2

Downloade die *.ipnb Dateien und starte den Notebook-Server mit `jupyter-notebook`

Die CSV Dateien müssen aus den .XLSX bzw. .PDF Dateien erstellt werden:
> java -jar tabula-1.0.2-jar-with-dependencies.jar --password <übermitteltes Passwort> --lattice --pages all "angebotene und verkaufte Artikel.pdf" --out artikel.csv

Siehe meinen Blogpost zur [Datenauskunft bei ebay.de](https://workpress.plattform32.de/2019/02/datenauskunft-bei-ebay-de/)
