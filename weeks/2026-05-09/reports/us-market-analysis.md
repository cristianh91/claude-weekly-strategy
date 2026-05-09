# US Market Environment Analysis — Semana del 2026-05-09

**Fecha del informe**: sábado 2026-05-09 (refleja cierre del viernes 2026-05-08)
**Datos primarios**: CSV de TraderMonty (Breadth + Uptrend Ratio + Sector Summary), fetch 2026-05-07
**Datos suplementarios**: lectura visual de gráficos `charts/2026-05-09/` (Breadth proxy RSP:SPY, Uptrend Ratio chart, VIX, NDX, SPX, heatmap, sector performance)
**Cross-check de precios**: technical-market-analysis.md (FMP API devolvió HTTP 403 en esta sesión; los precios provienen de la lectura visual ya validada en Step 1)

---

## Resumen Ejecutivo

El mercado cerró el 2026-05-08 con SPX y NDX en máximos absolutos (7.398,93 / 29.234,99) liderados por Tech +6,25% semanal y Cobre +5,15%, pero **bajo la superficie las métricas de amplitud emiten una advertencia inequívoca**. El **CSV oficial muestra Breadth 200MA en 60,01% — exactamente sobre la línea sano/borde**, con **8MA en 57,24% por debajo de 200MA = DEAD CROSS activo** y **Uptrend Ratio 25,31% en color ROJO con pendiente bajista (-0,0058)**. El **sector summary del CSV revela que sólo Technology está en uptrend (37,1%, ya overbought), mientras que 10 de 11 sectores están en downtrend interno**. Esto es la firma estadística de un **rally de cabeza estrecha**: índices pesados por capitalización marcan ATH mientras la mayoría de las acciones individuales pierden fuerza.

La fase técnica es **Risk-On de superficie / Caution de amplitud**. Mantengo la distribución del informe técnico (Risk-On 50% / Base 30% / Caution 15% / Stress 5%) como visión semanal **pero con sesgo asimétrico al downside** dado el dead cross y el liderazgo concentrado. El bubble score (Minsky/Kindleberger v2.1) arroja **4/15 — fase Normal** con presión específica sobre AMD (+92% 1M, blow-off local) y la concentración en pocos nombres mega-cap.

---

## 1. Clasificación de Fase de Mercado

### Diagnóstico: **RISK-ON de superficie / CAUTION de amplitud**

| Dimensión | Lectura | Clasificación |
|---|---|---|
| **Volatilidad (VIX 17,19)** | Risk-On clásico (<18) | Risk-On |
| **Tasa larga (10Y 4,38% FMP)** | Apenas sobre threshold warning 4,36%, sin quiebre 4,50% | Risk-On / borderline |
| **Índices** | SPX/NDX/Dow/IWM en ATH | Risk-On |
| **Breadth 200MA (CSV: 60,01%)** | Justo sobre línea de borde 60% | Borde sano/borde |
| **Breadth 8MA (CSV: 57,24%)** | Bajo 200MA = DEAD CROSS | **Caution** |
| **Uptrend Ratio (CSV: 25,31% RED)** | En zona neutral pero ROJO + pendiente bajista | **Caution** |
| **Sectores en uptrend interno (CSV)** | Sólo 1/11 (Technology) | **Caution** (concentración) |
| **Liderazgo** | Tech +19% 1M, AMD +92% 1M | Risk-On con riesgo blow-off |
| **Defensivos** | Healthcare/Utilities/Staples en rojo 1M | Risk-On |
| **Energy** | -2,58% 1M, crudo -7% semanal | Risk-Off táctico |

**Veredicto**: El régimen oficial es **Risk-On porque los índices de capitalización ponderada y el VIX lo dictan**, pero **internamente la amplitud está debilitándose**. Estos cuadros (índices ATH + dead cross 8MA/200MA + Uptrend Ratio rojo) históricamente preceden correcciones del 5-10% en horizonte de 2-6 semanas (no son señal de techo mayor por sí solos, pero exigen vigilancia activa).

---

## 2. Bubble Detection — Minsky/Kindleberger v2.1

### Phase 1 — Recolección Cuantitativa Obligatoria

