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

### Combat and Security

In progress:

- [Do space CZs count more than ground CZs?](bgs-ground-vs-space.md) [PDF](bgs-ground-vs-space.pdf)

TBD:

- When clearing bad security states such as terrorist attack or piracy, does clearing USS matter more than combat bounties?
- Does biowaste still cause outbreaks?
- How best to fix low security (likely combat bonds, but how much per Cmdr per day?)
- Is there a combat cap? If so, when does it become less useful per Cmdr? Can you overcome this with alts?
- For the various leaderboards, does combat move the needle?
- Does the model of a single victim faction with multiple beneficiary factions work better than a single victim faction and a single beneficiary faction?
- Is there a influence cap? If so, when does it become less useful per Cmdr? Can you overcome this with alts?
- Is there a way to fit combat, trade, exploration, and mission INF to results?

Some ideas on optimizing the analysis of results are here https://www.britannica.com/science/statistics/Residual-analysis
