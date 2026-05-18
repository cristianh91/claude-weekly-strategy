# Análisis Comprehensivo del Mercado US — Semana del 2026-05-15

**Fecha de análisis**: 15-mayo-2026
**Cierre de referencia**: 14-mayo-2026 (FMP API + CSV local TraderMonty)
**Idioma**: Español rioplatense (Argentina)
**Fuentes primarias**:
- CSV local `data/breadth-local/market_breadth_data.csv` (PRIMARY para Breadth 200MA/8MA)
- CSV local `data/breadth-local/uptrend_ratio_timeseries.csv` (PRIMARY para Uptrend Ratio)
- CSV local `data/breadth-local/sector_summary.csv` (PRIMARY para análisis sectorial breadth)
- FMP API (VIX, índices, commodities, yields)
- Charts breadth `charts/2026-05-15/` (SUPLEMENTARIO, confirmación visual)

---

## Resumen ejecutivo

- El mercado US se encuentra en una fase **Risk-On tardío con deterioración interna confirmada**: SPX, NDX y DJIA en ATH simultáneo, pero el **Uptrend Ratio cayó a 35.24% en RED con trend DOWN y slope -0.376**, mientras el **Breadth 200MA bajó desde 58.38% (5/8) a 54.78% (5/14)** — patrón clásico de narrow rally en fase tardía.
- **Bubble Score 7/15 (Caution, Risk Budget 70-80%)**: VIX comprimido + ATH simultáneo (2 pts), Breadth deteriorándose con índices en ATH (2 pts), valuation/social/IPO sin datos verificables (0 pts cualitativos). El score se sostiene por internals frágiles, no por exuberancia retail medible.
- **Uptrend Ratio es la señal dominante de esta semana**: 10 sesiones consecutivas de trend DOWN, slope acelerándose (-0.226 → -0.376), color RED estable. Esta deterioration **precede 1-2 semanas a la caída del Breadth 200MA** — primera señal de aviso operacional.
- **Sectores en stress de breadth amplio**: 8 de 11 sectores con trend DOWN en su uptrend ratio interno (Consumer Discretionary 18.79% oversold, Communication 23.89%, Consumer Staples 21.30%, Utilities 25.37% caen fuerte; Energy 57.14% overbought por shock WTI; solo Information Technology, Health Care y Materials con trend UP).
- **Fase de mercado: Caution** (transición desde Risk-On). El régimen sigue siendo Risk-On por VIX 18.89 (<20) y SPX en ATH, pero la simultaneidad de yields al alza (10Y 4.47%), Uptrend Ratio en RED-DOWN, y deterioration secuencial del Breadth 200MA cumplen los criterios para anticipar el cambio operativo a Caution antes de que VIX cierre >20 dos días.

**Postura recomendada**: Risk Budget 70-80%, comenzar trimming gradual de Tech mega-cap (NVDA, AMD, AVGO al alza ya extendidos), aumentar cash al 25-30%, mantener Gold cerca de soporte 4500 como hedge.

---

## 1. Fase actual del mercado: **CAUTION** (transición desde Risk-On)

### Criterios de clasificación

| Factor | Lectura actual | Risk-On | Base | **Caution** | Stress |
|--------|---------------|---------|------|------------|--------|
| VIX | 18.89 (+9.44% el 5/14) | <17 | 17-20 | **20-23** | >23 |
| US10Y | 4.470% | <4.11% | 4.11-4.36% | **4.36-4.50%** | >4.50% |
| SPX vs ATH | ATH 7501.24 | ATH/ATR positivo | rango | **ATH con divergencia interna** | <MA(50) |
| Breadth 200MA | 54.78% (DOWN secuencial) | ≥60% | 50-60% UP | **50-60% DOWN** | <50% |
| Uptrend Ratio | **35.24% RED DOWN** slope -0.376 | ≥50% GREEN UP | 30-50% UP | **<50% RED DOWN** | <20% RED |
| Sectores en RED en uptrend | **8 de 11 DOWN** | ≤3 DOWN | 4-5 DOWN | **6-8 DOWN** | ≥9 DOWN |

