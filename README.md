# Arthrogryposis Mobility Prediction Project

## Overview

This project focuses on developing machine learning models to predict **mobility severity** in children with **Arthrogryposis Multiplex Congenita (AMC)**, a rare congenital condition characterized by joint contractures and muscle weakness. Our goal is to integrate **genomic**, **functional**, and **evolutionary** data to create a predictive framework that can support early prognosis, guide treatment decisions, and inform precision medicine strategies in pediatric rehabilitation and disability care.

---

## Objectives

- **Primary Goal**: Predict **mobility impairment severity** based on gene mutations and molecular features.
- **Scientific Contribution**: Generate insights into genotype–phenotype associations in AMC.
- **Societal Impact**: Empower clinicians, families, and researchers with predictive tools to improve care pathways for children living with AMC.

---

##  Research Questions

1. Can specific gene mutations and molecular annotations (e.g., PolyPhen2, SIFT) predict functional mobility outcomes?
2. Are there patterns in allele frequency or conservation that align with severity levels?
3. How can machine learning assist in modeling rare, heterogeneous conditions like AMC?

---

## Dataset Description

### Input Features:
| Feature              | Description |
|----------------------|-------------|
| `Gene`               | Gene associated with the condition (e.g., PIEZO2, TNNT3, TPM2) |
| `MutationType`       | Variant type: Missense, Nonsense, Frameshift, etc. |
| `PolyPhen2_Score`    | Functional impact prediction (0–1) |
| `SIFT_Score`         | Functional tolerance prediction (0–1) |
| `Conservation_Score` | Evolutionary conservation of site |
| `AlleleFrequency`    | Frequency in the population (gnomAD or similar) |
| `MobilitySeverity`   | Target: Severity of mobility impairment (0 = Severe, 1 = Mild) |

> Note: All features have been curated or simulated from published case studies, ClinVar annotations, and rare disease genomic reports. Real-world validation is an intended next step.



