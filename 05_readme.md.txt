# RenovaCalc Light

Micro-app FastAPI per caricare un file Excel con colonne:
- descrizione
- quantita
- prezzo_unitario

e calcolare il totale per riga e il totale generale.

## Avvio locale

pip install -r requirements.txt  
uvicorn main:app --reload  

Apri nel browser: http://127.0.0.1:8000

## Struttura progetto

renovacalc/  
  main.py  
  requirements.txt  
  templates/  
    upload.html  
    result.html  
  static/  
    style.css  
