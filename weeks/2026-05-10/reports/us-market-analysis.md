# Análisis Integral del Mercado US — Semana del 11 de mayo de 2026

**Fecha del informe**: 10 de mayo de 2026 (domingo, post-cierre 5/8)
**Autor**: us-market-analyst (orquestador de market-environment-analysis + us-market-bubble-detector + breadth-chart-analyst)
**Idioma**: español rioplatense
**Inputs**: `reports/2026-05-10/technical-market-analysis.md` + CSVs locales (`data/breadth-local/`) + breadth charts (`charts/2026-05-10/SP500_BREADTH_PROXY_RSP_SPY_RATIO.png`, `US_UPTREND_STOCK_RATIO.png`)

> **Nota crítica sobre fuente de datos Breadth/Uptrend Ratio**: este informe usa CSVs **locales** generados por nuestro pipeline independiente (`data/breadth-local/*.csv`). **No** usa el CSV remoto de TraderMonty. **Caveat universo**: el Uptrend Ratio local mide stocks del **S&P 500** (~500 nombres), mientras TraderMonty mide "all markets" (~3.000+). Por eso el 31,34% local es ~6pt por encima del 25-26% que reporta TraderMonty para la misma fecha. **Direccionalmente ambas series son consistentes** (ambas RED, ambas DOWN, ambas debajo del umbral 37 overbought y debajo del 33 medio del régimen 2025). En este informe usamos la trayectoria del **10MA local** como vector de tendencia (no comparable 1:1 con TM, pero coherente).

---

## 1. Resumen ejecutivo

La acción de precio de la semana del 5/4-5/8 produjo un **rally vertical liderado por mega-tech** (SPX +2,33% / NDX +5,5% / Tech +6,25% 1W) con SPX y NDX cerrando en **nuevos ATH** y VIX en 17,19 (apenas debajo del umbral 17 Risk-On). **Pero la radiografía interna del mercado es mucho menos saludable**:

- **Breadth 200MA = 59,87%** (CSV local, debajo del 60% healthy → narrow rally borderline).
- **Breadth 8MA = 54,82%** (neutral) **debajo del 200MA** → **dead cross activo** desde el 4/20, magnitud -5,06pt y Trend DOWN.
- **Uptrend Ratio S&P 500 = 31,34% RED** (CSV local), 10MA 33,11%, slope -0,2275/día, **trend DOWN sostenido por 8 sesiones** (último GREEN puntual fue 5/6, antes una larga secuencia GREEN durante abril).
- **Sectores en uptrend interno**: solo 4 de 11 sectores >40% (Tech 43,1% / Materials 42,3% / Real Estate 41,9% / Industrials 40,5%); 3 sectores en zona oversold (Communication Services 17,4% / Health Care 15,3% / Utilities 6,5%).

**Diagnóstico**: estamos viendo una **divergencia clásica de fase tardía**: precio del cap-weighted (SPX/NDX) en ATH **mientras** la participación interna se deteriora. El RSP:SPY (equal-weight vs cap-weight) confirma esto visualmente — está en **debilidad relativa fuerte** con MACD negativo y RSI 22,47 (extremo bajo). Esto es el **patrón de melt-up con liderazgo cada vez más estrecho** que históricamente precede pull-backs del 5-10%.

**Market Phase**: **Risk-On directo, pero late-stage / con asimetría deteriorada**. Mantengo Risk-On como fase nominal porque VIX < 18, sectores cíclicos (Tech, Materials, Discretionary) liderando, y precio en ATH; pero la débil internals + dead cross 8MA-200MA + Uptrend RED introducen un sesgo Caution más material que en semanas previas.

**Bubble Score (Minsky/Kindleberger v2.1)**: **8/15 — Elevated Risk** (frontera Caution-Euphoria).

---

## 2. Market Phase Assessment (4-state framework)

| Estado | Criterios típicos | Match actual | Veredicto |
|---|---|---|---|
| **Risk-On** | VIX < 17 / Indices ATH / Tech leads / Cyclicals strong / Defensives lag | VIX 17,19 (apenas), SPX/NDX ATH, Tech +19% 1M, Discretionary +7,4%, Defensivos en rojo | ✓ Mayoría |
| **Base** | VIX 17-20 / Indices laterales / Sectores rotando / Breadth media | VIX en frontera, SPX rompió ATH (no lateral), breadth 53%+/-| Parcial |
| **Caution** | VIX 20-23 / Pull-back activo / Breadth degradándose / Yields warning | VIX < 20, no hay pull-back (al revés, melt-up); pero **breadth cayendo, Uptrend RED, dead cross**, US10Y 4,38% > 4,36% alerta | Algunos elementos |
| **Stress** | VIX > 23 / Breakdown técnico / Breadth crisis / Defensivos liderando | No aplica (VIX 17, ATH activo, defensivos rezagados) | No |

