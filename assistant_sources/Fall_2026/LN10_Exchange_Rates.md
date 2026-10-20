# Lecture Notes 10: Exchange Rates

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)  
**Source update:** October 20, 2026

This is an agent-oriented rendering of `main_LN10.tex`. Frame headings follow the lecture source. Figure filenames and accompanying notes are retained; image contents are not inferred from filenames. Diagram descriptions are based on the explicit TikZ source.

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

We express the nominal exchange rate, $E$, as **foreign currency per unit of domestic currency**: 

$$
E=\frac{\text{euro}}{\text{SEK}}
$$

 when Sweden is the home country and the euro area is foreign.

- $E\uparrow$: the domestic currency **appreciates**

- $E\downarrow$: the domestic currency **depreciates**

This convention follows Jones. Market quotations for SEK often use the inverse, so always check which currency appears in the numerator.

### Market quotations

EUR/SEK or EURSEK means that the first currency is the base currency:

- EURSEK is the number of SEK you need to buy one EUR

- On [Yahoo Finance](https://finance.yahoo.com/quote/EURSEK=X/) you can find quotations both for EURSEK and SEKEUR

**Figure source:** `USDSEK_EURSEK.png`

Note that if SEK is the home currency, this figure plots $1/E$. Source: BIS.

### The real exchange rate

The **real exchange rate**, $Q$, is the price of domestic goods relative to foreign goods: 

$$
\label{eq:rer}
        Q=E\frac{P}{P^w}
$$

 where $P$ is the domestic price level and $P^w$ is the foreign price level.

- $Q\uparrow$: real appreciation; domestic goods become relatively more expensive

- $Q\downarrow$: real depreciation; domestic goods become relatively cheaper

Since prices are sticky in the short run, movements in $E$ often generate similar short-run movements in $Q$.

### The Swedish real and nominal exchange rate

- Why sharp depreciations in the 1970s and early 1980s?

- Why did the real krona appreciate from 1983 to 1992?

- Why do the real and nominal rates follow each other more closely from 1993?

**Figure source:** `SEK_real_and_nominal.png`

Exchange rate indices against narrow currency basket (higher value = stronger SEK). Source: [BIS](https://data.bis.org/topics/EER/data).

## Purchasing power parity and the Balassa–Samuelson effect

### Purchasing Power Parity, PPP

- Theory of long-run nominal exchange rate determination

- Stresses the importance of goods markets

- Developed largely by Swedish economist Gustaf Cassel (1866-1945)

### The law of one price

Let $P_i$ be the domestic-currency price of good $i$ and $P_i^w$ its foreign-currency price.

With no transportation costs or trade barriers, arbitrage should imply the **law of one price**: 

$$
\label{eq:loop}
        P_i^w=E P_i
        \qquad\Longleftrightarrow\qquad
        E=\frac{P_i^w}{P_i}
$$

A good cannot permanently be cheaper in one country if it can easily be purchased there and resold elsewhere.

### Purchasing power parity

Purchasing power parity applies the law of one price to aggregate price levels.

- **Absolute PPP**: $P^w=EP$, so $Q=1$

- **Relative PPP**: changes in the nominal exchange rate offset inflation differentials

$$
\Delta\ln E \approx \pi^w-\pi.
$$

Relative PPP allows initial differences in price levels to persist.

### Why does purchasing power parity fail?

Large and persistent deviations from PPP are common because of:

- transportation costs and trade barriers

- different consumption baskets

- imperfect competition and price discrimination

- goods and services that cannot be traded internationally

PPP is more useful as a long-run benchmark than as a description of short-run exchange-rate movements.

### The Economist’s Big Mac index

**Figure source:** `MACRO6_Table20.01.jpg`

Source: Jones, Table 20.1.

### A comparison: the iPhone index

iPhone 16, 128 GB, black, unlocked, October 21, 2024

| Country             | Local price | Exchange rate | USD price |
|:--------------------|------------:|--------------:|----------:|
| United States (NYC) |     USD 903 |        1.0000 |       903 |
| Sweden              |  SEK 11,499 |       10.5217 |     1,093 |
| France              |     EUR 969 |        0.9212 |     1,052 |
| United Kingdom      |     GBP 800 |        0.7680 |     1,042 |
| Bulgaria            |   BGN 1,929 |        1.8031 |     1,070 |
| India               |  INR 79,900 |       84.0725 |       950 |

Why are international price differences much smaller for an iPhone than for a Big Mac?

### The Balassa–Samuelson effect

Why are aggregate price levels typically higher in rich countries?

1.  Productivity in the tradable sector is higher in rich countries.

2.  The law of one price links wages in the tradable sector to productivity.

3.  Labor mobility tends to equalize wages across sectors within a country.

4.  Nontradable services are therefore more expensive in rich countries even when productivity in those services is similar.

### Implications of the Balassa–Samuelson effect

- Price levels should be higher in rich countries than in poor countries when expressed in a common currency.

- Countries catching up through rapid productivity growth in the tradable sector should experience real appreciations.

- With a fixed nominal exchange rate, the real appreciation takes the form of higher domestic inflation.

The Big Mac contains a great deal of local labor and other nontradable inputs. An iPhone is much more easily traded internationally.

### GDP and price levels

**Figure source:** `Fig_balassa_samuelson.png`

Source: Penn World Table.

### Real exchange rates in the Baltics

**Figure source:** `RealExchRatesBaltics.png`

Broad real exchange-rate indices, 2020=100. Source: BIS.

## Interest-rate differentials and exchange rates

### Interest rates and exchange rates: the intuition

Consider a small economy open to international financial flows.

If the return on domestic assets rises relative to the return on foreign assets:

- investors want to hold more domestic assets

- demand for the domestic currency increases

- the domestic currency appreciates

Hence a higher domestic interest rate relative to the foreign interest rate tends to raise both the nominal and, with sticky prices, the real exchange rate.

### A formal version: uncovered interest parity

A Swedish investor is indifferent between domestic and foreign one-period bonds when their expected returns are equal: 

$$
\label{eq:uip}
        1+i_t=(1+i_t^w)\frac{E_t}{E_{t+1}^e}
$$

In logarithms, approximately, 

$$
e_t=i_t-i_t^w+e_{t+1}^e
$$

 where $e_t \equiv \ln{E_t}$ and $e_{t+1}^e \equiv \ln{E_{t+1}^e}$.

If the expected future exchange rate is unchanged, a higher domestic interest rate produces an immediate appreciation.

### Interest rate parity

**Figure source:** `UIP.png`

### Interest rate parity: an increase in the foreign interest rate

**Figure source:** `UIP_shift.png`

### From nominal to real interest rates and exchange rates

In the short run, prices and expected inflation adjust slowly.

We therefore use the following transmission chain: 

$$
(i_t-i_t^w)\uparrow
        \quad\Longrightarrow\quad
        (r_t-r_t^w)\uparrow
        \quad\Longrightarrow\quad
        Q_t\uparrow
$$

The real appreciation makes domestic goods more expensive relative to foreign goods and reduces net exports.

This is the link that Jones incorporates directly into the open-economy IS curve.

## Exchange rates in the short-run model

### The IS curve from earlier lectures

Recall the IS curve: 

$$
\label{eq:is_closed}
        \widetilde{Y}_t=\alpha-\beta(r_t-\bar r),
$$

 where $\widetilde{Y}_t$ is the output gap and $\bar r$ is the natural real interest rate.

The central bank sets the nominal interest rate. With expected inflation unchanged, a higher nominal rate raises the real rate and reduces investment.

We now add a second channel: the nominal interest rate also affects the exchange rate and net exports.

### Two channels of monetary policy

Suppose that the central bank raises the nominal interest rate $i_t$. Hold the foreign interest rate and the expected future exchange rate unchanged.

**The interest-rate channel** 

$$
i_t\uparrow
        \ \Longrightarrow\ r_t=i_t-\pi^e_{t+1}\uparrow
        \ \Longrightarrow\ I_t\downarrow
$$

 With expected inflation unchanged, the real interest rate rises.

**The exchange-rate channel** 

$$
i_t-i_t^w\uparrow
        \ \overset{\mathrm{UIP}}{\Longrightarrow}\ E_t\uparrow
        \ \Longrightarrow\ Q_t\uparrow
        \ \Longrightarrow\ NX_t\downarrow
$$

 With domestic and foreign prices fixed, the nominal appreciation is also a real appreciation.

### Net exports in Jones’s model

In an open economy, 

$$
Y_t=C_t+I_t+G_t+NX_t
$$

Jones summarizes the exchange-rate channel with 

$$
\label{eq:nx}
        \frac{NX_t}{\bar Y_t}
        =\alpha_{NX}-\beta_{NX}(r_t-r_t^w),
        \qquad \beta_{NX}>0.
$$

With domestic and foreign inflation expectations unchanged, the nominal and real interest rate differentials move together.

This equation incorporates the exchange-rate channel directly into the IS curve.

### The open-economy IS curve

Combining consumption, investment, government spending and net exports gives 

$$
\label{eq:is_open}
        \widetilde{Y}_t=\alpha-\beta(r_t-\bar r),
$$

 where 

$$
\begin{aligned}
        \alpha
        &=\alpha_C+\alpha_G+\alpha_I+\alpha_{NX}-1
          +\beta_{NX}(r_t^w-\bar r)\\
        \beta&=\beta_I+\beta_{NX}
    
\end{aligned}
$$

The equation has the same form as before:

- $\beta$ now captures both the investment and net-export responses to interest rates.

- The foreign interest rate affects $\alpha$ and can therefore shift the IS curve.

### The open-economy IS–MP–PC model

The structure of the model is unchanged:

- **IS**: the output gap depends negatively on the domestic real interest rate

- **MP**: the central bank sets the nominal interest rate in response to inflation and economic activity

- **PC**: inflation depends on expected inflation, the output gap and cost shocks

Given expected inflation, the nominal policy rate determines the real interest rate entering the IS curve.

In the open economy, domestic monetary policy also works through the exchange rate, and foreign monetary policy can shift domestic aggregate demand.

### A foreign monetary-policy tightening

Suppose that the foreign central bank raises $i_t^w$, while the domestic central bank initially holds $i_t$ unchanged.

For the initial effects, again hold prices, inflation expectations and the expected future exchange rate unchanged.

$$
i_t^w\uparrow
        \ \Longrightarrow\ i_t-i_t^w\downarrow
        \ \overset{\mathrm{UIP}}{\Longrightarrow}\ E_t\downarrow
        \ \Longrightarrow\ Q_t\downarrow
        \ \Longrightarrow\ NX_t\uparrow
$$

With foreign inflation expectations unchanged, $r_t^w$ also rises. In equation (equation `eq:is_open`), this raises $\alpha$ and shifts the IS curve outward.

Before the domestic policy response, this is a **positive aggregate-demand shock** for the domestic economy.

### Foreign tightening and the domestic policy response

**Figure source:** `Figs/IS_shift.png`

The higher foreign interest rate shifts the IS curve outward. The domestic central bank can raise its policy rate to stabilize output.

### How should the domestic central bank respond?

Suppose that the domestic central bank wants to stabilize output after $i_t^w$ rises by $\Delta i_t^w$.

How much should it raise $i_t$?

- If it raises $i_t$ by exactly $\Delta i_t^w$, the interest rate differential is unchanged. Given the expected future exchange rate, UIP implies that $E_t$ is unchanged.

- With prices fixed, $Q_t$ and net exports are also unchanged. But the higher domestic real interest rate reduces investment, so output falls below potential.

- To stabilize output, it should therefore raise $i_t$ by **less** than $\Delta i_t^w$.

The smaller increase in $i_t$ balances two effects: 

$$
r_t\uparrow\ \Longrightarrow\ I_t\downarrow
        \qquad\text{and}\qquad
        E_t\downarrow\ \Longrightarrow\ Q_t\downarrow
        \ \Longrightarrow\ NX_t\uparrow
$$

### Foreign monetary policy in the AS–AD framework

Jones now considers the case in which domestic monetary policy does not fully offset the initial demand shock.

**Figure source:** `MACRO6_FIG20.05_box.jpg`

Source: Jones, Figure 20.5.

### Interpreting Figure 20.5

1.  The temporary increase in aggregate demand moves the economy from $A$ to $B$.

2.  Because output is above potential, inflation rises. As short-run aggregate supply shifts up, output returns to potential at $C$.

3.  When the foreign interest rate returns to normal, the demand shock is reversed. Subsequent adjustment brings the economy back toward $A$ through $D$.

### An additional inflation channel

In Jones’s benchmark, the exchange rate affects inflation through aggregate demand: 

$$
Q_t\downarrow \ \Longrightarrow\ NX_t\uparrow
        \ \Longrightarrow\ \widetilde{Y}_t\uparrow
        \ \Longrightarrow\ \pi_t\uparrow
$$

In practice, a depreciation can also raise inflation more directly:

- imported consumer goods become more expensive

- imported intermediate inputs raise firms’ costs

In our Phillips curve, this direct pass-through can be treated as a temporary cost shock, $\sigma_t>0$.

## Exchange-rate regimes and currency crises

### Fixed exchange rates

Under a credible fixed exchange rate, 

$$
E_t=E_{t+1}^e=\bar E.
$$

With free international financial flows, interest parity then implies 

$$
i_t=i_t^w.
$$

The domestic central bank must set its interest rate to maintain the peg. It cannot independently choose the interest rate needed to stabilize domestic output and inflation.

### The trilemma of international finance

**Figure source:** `MACRO6_FIG20.07_box.jpg`

Source: Jones, Figure 20.7.

### Three possible regimes

An economy can combine at most two of the following:

1.  a fixed exchange rate

2.  free international financial flows

3.  independent monetary policy

- Floating exchange rate $+$ free capital flows $\Rightarrow$ monetary-policy autonomy

- Fixed exchange rate $+$ free capital flows $\Rightarrow$ foreign monetary policy determines the domestic interest rate

- Fixed exchange rate $+$ monetary-policy autonomy $\Rightarrow$ capital controls

### Why fixed exchange rates can become costly

Suppose that domestic prices rise faster than foreign prices while the nominal exchange rate is fixed.

$$
Q=\bar E\frac{P}{P^w}\uparrow.
$$

- The real exchange rate appreciates and net exports fall.

- Restoring competitiveness requires lower domestic inflation, falling domestic prices or a devaluation.

- Price adjustment is slow, and the recession needed to generate it may be costly.

A **devaluation** lowers the fixed value of $E$; a revaluation raises it.

### The gold standard in the Great Depression

- The Depression began after the downturn in the United States in 1929 and spread internationally.

- France, Germany and Italy attempted to maintain their exchange rates against gold.

- The United Kingdom, Sweden and Denmark left gold and depreciated their currencies in 1931.

- Recovery generally began earlier in countries that abandoned the gold standard.

The fixed exchange rate transmitted contractionary monetary conditions across countries and constrained the policy response.

### The 1992 European currency crisis

- Most European currencies were effectively pegged to the German mark through the Exchange Rate Mechanism.

- German unification generated a domestic boom and inflationary pressure.

- The Bundesbank raised interest rates.

- Other European countries faced weak activity but had to raise interest rates to defend their pegs.

Foreign monetary policy was poorly suited to domestic conditions, exactly the tension highlighted by the trilemma.

### Sweden and Germany around the 1992 crisis

**Figure source:** `SE_DE_inflation.png`

**Figure source:** `SE_DE_growth.png`

**Figure source:** `SE_DE_unemp.png`

Inflation, GDP growth and unemployment. Source: IMF WEO.

### Loss of credibility makes the peg harder to defend

Interest parity can be written approximately as 

$$
i_t=i_t^w+e_t-e_{t+1}^e.
$$

If investors begin to expect a devaluation, $e_{t+1}^e$ falls. Maintaining the current value of $e_t$ then requires a higher domestic interest rate.

- The higher rate deepens the recession.

- A deeper recession may weaken confidence in the peg further.

- Expectations can therefore become partly self-fulfilling.

### The Swedish defense of the krona

**Figure source:** `Figs/Sweden1992.png`

### Swedish and German interest rates

**Figure source:** `SE_DE_5y.png`

**Figure source:** `SE_DE_5y_spread.png`

Five-year government bond yields and the Sweden–Germany spread. Source: Riksbank.

### The krona was allowed to float in November 1992

**Figure source:** `SEK_DEM_1992.png`

### Monetary union

A common currency removes the possibility of a nominal devaluation between member countries.

- This eliminates currency risk within the union.

- But a common monetary policy may be poorly suited to countries hit by different shocks.

- Adjustment must instead occur through inflation differentials, wages, migration or fiscal policy.

- The euro crisis showed that destabilizing risk-premium dynamics can arise even without national currencies.

### Summing up

- The nominal exchange rate is the relative price of currencies; the real exchange rate is the relative price of goods.

- PPP is a long-run benchmark. Nontradable goods help explain persistent price-level differences.

- Interest-rate differentials affect exchange rates and net exports.

- In the open-economy IS curve, monetary policy operates through both investment and the exchange rate.

- Foreign monetary policy can shift domestic aggregate demand.

- A fixed exchange rate with free financial flows limits domestic monetary-policy autonomy.