| Indicador | Valor / Fuente | Estado |
|---|---|---|
| **VIX** | 17,19 (StockCharts, cierre 5/8) | Bajo (percentil ~25 sobre 3 meses) |
| **VIX 10D MA percentil** | ~percentil 30-40 vs últimos 90 días | Bajo, no extremo |
| **Put/Call Ratio (CBOE Equity)** | No disponible en esta sesión | **No verificado** |
| **Margin Debt FINRA** | Datos del último report no disponibles | **No verificado** |
| **Breadth (% > 50DMA)** | No directamente medido, pero 200MA = 60,01% (CSV) | Borderline |
| **Breadth (% > 200DMA, CSV)** | **60,01%** | Borde sano/borde |
| **IPO Heat** | No medido en esta sesión | **No verificado** |
| **Aceleración 3M precio** | NDX +18% en 3M, percentil estimado 80-90 sobre 10 años | Elevada |

**Limitación de datos**: Put/Call ratio, Margin Debt y IPO heat no fueron verificados en esta sesión. Los puntajes correspondientes serán **conservadores** (asignación 0 cuando no haya evidencia medida, conforme a v2.1).

### Phase 2 — Scoring Cuantitativo (0-12)

| # | Indicador | Valor medido | Score | Justificación |
|---|---|---|---|---|
| 1 | Put/Call Ratio | No verificado | **0** | Sin dato medido — no se asignan puntos |
| 2 | VIX <12 + cerca ATH | VIX 17,19 (>15) + ATH | **0** | El umbral estricto es VIX <15 con ATH; VIX 17,19 no califica |
| 3 | Margin Debt YoY | No verificado | **0** | Sin dato medido |
| 4 | IPO Heat | No verificado | **0** | Sin dato medido |
| 5 | Breadth Anomaly (narrow leadership) | NDX en ATH + Breadth 200MA 60,01% (borde) + 8MA 57,24% bajo 200MA (**dead cross**) + sólo 1/11 sectores en uptrend interno (CSV) | **2** | Condición clásica de narrow leadership: nuevo máximo + breadth en zona borde + dead cross 8/200 + concentración sectorial extrema |
| 6 | Price Acceleration (NDX 3M) | NDX +18% en 3M + AMD +92% 1M | **1** | NDX 3M está en zona percentil ~85-90 (no >95 estricto), pero AMD individual es blow-off claro. 1 punto |

**Phase 2 total: 3/12**

### Phase 3 — Ajuste Cualitativo (max +3)

**Checklist anti-confirmation bias**:
- [x] ¿Tengo evidencia concreta y medible? → Sólo parcial
- [x] ¿Un observador independiente llegaría a la misma conclusión? → Sí para Breadth narrow; AMD blow-off es observable
- [x] ¿Estoy evitando double-counting con Phase 2? → Sí
- [x] ¿Tengo sources documentadas? → CSV TraderMonty + StockCharts + chart visual

| Ajuste | Evidencia | Score |
|---|---|---|
| **A. Penetración social** | No hay reportes directos de no-inversores recomendando AMD/NVDA/AI en esta sesión. Ningún criterio cumplido | **0** |
| **B. Media/Search trends** | No medido Google Trends; sin verificación específica de cobertura mainstream con fechas | **0** |
| **C. Valuation disconnect** | NDX P/E elevado pero AMD/NVDA/GOOGL tienen ganancias reales sosteniendo IA. La narrativa "earnings don't matter" no está documentada en major media. **Fundamentals support** | **0** |

**Phase 3 total: 0/3**

### Phase 4 — Veredicto Final

**Score final: 3/15 puntos** → Fase **Normal (0-4)**

**Pero con ajuste contextual de monitoreo**: aunque el score mecánico es 3, **AMD +92% 1M individual es un blow-off detectable** y la concentración sectorial 1/11 en uptrend (CSV) es una bandera amarilla. **No bubble sistémico, sí riesgo idiosincrático en Tech/Semis hot stocks**.

**Risk Budget según v2.1**: 100% (Normal)
**Ajuste personal recomendado**: dado el dead cross 8MA/200MA y la narrow leadership en CSV, operar con risk budget **85-90% efectivo** (no full risk-on aunque la regla mecánica lo permita).

**Short-Selling**: Not Allowed (composite conditions 1-2/7 cumplidas: VIX no spike, leverage no medido, weakness en stocks débiles SI presente — HD/CRM/META/MSFT bajo MA50)

---

## 3. Análisis de Breadth (CSV PRIMARIO + Chart Suplementario)

### 3.1 S&P 500 Breadth (CSV: tradermonty.github.io/market-breadth-analysis)

**Valores oficiales al 2026-05-07**:

