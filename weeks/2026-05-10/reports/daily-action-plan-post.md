# Daily Action Plan — Post-Market (cierre 5/8 simulado)

**Fecha**: domingo 10/05/2026
**Timing**: Post-market
**Fase actual**: Risk-On de superficie / Caution de amplitud
**Estado del mercado**: 🔴 Cerrado (domingo) — **SIMULACIÓN forzada**: usamos el cierre real del **viernes 8/5** como si fuera el cierre del día. Acciones para el lunes 11/5 pre-market.

> **⚠️ Nota de re-baseline (10/05/2026 16:30 ART)**: este DAP fue actualizado tras detectar que el blog 5/10 anterior estaba mal anclado. La nueva versión del blog usa **5/4 publicado (28/19/17/36)** como anchor real, dando allocation **27/21/17/35** (Risk Budget 65%). **Datos breadth ahora del universo Russell 3000 (~2557 nombres)**, no S&P 500.

---

## Cierre del día (datos reales 5/8 vía FMP + Yahoo Finance fallback)

| Indicador | Cierre | Cambio | %Chg | Lectura |
|---|---|---|---|---|
| **VIX** | 17,19 | +0,11 | +0,64% | **Risk-On** apenas pisado bajo el umbral 17 |
| **S&P 500** | 7.398,93 | +61,82 | +0,84% | **ATH** semanal |
| **Nasdaq 100** | 29.234,99 | +1.524,63 | +5,50% | **ATH** parabólico, RSI semanal 74 (sobrecompra clara) |
| **Dow Jones** | 49.609,16 | +12,18 | +0,02% | lateral, narrow rally evidente |
| **US10Y** | 4,380% | — | — | **Warning** (sobre línea de alerta 4,36%) |
| **Gold (GC)** | $4.730,70 | +19,80 | +0,42% | sobre soporte $4.415, hedge intacto |
| **WTI (CL)** | $94,72 | -6,85 | -6,70% sem | corrección post pico Hormuz |
| **Cobre (HG)** | $6,30 | +0,35 | +5,96% sem | breakout cíclico (no en nuestra asignación) |
| **GLD ETF** | $433,77 | +10,59 | +2,50% sem | hedge institucional activo |
| **SPY** | $737,62 | +6,04 | +0,83% | sigue al SPX |
| **QQQ** | $711,23 | +37,08 | +5,50% sem | sobreextendido vs MA20 sem |
| **URA** | $55,18 | -0,66 | -1,18% | zona dip-buy $50-52 si retrocede |
| **XLE** | $55,70 | -3,15 | -5,35% sem | corte por WTI -7% |
| **XLP** | $84,18 | +0,01 | +0,01% | ancla defensiva, slope interno DOWN -0,33 |
| **XLV** | $143,49 | -1,67 | -1,15% sem | oversold, mean-reversion |
| **TLT** | $86,08 | +0,47 | +0,55% | bonos rebotando suave |
| **BIL** | $91,46 | +0,06 | +0,07% | cash equivalent |
| **DIA** | $496,13 | +1,11 | +0,22% | balance ancla |

*Fuente per-quote*: VIX/SPX/Dow/Gold/Treasury vía **FMP API** (5 símbolos); NDX/futures CL,HG,NG/todos los ETFs vía **Yahoo Finance v8 fallback** (13 símbolos). 18/18 cobertura sin necesidad de plan FMP paid.

---

## Breadth (CSV LOCAL `data/breadth-local/`, **universo Russell 3000 ~2557 nombres**)

| Indicador | Valor | Umbral | Lectura |
|---|---|---|---|
| **200-day MA** | **57,33%** | ≥60 healthy / 50 / 40 | **Narrow Rally** (debajo del 60% healthy en -2,67pt) |
| **8-day MA** | **57,85%** | 73 / 60 / 40 / 23 | Neutral |
| **8MA vs 200MA** | **+0,52pt (NO dead cross)** | — | 8MA marginalmente sobre 200MA — diferencia clave vs S&P 500 (donde sí dead cross) |
| **Uptrend Ratio Russell 3000** | **38,16% RED** | ≥40 strong / 25-40 neutral / 15-25 weak | **Neutral-bullish boundary**, slope -0,2562/día = **trend DOWN** |
| **10MA Uptrend** | 39,34% | — | bajando, slope negativo sostenido |
| **Sectores en uptrend interno** | 6/11 | — | Energy 51,3% / Real Estate 50,7% / Financials 49,2% / Industrials 41,1% / Materials 39,8% / IT 39,6% |
| **Sectores oversold trend DOWN** | Cons. Disc. 25,6% / Cons. Staples 23,1% / Utilities 20,9% | — | mean-reversion potencial XLP (en nuestra cartera) |

