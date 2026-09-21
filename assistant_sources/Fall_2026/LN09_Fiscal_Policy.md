# Lecture Notes 9: Fiscal Policy

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)

This is an agent-oriented rendering of `main_LN09.tex`. Frame headings follow the lecture source. Figure filenames and notes are retained when present; consult the lecture slides for the visual itself.


### Contents and literature

- Fiscal policy, the Keynesian cross and multipliers
- Automatic stabilizers and discretionary fiscal policy
- The government budget constraint and Ricardian equivalence
- Debt dynamics and fiscal sustainability
- The Swedish fiscal framework
- Interactions between fiscal and monetary policy

  Literature:
- Jones (2024), selected parts of Chapters 11 and 18

## Fiscal policy and aggregate demand

### Two questions about fiscal policy

A fiscal measure must be analyzed at more than one horizon.
Effects today
        How do government purchases, taxes and transfers affect aggregate
        demand, output, employment and inflation?
Financing over time
        How is the measure financed, and what does it imply for future taxes,
        expenditure, interest payments and debt?

  Expansionary fiscal policy can support demand today, but it also affects the
  room for future policy.

### Fiscal policy has several objectives

Fiscal policy comprises decisions about government expenditure, taxes and
  transfers.

  These decisions may aim to:
- provide public goods and correct market failures
- redistribute income and insure households against risks
- support long-run objectives such as infrastructure, defence or climate policy
- stabilize economic activity and inflation

  Our first focus is short-run stabilization. We then turn to financing and
  fiscal sustainability.

### Automatic and discretionary fiscal policy

Automatic stabilizers
        Taxes and transfers change automatically when income and unemployment
        change, without a new political decision.
Discretionary fiscal policy
        Policymakers actively change government purchases, tax rules or
        transfers in response to economic conditions.

  Examples of automatic stabilizers include income taxes and unemployment
  benefits. Examples of discretionary measures include temporary transfers,
  tax rebates and additional public investment.

## The Keynesian cross

### Planned expenditure and actual output

Start with a closed economy. At a given price level, let

$$E=C+I^p+G
    $$

  denote **planned expenditure**. Here $I^p$ is planned investment; it
  excludes unintended inventory changes.

  In the national income identity $Y=C+I+G$, actual investment includes
  unintended inventory changes.
- If $E<Y$, firms accumulate unwanted inventories and reduce production.
- If $E>Y$, inventories fall unexpectedly and firms raise production.

  In short-run goods-market equilibrium, planned expenditure equals output:

$$\boxed{Y=E}$$

### Consumption responds to current disposable income

Let $T$ denote net taxes: taxes minus transfers. Disposable income is $Y-T$.

  Extend the baseline consumption specification from LN6:

$$\boxed{
    C=\bar C+\mathrm{MPC}\times\big[(Y-T)-(\bar{Y}-\bar T)\big],
      0<\mathrm{MPC}<1}
    $$

  where $\bar C=\alpha_C\bar{Y}$ is consumption when disposable income is at its
  normal level.

- $\mathrm{MPC}$ is the **marginal propensity to consume** out of current
          disposable income.
- If disposable income rises by 100 units, consumption rises by
          $100\times\mathrm{MPC}$ units.
Note: Jones denotes the parameter corresponding to $\mathrm{MPC}$ by $\bar{x}$.

### How does this relate to LN5b?

In LN5b, a household that can smooth consumption across time spends only a
  small part of an unexpected temporary income gain.

  Here $\mathrm{MPC}$ captures how aggregate consumption changes when current income
  changes during an economic fluctuation.

- Some households cannot borrow freely or have little liquid wealth.
- Other households can smooth consumption and respond less to current income.
- The aggregate response depends on which households receive the income change.

  Equation \eqref{cons_func} is a simplifying aggregate relationship, not a
  consequence of the benchmark household model.

### Planned expenditure rises with output

