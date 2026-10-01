# Semana 4 · Pronosticando la NFL con un modelo de ELO

## ¿Cómo va el modelo? (semanas 1–3 · pick si prob. > 50%)

- Récord del modelo en la temporada (aciertos-fallos): **28-20 (58.3%)**
- Semana 3: 9-7 (56.2%)
- Aciertos que el propio modelo esperaba: 29.8 → reales: 28
- Brier: 0.234 (moneda al aire = 0.250) · Log loss: 0.660 (moneda = 0.693)
- Cuando eligió al local: 21-13 · al visitante: 7-7
- En esos mismos partidos, siempre el local: 28-20
- Favorito de Las Vegas: 32-16 (66.7%) · el modelo coincide con Las Vegas en 83.3% de los picks · Brier Las Vegas: 0.233
- El batacazo de la semana 3: **WAS** ganó con solo 25% de probabilidad (SEA 31–33 WAS)

### Calibración (temporada)

| Confianza | Partidos | Récord | Prob. media | % real |
|---|---|---|---|---|
| 50–60% | 23 | 12-11 | 56% | 52% |
| 60–70% | 15 | 8-7 | 65% | 53% |
| 70–80% | 10 | 8-2 | 73% | 80% |

## Picks de la semana 4 (hora CDMX)

- Jueves 1 oct 18:15 · PIT @ CLE → **PIT 54%**
- Domingo 4 oct 07:30 · IND @ WAS → **WAS 57%**
- Domingo 4 oct 11:00 · ARI @ NYG → **NYG 61%**
- Domingo 4 oct 11:00 · DAL @ HOU → **HOU 64%**
- Domingo 4 oct 11:00 · GB @ TB → **GB 55%**
- Domingo 4 oct 11:00 · JAX @ CIN → **JAX 53%**
- Domingo 4 oct 11:00 · LA @ PHI → **PHI 58%**
- Domingo 4 oct 11:00 · NE @ BUF → **BUF 64%**
- Domingo 4 oct 11:00 · NYJ @ CHI → **CHI 75%**
- Domingo 4 oct 11:00 · TEN @ BAL → **BAL 79%**
- Domingo 4 oct 14:05 · MIA @ MIN → **MIN 78%**
- Domingo 4 oct 14:25 · DEN @ SF → **SF 56%**
- Domingo 4 oct 14:25 · KC @ LV → **KC 55%**
- Domingo 4 oct 14:25 · LAC @ SEA → **SEA 77%**
- Domingo 4 oct 18:20 · DET @ CAR → **DET 59%**
- Lunes 5 oct 18:15 · ATL @ NO → **NO 51%**

## Destacados

- **El más seguro** · TEN @ BAL: El pick con más confianza de la semana: BAL gana con 79%
- **La moneda al aire** · ATL @ NO: Solo 2 puntos de diferencia: el partido más parejo de la semana
- **La sorpresa** · IND @ WAS: Las Vegas va con IND (62%). El modelo va con WAS (57%).