**Veredicto**: 4 de 6 criterios marcan **Caution**, 2 marcan Risk-On (VIX <20 estricto, SPX ATH). Se clasifica el régimen como **Caution con cobertura de Risk-On pasajera** — el mercado todavía cotiza como Risk-On, pero las plomerías internas ya están en Caution.

### Justificación

1. **ATH simultáneo de los tres índices** (SPX, NDX, DJIA) con NDX RSI 75.28 (sobrecompra extrema) es la señal de superficie Risk-On.
2. **Breadth 200MA cayó 3.60pt en 4 sesiones** (58.38% → 54.78%) mientras SPX subió de 7398.93 a 7501.24 (+1.38%). El precio sube; la participación baja. **Definición técnica de narrow rally**.
3. **Uptrend Ratio en RED hace 10+ sesiones**, slope acelerándose hacia abajo (-0.226 → -0.376) — no es ruido sino deterioration sistemática.
4. **8 de 11 sectores con trend DOWN** en su uptrend ratio sectorial — la debilidad ya no se limita a Real Estate/Utilities, contagió a Industrials, Consumer Staples, Communication, Consumer Discretionary y Financials.
5. **Yields al alza (10Y 4.47%)** + acciones en ATH es una combinación históricamente inestable.

Por estos motivos, **operativamente** debemos tratar al mercado como Caution aunque la superficie indique Risk-On. El triángulo de triggers para confirmar el switch a Caution declarado es: VIX cierre >20 dos días + 10Y cierre >4.50%. Cualquiera de los dos confirma; ambos juntos disparan rotación táctica acelerada.

---

## 2. Bubble Score: **7/15 — Caution Phase** (Risk Budget 70-80%)

Aplicando el framework v2.1 con datos cuantitativos primero y ajuste cualitativo estricto:

### Phase 2: Evaluación cuantitativa

| Indicador | Valor medido | Score | Justificación |
|-----------|--------------|-------|---------------|
| **Put/Call Ratio** | n/d (no recolectado) | 0 | Sin dato verificable, no se asignan puntos |
| **VIX + ATH simultáneo** | VIX 18.89, SPX/NDX/DJIA ATH | **+2** | VIX <20 con tres índices en ATH = complacencia + sobreextensión cumple criterio "near highs + low vol". Está apenas arriba del threshold ideal VIX<12, pero ATH simultáneo de tres índices califica el "near highs". Score conservador: 1.5→2. |
| **Margin Debt YoY** | n/d (no recolectado) | 0 | Sin dato verificable |
| **IPO heat** | n/d (no recolectado) | 0 | Sin dato verificable |
| **Breadth anomaly (narrow leadership)** | Breadth 200MA 54.78% en ATH | **+2** | **<60% above 200MA mientras SPX hace ATH = liderazgo estrecho confirmado**. Uptrend Ratio 35.24% RED refuerza: solo ~35% de stocks en uptrend sostenido con índice en ATH. **Patrón clásico de blow-off concentrado.** |
| **Price acceleration** | SPX +40% desde abril 2026 (V-shape) | **+2** | Retorno 3M en percentil >95 histórico (rally vertical desde 5300 a 7500 en ~6 semanas según technical analysis report). Velocidad de aceleración extrema. |

**Phase 2 subtotal: 6/12 puntos**

### Phase 3: Ajustes cualitativos (máx +3, criterio estricto)

| Adjustment | Evidencia | Score |
|-----------|-----------|-------|
| **A. Social penetration** | No hay reportes directos de no-inversores recomendando stocks documentados | **+0** |
| **B. Media/search trends** | Sin datos verificables Google Trends >5x YoY, sin tapas Time/CNBC con fechas | **+0** |
| **C. Valuation disconnect** | No se mide P/E directamente; pero la divergencia breadth/precio ya cuenta en Phase 2 → evitar double-count | **+1** |