Hold $I^p$, $G$, $T$ and potential output fixed. Substituting
  \eqref{cons_func} into \eqref{planned_exp} gives

$$E=\underbrace{\bar C+
      \mathrm{MPC}\times\big[(Y-T)-(\bar{Y}-\bar T)\big]}_{consumption}
      +I^p+G.$$

- The expenditure line has slope $\mathrm{MPC}$.
- When output and income rise by one unit, planned consumption and
          expenditure rise by $\mathrm{MPC}$ units.
- An increase in planned investment or government purchases shifts the
          expenditure line upward.

### The Keynesian cross

**Diagram:** See the original lecture slide for the constructed diagram.

  At $Y_0$, planned expenditure equals output. Away from the intersection,
  unintended inventory changes give firms a reason to adjust production.

### An increase in government purchases

**Diagram:** See the original lecture slide for the constructed diagram.

### An increase in government purchases

**Diagram:** See the original lecture slide for the constructed diagram.

  Higher $G$ raises expenditure directly. The resulting increase in income also
  raises consumption, so equilibrium output rises by more than $\Delta G$ in
  this simple model.

### Deriving the spending multiplier

Compare two goods-market equilibria and hold $\bar C$ fixed. Changes in
  consumption satisfy

$$\Delta C=\mathrm{MPC}\times(\Delta Y-\Delta T).$$

  Changes in equilibrium output therefore satisfy

$$\Delta Y
      =\mathrm{MPC}\times(\Delta Y-\Delta T)+\Delta I+\Delta G.$$

  Solving for $\Delta Y$ gives

$$\boxed{
    \Delta Y=
      \underbrace{\frac{1}{1-\mathrm{MPC}}}_{spending multiplier}
      \big(\Delta I+\Delta G-\mathrm{MPC}\times\Delta T\big).}$$

  At a fixed real interest rate and with unchanged taxes,
  $\Delta Y/\Delta G=1/(1-\mathrm{MPC})>1$.

### Why is the multiplier greater than one?

Suppose government purchases initially rise by 20 and $\mathrm{MPC}=0.4$.
- The initial increase in output and income is 20.
- Higher income raises consumption by $0.4\times20=8$.
- This raises income and consumption further, initially by
          $0.4\times8=3.2$, and so on.

$$\Delta Y=20(1+0.4+0.4^2+\cdots)
            =\frac{20}{1-0.4}\approx33.$$

  The successive rounds become smaller because $0<\mathrm{MPC}<1$. A higher MPC
  produces a larger multiplier in this simple model.

### Government purchases and taxes

At a fixed real interest rate, holding the other demand components fixed,

$$\boxed{
    \frac{\Delta Y}{\Delta G}=\frac{1}{1-\mathrm{MPC}},

    \frac{\Delta Y}{\Delta T}=-\frac{\mathrm{MPC}}{1-\mathrm{MPC}}}$$

- An increase in $G$ raises planned expenditure directly.
- A tax cut first raises disposable income. Households spend the
          fraction $\mathrm{MPC}$ of that increase and save the rest.
- The tax multiplier is therefore smaller in absolute value than the
          government-purchases multiplier in this model.

  Transfers work through household disposable income and their effect depends
  particularly strongly on who receives them.

### Income taxes act as an automatic stabilizer

Suppose net taxes respond automatically to income:

$$T-\bar T=\tau(Y-\bar{Y}),
      0<\tau<1.$$

  Then $\Delta T=\tau\Delta Y$, so a change in income produces

$$\Delta C
      =\mathrm{MPC}\times(1-\tau)\Delta Y.$$

  For a change in government purchases,

$$\boxed{
    \frac{\Delta Y}{\Delta G}
      =\frac{1}{1-\mathrm{MPC}\times(1-\tau)}}$$

  A higher $\tau$ weakens the feedback from output to disposable income and
  consumption. It therefore dampens both expansions and recessions.

