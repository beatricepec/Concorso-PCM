# Cheatsheet · Formule

[← Indice](README.md)

## Earned Value Management

| Formula | Significato | Lettura |
|---|---|---|
| `SV = EV − PV` | Schedule Variance | > 0 anticipo |
| `CV = EV − AC` | Cost Variance | > 0 risparmio |
| `SPI = EV / PV` | Schedule Performance Index | > 1 anticipo |
| `CPI = EV / AC` | Cost Performance Index | > 1 sotto budget |
| `EAC = BAC / CPI` | Estimate at Completion | Costo finale stimato |
| `ETC = EAC − AC` | Estimate to Complete | Quanto resta da spendere |
| `VAC = BAC − EAC` | Variance at Completion | > 0 si chiude in risparmio |

> Varianze = differenze · Indici = rapporti · si parte sempre da **EV**.

## Stime e schedulazione

```
PERT (beta)        Te = (O + 4M + P) / 6
PERT (triangolare) Te = (O + M + P) / 3
Deviazione std     σ  = (P − O) / 6
Float totale       TF = LS − ES = LF − EF     (attività critica: TF = 0)
Canali comunicaz.  n(n − 1) / 2
```

## Digital marketing

```
CTR   = click / impression × 100
CPC   = spesa / click
CPM   = spesa / impression × 1000
CPA   = spesa / conversioni
ROAS  = ricavi / spesa pubblicitaria
Tasso di conversione = conversioni / sessioni × 100
Engagement rate = interazioni / reach × 100      (oppure / follower × 100)
Open rate  = aperture uniche / email consegnate × 100
Bounce rate (email) = email non recapitate / email inviate × 100
```

## Intelligenza artificiale — metriche di classificazione

```
Accuracy  = (TP + TN) / (TP + TN + FP + FN)
Precision = TP / (TP + FP)
Recall    = TP / (TP + FN)
F1        = 2 · (Precision · Recall) / (Precision + Recall)
```

| | Predetto + | Predetto − |
|---|---|---|
| **Reale +** | TP | FN |
| **Reale −** | FP | TN |

## Punteggio della prova

```
Punteggio materie  = esatte − 0,5 · errate
Punteggio inglese  = esatte − 0,5 · errate
Punteggio situaz.  = (più efficaci · 1) + (neutre · 0,375)
Soglia             = 42 / 60
```

Valore atteso della risposta a caso su 4 opzioni: **−0,125** · con 2 opzioni residue: **+0,25**.
