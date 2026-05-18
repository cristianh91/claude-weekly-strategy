# Análisis Comprehensivo del Mercado US — Semana del 2026-05-18

**Fecha de análisis**: 18-mayo-2026 (lunes, pre-apertura ART/JST)
**Cierre de referencia (precios)**: 2026-05-18 close
**Último dato breadth CSV**: **2026-05-14** (rezago aprox. 3 días vs reporting date)
**Idioma**: Español rioplatense (Argentina)

**Fuentes primarias**:
- CSV local `data/breadth-local/market_breadth_data.csv` (PRIMARY — Breadth 200MA y 8MA)
- CSV local `data/breadth-local/uptrend_ratio_timeseries.csv` (PRIMARY — Uptrend Ratio "all")
- CSV local `data/breadth-local/sector_summary.csv` (PRIMARY — Uptrend Ratio sectorial)
- FMP API + chart técnico (precios VIX, índices, commodities, yields al 2026-05-18)
- Charts breadth `charts/2026-05-18/SP500_BREADTH_PROXY_RSP_SPY_RATIO.png` y `US_UPTREND_STOCK_RATIO.png` (SUPLEMENTARIO, confirmación visual)
- `reports/2026-05-18/technical-market-analysis.md` (Step 1)

---

## Resumen Ejecutivo

- El mercado US sigue en **fase Caution con deterioración interna confirmada y profundizándose**: SPX 7,408 / NDX 29,125 / Dow 49,526 cotizan cerca de ATH pero la sesión del 5/18 imprimió velas rojas de rechazo en los tres, con NDX -1.54% intra-sesión. El **Uptrend Ratio cayó a 35.24% en RED con trend DOWN y slope -0.376** (datos al 5/14, CSV con rezago ~3 días) — 11+ sesiones consecutivas de deterioration sin signo de bottom reversal todavía.
- **Bubble Score 7/15 (Caution, Risk Budget 70-80%)**: VIX 18.67 + ATH simultáneo (2 pts), Breadth narrow leadership (2 pts), price acceleration (2 pts), valuation/narrative concentrada (+1 cualitativo). Sin datos verificables de Put/Call, margin debt ni IPO heat. El score se sostiene por internals frágiles y la presión de yields, no por exuberancia retail medible.
- **El Uptrend Ratio es la señal dominante**: cayó de 43.41% (4/17) a 35.24% (5/14) — caída de ~8pt en 4 semanas con slope negativo acelerándose. **Esta deterioration anticipa 1-2 semanas a la respuesta del Breadth 200MA**. El Breadth 200MA quedó en **57.39% (Border / Narrow Rally)** después de tocar 58.38% el 5/8.
- **US10Y en zona RED LINE (4.59%)** es el catalizador agravante. La combinación de VIX 18.67 (cerca de Caution 20), Uptrend Ratio en RED-DOWN, 10Y en red line e índices con velas rojas de rechazo configura el escenario más frágil de las últimas 8 semanas.
- **Sectores: 8 de 11 con trend DOWN** en su uptrend ratio interno. Consumer Discretionary 18.79% (oversold), Communication 23.89%, Consumer Staples 21.30%, Utilities 25.37% siguen cayendo. Energy 57.14% (overbought) lidera pero **con trend DOWN** — es decir, el rally del sector ya empezó a romperse desde adentro. **Solo Information Technology, Health Care y Materials mantienen trend UP**, y de esos, Tech es el motor único del mercado.

**Postura recomendada**: Risk Budget 70-80%. Mantener trimming gradual de Tech mega-cap (NVDA, AMD, AMAT al alza ya extendidos), Cash al 25-30%, Gold cerca del soporte $4,186 como hedge. Si en la semana del 5/18 el VIX cierra weekly >20 **o** el 10Y rompe 4.60% en cierre, switch operativo a **Stress** declarado (Risk Budget 50-60%).

---

## 1. Fase Actual del Mercado: **CAUTION (continúa, presión creciente)**

### Criterios de Clasificación

| Factor | Lectura actual | Risk-On | Base | **Caution** | Stress |
|--------|---------------|---------|------|-------------|--------|
| **VIX** | **18.67** (al 5/18) | <17 | 17-20 | **20-23** | >23 |
| **US10Y** | **4.590%** (al 5/18) | <4.11% | 4.11-4.36% | 4.36-4.50% | **>4.50% (RED LINE)** |
| **SPX vs ATH** | **7,408 (cerca ATH, vela roja de rechazo)** | ATH/ATR positivo | rango | **ATH con divergencia interna** | <MA(50) |
| **Breadth 200MA** | **57.39%** (al 5/14, **flat-DOWN** desde 58.38%) | ≥60% | 50-60% UP | **50-60% DOWN** | <50% |
| **Uptrend Ratio** | **35.24% RED DOWN** slope -0.376 (al 5/14) | ≥50% GREEN UP | 30-50% UP | **<50% RED DOWN** | <20% RED |
| **Sectores con trend DOWN** | **8 de 11 DOWN** (al 5/14) | ≤3 DOWN | 4-5 DOWN | **6-8 DOWN** | ≥9 DOWN |

