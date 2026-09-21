# Lecture Notes 8: Money and Monetary Policy

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)

This is an agent-oriented rendering of `main_LN08.tex`. Frame headings follow the lecture source. Figure filenames and notes are retained when present; consult the lecture slides for the visual itself.


### Contents and literature

- Interpreting shocks with the IS–MP–PC and AS–AD models
- The transmission of monetary policy
- Banks, risk premia and financial crises
- Quantitative easing and central-bank balance sheets
- Money, Bitcoin and stablecoins
- Expectations, communication and central-bank independence

  Literature:

- Jones (2024), chapters 10 and 14
- McLeay, Radia and Thomas (2014),
      [``Money in the modern economy: an introduction''](https://www.bankofengland.co.uk/-/media/boe/files/quarterly-bulletin/2014/money-in-the-modern-economy-an-introduction.pdf)
- Royal Academy of Sciences (2022),
      [``The central role of banks in financial crises''](https://www.nobelprize.org/uploads/2022/10/popular-economicsciencesprize2022-2.pdf)

### Today

Today we use the IS-MP-PC and AS-AD models to organize several practical questions:

- What kind of shock has hit the economy?
- How does a change in the policy rate reach households and firms?
- What happens when banks or financial markets disrupt transmission?
- What can central banks do when short-term rates are constrained?
- Why do expectations, communication and institutions matter?

  The objective is interpretation rather than further model building.

## Interpreting shocks

### Demand shocks and cost shocks

Recall the two central equations from LN6–LN7:

$$AD:
      &\widetilde{Y}_t=\alpha_t-\beta\mu(\pi_t-\pi^*)\\[0.4em]
    AS:
      &\pi_t=\pi_t^e+\kappa\widetilde{Y}_t+\sigma_t$$
Positive demand shock
        $\alpha_t$ rises. Inflation and the output gap tend to rise together.
Adverse cost shock
        $\sigma_t$ rises. Inflation rises while the output gap tends to fall.

### The post-pandemic episode contained several shocks

The model distinguishes demand from cost shocks. Actual episodes need not
  fit neatly into one category.

- Pandemic restrictions disrupted production and international supply chains.
- Fiscal and monetary support sustained household and business spending.
- Demand shifted rapidly across goods and services.
- Energy and food prices rose sharply after Russia's invasion of Ukraine.
- Labor markets became tight in many countries and wage growth later increased.

  The relative importance of these forces differed across countries and changed
  over time.

### Similar inflation can imply different policy choices

Suppose inflation is above target.
Demand-driven inflation
        A positive output gap accompanies high inflation. Tighter policy moves
        both inflation and activity toward their desired levels.
Inflation after a cost shock
        Activity may already be weak. Tighter policy reduces inflationary
        pressure but makes the negative output gap larger.

  A central bank therefore needs a view about the sources and persistence of
  inflation, not only a reading of current inflation.

### Policy decisions are made in real time

Important inputs to policy cannot be observed precisely:
- potential output and the output gap
- the normal real interest rate, $\bar r_t$
- the extent to which current inflation reflects broad and persistent
      price pressures rather than temporary or volatile changes in particular prices
- the strength and timing of monetary transmission

  Data are published with delays and are often revised. Policymakers must also
  distinguish temporary disturbances from persistent changes.

  Taylor rules are useful benchmarks, but they cannot replace forecasts and
  judgment.

## The transmission of monetary policy

### The policy rate is only the starting point

A central bank directly controls a very short nominal interest rate.

  But monetary policy also affects
- expectations of future short-term interest rates,
- longer market interest rates and asset prices,
- lending rates and access to credit,
- household cash flows and firms' financing costs, and
- expectations of future inflation and economic activity.

    Monetary policy affects the economy through these
    **transmission channels**.

    Several links in this transmission mechanism can vary across time and countries.

### Expectations and longer interest rates

Longer interest rates depend partly on expected future short-term rates.

  A policy announcement can therefore affect market rates today even when the
  current policy rate does not change.

  Longer rates also contain term and risk premia, so they need not move one for
  one with expected policy rates.

**Figure source:** `Expected_r.png`

  { Market pricing and Riksbank forecast, September 2024.
  Source: Sveriges Riksbank.}

### Transmission to government bond rates

**Figure source:** `PolicyRate_GvtRates.png`

  { The Riksbank's policy rate and Swedish government bond rates, percent.
  Sources: Sveriges Riksbank and Statistics Sweden.}

### Rates faced by households and firms

**Figure source:** `Riksbank_MPR2024rates.png`
Source: Sveriges Riksbank, Monetary Policy Report, September 2024.

### Mortgage structures affect household cash flows

Policy tightening reaches indebted households more quickly when
- mortgages have short fixation periods, and
- household debt is large relative to income

  The cash-flow channel is therefore stronger in some countries than in others.

**Figure source:** `PassThroughInternational_Dec21_Jul23.png`

 Increase in household interest rates from December 2021 to July 2023,
  percentage points. Source: Macrobond.

### Transmission in the IS–MP–PC framework

Consider a monetary tightening with initially unchanged inflation expectations:

1. The central bank raises the nominal policy rate, $i_t$.
2. The ex ante real rate, $r_t\approx i_t-\pi_t^e$, rises.
3. Market and lending rates normally rise, though not mechanically.
4. Interest-sensitive consumption and investment weaken.
5. The output gap falls along the IS curve.
6. Weaker activity gradually reduces inflationary pressure through the
          Phillips curve.

  LN6 compresses these steps into one period. In reality they occur with
  different delays.

### The effects differ across households and firms

A single interest rate in the model conceals substantial heterogeneity.

- Borrowers lose cash flow when lending rates rise, while savers receive
          more interest income.
- Variable-rate borrowers adjust sooner than borrowers with fixed rates.
- Young and highly indebted households may reduce spending sharply.
- Firms with weak balance sheets or a need to refinance may cut investment
          more than firms with ample internal funds.

  The aggregate IS response depends on the distribution of these exposures.

### Monetary policy works with delays

Different parts of the economy respond at different speeds:
- financial-market prices can adjust within seconds,
- lending rates reset as contracts mature or are renegotiated,
- many consumption and investment decisions adjust over months or years, and
- wages and prices adjust gradually.

  Policy must therefore be forward-looking. Waiting until all effects are visible
  may mean acting too late.

  **Monetary policy necessarily relies on forecasts.**

### Correlation does not identify the effect of policy

Why not estimate the effect of monetary policy from the correlation between
  the policy rate and inflation?

  Central banks usually raise the policy rate when inflation or expected inflation
  is high.
- The policy rate may therefore be positively correlated with inflation.
- This does not mean that higher interest rates cause higher inflation.

  Empirical studies try to isolate **monetary-policy surprises**: changes in
  policy that were not predictable from information already available.

### Estimated effects of a Riksbank policy-rate surprise

**Figure source:** `MP_IRF.png`

  { Estimated impulse responses to a monetary-policy shock. Source:
  [Almerud et al. (2024)](https://www.riksbank.se/globalassets/media/rapporter/working-papers/2024/no.-445-measuring-riksbank-monetary-policy-shocks-and-macroeconomic-transmission.pdf).}

## Banks, risk premia and financial crises

### Why banks are useful and fragile

```latex
l r | l r
      \multicolumn{4}{c}{**A simplified bank**}\\
      Assets & & Liabilities & \\
      \hline
      Reserves & 10 & Deposits & 180\\
      Bonds & 30 & Other debt & 10\\
      Loans & 160 & Equity & 10\\
      \hline
      Total & 200 & Total & 200

```

- Banks fund long-term and illiquid loans partly with deposits that
            can be withdrawn quickly.
- Equity is a small share of the balance sheet.
- Losses can therefore threaten solvency, while withdrawals can create
            an immediate liquidity problem.

  Deposit insurance, liquidity requirements and capital requirements reduce
  these risks but cannot eliminate them.

### Risk premia create a wedge in the IS curve

Households and firms do not borrow at the risk-free real interest rate.
  Write the relevant borrowing rate as

$$r_t^b=r_t+\rho_t,$$

  where $\rho_t$ is a credit or risk premium.

  The IS curve becomes

$$\boxed{\widetilde{Y}_t=\alpha_t-\beta(r_t+\rho_t-\bar r)}$$

- A higher policy rate reduces demand by raising $r_t$.
- Financial stress can reduce demand by raising $\rho_t$, even if the
          policy rate is unchanged.

### Risk premia during the global financial crisis

**Figure source:** `MACRO6_FIG14.01_box.jpg`
Source: Jones (2024), Figure 14.1.

### A housing bust shifts the IS curve

**Figure source:** `MACRO6_FIG14.02a_box.jpg`

  A fall in housing wealth reduces demand. An ordinary monetary-policy response
  would lower the policy rate and partly offset the recession.

  { Source: Jones (2024), Figure 14.2(a).

### Risk premia amplify the recession

**Figure source:** `MACRO6_FIG14.02b_box.jpg`

   During the GFC, the policy rate fell while the borrowing rate relevant to the
  IS curve rose. The increase in the risk premium therefore reinforced the
  initial fall in demand.

  { Source: Jones (2024), Figure 14.2(b).

### From financial stress to recession and deflation risk

- The housing bust and higher risk premia shift aggregate demand to
              the left.
- Output falls below potential and inflation declines.
- If expected inflation also falls, the AS curve shifts down and
              real interest rates may rise further.

      The IS–MP and AS–AD models describe different stages of the same
      transmission mechanism.

**Figure source:** `MACRO6_FIG14.03_box.jpg`

  { Source: Jones (2024), Figure 14.3.

### Why was the Great Depression so severe?

Several mechanisms reinforced one another:
- monetary tightening in 1928–29 weakened demand before the crash,
- falling wealth and confidence shifted the IS curve further to the left,
- bank runs and bank failures disrupted credit intermediation,
- deflation raised real debt burdens and, at a given nominal rate, the
          real interest rate, and
- the gold standard constrained monetary responses and transmitted
          contraction across countries.

  Friedman and Schwartz emphasized the collapse in the money supply. Bernanke
  emphasized the additional credit effects of bank failures. These explanations
  are complementary rather than mutually exclusive.

### The Great Depression in the IS–MP framework

**Figure source:** `MACRO6_FIG14.12.jpg`

   Tight policy, the stock-market crash and financial disruption successively
  reduce demand. Deflation then raises the real interest rate when the nominal
  rate does not fall correspondingly.

  { Source: Jones (2024), Figure 14.12.

### A large output gap produces deflation

**Figure source:** `MACRO6_FIG14.13.jpg`

   The Phillips curve completes the story: a persistent negative output gap puts
  downward pressure on wages and prices. Deflation can then feed back into the
  IS–MP diagram through the real interest rate and real debt burdens.

  { Source: Jones (2024), Figure 14.13.

### Different crises, different mechanisms

- **Global financial crisis, 2008:** losses on risky assets,
          fragile bank funding and a collapse in credit. Policy provided bank
          liquidity, guarantees and recapitalization.

- **Euro crisis, 2010–12:** sovereign risk, weak banks and
          self-reinforcing increases in bond spreads. Policy required a credible
          backstop for sovereign bond markets and the banking system.

- **Pandemic, 2020:** a sudden stop in activity and a dash for cash.
          Policy supported market liquidity and credit, while fiscal policy
          supported household and business income.

- **SVB and related failures, 2023:** interest-rate losses and rapid
          runs by uninsured depositors. Policy provided emergency liquidity and
          protected depositors at failed banks.

  The common element is financial amplification. The source of stress and the
  appropriate intervention differ across episodes.

### Silicon Valley Bank: interest-rate risk becomes a run

```latex
l r | l r
      \multicolumn{4}{c}{**Stylized SVB balance sheet**}\\
      Assets & & Liabilities & \\
      \hline
      Reserves & 20 & Deposits & 170\\
      Bonds & 190 & Market funding & 25\\
       & & Equity & 15\\
      \hline
      Total & 210 & Total & 210

```

- Rising interest rates reduced the market value of long-term bonds.
- A concentrated depositor base held large uninsured balances.
- Concern about losses triggered unusually rapid withdrawals.
- Selling bonds to meet withdrawals would realize losses and further
            weaken the bank.

  Liquidity and solvency problems can reinforce one another during a run.

### Central banks in a financial crisis

Possible interventions include
- lending against collateral to solvent institutions
- supplying liquidity to important financial markets
- accepting a broader range of collateral
- purchasing assets when market functioning breaks down
- communicating a credible willingness to act

  Important complications:
- solvency and collateral values are difficult to assess during a crisis
- support can protect financial stability while encouraging future risk taking
- some interventions expose the public sector to losses or political conflict

## Quantitative easing

### Quantitative easing changes the central bank's balance sheet

Under **quantitative easing (QE)**, a central bank purchases longer-term
  securities and pays by creating central-bank reserves.

  Possible transmission channels include:
- purchases raise bond prices and lower longer-term yields and term premia
- investors rebalance toward other assets, affecting a wider range of
          financing conditions
- purchases can restore liquidity and market functioning during a crisis
- they can signal that short-term rates will remain low for longer

  QE is especially relevant when the policy rate is near its effective lower
  bound or when financial-market transmission is impaired.

### The Riksbank's balance sheet: then and after QE

**Figure source:** `RbBalanceSheet.png`

  { SEK billion. The comparison shows 2007 and March 2022. Source:
  Flod\'en (2022),
  [``My thoughts on the Riksbank's asset purchases.''](https://www.riksbank.se/globalassets/media/tal/engelska/floden/2022/floden-speech-my-thoughts-on-the-riksbanks-asset-purchases.pdf)

### Central-bank balance sheets expanded internationally

**Figure source:** `CB_balancesheets.png`

  { Total central-bank assets as a percentage of GDP. Dashed lines show
  the latest observations available when the figure was constructed (2024).
  Sources: National central banks and Macrobond.

### QE is not unproblematic

- Estimated effects are often modest and uncertain
  - They may be stronger during financial crises, especially when
              market functioning is impaired

- QE exposes the central bank to interest-rate risk
  - Rising interest rates can generate substantial losses and reduce
          transfers to the government

- Asset purchases affect the allocation of risk across the public and
          private sectors
  - They may distort market prices and weaken their information content
  - They may be more politically contentious than changes in the
              short-term policy rate

- QE may blur the distinction between monetary and fiscal policy

## Money and digital currencies

### What is money?

Money serves as
1. a **medium of exchange** used for payments,
2. a **unit of account** in which prices and contracts are stated, and
3. a **store of value** that transfers purchasing power over time.

  Some assets perform only some of these functions, or perform them imperfectly.

### How does money get its value?

Different forms of money derive their value in different ways:
- **Commodity money** has value for other purposes as well as for
          payments. Historical examples include gold and silver.
- **Fiat money** is not backed by a commodity. Its value depends on
          confidence that others will accept it and that its purchasing power
          will remain reasonably stable.

### Most money is created by commercial banks

Most money held by households and firms consists of deposits in
  commercial banks.

  When a bank grants a loan, it normally records
- a new loan as an asset, and
- a matching deposit as a liability.
  The new deposit is money.

  Banks' money creation is constrained by
- demand for loans from creditworthy borrowers,
- banks' willingness to lend and their funding costs, and
- regulatory requirements on bank capital and liquidity.

### Central banks underpin the monetary system

- Banks settle payments with one another in **central-bank money**.
  - The settlement asset therefore does not depend on the
            creditworthiness of another commercial bank.

- Central banks operate systems for settling payments.
  - In Sweden, the Riksbank operates RIX-RTGS and RIX-INST.

- Central banks provide liquidity to the banking system when needed.

- Through interest rates and liquidity provision, central banks
          influence lending conditions, credit and commercial-bank money creation.

### Bitcoin and stablecoins

Bitcoin
- An unbacked digital asset with supply governed by a protocol
- Not widely used as a unit of account or for ordinary payments
- A volatile store of value
- No issuer or lender of last resort
Stablecoins
- Private digital claims intended to maintain a fixed value against
                a currency such as the U.S. dollar
- Stability depends on reserves and credible redemption
- Similar in some respects to uninsured deposits or money-market funds
- Runs could force rapid sales of reserve assets

  The monetary question is less about the technology than about stable value,
  redemption, trust and financial backing.

## Expectations and institutions

### Inflation targeting provides a nominal anchor

An inflation target helps coordinate expectations about future inflation and
  the evolution of the price level.

- Wage setters need a view about future prices.
- Firms need a view about costs and competitors' prices.
- Borrowers and lenders need a view about future purchasing power.

  If long-run expectations remain close to the target, a temporary cost shock
  need not become persistent inflation.

  Credibility therefore affects the position and movement of the AS curve, not
  only central-bank communication.

### Inflation expectations in Sweden

**Figure source:** `Riksbank_MPR2024expect.png`

  { Money-market participants' expectations of Swedish CPI inflation.
  Source: Kantar Prospera and Sveriges Riksbank, Monetary Policy Report,
  September 2024.}

### Federal Reserve independence in the news

Reuters, June 29, 2026
    [*``US Supreme Court rejects Trump bid to fire Fed's Cook''*](https://www.reuters.com/world/us-supreme-court-rejects-trumps-unprecedented-bid-fire-feds-cook-2026-06-29/)

- The attempted removal of a Federal Reserve governor put the meaning
          of removal ``for cause'' at the center of a constitutional dispute.
- The Supreme Court rejected the removal and emphasized the safeguards
          created by long, staggered terms and removal only for cause.
- Political demands for substantially lower interest rates have
          nevertheless continued.

  The episode turns an abstract question from LN7 into a current one: who should
  control the policy instrument when political and monetary-policy horizons differ?

### Why delegate monetary-policy decisions?

LN7 showed how discretionary policy can produce inflation bias when the public
  expects attempts to create surprise inflation.

- Governments face elections and may prefer short-run stimulus or cheap
          financing of public debt.
- If the public anticipates such pressure, expected inflation and nominal
          interest rates rise without a lasting gain in output.
- Delegating instrument choice to an independent central bank can make a
          commitment to price stability more credible.

  **Independence concerns instrument choice.** The mandate and ultimate
  objectives remain grounded in the democratic political process.

### Independence requires accountability

Institutional safeguards and accountability mechanisms include:
- a clear objective established through the political process
- secure, overlapping terms for decision makers
- committee decisions rather than control by a single individual
- transparent forecasts and explanations
- published minutes, legislative hearings and public evaluation

  Independence is therefore compatible with scrutiny. The central bank must be
  free from instructions about individual rate decisions while explaining how
  those decisions serve its mandate.

### A quieter Federal Reserve?

Two headlines, June 2026
*``Kevin Warsh Wants the Fed to Stop Explaining Everything''* (https://www.wsj.com/economy/central-banking/fed-warsh-chair-communication-d2f2d226)

  Wall Street Journal
*``Will Warsh's call for a quieter Fed create more or less market noise?''* (https://www.reuters.com/commentary/reuters-open-interest/will-warshs-call-quieter-fed-create-more-or-less-market-noise-2026-06-17/)

  Reuters

  Chair Kevin Warsh argues that extensive forward guidance can make markets
  focus too much on the central bank's words and can constrain policy when new
  information arrives. He has called for communication to become quieter and
  more purposeful.

  This raises a genuine tradeoff: communication is itself a policy tool, but
  more communication is not automatically more informative.

  { See [Warsh, ``Reform of the Conduct of Monetary Policy,'' August 28, 2026](https://www.federalreserve.gov/newsevents/speech/warsh20260828a.htm).

### The monetary-policy communication tradeoff

What communication can achieve
- explain the reaction to data and shocks
- influence expected future short-term rates
- anchor inflation expectations
- make an independent institution accountable
What can go wrong
- many voices can create noise
- guidance may be misread as a promise
- markets may overreact to small changes in wording
- the central bank and markets may end up reading one another

  Effective communication should be clear, purposeful and compatible with
  policy adapting when the outlook changes.

### Flexible inflation targeting

Inflation targeting does not require inflation to equal the target every month.

- Monetary policy affects inflation with delays.
- Cost shocks can create a short-run conflict between inflation and activity.
- Returning inflation to target too quickly may require a large negative
          output gap.
- Returning too slowly may allow expectations to drift away from the target.

  A credible central bank can allow temporary deviations while explaining how
  policy will return inflation to target.

## Conclusions

### What the simple model captures and leaves out

What it captures
- demand and cost shocks
- the real-rate channel
- output gaps and inflation pressure
- expectations and systematic policy
What practice adds
- many interest rates and risk premia
- banks and balance-sheet constraints
- asset purchases and central-bank balance sheets
- heterogeneous households and firms
- institutions, communication and uncertainty

  The model remains useful because it organizes these complications around a
  small number of economic mechanisms.

### Main lessons

- The source of inflation matters for the appropriate policy response.
- The policy rate affects demand through market rates, credit, cash flows
          and expectations.
- Financial stress can tighten conditions independently of the policy rate.
- Different crises require different interventions even when all involve
          financial amplification.
- QE can affect longer-term financing conditions when ordinary interest-rate
          policy is constrained or transmission is impaired.
- Stable expectations, credible institutions and purposeful communication
          improve the tradeoffs faced by monetary policy.

  Simple models do not settle policy decisions, but they clarify the questions
  that evidence and judgment must answer.