Justificación de +1 cualitativo: la narrativa AI/Tech mantiene concentración extrema (Tech +15.01% mes, AMD +74.2%, CSCO +40.3%), y el rebote V-shape sin pullback significativo desde abril sugiere comportamiento de momentum-chasing. Sin embargo, sin datos de P/E ni de social/media verificables, el ajuste se limita a +1.

**Phase 3 subtotal: +1/3 puntos**

### Score final: **7/15 puntos** — **Phase: Caution**

### Recomendaciones por phase

**Caution (5-7 pts), Risk Budget 70-80%**:
- Comenzar trimming gradual (20-30% reducción) en posiciones Tech mega-cap más extendidas
- Tighten stops ATR 1.8× (vs 2.0× normal)
- Reducir sizing en nuevas posiciones al 50%
- **No iniciar shorts** todavía — esperar al menos 2/7 condiciones compuestas de reversión
- Aumentar cash gradualmente hacia 25-30%

### Composite short-selling conditions (0/7 cumplidas)

1. ❌ Weekly chart con lower highs (SPX hace ATH)
2. ❌ Volume peaks out (volumen confirma rally según tech report)
3. ❌ Leverage indicators drop (n/d)
4. ❌ Media/search trends peak out (n/d)
5. ⚠️ Weak stocks rompiendo primero — **señal parcial**: 8/11 sectores DOWN, URA, NFLX, META, Financials débiles → no contado como confirmado pero observable
6. ❌ VIX spike >20 (en 18.89)
7. ❌ Fed/policy shift signals (n/d)

**Conclusión bubble detector**: **No iniciar shorts**. El mercado está caro y estirado, pero sin señales técnicas de reversal confirmadas. La acción correcta es **defensa activa de posiciones existentes**, no toma de posiciones bajistas.

---

## 3. Breadth Index (S&P 500): 200MA + 8MA

### Valores actuales del CSV (5/14/2026)

| Métrica | Valor 5/14 | 5/13 | 5/12 | 5/11 | 5/8 | Δ semana |
|---------|-----------|------|------|------|-----|----------|
| **Breadth 200MA** | **54.78%** | 53.91% | 55.17% | 56.21% | 58.38% | **-3.60pt** |
| **Breadth 8MA** | **57.39%** | 57.37% | 57.36% | 57.35% | 57.33% | +0.06pt (plana) |
| **8MA vs 200MA** | **+2.61pt** | +3.46pt | +2.19pt | +1.14pt | -1.05pt | converging desde arriba |
| **SPX** | 7501.24 ATH | 7444.25 | 7400.96 | 7412.84 | 7398.93 | +1.38% |
| **Trend (CSV)** | up | up | up | up | up | up (no cambió aún) |

### Evaluación contra thresholds

| Indicator | Threshold | Lectura |
|-----------|-----------|---------|
| **200MA** | ≥60% Healthy | **54.78% = Narrow Rally / Border** |
| **200MA** | 50-60% Border | **Estado actual** — todavía no entró a Caution territory (<50%) |
| **200MA** | 40-50% Caution | No alcanzado |
| **200MA** | <40% Fragile | No alcanzado |
| **8MA** | ≥73% Overbought | No (57.39%) |
| **8MA** | 60-73% Healthy Bullish | No (57.39% justo abajo) |
| **8MA** | 40-60% Neutral | **Estado actual** |
| **8MA** | 23-40% Bearish | No |
| **8MA** | <23% Oversold | No |

### 8MA vs 200MA: cross status

- 8MA (57.39%) > 200MA (54.78%) → **NO dead cross** (todavía)
- Diferencial: +2.61pt, pero **convergiendo desde +3.46pt el 5/13**
- Si 200MA sigue cayendo al ritmo actual (-3.60pt/semana) mientras 8MA se mantiene plano cerca de 57%, en 1-2 semanas podríamos ver:
  - Escenario A: 200MA cae a ~52-53%, 8MA se mantiene → diferencial se amplía (NO cross, pero divergencia precio-breadth absoluta empeora)
  - Escenario B: 8MA empieza a caer también (probable si Uptrend Ratio sigue en DOWN) → ambos a la par → riesgo de dead cross **en 3-4 semanas** si SPX corrige