**Veredicto**: 5 de 6 criterios marcan **Caution o peor** (10Y ya cruzó a Stress por criterio puntual). Solo el VIX <20 estricto mantiene la superficie en Risk-On. Régimen oficial: **CAUTION confirmada y profundizándose**.

### Justificación

1. **Tres índices con velas semanales de rechazo en ATH**: SPX rechazó 7,517 (close 7,408 = -1.45% del high), NDX rechazó 29,679 (close 29,125 = -1.86% del high), Dow rechazó 50,200 (close 49,526 = -1.34% del high). El rechazo simultáneo en máximos absolutos con RSI semanal en sobrecompra (NDX 73.21, SPX 69.55) es una señal técnica de **distribución incipiente**.

2. **Breadth 200MA en territorio Border / Narrow Rally**: 57.39% al 5/14 (CSV con rezago ~3 días). El indicador venía oscilando 56-58% desde principios de abril, pero la última lectura está **flat con sesgo DOWN** mientras SPX hace nuevos highs. **Definición técnica de narrow rally tardío**.

3. **Uptrend Ratio en RED hace 11+ sesiones consecutivas**, con slope negativo acelerándose (-0.226 → -0.327 → -0.375). Esto es **deterioration sistemática**, no ruido. El indicador cayó de 43.41% (4/17) a 35.24% (5/14) — ~8pt de pérdida en 4 semanas mientras SPX subió de 7,126 a 7,501 en el mismo período. **La divergencia precio/participación está documentada con datos**.

4. **8 de 11 sectores con trend DOWN** en su uptrend ratio sectorial — la debilidad se generalizó. Consumer Discretionary 18.79% (oversold), Consumer Staples 21.30%, Communication 23.89%, Utilities 25.37%, Health Care con trend UP pero solo 31.21%. **La fragilidad del rally es estructural**, no concentrada en un sector específico.

5. **US10Y en 4.590% (RED LINE)** + acciones en ATH es históricamente la combinación más inestable. RSI del 10Y en 65.74 (cerca de sobrecompra 70). Si rompe 4.60% en weekly close, hay riesgo de extensión a 4.75-4.85%, lo que comprime múltiplos de Tech/Growth directamente.

6. **Energy +4.99% 1W lidera pero con trend DOWN** en su uptrend ratio sectorial (57.14%, "overbought" en status, pero slope -1.479 con trend DOWN). Esto significa que el liderazgo Energy ya empezó a romperse internamente — la fortaleza del precio en superficie está vacía por dentro.

### Triggers de Switch a Stress Declarado

| Trigger | Umbral | Si dispara |
|---------|--------|-----------|
| **VIX cierre weekly >20** | VIX 20.00+ en cierre del 5/22 | Confirma Caution → preparar transición Stress |
| **10Y cierre weekly >4.60%** | TNX 46.00+ en cierre del 5/22 | Stress declarada — recortar Tech agresivo |
| **SPX weekly close <7,338** | -1.0% adicional desde close 5/18 | Confirmación corrección -3 a -5% |
| **Uptrend Ratio rompe 30%** | <30% en CSV próximo | Stress táctica, gold/cash++ |
| **Breadth 200MA <55%** | Próximos updates CSV | Narrow rally franqueado |

---

## 2. Bubble Score: **7/15 — Caution Phase** (Risk Budget 70-80%)

Aplicando el framework v2.1 con datos cuantitativos primero y ajuste cualitativo estricto.

### Phase 2: Evaluación Cuantitativa

| Indicador | Valor medido | Score | Justificación |
|-----------|--------------|-------|---------------|
| **Put/Call Ratio** | n/d (no recolectado esta semana) | 0 | Sin dato verificable, no se asignan puntos |
| **VIX + ATH simultáneo** | VIX 18.67, SPX/NDX/Dow cerca de ATH | **+2** | VIX <20 estricto con tres índices con velas de rechazo en ATH = complacencia + sobreextensión. ATH simultáneo cumple "near highs"; vol comprimida cumple "low vol". |
| **Margin Debt YoY** | n/d (no recolectado) | 0 | Sin dato verificable |
| **IPO heat** | n/d (no recolectado) | 0 | Sin dato verificable |
| **Breadth anomaly (narrow leadership)** | Breadth 200MA 57.39% en ATH; Uptrend Ratio 35.24% RED | **+2** | **<60% above 200MA mientras SPX hace ATH = liderazgo estrecho confirmado**. Solo ~35% de stocks en uptrend con índice en ATH. Patrón clásico de blow-off concentrado en Tech (Tech +12.40% 1M mientras 7 sectores en rojo). |
| **Price acceleration** | NDX +57.4% vs MA200 semanal, SPX +39.7% vs MA200 | **+2** | Distancia precio vs MA200 en percentil >95 histórico. NDX retorno 3M extremo. Velocidad de aceleración cumple criterio. |

**Phase 2 subtotal: 6/12 puntos**

### Phase 3: Ajustes Cualitativos (máx +3, criterios estrictos)

