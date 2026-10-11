# Sentiment and Topic Analysis of Nearpod Feedback

An exploratory data-analysis project that examines feedback associated with the Nearpod learning platform. The notebook combines text analysis and visualization to help surface recurring themes and sentiment patterns in feedback.

## Research questions

- What themes appear repeatedly in the collected feedback?
- What sentiment patterns can be observed in the text?
- How can qualitative feedback be summarized into interpretable signals for further investigation?

## Methods

The notebook brings together several exploratory techniques:

- Data compilation, cleaning, and preprocessing
- Exploratory analysis and visual summaries
- Word-cloud and correlation-matrix visualizations
- Sentiment analysis
- Unsupervised topic modelling with Latent Dirichlet Allocation (LDA) and CorEx
- Thematic interpretation of the discovered patterns

The project is intended as an applied analysis workflow, not as a causal evaluation of an educational intervention.

## Repository contents

| Path | Description |
| --- | --- |
| Sentiment Analysis .ipynb | Main notebook containing preprocessing, analysis, modelling, and visualizations |

## How to explore the notebook

1. Clone or download this repository.
2. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
3. Review the data-loading cells first and make sure any required input data or credentials are available.
4. Run the notebook from top to bottom, checking each transformation and visualization.

The repository currently contains the notebook but does not provide a separate dataset file or a pinned environment specification. The exact setup therefore depends on the data source and libraries used by the notebook.

## Interpretation and limitations

- Topic and sentiment outputs depend on the quality, language, sampling, and preprocessing of the feedback.
- LDA and CorEx identify patterns in text; their topics need human interpretation and are not ground-truth labels.
- Descriptive analysis alone cannot establish that a product change caused an increase in user satisfaction. Any downstream impact claim should be supported by a documented measurement design and evidence.

## Future improvements

- Record the dataset source, collection period, schema, and usage permissions.
- Add a reproducible dependency file and explicit setup instructions.
- Separate preprocessing, modelling, and visualization into reusable functions.
- Evaluate sentiment/topic outputs with documented validation procedures.
- Add representative, privacy-safe figures and summarize findings with clear caveats.

## Technologies

Python · Jupyter Notebook · Pandas · Text Analysis · Sentiment Analysis · LDA · CorEx · Data Visualization
