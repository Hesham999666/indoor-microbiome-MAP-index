# indoor-microbiome-MAP-index

This repository contains data, code, and figures supporting the manuscript:

**"Enrichment of Anaerobic Airborne Bacteria in Bedrooms of Individuals with Elevated Risk of Sleep Apnea "**

---

## 📁 Repository Structure

- `data/`: Source files including metadata and microbiome profiles
- `scripts/`: Full R script used for analysis and figure generation
- `figures/`: All published figures including boxplots, PCoA, and heatmap
- `results/`: Output of linear models linking microbial genera to MAP index

---

## 🧪 Data Availability

- `Metadata.xlsx`: Participant characteristics and MAP scores
- `relative_abudunce_bacterial_genera.xlsx`: CLR-transformed relative abundances
- `Indoor_bacteria_Metadata_MAP_Index.rds`: Full `phyloseq` object used for beta diversity and ordination analyses

---

## 📊 Main Analyses

1. Character table stratified by gender
2. Linear regression of MAP index vs bacterial diversity/load
3. Boxplots (Figure 1)
4. PCoA with ANOSIM (Figure 2)
5. Heatmaps (Figure 3)
6. Genus-level linear models adjusted for environmental covariates