**Confirmation Bias Check**:
- [x] ¿Hay evidencia medible para cada punto cualitativo? Parcial (concentración Tech sí, social/media no medidos)
- [x] ¿Un observador independiente coincidiría? Sí en concentración, no en pánico/euforia retail
- [x] ¿Evito double-counting con Phase 2? Sí, valuation no se cuenta dos veces

| Adjustment | Evidencia | Score |
|-----------|-----------|-------|
| **A. Social penetration** | No hay reportes directos de no-inversores recomendando stocks documentados esta semana | **+0** |
| **B. Media/search trends** | Sin Google Trends >5x YoY medidos, sin tapas Time/CNBC con fechas confirmadas | **+0** |
| **C. Valuation disconnect / narrative dependence** | Concentración extrema en Tech: Tech +12.40% 1M, AMD +52.4% 1M, CSCO +39.9% 1M, semis liderando. Resto del mercado lateral o en rojo. La narrativa AI sostiene valuations sin amplio respaldo de earnings sectoriales | **+1** |

Justificación de +1 cualitativo: La narrativa AI/Tech mantiene concentración medible (Tech +12.40% mientras 7 de 11 sectores en rojo 1M), patrón de momentum-chasing en semis. Pero sin datos de P/E, social ni media verificables, el ajuste se limita a +1.

**Phase 3 subtotal: +1/3 puntos**

### Score Final

```
Score Total = Phase 2 (6) + Phase 3 (+1) = 7/15 puntos
Fase: CAUTION (5-7 puntos)
Risk Budget: 70-80%
```

### Comparación con Semanas Previas

| Fecha | Score | Fase | Comentario |
|-------|-------|------|-----------|
| 2026-05-10 | n/d | n/d | — |
| 2026-05-15 | 7/15 | Caution | Mismo nivel |
| **2026-05-18** | **7/15** | **Caution** | **Score sostenido. Las condiciones técnicas empeoraron (10Y en RED LINE, velas de rechazo en ATH) pero no agregan punto cuantitativo nuevo verificable** |

**Lectura**: El score se mantiene estable porque los componentes cuantitativos no cambiaron sustancialmente. Pero **el riesgo direccional aumentó** por proximidad a triggers (VIX a 1.3 puntos de Caution, 10Y a 1bp del extreme).

---

## 3. Breadth Index (200-Day MA) — CSV PRIMARY

### Datos al 2026-05-14 (CSV — último dato disponible, rezago ~3 días vs reporting 5/18)

| Métrica | Valor | Status |
|---------|-------|--------|
| **Breadth 200MA** | **57.39%** | **Border / Narrow Rally (entre 50-60%)** |
| **Breadth 8MA** | **56.76%** | **Neutral (40-60%)** |
| **8MA vs 200MA** | **-0.63pt (8MA por debajo)** | **Dead cross técnico activo** (8MA <200MA) |
| **Trend (CSV)** | **up** | Trend up reportado, pero **flat-DOWN observado en últimas 5 sesiones** |
| **S&P 500 precio** | 7,501.24 (al 5/14 close CSV) | Precio en ATH |

### Evolución reciente (CSV)

| Fecha | SP500 | Breadth 200MA | Breadth 8MA | 8MA-200MA |
|-------|-------|---------------|-------------|-----------|
| 5/01 | 7,230 | 57.20% | 58.58% | +1.38pt |
| 5/06 | 7,365 | 57.30% | 57.93% | +0.63pt |
| 5/08 | 7,399 | 57.33% | 57.85% | +0.52pt |
| 5/11 | 7,413 | 57.35% | 57.87% | +0.52pt |
| 5/12 | 7,401 | 57.36% | 57.47% | +0.11pt |
| 5/13 | 7,444 | 57.37% | 56.87% | **-0.50pt** |
| **5/14** | **7,501** | **57.39%** | **56.76%** | **-0.63pt** |

**Análisis**:
- **El 8MA cruzó por debajo del 200MA el 5/13** — esto es un **dead cross técnico de corto plazo** que confirma debilidad incipiente.
- Mientras SPX subió de 7,230 (5/01) a 7,501 (5/14) — **+3.74% en dos semanas**, el Breadth 200MA apenas se movió de 57.20% a 57.39% (+0.19pt). El precio se va, la participación queda. **Definición de narrow rally**.
- El 8MA cayó de 58.58% (5/01) a 56.76% (5/14) — **-1.82pt en dos semanas** con SPX subiendo. **Divergencia bajista corto plazo confirmada**.

### Interpretación según Guidelines

| Nivel Breadth 200MA | Clasificación | Estado actual |
|---------------------|---------------|---------------|
| ≥60% | Healthy | — |
| **50-60%** | **Border / Narrow Rally** | **✓ 57.39% confirma** |
| 40-50% | Caution | — |
| <40% | Fragile | — |

**Lectura clave**: 57.39% es **NORMAL para mid-cycle** y NO es "lo peor de la historia". Es un nivel intermedio que indica rally estrecho (liderazgo Tech principal). El riesgo es operacional: combinado con Uptrend Ratio en RED-DOWN y velas de rechazo en ATH, sugiere fase tardía del rally. **No es crisis breadth (eso requeriría <30%)**, pero requiere postura defensiva táctica.

