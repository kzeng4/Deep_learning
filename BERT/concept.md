# BERT
 ## Architecture
 - multi-layer **bidirectional transformer encoder**
- two steps in framework: **pre-training** and **fine-tuning**
- note: a distinctive fearture of BERT is its unified architecture across different tasks
  ## Pre-training 
  - train on **unlabeled data** over different tasks
  ## Fine-tuning
  - initialized with the pre-trained parameters
  - fine-tune all of the parameters using **labeled data** from the downstream tasks. (each downstream task has seperate fine-tuned models)
  - ![Screen Shot 2022-04-03 at 4 13 08 PM](https://user-images.githubusercontent.com/95585390/161446594-ee85056e-d266-46d3-a0ba-f2b111751d67.png)
