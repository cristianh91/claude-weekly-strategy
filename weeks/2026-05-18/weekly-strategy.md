# [Acciones US] Semana del 18 de mayo de 2026 — Estrategia semanal

**Fecha de publicación**: 18 de mayo de 2026
**Cierre de referencia**: 18 de mayo de 2026 (FMP API)
**Idioma**: español rioplatense (Argentina)

> **Nota de continuidad**: aplica la regla **±10-15pt gradual** desde el anchor publicado **5/15 (Core 24% / Defensivo 23% / Tema 16% / Cash 37%)**. Cambio absoluto total esta semana: **4pt**.

---

## Resumen 3 líneas

1. **Entorno (cierre 5/18)**: SPX **7408,50 (-1,24%)** / NDX **29125,20 (-1,54%)** / DJIA **49526,17 (-1,07%)** — primera corrección material desde el ATH **7501,24 del 5/14**, las tres con velas rojas de rechazo. **VIX 18,67** (Risk-On nominal, al borde Caution 20). **US10Y 4,590%** — rompió 4,50% al alza y está a **1bp del extreme 4,60%** (+12bp en 3 sesiones). Internals: **Breadth 200MA 57,39% (Border / Narrow Rally)** con **dead cross 8MA-200MA confirmado 5/13** (8MA 56,76 < 200MA 57,39); **Uptrend Ratio 35,24% RED-DOWN slope -0,376**, 11 sesiones DOWN consecutivas. **Datos breadth/uptrend al 5/14 (CSV TraderMonty con rezago 2 días hábiles vs precios 5/18); precios FMP cierre 5/18**. **Bubble Score 7/15 (Caution sostenido)**. Régimen: **Caution confirmada y profundizándose**.

2. **Foco**: el evento dominante sigue siendo **NVDA Q1 FY27 AMC mié 5/20 16:20 ET** (**5:20 JST jueves 5/21 / 17:20 ART miércoles 5/20**), acompañado **FOMC Minutes 14:00 ET** (**3:00 JST jueves 5/21 / 15:00 ART**) + cluster retail/defensivo (HD mar BMO, MDT/ADI/TGT/LOW mié BMO, INTU mié AMC, TJX mié BMO, **WMT jue BMO**, WDAY jue AMC) y discurso **Waller en Frankfurt vie 4:00 ET / 17:00 JST**. Sin FOMC Blackout esta semana (próximo 6/6-6/18 ET). Triángulo de riesgo: **US10Y cierre >4,60% / VIX cierre >20 dos días / NVDA gap -8% post-earnings**.

3. **Estrategia**: **micro-ajuste defensivo adicional** desde el anchor 5/15 (24/23/16/37) hacia **23/24/15/38** — el 10Y en red line + dead cross 8MA-200MA + Uptrend Ratio sin signo de bottom **(11 sesiones DOWN)** justifican apenas otro paso defensivo. Core -1pt (SPY 14→13, DIA 10 mantener, QQQ 0), Defensivo +1pt (XLV 11→12, XLP 12 mantener), Tema -1pt (XLE 3→2, GLD 13 mantener), Cash +1pt (37→38). **Activos de riesgo 62% / cash 38%**. Postura: hedges activos, **stops ATR 1,2× semana NVDA**, no agregar Tech, GLD intacto.

---

## Acción de la semana

### Lot management (modelo de cartera)

> **Nota**: lo que sigue es un **modelo de cartera ilustrativo**. La ejecución real (lotes, timing, instrumentos) depende de tu tolerancia al riesgo, situación fiscal y composición patrimonial. Revisar el disclaimer al final.
>
> **Freshness**: Breadth 200MA / 8MA y Uptrend Ratio son **CSV TraderMonty al 5/14/2026 con rezago 2 días hábiles vs precios FMP 5/18** (vie 5/15 + lun 5/18). El rezago importa: entre 5/14 y 5/18 hubo subida de +12bp en el 10Y y velas de rechazo en ATH — el Uptrend Ratio real al 5/18 probablemente sea **peor** que el 35,24% reportado.
>
> **Transparencia (corrección vs blog 5/15)**: el blog del 5/15 reportó "Breadth 200MA 54,78%" — eso era en realidad el `Breadth_Index_Raw` (valor diario crudo) del CSV, no la columna `Breadth_Index_200MA`. El valor correcto al 5/14 es **57,39%** (esta semana). El "+2,61pt aparente" es una **corrección de lectura del CSV**, no movimiento real de mercado. El Breadth raw siguió cayendo (54,78% → 53,91% promedio últimas sesiones); el 200MA por construcción se mueve lento.

**Fase actual**: **Caution confirmada y profundizándose**. Bubble Score 7/15 sostenido (Risk Budget 70-80%). **5 de 6 criterios marcan Caution o peor**: VIX 18,67 (a 1,33 puntos de Caution 20), US10Y 4,590% en RED LINE (cruzó al Stress puntual), Breadth 200MA 57,39% **Border con dead cross 8MA<200MA confirmado el 5/13** (CSV), Uptrend Ratio **35,24% RED-DOWN slope -0,376** (11 sesiones DOWN), 8 de 11 sectores con uptrend interno DOWN. Solo el VIX <20 estricto mantiene la superficie en Risk-On nominal. **El switch operativo a Stress declarado se gatilla con**: VIX cierre semanal >20 **o** US10Y cierre semanal >4,60%.

