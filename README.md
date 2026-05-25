# Heavy Quark Contributions to Polarized DIS in the ACOT Scheme: NLO Calculations

## Overview
This repository provides Mathematica notebooks for the analytical evaluation of Next-to-Leading Order (NLO) heavy-quark contributions to polarized Deep Inelastic Scattering (DIS) within the ACOT scheme. 

The implementation covers two key polarized processes:
* **Boson–gluon fusion**
* **Quark scattering**

To optimize performance, some heavy symbolic computation blocks are commented out, with numerical cross-checks performed against standard results from the literature.

---

## Repository Structure
The repository consists of the core analytical notebooks for the polarized channel:

* **`NLO_Pol_DIS_ACOT_BosGluonFus.nb`**
  Implements the NLO computations for the polarized boson–gluon fusion process. Results are benchmarked and validated against arXiv:1910.01536.
  
* **`NLO_Pol_DIS_ACOT_QuarkScatt.nb`**
  Implements the NLO computations for the polarized quark scattering process. Note that this specific channel is evaluated in the real case with $D=4$ dimensions.

---

## Prerequisites
Before running the notebooks, ensure you have installed the following Mathematica packages in your local environment:

### 1. FeynCalc
Required for automated symbolic evaluation of Feynman diagrams and Dirac algebra.
* **Installation Guide:** [FeynCalc Documentation](https://feyncalc.github.io/)
* **Target Path:** `Mathematica\Applications\FeynCalc`

### 2. HypExp (Optional)
Needed exclusively for the expansion of hypergeometric functions in the soft coefficient calculations (currently commented out in the main execution blocks).
* **Download:** [HypExp Project Page](https://www.physik.uzh.ch/~hubert/hypexp/)
* **Target Path:** `Mathematica\Applications\HypExp-win-2.0`
