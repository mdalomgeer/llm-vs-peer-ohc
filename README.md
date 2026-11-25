# Comparing human and LLM responses to patients' online questions

Analysis notebooks for our AMIA 2026 paper:

> Hussein MA, Doshi R, He L, Reynolds TL. Comparing Human and Large Language Model Responses to Patients' Online Questions: Towards Multi-dimensional Patient-centered Support. AMIA Annual Symposium Proceedings. Dallas, TX; 2026.

Preprint: https://www.medrxiv.org/content/10.64898/2026.07.15.26355314v1

The codebook and a worked prompt example are in a separate repository: https://github.com/mdalomgeer/llm-vs-peer-ohc-supplementary

## Notebooks

- `GPTresponse.ipynb`, `Latest_GPTresponse.ipynb`, `GPTresponse_Alomgeer.ipynb`, `GPTResponse_Answers.ipynb`: collecting model responses and computing readability (ARI, SMOG) for model and peer answers
- `ARI_SMOG_Average.ipynb`: averaging the readability scores
- `WordCount_GPTResponses.ipynb`: word counts and comparisons
- `Emotional_Support_Needed.ipynb`, `Emotional_Support_Needed_with_Reasoning.ipynb`: LLM-based labelling of whether a post asks for emotional support
- `Classifier_EmotionalSupport.ipynb`, `NLP_Classifier.ipynb`: classifiers for emotional support

The notebooks were written in Google Colab, so file paths point to `/content/...`.

## Data

The patient questions, peer answers and model outputs are not in this repository and all notebook outputs have been cleared. We do not redistribute the data, to respect the source platform's terms and the study's data-use conditions.

## API key

Notebooks that call the OpenAI API read the key from the `OPENAI_API_KEY` environment variable.

## Contact

Md Alomgeer Hussein, mdalomh1@umbc.edu
