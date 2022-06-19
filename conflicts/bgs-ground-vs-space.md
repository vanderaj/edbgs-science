---
title:  'Are ground combat zones equivalent to space combat zones'
journal: 'SINC Journal of BGS Science'
author:
- name: Andrew (Cmdr Purrfect) van der Stock
  email: vanderaj@gmail.com
  institute: SINC BGS
  corresponding: true
  footnote: 1
- name: Cmdr Infir
  footnote: 2
affiliation:
- number: 1
  name: SINC BGS
- number: 2
  name: SINC BGS
keyword:
  - bgs
  - combat zones
  - space
  - ground
lineno: false
abbreviation:
  - BGS, background simulation
  - SINC, Sirius Interim National Council aka Sirius Inc
abstract: |
  It is thought by many that Space combat zones (CZs) are more impactful than ground CZs. We are going to test 3 low ground CZs versus 3 space low CZs. 
bibliography: references.bib
acknowledgements: |
  We'd like to thank the ED BGS Discord Server for looking over these results and providing fearless and frank advice.
contribution: |
  A.V. conceived the experiment(s),  A.V. and Cmdr Infir conducted the experiment(s), TBA analysed the results.  All authors reviewed the manuscript.
template: elsevier
documentclass_options: 
  - final
...

# Introduction

After Odyssey's launch in May 2021, it was often thought that space CZs have more impact on winning the war. Instead, the mechanism seems to be that the most number of objectives won makes the most difference. We know one of the objectives is the win condition, but there are other objectives as well:

- Space CZs have Spec Ops / Protect / Kill objectives
- Ground CZs have capture base objectives
- (Shared) Fighting in *all* CZs and winning a day as a result will likely move the assets fought the most to the winning side. 

<!---
References are cited as @mittner2014brain or [@mittner2014brain].
-->

# Methods

To investigate this in a way that can be reproducible, the experiment is designed to run both sides of the war, with the following caveats:

- The two factions at war must be present, not controlling factions[^1]
- The two factions' influence should not exceed 25%[^2]
- There must be space and ground CZs of equal value (i.e. low, medium, or high)
- If multiple CZ locations, we only ran the CZs at the same location with the same rating.[^2]
- On any particular day, we will only run one rating of CZ (low, medium, or high) in case of hidden bonuses due to objectives

[^1]: We do not want to change the controller of any system, just observe the outcome of day or days of war
[^2]: This is to ensure that the mechanism by which lower factions have boosts are canceled out, and the movement will be larger if there is a difference.
[^3]: We controlled for this variable by fighting in a single location for each type of CZ.

Three low CZs

Data: 
- Objectives completed (bases, captured, etc)
- how long it took over the three runs
- Results

<!-- >
! [This is gonna be the caption.] (pics/dummy.pdf) {#fig:dummy width=100%}

And referenced from here as Fig. @fig:dummy.

Complex tables can use standard LaTeX code as this one.

Equations can be used inline $y=\beta_0 + \beta_1 x + \epsilon$ or as usual $$f(x)=\frac{1}{x}$$

<!---
Table in LaTeX format because of fancy formatting
-->

\begin{table}[ht]
\centering
\caption{Probability to observe Bayes Factors of a certain magnitude or above for the used sample-size of $N=60$ assuming the original and the null-hypothesis.}
\begin{tabular}{llrrr}
  & & \multicolumn{3}{l}{$P(\text{BF}\ge\theta)$}\\
  Hypothesis & BF Type & $\theta=3$ & $\theta=10$ & $\theta=20$ \\
  \hline
  $d\sim \mathcal{N}(1.57, 0.51)$ & JZS BF$_{10}$ & 0.98 & 0.97 & 0.96 \\
     & Replication BF$_{10}$ & 0.98 & 0.96 & 0.96 \\
     & Meta-Analysis BF$_{10}$ & 0.99 & 0.99 & 0.99 \\\cline{2-5}
    $d=0$ & JZS BF$_{01}$ & 0.81 & 0.00 & 0.00 \\
   & Replication BF$_{01}$ & 0.98 & 0.95 & 0.91 \\
     & Meta-Analysis BF$_{01}$ & 0.63 & 0.27 & 0.06 \\
   \hline
\end{tabular}
\label{tab:probbf}
\end{table}

# Results

# Discussion

# References
