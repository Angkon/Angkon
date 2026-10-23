# Angkon Biswas

Researcher at Purdue University, West Lafayette, Indiana. This profile is organized as a research portfolio: every project, agent skill, and method I produce lives in its own repository, and this page is the index.

<!-- TODO(angkon): one or two sentences on your research focus, group, and current position. -->

## Portfolio map

| Category | What goes there | Repositories |
|---|---|---|
| Research projects | One repository per project: code, experiments, results, write-ups. New ones start from the project template. | [SMURF](https://github.com/Angkon/SMURF) (private): physics-informed neural networks in JAX and Equinox with random weight factorization and Fourier feature layers, trained on Purdue's Gautschi cluster · MIME (private, placeholder) |
| Agent skills | Skills I write for Claude Code and Codex in the shared `SKILL.md` format, installable in either tool. | [agent-skills](https://github.com/Angkon/agent-skills) |
| Methods | Reusable research methods, derived by me, by an agent, or together, each with provenance and validation notes. | [research-methods](https://github.com/Angkon/research-methods) |
| Templates | Starting points so new repositories stay consistent. | [research-project-template](https://github.com/Angkon/research-project-template) |
| Coursework | Course material and problem sets. | [Intermediate-Fluid-Mech](https://github.com/Angkon/Intermediate-Fluid-Mech) |

## How the portfolio is organized

- **One repository per unit of work.** A project, the skill collection, the method collection, and the template each get their own repository so they can be cited, forked, and archived independently.
- **Consistent READMEs.** Every project README answers the same questions in the same order: what it is, its status, how to run it, how to reproduce the results, which agents and methods were used, and how to cite it.
- **Provenance is recorded.** Methods and skills state whether a person, an agent, or both produced them, and with which tool and model.
- **Topics mark categories.** Repositories carry the GitHub topics `research-project`, `agent-skill`, or `research-method` so they can be filtered from the profile page.

## Starting something new

| I want to... | Do this |
|---|---|
| Start a project | Click "Use this template" on `research-project-template`, then add the new repository to the map above. |
| Add a skill | Add a folder under `skills/` in `agent-skills` and run `scripts/build_catalog.py`. |
| Record a method | Copy `methods/_template` in `research-methods` and fill in `METHOD.md`. |

The design behind this layout, and the decisions still open, are in [docs/portfolio-design.md](docs/portfolio-design.md).

## Contact

- GitHub: [@Angkon](https://github.com/Angkon)
<!-- TODO(angkon): email, Google Scholar, ORCID, lab page. -->