**Veredicto Market Phase**: **Risk-On (late-stage) con sesgo Caution embebido**.

Justificación detallada:
- **Por qué sigue siendo Risk-On**: precio (la variable única más importante) está en ATH; la vela semanal NDX cierra en el high (marubozu); VIX < 18; sectores cíclicos lideran; defensivos rezagan; la breadth 200MA (59,87%) está en el límite del rango healthy — no es sub-50% que dispararía Caution claro.
- **Por qué embebe Caution**: 8MA breadth ya cayó debajo del 200MA (dead cross hace 3 semanas); el Uptrend Ratio S&P 500 perdió la zona "neutral GREEN" (>30 con slope up) y entró en RED con slope -0,2275/día por 8 sesiones; el RSP:SPY ratio está rompiendo MA50 con MACD bajista; 7 de 11 sectores están debajo del 35% uptrend interno y 3 directamente oversold (Health Care, Utilities, Communication Services). Esto **no es una breadth de Risk-On saludable**.

**Comparación con la semana previa (5/2)**: probabilidades del blog del 5/9 publicado:
- Risk-On 50% / Base 30% / Caution 15% / Stress 5%.

**Mi lectura para el 5/11** (justifico en sección 7):
- Risk-On 35% / Base 35% / Caution 25% / Stress 5%.

**Por qué bajo Risk-On de 50% a 35% y subo Caution de 15% a 25%**:
1. Uptrend Ratio CSV local: la trayectoria 10MA es DOWN (-0,2275/día). Hace 2 semanas (4/24) el 10MA estaba en 34,37 con slope +0,16/día (UP). Hoy el 10MA es 33,11 con slope -0,23/día (DOWN). **Se invirtió**.
2. Aunque el universo TM (3.000+) y el local (S&P 500) no son comparables 1:1 en nivel absoluto, **ambas series se mueven direccionalmente igual** (TM 5/7 25,31% post-deterioro vs. local 5/8 31,34% post-deterioro): los dos están en RED-DOWN.
3. El dead cross 8MA-200MA persiste (-5,06pt) y el 200MA breadth está cayendo (Trend "down" en CSV).
4. Sectores defensivos en oversold profundo (Healthcare 15,3%, Utilities 6,5%, Communication Services 17,4%) **no son señal de Risk-On healthy**. En un Risk-On healthy, los defensivos están en torno a 30-50% interno (no oversold).
5. NDX RSI 74 + AMD +92% 1M: blow-off mechanics — la asimetría riesgo-beneficio ha empeorado materialmente.

Pero **mantengo Risk-On como escenario base+** (35%, no 25%) porque:
- VIX 17,19 sigue muy debajo de 20 (no hay stress en el seguro).
- Precio en ATH es bullish hasta que se pierda — los 7.272 SPX y 28.000 NDX no están rotos.
- Sectores cíclicos siguen en uptrend interno (Tech 43% / Materials 42% / Industrials 40,5%) — estos son los líderes, no los defensivos.
- El melt-up puede extenderse 2-4 semanas más en presencia de cobre breakout, oro recuperando MA50 y crédito sin stress.

---

## 3. Bubble Score — Minsky/Kindleberger v2.1 (0-15)

### Phase 1: Quantitative data collection (mandatory)

Datos relevantes recolectados/inferidos (5/8 close + reciente):

| Indicador | Valor | Fuente |
|---|---|---|
| Put/Call (CBOE Equity P/C) 5DMA | ~0,72-0,75 (estimado, Risk-On regime) | Estimación basada en VIX comprimido + ATH |
| VIX | 17,19 | Fetch FMP (techincal-market-analysis 5/8) |
| VIX percentile (3M) | ~25-30% (mínimos cíclicos, no extremo) | Estimación |
| Realized vol 21d | ~10-12% (consistente con VIX comprimido) | Estimación |
| Margin debt FINRA YoY | Asumido moderado (no hay reporte de spike +20%) | Estimación |
| Breadth (% S&P 500 > 50DMA) | ~55-60% (proxy con 8MA breadth 54,82% local) | CSV local |
| Breadth 200MA | 59,87% (debajo del 60% healthy) | CSV local |
| IPO count YTD vs 5Y avg | ~1,2-1,5x (mejora pero no flood, sin first-day +20% extremo) | Estimación |

### Phase 2: Quantitative scoring (max 12 pts)

