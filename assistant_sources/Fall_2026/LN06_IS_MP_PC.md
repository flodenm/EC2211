# Lecture Notes 6: IS–MP–PC

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)

This is an agent-oriented rendering of `main_LN06.tex`. Frame headings follow the lecture source. Figure filenames and notes are retained when present; consult the lecture slides for the visual itself.


## From recent events to a short-run model

### A recurring macroeconomic problem

After the pandemic, inflation rose sharply in many countries.
  Central banks responded by raising policy rates.

  Inflation subsequently declined, while the effects on production and
  employment differed across countries and over time.

  This raises three questions:
- How can a higher interest rate reduce spending and output?
- How does economic activity affect inflation?
- Why can stabilizing inflation come at the cost of weaker activity?

### Inflation and the policy rate in Sweden

Inflation rose sharply after the pandemic. The Riksbank subsequently
  raised its policy rate, and inflation later declined.

  This sequence does not by itself establish causality. Our model will help
  us organize the different shocks and transmission mechanisms involved.

**Figure source:** `Inflation_PolicyRate_SE.pdf`

 CPIF inflation, annual percentage change, and the Riksbank's
  policy rate, percent. Sources: Statistics Sweden and Sveriges Riksbank.

### Inflation and the price level

Let $P_t$ denote the aggregate price level. The inflation rate is
  the percentage change in the price level:

$$\boxed{\pi_t=100\times\frac{P_t-P_{t-1}}{P_{t-1}}}$$

- Inflation is an increase in the general price level, not an
          increase in the price of one particular good
- Lower inflation means that prices increase more slowly; it does
          not normally mean that the price level falls
- Expected inflation, $\pi_t^e$, is the inflation rate expected
          before prices, wages and interest rates are set

  In Sweden, monetary policy targets annual CPIF inflation of 2 percent.
  We return later to inflation measurement, inflation targets and the
  costs of inflation.

### Measuring consumer prices in Sweden

Different price indices answer somewhat different questions.

- **CPI** measures the prices of goods and services consumed by
          households. Its treatment of owner-occupied housing implies that
          higher mortgage rates raise measured CPI inflation.

- **CPIF** holds mortgage rates fixed. It therefore removes the
          direct effect of policy-rate changes on measured housing costs.
          The Riksbank's inflation target is 2 percent annual CPIF inflation.

- **CPIF excluding energy** removes energy prices, which can move
          sharply in the short run. It is one measure of *core inflation*
          used to assess broader inflationary pressure.

  No single measure perfectly captures ``underlying'' inflation.

### A model for organizing the discussion

We will combine three relationships:
1. **IS**: the real interest rate affects demand and the output gap
2. **MP**: monetary policy determines the real interest rate in this first version
3. **PC**: economic activity affects inflation

  The model is deliberately simple. Its purpose is to identify mechanisms
  before we add monetary-policy rules, financial markets, fiscal policy,
  and the open economy.

### The route through the textbook

