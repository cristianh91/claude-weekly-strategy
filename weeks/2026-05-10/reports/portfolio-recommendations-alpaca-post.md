# Recomendaciones Portfolio Alpaca — Semana 5/11/2026 (re-baseline)

**Fecha**: domingo 10/05/2026 (re-generado 16:40 ART)
**Cash real disponible**: $7.500 USD
**Base**: blog 2026-05-10 **re-anclado a 5/4 publicado** (allocation 27/21/17/35), Druckenmiller 18M, DAP post 5/8

> **⚠️ Re-baseline alert**: la versión anterior de este reporte usaba allocation **40/22/16/22** (Risk Budget 78%) que estaba 14pt off del publicado real Monty 5/11 (26/20/17/37). Esta versión corrige usando **5/4 publicado (28/19/17/36)** como anchor real. Ver `reports/2026-05-10/strategy-review.md` para detalles del re-anclaje.

---

## 1. Estado actual del portfolio (Alpaca paper)

**Cuenta**:
- Equity: $100.005,53 (paper) | Cash paper: $96.578,78 | Long MV: $3.426,75
- Pattern Day Trader: NO | Daytrade count: 0
- **Cash REAL para esta semana**: **$7.500**
- **Total portfolio efectivo a planificar**: $3.426,75 + $7.500 = **$10.926,75**

**Posiciones activas**:

| Ticker | Qty | Entry | Cierre 5/8 | MV | P/L |
|---|---|---|---|---|---|
| **SPY** | 1,4522 | $731,43 | $737,62 | **$1.071,17** | +$8,99 (+0,85%) |
| **QQQ** | 0,8487 | $694,66 | $711,23 | **$603,62** | +$14,06 (+2,38%) |
| **AVGO** | 1,3954 | $435,38 | $430,00 | **$600,04** | -$7,51 (-1,24%) |
| **GOOGL** | 1,3290 | $393,19 | $400,80 | **$532,67** | +$10,11 (+1,93%) |
| **XLP** | 4,8891 | $83,82 | $84,18 | **$411,56** | +$1,75 (+0,43%) |
| **MSFT** | 0,5003 | $421,88 | $415,12 | **$207,68** | -$3,38 (-1,60%) |
| **TOTAL** | | | | **$3.426,75** | **+$24,02 (+0,71%)** |

---

## 2. Allocation actual vs modelo Monty 5/10 (re-baseline 27/21/17/35)

| Pilar | Posiciones actuales | Actual % (de $10.927) | **Target NUEVO 5/10** | Target $ | Gap |
|---|---|---|---|---|---|
| ① Core Index (SPY+DIA+QQQ) | SPY $1.071 + QQQ $604 = $1.675 | 15,3% | **27%** | $2.950 | +$1.275 |
| Tech single-name MAG7 | AVGO+GOOGL+MSFT = $1.341 | 12,3% | (subsumido en Core como tilt) | — | (treat as Core) |
| ② Defensivo (XLV+XLP) | XLP $412 | 3,8% | **21%** | $2.295 | **+$1.883** |
| ③ Tema/Hedge (GLD+XLE) | $0 | 0% | **17%** | $1.857 | **+$1.857** |
| ④ Cash/BIL | $7.500 | 68,6% | **35%** | $3.824 | -$3.676 (deploy) |

**Diferencia clave vs versión anterior** (40/22/16/22):
- **NO hay COPX** en el modelo nuevo (se removió post re-baseline; Monty publicado tampoco lo incluye)
- **Cash target subió a 35%** (vs 22% anterior) — buffer mucho mayor pre-eventos binarios CPI/AMAT
- **Risk Budget total 65%** (vs 78% anterior) — postura más defensiva consistente con régimen narrow_rally + Uptrend RED-DOWN

**Diagnóstico**:
- Si tratamos los MAG7 single-names ($1.341) como "Core tilt", **Core total efectivo = $3.016 ≈ target $2.950** ✓ (esencialmente AT target). Mínima rotación necesaria.
- **Gap principal**: defensivo +$1.883 + hedge +$1.857 = **$3.740 a desplegar** en buys nuevos.
- **Cash kept**: $3.824 (35% del total — buffer alto para CPI/AMAT week).
- **Total deploy: $7.500 - $3.824 = $3.676** (down de $5.096 en versión anterior).

---

## 3. Recomendaciones de compra (deploy $3.676 de los $7.500)

> **Filosofía corregida**: re-baseline a 5/4 publicado da allocation defensiva 27/21/17/35. CPI martes binario, AMAT jueves laggard. Deploy moderado (49% del cash) con **35% cash target final**. **NO chasing** tech parabolic, NO COPX (fuera de modelo), NO XLE agresivo.

### TRANCHE 1 — Lunes 5/11 al apertura (~$2.700 / 36% del cash)

