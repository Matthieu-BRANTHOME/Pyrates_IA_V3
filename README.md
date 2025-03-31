This repository includes the supplementary material and code for the analysis titled: "Impact of Adaptive Feedback on Learning Programming with a Serious Game in High Schools’ Classes".

The experimental data are gathered in the ./data folder.

- The format of the raw data file name is: <schooltag>_raw_<datatype>.csv, with schooltag indicating the code of the high school where the data were acquired (cer or lan), and datatype the data modality (pre-test, post-test and sessions).

The cleaned and consolidated data are in the same ./data folder and can be directly used for the analysis:

- cleaned_data_pre-test.xlsx includes the pre-test score
- cleaned_data_post-test.xlsx includes the post-test scores and usability survey answers
- cleaned_data_interaction.xlsx includes the logged in-game actions of all students

The data cleaning and analysis are in the UMAP_data_analysis.ipynb Jupyter Notebook, which includes the documentation, code and results.

If you reuse parts of our data and code, please cite the following paper:

- Matthieu Branthôme and Sébastien Lallé. 2025. Impact of Adaptive Feedback on Learning Programming with a Serious Game in High Schools’ Classes. In Proceedings of ACM International Conference on User Modeling, Adaptation
  and Personalization (UMAP '25). ACM, New York, NY, USA.