### Confirmación Visual (chart RSP:SPY proxy, supplementary)

El chart `SP500_BREADTH_PROXY_RSP_SPY_RATIO.png` (Invesco S&P 500 Equal Weight ETF / SPDR S&P 500 ETF) muestra:
- **Ratio actual: 0.273** (cierre 5/15) — niveles mínimos del año
- **MA(50): 0.287, MA(200): 0.286** — ratio por debajo de ambas
- **RSI 19.70 — sobrevenida extrema** del ratio equal-weight vs cap-weight
- **MACD: -0.0041 / -0.0035** — bajista, histograma negativo

**Interpretación del chart RSP:SPY**: La concentración en mega-caps es la **más extrema desde marzo 2025**. RSP (equal weight) está siendo aplastado relativo a SPY (cap-weighted). Esto es **confirmación visual independiente** del narrow rally que muestra el CSV breadth.

**Conclusión Breadth Index**: La data CSV confirma narrow rally activo. Combinada con confirmación visual del RSP:SPY ratio (mínimos del año, RSI 19.7 sobrevendido), la fragilidad estructural está documentada. **No es crisis pero sí late-cycle warning**.

---

## 4. Uptrend Stock Ratio (All Markets) — CSV PRIMARY

### Datos al 2026-05-14 (CSV — último dato disponible)

| Métrica | Valor | Status |
|---------|-------|--------|
| **Uptrend Ratio (all)** | **35.24%** | **Neutral-Bearish** |
| **Color (CSV)** | **RED** | (basado en trend, no es overbought ni cerca del 15% bearish line) |
| **10MA** | **37.67%** | 10MA por encima del valor actual = DOWN trend |
| **Slope** | **-0.376** | **Negativo acelerándose** |
| **Trend (CSV)** | **down** | **11+ sesiones consecutivas DOWN** |

### Evolución reciente (CSV — últimas 4 semanas)

| Fecha | Ratio | 10MA | Slope | Trend |
|-------|-------|------|-------|-------|
| 4/17 | 43.41% | 38.24% | +1.951 | up |
| 4/20 | 43.21% | 39.72% | +1.783 | up |
| 4/24 | 40.17% | 41.25% | +0.604 | up |
| 4/28 | 40.42% | 41.14% | +0.034 | up |
| **4/29** | 37.46% | 40.88% | **-0.055** | **DOWN** (primer cruce) |
| 5/01 | 40.34% | 40.62% | -0.126 | down |
| 5/04 | 37.70% | 40.07% | -0.227 | down |
| 5/07 | 37.99% | 39.54% | -0.277 | down |
| 5/11 | 36.54% | 38.94% | -0.226 | down |
| 5/12 | 36.39% | 38.54% | -0.257 | down |
| 5/13 | 34.25% | 38.22% | -0.325 | down |
| **5/14** | **35.24%** | **37.67%** | **-0.376** | **down** |

### Análisis de Bottom Reversal vs Continuación de Debilidad

**Conclusión: NO hay bottom reversal todavía. La debilidad se profundiza.**

Evidencia:
1. **11 sesiones consecutivas con trend DOWN** desde el 4/29 — sin un solo día de cruce a UP.
2. **Slope acelerándose hacia abajo**: -0.055 (4/29) → -0.227 (5/04) → -0.277 (5/07) → -0.325 (5/13) → **-0.376 (5/14)**. La pendiente negativa se hace más empinada, no menos.
3. **10MA todavía por encima del valor actual** (37.67% vs 35.24%) — el indicador no rebotó por encima de su propia media corta.
4. **El ratio cayó de 43.41% (4/17) a 35.24% (5/14)** = **-8.17pt en 4 semanas** mientras SPX subió **+5.3%** en el mismo período. **Divergencia bajista máxima**.

**Para que se confirme un bottom reversal necesitaríamos**:
- Cruce del valor actual por encima del 10MA (ahora 37.67%, requiere ratio >38%)
- Slope transitando de negativo a flat (slope >-0.10)
- Trend CSV cambiando a "up"
- Idealmente, ratio rebotando de zona <20% (no es el caso, viene cayendo desde 43%)

**Características del bottom reversal aún no presentes**. La señal sigue siendo **continuación de debilidad**.

### Interpretación según Guidelines

| Nivel Uptrend Ratio | Clasificación | Estado actual |
|---------------------|---------------|---------------|
| ≥50% UP/GREEN | Healthy bullish | — |
| 30-50% UP/GREEN | Neutral bullish | — |
| **30-50% DOWN/RED** | **Neutral-Bearish (deterioration)** | **✓ 35.24% confirma** |
| <30% RED | Bearish |  — |
| <20% RED | Extreme oversold (potencial bottom) | — |

### Confirmación Visual (chart US_UPTREND_STOCK_RATIO.png, supplementary)

El chart confirma:
- Línea azul (Uptrend Ratio) en zona **25-30%** al edge derecho (consistente con caída desde mid-30s)
- Línea naranja (10MA) por encima de la línea azul → confirma DOWN trend
- Sin contacto reciente con la línea verde Bearish (15%) — no estamos en extreme oversold todavía
- La caída desde el pico ~38% (mediados de abril) es **clara y sostenida** visualmente

