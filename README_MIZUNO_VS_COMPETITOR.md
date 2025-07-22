📘 Analisi Comparativa Scarpe Sportive: Mizuno vs Competitor 🧠 Introduzione Questo progetto nasce dall’esigenza di valutare la presenza e la competitività del marchio MIZUNO all’interno del mercato delle scarpe sportive, confrontandolo con altri brand noti come PUMA, UNDER ARMOUR, ASICS, NEW BALANCE, JOMA e DIADORA. L’approccio è stato guidato da metodologie di data science, partendo dallo scraping web del sito Zalando, passando per l’analisi statistica con Python e culminando con la visualizzazione dei dati per mezzo di grafici altamente leggibili e informativi. 🛠️ Tecnologie Utilizzate

Python (pandas, seaborn, matplotlib, numpy)
Power Query & Excel per la pre-pulizia e normalizzazione iniziale
Jupyter Notebook per l’elaborazione e visualizzazione
Web Scraping da Zalando: HTML parsing e dataset costruito da fonti multiple 📦 Dataset Due file principali:
Colori_aggregati.csv – con dettagli su taglie, colori, modelli, genere, sport, etc.
Splittato_tutto.csv – estensione del dataset con i prodotti completi provenienti dal sito Totale prodotti analizzati: oltre 14.000 modelli 🔍 Analisi Svolte
Pulizia & Aggregazione Dati
Normalizzazione taglie e colori
Creazione di colonne split per analisi multi-valore
Unificazione modelli con più taglie per analisi estese
Distribuzione Modelli
Per Marca
Per Genere (Uomo vs Donna)
Per Categoria Sportiva
Analisi dei Prezzi
Prezzi effettivi vs ordinari
Prezzo minimo, massimo e medio per marca e sport
Boxplot e Violinplot per distribuzioni dei prezzi
Comparazione Diretta
MIZUNO vs ASICS, PUMA, JOMA, NEW BALANCE, UNDER ARMOUR, DIADORA
Grafici violino e barre con quartili e range di prezzo
Distribuzione Taglie
Heatmap per taglie per sport per Mizuno
Radar chart per taglie Uomo vs Donna
Heatmap comparativa Mizuno vs UNDER ARMOUR
Colori preferiti
Top 25 colori per Uomo e per Donna
Barplot orizzontali per distribuzione cromatica
Distribuzione percentuale modelli
Grafico finale a barre per % di modelli per categoria sportiv
