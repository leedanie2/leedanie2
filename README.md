## Daniel Lee

Physics major at Grinnell College (B.A., Honors, May 2027) working at the seam
between physics and systems programming — measurement pipelines, signal
analysis, and the modeling that turns raw telemetry into a decision.

Most recently a **Future Computing Summer Intern at the National Security
Agency (via ORISE)**, researching whether software alone can smooth the power
swings that HPC clusters impose on the electrical grid.

### Selected work

| Project | What it does |
|---|---|
| **[Collecting and Adjusting Server Power](https://github.com/leedanie2/Collecting-and-Adjusting-Server-Power)** | Measures a datacenter CPU's power draw under load, detects transient onsets, smooths them with RAPL capping and di/dt ramp shaping, then scores fleet-scale grid impact against NERC/IEEE thresholds in a Simulink phasor model. C polling daemons, InfluxDB, MATLAB. |
| **[Curve Tracer](https://github.com/leedanie2/curve-tracer)** | Programmable semiconductor curve tracer (in progress). Two-layer KiCad PCB, STM32 firmware, and SPICE Monte Carlo analysis of the analog front end; designed to extract SPICE model parameters from measured I-V curves. |
| **[Telemetry Replay](https://github.com/leedanie2/telemetry-replay)** | PostgreSQL energy-telemetry replay: idempotent ingestion that doesn't double-count retries or overwrite conflicting measurements, SQL window analysis, Docker demo, tested CI. |
| **[Landing Target Vision](https://github.com/leedanie2/landing-target-vision)** | OpenCV ArUco landing-target detector with explicit image-plane offsets, failure handling, and a published evaluation correction. |
| **[Fantasy Baseball ML](https://github.com/leedanie2/fantasy-baseball-ml)** | Predicts fantasy points per game from pitch-level Statcast data using a stacked ensemble (ElasticNet + gradient boosting + neural net). Leakage-free point-in-time features, three-lens feature selection, automated in-season retraining. |

### Background

- **NSA / ORISE** — power-swing mitigation for HPC clusters; C telemetry daemons, random forest prediction with nightly retraining and champion–challenger promotion, custom NERC/IEEE reliability metrics
- **Grinnell Physics** — MATLAB pipelines analyzing extinction spectra across thousands of NANOBEM simulations of LSPR biosensors; derived new models of nanophotonic behavior
- **NASA L'SPACE** — modeled spacecraft command & data handling systems against mission requirements
- **Lab Assistant** — PHY-220 Electronics and PHY-234 Mechanics

### Tools

`C` `Python` `Java` `MATLAB` `Bash` `Linux` `Docker` `Slurm` `Git` `scikit-learn`
Parallel programming · oscilloscopes, function generators, circuit prototyping

### Contact

[leedanie2@grinnell.edu](mailto:leedanie2@grinnell.edu) · [LinkedIn](https://linkedin.com/in/leedanie2)
