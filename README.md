# Weather Report LLM Fine-Tuning

This project fine-tunes the pre-trained Mistral-7B LLM for weather reporting using real-world data from NWS and NOAA.  
Key tasks include weather alert classification and generating human-readable summaries.  

The model is trained with PyTorch using Parameter-Efficient Fine-Tuning (PEFT) and LoRA for low-resource hardware.  
Evaluation metrics achieved 88.2% accuracy (15.8% gain over baseline) and a 20 BLEU score for generated summaries, demonstrating effective domain adaptation.