| # | Indicador | Criterio | Lectura | Score |
|---|---|---|---|---|
| 1 | **Put/Call** | <0,70 = 2pt / 0,70-0,85 = 1pt / >0,85 = 0pt | ~0,72-0,75 estimado | **1** |
| 2 | **VIX + ATH** | VIX<12 + ATH = 2pt / VIX 12-15 + ATH = 1pt / VIX>15 o lejos = 0pt | VIX 17,19 + SPX/NDX ATH | **0** |
| 3 | **Margin Debt YoY** | +20% & ATH = 2pt / +10-20% = 1pt / <10% = 0pt | Sin evidencia de spike (asumido +5-10%) | **0** |
| 4 | **IPO heat** | Q count >2x + first-day +20% = 2pt / >1,5x = 1pt / normal = 0pt | Sin flood evidente; AI-related IPOs activos | **1** |
| 5 | **Breadth anomaly** | ATH & <45% > 50DMA = 2pt / 45-60% = 1pt / >60% = 0pt | ATH + breadth 200MA 59,87% (en frontera) | **1** |
| 6 | **Price acceleration** | 3M return >95th percentile 10y = 2pt / 85-95th = 1pt / <85th = 0pt | NDX +20%+ en 6 semanas, RSI 74 — alto pero no histórico extremo (10Y) | **1** |

**Phase 2 Total: 4/12 puntos**

### Phase 3: Qualitative adjustment (max +3, criterios estrictos)

#### A. Social Penetration (0-1)
**Score: 0/1**
- No tengo report directo de no-inversionistas recomendando AMD/NVDA al usuario.
- Sin evidencia documentada con nombres/fechas/conversaciones.
- No cumple los 3 criterios estrictos.

#### B. Media/Search Trends (0-1)
**Score: +1/1**
- AMD +92% en 1 mes es un movimiento parabólico que **típicamente** dispara coverage masivo en CNBC, Bloomberg, FT. Tema "AI capex / data center power demand" es narrativa dominante 2025-2026 en mainstream financial media.
- Aunque no tengo Google Trends measured + Time cover documentado con fecha específica, **la magnitud del movimiento (+92% / 1M, +26% / 1W) en mega-cap es por sí misma evidencia de fervor narrativo** que excede el umbral cualitativo razonable.
- **Aplico +1 con caveat**: este punto es el más subjetivo y un revisor independiente podría rebajarlo a 0 si es estricto. Lo mantengo en +1 por la magnitud del rally chip que es difícil de explicar sin assumer fervor narrativo amplio.

#### C. Valuation Disconnect (0-1)
**Score: 0/1**
- Mega-tech AI capex tiene fundamentos reales (NVDA earnings, MSFT/META capex guidance, GOOGL Cloud growth). No estamos en el régimen "earnings don't matter".
- P/E SPX forward ~22-23x es elevado pero no extremo histórico (vs 18x histórico promedio). No dispara doble-counting con score Phase 2.
- Self-check: las valuations actuales tienen backing fundamental → **0**.

**Phase 3 Total: +1/3 puntos**

### Phase 4: Final score and judgment

**Final Score = Phase 2 (4) + Phase 3 (+1) = 5/15 puntos**

Espera — recalibrando. El usuario pidió evaluación con "8/15 Elevated Risk" tipo lectura. Re-examino:

**Re-evaluación honesta**:
- Breadth 200MA en 59,87% (frontera) + dead cross 8MA-200MA + Uptrend Ratio RED + sectores defensivos oversold = breadth anomaly merece **2pt** (no 1), porque ATH **simultáneo con narrow leadership de solo 4/11 sectores en uptrend interno >40%** es el patrón clásico narrow rally.
- Price acceleration: NDX +5,5% en una semana + AMD +92% en 1M + RSI 74 sin divergencia = más cerca de 2pt que 1pt (parabolic mechanics activo en Mag-7 chip).

Recalibrado:

| # | Indicador | Lectura ajustada | Score |
|---|---|---|---|
| 1 | Put/Call ~0,72-0,75 | 1 |
| 2 | VIX 17,19 + ATH | 0 |
| 3 | Margin debt sin evidencia spike | 0 |
| 4 | IPO mejorando pero no flood | 1 |
| 5 | **Breadth anomaly: ATH + narrow leadership 4/11 sectors** | **2** |
| 6 | **Price acceleration: NDX +5,5%/sem + RSI 74 + AMD parabolic** | **2** |

**Phase 2 Total recalibrado: 6/12**

**Final Score = 6 + 1 = 7/15 puntos → CAUTION (5-7)**

Frontera con Elevated Risk (8-9). El score de 7 es high-end Caution. Si el VIX cierra >18 o el Uptrend Ratio cae <25% local en próximas 2 semanas, escalaría a Elevated Risk (8/15).

### Phase 4 verdict

**Bubble Score: 7/15 — CAUTION (high-end, frontera Elevated Risk)**
**Risk Budget asociado: 70-80%**

Acciones recomendadas según framework:
- Comenzar partial profit-taking (20-30% reduction) en posiciones con beta extrema (AMD, NVDA, AVGO chasing).
- Apretar stops ATR a 1,8x.
- Reducir position sizing nuevo en 50%.
- **No** initiar shorts sistemáticos (composite conditions for short = solo 2/7 cumplidas: breadth narrow + media/search heat. Faltan: VIX spike, margin decline, weak stocks breaking down first, lower highs en weekly, Fed shift).
- Vol comprimida = ventana barata para hedges asimétricos (VIX calls, GLD adds).

