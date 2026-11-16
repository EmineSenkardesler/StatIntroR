# StatIntroR

Animated, step-by-step walkthroughs of statistical methods in R, built for CPSC 442 (Fall 2026). Each page uses the real data, seeds and results from the course materials.

**Live site:** https://eminesenkardesler.github.io/StatIntroR/

| Page | What it covers |
|---|---|
| [PCA, step by step](https://eminesenkardesler.github.io/StatIntroR/pca/) | Scaling, finding PC1 and PC2, eigenvalues, the scree plot, scores and loadings, on the Romano-British pottery data |
| [Experimental design, step by step](https://eminesenkardesler.github.io/StatIntroR/experimental-design/) | Completely randomized, randomized complete block, Latin square and split-plot designs, Hasse diagrams, contrast coding and planned contrasts |

Use Next and Back or the arrow keys to move through the steps. Adding `#step-3` to a page's address opens step 3 directly.

## Data

- `RBPottery`, from the `archdata` R package
- `cochran.latin` and `stroup.splitplot`, from the `agridat` R package
- Rat liver weights, fern (cycad) mealybug counts and the drug crossover square, from the CPSC 442 course files

Layouts for the design pages come from the `agricolae` R package with the same seeds as the course code. ANOVA and PCA numbers come from `lm()`, `aov()` and `FactoMineR::PCA()` on these data.

## Files

Each walkthrough is one self-contained HTML file:

- `pca/index.html`
- `experimental-design/index.html`

To use them offline, download the repository and open either file in a browser.