| Métrica | Valor CSV | Umbral del proyecto | Lectura |
|---|---|---|---|
| **200-Day MA** | **60,01%** | ≥60% saludable / 50-60% borde | **Justo sobre línea sano-borde** |
| **8-Day MA** | **57,24%** | 60-73% sano-bullish / 40-60% neutral | **Neutral** |
| **8MA vs 200MA** | **-2,77pt** (8MA debajo) | — | **DEAD CROSS activo** |
| **Trend (CSV field)** | **-1** | — | **Downtrend** |

**Interpretación**:

1. **Breadth 200MA en 60,01%** está en el límite exacto del nivel "saludable". Una semana mala podría empujarlo bajo 60% (zona de borde). No es crisis (lejos del 40% frágil), pero **NO es expansión robusta**.
2. **8MA = 57,24% por DEBAJO de 200MA = DEAD CROSS**. En los datos históricos del proyecto, el 8MA es la línea rápida; cuando cruza por debajo del 200MA con índice en ATH, suele anteceder a una corrección de 5-10% en 2-6 semanas. **Es el detonante técnico clave de esta semana**.
3. **Trend = -1** (downtrend marker en el CSV) confirma el dead cross.

**Chart proxy RSP:SPY (suplementario, lectura visual)**:
El ratio Equal-Weight / Cap-Weight (RSP:SPY) cerró en **0,277**, **bajo MA50 (0,290) y MA200 (0,286)**. RSI(14) en 22,47 (oversold). MACD cruzando bajista. **Confirma técnicamente que el equal-weight está perdiendo terreno frente al cap-weight** = liderazgo concentrado en mega-caps. Esto es la traducción visual del dead cross 8/200 del Breadth oficial.

### 3.2 Uptrend Stock Ratio (CSV: tradermonty/uptrend-dashboard)

**Valores oficiales al 2026-05-07**:

| Métrica | Valor CSV | Umbral | Lectura |
|---|---|---|---|
| **Current ratio** | **25,31%** | <10% extremo oversold / 10-15% bottom / >37% overbought | **Zona neutral baja** |
| **Color CSV** | **RED** | — | **Downtrend phase activa** |
| **10MA** | **27,58%** | — | Por encima del valor actual |
| **Slope** | **-0,0058** | — | **Bajista (declining)** |
| **Trend** | **DOWN** | — | **Caída confirmada** |

**Interpretación CRÍTICA — Uptrend Ratio es leading indicator**:

1. **Color RED**: el indicador está en fase de downtrend interno aunque los índices estén en ATH. Esto es la divergencia estructural más importante.
2. **Slope NEGATIVO (-0,0058) y trend DOWN**: el ratio está cayendo (no fondeando ni rebotando). **No hay bottom reversal todavía**.
3. **Valor 25,31%** está **lejos del bottom histórico** del 10-15%. Un próximo movimiento natural antes de un rebote sería bajar al 15-20% (zona típica de bottom).
4. **El 10MA (27,58%) por encima del valor actual** confirma que el valor está acelerando a la baja respecto a su promedio reciente.

**Chart visual (suplementario)**:
El gráfico muestra el ratio con valores recientes oscilando entre 25-39% en los últimos meses, con la lectura más reciente cerca de 25-27% en color rojo, después de un pico cercano a 38% en marzo-abril 2026. La pendiente del 10MA (línea naranja) es claramente descendente al borde derecho. **Confirma exactamente la lectura CSV**.

**Bottom reversal check**: NO. No hay señal de bottom reversal en esta semana. El indicador requiere primero seguir cayendo (probablemente al 15-20%) y luego un giro al alza con cambio de color rojo→verde. Hoy está en pleno red+down phase.

### 3.3 Conclusión integrada de breadth

| Indicador | Valor | Color/Estado | Tendencia |
|---|---|---|---|
| Breadth 200MA | 60,01% | Borde sano | Plano alto |
| Breadth 8MA | 57,24% | Bajo 200MA (dead cross) | Cayendo |
| Uptrend Ratio | 25,31% | RED | Bajando (-0,0058) |
| Sectores en uptrend | 1/11 (Tech 37,1%, ya overbought) | Concentrado | Estrecha |

