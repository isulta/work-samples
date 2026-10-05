# Work Samples

Contained here are samples of my work in scientific data analysis and visualization for my research and graduate studies.

Some highlights are: **SimulationAnalysis.ipynb** (workflow for processing and visualizing galaxy simulation data), **PlanetaryClassification_Report.pdf** (image processing and classification), and **SMACC-parallel** (HPC software for large datasets).

## Notebooks

### [SimulationAnalysis.ipynb](SimulationAnalysis.ipynb)

A sample workflow for analyzing a ~10 GB simulation dataset from the FIRE project. 
The notebook demonstrates how I processed large simulation datasets and transformed them into quantitative results and visualizations while investigating scientific questions.
This workflow is representative of analyses I performed for my doctoral research, published in two [first-author publications listed below](#first-author-publications).

### [PlanetaryClassification_Report.pdf](PlanetaryClassification_Report.pdf)

A report I submitted for the final project of **Statistical Methods for Physicists and Astronomers**, a graduate course at Northwestern. 
In this project, I developed and tested two methods for classifying pictures of planets.

A notebook containing the calculations for the project is [PlanetaryClassification.ipynb](PlanetaryClassification.ipynb).


## Software (available on GitHub)

- **[iht](https://github.com/isulta/iht)**: A Python toolkit I developed for analyzing galaxy simulations. It includes tools for transforming coordinates, finding halo centers, and modeling gravitational potentials. This package was part of my analysis workflow, and is used by students and collaborators.
- **[SMACC-parallel](https://github.com/isulta/smacc-parallel)**: MPI-parallel data analysis framework to model dark matter structures in cosmological simulations.
I ran the software on supercomputers at Argonne to analyze the 1.24-trillion-particle Last Journey simulation.
- **[elfplott](https://github.com/isulta/elfplott)**: A visualization software I created for my graduate electromagnetism course. 
The tool visualizes fields from charge distributions and performs transformations under special relativity,
A [tutorial notebook](https://github.com/isulta/elfplott/blob/main/Tutorial.ipynb) is included in the package.

## Peer-Reviewed Publications (Selected)

Below is a selection of studies I authored, which present the results of scientific data analyses I carried out using large simulation datasets.

1. **[Cooling Flows as a Reference Solution for the Hot Circumgalactic Medium](https://academic.oup.com/mnras/article/540/1/1017/8129693)** — Sultan et al. (2025), *Monthly Notices of the Royal Astronomical Society*.
    Fits analytic models to measurements of gas properties I made using galaxy simulation datasets.
    (Connects to the sample analysis in `SimulationAnalysis.ipynb`.)

2. **[Cold vs. Hot Gas Accretion and Angular Momentum in FIRE Simulations: From Halo to Galaxy Scales](https://academic.oup.com/mnras/article/550/1/stag1117/8708459)** — Sultan et al. (2026), *Monthly Notices of the Royal Astronomical Society*.
   Investigates how disk galaxies form in the universe over billions of years.
   I extended the workflow in `SimulationAnalysis.ipynb` to analyze hundreds of simulation timesteps.

3. **[The Last Journey. II. SMACC — Subhalo Mass-loss Analysis Using Core Catalogs](https://iopscience.iop.org/article/10.3847/1538-4357/abf4fe)** — Sultan et al. (2021), *The Astrophysical Journal*.
Results of a method I developed to model dark matter structures applied to the extreme-scale Last Journey simulation.

## Visualizations

Visualization has been important to my explorations of different datasets and to communicating my results.
Examples of my work are in the **Research** section of [my website](https://imransultan.com/).
A few samples are below.

<table>
  <tr>
    <td width="50%" align="center">
      <a href="https://www.youtube.com/watch?v=7EXVPisN7pE">
        <img src="https://img.youtube.com/vi/7EXVPisN7pE/maxresdefault.jpg" alt="Formation of a Milky Way-like FIRE galaxy over 11 billion years" width="100%">
      </a>
      <br><sub>▶ Formation of a Milky Way-like FIRE galaxy over 11 billion years</sub>
    </td>
    <td width="50%" align="center">
      <a href="https://imransultan.com/media/research/FIRE_m12m_twoscales.png">
        <img src="https://imransultan.com/media/research/FIRE_m12m_twoscales.png" alt="Multiscale look at a Milky Way–mass FIRE halo" width="100%">
      </a>
      <br><sub>Multiscale look at a Milky Way–mass FIRE halo</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <a href="https://www.youtube.com/watch?v=k7R7lfLpY-0">
        <img src="https://img.youtube.com/vi/k7R7lfLpY-0/maxresdefault.jpg" alt="Core tracking: halo merger history" width="100%">
      </a>
      <br><sub>▶ Core tracking: halo merger history</sub>
    </td>
    <td width="50%" align="center">
      <a href="https://www.youtube.com/watch?v=1Zj5t_5B8tc">
        <img src="https://img.youtube.com/vi/1Zj5t_5B8tc/maxresdefault.jpg" alt="Halo particle tracking" width="100%">
      </a>
      <br><sub>▶ Halo particle tracking</sub>
    </td>
  </tr>
</table>