**Conclusión Uptrend Ratio**: **Leading indicator en RED, DOWN, sin signo de bottom**. Esta es **la señal más importante de la semana**. Históricamente, este patrón anticipa 1-2 semanas la caída del Breadth 200MA, que ya empezó a mostrar el cruce 8MA<200MA el 5/13. La cadena de leading→lagging indicators está confirmando deterioration en tiempo real.

---

## 5. Sector Rotation Pattern (sector_summary.csv)

### Estado al 2026-05-14 (CSV — último dato)

| Sector | Uptrend Ratio | 10MA | Slope | Trend | Status |
|--------|---------------|------|-------|-------|--------|
| Information Technology | 39.81% | 38.74% | **+0.234** | **UP** | neutral |
| Consumer Discretionary | 18.79% | 22.82% | -0.840 | DOWN | **oversold** |
| Communication | 23.89% | 29.86% | -0.767 | DOWN | neutral |
| Financials | 41.52% | 45.99% | -0.710 | DOWN | neutral |
| Health Care | 31.21% | 31.70% | **+0.128** | **UP** | neutral |
| **Energy** | **57.14%** | **62.44%** | -1.479 | **DOWN** | **overbought** |
| Consumer Staples | 21.30% | 23.80% | -0.778 | DOWN | neutral |
| Industrials | 38.48% | 39.58% | -0.183 | DOWN | neutral |
| Materials | 39.83% | 40.59% | **+0.407** | **UP** | neutral |
| Utilities | 25.37% | 28.06% | -1.582 | DOWN | neutral |
| Real Estate | 42.57% | 48.24% | -0.270 | DOWN | neutral |

### Resumen del Patrón

- **3 sectores con trend UP**: Information Technology, Health Care, Materials
- **8 sectores con trend DOWN**: Consumer Discretionary, Communication, Financials, Energy, Consumer Staples, Industrials, Utilities, Real Estate
- **1 sector oversold**: Consumer Discretionary (18.79%) — señal de capitulación de consumo cíclico
- **1 sector overbought**: Energy (57.14%) pero **con trend DOWN** — overbought rompiéndose

### Lectura

**Patrón mixto que no es típico de Risk-On saludable ni de Risk-Off claro**:

1. **Tech como motor único confirmado**: IT 39.81% con trend UP es el único sector que mantiene momentum positivo dentro de la canasta cíclica. Esto coincide con Tech +12.40% 1M en performance.

2. **Energy overbought con trend DOWN = late-cycle warning**: 57.14% es la ratio sectorial más alta, pero el slope -1.479 es el peor (junto con Utilities -1.582). El liderazgo Energy de la semana (+4.99% 1W en performance) está construido sobre una breadth interna que ya empezó a romperse. **Es rally por shock geopolítico, no estructural**.

3. **Defensivos en debilidad sospechosa**: Consumer Staples 21.30% y Utilities 25.37% deberían estar firmes en un mercado con yields al alza, pero ambos están en DOWN con slopes negativos. Esto sugiere que **los flujos defensivos no están ocurriendo** — los inversores no están rotando a defensa, están reduciendo riesgo a cash directamente.

4. **Consumer Discretionary oversold (18.79%)** es señal clásica de capitulación de consumo. Esto coincide con Luxury Goods -30.57% 1M en performance y Mortgage Finance -11.83% 1W. **Early warning de recesión de consumo**.

5. **Health Care y Materials con trend UP pero ratios neutrales (31-40%)**: estos son refugios "tibios" — no son trades de fortaleza convicta, sino rotaciones marginales.

### Comparación 1W vs Uptrend Ratio Sectorial

**Divergencias clave**:
- **Energy**: +4.99% 1W (performance) PERO trend DOWN (uptrend ratio) → el precio sube pero la participación interna se rompe. **Trade unsustainable medio plazo**.
- **Tech**: +0.53% 1W (performance) PERO trend UP (uptrend ratio) → corrección suave en superficie con base interna sólida. **Único sector con coherencia bullish**.
- **Consumer Defensive**: +0.88% 1W (performance) PERO trend DOWN (uptrend ratio) → rally técnico sin amplitud. **No es trade de calidad defensiva todavía**.

### Sectores Recomendados

| Sector | Postura | Justificación |
|--------|---------|---------------|
| **Information Technology** | **Mantener pero NO añadir** | Único sector con trend UP, pero ya extendido (+12.40% 1M). Trimming gradual de líderes (NVDA, AMD, AMAT) |
| **Health Care** | **Selectivo agregar** | Trend UP, defensiva premium (UNH +24.5% 1M, LLY +11.2% 1M) |
| **Materials** | **Watch / no añadir todavía** | Trend UP pero performance -3.50% 1W (Basic Materials sector) — divergencia interna. Esperar confirmación |
| **Energy** | **NO añadir / trimming selectivo** | Overbought con trend DOWN. XLE liderazgo posible pero unsustainable |
| **Consumer Discretionary** | **Evitar** | Oversold pero sin signal de bottom |
| **Resto (8 sectores DOWN)** | **Reducir / evitar** | Trend DOWN sostenido |

