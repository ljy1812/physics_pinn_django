# Physics PINN Django

This repository contains a numerical solver for the Schrödinger Equation using the Finite Difference method.

## Simulation Script
The file `solve_schrodinger.py` implements the 1D Time-Independent Schrödinger Equation solver.

## LaTeX Rendering for Physics Formulas in Django
Based on research, here are the recommended packages/libraries for rendering LaTeX in a Django application:

1. **MathJax**: The industry standard. A JavaScript library that renders LaTeX in the browser. Integration is simple via a CDN script tag in your base template.
2. **KaTeX**: A faster alternative to MathJax. Highly recommended for performance-critical physics applications where fast rendering is essential.
3. **django-mathjax**: A Django-specific wrapper that simplifies the inclusion of MathJax.
4. **django-markdownx**: Useful if you use Markdown; it can be configured to support LaTeX rendering via MathJax or KaTeX.
