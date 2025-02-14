# LoRA Fine-Tuning of FLAN-T5 for English-to-German Translation  

## 📌 Overview  
This project demonstrates **LoRA fine-tuning** of the **FLAN-T5-small** model for **English-to-German translation** using the **WMT16 dataset**. Instead of fine-tuning the entire model, we apply **Low-Rank Adaptation (LoRA)** to efficiently train only a subset of parameters, reducing computational cost and memory usage.  

## 🚀 Features  
- Uses **FLAN-T5-small** for sequence-to-sequence translation.  
- Implements **LoRA (Low-Rank Adaptation)** for efficient training.  
- Trains on the **WMT16 English-German** dataset.  
- Evaluates translations using **BLEU score**.  

## 📂 Dataset  
The **WMT16 (de-en)** dataset is loaded from the **Hugging Face Datasets** library.  


## 📊 Performance Evaluation  
- The model's translations are compared with reference texts using **BLEU score**.  
- The BLEU score is calculated using `nltk.translate.bleu_score`.  

## 💡 Results  
- The fine-tuned model achieves **significant improvements** with **fewer trainable parameters**.  
- LoRA fine-tuning speeds up training while maintaining high translation accuracy.  

## 🛠 Future Improvements  
- Experiment with **different LoRA ranks** to balance efficiency and performance.  
- Fine-tune larger FLAN-T5 models (**base, large**) for better accuracy.  
- Apply **LoRA to other NLP tasks** like summarization or sentiment analysis.  

## 🤝 Contributing  
Feel free to fork this repo, open issues, or submit pull requests!  

## 📜 License  
This project is licensed under the **MIT License**.  
