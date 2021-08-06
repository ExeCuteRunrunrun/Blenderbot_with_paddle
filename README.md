# Blenderbot_with_paddle
Paddle implementation of Blenderbot, [Recipes for building an open-domain chatbot](https://aclanthology.org/2021.eacl-main.24.pdf), with help of its [original implementation code](https://github.com/huggingface/transformers/tree/master/src/transformers/models/blenderbot)

# Goal:
1. Reimplement Blenderbot and Blenderbot Small
2. Convert models from pytorch to paddle 
    - 90M; 
    - 2.7B; 
    - 2.7B distilled to 1.4B; 
    - 2.7B distilled to 360M
3. BlenderbotForConditionalGeneration model & BlenderbotSmallForConditionalGeneration model inference
    - 90M
    - 2.7B distilled to 360M
4. Submit PR to PaddleNLP
