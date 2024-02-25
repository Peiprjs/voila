# Interactive dashboard from notebook with Voilà


| Voilà |
| :---------------------: |
| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Peiprjs/voila/HEAD?urlpath=voila%2Ftree%2Fnotebooks) |

| JupyterLab |
| :---------------------: |
| [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Peiprjs/voila/HEAD?urlpath=lab%2Ftree%2Fnotebooks) |


This example demonstrates how to use [Voilà](https://github.com/voila-dashboards/voila) on Binder.

Original code found on [this repository](https://github.com/binder-examples/voila)

## Configuration

If you would like to use the same configuration as this repository but for another project, check out the following steps:

1. Make sure the repository is publicly available (on GitHub, Gitlab or as a [GitHub Gist](https://gist.github.com)
2. Define the dependencies in [`environment.yml`](./environment.yml). `requirements.txt` is also supported. In the dependency file, add `voila`.
3. Edit the README file and change the Binder url to https://mybinder.org/v2/gh/YOUR-USERNAME/voila/HEAD?urlpath=voila%2Ftree%2Fnotebooks where you replace YOUR-USERNAME by your actual github username (you can find it in the link in the address bar in your own repository).

For more details, check out the Voilà documentation on https://voila.readthedocs.io/en/latest/deploy.html#deployment-on-binder

## TASKS
**Introduction: (5 pt)**
- [ ] Formulate a research question that allows for explorations and comparisons. For example: How have vaccinations influenced hospitalizations in different European Union (EU) countries? You can divide this in two steps: 1. How vaccinations have influenced hospitalizations in a country (i.e Netherlands or Italy); 2. How does one country compare to the other countries in the EU? (5 pt)

**Data preparation: (20 pt)**
- [X] Load the dataset using this link for health factors dataLinks to an external site.. Copy the link and load it as you did in the practicals. (5 pt)
- [X] Select rows and columns relevant to your research question. (15 pt)

**Explore and clean the data by: (20 pt)**
- [X] Exploring data using descriptive statistics or visualisations to get to know the dataset and spot possible issues (such as outliers or typos)(10 pt)
- [X] Identify and report issues with missing data. (5 pt)
- [X] Resolve issues with missing data and clean other data inconsistencies. Report also if you found no issues and how you verified this. (5 pt)

**Describe and visualise: (50 pt)**
- [ ] Provide a description of the population for the reader (e.g. countries or continents) relevant to your question using a table with descriptive statistics (i.e. means, medians, standard deviations) and where possible visualisation. (15pt)
- [ ] Make the report interactive: Create at least one interactive visualisation using input from the user. (20pt)
- [ ] Turn your interactive report into an application using GitHub, Voila and Binder.** (15pt)

**Conclusion: (5 pt)**
- [ ] Summarise the work and the main findings related to the initial research question. (5 pt)
