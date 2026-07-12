# RAW‑SYS‑IKI‑AXI‑ATOR  
Achsen‑System · RAW‑Ebene · Dispatcher · Engine‑Routing

Dieses Repository bildet die **RAW‑Ebene** des gesamten 3TH‑Achsen‑Systems ab.  
Es dient als **Achsen‑Dispatcher**, der Achsen‑IDs, Gruppen, Depth‑Werte und Engine‑Modi an die Fehler‑/Analyse‑Module weiterleitet.

---

## 🎯 Zweck des Systems

RAW‑SYS‑IKI‑AXI‑ATOR ist die **erste operative Ebene** nach der ROOT‑Achsen‑DNA (Α64‑Achsenfamilie).  
Es übernimmt:

- Achsen‑Routing  
- Achsen‑Identifikation  
- Achsen‑Parameter‑Dispatch  
- Fehler‑Weiterleitung  
- RAW‑Modus‑Analyse  
- Übergabe an QUAD / 3TH

---

## 🧬 Achsen‑DNA (Basis)

Die Achsen‑DNA stammt aus:

- Α64‑Achsenfamilie.html (ROOT)
- OCTA.core.json
- QUAD.core.json
- 3TH.core.json

Diese definieren:

- **primary**: X, Y, Z  
- **secondary**: T, S  
- **motion**: MOVE, STATE, FLOW  
- **tri‑core**: alpha, beta, gamma  

Jede Achse besitzt:

- Slot (1–64)  
- Gruppe  
- Depth‑Wert  
- Engine‑Modus  
- ID‑Code  

---

## ⚙️ Funktionsweise

Die Datei **index.html** erzeugt Buttons für jede Achse.  
Beim Klick wird die Achse mit Parametern an `error.html` gesendet:

- `axis=` Achsenname  
- `id=` Achsen‑ID  
- `group=` Achsengruppe  
- `depth=` Engine‑Tiefe  
- `mode=` RAW oder 3TH  

Beispiel:

