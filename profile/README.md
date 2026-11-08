# NaNIsaac Research

Research code for X-ray diffraction, reflectivity and inverse problems. This organization collects numerical models, reproducible studies and the code behind their figures and presentations.

## Research

### [TraTT — Time-dependent X-ray diffraction](https://github.com/NaNIsaac-Research/TraTT)

A time-dependent Takagi–Taupin solver for the formation of acoustic Bragg satellites as a GHz sound wave enters a crystal. The work examines satellite formation times, transient overshoot, and the range in which reduced analytical models agree with full dynamical diffraction calculations.

- [Results and limitations](https://github.com/NaNIsaac-Research/TraTT#results)
- [Research studies](https://github.com/NaNIsaac-Research/TraTT/blob/main/docs/research/README.md)
- [Install the solver on PyPI](https://pypi.org/project/tratt/)

The reported results are calculations; comparison with measured diffraction data has not yet been established.

### [ReflectoLearn — X-ray reflectivity and inverse problems](https://github.com/NaNIsaac-Research/ReflectoLearn)

A 1D CNN for initial thin-film parameter estimates followed by differentiable Abeles-model refinement. Alongside the fitting software, the research tests what can be inferred from an XRR curve: parameter identifiability, optimizer failures, fitting policies, and the relation between local Fisher information and global distinguishability.

- [Research experiments and verdicts](https://github.com/NaNIsaac-Research/ReflectoLearn/blob/main/docs/research/README.md)
- [Findings](https://github.com/NaNIsaac-Research/ReflectoLearn/blob/main/docs/FINDINGS.md)
- [Usage and reproduction](https://github.com/NaNIsaac-Research/ReflectoLearn/blob/main/docs/usage.md)

Fitting validation currently uses synthetic curves; the repository does not claim validation on measured XRR curves.

## Presentation

*Transient Formation Dynamics of Acoustic Bragg Satellites in Dynamical X-ray Diffraction* — Poster P2.17, Korean Physical Society Fall Meeting, Jeju, 22 October 2026. [Poster and source](https://github.com/NaNIsaac-Research/TraTT#poster).

## Reproducibility

The research repositories provide code, figures, study records, and instructions for rerunning reported calculations. Each result should be read together with its stated assumptions and limitations. Measured data is shared only where permitted.

## Maintainer

[Isaac Yong](https://github.com/NaNIsaac) · [Website](https://nanisaac.github.io)

NaNIsaac Research is a repository organization, not an academic institution. Publications and presentations retain the authors' actual affiliations.
