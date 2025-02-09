# Empirical Evaluation of Pre-trained Language Models for Summarizing Moroccan Darija News Articles

# GOOD-Sum_v2: Moroccan Darija Summarization Dataset  

## 📖 Description  
GOOD-Sum_v2 is an expanded version of the original GOOD-Sum dataset [Goud-sum](https://huggingface.co/datasets/Goud/Goud-sum), designed for **Moroccan Darija text summarization**. It contains a large collection of **news articles** with their **headlines** and **categories**, sourced from **GOUD.ma**, one of Morocco’s leading news websites.  

The dataset is useful for **text summarization, sentiment analysis, and language modeling** for Moroccan Darija, a low-resource Arabic dialect.  

## 📊 Dataset Details  
- **Total Articles**: 208,000  
  - **Training Set**: 189,000 articles  
  - **Validation Set**: 9,497 articles  
  - **Test Set**: 9,497 articles  
- **Languages**: Moroccan Darija, Modern Standard Arabic (MSA), or a mix of both  
- **Data Fields**:  
  - **Headline**: The news article's title (used as a reference summary)  
  - **Content**: The full text of the article  
  - **Category**: The topic classification of the article (e.g., news, sports, politics)  

## 🏆 Benchmark Models
We evaluated various pre-trained language models for Moroccan Darija summarization, including:

- **Arabic-Specific Models**: AraBERT, DarijaBERT, DziriBERT
- **Multilingual Models**: mBART, mT5
- **Causal Language Models**: GPT-based models (Llama 3 vs Mistral NeMo vs GPT-4o mini=

## 🔗 Access the Dataset
The dataset is also available on Hugging Face: [https://huggingface.co/datasets/azzedine/Goud-sum_v2](https://huggingface.co/datasets/azzedine/Goud-sum_v2)

## 📜 Citation

```bibtex
@inproceedings{aftiss2025empirical,
  title={Empirical Evaluation of Pre-trained Language Models for Summarizing Moroccan Darija News Articles},
  author={Aftiss, Azzedine and Lamsiyah, Salima and Schommer, Christoph and El Alaoui, Said Ouatik},
  booktitle={Proceedings of the 4th Workshop on Arabic Corpus Linguistics (WACL-4)},
  pages={77--85},
  year={2025}
}
