A hands-on RL tutorial accompanying my lecture *Reinforcement Learning: Classical Foundations and the LLM Era*, part of the [NASA AI/ML STIG lecture series](https://science.nasa.gov/astrophysics/programs/cosmic-origins/community/artificial-intelligence-machine-learning-science-technology-interest-group-ai-ml-stig/). The slides for the lectures can be found [here](https://slides.com/carolcuesta/rl)

The notebook walks through the classical foundations of RL from scratch, using LunarLander as a running example. We start from vanilla REINFORCE, add the standard variance-reduction tricks (reward-to-go, discounting, baselines), and build up to actor-critic methods.

Most of the algorithmic pieces are left as `TODO`s for you to fill in — the boilerplate (env loops, plotting) is provided so you can focus on the math.

## What's in this repo

- `rl_tutorial.ipynb` — the notebook itself
- `notes.pdf` — handwritten lecture notes with the full derivations

## Getting started

Open `rl_tutorial.ipynb` in Colab (no GPU needed — the whole notebook trains in ~10 minutes on CPU).

## Solutions

Filled-in solutions live on the [`solutions`](../../tree/solutions) branch. Try the `TODO`s yourself first. 

## What's covered

1. **REINFORCE** — the policy gradient from the log-derivative trick
2. **Variance reduction** — reward-to-go with discounting, and a baseline (the advantage)
3. **Actor-Critic** — a learned, state-dependent baseline