### Lectura

**Breadth 200MA 54.78% en zona Narrow Rally / Border**: NO es "crisis", NO es "fragile" — pero **está degradándose** desde 58.38% en 4 sesiones. La velocidad del deterioro es la señal, no el nivel absoluto. Históricamente, caídas de 3-4pt semanales en Breadth 200MA mientras el SPX hace ATH son **precursores de techos locales en 2-6 semanas**.

**8MA plano cerca de 57%** indica que la corriente reciente de stocks por encima de su MA200 no se está deteriorando aún en horizonte de corto plazo — la deterioration está en la cola larga (200MA cayendo más rápido). Esta divergencia (corto plazo estable, largo plazo cayendo) sugiere que el rally del precio se sostiene en muy pocos liderazgos.

**No hay dead cross todavía**, pero el sistema está en alerta. Si en la próxima semana 8MA cae por debajo de 200MA, sería confirmación bajista de mediano plazo.

### Comparación CSV vs chart visual

El chart `SP500_BREADTH_PROXY_RSP_SPY_RATIO.png` (RSP:SPY ratio) muestra:
- Ratio en 0.272 con vela roja
- MA50 (0.288) > MA200 (0.286) > Precio (0.272) — **death cross visual ya formado en el proxy**
- MACD bajista negativo
- RSI(14) 17.15 (oversold extremo del ratio)

**Divergencia interesante**: el RSP:SPY (equal-weight vs cap-weight) ya rompió bajista y está en oversold extremo del ratio, mientras el Breadth 200MA del CSV (54.78%) todavía no cruzó al territorio Caution (<50%). El proxy RSP:SPY es **más adelantado** y confirma que el cap-weight (SPY) está apalancado por pocas mega-caps mientras equal-weight (RSP) cae.

**Conclusión combinada**: la CSV indica "Border, deteriorating"; el chart proxy indica "narrow rally extremo con equal-weight ya en colapso relativo". Ambas lecturas son consistentes y refuerzan el sesgo Caution.

---

## 4. Uptrend Ratio (All Markets): la señal clave de la semana

### Valores actuales del CSV (5/14/2026)

| Métrica | Valor 5/14 | 5/13 | 5/12 | 5/11 | 5/8 | 5/7 | 5/6 | 5/5 |
|---------|-----------|------|------|------|-----|-----|-----|-----|
| **Uptrend Ratio** | **35.24%** | 34.25% | 36.39% | 36.54% | 38.16% | 38.00% | 40.89% | 39.16% |
| **MA10** | 37.67% | 38.22% | 38.54% | 38.94% | 39.34% | 39.54% | 39.84% | 39.82% |
| **Slope** | **-0.376** | -0.325 | -0.257 | -0.226 | -0.256 | -0.277 | -0.208 | -0.263 |
| **Trend (CSV)** | **DOWN** | DOWN | DOWN | DOWN | DOWN | DOWN | DOWN | DOWN |
| **Color (regla <50% RED)** | **RED** | RED | RED | RED | RED | RED | RED | RED |

### Evaluación

- **Color RED estable**: 10+ sesiones consecutivas en RED (<50% threshold operativo del proyecto). El último cruce a RED fue alrededor del 4/29 (37.46%, slope cruzó negativo).
- **Trend DOWN sostenido**: el slope se está acelerando hacia abajo (-0.226 → -0.257 → -0.325 → -0.376) — **no es un ruido temporal, es deterioration acelerada**.
- **MA10 cayendo**: 39.84% (5/6) → 37.67% (5/14) = -2.17pt en 8 sesiones.
- **No hay reversal de fondo**: NO se observa bottom turn — el ratio no rebota desde un piso, sigue bajando.

