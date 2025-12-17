# interview4empathy
from interview to empathy map: a tool

Empathy Interview Pipeline

This Streamlit application provides a **single interface** for the complete empathy-interview workflow:

1. **Stage 1** – Upload filled Word interview sheets → extract raw quotes  
2. **Stage 2** – Code quotes using a learning-adapted empathy map (dropdown-based)  
3. **Stage 3** – Synthesize empathy maps → export summary CSV, combined Excel, and optional PDF

The pipeline is designed for **qualitative research transparency**, keeping raw data separate from interpretation and preserving traceability from empathy maps back to original interview quotes.

---

This Streamlit app:
1) extracts quotes from filled Word interview sheets
2) generates an editable empathy-coding table with dropdowns (controlled vocabulary)
3) lets you download:
   - empathy_coding.csv
   - combined Excel with sheets: interview_metadata, raw_quotes, empathy_coding

## Install
```bash
pip install streamlit python-docx openpyxl pandas
```

## Run
```bash
streamlit run app.py
```
