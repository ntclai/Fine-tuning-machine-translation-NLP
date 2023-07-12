### General introduction
**Problem:** Machine translation using Transformer architecture model

**Project objectives:** This project will train an existing model on a new dataset new dataset by fine-tuning the weights and hyperparameters, to improve the accuracy and performance of the trained model

**Training model:** (original model)

  - Model name: Helsinki-NLP/opus-mt-en-vi

  - Link (Hugging Face): https://huggingface.co/Helsinki-NLP/opus-mt-en-vi

  - Source (Github): https://github.com/Helsinki-NLP/OPUS-MT-app/

**Training dataset:**

  - Dataset name: mt_eng_vietnamese (iwslt2015-en-vi)
  - Link (Hugging Face): https://huggingface.co/datasets/mt_eng_vietnamese/viewer/iwslt2015-vi-en/train
--- 
### Project result

This model is a fine-tuned version of Helsinki-NLP/opus-mt-en-vi on the mt_eng_vietnamese dataset. It achieves the following results on the evaluation set:

  - Loss: 1.376056

  - Bleu: 34.515300

  - Gen Len: 27.230600

The model after training is saved at: https://huggingface.co/ntclai/en_vi_translation_1

---

### Application
  - Applying model results as a translation website
  - Link: https://translate-hub.vercel.app/

--- 

### Reference
  - https://huggingface.co/docs/transformers/tasks/translation?fbclid=IwAR039-v3EKAUPU6hiim5iTAUoQtE2B_iK_5HY2U7ThR1HlJyeEb30PaUIOU

  - https://github.com/mariaviana21/fine-tuning-machine-translation