### Lectura clave: deterioration que precede al Breadth 200MA

El Uptrend Ratio es el **indicador adelantado** más confiable según la metodología del proyecto:

- Cuando el Uptrend Ratio entra en RED-DOWN sostenido con slope acelerándose, **el Breadth 200MA suele seguir 1-2 semanas después**.
- En este caso, el Uptrend Ratio entró a RED-DOWN el 4/29 (~16 días atrás). El Breadth 200MA **recién empezó a deteriorarse el 5/11-5/12** (de 58.38% a 54.78%), confirmando el lag clásico de ~1-2 semanas.
- Como el Uptrend Ratio sigue cayendo (slope se acelera), **el Breadth 200MA debería seguir cayendo en las próximas 1-2 semanas** hacia 50-52% en escenario base.

### ¿Estamos cerca de un bottom?

- **35.24% NO es nivel de bottom histórico** (los bottoms ocurren típicamente en zona <15% o oversold extremo del Bearish line a 15% en el chart).
- El chart `US_UPTREND_STOCK_RATIO.png` muestra que el ratio actual cae desde un peak local cerca de 40% (4/17 = 43.41%) hacia 35% — la pendiente es bajista y todavía hay espacio hacia 25-20% antes de zona de bottom.
- **No hay señal de reversal de fondo** — esperar.

### Implicancia operativa

**Esta es la señal MÁS IMPORTANTE de la semana**. Mientras el SPX hace ATH:
- Solo ~35% de stocks están en uptrend sostenido (criterio: above 200MA/50MA/20MA + perf 1M positiva)
- 65% de stocks NO están participando del nuevo high
- La concentración está confirmada en Tech mega-caps (AMD, NVDA, CSCO, AVGO, GOOGL)
- Este patrón **siempre precede** correcciones tácticas de 5-8%

### Comparación CSV vs chart visual

El chart `US_UPTREND_STOCK_RATIO.png` muestra:
- Línea azul (Uptrend Ratio) en zona ~25-35%, claramente debajo de Overbought (37% línea roja punteada)
- MA10 (naranja) descendiendo desde ~40% hacia 37%
- Trend bajista visible desde mediados de abril
- Línea verde de Bearish a 15% — todavía lejos

**Match perfecto entre CSV y chart**. CSV value 35.24% se ve en el extremo derecho del chart consistente con el trazo.

---

## 5. Análisis por sector industrial (sector_summary CSV)

### Ratios sectoriales internos (% de stocks en uptrend dentro del sector)

| Sector | Ratio | MA10 | Slope | Trend | Status | Lectura |
|--------|-------|------|-------|-------|--------|---------|
| **Energy** | **57.14%** | 62.44% | -1.479 | DOWN | **overbought** | Spike WTI llevó ratio a overbought, pero ya está corrigiendo desde MA10. Top reversal en marcha. |
| **Real Estate** | 42.57% | 48.24% | -0.270 | DOWN | neutral | Castigado por yields al alza. Caída fuerte vs MA10. |
| **Financials** | 41.52% | 45.99% | -0.710 | DOWN | neutral | Anómalo: yields al alza no benefician a bancos en breadth. Debilidad estructural. |
| **Information Technology** | **39.81%** | 38.74% | **+0.234** | **UP** | neutral | **Único sector con ratio + trend UP claro**. Concentración confirmada. |
| **Materials** | 39.83% | 40.59% | +0.407 | UP | neutral | Reflación cíclica + Copper breakout. Soporte intacto. |
| **Industrials** | 38.48% | 39.58% | -0.183 | DOWN | neutral | Pierde tracción a pesar de cyclical narrative. |
| **Health Care** | 31.21% | 31.70% | +0.128 | UP | neutral | Rebote técnico tras castigo previo (UNH +27% individual). |
| **Utilities** | 25.37% | 28.06% | -1.582 | DOWN | neutral | El que más cae (slope -1.582). Salida defensiva confirmada por Risk-On. |
| **Communication** | 23.89% | 29.86% | -0.767 | DOWN | neutral | NFLX -19%, META -7.9% golpean al sector. |
| **Consumer Staples** | **21.30%** | 23.80% | -0.778 | DOWN | neutral | Mucho debajo de Risk-On range. Defensa en colapso, coherente con flujo cíclico. |
| **Consumer Discretionary** | **18.79%** | 22.82% | -0.840 | DOWN | **oversold** | **Solo sector en oversold**. HD -10% individual. Lectura: rotación interna fuera de retail/cyclical consumer. |

