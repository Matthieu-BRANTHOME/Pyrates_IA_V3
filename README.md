This repository includes the supplementary material and code for the analysis titled: "Impact of Adaptive Feedback on Learning Programming with a Serious Game in High Schools’ Classes" (see reference below). The papers presents a field user study aimed at evaluating the impact of an adaptive feedback system in [Pyrates](https://py-rates.fr), a programming serious game designed to ease the transition from block-based to text-based programming in high school classes.

### Data
The experimental data are gathered in the [./data](data/) folder.

- The format of the raw data file name is: \<schooltag\>_raw_\<datatype\>.csv, with schooltag indicating the code of the high school where the data were acquired (cer or lan), and datatype the data modality (pre-test, post-test and sessions).

The cleaned and consolidated data are in the same [./data](data/) folder and can be directly used for the analysis:

- [cleaned_data_pre-test.xlsx](data/cleaned_data_pre-test.xlsx) includes the pre-test score
- [cleaned_data_post-test.xlsx](data/cleaned_data_post-test.xlsx) includes the post-test scores and usability survey answers
- [cleaned_data_interaction.xlsx](data/cleaned_data_interaction.xlsx) includes the logged in-game actions of all students

The [./tests](tests/) folder includes the study material (pre-test in Scratch, post-test in Python, and survey).

### Code
The data cleaning and analysis are in the [UMAP_data_analysis.ipynb](UMAP_data_analysis.ipynb) Jupyter Notebook, which includes the documentation, code and results.

### Citation
If you reuse parts of our data and code, please cite the following paper:

- Matthieu Branthôme and Sébastien Lallé. 2025. Impact of Adaptive Feedback on Learning Programming with a Serious Game in High Schools’ Classes. In Proceedings of ACM International Conference on User Modeling, Adaptation
  and Personalization (UMAP '25). ACM, New York, NY, USA. DOI: [https://doi.org/10.1145/3699682.3728326](https://doi.org/10.1145/3699682.3728326)


License: BSD 3-Clause.
