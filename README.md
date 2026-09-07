# Radial Visualizations Interactivity
## Manuscript

This repository is created for the following paper:

***"Limitations of Interaction Techniques in Modern Radial Chart Implementations"*** by Aleksandar Anžel and Georges Hattab

Please cite the paper as:
```bibtex
@Article{Anžel2026,
  author={An{\v{z}}el, Aleksandar
  and Hattab, Georges},
  title={Limitations of interaction techniques in modern radial chart implementations},
  journal={Discover Computing},
  year={2026},
  month={08},
  day={04},
  volume={29},
  number={1},
  pages={500},
  abstract={Radial visualization has gained prominence as a versatile approach to exploring complex, multivariate data in information visualization research and practice. However, the interactive potential of radial visualizations remains under-synthesized across existing high-level visualization libraries. In this work, we build upon Kosara et al.'s interaction taxonomy and Draper et al.'s seven radial design patterns to provide a systematic review of peer-reviewed studies and commercial systems, combined with supplementary research to capture significant recent developments beyond prior surveys. We assess the interactive capabilities of these individual tools/systems alongside seven leading high-level visualization libraries and map their support for Focus+Context, Multiple Views, Interaction with Dimensions, and Domain-Specific Methods across a range of radial visual designs. Our analysis reveals that while Focus+Context and Multiple View interactions are increasingly common in modern libraries, Interaction with Dimensions and specialized domain methods remain limited, especially outside standard Star and Concentric layouts. Targeted supplementary research also surfaces numerous contemporary systems that address previously unrecognized gaps. Our work not only reveals these critical gaps, but also identifies practical opportunities and emerging directions for advancing interactivity and methodological rigor in the development of future radial visualization tools and libraries.},
  issn={2948-2992},
  doi={10.1007/s10791-026-10416-2},
  url={https://doi.org/10.1007/s10791-026-10416-2}
}
```

[![DOI](./Data/DOI_badge.svg)](https://doi.org/10.1007/s10791-026-10416-2)

---
Abstract:

> Radial visualization has gained prominence as a versatile approach to exploring complex, multivariate data in information visualization research and practice. However, the interactive potential of radial visualizations remains under-synthesized across existing high-level visualization libraries. In this work, we build upon Kosara _et al._'s interaction taxonomy and Draper _et al._'s seven radial design patterns to provide a systematic review of peer-reviewed studies and commercial systems, combined with supplementary research to capture significant recent developments beyond prior surveys. We assess the interactive capabilities of these individual tools/systems alongside seven leading high-level visualization libraries and map their support for Focus+Context, Multiple Views, Interaction with Dimensions, and Domain-Specific Methods across a range of radial visual designs. Our analysis reveals that while Focus+Context and Multiple View interactions are increasingly common in modern libraries, Interaction with Dimensions and specialized domain methods remain limited, especially outside standard Star and Concentric layouts. Targeted supplementary research also surfaces numerous contemporary systems that address previously unrecognized gaps. Our work not only reveals these critical gaps, but also identifies practical opportunities and emerging directions for advancing interactivity and methodological rigor in the development of future radial visualization tools and libraries.

## Dependencies

The code is written in Python 3.14.6 and tested on Linux with the following libraries installed:

|Library|Version|
|---|---|
|pandas|3.0.3|
|scikit-learn|1.9.0|


The dependencies can also be found in [environment.yml](environment.yml).

## Data
|Location|Description|
|---|---|
|[Data/](Data/)|contains all data sets and results used in the manuscript.
|[Data/Coding_Results/](Data/Coding_Results/)|contains the data sets resulted from two independent codings for both tables.
|[Data/Results/Figures/](Data/Results/Figures/)|contains the resulting figures used in the manuscript.

## Code
|Source Code|Description|
|---|---|
|[Source/](Source/)|contains all source scripts.
|[Source/coding_agreement.ipynb](Source/coding_agreement.ipynb)|contains the source code used to calculate coding agreement.
|[Source/Main_Python.ipynb](Source/Main_Python.ipynb)|contains the source code used to generate Python figures.
|[Source/Main_R.ipynb](Source/Main_R.ipynb)|contains the source code used to generate R figures.
|[Source/Coding_Protocol.md](Source/Coding_Protocol.md)|contains the markdown-formatted coding protocol.

## Installation and Running

### User Study Analysis
This process requires users to install Anaconda or Miniconda package managers. Users can install Conda using the instructions on the following link [https://docs.anaconda.com/miniconda/#quick-command-line-install](https://docs.anaconda.com/miniconda/#quick-command-line-install). If Conda is installed, the following sequence of instructions (for Linux-based systems) installs all dependencies and runs the dashboard:

```bash
git clone git@github.com:AAnzel/Radial_Visualizations_Interactivity.git
cd Radial_Visualizations_Interactivity/
conda env create -f environment.yml
conda activate radial_interactive_env
cd Source/
jupyter-lab
```


## License

Licensed under the GNU General Public License, Version 3.0 ([LICENSE](LICENSE) or https://www.gnu.org/licenses/gpl-3.0.en.html)

## Contribution

Any contribution intentionally submitted for inclusion in the work by you, shall be licensed under the GNU GPLv3.
