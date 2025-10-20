In this project, I used **_lenstronomy_**, a Python-based package for **modeling gravitational lenses**, to analyze a **strong lensing system identified in the DESI Legacy Imaging Surveys**. My task involved **reconstructing the surface brightness** and m**ass distributions of the lens and source galaxy** using image data from the **Hubble Space Telescope (HST)**.

I began by carefully **masking out residuals**, such as those caused by nearby stars or galaxies, to keep only the lensing of the source galaxy. I then built **models for both the lensing galaxy and the source galaxy**, using **particle swarm optimization (PSO)** to obtain initial best-fit results. To refine these parameters, I employed **Markov Chain Monte Carlo (MCMC)** methods, **iteratively improving the model’s accuracy** until achieving satisfactory convergence. 

Despite my efforts and additional help from my supervisor and peers, **reconstructing the source galaxy proved challenging due to the complexity of the system**, and the case was ultimately discarded as unsuitable for further modeling. However, my contributions to the data preparation, modeling, and parameter optimization were acknowledged in the resulting article. 

The outcomes of this project included key findings about the **relationships between the mass and light distributions of elliptical galaxies and their local environments**. These findings **provided valuable insights into dark matter theories and the interplay between galaxy structure and environmental factors**. 

Project link:
https://www.astrobridge.org/projects/bdlensing

Article link:
https://www.aanda.org/articles/aa/full_html/2025/07/aa53239-24/aa53239-24.html
