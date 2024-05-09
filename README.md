# Comparative Analysis of Summarization Models on Amazon Fine Food Reviews

## Introduction
This project centers on evaluating the summarization abilities of four selected Language Models (LLMs) using the Amazon Fine Food Reviews dataset from Kaggle. The main objective is to assess which models deliver the most precise and succinct summaries of customer reviews. This analysis aims to enhance comprehension of consumer sentiments and product evaluations.

## Project Status
**Note**: This project is currently in progress. Updates on results and findings will be shared as they become available. (expected date: May, 2024)

## Methodology
### Dataset
The dataset employed is the [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews), which includes detailed reviews from Amazon customers spanning from October 1999 to October 2012.

### Models Under Comparison
1. **GPT-2**: It tends to generate creative and expansive text, which may occasionally diverge from the expected summarization focus.
2. **T5-BASE**: T5 provides concise and relevant summaries, focusing directly on the key elements of the input text.
1. **BART-LARGE**: BART excels in generating detailed and contextually rich summaries, closely aligning with the nuances of the source content.
2. **FALCONSAI/TEXT-SUMMARIZATION**: FalconSAI offers targeted summaries that pinpoint critical issues, but it may omit some contextual details for brevity.

The performance of these models will be evaluated based on precision, recall, and the F1 score using the ROUGE metric.

### Fine-Tuning (WIP)
Models are fine-tuned using an NVIDIA RTX A4000 to leverage its robust computational capabilities, ensuring efficient processing of the large dataset.

## Technology Stack
- **Languages**: Python
- **Libraries**: Transformers, PyTorch, TensorFlow, Scikit-learn
- **Hardware**: NVIDIA RTX A4000
- **Tools**: Jupyter Notebook

## Contributing
Feel free to fork the repository and submit pull requests with enhancements or fixes.

## Contact
For queries or suggestions, reach out via [mail](mailto:sde.tusharchandra@gmail.com).

---