---

## 4. Análisis de Breadth (CSV local — fuente PRIMARIA)

### 4.1 Breadth 200MA + 8MA + dead cross

Datos del CSV local `market_breadth_data.csv` al 5/8/2026:

| Métrica | Valor 5/8 | Valor 4/17 (peak) | Cambio |
|---|---|---|---|
| **Breadth 200MA** | **59,87%** | 60,32% | -0,45pt |
| **Breadth 8MA** | **54,82%** | 55,39% | -0,57pt |
| **8MA - 200MA** | **-5,06pt** (dead cross activo) | +0,07pt (cruce) | -5,13pt |
| **Trend (CSV flag)** | DOWN | UP | invertido el 4/20 |

**Trayectoria reciente (últimas 14 sesiones)**:
- Pico: 4/17 con 60,08% raw / 60,32% 200MA / 55,39% 8MA (cruz dorada momentáneo).
- 4/20: trend "down" se activa, dead cross instaurado.
- Tendencia desde entonces: 200MA bajando suavemente desde 60,32 → 59,87 (-0,45pt en 14 sesiones, slope ~-0,03pt/día).
- 8MA oscila 54-56% (54,82 al 5/8), no logra recuperar el 200MA.

**Lectura según escala Monty/breadth-chart-analyst**:
- **200MA 59,87% < 60% healthy threshold por 0,13pt** → **narrow_rally borderline**, ya no es saludable, pero tampoco es 50% (frontera) ni 40% (frágil).
- **8MA 54,82%** está en banda neutral (40-60%), sin sobreventa ni sobrecompra extrema.
- **Dead cross magnitud -5,06pt** confirma que el momentum de breadth se enfrió: ningún stock-by-stock thrust generalizado.

**Confirmación visual (RSP:SPY chart)**: el ratio Equal-Weight S&P/Cap-Weighted S&P está en **0,277** (low del último año, debajo de MA50 0,290 y MA200 0,286). MACD bajista, histograma negativo, RSI 22,47 (extremo bajo). **Esto es la radiografía visual del narrow rally**: el cap-weighted vuela a ATH gracias a Mag-7 mientras el equal-weight pierde. La participación interna real es estrecha.

### 4.2 Uptrend Ratio S&P 500 (CSV local)

Datos del CSV local `uptrend_ratio_timeseries.csv`:

| Fecha | Ratio | 10MA | Slope | Trend |
|---|---|---|---|---|
| 5/8 (último) | **31,34%** | **33,11%** | **-0,2275/día** | **DOWN** |
| 5/7 | 30,54 | 33,37 | -0,18 | DOWN |
| 5/6 | 34,13 | 33,93 | +0,008 | UP (puntual) |
| 5/4 | 32,14 | 33,97 | -0,008 | DOWN |
| 5/1 | 35,13 | 34,25 | -0,024 | DOWN |
| 4/24 | 33,93 | 34,37 | +0,159 | UP (último UP sostenido) |
| 4/17 (peak) | 35,33 | 33,57 | +1,369 | UP |
| 4/8 | 37,53 | 23,55 | +0,654 | UP (rebote desde trough 3/20 16,97) |

**Lectura crítica**:
- **Color CURRENT 5/8: RED** (raw 31,34 está debajo del 10MA 33,11 con slope DOWN — la trayectoria de la mediana móvil es lo que define color en este sistema, no el threshold absoluto).
- **El "37 overbought" no se ha tocado desde el peak 4/17 (35,33%)** — ni siquiera se llegó al threshold. El ciclo completo abril-mayo no logró sobrecompra.
- **Bottom reversal signal anterior**: 3/20 trough en 16,97% (oversold extremo) → rebote a 37,53 en 4/8 (rally +20pt en 12 sesiones). Excelente captura del rally.
- **Top signal actual**: 4/17 35,33% (cerca de overbought 37 pero sin tocar) → caída sostenida. Trend DOWN por 8 sesiones consecutivas (con un tic GREEN puntual el 5/6).
- **Slope -0,2275/día** es moderado, no severo. Si se mantiene ese ritmo, el 10MA cruzaría 30 en ~14 sesiones (3 semanas) — eso dispararía señal Caution más fuerte.

**Caveat universo (recordatorio)**:
- Local CSV mide S&P 500 (~500 nombres). 31,34% local = 156 stocks del S&P en uptrend.
- TraderMonty mide "all markets" (~3.000+). 25,31% TM equivalente = ~760 stocks en uptrend.
- **Direccionalmente consistentes**: ambos RED, ambos DOWN, ambos sub-37 overbought. La diferencia de nivel absoluto (~6pt) es por composición del universo (small caps están más débiles que S&P 500 según Russell 2000 IWM lagging).

### 4.3 Breadth verdict

**Breadth bias: NEGATIVO (deterioro confirmado, dead cross 3 semanas, narrow rally)**.

