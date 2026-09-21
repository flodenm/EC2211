# Lecture Notes 10: Exchange Rates

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)

This is an agent-oriented rendering of `main_LN10.tex`. Frame headings follow the lecture source. Figure filenames and notes are retained when present; consult the lecture slides for the visual itself.


### Contents and literature

- Nominal and real exchange rates
- Purchasing power parity and the Balassa–Samuelson effect
- Interest-rate differentials and exchange rates
- Exchange rates in the IS–MP–PC and AS–AD frameworks
- Exchange-rate regimes and currency crises

    Literature:
- Jones (2024), chapter 20

## Nominal and real exchange rates

### Nominal exchange rates

A nominal exchange rate is the price of one currency in terms of another.

    We express the nominal exchange rate, $E$, as **foreign currency per
    unit of domestic currency**:

$$E=\frac{euro}{SEK}$$

    when Sweden is the home country and the euro area is foreign.

- $E\uparrow$: the domestic currency **appreciates**
- $E\downarrow$: the domestic currency **depreciates**

    This convention follows Jones. Market quotations for SEK often use the inverse, so
    always check which currency appears in the numerator.

### Market quotations

EUR/SEK or EURSEK means that the first currency is the base currency:
- EURSEK is the number of SEK you need to buy one EUR
- On [Yahoo Finance](https://finance.yahoo.com/quote/EURSEK=X/) you can find quotations both for EURSEK and SEKEUR
- The following currencies (in order of priority) are typically used as the base currency: EUR, GBP, AUD, USD, CAD, CHF, JPY

**Figure source:** `USD_EUR.png`
Update the figure and make clear that this is USDSEK and EURSEK

### The real exchange rate

The **real exchange rate**, $Q$, is the price of domestic goods relative
    to foreign goods:

$$
        Q=E\frac{P}{P^w}$$

    where $P$ is the domestic price level and $P^w$ is the foreign price level.

- $Q\uparrow$: real appreciation; domestic goods become relatively
              more expensive
- $Q\downarrow$: real depreciation; domestic goods become relatively
              cheaper

    Since prices are sticky in the short run, movements in $E$ often generate
    similar short-run movements in $Q$.

### The Swedish real and nominal exchange rate

- Why sharp depreciations in the 1970s and early 1980s?

- Why did the real krona appreciate from 1983 to 1992?

- Why do the real and nominal rates follow each other more closely from 1993?

**Figure source:** `SEK_real_and_nominal.png`

 {Exchange rate indices against narrow currency basket (higher value = stronger SEK). Source: [BIS](https://data.bis.org/topics/EER/data)}.

## Purchasing power parity and the Balassa–Samuelson effect

### Purchasing Power Parity, PPP

- Theory of long-run nominal exchange rate determination

- Stresses the importance of goods markets

- Developed largely by Swedish economist Gustaf Cassel (1866-1945)

### The law of one price

Let $P_i$ be the domestic-currency price of good $i$ and $P_i^w$ its
    foreign-currency price.

    With no transportation costs or trade barriers, arbitrage should imply the
    **law of one price**:

$$
        P_i^w=E P_i
         \Longleftrightarrow
        E=\frac{P_i^w}{P_i}$$

    A good cannot permanently be cheaper in one country if it can easily be
    purchased there and resold elsewhere.

### Purchasing power parity

Purchasing power parity applies the law of one price to aggregate price
    levels.

- **Absolute PPP**: $P^w=EP$, so $Q=1$
- **Relative PPP**: changes in the nominal exchange rate offset
              inflation differentials

$$\Delta\ln E \approx \pi^w-\pi.$$

    Relative PPP allows initial differences in price levels to persist.

### Why does purchasing power parity fail?

Large and persistent deviations from PPP are common because of:
- transportation costs and trade barriers
- different consumption baskets
- imperfect competition and price discrimination
- goods and services that cannot be traded internationally

    PPP is more useful as a long-run benchmark than as a description of
    short-run exchange-rate movements.

### The Economist's Big Mac index

**Figure source:** `MACRO6_Table20.01.jpg`

 Source: Jones, Table 20.1.

### A comparison: the iPhone index

iPhone 16, 128 GB, black, unlocked, October 21, 2024

```latex
lrrr
        \toprule
        Country & Local price & Exchange rate & USD price \\
        \midrule
        United States (NYC) & USD 903   & 1.0000  & 903 \\
        Sweden              & SEK 11,499& 10.5217 & 1,093 \\
        France              & EUR 969   & 0.9212  & 1,052 \\
        United Kingdom      & GBP 800   & 0.7680  & 1,042 \\
        Bulgaria            & BGN 1,929 & 1.8031  & 1,070 \\
        India               & INR 79,900& 84.0725 & 950 \\
        \bottomrule

```

    Why are international price differences much smaller for an iPhone than
    for a Big Mac?

### The Balassa–Samuelson effect

Why are aggregate price levels typically higher in rich countries?

1. Productivity in the tradable sector is higher in rich countries.
2. The law of one price links wages in the tradable sector to
              productivity.
3. Labor mobility tends to equalize wages across sectors within a
              country.
4. Nontradable services are therefore more expensive in rich
              countries even when productivity in those services is similar.

### Implications of the Balassa–Samuelson effect

- Price levels should be higher in rich countries than in poor
              countries when expressed in a common currency.
- Countries catching up through rapid productivity growth in the
              tradable sector should experience real appreciations.
- With a fixed nominal exchange rate, the real appreciation takes
              the form of higher domestic inflation.

    The Big Mac contains a great deal of local labor and other nontradable
    inputs. An iPhone is much more easily traded internationally.

### GDP and price levels

**Figure source:** `Fig_balassa_samuelson.png`

 Source: Penn World Table.

### Real exchange rates in the Baltics

**Figure source:** `RealExchRatesBaltics.png`

 Broad real exchange-rate indices, 2020=100. Source: BIS.

## Interest-rate differentials and exchange rates

### Interest rates and exchange rates: the intuition

Consider a small economy open to international financial flows.

    If the return on domestic assets rises relative to the return on foreign
    assets:
- investors want to hold more domestic assets
- demand for the domestic currency increases
- the domestic currency appreciates

    Hence a higher domestic interest rate relative to the foreign interest
    rate tends to raise both the nominal and, with sticky prices, the real
    exchange rate.

### A formal version: uncovered interest parity

A Swedish investor is indifferent between domestic and foreign one-period
    bonds when their expected returns are equal:

$$
        1+i_t=(1+i_t^w)\frac{E_t}{E_{t+1}^e}$$

    In logarithms, approximately,

$$e_t=i_t-i_t^w+e_{t+1}^e$$

    If the expected future exchange rate is unchanged, a higher domestic
    interest rate produces an immediate appreciation.

### From nominal to real interest rates and exchange rates

In the short run, prices and expected inflation adjust slowly.

    We therefore use the following transmission chain:

$$(i_t-i_t^w)\uparrow
         \Longrightarrow
        (r_t-r_t^w)\uparrow
         \Longrightarrow
        Q_t\uparrow$$

    The real appreciation makes domestic goods more expensive relative to
    foreign goods and reduces net exports.

    This is the link that Jones incorporates directly into the open-economy IS
    curve.

## Exchange rates in the short-run model

### The closed-economy IS curve

Recall the IS curve from the earlier lectures:

$$
        \widetilde{Y}_t=\alpha-\beta(r_t-\bar r),$$

    where $\widetilde{Y}_t$ is the output gap and $\bar r$ is the natural real
    interest rate.

    A higher real interest rate reduces investment and aggregate demand.

    We now add a second channel: the real interest rate also affects the real
    exchange rate and net exports.

### Net exports in Jones's model

In an open economy,

$$Y_t=C_t+I_t+G_t+NX_t$$

    Jones summarizes the exchange-rate channel with

$$
        \frac{NX_t}{\bar Y_t}
        =\alpha_{NX}-\beta_{NX}(r_t-r_t^w),
          \beta_{NX}>0$$

    A higher domestic real interest rate relative to the foreign rate:

$$r_t-r_t^w\uparrow
        \ \Longrightarrow\ Q_t\uparrow
        \ \Longrightarrow\ NX_t\downarrow$$

### The open-economy IS curve

Combining consumption, investment, government spending and net exports
    gives

$$
        \widetilde{Y}_t=\alpha-\beta(r_t-\bar r),$$

    where

$$\alpha
        &=\alpha_C+\alpha_G+\alpha_I+\alpha_{NX}-1
          +\beta_{NX}(r_t^w-\bar r)\\
        \beta&=\beta_I+\beta_{NX}$$

    The equation has the same form as before, but the slope and the intercept
    now contain open-economy forces.

### Two channels of domestic monetary policy

Suppose that the central bank raises the domestic real interest rate.
Interest-rate channel
            A higher $r_t$ reduces investment.
Exchange-rate channel
            A higher $r_t-r_t^w$ appreciates the currency and reduces net
            exports.

    Both channels reduce aggregate demand. In this sense, monetary policy may
    have a stronger demand effect in a small economy open to trade and
    international financial flows.

### The open-economy IS–MP–PC model

The structure of the model is unchanged:
- **IS**: the output gap depends negatively on the domestic real
              interest rate
- **MP**: the central bank sets the interest rate in response to
              inflation and economic activity
- **PC**: inflation depends on expected inflation, the output
              gap and cost shocks

    The open economy adds two links to the IS curve:

$$r_t-r_t^w \longrightarrow Q_t \longrightarrow NX_t$$

    Foreign monetary policy can therefore shift domestic aggregate demand, and
    domestic monetary policy also works through the exchange rate.

### A foreign monetary-policy tightening

First hold the domestic policy rate unchanged and suppose that $r_t^w$
    increases.

$$r_t^w\uparrow
         \Longrightarrow
        r_t-r_t^w\downarrow
         \Longrightarrow
        Q_t\downarrow
         \Longrightarrow
        NX_t\uparrow$$

    In equation \eqref{eq:is_open}, the increase in $r_t^w$ raises $\alpha$ and
    shifts the IS curve outward.

    Before the domestic monetary-policy response, this is a
    **positive aggregate-demand shock** for the domestic economy.

### How should the domestic central bank respond?

Suppose that the domestic central bank wants to stabilize output after
    $r_t^w$ rises.

- If it raises $r_t$ by exactly the same amount, the exchange rate
              and net exports are unchanged, but investment falls.
- Output would then fall below potential.
- It should therefore raise $r_t$ by **less** than the increase
              in $r_t^w$.

    The smaller increase in $r_t$ balances two effects:

$$I_t\downarrow
         \text{and}
        Q_t\downarrow\ \Longrightarrow\ NX_t\uparrow$$

### Foreign tightening and the domestic policy response

**Figure source:** `Figs/IS_shift.png`

    The higher foreign interest rate shifts the IS curve outward. If the
    domestic central bank wants to stabilize output, it raises its interest
    rate by less than the foreign increase.

### Foreign monetary policy in the AS–AD framework

Jones now considers the case in which domestic monetary policy does not
    fully offset the initial demand shock.

**Figure source:** `MACRO6_FIG20.05_box.jpg`

 Source: Jones, Figure 20.5.

### Interpreting the adjustment in Figure 20.5

1. Because the shock is not fully offset, the higher foreign interest
              rate depreciates the domestic currency and shifts AD to the
              right: $A\rightarrow B$.
2. The positive output gap raises inflation over time:
              $B\rightarrow C$.
3. Higher domestic inflation generates a real appreciation and
              gradually removes the increase in net exports.
4. When the foreign interest rate returns to normal, AD shifts back
              and the economy moves through $D$ toward $A$.

### An additional inflation channel

In Jones's benchmark, the exchange rate affects inflation through aggregate
    demand:

$$Q_t\downarrow \ \Longrightarrow\ NX_t\uparrow
        \ \Longrightarrow\ \widetilde{Y}_t\uparrow
        \ \Longrightarrow\ \pi_t\uparrow$$

    In practice, a depreciation can also raise inflation more directly:
- imported consumer goods become more expensive
- imported intermediate inputs raise firms' costs

    In our Phillips curve, this direct pass-through can be treated as a
    temporary cost shock, $\sigma_t>0$.

## Exchange-rate regimes and currency crises

### Fixed exchange rates

Under a credible fixed exchange rate,

$$E_t=E_{t+1}^e=\bar E.$$

    With free international financial flows, interest parity then implies

$$i_t=i_t^w.$$

    The domestic central bank must set its interest rate to maintain the peg.
    It cannot independently choose the interest rate needed to stabilize
    domestic output and inflation.

### The trilemma of international finance

**Figure source:** `MACRO6_FIG20.07_box.jpg`

 Source: Jones, Figure 20.7.

### Three possible regimes

An economy can combine at most two of the following:
1. a fixed exchange rate
2. free international financial flows
3. independent monetary policy

- Floating exchange rate $+$ free capital flows $\Rightarrow$
              monetary-policy autonomy
- Fixed exchange rate $+$ free capital flows $\Rightarrow$
              foreign monetary policy determines the domestic interest rate
- Fixed exchange rate $+$ monetary-policy autonomy $\Rightarrow$
              capital controls

### Why fixed exchange rates can become costly

Suppose that domestic prices rise faster than foreign prices while the
    nominal exchange rate is fixed.

$$Q=\bar E\frac{P}{P^w}\uparrow.$$

- The real exchange rate appreciates and net exports fall.
- Restoring competitiveness requires lower domestic inflation,
              falling domestic prices or a devaluation.
- Price adjustment is slow, and the recession needed to generate it
              may be costly.

    A **devaluation** lowers the fixed value of $E$; a revaluation raises it.

### The gold standard in the Great Depression

- The Depression began after the downturn in the United States in
              1929 and spread internationally.
- France, Germany and Italy attempted to maintain their exchange
              rates against gold.
- The United Kingdom, Sweden and Denmark left gold and depreciated
              their currencies in 1931.
- Recovery generally began earlier in countries that abandoned the
              gold standard.

    The fixed exchange rate transmitted contractionary monetary conditions
    across countries and constrained the policy response.

### The 1992 European currency crisis

- Most European currencies were effectively pegged to the German
              mark through the Exchange Rate Mechanism.
- German unification generated a domestic boom and inflationary
              pressure.
- The Bundesbank raised interest rates.
- Other European countries faced weak activity but had to raise
              interest rates to defend their pegs.

    Foreign monetary policy was poorly suited to domestic conditions, exactly
    the tension highlighted by the trilemma.

### Sweden and Germany around the 1992 crisis

**Figure source:** `SE_DE_inflation.png`

**Figure source:** `SE_DE_growth.png`

**Figure source:** `SE_DE_unemp.png`

 Inflation, GDP growth and unemployment. Source: IMF WEO.

### Loss of credibility makes the peg harder to defend

Interest parity can be written approximately as

$$i_t=i_t^w+e_t-e_{t+1}^e.$$

    If investors begin to expect a devaluation, $e_{t+1}^e$ falls.
    Maintaining the current value of $e_t$ then requires a higher domestic
    interest rate.

- The higher rate deepens the recession.
- A deeper recession may weaken confidence in the peg further.
- Expectations can therefore become partly self-fulfilling.

### The Swedish defense of the krona

**Figure source:** `Figs/Sweden1992.png`

### Swedish and German interest rates

**Figure source:** `SE_DE_5y.png`

**Figure source:** `SE_DE_5y_spread.png`

 Five-year government bond yields and the
    Sweden–Germany spread. Source: Riksbank.

### The krona was allowed to float in November 1992

**Figure source:** `SEK_DEM_1992.png`

### Monetary union

A common currency removes the possibility of a nominal devaluation between
    member countries.

- This eliminates currency risk within the union.
- But a common monetary policy may be poorly suited to countries hit
              by different shocks.
- Adjustment must instead occur through inflation differentials,
              wages, migration or fiscal policy.
- The euro crisis showed that destabilizing risk-premium dynamics
              can arise even without national currencies.

### Summing up

- The nominal exchange rate is the relative price of currencies;
              the real exchange rate is the relative price of goods.
- PPP is a long-run benchmark. Nontradable goods help explain
              persistent price-level differences.
- Interest-rate differentials affect exchange rates and net exports.
- In the open-economy IS curve, monetary policy operates through
              both investment and the exchange rate.
- Foreign monetary policy can shift domestic aggregate demand.
- A fixed exchange rate with free financial flows limits domestic
              monetary-policy autonomy.
