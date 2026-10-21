# Semana 6 · Pronosticando la NFL con un modelo de ELO

## ¿Cómo va el modelo? (semanas 1–5 · pick si prob. > 50%)

- Récord del modelo en la temporada (aciertos-fallos-empates): **45-33-1 (57.6%)**
- Semana 5: 8-6-1 (56.7%)
- Aciertos que el propio modelo esperaba: 48.8 → reales: 45.5 (empate = ½)
- Brier: 0.225 (moneda al aire = 0.250) · Log loss: 0.647 (moneda = 0.693)
- Cuando eligió al local: 30-22-1 · al visitante: 15-11
- En esos mismos partidos, siempre el local: 41-37-1
- Favorito de Las Vegas: 50-28-1 (63.9%) · el modelo coincide con Las Vegas en 83.5% de los picks · Brier Las Vegas: 0.226
- El batacazo de la semana 5: **TB** ganó con solo 34% de probabilidad (TB 24–16 DAL)

### Calibración (temporada)

| Confianza | Partidos | Récord | Prob. media | % real |
|---|---|---|---|---|
| 50–60% | 39 | 17-21-1 | 55% | 45% |
| 60–70% | 25 | 15-10 | 64% | 60% |
| 70–80% | 15 | 13-2 | 75% | 87% |

## Picks de la semana 6 (hora CDMX)

- Jueves 15 oct 18:15 · SEA @ DEN → **DEN 53%**
- Domingo 18 oct 07:30 · HOU @ JAX → **JAX 69%**
- Domingo 18 oct 11:00 · BAL @ CLE → **BAL 57%**
- Domingo 18 oct 11:00 · CAR @ PHI → **PHI 63%**
- Domingo 18 oct 11:00 · CHI @ ATL → **CHI 52%**
- Domingo 18 oct 11:00 · NO @ NYG → **NYG 66%**
- Domingo 18 oct 11:00 · NYJ @ NE → **NE 80%**
- Domingo 18 oct 11:00 · PIT @ TB → **PIT 59%**
- Domingo 18 oct 11:00 · TEN @ IND → **IND 75%**
- Domingo 18 oct 14:05 · ARI @ LA → **LA 78%**
- Domingo 18 oct 14:25 · BUF @ LV → **BUF 70%**
- Domingo 18 oct 14:25 · LAC @ KC → **KC 71%**
- Domingo 18 oct 18:20 · DAL @ GB → **GB 67%**
- Lunes 19 oct 18:15 · WAS @ SF → **SF 82%**

## Destacados

- **El más seguro** · WAS @ SF: El pick con más confianza de la semana: SF gana con 82.1%
- **La moneda al aire** · CHI @ ATL: Solo 4.8 puntos de diferencia: el partido más parejo de la semana
- **La sorpresa** · CAR @ PHI: Las Vegas va con CAR (59.3%). El modelo va con PHI (63.3%).