- Inflation is discussed in chapter 8.
- The output gap follows chapter 9.
- The IS curve follows the baseline derivation in Chapter 11.
- The MP line and the Phillips curve follow Chapter 12.
- Read the selected parts of Chapters 9, 11, and 12 alongside these notes.

  Jones later allows consumption to respond to current income. That creates
  multiplier effects. We postpone that extension until we study fiscal policy.

  Recommended extra reading: Buiter and Rahbari (2015), [What is a (global) recession?](https://ir.citi.com/p%2FJ9Uj80%2BaxALKreeY0Z1vUZImlOZOLlB6g4Rv8kllN5sDCBZyPvGe3ti1Rfq%2BSM)

## Fluctuations around potential output

### Actual and potential output

**Figure source:** `MACRO6_FIG09.01.jpg`

  The output gap measures the deviation of actual output from potential output.
  Panel (b) expresses this deviation as a percentage of potential output.

  Jones calls $\tilde{Y}$ "short-run output". We use the standard term "output gap".
Jones (2024), Figure 9.1.

### Potential output and the output gap

**Potential output**, $\bar{Y}_t$, is the level of output consistent with
  normal utilization of labor and other productive resources.

  The **output gap** measures actual output relative to potential output:

$$\boxed{\widetilde{Y}_t\equiv\frac{Y_t-\bar{Y}_t}{\bar{Y}_t}
      =\frac{Y_t}{\bar{Y}_t}-1.}$$

- $\widetilde{Y}_t<0$: output is below potential
- $\widetilde{Y}_t>0$: output is above potential

  A gap of $0.02$ means that output is 2 percent above potential.

### The U.S. output gap and recessions

Output gap, percent of potential output
**Figure source:** `MACRO6_FIG09.03.jpg`

  Large negative output gaps tend to coincide with recessions.
  Potential output must be estimated and is therefore uncertain.

  { Jones (2024), Figure 9.3. Data from FRED and the
  Congressional Budget Office. Recession dates from the NBER.}

### Why can output differ from potential?

Over short horizons, many prices and wages adjust slowly.

  Firms may therefore respond to changes in demand by changing production
  and employment rather than immediately changing all prices.

- Weak demand can leave productive resources underutilized.
- Strong demand can push production temporarily above normal capacity.
- Persistent gaps eventually affect wages, prices, and inflation.

  The IS curve describes demand and output at different real interest rates.

## The IS curve

### Start from aggregate expenditure

The national income identity is

$$Y=C+I+G+EX-IM$$

  Divide by potential output:

$$\frac{Y}{\bar{Y}}
      =\frac{C}{\bar{Y}}+\frac{I}{\bar{Y}}+\frac{G}{\bar{Y}}
       +\frac{EX}{\bar{Y}}-\frac{IM}{\bar{Y}}$$

  In the short-run model, firms meet demand at the prevailing prices.
  The right-hand side therefore determines short-run production.

  We begin by asking how the components of demand depend on the real interest rate.

### A deliberately simple starting point

Following Jones, suppose initially that consumption, government purchases,
  exports, and imports are fixed fractions of potential output:

$$\frac{C}{\bar{Y}}=\alpha_C
    \frac{G}{\bar{Y}}=\alpha_G
    \frac{EX}{\bar{Y}}=\alpha_{EX}
    \frac{IM}{\bar{Y}}=\alpha_{IM}$$

  These assumptions do not claim that the components are always constant.
  They establish a baseline in which investment provides the direct link
  between the real interest rate and demand.

  Later, changes in these demand components will shift the IS curve.

  { Jones denotes the corresponding parameters by
  $\bar a_c$, $\bar a_g$, $\bar a_{ex}$, and $\bar a_{im}$.}

### Investment and the real interest rate

Recall the investment decision from Lecture Notes 5b: a higher financing cost makes
  fewer investment projects profitable.

  Represent this mechanism as

$$\boxed{\frac{I}{\bar{Y}}=\alpha_I-\beta(r-\bar r),
        \beta>0 }$$

- $\alpha_I$: investment relative to potential at the normal real rate
- $\bar r$: the normal real interest rate
- $\beta$: the sensitivity of investment to the real rate

  Optimism, expected profitability, or easier access to credit can raise
  investment at any given $r$ and are captured by an increase in $\alpha_I$.
Jones denotes $\alpha_I$, $\beta$ and $r$ by $\bar a_i$, $\bar b$ and $R$.

### Deriving the IS curve

Substitute the demand components into the expenditure identity:

$$\frac{Y}{\bar{Y}}
      =\alpha_C+\alpha_I-\beta(r-\bar r)
       +\alpha_G+\alpha_{EX}-\alpha_{IM}$$

  Because $\widetilde{Y}=Y/\bar{Y}-1$, this becomes

$$\boxed{\widetilde{Y}=\alpha-\beta(r-\bar r),}$$

  where

$$\alpha\equiv
      \alpha_C+\alpha_I+\alpha_G+\alpha_{EX}-\alpha_{IM}-1$$

  This negative relationship between the real interest rate and the output gap
  is the **IS curve**.

### The economic mechanism behind IS

Consider an increase in the real interest rate, holding the other demand
  determinants fixed:

$$\Delta\widetilde{Y}=-\beta \Delta r$$

1. A higher real rate raises the financing cost of investment.
2. Firms undertake fewer investment projects.
3. Aggregate demand falls.
4. With sticky prices, firms reduce production and employment.

  Consumption may also respond directly to interest rates, but the investment response is
  sufficient for the basic IS mechanism.

### The IS curve in $(\widetilde{Y},r)$ space

**Diagram:** See the original lecture slide for the constructed diagram.

 A lower real rate raises investment and the output gap:
  the economy moves down along the IS curve.

### Movements along IS and shifts of IS

Movement along IS
        A change in $r$ changes investment and the output gap, holding
        $\alpha$ fixed
Shift of IS
        A change in demand at a given $r$ changes $\alpha$ and shifts the
        entire IS curve

  IS shifts to the right when, for example,
- households become more willing to consume,
- firms become more optimistic about future profitability,
- government purchases or exports increase, or
- imports decrease at a given level of domestic activity.

### What the baseline IS curve leaves out

The baseline takes consumption as fixed relative to potential output.

  If higher income induces additional consumption, an initial demand change
  can be amplified through a **multiplier mechanism**. Taxes and imports
  affect the strength of that feedback.

  We return to these mechanisms, and to the Keynesian cross, when we study
  fiscal policy. They enrich the IS curve but are not needed to understand
  why it slopes down.

## The monetary-policy line

### Nominal and real interest rates: the Fisher equation

The central bank sets a short-term **nominal policy rate**, $i_t$.

  The **Fisher equation** relates the nominal interest rate to
  the ex ante real interest rate:

$$\boxed{r_t\approx i_t-\pi^e_t}$$

  where $\pi^e_t$ is expected inflation over the relevant period.

  If expected inflation is given within the period, a one-percentage-point
  increase in the nominal rate raises the real rate by approximately one
  percentage point.

  The lending rates facing households and firms need not move one for one
  with the policy rate. We return to monetary transmission later.

### The MP line

For now, suppose that the central bank chooses the real interest rate
  $r^{MP}$, given expected inflation:

$$\boxed{r=r^{MP}}$$

  In a diagram with the output gap on the horizontal axis and the real rate
  on the vertical axis, this is a **horizontal line**.

  We examine how central banks implement policy and how they respond systematically to the
  economy in later lectures.

### IS and MP determine the output gap

**Diagram:** See the original lecture slide for the constructed diagram.

 The central bank chooses the real rate. The IS curve then tells
  us the output gap consistent with aggregate demand.

### Monetary tightening

Suppose the central bank raises the policy rate and expected inflation
  does not change immediately.
1. The real interest rate rises: the MP line shifts up.
2. Investment falls: the economy moves up along the IS curve.
3. The output gap declines.

  Monetary policy affects activity with delays in reality. Our one-period
  model compresses this adjustment into a movement from one equilibrium
  to another.

## The Phillips curve

### From the output gap to inflation

IS and MP determine the output gap. How does activity affect inflation?

  When output is high relative to potential,
- labor and productive capacity are used intensively,
- wages and other production costs tend to face upward pressure, and
- firms find it easier to raise prices.

  Weak activity tends to reduce these pressures. Inflation also depends on
  expectations and on disturbances that affect firms' costs directly.

### The Phillips curve

A simple Phillips curve is

$$\boxed{\pi_t=\pi^e_t+\kappa\widetilde{Y}_t+\sigma_t,
        \kappa>0}$$

- $\pi_t$: inflation during period $t$
- $\pi^e_t$: inflation expected when relevant prices and wages were set
- $\widetilde{Y}_t$: the output gap
- $\sigma_t$: a price or cost shock

  A positive output gap raises inflation *relative to expected inflation*,
  holding the cost shock fixed.

### Inflation dynamics

Suppose expected inflation equals inflation in the previous period:

$$\pi^e_t=\pi_{t-1}$$

  The Phillips curve then becomes

$$\boxed{\pi_t-\pi_{t-1}=\kappa\widetilde{Y}_t+\sigma_t}$$

- A positive gap tends to make inflation rise.
- A negative gap tends to make inflation fall.
- A positive cost shock can raise inflation even when output is below potential.

  Expectations need not always be backward-looking. Their formation becomes
  important for monetary policy.

## Putting the model together

### The IS–MP–PC framework

$$IS:
      &\widetilde{Y}_t=\alpha_t-\beta(r_t-\bar r)\\[0.5em]
    MP:
      &r_t=i_t-\pi^e_t=r^{MP}_t\\[0.5em]
    PC:
      &\pi_t=\pi^e_t+\kappa\widetilde{Y}_t+\sigma_t$$

  Within a period, take potential output, expected inflation, and the demand
  and cost shocks as given.
1. IS and MP determine the output gap.
2. The Phillips curve then determines inflation.

### A positive aggregate-demand shock

Suppose households or firms become more optimistic, so $\alpha_t$ rises.
  If the central bank initially holds the real rate fixed:
1. IS shifts to the right.
2. The output gap increases.
3. Inflation rises relative to expectations.

  If the central bank instead raises the real rate, the MP line shifts up.
  The economy moves up along the new IS curve and the increase in activity
  is smaller.

### A cost shock creates a policy dilemma

Suppose energy or other input costs rise unexpectedly: $\sigma_t>0$.
- Inflation rises at any given output gap.
- Raising the real rate reduces demand and inflationary pressure.
- But the weaker demand also pushes output further below potential.

  This captures one difficulty faced by central banks after large supply
  disturbances: stabilizing inflation and stabilizing activity may point
  toward different interest-rate decisions.

  The model does not tell the central bank how strongly to respond. We add
  a monetary-policy rule in LN7.

### What this first version leaves for later

- How do monetary-policy decisions respond systematically to inflation and activity? *Taylor rules and AS–AD.*
- How do policy rates affect lending rates, credit, and expectations? *Monetary transmission and financial markets.*
- What determines the money stock, and what does a central bank actually do? *Money and banking.*
- How do taxes, transfers and government spending affect economic activity? *Fiscal policy.*
- How does the analysis change in a small economy open to international trade? *Exchange rates and international finance.*

### Check your understanding

Consider each change separately.
1. Firms become more optimistic about future demand. Which curve shifts,
          and what happens if the real rate is unchanged?
2. The central bank raises the nominal policy rate while expected
          inflation is unchanged. How does the economy move in the IS–MP diagram?
3. Energy prices rise unexpectedly. Which equation changes directly,
          and what tradeoff does the central bank face?

### The main mechanisms

- **Output gap**: actual output can deviate from potential in the short run
- **IS**: a higher real rate reduces investment, demand and output
- **MP**: given expected inflation, the policy rate helps determine the real rate
- **PC**: stronger activity raises inflation relative to expectations
- **Policy dilemma**: a cost shock can raise inflation while weakening activity

  Next: monetary-policy reactions, inflation dynamics, and the AS–AD framework.
