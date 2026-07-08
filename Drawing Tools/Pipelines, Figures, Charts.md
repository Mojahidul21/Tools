# 🎨 Tools & Workflow for Drawing Research Diagrams (Pipelines, Figures, Charts)

A quick reference for creating clean, professional diagrams commonly used in research papers and technical documentation — pipeline/workflow diagrams, system architectures, flowcharts, and data visualizations.

---

## 📐 What Counts as This Kind of Diagram?

- **Pipeline / workflow diagrams** — numbered stages showing a process end-to-end (e.g., Data → Preprocessing → Model → Evaluation → Output)
- **System architecture diagrams** — how components/modules connect
- **Flowcharts** — decision logic, algorithms
- **Charts & graphs** — bar charts, line graphs, confusion matrices, correlation heatmaps (usually generated from code, not drawn manually)

This note focuses mainly on the **first two** (diagrams you draw/design by hand), with a short note on charts at the end.

---

## 🛠️ Tools for Manually-Drawn Diagrams

| Tool                           | Best For                          | Notes                                                                                                                                              |
| ------------------------------ | --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| **draw.io (diagrams.net)**     | Go-to all-rounder                 | Free, web-based, built-in icon libraries, exports to PNG, SVG, and PDF.                                                                            |
| **Canva**                      | Polished look, low effort         | Ready-made infographic and diagram templates.                                                                                                      |
| **Figma**                      | Pixel-perfect control             | Offers precise alignment and spacing, but has a steeper learning curve.                                                                            |
| **BioRender / Mind the Graph** | Scientific workflow figures       | Large libraries of research-relevant icons (e.g., databases, AI/ML, laboratory, gears).                                                            |
| **Microsoft PowerPoint**       | Quick and familiar                | SmartArt and manual icons make it easy to create aligned workflow diagrams.                                                                        |
| **Microsoft Visio**            | Technical and enterprise diagrams | Extensive shape libraries (network, UML, floor plans). Requires a separate license and is not included in the standard Microsoft 365 subscription. |

## 🖼️ Icon Sources

- [Flaticon](https://flaticon.com)
- [Magnific](https://www.magnific.com/app)
- [The Noun Project](https://thenounproject.com)

> Pick **one icon style** (flat / line / filled) and stick with it throughout — mixing styles is the fastest way to make a diagram look unpolished.

---

## 📋 Step-by-Step Workflow

1. **Sketch the flow first, on paper or in your head.** Know your stages/components before opening any tool.
2. **Assign one color per stage or module.** Keep it consistent across headers, borders, and backgrounds.
3. **Number the stages** with small circular badges if the process is sequential.
4. **Use consistent icons** for similar types of components across the whole diagram.
5. **Connect elements with arrows**, keeping a clear direction (left-to-right or top-to-bottom).
6. **Export as vector** (SVG or PDF) whenever possible — keeps text and lines crisp at any zoom level or print size.

## ✅ Quick Checklist

- [ ] Consistent icon style across the whole diagram
- [ ] One color scheme per stage/module, used consistently
- [ ] Clear, single direction of flow
- [ ] Legible font size at final print resolution
- [ ] Exported as vector (SVG/PDF), not just a raster PNG

---

## 📊 For Charts & Graphs (Data Visualizations)

Confusion matrices, histograms, correlation heatmaps, accuracy comparison bars, etc. are usually **generated from code** rather than drawn by hand:

- **Python:** `matplotlib`, `seaborn`, `plotly`
- **R:** `ggplot2`
- **No-code:** Excel/Google Sheets for simple bar/line charts

Keep these consistent with your manually-drawn diagrams by matching the color palette and font.

---

*This note is a general-purpose reference — useful any time you need to design a clear figure for a paper, README, or presentation.*
