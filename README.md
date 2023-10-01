MicrobiomeStat: Supporting Longitudinal Microbiome Analysis in R
================

<p align="center" style="margin:0; padding:0;">
<img src="man/figures/logo.png" alt="MicrobiomeStat Logo" width="400" style="margin:0; padding:0;"/>
</p>
<!-- badges: start -->

[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/MicrobiomeStat)](https://cran.r-project.org/package=MicrobiomeStat)
[![Downloads](https://cranlogs.r-pkg.org/badges/grand-total/MicrobiomeStat)](https://cran.r-project.org/package=MicrobiomeStat)
[![License: GPL
v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
<!-- badges: end -->

The `MicrobiomeStat` package is a dedicated R tool crafted with an
emphasis on exploring **longitudinal microbiome data**. While it also
offers the flexibility to engage with multi-omics data and
cross-sectional studies, its essence is enriched by the facilitation of
longitudinal analysis. This attribute aims to support researchers
navigating through extensive biological inquiries over time.

# Citations

## General Citation for MicrobiomeStat

If you are using features beyond the `linda` and `linda.plot` functions,
please cite as follows, until a preprint version is published:

    @Manual{,
      title = {MicrobiomeStat: Comprehensive Statistical and Visualization Methods for Microbiome and Multi-Omics Data},
      author = {Xianyang Zhang and Jun Chen and Caffery(Chen) Yang},
      year = {2023},
      note = {R package version 1.1.1},
      url = {https://www.microbiomestat.wiki},
    }

## Citation for Specialized `MicrobiomeStat` Functions

If you are using the `linda`, `linda.plot`,
`generate_taxa_association_test_long`, `generate_taxa_test_pair`,
`generate_taxa_test_single`, or `generate_taxa_trend_test_long`
functions, please cite the following paper:

    @article{zhou2022linda,
      title={LinDA: linear models for differential abundance analysis of microbiome compositional data},
      author={Zhou, Huijuan and He, Kejun and Chen, Jun and Zhang, Xianyang},
      journal={Genome biology},
      volume={23},
      number={1},
      pages={1--23},
      year={2022},
      publisher={BioMed Central}
    }

We will update the citation guidelines as soon as the preprint is
published.

## Important Note on CRAN Version

Due to the **ongoing development cycle**, the **most up-to-date
features** of `MicrobiomeStat` have **not yet been uploaded to the CRAN
repository**. The current CRAN version **only supports the `linda` and
`linda.plot` functions**. If you **require additional functionalities**,
particularly for **analyzing longitudinal data**, we recommend
**installing the development version from GitHub**. To do this, you’ll
first need to **install the `devtools` package** if you haven’t already:

``` r
install.packages("devtools")
```

Once `devtools` is installed, you can install `MicrobiomeStat` from
GitHub using the following command:

``` r
devtools::install_github("cafferychen777/MicrobiomeStat")
```

# Table of Contents

1.  [Citations](#citations)
    - [General Citation for MicrobiomeStat](#general-citation)
    - [Citation for Specialized `MicrobiomeStat`
      Functions](#specialized-citation)
    - [Important Note on CRAN Version](#cran-version-note)
2.  [Online Tutorials](#online-tutorials)
    - [Acquaint Yourself for a Seamless Experience](#acquaint-yourself)
    - [Discovering MicrobiomeStat](#explore-microbiomestat)
      - [Feature Exploration](#feature-exploration)
      - [Acknowledgements](#acknowledgements)
3.  [Benefits of Using MicrobiomeStat](#why-choose-microbiomestat)
    - [User Support](#user-support)
    - [Ongoing Development](#ongoing-development)
    - [Collaborative Development](#collaborative-development)
    - [Conclusion and Features](#conclusion)
    - [Demo Reports](#demo-reports)
4.  [Assistance & Contact Information](#support-contact)
5.  [Engage in Our Discord Community](#discord-community)
6.  [Share and Connect](#share-and-connect)

# Online Tutorials

`MicrobiomeStat` offers a **supportive toolkit** for microbiome data
analysis, providing a range of capabilities from data input to
visualization.

To **familiarize** yourself with `MicrobiomeStat`, we invite you to
explore our detailed online tutorial using GitBook. This tutorial
includes:

- **Step-by-Step Installation and Configuration Guidance**
  - Help ensure your setup is correct and optimized.
- **Analysis Walkthroughs Inspired by Real-World Cases**
  - Gain practical insights and skills.
- **Hands-On Code Examples**
  - Get acquainted with `MicrobiomeStat` coding practices.
- **Guides on Result Interpretation and Visualization**
  - Learn to understand and present your data effectively.
- **Frequently Asked Questions**
  - Quickly find answers to common queries.

## Acquaint Yourself for a Seamless Experience

For a seamless experience with `MicrobiomeStat`, make the most of these
enriching resources:

[**📘 Explore MicrobiomeStat
Tutorials**](https://www.microbiomestat.wiki)

## Discovering MicrobiomeStat

The realm of microbiome research is intricate and continually advancing.
The analytical tools selected can play a crucial role in navigating
through the research journey. In this scenario, `MicrobiomeStat` aims to
be a supportive companion.

### Feature Exploration

To better understand the capabilities of `MicrobiomeStat`, we have
outlined its features and functionalities on our website, along with
some contextual references to other tools for a more informed
perspective:

- [Exploring Longitudinal Analysis
  Features](https://www.microbiomestat.wiki/introduction/unveiling-microbiomestat-a-glimpse-into-diverse-microbiome-analysis-solutions/exploring-longitudinal-analysis-features-microbiomestat-among-other-packages)

- [Exploring Integrated Analysis
  Features](https://www.microbiomestat.wiki/introduction/unveiling-microbiomestat-a-glimpse-into-diverse-microbiome-analysis-solutions/exploring-feature-offerings-microbiomestat-among-integrated-analysis-packages)

### Acknowledgements

We stand on the shoulders of giants with `MicrobiomeStat`, and our
heartfelt gratitude goes out to the diligent and brilliant developers of
the dependencies that our package relies on. Their remarkable efforts
have not only made our work possible but have also significantly
elevated the standards of computational tools available to the
scientific community:

- **Core Dependencies:**
  - R (\>= 3.5.0), rlang, tibble
- **Imported Packages:**
  - ggplot2, matrixStats, parallel, ggrepel, lmerTest, foreach, modeest,
    vegan, dplyr, pheatmap, tidyr, ggh4x, ape, GUniFrac, scales,
    stringr, broom
- **Suggested Packages:**
  - rmarkdown, knitr, ggprism, aplot, philentropy, forcats, pander,
    tinytex

Furthermore, we extend our deepest appreciation and respect to the
trailblazers in the microbiome research community who have created and
maintained the following remarkable tools. Their pioneering work has
laid down paths through the complex landscape of microbiome data
analysis, and we are truly honored to walk alongside:

- **microbiomeutilities**, **phyloseq**, **microbiomemarker**,
  **MicrobiomeAnalyst**, **microbiomeeco**, **EasyAmplicon**, **STAMP**,
  **qiime2**, and **MicrobiotaProcess**

Their contributions inspire us to continue improving and expanding the
capabilities of `MicrobiomeStat`, and we sincerely hope our humble
addition proves to be a useful complement to the incredible array of
tools already available to researchers.

### User Support

`MicrobiomeStat` is designed with users in mind. Comprehensive
[**documentation and tutorials**](https://www.microbiomestat.wiki/) are
available to assist both novice and experienced researchers. Before
posting a question or issue, we encourage users to [check previous
questions and
issues](https://github.com/cafferychen777/MicrobiomeStat/issues?q=is%3Aissue+is%3Aclosed)
to see if the topic has already been addressed. If not, feel free to
[open a new issue on
GitHub](https://github.com/cafferychen777/MicrobiomeStat/issues). We are
here to help you navigate any challenges you may encounter.

### Ongoing Development

Ensuring that `MicrobiomeStat` remains a leading tool in its category
requires **ongoing development**. We’re dedicated to regular updates and
addressing user feedback.

### Collaborative Development

`MicrobiomeStat` is an open-source tool, and we highly value
contributions from the community. If you have suggestions, improvements,
or feedback for future development directions and feature additions,
**[pull
requests](https://github.com/cafferychen777/MicrobiomeStat/pulls) are
welcomed**, and you can also share your ideas in the [**discussion
area**](https://github.com/cafferychen777/MicrobiomeStat/discussions) of
our GitHub repository. Engage with other community members and help us
make `MicrobiomeStat` an even more useful tool for microbiome research.

### Conclusion

`MicrobiomeStat` aspires to be a **reliable and efficient tool** for
microbiome data analysis. For those who cherish **open-source
collaboration**, we warmly invite you to join our community and
contribute to its continuous enhancement.

| **Feature**                                                                                                                                                                                 | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **[Data Import and Conversion](https://www.microbiomestat.wiki/setting-up-microbiomestat-installation-and-data-preparation/laying-the-foundation-creating-the-microbiomestat-data-object)** | Supports numerous input formats from popular tools like **[QIIME2](https://www.microbiomestat.wiki/setting-up-microbiomestat-installation-and-data-preparation/laying-the-foundation-creating-the-microbiomestat-data-object/importing-data-from-qiime2-into-microbiomestat), [Mothur](https://www.microbiomestat.wiki/setting-up-microbiomestat-installation-and-data-preparation/laying-the-foundation-creating-the-microbiomestat-data-object/fetching-data-from-mothur-into-microbiomestat), [DADA2](https://www.microbiomestat.wiki/setting-up-microbiomestat-installation-and-data-preparation/laying-the-foundation-creating-the-microbiomestat-data-object/integrating-data-from-dada2-into-microbiomestat), [Phyloseq](https://www.microbiomestat.wiki/setting-up-microbiomestat-installation-and-data-preparation/laying-the-foundation-creating-the-microbiomestat-data-object/navigating-data-from-phyloseq-into-microbiomestat)** and more |
| **[Cross-sectional Study Analysis](https://www.microbiomestat.wiki/cross-sectional-study-design/unraveling-cross-sectional-studies-with-microbiomestat)**                                   | Performs comprehensive analysis of **cross-sectional studies**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **[Paired Sample Analysis](https://www.microbiomestat.wiki/paired-samples-analysis/unveiling-paired-samples-analysis-a-comprehensive-guide)**                                               | Excellent tool for analyzing **paired samples**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **[Longitudinal Study Analysis](https://www.microbiomestat.wiki/longitudinal-study-design/grasping-longitudinal-studies-introduction-and-dataset-overview)**                                | Allows for exploring the **temporal dynamics** of the microbiome                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **One-Click Report Generation**                                                                                                                                                             | Generates **professional analysis reports** with a single click for [**cross-sectional**](https://www.microbiomestat.wiki/cross-sectional-study-design/cross-sectional-reporting-microbial-analysis-reports-with-microbiomestat), [**paired**](https://www.microbiomestat.wiki/paired-samples-analysis/automated-reporting-for-paired-studies-microbiomestats-integrated-analysis-reports), [**longitudinal**](https://www.microbiomestat.wiki/longitudinal-study-design/longitudinal-reporting-microbiome-analysis-automation-with-microbiomestat) study designs                                                                                                                                                                                                                                                                                                                                                                                       |
| **Visualization Capabilities**                                                                                                                                                              | Offers a wide variety of **visualization styles**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Ongoing Development**                                                                                                                                                                     | Continual **feature refinement** and **new functionality addition**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

This approach ensures that users can effortlessly navigate to the
specific sections of the `MicrobiomeStat` documentation, garnering
detailed information and guidelines for diverse analysis types. The
structure and accessibility assist users in leveraging `MicrobiomeStat`
effectively for their microbiome data analysis needs.

### Demo Reports

For those interested in seeing `MicrobiomeStat` in action, we have
prepared demo reports tailored to different study designs:

- [Cross-sectional Study Design: Reporting Microbial Analysis with
  MicrobiomeStat](https://www.microbiomestat.wiki/cross-sectional-study-design/cross-sectional-reporting-microbial-analysis-reports-with-microbiomestat)
- [Paired Samples Analysis: Reporting Microbial Analysis with
  MicrobiomeStat](https://www.microbiomestat.wiki/paired-samples-analysis/automated-reporting-for-paired-studies-microbiomestats-integrated-analysis-reports)
- [Longitudinal Study Design: Microbiome Analysis Automation with
  MicrobiomeStat](https://www.microbiomestat.wiki/longitudinal-study-design/longitudinal-reporting-microbiome-analysis-automation-with-microbiomestat)

We encourage you to explore these examples and discover the powerful
capabilities of our tool.

## Assistance & Contact Information

For assistance or inquiries, feel free to reach out to:

| Name                                                                         | Email                       |
|------------------------------------------------------------------------------|-----------------------------|
| [Dr. Jun Chen](https://scholar.google.com/citations?user=gonDvdwAAAAJ&hl=en) | <Chen.Jun2@mayo.edu>        |
| [Chen Yang](https://cafferyyang.owlstown.net/)                               | <cafferychen7850@gmail.com> |

## Engage in Our Discord Community

Join our Discord community to stay on top of the latest updates,
developments, and enhancements in `MicrobiomeStat`. Be part of vibrant
discussions, ask questions, share insights, and avail support from peers
and experts alike:

[Join the MicrobiomeStat Discord Server!](https://discord.gg/BfNvTJAt)

In our Discord server, an automated bot keeps you informed about every
package and tutorial update, ensuring you never miss out on new
features, improvements, and learning materials. Our active community
thrives on **collaboration, feedback, and continuous learning**, making
it an invaluable space for both novice and experienced researchers
navigating the world of microbiome data analysis. Stay connected, stay
informed, and let’s advance the field of microbiome data analysis
together!

## Share and Connect

Spread the word about `MicrobiomeStat` and stay connected through
various platforms!

[![Twitter](https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&style=social)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&text=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![Facebook](https://img.shields.io/badge/Share_on-Facebook-1877F2?logo=facebook&style=social)](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&quote=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![LinkedIn](https://img.shields.io/badge/Share_on-LinkedIn-0077B5?logo=linkedin&style=social)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&title=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![Reddit](https://img.shields.io/badge/Share_on-Reddit-FF4500?logo=reddit&style=social)](https://www.reddit.com/submit?url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&title=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![WhatsApp](https://img.shields.io/badge/Share_on-WhatsApp-25D366?logo=whatsapp&style=social)](https://wa.me/?text=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!%20https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat)

[![Slack](https://img.shields.io/badge/Share_on-Slack-4A154B?logo=slack&style=social)](https://slack.com/intl/en-cn/)

[![Email](https://img.shields.io/badge/Share_on-Gmail-D14836?logo=gmail&style=social)](mailto:?subject=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!&body=I%20found%20this%20amazing%20R%20package%20for%20microbiome%20analysis%20called%20%60MicrobiomeStat%60.%20Check%20it%20out%20here:%20https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat)