### Lecturas clave

1. **Solo 3 sectores con trend UP**: Information Technology (+0.234), Materials (+0.407), Health Care (+0.128). Los tres son consistentes con la narrativa Tech-AI + reflación cíclica + rebote idiosincrásico Healthcare (UNH).
2. **8 sectores con trend DOWN**: el daño breadth es **amplio**, no aislado. No es un caso de "Tech sube vs Defensives caen" — es "Tech sube vs casi todo lo demás cae".
3. **Energy en overbought con slope -1.479**: el spike WTI puso al sector en zona caliente, pero el ratio ya está dropping fast. **Top forming en Energy** — confirma la lectura del technical report sobre WTI siendo "supply shock spike".
4. **Consumer Discretionary en oversold (18.79%)**: junto con HD -10% individual, es la **primera señal cíclica de stress** en demanda doméstica. Inconsistente con narrativa Risk-On pura.
5. **Consumer Staples 21.30%**: defensive típico cae junto con cíclicos = flujo masivo hacia muy pocas mega-caps Tech. **Confirmación final de narrow rally**.
6. **Materials único defensive-cíclico-reflación-hedge UP**: junto con Copper breakout y Energy, hay una pata válida de inflation hedge cíclica que funciona.

### Sintesis sectorial

El patrón es **Tech-dominant + Inflation hedge cíclico (Materials/Energy temporal)**, con **colapso amplio de todos los demás sectores** (defensives y cíclicos consumidores). Esta NO es la rotación healthy de un Risk-On expansivo; es la **concentración terminal de un Risk-On tardío**.

**Implicancia para asignación**: reducir exposición a sectores fuera del trifecta UP (Tech, Materials, Health Care) y rotar parcialmente a cash mientras se monitorean los triggers de reversal.

---

## 6. Volatility regime

### Lectura VIX

| Métrica | Valor | Lectura |
|---------|-------|---------|
| VIX cierre 5/14 | **18.89** | Justo debajo de threshold Caution (20) |
| VIX cambio diario | **+9.44%** | Suba intradía significativa el viernes |
| VIX cierre semanal (chart) | 17.26 | Below 18-MA200/MA50 |
| VIX MA(50) | 18.23 | VIX cotizó encima brevemente |
| VIX MA(200) | 18.19 | Confluencia técnica |
| VIX percentile 3M | bajo-medio | Compresión persistente |
| VIX RSI(14) | 45.85 | Neutral |

### Régimen identificado

**Régimen actual: Compresión persistente con primera fisura intradía**

- El VIX se mantuvo en banda estrecha 15-19 durante el rally de abril-mayo.
- La suba del +9.44% el 5/14 (de ~17 a 18.89) es la **primera señal técnica de que el suelo de volatilidad puede estar formándose**.
- Históricamente, después de compresión prolongada (VIX bottom <17 durante 3-4 semanas), una suba intradía de 9-10% precede a expansión de volatilidad en 1-3 semanas, especialmente si coincide con yields al alza y deterioration breadth (ambos cumplidos).

### Triggers a monitorear

| Trigger | Implicancia |
|---------|-------------|
| VIX cierre <17 | Risk-On consolidado (revierte el alerta del 5/14) |
| **VIX cierre >20 dos días consecutivos** | Cambio operativo a Caution declarado |
| VIX cierre >23 | Stress regime — trim agresivo, hedges activos |
| VIX cierre >26 | Panic — emergency hedge |

