## Hateful meme detection
<p align="justify">
Social media in the recent times has become the perpetrator of hateful content,and detecting these elements has never been more relevant than it is now. When we humans look at a meme, we do not separate the image from the text on it. We understand the combined meaning together. An AI tool built to detect hateful memes require that it understands the content and the context like we humans do.  
</p>
<p align="justify">
The project work proposes to solve the problem of automatically classifying memes as to being hateful or not by combining text, image feature information and additional source of information from web entity detection. The work done makes use of the Multimodal dataset from Hateful Meme Detection Challenge 2020. The dataset is introduced with confounder examples that contain memes that are benign, contrastive or counterfactual, making any State-Of-The-Art (SOTA) visual linguistic models perform less precisely in comparison to non-expert humans, showing difficulty of the task. It is essential for the models to have a deeper knowledge about the language, image, current events, and to understand the interaction among different modalities. 
</p>
<p align="justify">
The proposed approach uses the text, image and the information collected from the web entity detection process. The report discusses the shortfall of the approach and future directions to improve upon the proposed methodology. The work presented sometimes suffers from the lack of real-world knowledge. Detecting people's characteristics is hard and it is not fully capable of identifying racial/religious groups. It does not perform well on memes suggestive of disability, injury and abuse. The models find it hard to understand the Cultural, Political, Societal References, Traditional attires, and Religious practices.
</p>
<p align="justify">
The proposed architecture uses two parallel streams for processing text and image with cross attention training. Both the streams are based on the bidirectionl multi-head attention model. The work discusses the preprocessing pipeline required for the proposed architecture. The project was done in two phases, the first phase resulted in an Area Under The Receiver Operating Characteristic (AUROC) of 0.71 and accuracy of 0.74 on the hateful memes dataset. The model resulted in an AUROC of 0.8108 on the test unseen data and 0.7555 on dev unseen data of the extended Hateful Meme Detection Dataset with an accuracy of 0.7352 for the test unseen and 0.7650 for the dev unseen data. The Hateful Meme detection dataset was extended to include more memes in Phase-II.
</p>
<p align ="center">
<img src="https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/input_dataset.jpg" alt="drawing" width="800"/>
<img src="https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/pipeline.jpg" alt="drawing" width="800"/>
<img src="https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/easyocr.jpeg" alt="drawing" width="500"/>
<img src="https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/preprocess.jpg" alt="drawing" width="500"/>
<img src="https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/webdetect.jpg" alt="drawing" width="500"/>
<img src="https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/coattention.png" alt="drawing" width="500"/>
</p>
<!-- ![Input](https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/input_dataset.jpg)
![Pipeline](https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/pipeline.jpg)
![Preprocess](https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/preprocess.jpg)
![OCR](https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/easyocr.jpeg)
![Web Detect](https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/webdetect.jpg)
![Coattention](https://github.com/Srigowri/Hateful-Meme-Detection/blob/main/images/coattention.png)
 -->