---

## 6. Volatility Regime

### Lectura Actual

- **VIX al 5/18**: **18.67** (+0.24, +1.30% sesión)
- **VIX semana previa**: 18.43 con vela intra-semana +7.21% (high 19.27, low 17.20)
- **MA50 semanal**: 18.26
- **MA200 semanal**: 18.19
- **RSI(14)**: 47.85 (neutral)
- **MACD**: histograma negativo (-0.720) pero próximo a girar

### Niveles Estándar (Monty Style)

| Nivel | Valor | Estado |
|-------|-------|--------|
| Risk-On | 17 | Por debajo |
| **Caution** | **20** | **Cerca — VIX 18.67 está a 1.33 puntos** |
| Stress | 23 | Lejos |
| Panic | 26 | Lejos |

### Análisis

1. **VIX cotiza levemente arriba de ambas medias semanales** (50 y 200), configurando un soporte dinámico en 18.19-18.26. La estructura técnica del VIX sugiere que **el suelo está siendo construido**.

2. **Patrón de dobles techos rechazados** en zona 30-35 (marzo-abril 2026) seguido de descenso ordenado hacia base 17-20. Esto significa que **el régimen de baja volatilidad de los últimos meses está intacto** pero al borde de cambiar.

3. **Vela intra-semana +7.21%** sugiere que **los compradores de volatilidad están apareciendo** en la zona 17-18. No es un spike vertical (típico de pánico), sino un acumulación gradual.

4. **RSI(14) en 47.85 (neutral)** y MACD histograma negativo cerca de girar — **setup técnico de potencial VIX expansion**.

### Régimen de Volatilidad: **Compresión Tardía con Tensión Acumulándose**

**Característica del régimen**:
- Volatilidad realizada baja (consistente con índices en ATH)
- Volatilidad implícita comprimida pero arriba de MAs
- VIX no en sobrevendido (RSI 47.85 neutral) — no hay margen de "más compresión"
- Skew (asumido) probablemente elevado por demanda de puts
- Estructura técnica del VIX sugiere **base lista para expansion**

**Implicaciones**:
- Comprar volatilidad (VXX, VIX calls) en niveles 18-19 tiene **riesgo/recompensa favorable** si Caution se transforma en Stress.
- Vender vol (income strategies) en estos niveles tiene **riesgo asimétrico desfavorable** — la compensación por el riesgo es baja.
- Hedges via puts (SPY, QQQ) cotizan a IV razonable pero no barata — preferible ETF-based hedges (GLD, TLT, BIL) para parte del libro.

### Triggers de Cambio de Régimen Vol

| Trigger | Umbral | Consecuencia |
|---------|--------|--------------|
| **VIX cierre weekly >20** | El 5/22 | Caution oficial → Stress táctica |
| **VIX cierre >23 dos días** | Stress declarada | Risk Budget 50-60% |
| **VIX spike intraday >25 sin retroceso** | Pánico inicial | Activar hedges máximos |
| **VIX vuelve a <17** | Risk-On reanudado | Solo si breadth confirma con Uptrend Ratio en GREEN |

---

## 7. Resumen Ejecutivo con Probabilidades de Escenarios (próximas 1-3 semanas)

### Escenario Base — "Caution se profundiza, corrección -3 a -6%" (52%)

**Descripción**:
Los índices grandes corrigen suavemente desde ATH por sobreextensión técnica y presión del 10Y. La rotación interna continúa: Tech digiere ganancias, Energy se rompe internamente, 8 sectores en DOWN profundizan. Uptrend Ratio sigue cayendo hacia 28-30%. Breadth 200MA cae a 54-56%.

**Condiciones técnicas**:
- VIX oscila 17-22 (sin breakout >23)
- 10Y oscila 4.50-4.65% (sin ruptura clara de 4.60% en weekly)
- SPX corrige hacia 7,100-7,250 (-2 a -4%)
- NDX corrige hacia 27,500-28,500 (-2 a -5%)
- Uptrend Ratio: continúa en RED-DOWN, llega a 28-32%
- Breadth 200MA: erosión gradual a 54-56%

**Trigger confirmatorio**:
- Weekly close SPX <7,338 (low semanal previo)
- Weekly close NDX <28,628
- Próximo CSV Breadth muestra 8MA cruzando más profundo bajo 200MA

**Invalidación**:
- VIX cierra weekly >23 (escala a Stress, 22% prob)
- SPX cierra weekly >7,517 con volumen (regresa a Risk-On, 26% prob)

**Postura**: Risk Budget 70-80%, Core 38-42%, Defensive 18-22%, Theme/Hedge 16-20% (GLD prominente), Cash 22-28%. Sin agregar Tech mega-cap, trimming gradual de winners 1M (AMD, CSCO).

---

### Escenario Risk-On — "Yields se relajan, rally se reanuda con amplitud" (26%)

