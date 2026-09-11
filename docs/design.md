# From economic position to what a stranger can tell

## The clarified question

The motivating observation concerns **resolution of visible material cues**.
Differences between ₹2,000 and ₹2,500 per person per month can matter to a
household while being difficult for a stranger to discern. We should test that
observation rather than assume either identical appearances or perfect income
measurement by an observer.

Keep four quantities separate:

| Quantity | Example question |
|---|---|
| Economic position Y | What income, assets, or consumption does the household actually report? |
| Material cue C | What clothing, consumer goods, housing or transport is observable in this encounter? |
| Social identity J | What group identity is self-reported or recorded in an independently audited source? |
| Observer judgment R | What does an observer conclude, and with how much confidence? |

The economic pathway motivating the project is `J → Y → C → R`. This is a
conceptual pathway, not an identified causal model. Geography, age, wealth,
credit, preferences and local norms can affect several links. Cultural signals
can reveal identity independently of current income.

If C is *only* a coarsened/noisy measurement of Y, so that `J ⟂ C | Y`, the
data-processing inequality gives `I(J;C) ≤ I(J;Y)`. Under the same restricted
channel, optimally observing C cannot beat optimally observing Y for identifying
J. This is not a blanket upper bound for appearance: dress conventions or local
knowledge can supply information outside income. State the restriction whenever
using the bound.

## A first economic-cue analysis

Use the existing IHDS income/consumption and self-reported asset fields. Do not
label an asset-derived wealth index as an independent outcome when the same
assets are the predictors.

1. Start with documented broad groups and, separately, reviewed jati labels.
   Establish the population prior, including missing/unresolved coverage.
2. Measure aggregate reverse composition using exact reported economic position
   and increasingly coarse, prespecified economic bands. A ₹2,000–₹3,000 band is
   a useful illustration of lost resolution, not an observed human perceptual
   threshold. Sweep several band schemes rather than selecting one for effect.
3. Compare common material profiles from non-facial survey fields: durable goods,
   housing facilities and transport. Separate street-visible possessions from
   information available only on entering someone's home. Household phone
   ownership is not necessarily the phone being carried by the person encountered.
4. Evaluate held-out probability forecasts against identical target categories
   and samples. Show entropy/log-score gain, posterior composition, calibration,
   and decision error relative to population priors. Report the percentage for
   whom a cue changes the most likely category, not just pairwise AUC.
5. Repeat by region, rural/urban status and year. Report both total information
   and additional information after geography; place is a real cue in some
   encounters and absent in others.

A possible lead figure has three panels: economic distributions by group;
composition of a few common material profiles; and how often an available cue
changes the most likely group. Its caption must distinguish actual estimates
from hypothetical illustrations. None of these estimates alone demonstrates
how real observers perform.

## Perception, confidence and consequences

Use published experiments to separate signal validity from stereotype-driven
judgment. A manipulated outfit can alter perceived class or competence even
when it says nothing about the wearer's actual income. Agreement among observers
therefore does not establish accuracy.

An appropriate new experiment could use fictional written material profiles or
object-only displays, with controlled differences in clothing brands, transport
or possessions. Measure perceived economic standing and confidence. These can
test which differences people notice without trying to derive real people's
caste from their portraits. Relate the profiles back to aggregate survey
frequencies only after defining the target population and measurement bridge.

Keep accuracy, confidence, and consequential treatment distinct. Small average
predictive gains do not preclude consequential discrimination against people
with conspicuous cues. Conversely, systematic stereotyping can produce unequal
treatment even when the underlying categorization is inaccurate.

## Global flattening and moving signals

There are at least three distinct temporal hypotheses:

- **Convergence of visible goods:** broad ownership categories become common
  across income groups, making those categories less informative.
- **Migration of the signal:** distinctions move to model, quality, condition,
  combinations, experiences or less visible possessions.
- **Observer dependence:** remaining distinctions become recognizable to insiders
  but less so to strangers or people from another region.

An iPhone is a dated, context-dependent cue. Ownership, current model, condition,
financing, gifts and second-hand purchase are different variables. More
widespread smartphone ownership alone does not show convergence of all consumer
signals or social circumstances.

For a US comparison, Bertrand and Kamenica offer a direct framework: predicting
group membership from consumption, time use and attitudes over time. Their
findings do not establish universal flattening. BLS Consumer Expenditure data
can examine goods and expenditure by economic position, while Pew tracks
technology adoption; neither measures caste or what a passer-by can see.
[Sources](literature.md).

Use fixed target categories, common sample support and explicit population
priors for temporal comparisons. Distinguish absolute income thresholds from
relative rank, and inflation from changes in the informational value of goods.
An accuracy change caused solely by one group becoming larger is not a change
in a cue's discriminating power.

## Income volatility and persistent appearance

Durable goods and dress can reflect resources accumulated over years, credit or
transfers, whereas current income fluctuates. That can weaken the relation
between appearance and one month's income without weakening the relation to
long-run resources. Compare current income, annual income and multi-year
averages; distinguish income flow from asset stock.

The existing IHDS annual income variable, averaged over twelve months, is not a
monthly panel. CPHS/VDSA could identify shorter-run dynamics if access and sample
coverage are established. High income volatility may coexist with persistent
poverty and stable visible consumption.

## What can be synthesized now

The source repositories differ in target categories, samples, label quality and
validation. Do not average their AUCs or add their information gains. Combining
cues requires joint observations in the same population or explicit assumptions
about their dependence. In particular, labels inferred from a surname cannot
independently validate the surname, and a model's predictive score cannot be
substituted for a human observer study.

The current deliverable is a framework and source register. A joint empirical
comparison awaits compatible data and harmonized labels. Prioritize the
non-facial survey-cue analysis and the income-resolution comparison before
making claims about what a stranger can tell.
