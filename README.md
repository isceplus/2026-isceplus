# 2026-isceplus
Contains materials for the [2026 EarthScope Technical Course: InSAR Processing and Analysis (ISCE+)](https://www.earthscope.org/event/2026-technical-course-insar-processing-and-analysis-isce/)

This 5-day course covers basic and advanced InSAR theory and hands-on processing of Sentinel-1 and NISAR data using the JPL/Caltech InSAR Scientific Computing Environment (ISCE/ISCE3). Topics include noise mitigation, accessing ARIA and OPERA standard InSAR products and preparing them for time-series analysis, InSAR time-series analysis with MintPy, pixel offset tracking, and basic interpretation and modeling.

This repository is not guaranteed to be maintained or have substantive updates after the conclusion of the 2026 EarthScope Technical Course: InSAR Processing and Analysis (ISCE+). At our discretion, we will fix emergent bugs caused by changes to environment dependencies or hosted datasets. All maintenance will cease after the launch of the 2027 course, at which point a new repository will be released.

### The notebooks in this repository may be run locally in a Pixi environment on macOS and Linux machines.

1. Install `Pixi` using one of the following options if not already installed:
    - **macOS / Linux**:
    ```bash
        curl -fsSL https://pixi.sh/install.sh | bash
    ```
    - **Download the [pixi installer](https://pixi.prefix.dev/latest/installation/)**

1. Restart your terminal after installing `Pixi`.

1. Clone the `https://github.com/isceplus/2026-isceplus` repository:

   ```bash
    git clone https://github.com/isceplus/2026-isceplus.git
   ```

1. Move into the `2026-isceplus` directory
   ```bash
   cd 2026-isceplus
   ```
1. Install the `Pixi` environment needed to execute the notebooks and launch JupyterLab with a single command:

    ```
    pixi run lab
    ```

1. When running notebooks, select the `iscePlus` kernel.