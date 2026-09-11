# One common possession, two very different income groups

Pew's 2025 survey reports smartphone ownership among US adults:

| Annual household income | Own smartphone |
|---|---:|
| Below $30,000 | 82% |
| $100,000 or more | 97% |

[Primary source and survey methods](https://www.pewresearch.org/internet/fact-sheet/mobile/).

Using those rounded percentages, ownership alone has binary overlap
`min(.82,.97) + min(.18,.03) = .85`.
With **equally weighted income groups**, optimal classification accuracy is
`(.97 + .18)/2 = .575`: 57.5%, against a 50% baseline.
Among smartphone owners in that balanced comparison, the higher-income share
is `.97/(.97+.82) = 54.2%`.

This calculation illustrates limited information in broad ownership despite a
real group difference. Equal priors are illustrative, not US population shares.
It measures ownership, not iPhone brand, visible model, human accuracy, or caste.
No sampling interval was calculated from the rounded published rates.
