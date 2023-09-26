MicrobiomeStat: Comprehensive & Longitudinal Microbiome Analysis in R
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

The `MicrobiomeStat` package is a state-of-the-art R tool with a
**special focus on the analysis of longitudinal microbiome data**. While
capable of handling multi-omics data and cross-sectional studies, its
**core strength lies in its proficiency in longitudinal analysis**. This
makes it an invaluable resource for researchers conducting extensive
biological studies over time.

# Citations

## General Citation for MicrobiomeStat

If you are using features beyond the `linda` and `linda.plot` functions,
please cite as follows, until a preprint version is published:

    @Manual{,
      title = {MicrobiomeStat: Comprehensive Statistical and Visualization Methods for Microbiome and Multi-Omics Data},
      author = {Xianyang Zhang and Jun Chen and Caffery(Chen) Yang},
      year = {2023},
      note = {R package version 1.1.1},
      url = {www.microbiomestat.wiki},
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
3.  [Benefits of Using MicrobiomeStat](#why-choose-microbiomestat)
    - [Comparative Overview](#comparative-overview)
    - [User Support](#user-support)
    - [Ongoing Development](#ongoing-development)
    - [Collaborative Development](#collaborative-development)
    - [Conclusion and Features](#conclusion)
    - [Demo Reports](#demo-reports)
4.  [Assistance & Contact Information](#support-contact)
5.  [Engage in Our Discord Community](#discord-community)
6.  [Share and Connect](#share-and-connect)

# Online Tutorials

`MicrobiomeStat` represents a **comprehensive toolset** for microbiome
data analysis, boasting extensive capabilities from data input to
visualization.

For an **in-depth understanding** of `MicrobiomeStat`, explore our
detailed online tutorial using GitBook. This tutorial covers:

- **Comprehensive Installation and Configuration Guidance**
  - Ensure your setup is correct and optimized.
- **Analysis Walkthroughs Driven by Real-World Cases**
  - Gain practical insights and skills.
- **Hands-On Code Examples**
  - Get comfortable with `MicrobiomeStat` coding practices.
- **Detailed Guides on Result Interpretation and Visualization**
  - Understand and present your data effectively.
- **Frequently Asked Questions**
  - Quickly find answers to common queries.

## Acquaint Yourself for a Seamless Experience

For a seamless experience with `MicrobiomeStat`, make the most of these
enriching resources:

[**📘 Explore MicrobiomeStat
Tutorials**](https://www.microbiomestat.wiki)

## Benefits of Using MicrobiomeStat

The field of microbiome research is complex and rapidly evolving. The
analytical tools chosen can have significant implications for research
outcomes. In this context, `MicrobiomeStat` presents itself as a robust
option.

### Comparative Overview

For a thorough understanding of how `MicrobiomeStat` measures against
other tools, we’ve provided detailed comparisons on our website:

- [Comparison with Other Longitudinal
  Packages](https://www.microbiomestat.wiki/introduction/microbiomestat-versus-the-competition-a-comparative-overview/microbiomestat-vs.-other-longitudinal-packages-an-in-depth-comparison)

- [Comparison with Integrated Analysis
  Packages](https://www.microbiomestat.wiki/introduction/microbiomestat-versus-the-competition-a-comparative-overview/microbiomestat-vs-integrated-analysis-packages-a-feature-comparison)

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

`MicrobiomeStat` aims to be a **reliable and efficient tool** for
microbiome data analysis. For those who value **open-source
collaboration**, we warmly invite you to be part of our community and
contribute to its continuous improvement.

| **Feature**                        | **Description**                                                                                                                          |
|------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| **Data Import and Conversion**     | Supports numerous input formats from popular tools like **QIIME2, Mothur, DADA2, Phyloseq** and more                                     |
| **Cross-sectional Study Analysis** | Performs comprehensive analysis of **cross-sectional studies**                                                                           |
| **Paired Sample Analysis**         | Excellent tool for analyzing **paired samples**                                                                                          |
| **Longitudinal Study Analysis**    | Allows for exploring the **temporal dynamics** of the microbiome                                                                         |
| **One-Click Report Generation**    | For different study designs (**cross-sectional, paired, longitudinal**), generates **professional analysis reports** with a single click |
| **Visualization Capabilities**     | Offers a wide variety of **visualization styles**                                                                                        |
| **Data Export**                    | Supports export of analysis results in **diverse formats**                                                                               |
| **Ongoing Development**            | Continual **feature refinement** and **new functionality addition**                                                                      |
|                                    |                                                                                                                                          |

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

Join our Discord community to stay abreast of the latest developments in
`MicrobiomeStat`, engage in discussions, and avail support:

[Join the MicrobiomeStat Discord Server!](https://discord.gg/BfNvTJAt)

Our active community fosters an environment of **collaboration,
feedback, and continuous learning**.

## Share and Connect

Spread the word about `MicrobiomeStat` and stay connected through
various platforms!

[![Twitter](https://img.shields.io/twitter/url?url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&style=social)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&text=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![Facebook](https://img.shields.io/badge/Share_on-Facebook-1877F2?logo=facebook&style=social)](https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&quote=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![LinkedIn](https://img.shields.io/badge/Share_on-LinkedIn-0077B5?logo=linkedin&style=social)](https://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&title=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![Reddit](https://img.shields.io/badge/Share_on-Reddit-FF4500?logo=reddit&style=social)](https://www.reddit.com/submit?url=https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat&title=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!)

[![WhatsApp](https://img.shields.io/badge/Share_on-WhatsApp-25D366?logo=whatsapp&style=social)](https://wa.me/?text=Check%20out%20this%20awesome%20package%20for%20comprehensive%20and%20longitudinal%20microbiome%20analysis%20in%20R!%20https%3A%2F%2Fgithub.com%2Fcafferychen777%2FMicrobiomeStat)

[![Slack](https://img.shields.io/badge/Share_on-Slack-4A154B?logo=slack&style=social)](https://slack.com/intl/en-cn/)
