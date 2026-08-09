# Perovskite Band Gap Prediction

Predicting band gaps of lead-free perovskite materials with machine
learning, as a screening step for photovoltaic applications.

## The problem

Perovskites (ABX₃ crystal structures) are among the most promising
solar cell materials, but the best-performing ones contain lead, which
is toxic. Finding lead-free alternatives means searching a very large
space of possible compositions. DFT gives accurate band gaps but takes
hours per material — far too slow to screen thousands of candidates.

## The approach

Train a model on DFT-computed band gaps from the Materials Project
database, then use it to predict which lead-free compositions land near
the band gap solar cells need — roughly 1.3–1.5 eV.

## Tools

Python · pandas · pymatgen · matminer · scikit-learn

## Status

In progress, started August 2026.

- [x] Repository set up
- [ ] Pull data from Materials Project
- [ ] Explore the dataset
- [ ] Generate features with matminer
- [ ] Train and compare models
- [ ] Write up

---

Jennifer Onosatale - physics undergraduate, University of Benin
---

Jennifer Onosatale — physics undergraduate, University of Benin