> **Caveat universo**: Russell 3000 NO matchea TraderMonty exacto (TM ~25% Uptrend vs local 38%, +13pt diff). TM probablemente usa un screener custom con filtros de liquidez. **Direccionalmente coinciden** (todos DOWN, todos RED) — usar la **dirección y slope**, no el nivel absoluto, para decisiones.

---

## Trigger evaluation (vs blog [2026-05-10](../../blogs/2026-05-10-weekly-strategy.md) re-baseline)

| Trigger | Criterio | Cierre 5/8 | Distancia | Status |
|---|---|---|---|---|
| **Risk-On VIX <16,00** | cierre semanal | 17,19 | +1,19 sobre umbral | **NO activo** |
| **Risk-On SPX >7.500** | cierre semanal | 7.398,93 | -101 | **NO activo** (a 1,4% del breakout) |
| **Risk-On Uptrend GREEN** | reversa a >40 con slope UP | 38,16 RED slope -0,26 | falta slope UP | **NO activo** |
| **Caution VIX >20** | cierre 2 días consecutivos | 17,19 | -2,81 bajo umbral | NO activo |
| **Caution US10Y >4,50%** | cierre semanal | 4,38% | -0,12pt | NO activo (a 12bp del red line) |
| **Caution Breadth 200MA <50%** | CSV semanal | 57,33% | -7,33pt | NO activo |
| **Caution AMAT miss + guide flat** | jueves 5/14 AMC | pendiente | — | evento próximo |
| **Stress VIX >23 cierre 2 días** | — | 17,19 | -5,81 | NO activo |
| **Stress US10Y >4,60%** | cierre semanal | 4,38% | -0,22pt | NO activo |

**Veredicto del día**: ningún trigger duro activado. Indicadores internos (Uptrend RED slope DOWN, US10Y borderline 4,38% sobre alerta 4,36%, narrow_rally Breadth) marcan **zona de pre-Caution silencioso pero no Caution operativa**. El precio dice Risk-On, la amplitud dice ojo.

---

## Lectura de escenarios (probabilidades blog re-baseline)

| Escenario | Prob. blog | Lectura post-cierre 5/8 |
|---|---|---|
| **Risk-On** "extensión goldilocks CPI" | **27%** | sin invalidar pero **sin avance** — VIX +1,19 sobre umbral 16, SPX a 1,4% del breakout 7.500 |
| **Base** "consolidación digestiva narrow" | **45%** | **escenario más probable hoy** — SPX 7.272-7.500 lateral es el rango Base |
| **Caution** "pullback técnico + yield/CPI shock" | **23%** | embedded — Uptrend deteriorando confirma sesgo Caution sin gatillo duro |
| **Stress** "reversa abrupta correction" | **5%** | sin señal |

**¿Dónde estamos?**: posicionados en **Base con sesgo Caution embedded**. Allocation 27/21/17/35 (Risk Budget 65%) refleja postura defensiva-balanceada apropiada al régimen narrow_rally + dead cross marginal + Uptrend RED-DOWN. Si el lunes abre con AMD/NVDA mostrando reversión técnica clara o US10Y rompe 4,42% intraday, las probabilidades migran +5pt a Caution antes del CPI martes.

---

## Acciones concretas para el lunes 11/05 (pre-market)

### Niveles a vigilar (gap pre-market 22:30 JST domingo / 10:30 ART lunes)

- **SPX futures**: defensa **7.380-7.400**; ruptura **7.450** al alza = extensión Risk-On parcial; ruptura **7.300** = pre-Caution material
- **NDX/QQQ**: QQQ defensa **$700-705** (NDX 28.800-29.100); ruptura **$715** = melt-up; ruptura **$695** (NDX 28.000) = top probable Tech
- **VIX premarket**: **<17,5 ok**; **>18,5** primera campanada
- **US10Y intraday**: **<4,40% ok**; **>4,45%** segunda campanada (red line 4,50%)
- **GLD**: defensa **$430**; ruptura **$440** al alza = breakout hedge institucional → reforzar
- **WTI**: defensa **$94**; ruptura **$90** = sobreextiende corrección (-7% adicional)
- **XLP**: defensa **$83,80**; tenencia clave para el shift defensivo del lunes

### Posiciones a ajustar (lunes apertura, modelo 27/21/17/35)

**Si gap apertura tranquilo + datos macro alineados** (escenario Base):
- Ejecutar el shift modesto del blog vs anchor 5/4: **Core 28%→27%** (-1pt: cortar QQQ -2pt, +1pt SPY); **Defensivo 19%→21%** (+2pt: XLP +2pt); **Tema 17%→17%** (0pt neto: GLD +1pt, XLE -1pt); **Cash 36%→35%** (-1pt re-deploy a XLP)
- Trigger: lunes apertura, primer hora si SPX ±0,5% del cierre y VIX <18

