# Beyond the black box: Causality-informed symbolic regression reveals mechanistic interactions in alloy strengthening

This repository contains the code accompanying the paper:

**“Beyond the black box: Causality-informed symbolic regression reveals mechanistic interactions in alloy strengthening”**

---

## 📌 Description

We propose a **causality-informed machine learning framework** that integrates **causal discovery** with **symbolic regression** to derive **analytical and interpretable structure–property relationships**.

The framework is demonstrated on a binary **Pt–Au alloy system**, where:

- A kernel-based statistical independence test identifies **candidate causal pathways**
- These pathways connect:
  - Processing → Composition → Microstructure → Property
- Symbolic regression is then guided by these causal relationships to derive **mechanism-consistent analytical expressions**

This approach enables the discovery of a **unified strengthening function** featuring a **multiplicative coupling term**, where:

- A dislocation-related factor is modulated by:
  - grain-boundary descriptors
  - solute segregation

revealing **nonlinear interactions between strengthening mechanisms**.

---

## ⚙️ Workflow

The framework consists of two coupled components:

### 1. Causal Inference (CI)

- Infers **directional relationships** between variables based on the **Additive Noise Model (ANM)** framework  
- Uses **HSIC (Hilbert–Schmidt Independence Criterion)** to evaluate residual independence and determine causal direction  

---

### 2. Symbolic Regression (SR)

- Discovers **analytical expressions for hardness**  
- Constrained by physically motivated strengthening mechanisms:  
  - Hall–Petch strengthening  
  - Solid-solution strengthening  
  - Dislocation strengthening  
- Constructs a **unified strengthening model** guided by inferred causal pathways  

---


