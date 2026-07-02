### Inyoung Oh

Postdoctoral Researcher, [Visual Intelligence Group](https://vig.kist.re.kr/), KIST · PhD, GIST (2026)

I build the geometric half of 3D perception. Learned and foundation models recognize *what is where* but stay geometrically loose: they blur the boundaries and discontinuities where 3D structure lives, and they lose absolute scale.

My approach is one principle: find the geometric relation a model gets wrong, then supply the explicit cue that fixes it. For one problem that cue is a surface-normal field, for another a sharp-feature descriptor, for another a ground plane. I feed it into learned and semantic models so the recovered 3D becomes metric and structurally consistent.

The work follows one arc: from point clouds, to image-grounded 3D, toward fusing explicit geometry into semantic foundation models. Each project below is an instance of that approach, not the point of it.

**Selected work**

- **[SFD-Net](https://github.com/inyoungoh-cde/SFD-Net)** · [project page](https://inyoungoh-cde.github.io/SFD-Net/) — sharp features as discontinuities of the normal field: a compact, architecture-agnostic descriptor that improves different point-cloud backbones and transfers zero-shot from CAD to real scans. *[ECCV](https://eccv.ecva.net/) 2026.*
- **[Multi-scale normal estimation](https://github.com/inyoungoh-cde/DeepLearningNormalEstimation)** — stabilizing surface normals under non-uniform sampling and noise ([IJIG](https://www.worldscientific.com/worldscinet/IJIG?srsltid=AfmBOoq15eXNYhlsTrT4qEWLhb9VLQZge0MC5JfHmjObFX2zb-dGxpx7), 2026).
- **Normal-guided LiDAR segmentation** — injecting physically grounded normals to sharpen safety-critical boundaries ([JCDE](https://academic.oup.com/jcde), 2023).
- **Metric relocalization from a moving camera** (KIST, in preparation) — recovering metric 3D via the ground-plane normal, carrying the same geometry from point clouds into 2D-to-3D.

**Elsewhere:** [Homepage](https://inyoungoh-cde.github.io/) · [Google Scholar](https://scholar.google.co.kr/citations?hl=en&user=e3h5YtAAAAAJ&view_op=list_works&sortby=pubdate) · [LinkedIn](https://www.linkedin.com/in/iyohcde/)