**Si gap up NDX >+1,5% sin breadth confirm**:
- **NO sumar QQQ**. Esperar pullback.
- Mantener cash 35%; CPI martes es binario.

**Si gap down NDX -2% o VIX >19 premarket**:
- Pivotar a tabla **Caution** del blog: Core 23%, Defensivo 23%, Tema 18% (GLD +2pt → 14%), Cash 36% (+1pt)
- Cortar 1/3 de QQQ inmediatamente
- Comprar VIX call $20 strike (5/30 expiry) si IV<25%

### Watchlist específica (pre-market 5/11)

| Ticker | Vigilar | Trigger acción |
|---|---|---|
| **AMD** | reversa con sombra superior larga (post +92% 1M) | -8% intraday → cortar parcial; nuevo high → mantener pero NO agregar |
| **NVDA** | comportamiento single-name | ruptura cierre 2 días bajo MA20 sem = top probable |
| **AMAT** | pre-pricing pre-earnings jueves AMC | gap pre-mercado lunes ±5% = sentimiento semis IA |
| **GLD** | hedge activo, dip-buy en $430-432 | dip a $430 = comprar para llegar a 12% target |
| **XLP** | defensivo objetivo +2pt | dip a $83-84 = comprar para llegar a 11% target |
| **XLE** | corrección WTI -7%, recortar -1pt | rebote a $58 sin WTI > $100 = vender 20% del XLE remanente |
| **URA** | dip a zona $50-52 = compra clara (fuera modelo principal) | dip a $50 con MAs alineadas = oportunidad táctica |

---

## Riesgos próximas 24-48h

1. **CPI martes 5/12 21:30 ART** — el evento binario. Plan A/B/C arriba según print
   - **Headline ≥3,5% o core ≥3,3%** → activa Caution table del blog inmediatamente
   - **Headline ≤3,0% y core ≤3,1%** → Risk-On expansión (poco probable)
   - **In-line 3,1-3,3%** → Base se mantiene, sin movida fuerte

2. **Iran/Hormuz ceasefire frágil** — incidente con tankers o nueva escalada militar
   - Cualquier titular = WTI spike +10-15% en horas
   - GLD ganador asimétrico (en nuestra cartera +1pt → 12%)

3. **AMAT jueves AMC** — laggard semis, miss = NDX -3-5%

4. **Powell→Warsh transición** — viernes 5/15 mandato Chair expira, Senate confirmation pendiente

5. **NDX RSI 74 reversion risk** — sobrecompra extrema; con dead cross marginal en S&P 500 (no en Russell 3000), preceden correcciones del 5-8% en 2-6 semanas

---

## Chequeo nocturno (lunes 11/5 / madrugada martes JST)

| Hora JST | Hora ART | Hora ET | Evento | Decisión |
|---|---|---|---|---|
| Lun 22:30 JST | Lun 10:30 ART | Lun 09:30 ET | **Apertura US** | Confirmar gap, ejecutar shift allocation si apertura tranquila |
| Mar 21:30 JST | Mar 09:30 ART | Mar 08:30 ET | **CPI abril** | binario: hot ≥3,5% → Caution / cool ≤3,0% → Risk-On / in-line → mantener |
| Mar 23:00 JST | Mar 11:00 ART | Mar 10:00 ET | resaca CPI + apertura US | confirmar dirección post-CPI; gap >±1% en SPY/QQQ define el día |

---

## Disclaimer

Este reporte presenta un **modelo de cartera y análisis** con fines educativos e informativos; **NO constituye asesoramiento financiero individual**. Las menciones a "ejecutar al lunes apertura", "vigilar tal nivel", "comprar a tal nivel" o cualquier indicación de timing/ejecución describen **ejecuciones hipotéticas dentro de un modelo de portafolio ilustrativo** y no son recomendaciones personales de operación. Cada lector debe considerar su **tolerancia al riesgo, horizonte temporal, situación fiscal y composición patrimonial** antes de operar; cuando corresponda, consultá con un **asesor financiero matriculado** habilitado en tu jurisdicción. Las **probabilidades de escenarios (27/45/23/5) son estimaciones personales del autor** (筆者推定 / author estimate), no consensos verificables de mercado. Los rendimientos pasados no garantizan resultados futuros. Operar con apalancamiento, derivados u opciones implica riesgo de pérdida total o superior al capital inicial.

---

*Reporte regenerado: 2026-05-10 16:35 ART (post re-baseline). Fuentes: **FMP API + Yahoo Finance v8 fallback** (`scripts/fetch_market_close.py`, 5 FMP + 13 Yahoo); **CSVs locales Russell 3000** Breadth/Uptrend (`data/breadth-local/`, ~2557 nombres); blog vigente [`blogs/2026-05-10-weekly-strategy.md`](../../blogs/2026-05-10-weekly-strategy.md) (anchor 5/4 publicado).*