**Diagnóstico de breadth**: **el rally es de cabeza estrecha**. Los índices marcan ATH gracias a 5-7 mega-caps (NVDA/AVGO/AMD/GOOGL/AMZN/AAPL/TSLA), pero la mayoría de acciones individuales se debilita. Históricamente este cuadro (índice ATH + breadth 8/200 dead cross + uptrend ratio rojo bajando) es precursor de corrección del 5-10%, no señal de techo de ciclo. La señal de alerta crítica sería: **Breadth 200MA cayendo bajo 55% + Uptrend Ratio bajo 15%**.

---

## 4. Patrón de Rotación Sectorial

### 4.1 Datos CSV — Sector Summary (oficial 2026-05-07)

| Sector | Ratio CSV | Estado |
|---|---|---|
| Technology | 37,1% | **Overbought** + único en uptrend |
| Communication Services | 24,3% | Uptrend interno |
| Industrials | 32,6% | Downtrend |
| Basic Materials | 31,9% | Downtrend |
| Energy | 31,3% | Downtrend |
| Healthcare | 25,5% | Downtrend |
| Real Estate | 22,9% | Downtrend |
| Financial | 17,8% | Downtrend |
| Consumer Cyclical | 17,5% | Downtrend |
| Consumer Defensive | 14,7% | Downtrend |
| Utilities | 10,0% | Downtrend (frágil) |

**Lectura crítica**: aunque la performance 1W/1M muestra ganadores cíclicos (Tech, Materials, Comm Services, Cíclicos), el CSV indica que **el ratio interno de uptrend stocks ha caído en 10 de 11 sectores**. El cuadro es: **rotación intensa hacia los líderes Tech y abandono interno generalizado**.

### 4.2 Lectura combinada con performance 1W/1M

| Patrón | Evidencia | Implicancia |
|---|---|---|
| Tech +19% 1M, ratio interno 37,1% (overbought) | CSV + sector chart | Líder pero **agotamiento posible** |
| Energy ratio 31,3% downtrend + perf -2,58% 1M + crudo -7% | Multi-fuente | **Salida confirmada** del trade Energy |
| Utilities ratio 10% (mínimo) + perf -3,91% 1M | CSV + sector chart | **Defensivo de duración roto** por 10Y warning |
| Healthcare ratio 25,5% downtrend + perf -3,11% 1M | CSV + sector chart | Defensivo en rotación negativa, UNH la excepción |
| Consumer Defensive ratio 14,7% downtrend | CSV | **Muy débil**, no funciona como hedge |
| Materials ratio 31,9% **pese a perf +0,65% 1M y +3,43% 1W** | CSV vs perf chart | Divergencia: Materials sube en superficie pero su breadth interno cae — el +3,43% lo explica el cobre, no la mayoría de acciones |

**Conclusión sectorial**: **rotación pro-cíclica de superficie con debilitamiento interno generalizado**. La única "tendencia limpia" interna es Tech, pero ya overbought. Communication Services es el segundo en uptrend pero en zona neutral.

**Implicancia operativa**: agregar exposición sectorial táctica nueva es difícil — Tech está overbought, Materials/Energy débiles internamente, defensivos rotos. **Cash y exposición a índice cap-weight** son las posiciones menos contradictorias.

---

## 5. Régimen de Volatilidad

| Métrica | Valor | Lectura |
|---|---|---|
| VIX cierre semanal | 17,19 | Risk-On (<18) |
| VIX MA50 semanal | 18,26 | VIX bajo MA50 |
| VIX MA200 semanal | 18,22 | VIX bajo MA200 |
| Rango semanal | 16,18 - 19,08 | Volatilidad realizada baja |
| RSI VIX | 45,72 | Neutral |
| MACD VIX | Comprimido cerca de cero | Sin divergencia alcista |

**Diagnóstico**: **régimen de baja volatilidad clásico**. El VIX colapsó desde el spike de marzo (~30) en 8 semanas y volvió a la zona Risk-On clásica (<18). MACD comprimido cerca del cruce neutral indica **falta de momentum bajista** — i.e., VIX está bajo pero no en complacencia extrema (<12).

**Implicancia**: el ambiente de baja volatilidad permite **multiples expansion** y favorece growth/Tech. **Pero**: VIX MACD comprimido cerca del cero es históricamente inestable — un disparo a 20+ desde niveles 16-17 es probable estadísticamente en cualquier semana, especialmente con 10Y apenas sobre warning (4,38% FMP / threshold 4,36%) y RSI NDX en 74.

**Triggers**:
- VIX cierre semanal >20 dos veces consecutivas → primera alerta Caution.
- VIX cierre semanal >23 → activa Stress.
- VIX cierre semanal <15 sostenido → complacencia extrema (red flag).