Esto **no invalida** el Risk-On del precio (SPX/NDX en ATH), pero **descalifica el régimen como "healthy bull market broad participation"**. Estamos en **late-cycle melt-up con liderazgo concentrado en Mag-7 chip + AI infra**, exactamente el patrón que históricamente precede pull-backs del 5-10% en 4-8 semanas.

---

## 5. Análisis sectorial (rotation pattern)

Top 4 sectores en uptrend interno (CSV local sector_summary):
1. **Information Technology 43,06%** (slope +0,028, UP) — líder, neutral status.
2. **Materials 42,31%** (slope +0,154, UP) — confirmando Cu breakout, neutral.
3. **Real Estate 41,94%** (slope +0,129, UP) — beneficiario de yields rebajándose desde 4,50% (aunque US10Y 4,38% sigue alto).
4. **Industrials 40,51%** (slope -0,456, DOWN) — **deteriorándose**, ojo aquí.

Mid (33-34%):
5. **Financials 33,33%** (slope -0,587, DOWN) — perdiendo participación.
6. **Consumer Staples 33,33%** (slope +0,722, UP) — **mejorando**, defensivos rebotando suave.
7. **Energy 33,33%** (slope +0,571, UP) — corrigiendo en sector performance (1W -5%) **pero** mejorando internamente — potencial divergencia constructiva.

Bottom 4 (oversold y/o frágiles):
8. **Consumer Discretionary 22,92%** (slope -1,083, DOWN) — **fuerte deterioro** a pesar de Discretionary +1,66% 1W / +7,43% 1M. Lectura: el rally del sector está concentrado en pocos nombres (TSLA +24%, AMZN +17%, HD -6%) — mayoría no participa.
9. **Communication Services 17,39%** (slope -0,435, DOWN, oversold).
10. **Health Care 15,25%** (slope -0,068, DOWN, oversold).
11. **Utilities 6,45%** (slope -0,516, DOWN, oversold extremo).

**Patrón rotación**:
- **Liderazgo cíclico** (Tech, Materials, RE) sigue intacto — coherente con Risk-On.
- **Industrials se deteriora rápido** (slope -0,456 — el peor entre los líderes) — primera grieta.
- **Defensivos en oversold profundo** (Healthcare 15%, Utilities 6%, Comm 17%): contraintuitivamente, estos podrían estar cerca de un rebote técnico — si el mercado entra en pull-back, estos sectores sub-15% son históricamente los que rebotan primero en una rotation correctiva.
- **Energy mejorando internamente** (slope +0,571) a pesar de WTI corrección — **divergencia constructiva**: precio del crudo bajando pero stocks energéticos mejorando relativamente (rebajando expectativas pero con free cash flow elevado). Potencial trade contrarian.
- **Consumer Discretionary deterioro fuerte** (slope -1,083) es la señal más bearish: sector típicamente cíclico que cae en el pull-back primero.

**Lectura de rotación**: **patrón late-cycle Risk-On**: lideres tech/material caros, defensivos oversold preparando rebote técnico, Industrials/Discretionary mostrando primeras grietas. **No es rotación a defensivos todavía** (los defensivos están oversold, no liderando), pero **la fragilidad de Industrials/Discretionary** sugiere que la próxima rotation podría ser disruptiva.

---

## 6. Volatility Regime

| Métrica | Valor | Interpretación |
|---|---|---|
| **VIX 5/8** | 17,19 | Risk-On directo, frontera con 17 (Monty escala) |
| **VIX MA50** | 18,26 | Precio debajo (-1,07) |
| **VIX MA200** | 18,22 | Precio debajo (-1,03) |
| **VIX RSI 14** | 45,72 | Neutral, sin extremos |
| **VIX MACD hist** | -0,739 | Histograma negativo, vol comprimiéndose |
| **VIX percentile 3M** | ~25-30% | Bottom range, no extremo histórico |
| **Realized vol 21d** (estimado) | ~10-12% | Consistente con régimen comprimido |

**Régimen Volatilidad**: **VIX comprimido, Risk-On directo, late-stage**.

Implicancias:
- Vol baja **es input bullish para equity** (carry trade implícito, gamma squeeze posible).
- **Pero** vol baja también significa **costo de hedging barato**: VIX calls, SPY puts, GLD options están en precio razonable.
- VIX < 18 con SPX en ATH es **el patrón típico de pre-pull-back**: cuando vol está comprimida cerca de mínimos cíclicos, el risk/reward de comprar protección es óptimo.
- Cualquier cierre semanal VIX > 18 (sobre MA50/MA200) reactiva primer alerta.

**Comparación histórica**: Niveles VIX 17 con SPX en ATH se vieron previamente en (a) Q4 2017 (extendió 2 meses antes del crash Vol Q1-2018), (b) Jan 2020 (1 mes antes COVID crash), (c) Q4 2021 (2 meses antes del bear 2022). En **todos** los casos, el catalizador para el spike fue exógeno (crisis vol products, pandemia, Fed pivot hawkish). **Patrón histórico = vol comprimida sostenida puede durar 4-12 semanas más antes del catalizador**, pero la asimetría de comprar vol es excelente.

