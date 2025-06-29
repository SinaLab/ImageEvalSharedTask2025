
# 🖼️ [Arabic Image Captioning Shared Task 2025](https://sina.birzeit.edu/image_eval2025/index.html)

This repository contains official baselines for the **Arabic Image Captioning Shared Task 2025**, which aims to advance the development of culturally aware Arabic image captioning models. The task provides an Arabic-language dataset and invites participants to generate natural captions for images using zero-shot or fine-tuned approaches. This repository includes two baseline systems using Qwen2.5-VL 7B, along with an evaluation script.

## 📂 Contents

- A zero-shot baseline for generating captions using Qwen2.5-VL 7B without fine-tuning.
- A fine-tuned baseline using Qwen2.5-VL 7B trained on the provided Arabic-captioned training set.
- An evaluation script to compare predictions with ground truth using the official metrics (BLEU, ROUGE, Cosine Similarity,and LLM as a Judge).

## 📊 Dataset

The dataset comprises approximately 3471 images with Arabic captions. It is divided into:

- **Training Set**: about 2718 images (for fine-tuning)
- **Test Set**: about 753 images (for evaluation)

The dataset is shared via Google Drive with registered participants. To access, teams must register through [the official registration form](https://docs.google.com/forms/d/e/1FAIpQLSfBqpu8badMfm_IgsLqVGAfmWiXHS_56ntPsWMN77nbB1ENw/viewform)
 
## 🧪 Running the Baselines

This repository provides two baseline systems, implemented in the following notebook files. You can run them using Colab Pro for less than 10$.

 **Zero-Shot Inference** (`ImageValZeroShot.ipynb`):  
   Directly generates Arabic captions from images using Qwen2.5-VL in a zero-shot setting.

**Fine-Tuning** (`ImageValFinetune.ipynb`):  
   Fine-tunes Qwen2.5-VL on the provided training data (3,000 images), then generates captions for the test set.

## 📏 Evaluation

The evaluation script (`EvaluationScriptImageVal.ipynb`) computes performance on the test set using the following metrics:

- BLEU (Bilingual Evaluation Understudy)
- ROUGE (Recall-Oriented Understudy for Gisting Evaluation)
- Cosine Similarity
- LLM as a Judge

  


## 📬 Contact

For any questions or support:

- Email: imageeval2025@gmail.com