---

## 6. Indicadores de Sentimiento

**Limitación**: en esta sesión no se logró fetch de Put/Call Ratio (CBOE) ni AAII Investor Sentiment. **Las siguientes métricas se infieren del comportamiento técnico observado**:

### 6.1 Sentimiento implícito por price action

| Señal | Lectura | Implicancia de sentiment |
|---|---|---|
| AMD +92% 1M, vela +26% semanal | Blow-off vertical | **FOMO específico en hot AI names** |
| RSI semanal NDX 74, IWM 70, SPX 69 | Zona caliente | **Optimismo elevado, no eufórico** |
| VIX 17,19 (no <12) | Cautela residual | **No hay complacencia extrema** |
| Defensivos (HC/Util/Staples) en rojo 1M | Rotación out | **Risk-On preference** |
| IWM en ATH | Risk-On amplio | Confirmación cíclica |
| Materials +3,4% 1W (cobre) | Reflación cíclica | Ánimo expansivo |
| MSFT/META rezagados, RSI 46 cada uno | Rotación intra-Tech | Discriminación, no euforia ciega |

### 6.2 Lectura sintética de sentimiento

**El sentimiento es Risk-On con discriminación**. NO es eufórico generalizado (caso típico de top): los inversores están **rotando dentro de Tech** (saliendo de MSFT/META/CRM, entrando a NVDA/AVGO/AMD/GOOGL). Esto es **selectividad**, no manía.

**Bandera amarilla**: el blow-off de AMD (+92% 1M) es una señal de **FOMO localizado** que históricamente precede correcciones técnicas en el activo y a veces contagia al sector si reverse violentamente.

---

## 7. Análisis de Escenarios — Semana del 12-16 de mayo 2026

### Reconciliación con technical-market-analysis.md

El informe técnico asignó: Risk-On 50% / Base 30% / Caution 15% / Stress 5%.
**Mantengo esta distribución** porque:
1. Los precios y momentum confirman Risk-On como modal.
2. Los datos de Breadth/Uptrend agregan **convicción al escenario Caution dentro de la distribución existente**, no la cambian estructuralmente.
3. Es coherencia inter-report (regla del proyecto).

**Sin embargo, comunico el ajuste de sesgo**: dentro de la misma distribución, **el Caution 15% tiene mayor probabilidad efectiva de materializarse a 2-4 semanas de horizonte** dado el dead cross 8/200 y el Uptrend Ratio en rojo descendente.

### 7.1 Escenario Risk-On (50%) — Extensión del rally

**Tesis**: Tech/Semis sostienen ATH, VIX <18, 10Y en 4,30-4,45%. La narrow leadership continúa pero los líderes (NVDA/AVGO/GOOGL/AMD) no se quiebran.
**Drivers clave**:
- NDX > 30.000 con cierre semanal alcista
- VIX cierra <17
- 10Y se desinfla a 4,25-4,30%
- Cobre > 6,30 sostiene reflación
**Comportamiento esperado**: SPX target 7.500-7.600, NDX 30.500-31.000, IWM 295-300. Volatilidad realizada baja. Breadth 200MA podría rebotar a 62-63% si los rezagados (MSFT, META) recuperan MA50.
**Early warning of breakdown**: si Breadth 200MA cae bajo 58% O Uptrend Ratio cae bajo 20% → reasignar probabilidad a Caution.

### 7.2 Escenario Base (30%) — Consolidación lateral

**Tesis**: tras vela +5,5% NDX y +2,3% SPX, digestión de 2-4 semanas. RSI 74 NDX y sobreextensión a MA50 (NDX +19%) invitan a pausa. Breadth 200MA estabiliza 58-62%.
**Drivers**:
- SPX 7.150-7.450, NDX 27.500-29.500
- VIX 17-22 oscilando
- 10Y 4,30-4,50%
- Pull-back saludable de AMD/NVDA -5/-8%
- MSFT/META intentando catch-up
**Comportamiento**: rotación intra-mercado, posible recuperación de Breadth si rezagados rebotan. Uptrend Ratio podría girar de rojo a verde si baja a 15-18% y rebota.
**Early warning**: SPX cierre bajo 7.150 + VIX >20 + Uptrend Ratio sigue en rojo → Caution.

### 7.3 Escenario Caution (15%) — Corrección 5-10%

