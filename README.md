# Specific-GPTs [简体中文](https://github.com/K-tang-mkv/Specific-GPTs/blob/main/README_cn.md#%E4%B8%93%E5%AE%B6%E5%A4%A7%E6%A8%A1%E5%9E%8B-)
🚀 Apart from the general language model (LLM), we also need more domain specific GPTs to assist us in handling downstream tasks or driving industry development.

### [roomGPT](https://github.com/Nutlope/roomGPT) - redesign your room with AI
It uses an ML model called [ControlNet](https://github.com/lllyasviel/ControlNet) to generate variations of rooms. This application gives you the ability to upload a photo of any room, which will send it through this ML Model using a Next.js API route, and return your generated room. The ML Model is hosted on Replicate and Upload is used for image storage.

### [BloombergGPT: A Large Language Model for Finance](https://arxiv.org/abs/2303.17564) - (didn't open source)
LLM specialized for the financial domain. BloombergGPT, a 50 billion parameter language model that is trained on a wide range of financial data. The authors construct a 363 billion token dataset based on Bloomberg's extensive data sources, perhaps the largest domain-specific dataset yet, augmented with 345 billion tokens from general purpose datasets.

### [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) - AI for Finance
Wall Street didn't open source LLMs or API, so FinGPT is coming out! Unlike proprietary models, FinGPT takes a data-centric approach, providing researchers and practitioners with accessible and transparent resources to develop their FinLLMs. They highlight the importance of an automatic data curation pipeline and the lightweight low-rank adaptation technique in building FinGPT. 

### [LaWGPT](https://github.com/pengxiao-song/LaWGPT) - LLM based on Chinese legal knowledge
The series of models are based on the general Chinese language base models such as Chinese-LLaMA and ChatGLM, with the addition of an exclusive legal vocabulary and large-scale Chinese legal corpus pre-training to enhance the basic semantic understanding capability of large models in the legal field. Based on this, a legal domain dialogue question answering dataset and a Chinese judicial examination dataset were constructed for fine-tuning, which improved the model's understanding and execution capabilities of legal content.

### [FoodGPT](https://huggingface.co/spaces/thirdai/FoodUDT-1B) - (didn't opensource)
A “specialized” billion-parameter FoodUDT-1B model from ThirdAI that is pre-trained on 500K recipes. An expert network, FoodUDT-1B, trained only on recipes, views “meat” and “sugar” as non-complementary flavors. Meat and sugar usually don’t go together in a recipe. For a food expert, everything is about the pairing, the taste, enhancement, etc.

