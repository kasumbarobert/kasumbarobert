## Robert Kasumba

I build AI systems that understand how people think and act, not just what they do.

PhD candidate in Computational & Data Sciences at Washington University in St. Louis, co-advised by
Chien-Ju Ho and Dennis Barbour, finishing December 2026. Before the PhD I was a software engineer:
two Android products on Google Play, one with 50,000+ downloads, and a five-engineer team shipping
farm management tools used by 500+ farmers in Uganda.

Python · PyTorch · SQL · AWS · Docker · R

### Research code

| Repository | What it does | Paper |
|---|---|---|
| [data-driven-grd](https://github.com/kasumbarobert/data-driven-grd) | Learns human behaviour models from 70K+ decisions and redesigns environments so goals can be inferred earlier | [TMLR 2025](https://openreview.net/forum?id=GDuWBhvMid) |
| [NMIL230/nmil-p-mat-ef-man03](https://github.com/NMIL230/nmil-p-mat-ef-man03) | Distributional models of executive functioning — full response distributions instead of point scores, with per-subject uncertainty | [Behavior Research Methods 2026](https://arxiv.org/abs/2510.00387) |

Code for [Early Prediction of Future Behavioral Strategy from Process
Traces](https://arxiv.org/abs/2605.30550) (NeurIPS 2026) is being prepared for release. See also
[Distributional Latent Variable Models with an Application in Active Cognitive
Testing](https://arxiv.org/abs/2312.09316) (IEEE TCDS 2025).

### Dissertation

One question runs through my PhD: how do you infer what a person is doing, or about to do, from
their behaviour — and how do you make that inference cheaper, earlier, and better calibrated? Three
strands.

**Choosing what to measure.** Latent-variable models with Bayesian active selection pick the most
informative next observation instead of running a fixed battery, halving the items needed to
estimate someone's ability while holding accuracy, and reporting per-person uncertainty rather than
a point score. Deployed as a real-time inference service on AWS running live data collection.
*(IEEE TCDS 2025; Behavior Research Methods 2026)*

**Reading the trace, not the summary.** Most practice collapses event-level behaviour into
per-person statistics. Modelling the raw sequences predicts future strategy on tasks a person has
never seen, up to 13 percentage points better than summary features, across 11,080 users.
*(NeurIPS 2026)*

**Designing for inference.** If you can change the environment, you can make intent observable
sooner. Learning behaviour models from 70K+ human decisions and optimising the environment yields
earlier goal recognition — which raises the question of how a system should act when a person is
interpreting its output and deciding for themselves.
*(TMLR 2025; [preprint on human beliefs about AI behaviour](https://arxiv.org/abs/2406.06051))*

### Elsewhere

[Website](https://sites.wustl.edu/robertkasumba/) ·
[Google Scholar](https://scholar.google.com/citations?hl=en&user=V7bHYJYAAAAJ) ·
[LinkedIn](https://www.linkedin.com/in/rkasumba) ·
rkasumba@wustl.edu
