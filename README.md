# Optimization Course Visuals
This repository stores a single, self-contained notebook named `visuals.ipynb`. The notebook bundles a set of geometric experiments and dashboards that illustrate different optimization concepts:

1. **Hessian intuition** – surfaces demonstrating how eigenvalue signs, magnitudes, and zeros change local curvature.
2. **Degenerate and deceptive critical points** – quick comparisons via reusable plotting helpers.
3. **Constraint geometry** – scenes covering linear tangency, non-convex objectives, and curved feasible boundaries.
4. **Linear-programming dashboards** – simplex-style feasible regions, sensitivity shifts, and infeasible scenario diagnostics.

## Getting Started
1. Create (or activate) a Python 3 environment with the packages used inside the notebook.
2. Install the minimal dependencies:

	```bash
	pip install numpy matplotlib scipy
	```

3. Launch JupyterLab/VS Code, open `visuals.ipynb`, and run cells sequentially. Each experiment section has a markdown header explaining what the forthcoming plots represent.
## Repository Flow
- Keep upstream changes small and review the rendered plots before committing.
- When updating the notebook, re-run the affected experiments so saved outputs stay in sync with code.
## The remaining files are course class code files