| Categoría | Anchor 5/15 (publicado) | Esta semana 5/18 | Cambio | Implementación | Razonamiento |
|---|---|---|---|---|---|
| **① Core Index** (SPY/QQQ/DIA) | 24% (SPY 14 + DIA 10 + QQQ 0) | **23%** (SPY 13 + DIA 10 + QQQ 0) | **-1pt** | **Lunes 5/18 cierre / martes 5/19 apertura** (defensa pre-NVDA) | SPX rechazó el ATH 7517 con vela roja -1,24% el 5/18 + NDX RSI 73,21 sobrecompra + dead cross 8MA<200MA. Cortar SPY 14→13 (-1pt). DIA se mantiene (Dow es el índice más sano técnicamente: RSI 59,25 neutral, menos extendido vs MA200). QQQ ya estaba en 0 desde 5/15 — confirmar |
| **② Defensivo** (XLV/XLP) | 23% (XLV 11 + XLP 12) | **24%** (XLV 12 + XLP 12) | **+1pt** | **Lunes 5/18 cierre / martes 5/19 apertura** | XLV +1pt a 12 (Health Care sector con uptrend trend UP slope +0,128 — único defensivo en UP; UNH +24,5% mensual confirma rebote; MDT reporta mié BMO con setup constructivo en healthcare premium). XLP 12 se mantiene (Consumer Staples interno 21,30% RED-DOWN — ancla defensiva sin agregar) |
| **③ Tema/Hedge** (GLD/XLE) | 16% (GLD 13 + XLE 3) | **15%** (GLD 13 + XLE 2) | **-1pt** | **Lunes 5/18 cierre / martes 5/19 apertura** | GLD 13 mantener (hedge primer ciclo Warsh + Tail Risk Hormuz; close $4559 estable, soporte MA50 GC $4186). XLE -1pt a 2% (sector Energy interno 57,14% **overbought con slope -1,479 DOWN** — top forming; **WTI -4,48% el 5/18 a $100,70** confirma top de rally explosivo desde $60 → $115) |
| **④ Cash/BIL** | 37% | **38%** | **+1pt** | **Lunes 5/18 cierre / martes 5/19 apertura** | Buffer adicional pre-NVDA + FOMC Minutes mié + 10Y en RED LINE. Absorbe -1pt Core y -1pt Tema vs +1pt Defensivo = neto +1pt Cash. Risk Budget 62% bajo el cap superior del rango Caution (70-80%) — postura defensiva consciente |

**Total** ① + ② + ③ = **62%** (activos de riesgo) / ④ **38%** (cash y bonos cortos). Risk Budget compatible con phase Caution profundizándose.

**Verificación de la regla ±10-15pt** (Δ vs anchor 5/15):
- Core: 24% → 23% (-1pt) ✓
- Defensivo: 23% → 24% (+1pt) ✓
- Tema/Hedge: 16% → 15% (-1pt) ✓
- Cash: 37% → 38% (+1pt) ✓
- **Cambio total absoluto: 4pt** (1+1+1+1). Muy dentro del límite ±10-15pt — estilo Monty de ajuste micro por trigger técnico (10Y rompió 4,50%, ahora en red line 4,59%) y evento binario (NVDA mié AMC).

**Ejemplo $100K**:
- Core $23K (SPY $13K + DIA $10K + QQQ $0K)
- Defensivo $24K (XLV $12K + XLP $12K)
- Tema/Hedge $15K (GLD $13K + XLE $2K)
- Cash $38K (BIL principalmente)
- **Total $100K** ✓ (23+24+15+38=100)

### Niveles de compra/venta clave

| Activo | Compra | Venta parcial | Stop |
|---|---|---|---|
| **S&P 500 (SPX)** | 7250 (gap fill) / 7100 (soporte mayor) | 7517 (re-test ATH) / 7600 | **7338 cierre semanal** (low semana 5/15) |
| **Nasdaq 100 (NDX)** | 28000 / 26500 (soporte intermedio) | 29679 (re-test ATH) | **28628 cierre 2 días** (low semana 5/15) |
| **QQQ** (~$710, NDX 29125) | $690 (gap) / $670 | $730 (ATH zone) | $695 cierre 2 días |
| **DJIA** | 48500 / 46833 (MA50) | 50200 (ATH) | 48500 cierre por debajo |
| **IWM** (~$277,60) | $270 / $262 (MA20) | $285 / $295 | $262 cierre por debajo |
| **WTI ($100,70)** | $95 (zona psicológica) / $85 | $110 / $115 (re-spike Hormuz) | $95 cierre 2 días |
| **Oro (GC $4559,70 / GLD $417,29)** | GLD $410 (pullback técnico) / $395 (MA50 GC-equiv) | GLD $430 / $445 | GLD $390 cierre por debajo (MA50 GC $4186 → GLD-equiv) |
| **Cobre (HG $6,22)** | $6,00 (pullback) / $5,35 (MA50) | $6,60 (high reciente) | $5,35 cierre por debajo |

### Sector allocation (modelo)

| Sector | ETF | % | Stance |
|---|---|---|---|
| Broad US | SPY | 13% | **-1pt** (SPX rechazó ATH 7517, vela roja -1,24% 5/18) |
| Dividendos (Dow) | DIA | 10% | Mantener (DJIA RSI 59,25 sano, el menos extendido) |
| Tech | QQQ | 0% | Mantener en 0 (NDX RSI 73,21 + NVDA binario mié) |
| Healthcare | XLV | 12% | **+1pt** (único defensivo trend UP; MDT mié BMO; UNH +24,5% mensual) |
| Staples | XLP | 12% | Mantener (Cons Staples interno 21,30% RED-DOWN; ancla pre-WMT jue) |
| Oro | GLD | 13% | Mantener (hedge Warsh-ciclo + Tail Risk Hormuz; close $417,29 -2,32%, soporte MA50 GC $4186 → GLD-equiv $390) |
| Energy | XLE | 2% | **-1pt** (Energy interno overbought slope -1,479; WTI -4,48% confirma top) |
| Cash/BIL | BIL | 38% | **+1pt** (buffer adicional, 10Y red line + NVDA + FOMC Minutes mismo día) |
| **Total** | | **100%** | (13+10+0+12+12+13+2+38=100) ✓ |