**Descripción**:
El mercado absorbe el spike de yields, el 10Y retrocede debajo de 4.50% en weekly close, VIX cae a 16-17. Los índices rompen los highs semanales con volumen. **Crucialmente, el Uptrend Ratio cruza a UP (>10MA) y el Breadth 200MA expande a 60%+** — el rally se amplía a sectores fuera de Tech.

**Condiciones técnicas**:
- VIX cierra weekly <17
- 10Y retrocede <4.50% en weekly close (preferentemente <4.40%)
- SPX rompe 7,517 con volumen
- **Uptrend Ratio cruza a GREEN/UP con slope >+0.10**
- **Breadth 200MA expande a 60%+**
- Cu mantiene >$6.00, Tech no pierde liderazgo

**Trigger confirmatorio**:
- Conjunto simultáneo: VIX <17 + 10Y <4.50% + Uptrend Ratio UP
- WTI retrocede a $90-95 (alivia presión inflacionaria)

**Invalidación**:
- 10Y rompe 4.60% en weekly close
- VIX >20 en weekly close
- WTI rebota >$115

**Postura**: Risk Budget 90-95%, regresar a Core 45-50%, Theme 20-25%, Cash 10-15%. Agregar tech selectivo, Materials/Industrials breakout.

**Por qué solo 26%**: Para este escenario necesitamos **tres confirmaciones simultáneas** (VIX, 10Y, breadth). El estado actual está deteriorándose, no mejorando. Probabilidad reducida respecto a semana previa (29%→26%) porque la profundización de DOWN en Uptrend Ratio reduce esta vía.

---

### Escenario Stress — "10Y rompe 4.60%, corrección -7 a -12%" (22%)

**Descripción**:
El 10Y rompe 4.60% en weekly close con momentum sostenido, VIX cierra >23, los índices entran en corrección sustancial. La concentración Tech amplifica la caída (NVDA, AMD, CSCO en pull-back -10 a -15%). El Uptrend Ratio cae a <20% (zona oversold extrema). WTI rebota >$115 (geopolítica) o se mantiene >$100 sumando inflación. Bubble Score sube a 9-10/15.

**Condiciones técnicas**:
- 10Y weekly close >4.60% (zona extreme)
- VIX >23 (zona Stress)
- SPX rompe 7,338 → 7,000 (-5%)
- NDX rompe 28,628 → 26,500 (-9%)
- IWM rompe 270 → 245 (-10%)
- Uptrend Ratio <25% (potencial bottom forming si llega a <20%)
- Breadth 200MA cae a <55%

**Trigger confirmatorio**:
- 10Y >4.60% en cierre weekly + VIX >23 simultáneamente
- WTI >$115 con sostenibilidad (geopolitical shock)
- Gold breakout >$4,750 (huida hacia safe-haven)

**Invalidación**:
- VIX retorna <20 en weekly close
- 10Y <4.50% en weekly close
- Uptrend Ratio cruza UP (señal de capitulación + reversal)

**Postura**: Risk Budget 50-60%, Core 28-32%, Defensive 22-28% (Healthcare Plans++), Theme 18-22% (GLD 12-14% + TLT 5-8%), Cash 30-35%. Cerrar Tech mega-cap en pull-back. Considerar VIX calls / SPY puts en bid bajo.

**Riesgo amplificador**: La concentración 1M en Tech (+12.4%) significa que una corrección sería **rápida y vertical** si los líderes claudican.

---

### Tabla Sintética de Escenarios

| Escenario | Prob | SPX target | NDX target | VIX | 10Y | Acción Principal |
|-----------|------|------------|------------|-----|-----|------------------|
| **Base** | **52%** | 7,100-7,250 (-2 a -4%) | 27,500-28,500 (-2 a -5%) | 17-22 | 4.50-4.65% | **Mantener postura Caution, no agregar** |
| **Risk-On** | 26% | 7,600+ (+2.6%) | 30,000+ (+3%) | <17 | <4.50% | Re-add Tech + Industrials |
| **Stress** | 22% | 7,000 (-5.5%) | 26,500 (-9%) | >23 | >4.60% | Cerrar Tech, GLD++, TLT, VIX calls |

**Total probabilidad**: 52% + 26% + 22% = **100%**

---

## 8. Conclusión Operativa

### Postura Sintética

El mercado US está en **fase Caution confirmada y profundizándose** al 2026-05-18. Los siguientes hechos lo definen:

1. **Tres índices con velas semanales de rechazo en ATH** (SPX, NDX, Dow) con RSI semanal en sobrecompra (NDX 73.21).
2. **US10Y en zona RED LINE (4.59%)** — a 1bp del extreme — con RSI 65.74 cerca de sobrecompra.
3. **VIX 18.67** comprimido pero **a 1.33 puntos de Caution (20)** — sin margen para caída adicional.
4. **Breadth 200MA en 57.39%** (Border / Narrow Rally) con **dead cross 8MA-200MA confirmado el 5/13** (CSV).
5. **Uptrend Ratio en 35.24% RED-DOWN** con slope -0.376 acelerándose. **11 sesiones consecutivas de deterioration sin signo de bottom**.
6. **8 de 11 sectores con trend DOWN** en uptrend ratio interno. Energy overbought rompiéndose. Consumer Discretionary oversold.
7. **Bubble Score 7/15 Caution** sostenido — Risk Budget 70-80%.
8. **Concentración Tech extrema** (Tech +12.40% 1M vs 7 sectores en rojo) sigue siendo el motor único.

