# Elite BGS Science Repo

This is a repo containing a list of basic research into Elite Dangerous: Odyssey to validate assumptions on the background simulation, questions, hypotheses, predictions, variables, controlled variables, risk assessment, materials (if any), method and design, results with test data. This repo is a way to document experiments and their results that validate or disprove the data we see.

Sadly, FDev don't often document what are the limits or assumptions of BGS, so it's up to us to work out what's helpful, and when does it become more useful to spread effort over alts. We really want to make BGS less a second job and more of a passion by giving Cmdrs the knowledge to best use their time.

We will use the standard scientific method, using sequential analysis to optimize results. What this means is that we will try a few things until it is clear that we have either concluded that it has no real effect, but also to explore what are the likely variables for a particular question. This may require some level of probability or other maths capability to ensure that our biases are not the biases of the data, or allow the replication of results using our methodology. 

We will go into each experiment with zero assumptions. The best science are results that surprise the researchers.

## Build instructions

The papers in this repo are built using markdown-paper. Install:

- Latex, we used Texlive on Debian

```shell
sudo apt-get install pandoc pandoc-citeproc texlive ghostscript texlive-bibtex-extra texlive-science fonts-lato texlive-fonts-extra texlive-publishers
pip install pandoc-fignos
```

### Trade and Economy

In progress:

- In [Elite Dangerous: Odyssey Update 10](https://forums.frontier.co.uk/threads/update-10-odyssey-and-horizons.597956/#post-9713547), BGS from trade changed. What is more important: demand (or supply), profit, transactions, or value?

TBD:

- Is there a trade cap? If so, when does it become less useful per Cmdr? Can you overcome this with alts?
- When clearing bad economic states, such as bust, does trade or missions help more? If trade, what sort?
- Can we determine an INF from trade equation? I.e. given no contest, what value of trade will become influence?
- Does selling 1t, 1.5 mCr, or all at once make any difference at all?
- For the various leaderboards, does trade move the needle?
- Does trade shares affect BGS? If so, are there states that count it or not?

### Random BGS stuff

Things that aren't mentioned in BGS Guides or Squadron Hub

- Does search and rescue affect BGS? If so, for what states?

Some ideas on optimizing the analysis of results are here https://www.britannica.com/science/statistics/Residual-analysis