### Imports are another leakage from the multiplier process

Suppose imports rise with domestic income:

$$\Delta IM=m\Delta Y,
      m>0.$$

  With income-dependent taxes and imports, the government-purchases multiplier is

$$\boxed{
    \frac{\Delta Y}{\Delta G}
      =\frac{1}{1-\mathrm{MPC}\times(1-\tau)+m}}$$

- Taxes reduce the increase in disposable income.
- Imports direct part of the increase in expenditure toward foreign output.
- Multipliers therefore tend to be smaller in more open economies, all
          else equal.

### From the Keynesian cross back to the IS curve

LN6 derived the baseline IS curve

$$\widetilde{Y}=\alpha-\beta(r-\bar r).$$

- Higher government purchases raise demand at a given real interest
          rate: $\alpha$ rises and IS shifts to the right.
- The Keynesian cross explains how consumption–income feedback can
          amplify this initial demand change.
- The cross holds the real interest rate fixed. In the IS–MP framework,
          monetary policy may respond to the fiscal expansion.

  If the central bank raises $r$, the economy moves up along the new IS curve
  and the output effect is reduced.

### The fiscal multiplier depends on monetary policy

The Keynesian cross holds the real interest rate fixed. In practice,
    the central bank may respond to the effects of fiscal policy.
Monetary policy accommodates
                If the real interest rate remains unchanged, the increase in
                demand is allowed to raise output and inflation.

                This may be appropriate when demand is weak and inflation is low,
                or when the policy rate is at its effective lower bound.
Monetary policy counteracts
                If the fiscal expansion raises inflationary pressure, the central
                bank may increase the real interest rate.

                Lower private consumption and investment then offset part of the
                increase in government demand.

### The simple multiplier is a benchmark

The Keynesian-cross formula assumes:
- fixed prices and wages
- spare productive capacity
- a fixed real interest rate
- a stable consumption response
- no reaction of expectations, risk premia or asset prices
- lump-sum taxes unless an income-dependent tax rule is added

  It explains a mechanism. It does not imply that an empirical fiscal
  multiplier must equal $1/(1-\mathrm{MPC})$.

### What determines the size of fiscal multipliers?

The output response to a fiscal measure is likely to be larger when
- there is substantial economic slack
- monetary policy accommodates the fiscal measure or is constrained by the
          effective lower bound
- spending falls on domestic goods and services
- recipients of transfers or tax cuts have high MPCs

  The output response is likely to be smaller when
- the economy is close to capacity and prices respond strongly
- monetary policy responds and counteracts the fiscal measure
- imports respond strongly
- households anticipate offsetting future taxes
- higher borrowing raises long-term interest rates or risk premia

### Estimating multipliers is difficult

Government expenditure and taxes normally respond to the economy.
- A recession may cause fiscal support.
- The same recession also reduces output.
- A simple correlation can therefore make expansionary policy appear
          contractionary.

  Researchers seek fiscal changes that were not themselves caused by current
  economic conditions, for example:
- unexpected policy announcements
- military buildups driven by geopolitical events
- institutional rules that allocate spending across regions

  Estimates differ across methods, countries, time periods and economic conditions.

## Stabilization in practice

### Automatic stabilizers

Automatic stabilizers mitigate fluctuations without requiring a new decision.
- In a recession, income-tax revenue falls as incomes fall.
- Unemployment rises and expenditure on unemployment benefits increases.
- The fiscal balance deteriorates, supporting household disposable income.
- The reverse happens in an expansion.

  Automatic stabilizers are timely and predictable. Their strength depends on
  the design of the tax and transfer systems.

### Discretionary stabilization policy

In a recession, policymakers can actively:
- raise public consumption or investment
- reduce tax rates or provide tax rebates
- increase transfers or unemployment benefits
- subsidize firms' employment or investment

  Potential difficulties include:
- decision, implementation and impact lags
- uncertainty about the output gap and the multiplier
- measures that are difficult to reverse when the economy recovers
- conflict with monetary policy or long-run debt objectives

### U.S. disposable income rose while output collapsed during the pandemic

**Figure source:** `dinc_gdp_US.png`

**Figure source:** `dinc_gdp_SE.png`

  Fiscal support stabilized disposable income in both countries. In the United
    States, however, disposable income rose sharply even as production collapsed.
    With domestic production restricted and imports disrupted, household purchasing
    power increased while the supply of goods and services contracted.

### Fiscal policy during the pandemic: a retrospective

- Restrictions and supply disruptions initially prevented many goods
          and services from being produced.
- Fiscal support protected households and firms and prevented a collapse
          in income and demand.
- Demand recovered rapidly while supply constraints persisted.
- Fiscal support therefore contributed both to the recovery and, in
          several countries, to subsequent inflation pressure.

  The relevant question is not simply whether the support raised demand. It is
  whether its size, composition and duration were appropriate given the
  changing balance between deficient demand and constrained supply.

### A potential tension after an adverse supply shock

An adverse supply shock raises inflation while reducing output and real
    household income.

- The central bank may tighten monetary policy to prevent the
              inflation increase from becoming persistent.

- The government may want to compensate households for their loss
              of purchasing power.

- Broad transfers or tax cuts sustain aggregate demand and may
              therefore add to inflationary pressure.

- Monetary policy may then have to tighten more, further reducing
              private consumption and investment.

    The tension reflects different objectives: monetary policy seeks to
    stabilize inflation and activity, while fiscal policy may also pursue
    distributional objectives.

## Financing and Ricardian equivalence

### A fiscal measure must be financed

An increase in government purchases or a tax cut can be financed by:
- higher taxes today
- lower expenditure elsewhere
- government borrowing today and future primary surpluses
- in extreme cases, default or inflationary financing

  The Keynesian cross describes the short-run demand response under simple
  assumptions.

  The financing of the measure can change household expectations,
  interest rates and the size of that response.

### The government's two-period budget constraint

Let $B_1$ be debt entering period 1 and suppose the government ends period 2
  without debt. Its intertemporal budget constraint is

$$T_1+\frac{T_2}{1+i_2}
      =G_1+\frac{G_2}{1+i_2}+(1+i_1)B_1
    $$

  The present value of net tax revenue must equal
- the present value of government purchases, plus
- repayment of the initial debt with interest.

  Borrowing changes the timing of taxes. It does not remove the government's
  financing requirement.

### Ricardian equivalence

Recall the household's two-period budget constraint from LN5b:

$$C_1+\frac{C_2}{1+i_2}
      =Y_1-T_1+\frac{Y_2-T_2}{1+i_2}$$

  Suppose initially that $B_1=0$. Use the government's budget constraint to
  substitute for the present value of taxes:

$$\boxed{
    C_1+\frac{C_2}{1+i_2}
      =Y_1+\frac{Y_2}{1+i_2}
       -\left(G_1+\frac{G_2}{1+i_2}\right)}$$

  The timing of lump-sum taxes then does not affect the household's lifetime
  resources. A tax cut financed by debt does not by itself raise consumption.

### The effects of a debt-financed tax cut

Consider a tax cut of $\Delta T_1$ in period 1, with government purchases unchanged.

  The period-1 tax cut requires a period-2 tax increase of
  $(1+i_2)\Delta T_1$. Its present value is

$$\frac{(1+i_2)\Delta T_1}{1+i_2}=\Delta T_1.$$

  Under Ricardian equivalence, households save the entire tax cut to pay the
  future tax increase. The tax cut does not affect aggregate demand.

  This contrasts with the Keynesian-cross assumption that consumption responds
  to current disposable income.

### Why Ricardian equivalence may fail

