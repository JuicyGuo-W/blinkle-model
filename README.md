# blinkle-model
A lightweight NLP pipeline for extracting structured information (task, impact, domain keywords, tools, numerics) from resumes and job descriptions using LLMs with LoRA-based fine-tuning. Supports zero-, few-, and multi-shot inference, enabling resume tailoring, summarization, and scoring.

	This project aims to extract structured insights from unstructured job and resume texts for downstream tasks like summarization, resume customization, and scoring.
Using PEFT (LoRA) techniques and base models such as FLAN-T5 and LLaMA, we train and evaluate prompt-based extraction performance across multiple shots.
The pipeline supports automatic labeling, data preprocessing, and instruction-output generation from both JD and resume sources.