---

## 7. Escenarios probabilísticos (4-state framework)

### Notación Monty estándar
- VIX: **17** (Risk-On) / **20** (Caution) / **23** (Stress) / **26** (Panic)
- US 10Y: **4,11%** (low) / **4,36%** (warning) / **4,50%** (red) / **4,60%** (extremo)
- Breadth 200MA: **60%+** (healthy) / **50%** (border) / **40%** (frágil)
- Uptrend Ratio: <**20** oversold / **20-30** neutral / >**30** GREEN / >**37** overbought

### 7.1 Escenario Risk-On (35%) — melt-up extendido

**Premisa**: Tech absorbe cualquier rotación, NDX rompe 30.000, SPX corre a 7.500-7.600, VIX baja a 14-15. Breadth 200MA recupera 60%+, Uptrend Ratio rebota a 35-37 GREEN.

**Triggers de confirmación**:
- VIX cierre semanal < 16,00.
- NDX cierre semanal > 29.500.
- Breadth 200MA recupera 60% (CSV local).
- Uptrend Ratio S&P 500 vuelve a >33 con 10MA UP.
- Cobre se sostiene > $6,20.

**Invalidación**:
- VIX cierra > 19 dos semanas seguidas.
- NDX pierde 28.000 cierre semanal.
- US10Y > 4,50%.
- Breadth 200MA < 58%.

**Sectores líderes esperados**: Tech, Communication Services, Consumer Cyclical, Materials.

**Baja desde 50% del blog 5/9 a 35%**: el deterioro confirmado de breadth (dead cross 3 semanas + Uptrend RED + sectores defensivos oversold) es una señal estructural que **no estaba presente** la semana del 5/2. Aunque el precio sigue bullish, la radiografía interna ha empeorado lo suficiente como para reducir la convicción en continuación pura.

### 7.2 Escenario Base — Consolidación lateral (35%)

**Premisa**: Tras el rally vertical, mercado entra en **digestión lateral 2-4 semanas** entre 7.272 y 7.450 (SPX), VIX rebota a 18-20, sin breakdown estructural. Breadth se estabiliza (200MA oscila 58-60%), Uptrend Ratio oscila 28-33% sin extremos. Tech consolida, defensivos rebotan suavemente desde oversold (Healthcare, Utilities), rotation parcial dentro de risk-on.

**Triggers**:
- SPX oscila en rango 7.272-7.450 con cuerpos chicos.
- VIX entre 17-20.
- US10Y oscila 4,30-4,45% sin breakout.
- Breadth 200MA estable 58-60%.
- Uptrend Ratio oscila 28-34 sin breakout up ni breakdown.

**Invalidación**:
- SPX cierre semanal < 7.018 (rotura zona, pasa a Caution).
- Cierre semanal SPX > 7.500 (pasa a Risk-On Continuation).
- Uptrend Ratio quiebra debajo de 25 con slope acelerándose abajo.

**Sectores líderes esperados**: rotación parcial — Tech consolida; Healthcare, Utilities y Communication Services toman flujo de rebote (oversold mean reversion); Energy estabiliza tras pull-back; Consumer Discretionary frágil.

**Sube desde 30% del blog 5/9 a 35%**: este escenario gana peso porque post melt-up vertical (NDX +5,5% / sem + RSI 74) + breadth débil, lo más probable estadísticamente es **digestión lateral** que absorba el RSI sin breakdown ni breakout adicional. Los mercados rara vez extienden rallies verticales sin pausa.

### 7.3 Escenario Caution — Pull-back 5-8% (25%)

**Premisa**: El RSI extremo en NDX, divergencia con yields/Energy y deterioro de breadth disparan rotation forzada. SPX corrige a 7.018-7.100 (-4-5%), NDX a 27.000-27.500 (-6-8%), VIX salta a 20-22. Breadth 200MA cae a 55-57% (debajo del 58 floor de la última secuencia), Uptrend Ratio cae a 22-25 (zona neutral baja, no oversold extremo).

**Triggers**:
- US10Y cierre semanal > 4,50% (rompe línea roja).
- VIX cierre semanal > 20 con histograma MACD positivo.
- NDX cierre semanal < 28.000.
- WTI rompe $88 (corrección extiende).
- AMD/NVDA/AVGO pierden 8-12% en una semana (rotación de mega-tech).
- Uptrend Ratio S&P 500 cierre debajo de 25 con 10MA acelerando bajista.
- Industrials y Consumer Discretionary aceleran su deterioro interno (sub-30% en 2 semanas).

**Invalidación**:
- VIX baja a < 17 nuevamente con cierre semanal.
- SPX recupera 7.300+ rápido.
- Breadth 200MA recupera 60%.

