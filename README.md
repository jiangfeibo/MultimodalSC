# Large AI Model Empowered Multimodal Semantic Communications
## Authors：Feibo Jiang, Yubo Peng, Li Dong, Kezhi Wang, Kun Yang, Cunhua Pan, Xiaohu You
## Paper：https://arxiv.org/abs/2309.01249
## Code：https://github.com/qiyuqianxai/Large-AI-Model-Empowered-Multimodal-Semantic-communication.git
## Abstract
Multimodal signals, including text, audio, image, and video, can be integrated into Semantic Communication (SC) to provide an immersive experience with low latency and high quality at the semantic level. However, the multimodal SC has several challenges, including data heterogeneity, semantic ambiguity, and signal fading. Recent advancements in large AI models, particularly in the Multimodal Language Model (MLM) and Large Language Model (LLM), offer potential solutions for these issues. To this end, we propose a Large AI Modelbased Multimodal SC (LAM-MSC) framework, in which we first present the MLM-based Multimodal Alignment (MMA) that utilizes the MLM to enable the transformation between multimodal and unimodal data while preserving semantic consistency. Then, a personalized LLM-based Knowledge Base (LKB) is proposed, which allows users to perform personalized semantic extraction or recovery through the LLM. This effectively addresses the semantic ambiguity. Finally, we apply the Conditional Generative adversarial networks-based channel Estimation (CGE) to obtain Channel State Information (CSI). This approach effectively mitigates the impact of fading channels in SC. Finally, we conduct simulations that demonstrate the superior performance of the LAM-MSC framework.
## 1.The proposed SemCom System
https://github.com/jiangfeibo/MultimodalSC/assets/67264710/f9f10be8-8a36-4983-91a4-3c927191845d
### Explanation of the video：
  - Illustration：The video demonstrates our proposed multimodal semantic communication system. During the transmission process, text is used instead of the original video for transmission. GPT is employed to disambiguate and correct the transmitted text. Finally, the video is reconstructed based on user identity and voice characteristics according to the transmitted text.
## 2.Multimodal large models at the edge (Jetson Iron)
https://github.com/jiangfeibo/MultimodalSC/assets/67264710/8d018280-b0a8-43e7-9825-101dba51bc3e
### Explanation of the video：
  - Model：MobileVLM
  - Video content：
  
    Q：What did you see? 

    
    A：In the image, a person is holding a book, possibly a textbook, with a flower design on the cover. The book is open and appears to be in a foreign language. The person is also holding a hand, possibly to hold the book or to show the book to someone.
## 3.Large Language Model at the edge (Jetson Iron)
https://github.com/jiangfeibo/MultimodalSC/assets/67264710/7564d320-b041-4bb3-969d-817e418659e4
### Explanation of the video：
  - Model：qwen1.6b
  - Pre filling rate：253.35token/s
  - Decoding rate：9.04token/s
  - Video content：

    Q：喂！你好.
  
  
    A：你好！有什么我能帮助你的吗？
  
    
    Q：你能做些什么呢？
  
    
    A：我可以回答问题，提供定义，解释和建议，将文本从一种语言翻译成另一种语言，总结文本，生成文本，写故事，分析感情，提供建议，开发算法，编写代码以及任何其他基于语言的任务.

## Citation   
```python
@misc{jiang2023large,
      title={Large AI Model Empowered Multimodal Semantic Communications}, 
      author={Feibo Jiang and Yubo Peng and Li Dong and Kezhi Wang and Kun Yang and Cunhua Pan and Xiaohu You},
      year={2023},
      eprint={2309.01249},
      archivePrefix={arXiv},
      primaryClass={cs.AI}
}
```
