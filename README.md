# imgs2imgs: Improving Visual Consistency in Multiview Image Editing

🏆 **Best Student Paper — AIPR 2025 (Oral)**  
![Award](docs/awards/aipr2025_best_student_paper.jpg)

**Authors:** Mohamed Gallai, Abby Stylianou  
**Venue:** Applied Imagery Pattern Recognition Workshop (AIPR 2025) — *to appear in Springer proceedings*  
📄 **Preprint (author-created):** [paper/preprint.pdf](paper/preprint.pdf)

---

## What this work solves
Multiview image editing (wide-baseline pairs) often fails due to **cross-view inconsistency** and poor **localized control**. This work introduces a lightweight, training-free pipeline that improves consistency while keeping edits localized.

## Key contributions
- **Mask-guided partial diffusion** to localize edits  
- **Training-free cross-view feature sharing** to improve consistency across viewpoints

---

## Figures (highlights)
(Selected qualitative and method figures from the paper.)

- Method overview — `docs/figures/fig10_method.png`  
- Feature sharing — `docs/figures/fig12_feature_sharing.png`  
- Qualitative comparisons — `docs/figures/fig15_comparison.png`, `docs/figures/fig16_comparison.png`  
- Hero result — `docs/figures/fig17_result.png`

---

## Citation
```bibtex
@inproceedings{gallai2025imgs2imgs,
  title     = {imgs2imgs: Improving Visual Consistency in Multiview Image Editing},
  author    = {Gallai, Mohamed and Stylianou, Abby},
  booktitle = {Applied Imagery Pattern Recognition Workshop (AIPR)},
  year      = {2025},
  note      = {To appear in Springer proceedings}
}
