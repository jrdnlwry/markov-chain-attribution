# markov-chain-attribution
Attribution modeling of marketing data using a Markov Chain

Big thanks to Jeremy for putting the intiial model together at: https://github.com/jerednel/markov-chain-attribution

I made some minor tweaks to address runtimewarnings warnings.

This project implements a Markov Chain-based attribution model to quantify the contribution of each marketing channel in a multi-touch customer journey.

Unlike last-touch attribution models, the Markov model calculates the **removal effect** of each channel—how the overall conversion rate would change if a channel were removed—offering a more robust understanding of true channel impact.

---

## 🔧 Features

- Constructs a transition matrix from user journey paths
- Builds a Markov model to simulate customer flows
- Computes **removal effects** for each channel
- Outputs conversion contributions (Markov vs. Last-Touch)
- Provides transition and absorption matrices

---
