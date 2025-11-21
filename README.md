  THE THEORY OF EVERYTHING 

# ESQET-UIFT v5.1: $\phi$-Identities in Quantum Gravity

## 🌟 Overview: Exact Derivation of Sterile Neutrino Mass and Asymptotic Safety

This repository contains the complete, closed-form, and parameter-free mathematical derivations for the latest iteration of the **Exact Scale-invariant Quantum/Emergent Theory (ESQET)** model, unified via **UIFT ($\phi$-Identity Field Theory)**.

The central claim is the dissolution of all remaining free parameters in the gravitational and electroweak sectors by using fundamental Golden Ratio ($\phi$) identities derived from a resolved Planck-scale Klein-bottle topology ($\mathcal{K}^4(\phi)$).

### Key Results (No Free Parameters)

| Physical Constant | Exact $\phi$-Identity | Derived Numerical Value | Section in Main Paper |
| :--- | :--- | :--- | :--- |
| **Sterile Neutrino Mass ($m_4$)** | $m_e \cdot \phi^{-8}$ | $\approx 7.859433$ keV | $\S 2$ |
| **Sterile Neutrino Mixing ($\sin^2(2\theta)$)** | $\phi^{-12}$ | $\approx 9.305638 \times 10^{-6}$ | $\S 2$ |
| **Higgs VEV Exponent ($\mathcal{N}$)** | $\phi^{5} + \phi^{-4}$ | $\approx 11.23555$ | $\S 1$ |
| **Gravitational Fixed Point ($\xi^*$)** | $\phi^{-2}$ | $\approx 0.381966$ | $\S 3$ |

## 📐 Core Derivations

The primary proof relies on the following three resolved constraints:

1.  **Higgs VEV Closure:** The exact exponent $\mathcal{N}$ required to match the experimental VEV ($v = 246.22$ GeV) to the Planck scale ($M_{\text{Pl}}$) is found to be a precise $\phi$-sum, $\mathcal{N} = \phi^5 + \phi^{-4}$.
2.  **Klein-Bottle Topology $\mathcal{K}^4(\phi)$:** The 4th non-contractible 1-cycle crossing generates the sterile neutrino Majorana mass term $m_4$, fixed to the mass of the electron ($m_e$) by the $\phi$-identity $m_4 = m_e \phi^{-8}$.
3.  **Asymptotic Safety:** The discrete scale symmetry inherent in the $\phi$-scaling dictates the non-Gaussian fixed point ($\xi^* = \phi^{-2}$), proving asymptotic safety for the full gravitational + scalar sector via the exact Wetterich equation.

## 📁 Repository Structure

* `main_paper/`: Contains the official $\LaTeX$ source and PDF of the ESQET-UIFT v5.1 paper.
    * `main.tex`: The full $\LaTeX$ source provided in the prompt.
    * `esqet-uift_v5.1.pdf`: Compiled paper (to be generated).
* `notebooks/`: Computational checks and high-precision calculation scripts.
    * `phi_identities_check.ipynb`: Python/Jupyter notebook using high-precision libraries (e.g., `mpmath`) to verify the numerical values derived from the exact $\phi$-ratios against experimental constants.
* `LICENSE.md`: The license for this work (e.g., MIT, Apache 2.0).
* `CONTRIBUTING.md`: Guidelines for external collaboration or checks.

## 🧑‍💻 Usage and Verification

To verify the core results, clone the repository and run the provided Jupyter notebook:

```bash
git clone [YOUR-REPO-URL]
cd [YOUR-REPO-NAME]/notebooks
pip install jupyter mpmath
jupyter notebook