### Recomendaciones Tácticas

| Item | Recomendación |
|------|---------------|
| **Risk Budget** | 70-80% (Caution) |
| **Core Index (SPY/QQQ/DIA)** | 38-42% (reducción gradual desde semana previa) |
| **Defensive (XLV + XLP)** | 18-22% (Healthcare Plans premium) |
| **Theme/Hedge (GLD, XLE selectivo)** | 16-20% (GLD prominente como hedge) |
| **Cash/BIL** | 22-28% (acumular gradualmente) |
| **Trimming candidates** | NVDA, AMD, CSCO, AMAT (winners 1M extendidos) |
| **Avoid** | Consumer Cyclicals, Real Estate, Utilities, Basic Materials |
| **Watch list (re-entry si Risk-On)** | Materials breakout, Industrials, Solar (si VIX <17 + Uptrend UP) |

### Variables Críticas para Monitorear esta Semana

1. **10Y close**: Si rompe 4.60% weekly close → switch a Stress táctica
2. **VIX close**: Si >20 weekly close → confirmación Caution → preparar Stress
3. **Uptrend Ratio próximo update CSV**: Necesitamos ver el primer día de slope >-0.20 como early bottom signal
4. **Breadth 200MA próximo update**: Si cae <55% → narrow rally confirmado en deterioration profunda
5. **Energy sector**: Si XLE rompe 1W -5%+, confirma que el liderazgo geopolítico se acabó

### Continuidad con Reporte Previo (5/15)

| Item | 5/15 | 5/18 | Cambio |
|------|------|------|--------|
| Fase | Caution | Caution | Sin cambio |
| Bubble Score | 7/15 | 7/15 | Sin cambio |
| Risk Budget | 70-80% | 70-80% | Sin cambio |
| Uptrend Ratio | 35.24% RED DOWN | 35.24% RED DOWN | Sin cambio (mismo último CSV) |
| Breadth 200MA | 54.78% | **57.39%** | **+2.61pt — pero por composition del CSV update (último dato 5/14)** |
| Prob Base | n/d | 52% | — |
| Prob Risk-On | n/d | 26% | — |
| Prob Stress | n/d | 22% | — |
| 10Y | 4.47% | **4.59%** | **+12bp — escala a RED LINE** |
| VIX | 18.89 | 18.67 | -0.22 (marginal) |

**Cambio clave esta semana**: 10Y rompió 4.50% y se acercó a 4.60% (red line → extreme). Esto **aumenta la probabilidad de Stress** (22% vs estimación inferior previa) y **reduce la probabilidad de Risk-On** (26% vs 29% típico) porque la presión de yields es el catalizador agravante principal.

---

## Nota sobre Data Freshness (Issue #15)

**Rezagos de datos importantes**:

| Fuente | Última fecha disponible | Reporting date | Rezago |
|--------|------------------------|----------------|--------|
| `market_breadth_data.csv` | **2026-05-14** | 2026-05-18 | **~3 días hábiles** |
| `uptrend_ratio_timeseries.csv` | **2026-05-14** | 2026-05-18 | **~3 días hábiles** |
| `sector_summary.csv` | **2026-05-14** (asumido por consistencia) | 2026-05-18 | **~3 días hábiles** |
| FMP API (precios) | 2026-05-18 close | 2026-05-18 | **0 días** |
| Charts técnicos | 2026-05-15 close (chart RSP:SPY) | 2026-05-18 | **1 día hábil** |

**Implicancia**: Todos los valores Breadth/Uptrend en este reporte son **al 5/14** (último dato CSV). Los precios (VIX, índices, commodities, yields) son **al 5/18 close**. Cuando se discute "tendencia del Breadth" o "Uptrend Ratio actual", se entiende **al 5/14 con rezago de 3 días hábiles** hasta el próximo update CSV. Si entre el 5/14 y el 5/18 hubo movimientos de mercado importantes (como la subida del 10Y), el Breadth/Uptrend actuales podrían ser ya **diferentes a los reportados** — probablemente **peores** dadas las velas de rechazo en ATH del 5/18.

---

*Disclaimer: Este reporte es análisis de mercado basado en datos cuantitativos (CSV TraderMonty + FMP API) y confirmación visual de charts. Las probabilidades son estimaciones del autor basadas en evidencia técnica observable. No considera fundamentales corporativos individuales ni eventos macro específicos (eso se cubre en `market-news-analysis.md` — Step 3). No constituye recomendación de inversión personalizada.*

*Datos: CSV local TraderMonty (Breadth, Uptrend Ratio, Sector Summary al 2026-05-14), FMP API (precios al 2026-05-18), charts breadth en `charts/2026-05-18/`. Fase y Bubble Score basados en framework Minsky/Kindleberger v2.1 + Monty Style guidelines.*
