# AI Functional Emotion

Colab notebooks and saved artifacts for emotion-vector experiments with Mistral 7B.

## Notebooks

- `notebooks/01_truthfulqa_failure_emotion_vectors.ipynb`
  - sample 150 TruthfulQA rows
  - benchmark Mistral 7B
  - build success/failure middle-layer vectors
  - sample emotion sentences
  - extract emotion vectors
  - fit failure direction as a non-negative mixture of emotion vectors

## Artifact layout

Runtime outputs are written under `/content/ai_functional_emotion_outputs` in Colab.
Copy or commit the saved CSV/JSON/PT files you want to preserve.