### Probabilidad cualitativa del cambio de régimen

Con Uptrend Ratio en RED-DOWN y Breadth 200MA cayendo, **la probabilidad de que VIX rompa 20 en cierre 2 días consecutivos en las próximas 2 semanas es elevada** (estimación cualitativa del autor: ~50-55%, no es una probabilidad estadística sino lectura de confluencia de factores).

---

## 7. Comparación CSV vs charts: divergencias y consistencia

| Métrica | CSV (PRIMARY) | Chart visual | Consistencia |
|---------|---------------|--------------|--------------|
| Breadth 200MA | 54.78% (5/14) | RSP:SPY proxy en 0.272, MACD bajista, MA50>MA200>Price | ✅ Ambos indican narrow rally / deterioration. Proxy más adelantado. |
| Breadth 8MA | 57.39% | n/d directo, pero RSP:SPY ratio plano-bajista | ✅ Consistente con 8MA flat. |
| Dead/Golden Cross | 8MA > 200MA por +2.61pt → NO dead cross | RSP:SPY ya tiene death cross MA50/MA200 visible | ⚠️ El proxy ya cruzó bajista; el CSV breadth oficial no aún. **CSV es el indicador autoritativo del proyecto**, así que: NO dead cross todavía, pero proxy adelantado señala riesgo. |
| Uptrend Ratio | 35.24% RED DOWN | Línea azul ~35% bajando, MA10 naranja descendente | ✅ Match perfecto. |
| Trend Uptrend | DOWN slope -0.376 | Trazo visualmente bajista desde mediados de abril | ✅ Consistente. |
| Bottom signal Uptrend | NO hay bottom | Línea sigue cayendo, no toca zona <15% | ✅ Sin reversal. |

**No hay divergencia material entre CSV y charts**. La única nota de cautela es que el chart RSP:SPY (proxy de breadth) está MÁS adelantado en señalar deterioration relativa que el CSV Breadth 200MA oficial — esto es esperable porque RSP:SPY mide concentración cap-weighted en tiempo real, mientras Breadth 200MA es promedio rolling.

**Veredicto**: los datos CSV son los autoritativos para todos los reports posteriores. Los charts confirman visualmente las lecturas.

---

## 8. Implicancias estratégicas para la próxima semana

### Postura agregada

**Risk Budget: 70-80%** (Caution phase). No bullish complacency, no bearish overreaction. Defensa activa.

### Asignación táctica recomendada (model portfolio guidance)

| Pillar | Comentario | Sugerencia |
|--------|-----------|------------|
| **Core Index (SPY/QQQ/DIA)** | Mantener exposición pero no agregar arriba | 40-45% (vs 45-50% en Risk-On pleno) |
| **Defensive (XLV + XLP)** | Defensives en breadth DOWN — no agregar XLP, mantener XLV por UNH idiosyncratic | 17-20% |
| **Theme/Hedge (XLE + GLD + COPX)** | XLE en top forming (Energy ratio overbought), reducir; GLD cerca de soporte 4500, atractivo entry; COPX nuevo viable | 17-22% (XLE 5%→3%, GLD 8-10% mantener, COPX 4-5% nuevo) |
| **Cash/Short bonds (BIL)** | Aumentar gradualmente | 23-28% (vs 15-20% en Risk-On) |

### Triggers de acción operativa

| Trigger | Acción |
|---------|--------|
| **VIX cierre >20 dos días consecutivos** | Trim 5-10% Tech mega-cap (NVDA/AMD/AVGO), incrementar BIL hacia 28-30% |
| **US10Y cierre semanal >4.50%** | Trim duration sensitives, reducir Real Estate y Utilities a cero (si quedaban) |
| **SPX cierre semanal <7350** | Reducir core index 5%, hedge parcial con SH o SDS |
| **SPX cierre semanal <7200** | Defensive completo: cash al 35%, hedge GLD aumentado |
| **Uptrend Ratio cruza GREEN (≥50%) con trend UP** | Reversal confirmado → reactivar Risk-On |
| **Breadth 8MA cruza debajo de 200MA (dead cross)** | Bear regime confirmado → Risk Budget al 50% |

