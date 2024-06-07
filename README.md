![A poster displaying the talk title, "Fair machine learning," as well as my name and username. Beside the text is a set of six hexagonal logos, showing hex stickers for selected tidymodels packages.](figures/hero.png)

This repository contains source code and slides for the talk "Fair machine learning" at [Cascadia R Conf](https://cascadiarconf.org/) in June 2024.

* The **slides** for the talk are available [here](https://simonpcouch.github.io/cascadia-24).
* The example analysis **Are GPT detectors fair?** is available [here](https://www.tidymodels.org/learn/work/fairness-detectors/).
* The example analysis **Fair prediction of hospital readmission** is [here](https://www.tidymodels.org/learn/work/fairness-readmission/).

To learn more about data science and machine learning with R,

- Data science with the tidyverse: [r4ds.hadley.nz](r4ds.hadley.nz)
- Machine learning with tidymodels: [tmwr.org](tmwr.org)
- More example notebooks with tidymodels: [tidymodels.org](tidymodels.org)

----

To install the packages needed to run this code yourself, use the following R code:

```r
# if needed:
install.packages("tidymodels", "detectors")
```

----

In this repository,

-   `index.qmd` contains the source code for the slides. The slides use images in the `/figures` directory.
-   `/docs` is auto-generated from `index.qmd`. Content in that folder is likely unhelpful for a human reader, and is better viewed at the links above. :)