The Ricardian result builds on strong assumptions:
- households are forward looking and understand the government budget constraint
- taxes are lump sum and future taxes are anticipated
- households can borrow and save freely
- households care about taxes falling on future generations
- the tax change does not alter government purchases
- taxes do not distort labor supply, investment or other choices

  Credit-constrained households may have a high MPC out of a current tax cut or
  transfer even if other households behave approximately as in the Ricardian model.

### Temporary and permanent increases in government purchases

Even under Ricardian equivalence, changes in government purchases can
  affect aggregate demand.
Temporary increase
        The present value of government purchases and future taxes rises
        relatively little. Consumption falls, but the loss of lifetime
        resources is spread across consumption in many periods. Current
        aggregate demand is likely to rise.
Permanent increase
        The present value of government purchases and future taxes rises much
        more. Consumption therefore falls by more and may offset most or all
        of the increase in government purchases.

  The effect comes from the change in government purchases, not from debt
  financing or the timing of taxes. It also depends on what the government
  purchases.

## Government debt

### U.S. federal government spending and revenue

**Figure source:** `MACRO6_FIG18.01.jpg`
Source: Jones (2024), Figure 18.1.

### The U.S. fiscal outlook in 2026

In the Congressional Budget Office baseline:
- the federal deficit is projected at \$1.9 trillion, or 5.8 percent of
          GDP, in fiscal year 2026
- debt held by the public rises from 101 percent of GDP in 2026 to
          120 percent in 2036
