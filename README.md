# analiza-bilanturi-anaf
Analiza bilanturi anaf cel mai usor mod posibil

📊 Analiza Bilanțuri ANAF (Multi-An)
Acest instrument automatizează extragerea datelor financiare de pe portalul ANAF pentru companiile din România, permițând analiza comparativă pe mai mulți ani (2020-2024).

✨ Funcționalități

Interogare Multi-An: Extrage date pentru o listă de CUI-uri pe o perioadă de până la 20 de ani simultan.


Automatizare Excel: Include un macro VBA care procesează automat răspunsurile JSON de la API-ul ANAF.


Analiză Vizuală: Generează automat tabele Pivot și grafice de evoluție pentru indicatori cheie precum Cifra de Afaceri și Profitul Net.


Sistem de Log: Monitorizează statusul fiecărei cereri (Succes/Eroare) în timp real.


🚀 Cum îl folosești?

Input: Introdu lista de CUI-uri în foaia CUI_Input (coloana A) și anii doriți în rândul 1.


Extragere: Apasă butonul "Extrage Bilanțuri". Tool-ul va interoga API-ul cu o pauză de 3 secunde între cereri pentru a evita blocarea IP-ului.


Rezultate: Datele brute apar în Date_Bilanturi, iar analizele în Analiza_Pivot și Grafice.

🛠️ Cerințe tehnice
Microsoft Excel cu Macro-uri activate (.xlsm).

Conexiune la internet (pentru accesarea API-ului webservicesp.anaf.ro).

Librăria JsonConverter (inclusă în proiect).

Licență: MIT – Liber pentru utilizare și modificare.
https://www.linkedin.com/in/nelu-badalan-8ab7a120/
