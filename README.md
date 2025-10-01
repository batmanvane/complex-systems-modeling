# Complex Systems Modeling (Python)

Learn how (and why) to build models of complex systems — from dynamical systems and chaos to networks, cellular automata, agent-based simulations, and stochastic processes. The course emphasizes **model-building**, **computational thinking in Python**, and **hands-on experimentation**. By the end, you’ll have a small portfolio of working models and a solid sense for when mathematics and code unlock real insight.

---

## What’s inside

- `lectures/` – slide decks & lecture notes that introduce concepts and walk through worked examples.  
- `exercises/` – short, focused tasks to practice each week’s ideas.  
- `notebooks/` – runnable Jupyter notebooks (demos, templates, and explorations).  
- `miniprojects/` – bi-weekly, open-ended modeling problems for deeper practice.  
- `resources/` – readings, links, datasets, and cheatsheets.  
- `requirements.txt` – Python dependencies for local installs.  
- `setup_script.py` – helper to bootstrap a fresh environment (optional).

> License: **Creative Commons BY-SA 4.0** (you may share/adapt with attribution & share-alike).

---

## Who this is for

- Bachelor-level students and practitioners who want practical modeling skills.  
- Anyone comfortable with basic Python (variables, loops, functions) and curious about dynamical systems, networks, stochasticity, and emergence.

---

## Learning goals

By completing the materials you will be able to:

1. Translate real-world questions into tractable computational models.  
2. Implement and analyze core models (e.g., logistic map, predator–prey, Ising/CA, SIR, random walks/Markov chains, small-world & scale-free networks, agent-based systems).  
3. Explore stability, sensitivity, bifurcations, and chaos via simulation.  
4. Run reproducible experiments, visualize results, and compare model variants.  
5. Use Python effectively for scientific work (Jupyter, plotting, packages, IDEs).

---

## Quick start

### Option A: Run in Google Colab (zero install)

1. Open a notebook from `notebooks/` in Colab (File → Open Notebook → GitHub → paste repo URL).  
2. If a notebook references packages, run the install cell (or see `requirements.txt`).

---

### Option B: Run locally

You’ll need [Miniconda](https://docs.conda.io/en/latest/miniconda.html) (recommended) and optionally an IDE such as [PyCharm Community Edition](https://www.jetbrains.com/pycharm/download/).

```bash
# 1) Install Miniconda from the link above, then create a fresh environment
conda create -n csm python=3.11 -y
conda activate csm

# 2) Install dependencies
pip install -r requirements.txt

# 3) Start Jupyter
jupyter lab  # or: jupyter notebook
```

If provided, you can also use the helper:
```bash
python setup_script.py
```

In PyCharm:  
- Open the repo folder as a project.  
- Set the project interpreter to the new conda environment (`csm`).  
- You can then run scripts or open notebooks with the built-in Jupyter support.

---

## Suggested course flow (15 weeks)

- **Weeks 1–2**: Modeling mindset; discrete maps & fixed points; numerical experiments.  
- **Weeks 3–4**: Continuous-time systems (Lotka–Volterra, SIR); stability; phase portraits.  
- **Weeks 5–6**: Chaos & bifurcations (logistic map, Lorenz); sensitivity & Lyapunov intuition.  
- **Weeks 7–8**: Cellular automata & fractals (Game of Life, Sierpiński via chaos game).  
- **Weeks 9–10**: Stochastic processes (random walks, Markov chains, Monte Carlo).  
- **Weeks 11–12**: Networks (ER, small-world, scale-free); diffusion & epidemics on graphs.  
- **Weeks 13–14**: Agent-based modeling; calibration vs. explanation; scenario testing.  
- **Week 15**: Mini-project presentations & reflection.

(Exercises each week; **bi-weekly** miniprojects alternate with **study-at-home** sessions.)

---

## How to use this repo

1. **Start with a lecture** to get the idea.  
2. **Open the matching notebook** to run the model, tweak parameters, and visualize.  
3. **Do the exercise(s)** to solidify the concept.  
4. **Pick a miniproject** every other week to build something end-to-end.

---

## Contributing

- Spot a bug or have a neat extension? Open an issue or PR with a short explanation and a minimal example.  
- Keep notebooks lightweight (prefer small, bundled datasets) and **clearly comment** parameters and outputs.

---

## Citation / reuse

If you reuse or adapt materials, please attribute this repository (CC BY-SA 4.0) and link back here so others can find the source.