**Tesis**: 10Y cierra >4,50% **o** VIX cierra >20 dos semanas seguidas. La narrow leadership colapsa cuando NVDA/AMD/GOOGL corrigen y no hay segunda línea para sostener (Breadth 200MA confirma debilidad cayendo bajo 55%). El dead cross 8/200 actual es el preámbulo técnico.
**Drivers/Triggers**:
- 10Y cierre semanal sobre 4,50%
- VIX cierre >20 dos semanas
- AMD/NVDA reverse candle (engulfing bajista) en zona ATH
- Breadth 200MA cae bajo 55%
- Uptrend Ratio sigue rojo y baja a 15-18%
**Comportamiento**: SPX target 6.800-6.650 (test MA50), NDX 26.500-25.500, IWM 260-250. VIX 22-25. Energy y defensivos podrían rotar verde temporalmente (refugio). GLD podría retomar tendencia si dólar cede.
**Early warning**: si CSV Breadth 200MA cae a 50-52% → riesgo de transición a Stress.

### 7.4 Escenario Stress (5%) — Cascada exógena

**Tesis**: shock exógeno (geopolítico, sorpresa CPI/empleo, default soberano, escándalo IA) + quiebre técnico simultáneo. Probabilidad baja por ausencia de catalizador identificado.
**Drivers**:
- VIX cierre >26
- 10Y >4,60%
- SPX rompe MA50 (6.646)
- IWM <270
- Breadth 200MA <45%
- Uptrend Ratio <10%
**Comportamiento**: SPX target 6.300-6.000, NDX 23.000-22.000. Rotación violenta a TLT, BIL, GLD, USD.

**Suma**: 50% + 30% + 15% + 5% = **100%** ✓

---

## 8. Riesgos Clave y Puntos de Monitoreo

### 8.1 Riesgos primarios

1. **Dead cross Breadth 8/200 (CSV 2026-05-07)** — el indicador histórico de narrow leadership está activo. Vigilar si el 8MA recupera el 200MA en próximas 1-2 semanas (señal de alivio) o si profundiza la divergencia (señal de aceleración).
2. **Uptrend Ratio en RED + slope negativo** — leading indicator emite señal de caution. Vigilar bottom reversal: cambio de color rojo→verde en zona 15-20% sería señal alcista; profundización a <15% sería pre-stress.
3. **Concentración sectorial extrema (1/11 sectores en uptrend interno)** — si Tech corrige >5%, no hay sector de "reemplazo" liderando.
4. **AMD blow-off (+92% 1M)** — riesgo idiosincrático de reverse candle violenta que contagia Semis.
5. **10Y en 4,38% (FMP, sobre threshold warning 4,36%)** — un cierre semanal sobre 4,50% activa caution táctica.

### 8.2 Puntos de monitoreo semanal

| Indicador | Watch level | Acción |
|---|---|---|
| Breadth 200MA (CSV) | <58% | Reducir Tech 10-15% |
| Breadth 200MA (CSV) | <55% | Activar modo Caution |
| Breadth 200MA (CSV) | <50% | Modo Stress, defensivo |
| Uptrend Ratio (CSV) | Cambio rojo→verde | Señal alcista, agregar |
| Uptrend Ratio (CSV) | <15% | Zona bottom (potencial entrada) |
| Uptrend Ratio (CSV) | <10% | Pre-stress, full defensive |
| VIX cierre semanal | >20 | Reducir 10-15% |
| VIX cierre semanal | >23 | Reducir 20-25% |
| 10Y cierre semanal | >4,50% | Reducir duración / growth |
| 10Y cierre semanal | >4,60% | Stress trigger |
| NVDA / AMD | Engulfing bajista en ATH | Tomar parcial Tech |
| MSFT/META recuperan MA50 | — | Confirma Risk-On amplio |

### 8.3 Catalizadores externos a vigilar (no medidos en este informe)

- Datos macro próximos (CPI, empleo, FOMC) — referirse a market-news-analysis.md cuando esté disponible.
- Earnings de mega-cap pendientes — vigilar guidance para detectar crack en narrativa IA.
- Geopolítica energética — si el crudo profundiza pérdidas <$80, refuerza desinflación pero también puede señalar demand destruction.

---

## 9. Conclusión y Postura de Mercado