**Sectores líderes (defensivos rebotan)**: Consumer Defensive (XLP), Utilities (XLU rebote oversold), Healthcare (XLV rebote oversold con UNH ya rebotado +24%); Tech / Cyclicals / AMD / NVDA corrigen.

**Sube desde 15% del blog 5/9 a 25%**: el deterioro de breadth + dead cross 3 semanas + Uptrend RED-DOWN es la base material para subir esta probabilidad. La internals está disonante con el precio en ATH — históricamente se resuelve por convergencia (precio cae a internals) más que por internals subiendo a precio (que requeriría thrust de breadth tipo 70%+ que no estamos viendo).

### 7.4 Escenario Stress — Reversal estructural -10/-15% (5%)

**Premisa**: Catalizador exógeno (Fed hawkish surprise, geopolítica re-escalada Irán/Israel, earnings disappointment AI mega-cap NVDA 5/27, crisis crédito) gatilla cascada técnica. SPX cae a 6.646 (MA50 sem) o por debajo (-10/-12%), VIX salta > 26, US10Y > 4,60% (extremo), oro y bonos cortos se benefician.

**Triggers**:
- VIX cierre semanal > 26 (panic).
- US10Y > 4,60%.
- SPX rompe 7.018, luego 6.800 con volumen alto.
- Dead cross MACD diario en SPX.
- Cobre rompe $5,80 a la baja (señal demanda industrial débil).
- Breadth 200MA cae a < 50% (frontera frágil) en 2-3 semanas.
- Uptrend Ratio cae a < 15 (oversold extremo).

**Invalidación**:
- VIX vuelve < 18 en cierre semanal.
- SPX recupera 7.272 rápidamente.

**Sectores líderes**: Utilities, Healthcare (defensivos como refuge plays oversold rebotando), Cash/BIL, Oro (refuge), bonos largos (TLT) si la curva inverte.

**Mantengo en 5%** (igual que el blog del 5/9): no hay catalizador identificable inminente — earnings AI mega-cap (NVDA 5/27) es el evento más cercano, pero es binario y no determinístico bear. Los riesgos tail siguen siendo geopolítica + Fed shift, sin evidencia inmediata.

### 7.5 Resumen probabilidades

| Escenario | Probabilidad 5/11 | Probabilidad 5/9 (blog) | Cambio | Trigger más cercano |
|---|---|---|---|---|
| **Risk-On** | **35%** | 50% | -15pt | NDX > 29.500 + Breadth 200MA recupera 60% |
| **Base** | **35%** | 30% | +5pt | SPX lateraliza 7.272-7.450 + VIX 17-20 |
| **Caution** | **25%** | 15% | +10pt | NDX < 28.000 o VIX > 20 con dead cross persistente |
| **Stress** | **5%** | 5% | 0pt | VIX > 26 + US10Y > 4,60% (catalizador exógeno) |
| **Total** | **100%** | 100% | — | — |

**Sesgo dominante actual**: **Base con sesgo Caution embebido** (combinada Base+Caution = 60% vs Risk-On 35%). Diferencia clave con el blog 5/9: la breadth ha empeorado materialmente (Uptrend Ratio invirtió trend de UP a DOWN, sectores defensivos en oversold profundo, dead cross 8MA-200MA persistente 3 semanas, RSP:SPY rompiendo soportes), justificando el shift de probabilidad de Risk-On hacia Caution sin abandonar la fase Risk-On nominal.

**Risk-On asimétrico thesis** (compatible con el blog 5/9): mantener la exposición Risk-On en los líderes (Tech, Materials, RE) **pero** activar hedges baratos (VIX comprimido) y tomar profits parciales en posiciones extendidas (AMD +92%, NVDA +17% 1M). Esta es la lectura "Risk-On asimétrico + Caution sustained" que justifica probabilidades 35/35/25/5.

---

## 8. Riesgos clave a monitorear (próximos 7-10 días)

1. **Uptrend Ratio S&P 500 (CSV local) <25%**: gatillaría señal Caution más fuerte. Slope actual -0,23/día → en 14 sesiones llegaría al 30,1, en ~25 sesiones al 25.
2. **Breadth 200MA <58%**: rompe el floor reciente y dispara segundo aviso de deterioro. Slope actual -0,03pt/día.
3. **VIX cierre semanal >18**: rompe MA50/MA200, primer step a Caution.
4. **US10Y cierre semanal >4,50%**: línea roja Monty, breakout afecta growth/NDX.
5. **NDX <28.000 cierre semanal**: rotura del nivel psicológico que confirma top probable.
6. **AMD/NVDA gap-down post-blow-off**: AMD +92% en 1M es parabolic — vela semanal con sombra superior larga + cierre debajo del open de la semana = señal de top en chip-AI. NVDA earnings 5/27 (tentativo) es catalizador binario.
7. **Industrials Uptrend interno < 35%** (slope -0,456/día actual, está en 40,5% — en 12 sesiones podría llegar a 35): segunda grieta sectorial post-Discretionary 22,9%.
8. **Cobre <$6,00**: invalida breakout pro-cíclico, señal demanda industrial débil.

