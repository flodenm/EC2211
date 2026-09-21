# Lecture Notes 7: AS–AD and Monetary Policy

**Course:** EC2211 Intermediate Macroeconomics, Stockholm University  
**Instructor:** Martin Flodén  
**Course version:** Fall 2026 (authoritative)

This is an agent-oriented rendering of `main_LN07.tex`. Frame headings follow the lecture source. Figure filenames and notes are retained when present; consult the lecture slides for the visual itself.


### Contents and literature

- Amplification and propagation
- The AS–AD model
- The Taylor rule
- Rules, discretion and the time-inconsistency problem

    Literature:

- Jones (2024), chapters 9–13
- Giannone and Primiceri (2024),
        [``The drivers of post-pandemic inflation''](https://cepr.org/voxeu/columns/drivers-post-pandemic-inflation)
- Nakamura, Riblier and Steinsson (2025),
        [``Beyond the Taylor Rule''](https://eml.berkeley.edu/~jsteinsson/papers/Taylor_Rule.pdf)
- Royal Swedish Academy of Sciences (2004), ["... The time consistency problem of economic policy..."](https://www.nobelprize.org/uploads/2018/06/advanced-economicsciences2004-1.pdf)

## Amplification and propagation

### Economic fluctuations involve strong co-movements

In a typical recession:
- output and income fall
- consumption falls, but usually less than income
- investment falls sharply
- employment falls and unemployment rises
- imports fall

    A disturbance in one part of the economy can spread to other variables.

**Figure source:** `MACRO6_Table10.01.jpg`

### Amplification and propagation

Suppose that households or firms become more pessimistic and reduce their
    spending:
1. aggregate demand falls
2. firms reduce production and employment
3. household income and firms' revenues fall
4. consumption and investment may then fall further

    The initial disturbance is therefore **propagated** through the economy
    and may be **amplified**.
For later
        This feedback is often summarized by a *multiplier*. We will study
        fiscal multipliers in the lecture on fiscal policy.

## The AS–AD model

### From IS–MP–PC to AS–AD

The IS–MP–PC framework separates three relationships:
- the IS curve describes aggregate demand at a given real interest rate
- monetary policy determines the real interest rate
- the Phillips curve links inflation to the output gap

    The AS–AD model combines these relationships in a diagram with
- inflation on the vertical axis, and
- the output gap on the horizontal axis

### The monetary-policy rule

Suppose that monetary policy follows the rule

$$r_t-\bar r = \mu(\pi_t-\pi^*),
          \mu>0$$

- $\pi^*$ is the inflation target
- $\bar r$ is the normal real interest rate
- $\mu$ shows how strongly monetary policy responds when inflation
            deviates from target

    If inflation rises above target, the central bank raises the real interest
    rate and reduces aggregate demand.

    This is a simplified description of systematic monetary policy, not a
    complete account of how central banks make decisions.

### Deriving the AD curve

The IS curve is

$$\tilde Y_t = \alpha_t-\beta(r_t-\bar r),
          \beta>0$$

    Use the monetary-policy rule

$$r_t-\bar r = \mu(\pi_t-\pi^*)$$

    to obtain the AD curve:

$$\boxed{\tilde Y_t=\alpha_t-\beta\mu(\pi_t-\pi^*)}$$

    Higher inflation induces tighter monetary policy. The higher real interest
    rate reduces aggregate demand and the output gap.

### The AD curve

**Figure source:** `MACRO6_FIG13.01.jpg`

  Figure 13.1 in Jones

### Movements along and shifts of the AD curve

- A change in inflation produces a **movement along** the AD curve
  - monetary policy responds
  - the real interest rate and aggregate demand change

- A demand shock changes $\alpha_t$ and **shifts** the AD curve
  - a positive demand shock raises $\alpha_t$ and shifts AD to the right

- A larger $\mu$ makes AD flatter
  - monetary policy responds more strongly to inflation

### A more aggressive monetary-policy rule

**Figure source:** `MACRO6_FIG13.03.jpg`

  Figure 13.3 in Jones

### The AS curve is the Phillips curve

Recall the Phillips curve with a cost-push shock:

$$\pi_t=\pi_t^e+\kappa\tilde Y_t+\sigma_t,
          \kappa>0$$

    With adaptive inflation expectations, $\pi_t^e=\pi_{t-1}$:

$$\boxed{\pi_t=\pi_{t-1}+\kappa\tilde Y_t+\sigma_t}$$

    This is the aggregate supply curve in the AS–AD model.

- It slopes upward because a positive output gap raises inflation
- Higher expected inflation or a positive cost-push shock shifts it up

### Equilibrium in the AS–AD model

**Figure source:** `MACRO6_FIG13.05.jpg`

  Figure 13.5 in Jones

### A temporary inflation shock

**Figure source:** `MACRO6_FIG13.06.jpg`

  Figure 13.6 in Jones

- A positive cost-push shock shifts the AS curve up.
- Inflation rises and the output gap becomes negative.
- The monetary-policy response is already built into the AD curve.
- At the new equilibrium, the central bank has raised the real
            interest rate and economic activity has weakened.

### The shock disappears, but inflation remains elevated

**Figure source:** `Fig13p7.png`

  Figure 13.7 in Jones

- The cost-push shock was temporary: $\sigma_1>0$ but $\sigma_2=0$.
- Inflation expectations are now high: $\pi_2^e=\pi_1>\pi^*$.
- The AS curve therefore remains above its original position.
- The negative output gap gradually brings inflation down.

### The economy gradually returns to steady state

**Figure source:** `MACRO6_FIG13.09.jpg`

  Figure 13.9 in Jones

- The negative output gap reduces inflation.
- Lower inflation also reduces expected inflation, shifting AS down.
- As inflation falls, the central bank reduces the real interest rate.
- The economy moves down along AD and gradually approaches steady state.

### Disinflation in the AS–AD framework

Suppose that the economy initially has persistently high inflation.
- Think, for example, of the United States or Sweden in the 1970s.
- Interpret this as an equilibrium with a high inflation target.

    Suppose now that the central bank announces and implements a lower target.
- What happens to inflation and the output gap if expectations are adaptive?
- What changes if the new target is immediately credible?

## The Taylor rule

### How do central banks set their policy rate?

**Figure source:** `john_taylor.jpg`

  John Taylor, 1946–

    Taylor observed in 1993 that U.S. monetary policy could be described by a
    simple rule in which the policy rate responds to
- inflation relative to its target, and
- the output gap.

    The rule was intended as a useful benchmark, not as a mechanical instruction
    that central banks must follow.

### The Taylor rule

$$i_t=\pi_t+\bar r_t
        +\mu(\pi_t-\pi^*)+\omega\tilde Y_t$$

- $\pi_t+\bar r_t$ is the neutral nominal interest rate
- $\mu>0$: the policy rate responds more than one-for-one to inflation
- $\omega>0$: the policy rate also responds to the output gap

    Taylor's original calibration used $\mu=0.5$ and $\omega=0.5$.
- If inflation rises by one percentage point, the prescribed nominal
            interest rate rises by 1.5 percentage points.

### The original Taylor rule for 1987–1992

**Figure source:** `TaylorRule_Nakamura_et_al.png`

  Figure 2 in
    [Nakamura et al. (2025)](https://eml.berkeley.edu/~jsteinsson/papers/Taylor_Rule.pdf)

### The Taylor principle

Recall the Fisher equation:

$$r_t=i_t-\pi_t^e.$$

    Suppose, for simplicity, that $\pi_t^e=\pi_t$.
- If inflation rises, the nominal interest rate must rise by more than
            inflation for the real interest rate to increase.
- In our notation, this requires $\mu>0$.
- The idea that the nominal interest rate should respond more than
            one-for-one to inflation is the **Taylor principle**.

    Without this response, higher inflation would reduce the real interest rate,
    stimulate demand and push inflation up further.

### A benchmark, not a mechanical rule

- Central banks do not mechanically follow a simple Taylor rule.

- The output gap, the neutral real interest rate and even current
            inflation are measured with uncertainty.

- Policymakers also consider forecasts, financial conditions and risks
            that are absent from the simple rule.

- The appropriate response also depends on the source of inflation:
  - a positive demand shock typically raises both inflation and the
                output gap, so both call for tighter monetary policy
  - an adverse supply shock raises inflation but reduces the output
                gap, creating a trade-off for monetary policy

- Nevertheless, the rule is a useful benchmark for describing the
            systematic part of monetary policy.

### The original Taylor rule over a longer period

**Figure source:** `TaylorRule2_Nakamura_et_al.png`

  Figure 3 in
    [Nakamura et al. (2025)](https://eml.berkeley.edu/~jsteinsson/papers/Taylor_Rule.pdf)

## Rules, discretion and time inconsistency

### Rules, discretion and commitment

Should monetary policy follow a fixed rule or respond flexibly to current
    circumstances?

- A strict rule cannot accommodate every possible disturbance.
- Discretion allows policymakers to use all available information.
- But discretion can create a credibility problem if the action that
            seems best later differs from the policy announced earlier.

    A policy is **time inconsistent** when
- it is optimal to announce one policy before private decisions are made,
- but policymakers have an incentive to choose another policy after
            those decisions have been made.

### The temptation to create surprise inflation

Consider a simple Phillips curve:

$$\pi=\pi^e+\kappa\tilde Y,
          \kappa>0$$

    Suppose that wages and prices are set on the basis of expected inflation
    $\pi^e$. After expectations have been formed, the central bank can create a
    positive output gap by allowing inflation to exceed expectations.

    Why might policymakers be tempted to do this?
- They may want temporarily higher output and employment.
- They may believe that distortions keep employment below its socially
            desirable level.

    This is a stylized assumption used to reveal the commitment problem.

### Why the attempt fails in equilibrium

Households and firms understand the central bank's incentive.

1. The central bank would like to promise inflation at the target.
2. Once expectations are fixed, it is tempted to create surprise inflation.
3. Private agents anticipate this and set higher inflation expectations.
4. In equilibrium, inflation cannot systematically exceed expected inflation.

    Hence

$$\pi=\pi^e>\pi^*
         \text{and}
        \tilde Y=0$$
Inflation bias
        Discretion produces higher inflation without a lasting increase in output.

### Institutions can support credible policy

The lesson is not that monetary policy should follow an inflexible formula.
    The challenge is to preserve flexibility while limiting the incentive to
    exploit surprise inflation.

    Relevant institutions include
- an operationally independent central bank
- a clear objective established through the political process
- decision-making by a committee with overlapping terms
- transparent forecasts, decisions and explanations
- accountability for outcomes

    These arrangements help the central bank build credibility and make its
    inflation target more firmly anchored in expectations.

## Appendix: the time-inconsistency model

### Time inconsistency: model setup

Suppose that the policymaker chooses $\pi$ and $\tilde{Y}$ to minimize

$$L=(\pi-\pi^*)^2+\lambda(\tilde Y-Y^*)^2,$$

    subject to

$$\pi=\pi^e+\kappa\tilde Y.$$

- $Y^*>0$ captures the policymaker's desire to push output above potential.
- The policymaker chooses inflation after $\pi^e$ has been formed.
- When choosing inflation, the policymaker therefore takes $\pi^e$ as given.

### Time inconsistency: the policymaker's choice

Substitute

$$\tilde Y=\frac{\pi-\pi^e}{\kappa}$$

    into the loss function and minimize with respect to $\pi$:

$$\min_{\pi}
        (\pi-\pi^*)^2
        +\lambda\left(\frac{\pi-\pi^e}{\kappa}-Y^*\right)^2.$$

    The first-order condition can be written as

$$\left(1+\frac{\lambda}{\kappa^2}\right)\pi
        =\pi^*+\frac{\lambda}{\kappa^2}\pi^e
        +\frac{\lambda}{\kappa}Y^*.$$

### Time inconsistency: equilibrium inflation

In equilibrium, private agents correctly anticipate inflation:

$$\pi^e=\pi.$$

    The first-order condition therefore implies

$$\boxed{\pi=\pi^*+\frac{\lambda}{\kappa}Y^*}.$$

    Since $\pi=\pi^e$, the Phillips curve implies

$$\tilde Y=0.$$

    If $Y^*>0$ and $\lambda>0$, discretionary policy produces an inflation bias
    but no lasting output gain.
