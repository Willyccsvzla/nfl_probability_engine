# Semana 5 · Pronosticando la NFL con un modelo de ELO

## ¿Cómo va el modelo? (semanas 1–4 · pick si prob. > 50%)

- Récord del modelo en la temporada (aciertos-fallos): **37-27 (57.8%)**
- Semana 4: 9-7 (56.2%)
- Aciertos que el propio modelo esperaba: 39.7 → reales: 37
- Brier: 0.231 (moneda al aire = 0.250) · Log loss: 0.652 (moneda = 0.693)
- Cuando eligió al local: 27-18 · al visitante: 10-9
- En esos mismos partidos, siempre el local: 36-28
- Favorito de Las Vegas: 41-23 (64.1%) · el modelo coincide con Las Vegas en 81.2% de los picks · Brier Las Vegas: 0.229
- El batacazo de la semana 4: **DAL** ganó con solo 36% de probabilidad (DAL 34–30 HOU)

### Calibración (temporada)

| Confianza | Partidos | Récord | Prob. media | % real |
|---|---|---|---|---|
| 50–60% | 32 | 16-16 | 55% | 50% |
| 60–70% | 18 | 9-9 | 64% | 50% |
| 70–80% | 14 | 12-2 | 75% | 86% |

## Picks de la semana 5 (hora CDMX)

- Jueves 8 oct 18:15 · TB @ DAL → **DAL 66%**
- Domingo 11 oct 07:30 · PHI @ JAX → **JAX 62%**
- Domingo 11 oct 11:00 · CHI @ GB → **CHI 50%**
- Domingo 11 oct 11:00 · CIN @ MIA → **CIN 53%**
- Domingo 11 oct 11:00 · CLE @ NYJ → **CLE 59%**
- Domingo 11 oct 11:00 · HOU @ TEN → **HOU 65%**
- Domingo 11 oct 11:00 · IND @ PIT → **PIT 61%**
- Domingo 11 oct 11:00 · LV @ NE → **NE 75%**
- Domingo 11 oct 11:00 · MIN @ NO → **MIN 69%**
- Domingo 11 oct 11:00 · NYG @ WAS → **WAS 54%**
- Domingo 11 oct 14:05 · DEN @ LAC → **DEN 62%**
- Domingo 11 oct 14:25 · DET @ ARI → **DET 63%**
- Domingo 11 oct 14:25 · SF @ SEA → **SEA 60%**
- Domingo 11 oct 18:20 · BAL @ ATL → **ATL 50%**
- Lunes 12 oct 18:15 · BUF @ LA → **LA 52%**

## Destacados

- **El más seguro** · LV @ NE: El pick con más confianza de la semana: NE gana con 75.4%
- **La moneda al aire** · BAL @ ATL: Solo 0.8 puntos de diferencia: el partido más parejo de la semana
- **La sorpresa** · CLE @ NYJ: Las Vegas va con NYJ (54.3%). El modelo va con CLE (58.9%).
