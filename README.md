# Rebuttal_ICML2026-8291

![Table A](Multi-missing_classification.PNG)

![Table B](Multi-missing_weee_MAE.PNG)

![Table C](Multi-missing_weee_R2.PNG)

![Table D](shared_specific_ablation.PNG)


![Figure A](lsm2_hallucination_recon_scatter_replot.png)
**Figure A: Correlation between Representation Shift and Ground Truth Probability Drop.** The larger the discrepancy between **emb** and **emb'**, the greater the performance drop. This suggests that reconstructing an entire missing modality, including uninferable modality-specific details, can induce hallucination-like completions, leading to semantic inconsistency and directly harming performance.