### Eventos clave de la semana (ET base, JST/ART abajo)

| Día | Evento | Hora ET | Impacto | IR / Source |
|---|---|---|---|---|
| **lun 5/18** | BIDU Q1 2026 + G7 Finance Ministers París (start) | 8:00 ET / EOD | ★★ | [Baidu IR](https://ir.baidu.com/news-releases/news-release-details/baidu-report-first-quarter-2026-financial-results-may-18-2026) |
| **mar 5/19** | **HD Q1 FY27 BMO** (release ~6:00 ET / call 9:00) | BMO | ★★★★ (pulse consumer) | [HD IR](https://ir.homedepot.com/news-releases/2026/05-05-2026-130040601) |
| **mar 5/19** | Pending Home Sales abril | 10:00 | ★ | [NAR](https://www.nar.realtor/research-and-statistics/housing-statistics/pending-home-sales) |
| **mar 5/19** | TOL Toll Brothers Q2 FY26 AMC | 16:15 | ★★ | [TOL IR](https://investors.tollbrothers.com/) |
| **mié 5/20** | **MDT Q4 FY26 BMO** | 7:00 | ★★★★ | [MDT IR](https://investorrelations.medtronic.com/) |
| **mié 5/20** | **ADI Q2 FY26 BMO** | 7:00 | ★★★★ (semis pre-NVDA read) | [ADI IR](https://investor.analog.com/news-releases/news-release-details/analog-devices-report-second-quarter-fiscal-year-2026-financial) |
| **mié 5/20** | **TGT Q1 FY26 BMO** | 8:00 | ★★★★ | [TGT IR](https://corporate.target.com/investors/events-presentations) |
| **mié 5/20** | **LOW Q1 FY26 BMO** | 9:00 | ★★★★ | [LOW IR](https://corporate.lowes.com/investors) |
| **mié 5/20** | Gov Barr — speech (Atlanta) | 9:15 | ★★ | [Fed May 2026](https://www.federalreserve.gov/newsevents/2026-may.htm) |
| **mié 5/20** | **FOMC Minutes (April 28-29)** | **14:00** | ★★★★ | [FOMC Calendars](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| **mié 5/20** | **INTU Q3 FY26 AMC** | 16:30 | ★★★★ (tax season + AI) | [INTU IR](https://investors.intuit.com/financial-information/financial-results) |
| **mié 5/20** | **NVDA Q1 FY27 AMC** (release 16:20 / call 17:00) | **AMC** | ★★★★★ (evento dominante) | [NVIDIA IR](https://investor.nvidia.com/financial-info/quarterly-results/default.aspx) |
| **jue 5/21** | **WMT Q1 FY27 BMO** (release ~7:00 / call 8:00) | BMO | ★★★★ (consumer low-mid) | [WMT IR](https://corporate.walmart.com/news/events/fy2027-q1-earnings-release) |
| **jue 5/21** | Initial Jobless Claims + Durable Goods + Housing Starts | 8:30 | ★★ | [DOL](https://www.dol.gov/ui/data.pdf) |
| **mié 5/20** | **TJX Q1 FY27 BMO** (release pre-9:30, call 11:00 ET) | BMO | ★★★ | [TJX IR](https://investor.tjx.com/) |
| **jue 5/21** | WDAY Q1 FY27 AMC | 16:30 | ★★★ | [Workday IR](https://investor.workday.com/news-and-events/press-releases/news-details/2026/Workday-to-Announce-Fiscal-2027-First-Quarter-Financial-Results-on-May-21-2026/default.aspx) |
| **vie 5/22** | **Gov Waller — Frankfurt lecture** | 4:00 (10:00 CEST) | ★★★★ (signal Warsh-ciclo) | [Fed 2026 speeches](https://www.federalreserve.gov/newsevents/speech/2026-speeches.htm) |
| **vie 5/22** | LEI Conference Board abril | 10:00 | ★★ | [Conference Board](https://www.conference-board.org/topics/us-leading-indicators/) |

**Fed Blackout**: **NO activo esta semana** (terminó 4/30 ET). Próximo Blackout: **sáb 6/6 — jue 6/18 ET** pre-FOMC 16-17 junio (primera reunión Warsh-Chair). [PDF Blackout Calendar](https://www.federalreserve.gov/monetarypolicy/files/fomc-blackout-period-calendar.pdf) verificado.

---

## Planes de escenario

### Escenario Base — "Caution se profundiza, corrección -3 a -6% / NVDA in-line + Minutes balanced" — **52%**

- **Triggers** (necesita ≥3 confirmados, cierre semanal donde aplique): NVDA Revenue $43-45B con guidance Q2 in-line, sin sorpresa negativa material / FOMC Minutes lenguaje balanceado data-dependent / VIX cierra rango 17-22 / US10Y oscila 4,50-4,65% sin breakout claro / SPX corrige a 7100-7250 / Uptrend Ratio profundiza a 28-32% / Breadth 200MA cae a 54-56%
- **Acción**: mantener allocation **23/24/15/38**. No agregar Tech. Trimming gradual de winners 1M (CSCO, AMAT) si gap up oportunista. Hedges (GLD 13%, BIL 38%) intactos. Stops ATR 1,2× la semana NVDA
- **Probabilidad — estimación del autor**: 52% (base: SPX rechazó ATH con vela roja confirmada, Uptrend Ratio sin signo de bottom, dead cross 8MA<200MA activo, pero sin trigger Stress claro todavía)

### Escenario Risk-On — "Yields se relajan + rally se reanuda con amplitud" — **26%**

- **Triggers** (necesita ≥3 simultáneos, cierre 2 días donde aplique): NVDA Revenue ≥$45B + guide Q2 ≥$50B + GM >73% / FOMC Minutes referencia condicional a cuts H2 / VIX cierra <17 / **US10Y retrocede <4,50% en cierre semanal (idealmente <4,40%)** / **Uptrend Ratio cruza UP (>10MA 37,67%)** con slope >+0,10 / Breadth 200MA expande a 60%+
- **Acción**: Core 23→**26** (+3pt: SPY 13→15, QQQ 0→1 sólo si Uptrend GREEN confirmado, DIA 10 mantener); Defensivo 24→**22** (-2pt: XLV 12→11, XLP 12→11); Tema 15→**15** (mantener: GLD 13 + XLE 2); Cash 38→**37** (-1pt buffer release). **Total: 26+22+15+37=100%** ✓
- **Probabilidad — estimación del autor**: 26% (base: necesita **3 confirmaciones simultáneas** VIX + 10Y + Uptrend Ratio UP — el estado actual está deteriorándose, no mejorando; reducida vs 5/15 por profundización DOWN)

### Escenario Stress — "10Y rompe 4,60% / NVDA miss o guidance soft / corrección -7 a -12%" — **22%**

- **Triggers** (cualquiera dispara, cierre 2 días donde aplique): **US10Y cierre semanal >4,60%** (zona extreme) / **VIX cierre >23 dos días consecutivos** / SPX cierre semanal <7338 → 7000 / NDX cierre <28628 → 26500 / NVDA gap post-earnings <-5% con cierre debajo MA50 / FOMC Minutes lenguaje hawkish ("upside risk to inflation", "limited progress") con bloque Hammack/Kashkari/Logan ganando momentum / WTI rebote cierre semanal >$115 (Hormuz escalation)
- **Acción**: Core 23→**18** (-5pt: SPY 13→8, DIA 10 mantener, QQQ 0); Defensivo 24→**26** (+2pt: XLV 12→13, XLP 12→13); Tema 15→**18** (+3pt: **GLD 13 mantener** flight-to-quality, **TLT 0→3** inicio posición bonos largos para escenario yield-relief post-shock, XLE 2 mantener hedge geopolítico residual = GLD 13 + TLT 3 + XLE 2 = 18); Cash 38→**38** (mantener buffer re-entry). **Total: 18+26+18+38=100%** ✓
- **Probabilidad — estimación del autor**: 22% (base: 10Y a 1bp del extreme + Uptrend Ratio 11 sesiones DOWN + concentración Tech +12,4% 1M con NDX RSI 73 sobrecompra = setup técnico de corrección rápida si NVDA decepciona o Minutes hawkish)

### Escenario Tail Risk — "Shock combinado / Hormuz escalation + NVDA disclosure mayor" — **menos del 5%, dentro del Stress arriba**

- **Triggers críticos** (combinación): **WTI cierre >$115** por escalation Hormuz **+** NVDA cuts guidance H2 FY27 / China revenue zero forward **+** US10Y rompe 4,65% sin Fed put **+** VIX cierre >23 con MA50 crossing up
- **Acción**: tratar como Stress amplificado — Core 18→**14**, Defensivo 26→**28**, Tema 18→**20** (GLD 13→15 amplificación flight-to-quality + Hormuz escalation premium, TLT 3 mantener, XLE 2 mantener hedge = 15+3+2=20), Cash 38→**38**. VIX call cubierta opcional (strike 25 expiry 6/19) sólo para experimentados. **Total: 14+28+20+38=100%** ✓

**Suma probabilidades**: 52% + 26% + 22% = **100%** (Tail Risk subsumido dentro de Stress). Probabilidades estimadas por el autor — ver disclaimer.

---

## Estado del mercado (cierre 5/18)

| Indicador | Valor | Triggers (Risk-On / Caution / Stress / Pánico) | Lectura |
|---|---|---|---|
| **VIX** | **18,67** (+1,30% sesión) | <17 / 20 / 23 / 26 | **Risk-On nominal pero al borde Caution** — a 1,33 puntos de 20 |
| **US 10Y** | **4,590%** (+12bp en 3 sesiones) | <4,11% / 4,36% / 4,50% / 4,60% | **RED LINE — a 1bp del extreme**, RSI 65,74 cerca sobrecompra |
| **Breadth 200MA** (CSV 5/14, **rezago 2 días hábiles**) | **57,39%** | ≥60 / 50 / 40 | **Border / Narrow Rally** |
| **Breadth 8MA** (CSV 5/14, rezago 2 días hábiles) | **56,76%** | — | **Dead cross 8MA<200MA confirmado 5/13** (-0,63pt) |
| **Uptrend Ratio** (CSV 5/14, rezago 2 días hábiles) | **35,24% RED-DOWN slope -0,376** (MA10 37,67) | <50 RED / >50 GREEN; slope ± | **RED-DOWN 11 sesiones consecutivas**, leading indicator sin signo de bottom |
| **SPX** | **7408,50** (-1,24% sesión) | 7338 / 7100 / 7000 | Rechazó ATH 7517, vela roja con mecha superior, RSI 69,55 |
| **NDX** | **29125,20** (-1,54% sesión) | 28628 / 26500 | Rechazó ATH 29679, **RSI 73,21 sobrecompra**, +57% vs MA200 |
| **DJIA** | **49526,17** (-1,07% sesión) | 48500 / 46833 | Rechazó ATH 50200, RSI 59,25 (más sano de los grandes) |
| **IWM** | **~$277,60** (-2,41% sesión) | $270 / $262 | Pullback ordenado desde $285 |
| **WTI** (FMP spot) | **$100,70** (-4,48% sesión) | $95 / $85 / $75 | Pullback fuerte desde pico $115 — top de rally |
| **Oro (GC $4559,70 / GLD $417,29)** | GC -0,06% / GLD -2,32% | GLD $410 / $390 (MA50 GC-equiv) | Consolidación constructiva post-rally en GC; GLD bajó más que GC por dinámica del ETF (USD/holdings), aún sobre soporte técnico |
| **Cobre (HG $6,22)** | -0,46% | $6,00 / $5,35 | Breakout estructural; RSI 63 saludable |
| **Uranium (URA $49,93)** | **-9,51% sem** | $47,50 / $45,73 (MA50) | Corrección activa post-doble techo $58-62 |

**Sectores con uptrend trend UP (3 de 11)**: Information Technology (39,81% slope +0,234), Materials (39,83% slope +0,407), Health Care (31,21% slope +0,128)
**Sectores con uptrend trend DOWN (8 de 11)**: Energy 57,14% **overbought** slope -1,479 / Real Estate 42,57% / Financials 41,52% / Industrials 38,48% / Utilities 25,37% / Communication 23,89% / Consumer Staples 21,30% / **Consumer Discretionary 18,79% oversold**

**Veredicto**: **Caution confirmada y profundizándose**. Tres índices con velas rojas de rechazo simultáneas en ATH + 10Y en red line + Uptrend Ratio 11 sesiones DOWN sin signo de bottom + dead cross 8MA<200MA activo + Energy overbought rompiéndose por dentro = el escenario más frágil de las últimas 8 semanas. Pero sin VIX >20 ni 10Y >4,60% en cierre semanal, el Stress declarado está pendiente — sólo postura defensiva preventiva.

---

## Tácticas de commodities/sectores

| Tema | Cierre 5/18 | Acción | Razonamiento (1 frase) |
|---|---|---|---|
| **Oro (GLD/GC)** | GC $4559,70 / GLD $417,29 | **Mantener 13%** | Consolidación constructiva post-rally en GC, hedge primer ciclo Warsh + Hormuz Tail Risk; GLD -2,32% el 5/18 por dinámica ETF pero soporte técnico intacto (MA50 GC-equiv $390); breakout potencial sobre GC $4750 |
| **Energy (XLE/WTI)** | WTI $100,70 (-4,48% sesión) | **Cortar -1pt a 2%** | Sector interno 57,14% **overbought slope -1,479 DOWN** (top forming confirmado); WTI rolled del pico $115 con vela -4,48%; lidera 1W (+4,99%) por inercia geopolítica pero internals rotos |
| **Tech (QQQ/SOXX)** | NDX 29125 RSI 73,21 | **Mantener QQQ en 0** | NDX rechazó ATH 29679 con vela roja, RSI 73 sobrecompra extrema + NVDA evento binario mié AMC; asimetría riesgo/recompensa peor del año, no agregar hasta post-evento |
| **Healthcare (XLV)** | sector trend UP slope +0,128 | **Aumentar +1pt a 12%** | Único defensivo con trend UP; UNH +24,5% mensual y LLY +11,2% confirman momentum healthcare premium; MDT reporta mié BMO con setup constructivo |
| **Staples (XLP)** | Cons Staples interno 21,30% RED-DOWN | **Mantener 12%** | Ancla pre-WMT jue BMO; sector en oversold técnico pero trend DOWN no permite agregar todavía; mantener exposure existente |
| **Cobre (HG)** | $6,22 | **Atención (no agregar)** | Breakout estructural sostenido sobre $6,00, MACD +0,229 bullish; pullback a $6,00 o $5,35 sería entry favorable; divergencia con Basic Materials sector (-3,50% 1W) sugiere esperar |
| **Uranium (URA $49,93)** | -9,51% sem | **No comprar / vigilar invalidación** | Corrección activa post-doble techo $58-62; si rompe MA50 $45,73 weekly close, riesgo a $40; tendencia primaria intacta pero short-term bajista |
| **NVDA individual** | -- | **Pre-evento, no agregar / no recortar** | Q1 FY27 AMC mié 5/20 16:20 ET. **Implied move ~7-9%**. Evaluar **gap up +8/+12%** (Bull) o **gap down -8/-12%** (Bear) post-evento; no operar AH si no estás monitoreando activamente |

---

## Guía operativa para tiempo parcial

### Check matutino (antes de apertura US)

- **Martes 5/19 apertura** ejecutar el micro-ajuste vs anchor 5/15 (24/23/16/37 → 23/24/15/38):
  - Core -1pt (SPY 14→13)
  - Defensivo +1pt (XLV 11→12)
  - Tema/Hedge -1pt (XLE 3→2)
  - Cash +1pt (37→38, BIL)
- Verificar gaps premarket NVDA / QQQ / NDX (zona ATH digestion)
- Confirmar **US10Y vs 4,60% extreme**: cierre semanal >4,60% activa Stress declarado; oscilación 4,50-4,65% mantiene Caution
- Confirmar **VIX premarket**: >19,5 = primera campanada; >20 cierre = primer día Caution-confirm; segundo día = switch operativo Stress
- Confirmar **XLE flat o negativo**: Energy sector top forming — no perseguir, ejecutar el cut planeado

### Chequeo nocturno (JST + ART) — semana operativa

| Día | Hora ET | Hora JST | Hora ART | Evento | Decisión |
|---|---|---|---|---|---|
| **lun 5/18** | EOD | mar 05:00 JST | lun 17:00 ART | Cierre 5/18 (-1,24% SPX) | Confirmar 10Y close y reacción AH (NVDA/MSFT/META) |
| **mar 5/19** | **6:00 ET (release) / 9:00 ET (call)** | **mar 19:00 / 22:00 JST** | **mar 07:00 / 10:00 ART** | **HD Q1 FY27 BMO** | Comp sales US ≥+4% → consumer cíclico revalidado; <+2,5% → primer crack retail (presagio NVDA/WMT) |
| **mar 5/19** | 16:00 ET | mié 05:00 JST | mar 17:00 ART | Cierre día 2 (post-HD) | Verificar reacción Consumer Discretionary (XLY) y Russell |
| **mié 5/20** | **7:00 ET** | **mié 20:00 JST** | **mié 08:00 ART** | **MDT + ADI BMO** | MDT raise guidance FY27 → XLV revalidado; ADI Q2 EPS vs $2,89 = read pre-NVDA semis |
| **mié 5/20** | **8:00 / 9:00 ET** | **mié 21:00 / 22:00 JST** | **mié 09:00 / 10:00 ART** | **TGT + LOW BMO** | Discretionary mid-tier (TGT) + housing improvement (LOW) — beat = consumer holding up; miss = recession signal |
| **mié 5/20** | 9:15 ET | mié 22:15 JST | mié 10:15 ART | Gov Barr — speech Atlanta | Inflation persistence framing — secundario |
| **mié 5/20** | **14:00 ET** | **jue 03:00 JST** | **mié 15:00 ART** | **FOMC Minutes (April 28-29)** | Hawkish ("persistence", "limited progress") → 10Y +8/+12bp rompe 4,65% → SPX -1/-1,5%; balanced → mínima reacción |
| **mié 5/20** | **16:20 ET (release) / 17:00 ET (call)** | **jue 05:20 / 06:00 JST** | **mié 17:20 / 18:00 ART** | **NVDA Q1 FY27 AMC** ⭐ evento dominante | **Bull (≥$45B + guide ≥$50B + GM >73%)** → gap up +8/+12% → NDX +1,5/+2,5% jue → Risk-On scenario; **Bear (gap <-5% o guide <$48B)** → NDX -3/-5% jue → Stress scenario |
| **mié 5/20** | 16:30 ET | jue 05:30 JST | mié 17:30 ART | INTU Q3 FY26 AMC | Tax season + AI software — secundario |
| **jue 5/21** | **7:00 ET (release) / 8:00 ET (call)** | **jue 20:00 / 21:00 JST** | **jue 08:00 / 09:00 ART** | **WMT Q1 FY27 BMO** | Comp +3,5%+ + raise → defensive bid revalidado; comp <+2,5% + cut → stagflation signal (XLP -1,5%, bonds bid) |
| **jue 5/21** | 8:30 ET | jue 21:30 JST | jue 09:30 ART | Claims + Durable Goods + Housing Starts | Claims >225K + Housing Starts -5% MoM = recession bid bonds |
| **mié 5/20** | ~9:00 ET (release) / 11:00 ET (call) | mié 22:00 / jue 00:00 JST | mié 10:00 / 12:00 ART | **TJX Q1 FY27 BMO** | Off-price retail — defensivo consumer; cluster con cluster retail mié; comp <+2% confirma debilidad trade-down |
| **jue 5/21** | 16:30 ET | vie 05:30 JST | jue 17:30 ART | WDAY Q1 FY27 AMC | Enterprise software — tema AI lateral |
| **vie 5/22** | **4:00 ET (10:00 CEST)** | **vie 17:00 JST** | **vie 05:00 ART** | **Gov Waller — Frankfurt Economic Outlook** | Hawkish (35%) → 10Y +5bp cierra cerca 4,65%; dovish surprise (15%) → 10Y -7bp; neutral (50%) probable |
| **vie 5/22** | 10:00 ET | vie 23:00 JST | vie 11:00 ART | LEI Conference Board abril | LEI -0,3/-0,5% confirma slowdown signal (bond bid marginal) |

### Cuidados de la semana

- **10Y en RED LINE (4,59%) a 1bp del extreme (4,60%)**: el catalizador agravante #1 de la semana. Cierre semanal >4,60% **activa Stress declarado** independiente de los demás triggers. Reducir Tech mega-cap inmediatamente si dispara.
- **NVDA + FOMC Minutes + Barr mismo día (mié 5/20)**: triple catalizador concentrado entre 14:00 y 17:00 ET. La reacción AH (NVDA) y next-day open (jueves) pueden combinar señales hawkish Fed + miss/beat NVDA en gap único. **Evitar trades intra-AH** si no estás monitoreando activamente.
- **Uptrend Ratio 11 sesiones DOWN consecutivas sin signo de bottom**: si el próximo update CSV (próximos días) muestra ratio <30% o slope <-0,5 sostenido = **stress táctica confirmada** independiente del precio.
- **Energy en top forming (sector interno 57,14% overbought slope -1,479)**: XLE -1pt anticipa la rotación; si WTI rompe $95 al cierre semanal, reducción adicional posible a XLE 1%.
- **Hormuz tregua frágil + ship seizure 5/15 + waiver Russia oil expirado 5/16**: dos chokepoints de supply activos. WTI >$115 sostenido = Tail Risk activado (Hormuz escalation) + 10Y +10bp adicional.
- **WMT jue es el barómetro consumer low/mid-income**: comp <+2,5% + guidance cut = single best signal de recession risk; combinado con HD/TGT/LOW miss = stagflation lite confirmada (consumer hurt + prices still up).

---

## Gestión de riesgo

- **Position size por nombre individual**: máximo 5% (semis ATR-based)
- **Stops ATR**:
  - Normal: ATR 1,6× (-6 a -8%)
  - **Semana NVDA (esta semana): reducir a ATR 1,2×** (-5 a -6%) — la volatilidad intra-evento puede gappear stops normales
- **Hedge principal (ETF-based)**: Cash 38% + GLD 13% + XLP 12% + XLV 12% = **75% del portfolio en hedges/defensivos directos o indirectos**
- **Hedge avanzado opcional** (sólo experimentados, no esencial):
  - **VIX call strike 25** (expiry 6/19) — propósito hedge NVDA downside + FOMC Minutes hawkish; estima 1-2% del portfolio cost máximo, asimétrico dado VIX 18,67
  - **QQQ put strike $680** (current ~$710, -4,2% OTM, propósito hedge NVDA miss, expiry 6/19, IV ~28%) — opcional, cubre caso NVDA gap -8% + NDX -5%
  - **GLD call strike $435** (current $417,29, +4,2% OTM, propósito hedge Tail Risk Hormuz + breakout, expiry 6/19, IV ~22%) — alternativa long-vol asimétrica si el escenario Stress combina shock geopolítico con flight-to-quality
- **Riesgos clave esta semana**:
  1. **NVDA gap post-earnings <-5%** (mié AH / jue open) → NDX -3/-5% → contagio AMD/AVGO/AMAT/MU + activa Stress
  2. **US10Y cierre semanal >4,60%** → multiple compression Tech + Real Estate breakdown + Stress declarado
  3. **VIX cierre >20 dos días consecutivos** → switch operativo a Caution declarado → trim 5-10% adicional Tech mega-cap (no aplica aquí ya que QQQ está en 0, pero impacta a SPY)
  4. **WMT miss + guidance cut** → recession signal → XLP/XLY -1,5/-3%, bonds bid (única vía bullish bonos esta semana)
  5. **Hormuz re-escalation formal** → WTI >$115 → re-inflation + 10Y +10bp + Tail Risk activado
- **Disciplina**: respetar el stop SIEMPRE. Si se activa Stress (cualquier trigger), ejecutar la rotación al cierre del día disparador, sin dudar. **No promediar a la baja en Tech mega-caps** (SPY weighting ya hace el trabajo).

---

## Resumen final

La semana del **18 de mayo de 2026** llega con **Caution confirmada y profundizándose**: el cierre del 5/18 imprimió **velas rojas de rechazo simultáneas** en SPX/NDX/Dow desde sus ATH del 5/14, el **US10Y rompió 4,50% y está en 4,59% (RED LINE, a 1bp del extreme 4,60%)**, el VIX 18,67 está a 1,33 puntos del umbral Caution, y los internals siguen deteriorándose (Uptrend Ratio **11 sesiones DOWN sin bottom**, dead cross 8MA<200MA confirmado 5/13, 8 de 11 sectores con trend interno DOWN). El evento dominante es **NVDA Q1 FY27 AMC el miércoles 5/20 16:20 ET (5:20 JST jueves 5/21 / 17:20 ART miércoles 5/20)**, acompañado de **FOMC Minutes 14:00 ET** el mismo día y una semana retail pesada (HD mar BMO / MDT+ADI+TGT+LOW mié BMO / WMT jue BMO). El micro-ajuste **23/24/15/38** desde el anchor 5/15 (24/23/16/37) responde al deterioro técnico marginal: SPY -1pt, XLV +1pt, XLE -1pt, Cash +1pt — cambio total absoluto de **4pt**, dentro del corte gradual estilo Monty. Para activar Risk-On (26%) necesitamos 3 confirmaciones simultáneas: VIX <17 + 10Y <4,50% + Uptrend Ratio UP. Para activar Stress (22%) cualquiera de: 10Y >4,60% cierre / VIX >23 cierre 2 días / NVDA gap <-5%. Hasta entonces, **postura Caution con cobertura preventiva, stops ATR 1,2× la semana NVDA, no perseguir índices, hedges activos (GLD 13% + XLP 12% + XLV 12% + Cash 38% = 75%) y disciplina absoluta de stops**.

---

## Sources

- **Breadth & Uptrend Ratio**: CSV TraderMonty local (`data/breadth-local/market_breadth_data.csv`, `uptrend_ratio_timeseries.csv`, `sector_summary.csv`) al **5/14/2026 (rezago 2 días hábiles vs precios 5/18)**.
- **Precios mercado (FMP API al cierre 5/18/2026)**: VIX 18,67; SPX 7408,50; NDX 29125,20; DJIA 49526,17; IWM ~$277,60; WTI $100,70; Gold GC $4559,70; Copper HG $6,22; URA $49,93; US10Y 4,590%.
- **Calendario macro (oficial)**: [BLS Schedule](https://www.bls.gov/schedule/2026/05_sched_list.htm) · [BLS NFP](https://www.bls.gov/schedule/news_release/empsit.htm) · [BLS CPI](https://www.bls.gov/schedule/news_release/cpi.htm) · [BEA Schedule (PCE)](https://www.bea.gov/news/schedule) · [Census Calendar](https://www.census.gov/economic-indicators/calendar-listview.html) · [NAR Pending Home Sales](https://www.nar.realtor/research-and-statistics/housing-statistics/pending-home-sales) · [DOL Claims](https://www.dol.gov/ui/data.pdf) · [Conference Board LEI](https://www.conference-board.org/topics/us-leading-indicators/) · [NY Fed Empire Survey](https://www.newyorkfed.org/survey/empire/empiresurvey_overview)
- **Fed (oficial)**: [FOMC Calendars](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) (Minutes 5/20 14:00 ET confirmado, próximo FOMC 6/16-17 Warsh-Chair) · [Fed May 2026 Events](https://www.federalreserve.gov/newsevents/2026-may.htm) (Barr 5/20 9:15 + Waller Frankfurt 5/22 confirmados) · [Fed 2026 Speeches](https://www.federalreserve.gov/newsevents/speech/2026-speeches.htm) · [FOMC Blackout Calendar PDF](https://www.federalreserve.gov/monetarypolicy/files/fomc-blackout-period-calendar.pdf) (verificado: 5/18-5/22 NO está en blackout) · [April 28-29 Statement](https://www.federalreserve.gov/newsevents/pressreleases/monetary20260429a.htm)
- **Earnings IR (oficiales — uno por ticker, Issue #17 priority)**:
  - **NVDA** (5/20 AMC): [investor.nvidia.com](https://investor.nvidia.com/financial-info/quarterly-results/default.aspx) + [press release schedule](https://nvidianews.nvidia.com/news/nvidia-sets-conference-call-for-first-quarter-financial-results-6919947)
  - **HD** (5/19 BMO): [ir.homedepot.com](https://ir.homedepot.com/news-releases/2026/05-05-2026-130040601)
  - **MDT** (5/20 BMO): [investorrelations.medtronic.com](https://investorrelations.medtronic.com/)
  - **ADI** (5/20 BMO): [investor.analog.com](https://investor.analog.com/news-releases/news-release-details/analog-devices-report-second-quarter-fiscal-year-2026-financial)
  - **TGT** (5/20 BMO): [corporate.target.com](https://corporate.target.com/investors/events-presentations)
  - **LOW** (5/20 BMO): [corporate.lowes.com](https://corporate.lowes.com/investors)
  - **INTU** (5/20 AMC): [investors.intuit.com](https://investors.intuit.com/financial-information/financial-results)
  - **WMT** (5/21 BMO): [corporate.walmart.com](https://corporate.walmart.com/news/events/fy2027-q1-earnings-release)
  - **TJX** (5/20 BMO): [investor.tjx.com](https://investor.tjx.com/)
  - **WDAY** (5/21 AMC): [investor.workday.com](https://investor.workday.com/news-and-events/press-releases/news-details/2026/Workday-to-Announce-Fiscal-2027-First-Quarter-Financial-Results-on-May-21-2026/default.aspx)
  - **TOL** (5/19 AMC): [investors.tollbrothers.com](https://investors.tollbrothers.com/)
  - **BIDU** (5/18): [ir.baidu.com](https://ir.baidu.com/news-releases/news-release-details/baidu-report-first-quarter-2026-financial-results-may-18-2026)
- **Geopolítica & noticias (3rd party — Issue #17 separación: hechos reportados por medios; probabilidades = estimación del autor)**: [PBS — Strait of Hormuz crisis](https://www.pbs.org/newshour/world/tensions-flare-near-strait-of-hormuz-as-one-ship-is-seized-and-another-is-sunk) · [Wikipedia 2026 Strait of Hormuz crisis](https://en.wikipedia.org/wiki/2026_Strait_of_Hormuz_crisis) · [CNN — Trump rejects Iran framework](https://www.cnn.com/2026/05/11/world/live-news/iran-war-proposal-trump) · [Bloomberg — Ukraine on Russia oil sanctions](https://www.bloomberg.com/news/articles/2026-05-18/ukraine-says-it-s-unsure-of-us-stance-on-russia-oil-sanctions) · [CNBC — PPI April](https://www.cnbc.com/2026/05/13/ppi-inflation-report-april-2026-.html) · [Channels TV — G7 Finance Ministers Paris](https://www.channelstv.com/2026/05/18/g7-finance-chiefs-meet-amid-mideast-truce-uncertainties/) · [Bloomberg — Bond yields](https://www.bloomberg.com/news/articles/2026-05-15/treasuries-lead-global-bond-yields-higher-on-inflation-angst)
- **Anchor de continuidad**: `blogs/2026-05-15-weekly-strategy.md` (24/23/16/37 publicado)
- **Reports upstream**: `reports/2026-05-18/technical-market-analysis.md`, `reports/2026-05-18/us-market-analysis.md`, `reports/2026-05-18/market-news-analysis.md`

---

## Disclaimer

Este artículo presenta un **modelo de cartera y análisis** con fines educativos e informativos; **NO constituye asesoramiento financiero individual**. Las menciones a "ejecutar al lunes en la apertura", "comprar a tal nivel", "rotar tal porcentaje" o cualquier indicación de timing/ejecución describen **ejecuciones hipotéticas dentro de un modelo de portafolio ilustrativo** y no son recomendaciones personales de operación. Cada lector debe considerar su **tolerancia al riesgo, horizonte temporal, situación fiscal y composición patrimonial** antes de operar; cuando corresponda, consultá con un **asesor financiero matriculado** habilitado en tu jurisdicción. Las **probabilidades de escenarios listadas (52/26/22) son estimaciones personales del autor** (筆者推定 / author estimate), no consensos verificables de mercado ni implied de opciones. Las fuentes citadas son **factuales** (eventos, fechas, datos publicados, releases IR oficiales); las **interpretaciones, asignaciones, niveles y porcentajes son interpretativas del autor**. Operar con apalancamiento, derivados u opciones implica riesgo de pérdida total o superior al capital inicial. Los rendimientos pasados no garantizan resultados futuros.

---

*Reporte semanal: semana del 2026-05-18 (publicado 2026-05-18). Anchor de continuidad: `blogs/2026-05-15-weekly-strategy.md` (24/23/16/37). Regla aplicada: ±10-15pt gradual, cambio total absoluto **4pt**.*
