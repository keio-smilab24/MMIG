# Mobile Manipulation Instruction Generation from Multiple Images with　Automatic Metric Enhancement

This repository contains the code for the paper Mobile Manipulation Instruction Generation from Multiple Images with
Automatic Metric Enhancement (RA-L 2025)

Kei Katsumata, Motonari Kambara, Daichi Yashima, Ryosuke Korekata and Komei Sugiura

We consider the problem of generating free-form mobile manipulation instructions based on a target object image and receptacle image.
Conventional image captioning models are not able to generate appropriate instructions because their architectures are typically optimized for single-image.
In this study, we propose a model that handles both the target object and receptacle to generate free-form instruction sentences for mobile manipulation tasks.
Moreover, we introduce a novel training method that effectively incorporates the scores from both learning-based and n-gram based automatic evaluation metrics as rewards.
This method enables the model to learn the co-occurrence relationships between words and appropriate paraphrases. 
Results demonstrate that our proposed method outperforms baseline methods including representative multimodal large language models on standard automatic evaluation metrics.
Moreover, physical experiments reveal that using our method to augment data on language instructions improves the performance of an existing multimodal language understanding model for mobile manipulation.