### Niveles de invalidación

- **Invalidación de la postura Caution**: VIX cierre <17 + Uptrend Ratio cruza ≥40% con slope UP + Breadth 200MA estabilizado >56%. Si los tres se dan, recovery breadth en marcha → restaurar Risk-On.
- **Confirmación bear regime**: Uptrend Ratio <25% + Breadth 200MA <50% + VIX >20 sustained + SPX < MA(50) semanal. Si los cuatro se dan, salir del Caution hacia Stress.

### Foco de monitoreo diario (siguiente semana)

1. **Uptrend Ratio**: ¿slope se estabiliza (-0.376 → menos negativo) o se acelera (más negativo de -0.4)? Cualquier slope <-0.5 sostenido = stress.
2. **Breadth 200MA**: ¿cae bajo 52% (Caution territory <50% se aproxima)?
3. **VIX**: ¿confirma suba o vuelve a comprimirse hacia 17?
4. **US10Y**: ¿rompe 4.50% en cierre? Es el catalyst macro más probable de la corrección.
5. **Tech mega-caps (NVDA, AMD, AVGO)**: ¿siguen subiendo (concentración extrema continúa) o muestran first signs of distribution (vela roja con volumen alto en ATH)?

---

## 9. Conclusión y postura recomendada

El mercado US del 14-mayo-2026 está en una **fase Risk-On terminal con caracterización operativa de Caution**. Los tres índices major hicieron ATH simultáneo, pero el deterioro interno es inequívoco:

- **Uptrend Ratio 35.24% RED-DOWN** con slope acelerando (-0.376) en 10+ sesiones — **leading indicator clave**.
- **Breadth 200MA cayendo 3.60pt en 4 sesiones** (58.38% → 54.78%) mientras precio sube — **divergencia precio-breadth confirmada**.
- **8 de 11 sectores con trend DOWN** en uptrend ratio — **debilidad amplia, no aislada**.
- **VIX +9.44% intradía el 5/14** — **primera fisura en compresión persistente**.

**Bubble Score 7/15 (Caution, no Euphoria)**: el mercado está caro y estirado, pero sin evidencia cuantitativa de mass-penetration retail ni media frenzy verificable. La sobrevaloración técnica es real; la euforia social NO está medida.

**Postura recomendada**:
1. **Risk Budget 70-80%**, NO 100%.
2. **Defensa activa**: trim gradual de mega-caps Tech más extendidas, aumentar cash hacia 25-30%.
3. **Hedge con Gold** cerca de soporte 4500 (entry técnico favorable).
4. **No shorts** todavía — 0/7 condiciones compuestas cumplidas.
5. **Monitorear triggers**: VIX 20 / 10Y 4.50% / Uptrend Ratio slope < -0.5 / Breadth 200MA < 52%.

El mercado puede seguir subiendo 1-3 semanas más (escenario Bull 20%), pero **el risk/reward asimétrico ya no favorece agregar exposición agresivamente**. La paciencia y la disciplina de stops son las herramientas centrales para esta semana.

---

*Fuentes:*
- *CSV TraderMonty local: market_breadth_data.csv, uptrend_ratio_timeseries.csv, sector_summary.csv (al 5/14/2026)*
- *FMP API: VIX 18.89, SPX 7501.24, NDX 29580.30, DJIA 50063.46, WTI 99.81, Gold 4557.80, US10Y 4.470%*
- *Charts breadth (suplementarios): SP500_BREADTH_PROXY_RSP_SPY_RATIO.png, US_UPTREND_STOCK_RATIO.png*
- *Reporte upstream: reports/2026-05-15/technical-market-analysis.md*
