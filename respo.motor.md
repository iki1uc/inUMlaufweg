# RESPO — inUMlaufweg

RESPO ist das Umlauf‑Modul des Systems.  
Es bildet die Achse‑Quelle‑7 ab und steuert alle Transit‑Bewegungen.

## Funktionen
- Transit
- Router
- Cache
- Umlauf
- Durchlauf
- Rücklauf
- Vorlauf

## GEO‑Bezug
RESPO verbindet:
- Ursache (3 → QI → 9)
- Wirkung (9 → IQQ → 81)
- Prüfung (PIPELINE9 → REL/RDY/FAL/MISS)
- Rückführung (81.tmp → 3)

## Pipeline‑Bezug
RESPO ist direkt an PIPELINE9 gekoppelt und liefert Umlauf‑Daten für:
- REL
- RDY
- FAL
- MISS
