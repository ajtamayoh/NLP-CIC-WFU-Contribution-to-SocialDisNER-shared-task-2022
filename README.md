# NLP-CIC-WFU at SocialDisNER: Disease Mention Extraction in Spanish Tweets Using Transfer Learning and Search by Propagation

Authors:

Antonio Tamayo (ajtamayo2019@ipn.cic.mx, ajtamayoh@gmail.com)

Diego A. Burgos (burgosda@wfu.edu)

Alexander Gelbulkh (gelbukh@gelbukh.com)

For bugs or questions related to the code, do not hesitate to contact us (Antonio Tamayo: ajtamayoh@gmail.com)

If you use this code please cite our work: comming soon.

## Abstract

Named entity recognition (e.g., disease mention extraction) is one of the most relevant tasks for data mining in the medical field. Although it is a well-known challenge, the bulk of the efforts to tackle this task have been made using clinical texts commonly written in English. In this work, we present our contribution to the SocialDisNER competition, which consists of a transfer learning approach to extracting disease mentions in a corpus from Twitter written in Spanish. We fine-tuned mBERT and applied post-processing based on regular expressions to propagate the entities identified by the model and enhance disease mention extraction. Our system achieved a competitive strict F1 of 0.851 on the testing data set.

### How to use our model

Option 1: [Hugging Face Space](https://huggingface.co/spaces/ajtamayoh/NLP-CIC-WFU_SocialDisNER)

Option 2: [Hugging Face Model](https://huggingface.co/ajtamayoh/NLP-CIC-WFU_SocialDisNER_fine_tuned_NER_EHR_Spanish_model_Mulitlingual_BERT_v2)

### How to replicate our experiments

[source code](https://github.com/ajtamayoh/NLP-CIC-WFU-Contribution-to-SocialDisNER-shared-task-2022/blob/main/Code.ipynb)
