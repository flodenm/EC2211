# Lecture Notes 11b: International Capital Flows and Policy

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)

This is an agent-oriented rendering of `main_LN11b.tex`. Frame headings follow the lecture source. Figure filenames and notes are retained when present; consult the lecture slides for the visual itself.


### Contents and literature

- The balance of payments and international capital flows
- The net international investment position

    Literature:
- Jones (2024), chapter 19
- Obstfeld (2025), [``The U.S. trade deficit: myths and realities''](https://www.brookings.edu/wp-content/uploads/2025/03/BPEA-SP25_WEB_Obstfeld.pdf), pages 139–167

## The balance of payments and international capital flows

### The balance of payments

The **balance of payments** records transactions between residents of the
    home country and the rest of the world.

    It contains three main accounts:
1. the **current account**: goods, services, income and transfers
2. the **capital account**: capital transfers and nonproduced,
              nonfinancial assets
3. the **financial account**: purchases and sales of financial
              assets

    The capital account is normally small. We will therefore focus on the current
    and financial accounts.

### The current account

Ignoring the small capital account, write

$$CA = NX + NFI + TR,$$

    where
- $CA$: current account balance
- $NX$: exports of goods and services minus imports
- $NFI$: net primary income from abroad, including interest, dividends
              and labor income
- $TR$: net secondary income, including remittances and foreign aid

    Jones often abstracts from $NFI$ and $TR$, in which case $CA=NX$.

### The financial account is the mirror image

The **financial account** records transactions in financial assets.

    Define $FA$ as:

$$FA = {} & residents' net purchases of foreign assets \\
        - {} & foreigners' net purchases of domestic assets$$

- $FA>0$: residents make larger net purchases of foreign assets
- $FA<0$: foreigners make larger net purchases of domestic assets

    Ignoring the small capital account and statistical discrepancies:

$$CA=FA$$

### From the national-income identity to saving and investment

Start with

$$Y=C+I+G+NX.$$

    Add and subtract net taxes, $T$:

$$NX
        &=Y-C-G-I\\
        &=(Y-T-C)+(T-G)-I.$$

- $Y-T-C$ is private saving
- $T-G$ is government saving
- their sum is national saving, $S$

### The key open-economy identity

It follows that

$$NX=S-I$$

- If $NX>0$, the country saves more than it invests domestically and
              accumulates foreign assets
- If $NX<0$, domestic investment exceeds domestic saving and the
              difference is financed from abroad

    Following Jones, we initially abstract from net foreign income and
    international transfers. Hence

$$\boxed{CA=NX=S-I}.$$

    We reintroduce net foreign income when studying the international investment
    position.

### The U.S. current-account balance

**Figure source:** `Figs/US_CA.png`

  Percent of GDP. Source: BEA/FRED.

### How should we interpret the U.S. deficit?

A negative U.S. current-account balance means that:
- U.S. national saving is smaller than investment in the United States
- the United States is a net borrower from the rest of the world
- foreigners acquire net claims on U.S. residents

    This is neither automatically good nor automatically bad:
- borrowing can finance productive investment
- persistent deficits can also reflect low saving and create exposure
              to changes in foreign portfolio preferences

### Current-account and trade balances around the world

**Figure source:** `Figs/OECD_EO_CA_NX1.png`

 Source: OECD Economic Outlook.

### Why can the current account differ from net exports?

**Figure source:** `Figs/OECD_EO_CA_NX2.png`

    Differences between $CA$ and $NX$ reflect net income and transfers. Ireland illustrates this: multinational firms strongly affect GDP,
    trade and cross-border income flows.

 Source: OECD Economic Outlook.

## The net international investment position

### Can a country run current-account deficits forever?

The **net international investment position**, $NIIP$, is the value of
    residents' foreign assets minus foreign claims on residents.

    The logic resembles government-debt dynamics:

```latex
ll
            \toprule
            Government debt & International investment position \\
            \midrule
            debt & $-NIIP$ for a net debtor \\
            primary balance & trade balance, $NX$ \\
            total budget balance & current account, $CA$ \\
            \bottomrule

```

    The central question is whether the position stabilizes relative to GDP.

### A first benchmark: no valuation changes

If asset prices and exchange rates do not change the value of existing
    positions,

$$
        NIIP_{t+1}=NIIP_t+CA_t$$

- $CA_t>0$: residents acquire net claims on foreigners
- $CA_t<0$: foreign claims on residents increase

    This benchmark isolates the flow contribution of the current account.

### The U.S. net international investment position

**Figure source:** `Figs/US_NIIP.png`

 Percent of GDP. Source: BEA/FRED.

### From the current account to the trade balance

We now allow for net foreign investment income, while continuing to abstract
    from international transfers:

$$CA_t=NX_t+NFI_t.$$

    Assume that the same return, $i$, applies to foreign assets and liabilities:

$$NFI_t=i \times NIIP_t.$$

    Combining these equations with $NIIP_{t+1}=NIIP_t+CA_t$ gives

$$NIIP_{t+1}
        &=NIIP_t+NX_t+i \times NIIP_t\\
        &=(1+i)NIIP_t+NX_t.$$

    For a net debtor, net investment income is negative. Whether positive net
    exports are needed to stabilize the NIIP relative to GDP also depends on
    economic growth.

### Dynamics relative to GDP

Let lower-case letters denote ratios to GDP and let GDP grow at rate $g$.
    Dividing the two accumulation equations by $Y_t$ gives

$$(1+g)niip_{t+1}=niip_t+ca_t$$

    and

$$(1+g)niip_{t+1}=(1+i)niip_t+nx_t.$$

    The logic is the same as for government debt: growth enlarges the denominator,
    while investment income compounds the existing position.

### Stabilizing the international investment position

A constant $niip$ requires

$$ca = g \times niip
         \text{and}
        nx=-(i-g)niip$$

    Example: suppose $i=5%$, $g=4%$ and $ca=-4%$.
- $niip$ stabilizes at $-100%$ of GDP
- with the common-return assumption, stabilization also requires
              $nx=1%$ of GDP
- the current-account deficit can persist because nominal GDP grows

### A missing term: valuation changes

In practice, the market value of existing assets and liabilities changes:

$$NIIP_{t+1}=NIIP_t+CA_t+VAL_t,$$

    where $VAL_t$ collects valuation effects and other adjustments.

- movements in equity and bond prices
- exchange-rate movements
- write-downs, reclassifications and measurement changes

    Because many U.S. foreign assets are denominated in foreign currency while
    many U.S. liabilities are in dollars, a dollar depreciation tends to improve
    the U.S. $NIIP$ through valuation effects.

### The return on assets need not equal the return on liabilities

A more realistic expression for net investment income is

$$NFI_t=r_t^A A_t-r_t^L L_t,$$

    where $A_t$ and $L_t$ are gross foreign assets and liabilities.

    A country can have $NIIP=A-L<0$ but $NFI>0$ if:
- its foreign assets earn a higher average return
- its liabilities include low-yield safe and liquid assets
- the composition of assets and liabilities differs

    Gross positions therefore matter, not only the net position.

### U.S. current account, net exports and investment income

**Figure source:** `Figs/US_CA_NX_InvInc.png`

    Despite a large negative $NIIP$, U.S. net investment income has often been
    positive. The simple common-return benchmark misses this return differential.
