# 📊 Dashboard Interattiva per l'Analisi dei Dati di Vendita

### 🚀 Descrizione
Questa applicazione web, sviluppata con **Streamlit**, consente di caricare un file CSV contenente dati di vendita e analizzarlo in tempo reale. L'utente può applicare filtri interattivi, visualizzare metriche chiave e generare grafici dinamici per ottenere insight utili sui dati.

---

## 📦 Funzionalità
✅ **Caricamento file CSV** 📂  
✅ **Filtri interattivi (per categoria di prodotto)** 🔍  
✅ **Metriche chiave (Totale Vendite e Quantità Venduta)** 💰  
✅ **Grafico interattivo del trend vendite nel tempo** 📈  
✅ **Grafico delle vendite per categoria** 🎯  
✅ **Visualizzazione dei dati grezzi** 🗂️  

---

## 🛠️ Installazione e Setup

### 1️⃣ Clonare il repository
```bash
 git clone https://github.com/tuo-utente/dashboard-vendite.git
 cd dashboard-vendite
```

### 2️⃣ Creare un ambiente virtuale (opzionale ma consigliato)
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows
```

### 3️⃣ Installare le dipendenze
```bash
pip install -r requirements.txt
```

### 4️⃣ Eseguire l’app
```bash
streamlit run dashboard_vendite.py
```

---

## 🗂️ Struttura del Progetto
```
📂 dashboard-vendite
│-- 📜 dashboard_vendite.py    # Codice principale dell'app Streamlit
│-- 📜 requirements.txt        # Dipendenze del progetto
│-- 📜 vendite.csv             # Esempio di dataset di vendite
│-- 📜 README.md               # Documentazione del progetto
```

---

## 📊 Dataset di Esempio (`vendite.csv`)

| Data       | Prodotto   | Categoria       | Vendite | Quantità | Prezzo Unitario |
|------------|-----------|----------------|---------|---------|----------------|
| 2024-01-01 | Laptop    | Elettronica    | 1500    | 1       | 1500           |
| 2024-01-03 | Smartphone| Elettronica    | 800     | 2       | 400            |
| 2024-01-05 | Scarpe    | Abbigliamento  | 200     | 5       | 40             |
| 2024-01-07 | Frigorifero | Elettrodomestici | 500 | 1       | 500            |

> 📌 **Nota:** Puoi usare il tuo dataset personalizzato, assicurandoti che abbia colonne simili.

---

## 🔥 Possibili Estensioni
🔹 **Aggiungere più filtri** (intervallo di date, range di prezzi)  
🔹 **Aggiungere KPI aggiuntivi** (media prezzo per categoria, top seller)  
🔹 **Integrare Machine Learning** (previsione delle vendite future)  
🔹 **Esportazione dei dati filtrati in CSV**  

---

## 🤝 Contributi
Se vuoi migliorare questa dashboard, sentiti libero di **forkare** il repository e aprire una **pull request**! 🚀

---

## 📜 Licenza
Questo progetto è distribuito sotto licenza **MIT**.

📧 Per domande o suggerimenti, contattami su [tuo.email@example.com](mailto:tuo.email@example.com).