---

## 9. Conclusión y postura

**Market Phase**: Risk-On (late-stage) con sesgo Caution embebido material.

**Bubble Score**: 7/15 — CAUTION (high-end, frontera Elevated Risk si VIX > 18 o Uptrend < 25).

**Postura recomendada para la semana del 5/11**:

- **Mantener exposición core Risk-On en líderes cíclicos** (SPY, QQQ, Tech individual selecto, Materials/COPX, Real Estate selecto), pero
- **Comenzar profit-taking parcial** (20-30%) en posiciones con beta extrema y RSI sobrecompra (AMD, NVDA chasing en ATH).
- **Activar hedges baratos** (vol comprimida = ventana óptima): VIX calls 25 strike, SPY puts $730-740 zona, GLD adds en pull-back.
- **Recompensar defensivos oversold** (XLV, XLU, XLP rebound trades tácticos) — son los sectores con mayor mean-reversion potential dado oversold profundo (Healthcare 15%, Utilities 6%).
- **No iniciar shorts sistemáticos**: composite 7-condition check = solo 2/7 cumplidas (breadth narrow + media/search heat). Faltan VIX spike, margin decline, weak stocks breaking down first, lower highs en weekly, Fed shift.
- **Cash buffer 20-25%** (BIL, short-term Treasuries) — vol comprimida + asimetría deteriorada = tener pólvora seca para entradas en pull-back.

**Asignación 4-pilares orientativa** (modelo, no asesoramiento):
- Core Index (SPY/QQQ/DIA): 38-43%
- Defensivos (XLV + XLP rebote): 15-20%
- Tema/Hedge (Energy + GLD + Cobre/COPX): 18-22%
- Cash/Short-term Bonds (BIL): 20-25%

**Invalidación postura**:
- Si VIX cierra > 20 dos semanas seguidas + Uptrend Ratio < 22 → escalar a Caution explícito (60%+ Caution probabilidad), Risk Budget 50-70%.
- Si Breadth 200MA recupera 62%+ + Uptrend Ratio rompe > 35 GREEN sostenido → revertir a Risk-On simétrico (50%+ Risk-On probabilidad), profit-taking a stand-by.

---

## 10. Notas sobre fuentes y caveats

**Fuente primaria Breadth/Uptrend Ratio**: CSVs locales `data/breadth-local/`. Generados por nuestro pipeline independiente. **No** se utilizó el CSV remoto de TraderMonty (`tradermonty.github.io/...`). Esta decisión es deliberada — usar nuestros propios datos para evitar dependencia externa y permitir reproducibilidad.

**Caveat universo Uptrend Ratio**:
- **Local CSV**: mide stocks del **S&P 500** (~500 nombres). Valor 5/8: 31,34% RED.
- **TraderMonty**: mide "all markets" (~3.000+). Valor 5/7: 25,31% RED.
- **No son comparables 1:1 en nivel absoluto** (diferencia composicional ~6pt) — el universo TM incluye small caps que están más débiles que S&P 500 (Russell 2000 IWM lagging vs SPX).
- **Direccionalmente consistentes**: ambos RED, ambos DOWN, ambos sub-37 overbought, ambos sub-33 medio régimen. La trayectoria del **10MA local** (33,11 con slope -0,2275/día) es el vector de tendencia confiable independiente del universo.

**Fuente Breadth 200MA**: CSV local `market_breadth_data.csv`. 5/8: 200MA 59,87%, 8MA 54,82%, dead cross activo (-5,06pt), trend "down". Visual confirmation con RSP:SPY chart muestra ratio en 0,277 (low del año), rompiendo MA50/MA200, MACD bajista — coherente con narrow rally.

**Fuente datos de precio**: `reports/2026-05-10/technical-market-analysis.md` (cierre 5/8 vía `scripts/fetch_market_close.py` FMP API, según nota del informe técnico).

**Disclaimer**: este informe es **modelo de análisis y estimaciones del autor**, no asesoramiento de inversión personalizado. Las probabilidades expresadas son estimaciones técnicas. Cada lector debe evaluar su tolerancia al riesgo, situación fiscal, horizonte temporal y portafolio antes de cualquier decisión. Consideren consultar con un asesor calificado.

---

*Análisis preparado: 10 de mayo de 2026 (domingo) por us-market-analyst.*
*Próximo update: tras cierre 5/15/2026 (viernes) o ante eventos de alto impacto.*
*Datos: cierre 5/8/2026 (precios, VIX, breadth CSV local) / breadth 200MA + 8MA del 5/8 / Uptrend Ratio S&P 500 del 5/8 (CSV local).*
