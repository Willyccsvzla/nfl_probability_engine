# Semana 3 · Pronosticando la NFL con un modelo de ELO

## ¿Cómo va el modelo? (semanas 1–2 · pick si prob. > 50%)

- Récord del modelo en la temporada (aciertos-fallos): **19-13 (59.4%)**
- Semana 2: 10-6 (62.5%)
- Aciertos que el propio modelo esperaba: 19.9 → reales: 19
- Brier: 0.237 (moneda al aire = 0.250) · Log loss: 0.666 (moneda = 0.693)
- Cuando eligió al local: 14-10 · al visitante: 5-3
- En esos mismos partidos, siempre el local: 17-15
- Favorito de Las Vegas: 23-9 (71.9%) · el modelo coincide con Las Vegas en 87.5% de los picks · Brier Las Vegas: 0.222
- El batacazo de la semana 2: **NO** ganó con solo 31% de probabilidad (NO 24–17 BAL)

### Calibración (temporada)

| Confianza | Partidos | Récord | Prob. media | % real |
|---|---|---|---|---|
| 50–60% | 14 | 8-6 | 56% | 57% |
| 60–70% | 12 | 6-6 | 64% | 50% |
| 70–80% | 6 | 5-1 | 72% | 83% |

## Picks de la semana 3 (hora CDMX)

- Jueves 24 sep 18:15 · ATL @ GB → **GB 65%**
- Domingo 27 sep 11:00 · CAR @ CLE → **CLE 54%**
- Domingo 27 sep 11:00 · CIN @ PIT → **PIT 58%**
- Domingo 27 sep 11:00 · HOU @ IND → **HOU 58%**
- Domingo 27 sep 11:00 · KC @ MIA → **KC 55%**
- Domingo 27 sep 11:00 · LAC @ BUF → **BUF 74%**
- Domingo 27 sep 11:00 · NE @ JAX → **NE 52%**
- Domingo 27 sep 11:00 · NYJ @ DET → **DET 74%**
- Domingo 27 sep 11:00 · SEA @ WAS → **SEA 75%**
- Domingo 27 sep 11:00 · TEN @ NYG → **NYG 66%**
- Domingo 27 sep 14:05 · ARI @ SF → **SF 78%**
- Domingo 27 sep 14:05 · MIN @ TB → **MIN 65%**
- Domingo 27 sep 14:25 · BAL @ DAL → **DAL 51%**
- Domingo 27 sep 14:25 · LV @ NO → **NO 60%**
- Domingo 27 sep 18:20 · LA @ DEN → **DEN 59%**
- Lunes 28 sep 18:15 · PHI @ CHI → **PHI 52%**

## Destacados

- **El más seguro** · ARI @ SF: El pick con más confianza de la semana: SF gana con 78%
- **La moneda al aire** · BAL @ DAL: Solo 2 puntos de diferencia: el partido más parejo de la semana
- **La sorpresa** · CIN @ PIT: Las Vegas va con CIN (62%). El modelo va con PIT (58%).