| # | Ticker | Buy zone | Cantidad | Inversión | Stop | Tesis |
|---|---|---|---|---|---|---|
| 1 | **GLD** | **$430-435** (ideal dip $430-432) | 3 shares | **$1.302** | **$410** cierre 2 días (-5%) | Hedge institucional Druckenmiller alta convicción + cobertura CPI martes binario + Powell-Warsh transición. Target 12% × $10.927 = $1.311 ✓ |
| 2 | **XLV** | **$143-145** (current $143,49) | 7 shares | **$1.008** | **$138** cierre 2 días (-3,8%) | Defensive oversold; UNH +23,8% 1M ya validó rebote. Target 10% × $10.927 = $1.093 ✓ |
| 3 | **XLP top-up** | **$83,80-84,20** | 5 shares | **$421** | **$82** cierre 2 días | Llegar a XLP $830 total = ~7,6% (target 11% × $10.927 = $1.202; resto en futuras tranches o rebalance gradual) |

**Total Tranche 1: $2.731 (36,4% del cash)**

### TRANCHE 2 — Martes 5/12 post-CPI (~$1.000 / 13% del cash)

**Decisión depende del print CPI 8:30 ET / 21:30 JST / 9:30 ART:**

#### Camino A — CPI in-line (3,1-3,3%, Base 45% prob)

| # | Ticker | Buy zone | Cantidad | Inversión | Stop | Tesis |
|---|---|---|---|---|---|---|
| 4 | **DIA** | $494-498 | 2 shares | **$992** | **$475** cierre semanal | Diversificación Core balance vs concentración MAG7 (SPY+QQQ ya cubre tech, DIA cubre dividendos). Target ~9-10% × $10.927 = $1.093 |

**Total Tranche 2A: $992**

#### Camino B — CPI hot (≥3,5% headline, Caution 23% prob)

| # | Ticker | Buy zone | Cantidad | Inversión | Stop | Tesis |
|---|---|---|---|---|---|---|
| 4' | **GLD** top-up | $433-440 (post spike) | 2 shares | **$867** | **$410** | Pivot a Caution: GLD 12→14% según blog Caution table |
| 5' | **XLP** top-up | en pullback $82-83 | 5 shares | **$415** | **$80** | Reforzar defensivo en print hot |

**Total Tranche 2B: $1.282**

#### Camino C — CPI cool (≤3,0%, Risk-On 27% prob)

| # | Ticker | Buy zone | Cantidad | Inversión | Stop | Tesis |
|---|---|---|---|---|---|---|
| 4'' | **DIA** | $494-498 | 2 shares | **$992** | **$475** | Mismo target Core diversificación; en Risk-On QQQ no es prioridad porque estás overweighted en MAG7 single-names ya |

**Total Tranche 2C: $992**

### TRANCHE 3 — RESERVA pre-AMAT jueves 5/14 (~$945 / 12% del cash final)

**No deployar antes del cierre AMAT.** AMAT 16:30 ET es el laggard del trade semis IA — si miss + guide flat, NDX cae -3 a -5% rápido.

- **Si AMAT beat + guide strong**: deploy última tranche en **XLE** $545 (10 shares × $55,7) si WTI rebote sostiene + **XLP** top-up final $400.
- **Si AMAT miss**: keep cash, ejecutar Caution table del blog (cortar parcial QQQ existente, rotar a GLD/XLP).

**Cash final post-semana objetivo**: $3.824 (35% del total) = **dry powder estructural alto**, consistente con régimen narrow_rally + Uptrend RED-DOWN.

---

## 4. Recomendación prioritaria — solo 3 buys esta semana

| Prioridad | Ticker | $ | Razón |
|---|---|---|---|
| 🥇 **MUST BUY** | **GLD** $1.302 | hedge alta convicción Druckenmiller 18M + CPI hedge inmediato (target 12%) |
| 🥈 **STRONG BUY** | **XLV** $1.008 | defensivo oversold mean-reversion 12M trade (target 10%) |
| 🥉 **CONDITIONAL** | **DIA** $992 (post-CPI in-line o cool) | balance Core vs concentración MAG7 (target ~9%) |

Total prioritario: **~$3.300** — el resto ($4.200) queda en cash para AMAT jueves y volatilidad post-CPI.

---

## 5. Watchlist — NO comprar esta semana

| Ticker | Motivo |
|---|---|
| **AMD** | Ya parabolic +92% 1M post-earnings, RSI extremo. Esperar -15% pullback mínimo |
| **NVDA** | Líder tech en zona de top probable, RSI semanal NDX 74. Watchful, no chase |
| **AMAT** | Jueves AMC = evitar pre-earnings exposure |
| **URA** | Current $55,18; comprar sólo en dip a $50-52 (NO en modelo principal) |
| **COPX** | **Removido del modelo post re-baseline** (no figura en publicado Monty 5/11). Si querés exposición cobre, sería táctica externa al modelo |
| **XLE agresivo** | WTI corrigió -7%, slope mixto. Target sólo 5% × $10.927 = $546; postergar para Tranche 3 si AMAT beat |
| **NFLX/CRM** | No están en modelo, evitar single-names extras |
| **QQQ extra** | Ya tenés QQQ $604 + MAG7 $1.341 = $1.945 en tech; suficiente exposición |

