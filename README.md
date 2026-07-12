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

error.html?axis=X&id=X-001&group=primary&depth=0.40&mode=RAW


---

## 📁 Dateien im Repository

| Datei | Funktion |
|-------|----------|
| `index.html` | Achsen‑Dispatcher (Buttons → Parameter → error.html) |
| `error.html` | Fehler‑/Analyse‑Modul für Achsen‑Parameter |
| `demo.DE` | Demo‑Modus (Deutsch) |
| `demo.me` | Demo‑Modus (EN) |
| `demoTR.me` | Demo‑Modus (Türkisch) |
| `r.me` | RAW‑Modus‑Test |
| `rDE.me` | RAW‑Modus‑Test (Deutsch) |
| `rTR.me` | RAW‑Modus‑Test (Türkisch) |
| `README.md` | Dokumentation |

---

## 🔧 Achsen‑Erweiterung (Slots 15–64)

Slots 15–64 sind reserviert für:

- neue Achsen  
- RAW‑Vektoren  
- Engine‑Upgrades  
- Fusion‑Achsen  
- Spezial‑Achsen (RP, NC, MS, R1, LS)

Diese können über `ID.html` erweitert werden.

---

## 🎨 Achsen‑Visualisierung

Die Visualisierung erfolgt über:

- Farben  
- Glow / Pulse / Dash / Wave  
- Depth‑Werte  
- Engine‑Modi  

Visual‑Module:

- OCTA.visual.json  
- QUAD.visual.json  
- 3TH.visual.json  

---

## 🧩 Achsen‑Slots optimieren

Optimierung erfolgt über:

- Depth‑Balance  
- Gruppen‑Konsistenz  
- Fusion‑Kompatibilität  
- SYNC‑Stabilität  

Verwendete Dateien:

- OCTA.map.json  
- QUAD.map.json  
- 3TH.map.json  

---

## 🔥 Achsen‑DNA finalisieren

Die finale Achsen‑DNA entsteht durch Kombination von:

- Α64‑Achsenfamilie.html  
- RAW‑SYS‑IKI‑AXI‑ATOR  
- OCTA / QUAD / 3TH  
- RAW‑Achsen  
- FUSION‑Matrix  
- SYNC‑Matrix  

Damit ist das Achsen‑System vollständig Engine‑kompatibel.

---

## 📌 Status

RAW‑SYS‑IKI‑AXI‑ATOR ist **funktionsfähig**, **erweiterbar**, **Engine‑ready**.