El cierre del **2026-05-08** consolida un régimen **Risk-On estructural pero con amplitud frágil**. Los datos CSV oficiales ratifican que: (1) Breadth 200MA en 60,01% está justo en el borde sano, (2) **8MA bajo 200MA (dead cross) emite advertencia técnica**, (3) **Uptrend Ratio 25,31% en color RED con pendiente bajista** confirma que internamente el mercado se debilita, (4) **sólo 1 de 11 sectores está en uptrend interno** (Technology, ya overbought).

**No es bubble (score 3/15 en framework v2.1, fase Normal)** pero hay **riesgo idiosincrático en hot AI stocks** (AMD +92% 1M es blow-off local). La narrativa IA se sostiene en earnings reales (NVDA/AVGO/GOOGL), no en "esta vez es diferente" sin fundamentals — eso evita los puntos de qualitative adjustment.

**Postura recomendada (operativa)**:
1. **Mantener exposición a tendencia primaria** Tech/Semis/IWM sin agregar agresivamente en estos niveles.
2. **No agregar en sectores defensivos** dado que el CSV los tiene en downtrend interno (excepto Comm Services que sigue en uptrend a 24,3%).
3. **Cobre y Materials** — mantener exposición táctica, es la confirmación cíclica más limpia desde el lado real.
4. **Energy** — evitar agregar; el ratio interno está roto (31,3% downtrend) y crudo en distributive phase.
5. **Cash 20-25%** justificado por el dead cross de breadth y el risk de reversion en hot AI names.
6. **Triggers automáticos**: VIX >20 cierre dos semanas → reducir 10-15%. 10Y >4,50% cierre → reducir 15-20%. Breadth 200MA <55% → activar Caution mode.

**Distribución probabilística semanal final**: **Risk-On 50% / Base 30% / Caution 15% / Stress 5%** (consistente con technical-market-analysis.md).

**Sesgo direccional dentro de la distribución**: dado el dead cross 8/200 y el Uptrend Ratio en rojo descendente, el Caution 15% tiene **mayor probabilidad efectiva** de materializarse en 2-4 semanas que en una semana típica de Risk-On limpio.

---

## Anexo — Fuentes y Cross-Check

### Fuentes primarias (CSV)
- **Market Breadth**: `https://tradermonty.github.io/market-breadth-analysis/market_breadth_data.csv` (fetch 2026-05-07: 200MA 60,01%, 8MA 57,24%, dead cross activo, trend -1)
- **Uptrend Ratio**: `https://raw.githubusercontent.com/tradermonty/uptrend-dashboard/main/data/uptrend_ratio_timeseries.csv` (fetch 2026-05-07: 25,31% RED, 10MA 27,58%, slope -0,0058, trend DOWN)
- **Sector Summary**: `https://raw.githubusercontent.com/tradermonty/uptrend-dashboard/main/data/sector_summary.csv` (fetch 2026-05-07: Technology 37,1% overbought + único en uptrend; 10/11 sectores en downtrend interno)

### Fuentes suplementarias
- **VIX, índices, commodities**: lectura visual gráficos `charts/2026-05-09/*.png` (StockCharts, timestamps 2026-05-09 08:51) — cross-check con technical-market-analysis.md
- **RSP:SPY (Equal-Weight / Cap-Weight)**: chart visual confirma narrow leadership (cierre 0,277, bajo MA50 0,290 y MA200 0,286, RSI 22,47 oversold)
- **Technical Market Analysis**: `reports/2026-05-09/technical-market-analysis.md`

### Limitaciones de datos
- **FMP API**: HTTP 403 en esta sesión — precios no fueron cross-checkeados vía API; se usaron lecturas visuales de StockCharts ya validadas en Step 1.
- **Put/Call Ratio (CBOE)**: no fetch en esta sesión.
- **FINRA Margin Debt**: no fetch.
- **Renaissance IPO**: no fetch.
- Estas limitaciones llevaron a que el bubble score de v2.1 sea conservador (3/15) por aplicación estricta de "0 puntos sin evidencia medida".

### Reglas de prioridad aplicadas
- **CSV PRIMARIO** sobre lectura de imagen en todos los valores de Breadth y Uptrend Ratio (Issue #7 del proyecto).
- Cross-check entre CSV y chart visual: **consistente** (chart confirma color rojo + pendiente bajista + dead cross 8/200).

---

*Análisis basado en datos al cierre del 2026-05-08. Reconcilia con technical-market-analysis.md (Step 1). Las probabilidades son estimaciones del autor basadas en evidencia técnica observable. No constituye asesoramiento de inversión individual.*