---

## 6. Riesgos a vigilar (orden de prioridad)

1. **CPI martes 5/12 21:30 ART** — el evento binario. Plan A/B/C arriba según print
2. **Iran/Hormuz incident** — cualquier titular = WTI spike, GLD ganador asimétrico
3. **AMAT jueves AMC** — laggard semis, miss = NDX -3-5%
4. **Powell→Warsh transición** — viernes 5/15 mandato Chair expira, Senate confirmation pendiente

---

## 7. Tabla resumen final — ejecución (re-baseline)

| Día/Trigger | Acción | Inversión | Stop |
|---|---|---|---|
| **Lun 5/11 09:30 ET / 10:30 ART** | BUY 3 GLD @ $430-435 | $1.302 | $410 |
| Lun 5/11 09:30 ET | BUY 7 XLV @ $143-145 | $1.008 | $138 |
| Lun 5/11 09:30 ET | BUY 5 XLP @ $83,80-84,20 | $421 | $82 |
| **Mar 5/12 09:30 ART pre-CPI** | HOLD cash, no nuevos buys | — | — |
| Mar 5/12 post-CPI 22:00 ART | Decidir Camino A/B/C según print | $992-1.282 | varios |
| **Jue 5/14 16:30 ET** | HOLD cash pre-AMAT AMC | — | — |
| Vie 5/15 09:30 ET | Deploy última tranche según AMAT | $545-945 | varios |

**Cash final post-semana objetivo**: ~$3.700-3.900 (35% del total) = **dry powder estructural** consistente con allocation modelo 27/21/17/**35**.

---

## 8. Niveles macro a vigilar (gap pre-market lunes)

- **SPX futures**: defensa **7.380-7.400**; ruptura **7.450** = extensión Risk-On parcial; ruptura **7.300** = pre-Caution
- **NDX/QQQ**: QQQ defensa **$700-705**; ruptura **$715** = melt-up; ruptura **$695** = top probable Tech
- **VIX premarket**: **<17,5 ok**; **>18,5** primera campanada
- **US10Y intraday**: **<4,40% ok**; **>4,45%** segunda campanada (red line 4,50%)
- **GLD**: defensa **$430**; ruptura **$440** = breakout hedge institucional
- **WTI**: defensa **$94**; ruptura **$90** = sobreextiende corrección

---

## 9. Diferencias vs versión anterior (transparencia)

| Aspecto | Versión anterior (mal anclada) | Versión actual (re-baseline) |
|---|---|---|
| Allocation target | 40/22/16/22 (Risk 78%) | **27/21/17/35** (Risk 65%) |
| Anchor de continuidad | 5/9 local "fresh-start" Core 44% | **5/4 publicado Core 28%** |
| Universo Breadth | S&P 500 (~500) | **Russell 3000 (~2557)** |
| Cash kept post-semana | $1.500-2.500 (20-33%) | **$3.700-3.900 (35%)** |
| COPX en plan | $1.000-1.250 | **Removido (no en modelo)** |
| Total deploy | $5.350 | **$3.676** |
| Núm. de buys recomendados | 5-6 | **3 prioritarios + 1 condicional** |

**Conclusión**: el plan corregido es **menos agresivo en deploy** (49% del cash vs 71% antes) y **más alineado con el publicado Monty 5/11**. La diferencia se debe principalmente al baseline corregido y al Russell 3000 universe que muestra Breadth menos deteriorado (200MA 57,33% sin dead cross) que S&P 500 (200MA 59,87% con dead cross).

---

## 10. Disclaimer

Este análisis presenta un **modelo de cartera** basado en los reports del 2026-05-10 (weekly-strategy + druckenmiller-strategy + daily-action-plan-post). **NO constituye asesoramiento financiero individual**. Los precios de entrada y stops son sugerencias técnicas; cada lector debe considerar su tolerancia al riesgo, situación fiscal, exposición previa y composición patrimonial total. Las **probabilidades 27/45/23/5 (weekly tactical) y 20/40/30/10 (Druckenmiller 18M) son estimaciones del autor** (筆者推定 / author estimate), no consensos verificables. Operar con $7.500 implica **riesgo de pérdida total del capital**. Consultá un asesor financiero matriculado antes de operar capital real.

---

*Reporte regenerado: 2026-05-10 16:42 ART (post re-baseline). Datos: cierre 5/8 vía FMP API + Yahoo Finance v8 fallback (`scripts/fetch_market_close.py`). Breadth/Uptrend Ratio: CSV local Russell 3000 (`data/breadth-local/`, ~2557 nombres vía iShares IWV holdings + Yahoo). Portfolio Alpaca: paper account, query directa via REST API.*
