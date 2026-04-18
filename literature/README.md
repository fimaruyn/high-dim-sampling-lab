# Literature Library

This directory houses a curated collection of over 300 scholarly articles, monographs, and conference proceedings pertaining to high-dimensional sampling methods. The scope of this library encompasses:

- **Theoretical Foundations:** Digital $(t, m, s)$-nets, low-discrepancy sequences, and discrepancy theory.
- **Verification & Analysis:** Algorithms for verifying the quality parameter $t$, linear complexity profiles, and correlation analysis (PCA).
- **Stochastic Methods:** Markov Chain Monte Carlo (MCMC), Sequential Monte Carlo (SMC), and adaptive sampling strategies.
- **Advanced Intersections:** Hybrid QMC-MCMC approaches, optimal transport theory, Wasserstein gradient flows, and machine learning applications in sampling.

## Directory Structure

The library is organized thematically to facilitate efficient research and cross-referencing:

- **`01_fundamentals`**: Core monographs (e.g., Dick & Pillichshammer, Kuipers & Niederreiter) and comprehensive surveys establishing the mathematical basis of uniform distribution.
- **`02_digital_nets_theory`**: Theoretical underpinnings of net construction, duality theory, algebraic constructions, and existence proofs.
- **`03_verification_and_properties`**: Literature focused on quality assurance, including $t$-parameter verification, linear complexity, and statistical tests. *Contains primary works by the project author.*
- **`04_specific_sequences`**: Detailed studies on specific generator types, including Sobol', Halton, Faure, and inversive congruential sequences.
- **`05_algebraic_geometry_constructions`**: Advanced construction methodologies utilizing global function fields and algebraic geometry.
- **`06_polynomial_lattice_rules`**: Research on lattice rules, component-by-component (CBC) construction algorithms, and polynomial lattices.
- **`07_applications`**: Practical implementations in computational finance, global optimization, physics simulations, and sensitivity analysis.
- **`08_mcmc_and_hybrid_methods`**: Integration of deterministic and stochastic methods, including adaptive Metropolis-Hastings algorithms and hybrid schemes.
- **`09_sequential_monte_carlo`**: Particle filtering, state-space models, and sequential sampling techniques.
- **`10_advanced_topics_ml_transport`**: Contemporary research at the intersection of sampling, machine learning, neural networks, and optimal transport.
- **`11_misc_and_theses`**: Miscellaneous papers, doctoral dissertations, and technical reports.

## Usage Guidelines

1.  **Navigation:** Utilize the [`INDEX.md`](INDEX.md) file to locate specific publications by title, author, or topic. Update the reading status indicators (`[ ]` to `[x]`) as you progress through the literature.
2.  **Citation Management:** All bibliographic metadata is consolidated in the [`../bibliography.bib`](../bibliography.bib) file. Reference entries using their unique BibTeX keys within LaTeX documents (e.g., `\cite{dick2010digital}`).
3.  **Adding New Entries:**
    - Download the PDF into the appropriate thematic subdirectory.
    - Extract and append metadata to `bibliography.bib` via a reference manager (e.g., Zotero, JabRef) or manual entry.
    - Update `INDEX.md` with the new file path and initial status.
4.  **Copyright Notice:** These materials are provided strictly for personal academic research and educational purposes. Redistribution of copyrighted full-text PDFs is prohibited. Users should adhere to the licensing terms of respective publishers (Elsevier, Springer, IEEE, Cambridge University Press, etc.).
