# Semana 6 · Pronosticando la NFL con un modelo de ELO

## ¿Cómo va el modelo? (semanas 1–5 · pick si prob. > 50%)

- Récord del modelo en la temporada (aciertos-fallos): **45-33 (57.7%)**
- Semana 5: 8-6 (57.1%)
- Aciertos que el propio modelo esperaba: 48.2 → reales: 45
- Brier: 0.228 (moneda al aire = 0.250) · Log loss: 0.646 (moneda = 0.693)
- Cuando eligió al local: 30-22 · al visitante: 15-11
- En esos mismos partidos, siempre el local: 41-37
- Favorito de Las Vegas: 50-28 (64.1%) · el modelo coincide con Las Vegas en 83.3% de los picks · Brier Las Vegas: 0.229
- El batacazo de la semana 5: **TB** ganó con solo 34% de probabilidad (TB 24–16 DAL)

### Calibración (temporada)

| Confianza | Partidos | Récord | Prob. media | % real |
|---|---|---|---|---|
| 50–60% | 38 | 17-21 | 55% | 45% |
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
- **La sorpresa** · NO @ NYG: Las Vegas va con NO (51.1%). El modelo va con NYG (65.5%).
