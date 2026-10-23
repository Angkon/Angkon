# Angkon Biswas

Graduate researcher in the School of Mechanical Engineering at Purdue University, West Lafayette, Indiana. I work on scientific machine learning for medical flow imaging: physics-informed, unsupervised reconstruction of blood flow from MRI, built in JAX. Alongside the research I build skills for coding agents (Claude Code and Codex) and keep the methods they help derive in a reusable, documented form.

<!-- TODO(angkon): confirm the position and group above, and add advisor or lab if you want it listed. -->

## Research

| Repository | What it is |
|---|---|
| [SMURF](https://github.com/Angkon/SMURF) (private) | Physics-informed extension of SMURF (Hans et al., 2025) from 4D flow MRI to 2D phase-contrast MRI. Joint unsupervised segmentation and velocity and pressure reconstruction with Fourier-feature, random-weight-factorized MLPs, plus divergence, Navier-Stokes and pressure-Poisson residual losses. JAX, Equinox, Optax; sweeps on Purdue's Gautschi H100 cluster. |

New projects start from [research-project-template](https://github.com/Angkon/research-project-template) and are added here.

## Agent tooling and methods

| Repository | What it is |
|---|---|
| [agent-skills](https://github.com/Angkon/agent-skills) | Skills for Claude Code and Codex in the shared `SKILL.md` format, with an installer that links them into both tools and a CI-checked catalog. |
| [research-methods](https://github.com/Angkon/research-methods) | Reusable methods, derived by me, by an agent, or together, each with a `METHOD.md` recording procedure, validation and provenance. |
| [research-project-template](https://github.com/Angkon/research-project-template) | Starting point for project repositories: layout, `AGENTS.md` shared by both agents, CI, citation file. |

## Coursework

- [Intermediate-Fluid-Mech](https://github.com/Angkon/Intermediate-Fluid-Mech): course material and problem sets.

## How this portfolio is organized

- One repository per unit of work, so each can be cited, forked and archived on its own.
- Project READMEs answer the same questions in the same order: what, status, how to run, how to reproduce, which agents and methods were used, how to cite.
- Provenance is recorded for methods and skills: person, agent or both, with tool and model.
- Repositories carry the topics `research-project`, `agent-skill` or `research-method`.

The reasoning behind the layout and the decisions still open are in [docs/portfolio-design.md](docs/portfolio-design.md).

## Contact

- GitHub: [@Angkon](https://github.com/Angkon)
<!-- TODO(angkon): email, Google Scholar, ORCID. -->