- the deficit reaches 6.7 percent of GDP in 2036
- rising net interest costs account for much of the increase

  These are large deficits even though the economy is not projected to be in a
  deep recession. The problem is therefore mainly structural rather than a
  consequence of automatic stabilizers.

  { Source: Congressional Budget Office,
  [*The Budget and Economic Outlook: 2026 to 2036*](https://www.cbo.gov/publication/61882), February 2026.}

### Gross debt ratios differ greatly across countries

**Figure source:** `GrossDebt.png`

  { Gross general government debt as a percentage of GDP. Source: IMF WEO.
  The latest observation in this figure is 2024.}

### Net debt is lower in some countries

**Figure source:** `NetDebt.png`

  Net debt subtracts financial assets from gross debt. The difference is large
  for countries with substantial public financial assets.
Source: IMF WEO. The latest observation in this figure is 2024.

### Some questions

- Can a government run a budget deficit forever?
- When does a rising debt ratio become unsustainable?
- How do economic growth and interest rates affect the answer?
- Can high debt itself raise the interest rate?
- How does debt constrain fiscal and monetary policy during a crisis?

  There is no universal debt threshold at which a government suddenly becomes
  insolvent. Sustainability depends on future primary balances, growth,
  interest rates, institutions, the currency denomination of debt and investor confidence.

## The government budget constraint

### Notation for the government budget

- $B_t$: nominal government debt entering period $t$
- $Y_t$: nominal GDP
- $i_t$: average nominal interest rate paid on the debt
- $g_t$: growth rate of nominal GDP
- $T_t$: net tax revenue, including taxes minus transfers
- $G_t$: government purchases, excluding interest and transfers
- $S_t^P$: primary surplus
- $S_t$: total fiscal surplus, or net lending

  Small letters will denote ratios to GDP: $b_t=B_t/Y_t$ and
  $s_t^P=S_t^P/Y_t$.

### The government's per-period budget constraint

Government uses of funds equal its sources of funds:

$$\boxed{G_t+(1+i_t)B_t=T_t+B_{t+1}}
    $$

- The left-hand side contains government purchases and repayment of
          existing debt with interest.
- The right-hand side contains net tax revenue and newly issued debt.

  Define the primary and total surpluses as

$$S_t^P=T_t-G_t,

    S_t=T_t-G_t-i_tB_t$$

  Hence $S_t=S_t^P-i_tB_t$.

### Debt dynamics in levels

Rearranging the per-period budget constraint gives

$$\boxed{B_{t+1}=(1+i_t)B_t-S_t^P}
    $$

- Interest increases the debt that must be financed.
- A primary surplus reduces debt.
- A primary deficit adds to debt before interest is taken into account.

  In terms of the total surplus,

$$B_{t+1}-B_t=-S_t$$

  A total deficit therefore increases nominal debt one for one in this
  stripped-down accounting framework.

### Debt dynamics relative to GDP

Nominal GDP evolves according to $Y_{t+1}=(1+g_t)Y_t$. Divide
  \eqref{GBC_level} by $Y_t$:

$$\boxed{(1+g_t)b_{t+1}=(1+i_t)b_t-s_t^P}$$

  For moderate interest and growth rates, this can be approximated by

$$\boxed{
    b_{t+1}-b_t\approx(i_t-g_t)b_t-s_t^P}
    $$

  The debt ratio tends to rise when the interest rate is high, nominal GDP
  growth is low, the initial debt ratio is high or the primary balance is weak.

### Stabilizing the debt ratio

If the debt ratio is constant, $b_{t+1}=b_t=b$, the exact debt equation gives

$$\boxed{s^P=(i-g)b}$$

  Example:
- debt ratio: $b=100$ percent
- average nominal interest rate: $i=5$ percent
- nominal GDP growth: $g=3$ percent
  The primary surplus required to stabilize the debt ratio is

$$s^P=(0.05-0.03)\times1=0.02,$$

  or 2 percent of GDP.

### Can a government run a deficit forever?

Yes, a government can run a *total* deficit forever while maintaining a
  positive and stable debt ratio.

  From $B_{t+1}-B_t=-S_t$, a stable debt ratio with nominal GDP growth $g>0$
  requires

$$\boxed{s=-gb}$$

  The nominal debt then grows at the same rate as nominal GDP.

  But if $i>g$, a government with positive debt cannot run a permanent primary
  deficit while keeping the debt ratio stable. It then needs a primary surplus,

$$s^P=(i-g)b>0$$

### What if growth exceeds the interest rate?

If $g\geq i$, the debt ratio can be stable even without a primary surplus.

  This does not make debt costless or remove all limits on borrowing:
- future growth and interest rates are uncertain
- the marginal interest rate may rise when debt increases
- persistent deficits may crowd out private capital or raise inflation
- refinancing needs can create risks before an accounting limit is reached

  The comparison between $i$ and $g$ is an important input into sustainability
  analysis, not a complete sustainability test.

### Long-term government bond yields rose sharply in 2026

Global bond sell-off, September 2026
    The U.S. ten-year Treasury yield briefly exceeded 5 percent, its highest
    level since 2007. Long-term yields also reached multiyear highs in Germany,
    the United Kingdom and several other advanced economies.

  Factors currently emphasized include
- persistent inflation and renewed energy-price pressure, raising
          expected future policy rates
- greater uncertainty about inflation and interest rates, raising
          term premia
- large government deficits and heavy issuance of government bonds
- unusually large corporate borrowing, partly to finance AI and
          data-center investment
- concerns about fiscal trajectories and demand for government bonds

  { See
  [*Wall Street Journal*, September 16, 2026](https://www.wsj.com/finance/investing/u-s-10-year-treasury-yield-rises-to-highest-since-2007-91d1e44f), and
  [Reuters, September 2, 2026](https://www.reuters.com/business/finance/whats-behind-selloff-world-bond-markets-2026-09-01/).}

### Market yields and the government's interest bill

The yield on a newly issued bond is not the same as the average interest rate
  paid on the existing debt stock.

- Existing fixed-rate debt retains its coupon until it matures.
- Higher market yields raise interest expenditure gradually as debt is
          refinanced.
- The adjustment is faster when debt has a short average maturity or a
          large share is indexed to short rates or inflation.

  Expectations matter immediately, however: anticipated future interest costs
  can affect current bond prices, fiscal plans and confidence in debt sustainability.

### Vicious circles and doom loops

Recall that stabilizing the debt ratio requires

$$s^P=(i-g)b.$$

- Higher interest rates increase the primary surplus required to
          stabilize debt.
- Fiscal consolidation may reduce aggregate demand and growth in the
          short run.
- Lower growth makes the debt dynamics less favorable.
- Doubts about fiscal sustainability may raise risk premia and interest
          rates further.

  These feedbacks are more dangerous when debt and refinancing needs are already
  high, growth is weak, banks hold large quantities of domestic government debt
  or the government borrows in a currency it cannot issue.

### Why high debt can be costly before a crisis

High debt may:
- raise interest expenditure and displace other public expenditure
- reduce the room for fiscal support in a future recession or emergency
- increase exposure to interest-rate and refinancing risk
- crowd out private investment if it raises real interest rates
- create uncertainty about future taxes and public services, potentially discouraging investment today
- increase the temptation to use inflation to reduce the real value of debt

  These costs depend on the use of borrowed funds. Debt-financed investment that
  raises future productive capacity is different from borrowing that leaves no
  future assets or revenue.

## Debt, inflation and monetary policy

### What if primary surpluses cannot stabilize the debt?

There are several possible outcomes:
- explicit default or restructuring
- fiscal adjustment through higher taxes or lower expenditure
- financial repression that holds government borrowing costs down
- monetary financing or pressure for more expansionary monetary policy
- an increase in the price level that reduces the real value of nominal debt

  Expectations of these outcomes can affect inflation and interest rates before
  any formal default or monetary financing occurs.

### Fiscal limits and inflation

Primary surpluses cannot be increased without limit.
- High tax rates distort economic decisions and may reduce the tax base.
- Very low public expenditure may be economically and politically unacceptable.
- Large primary surpluses are difficult to sustain for many years.

  If the public believes that future fiscal policy will not stabilize debt, the
  expected adjustment may instead occur through default or the price level.

  Fiscal sustainability is therefore important for a monetary policy aimed at
  low and stable inflation.

### From a rate peg to the Treasury–Fed Accord

- During World War II, the Federal Reserve committed to holding yields
            on U.S. government debt low.
- The rate peg continued after the war even as inflation rose.
- The 1951 Treasury–Fed Accord separated monetary policy from
            government debt management.
- The agreement became an important foundation for Federal Reserve independence.

**Figure source:** `TreasuryFedAccord.png`
Source: [Federal Reserve History](https://www.federalreservehistory.org/essays/treasury-fed-accord).

### Fiscal pressure and central-bank independence

Governments may prefer lower interest rates because they:
- stimulate demand and employment in the short run
- reduce the government's debt-service costs
- may reduce the real value of nominal debt through higher inflation

  If monetary policy becomes subordinated to the government's financing needs,
  the economy is said to face **fiscal dominance**.

  LN8 discussed current political pressure on the Federal Reserve. High public
  debt strengthens the fiscal incentive behind such pressure, but political
  criticism alone does not establish that monetary policy is fiscally dominated.

### Monetary financing in the European Union

The EU treaty prohibits central banks from providing direct credit to
  governments or purchasing government debt directly from them.

  The distinction between monetary and fiscal policy can nevertheless become
  difficult in practice:
- central banks can purchase government bonds in secondary markets
- asset purchases affect government borrowing costs and the allocation of risk
- central-bank profits and losses affect transfers to the government
- financial stability may require intervention in government bond markets

  These issues connect to the discussion of QE in LN8.

## The Swedish fiscal framework

### The Swedish fiscal-policy framework

The framework includes
- a target for general government net lending over the business cycle
- a debt anchor for Maastricht debt
- a central-government expenditure ceiling
- a balanced-budget requirement for municipalities and regions
- a top-down central-government budget process
- external evaluation by the Swedish Fiscal Policy Council

  The purpose is to combine long-run sustainability with room for fiscal policy
  to respond to economic fluctuations and exceptional events.

### From a surplus target to a balance target

- Through 2026, the target for general government net lending is a
          surplus of one-third of a percent of GDP on average over the business cycle.
- From 2027, the target is balance over the business cycle.
- The debt anchor remains 35 percent of GDP for consolidated general
          government gross debt.
- Temporary deviations are allowed, but the government must explain
          the deviation and the path back toward the target.
See chapter 2 in  [Swedish Fiscal Policy Council (2026)](https://www.fpr.se/download/18.4ccc669119c47c5351b11345/1770968668135/Svensk%20finanspolitik%202026.pdf), in Swedish but there is an English summary.

### What would a permanent balance target imply in the simple model?

Recall that the total surplus satisfies

$$B_{t+1}-B_t=-S_t.$$

  If $S_t=0$ every period, nominal debt is constant. With positive nominal GDP
  growth, the debt ratio then gradually falls:

$$\frac{B}{Y_t}\longrightarrow0.$$

  This is a result from the stripped-down model, not a literal forecast for
  Swedish Maastricht debt:
- the balance target applies on average over the business cycle
- gross debt and net lending are connected by asset transactions and
          other stock–flow adjustments
- the target is reviewed periodically and complemented by the debt anchor

### Rules and stabilization must coexist

Fiscal rules can:
- restrain incentives to postpone difficult financing decisions
- protect fiscal space for future crises
- make policy more predictable and transparent

  But rules that force immediate consolidation in a recession can destabilize
  the economy.

  A well-designed framework therefore:
- allows automatic stabilizers to operate
- permits justified temporary deviations
- requires transparent medium-term plans
- distinguishes cyclical deficits from persistent structural deficits

## Conclusions

### Main lessons

- The Keynesian cross shows how income-induced consumption can amplify
          an initial change in demand.
- Taxes, imports, monetary policy and supply constraints reduce or alter
          the simple multiplier.
- Automatic stabilizers support demand without new political decisions.
- Deficits change the timing of financing; they do not remove the
          government's intertemporal budget constraint.
- Debt dynamics depend centrally on the primary balance, the interest
          rate, GDP growth and the initial debt ratio.
- High debt can reduce fiscal space and create pressure on monetary policy
          well before an outright debt crisis.

### Two horizons, one policy decision

Short run
        Is demand too weak or too strong? Who receives the measure? How will the
        central bank and prices respond?
Long run
        Does the measure raise future productive capacity? How will it be
        financed? Is the resulting debt path robust to adverse shocks?

  Sound fiscal analysis requires both perspectives. A measure can be effective
  stabilization policy and still require a credible long-run financing plan.

### Appendix: the intertemporal budget constraint

Iterating the per-period budget constraint forward gives

$$\sum_{t=1}^{\infty}\frac{T_t}{(1+i)^{t-1}}
      =\sum_{t=1}^{\infty}\frac{G_t}{(1+i)^{t-1}}
       +(1+i)B_1,$$

  when the interest rate is constant and debt satisfies the appropriate
  no-Ponzi condition.

  The condition does not require nominal debt to become zero at a particular
  date. It requires the present value of debt in the distant future to vanish.

  Debt may therefore remain positive or even grow over time, provided it does
  not grow too rapidly relative to the discount factor and future primary surpluses.

### Appendix: debt dynamics using the total balance

Since $S_t=S_t^P-i_tB_t$, the debt equation can also be written as

$$B_{t+1}-B_t=-S_t.$$

  Divide by nominal GDP and impose a constant debt ratio:

$$\boxed{s=-gb.}$$

  Example: if $b=50$ percent and nominal GDP grows at 3 percent per year, a
  total deficit of 1.5 percent of GDP is consistent with a stable debt ratio.

  This is compatible with a primary surplus when interest expenditure exceeds
  the total deficit.
