# Deep-learning-Project

Project Name: MemesViTa: A Novel Multimodal Fusion Technique to Troll Memes Identification

Team Members: Tipu Sultan

GitHub: https://github.com/Tipusultan199/Deep-learning-Project

Project Proposal:

# MemeFusionNet: A Cross-Linguistic Multimodal Model for Identifying Troll Memes

**Author:** Tipu Sultan  , Dr. Hadi Akbarpour


## Problem
Memes, blending visual and textual modalities, are a prominent medium for humor, satire, and, often, trolling on social media. Troll memes spread misinformation, provoke negativity, and disrupt discourse, presenting challenges for automated detection. Traditional detection models either analyze text or image modalities independently or are tailored for specific languages, making them less effective for diverse, multilingual contexts. The complexity of troll meme detection lies in understanding subtle interactions between modalities and interpreting cultural and linguistic nuances embedded in meme content. Addressing these challenges is critical for scalable and inclusive content moderation.

## Relevance

Troll memes are challenging to moderate due to their ambiguous, often culturally contextual nature. Detecting such content requires a sophisticated approach that integrates both visual and textual analysis. With the rapid spread of memes across social media, developing accurate detection systems is essential for maintaining safe and healthy digital environments. Leveraging advancements in deep learning and multimodal fusion, this project seeks to enhance troll meme detection accuracy, addressing current limitations in single-modality approaches.

## Data Sources

This project utilizes a publicly available dataset(https://github.com/eftekhar-hossain/MemoSen-LREC2022) comprising 4300 labeled troll memes for training and 1200 labeled memes for testing. Each meme includes an image and textual caption, supporting multimodal analysis. The dataset represents diverse meme styles and themes, ensuring exposure to various forms of troll content. The data is split into training, validation, and testing subsets to assess model performance in detecting troll memes across different content types.

## Methodology

The project explores multiple multimodal deep-learning architectures to identify the most effective model for troll meme detection. For image processing, we experiment with Vision Transformer (ViT), ResNet50, and VGG16, each offering unique feature extraction capabilities: ViT for global attention, ResNet50 for robust features, and VGG16 for simplicity and accuracy in visual tasks. For text analysis, we evaluate language models like BERT, DeBERTa, and GPT-2, known for their strengths in understanding contextual and semantic relationships in text. We also test zero-shot and few-shot learning scenarios with large language models to enable classification with minimal labeled data. Through this dataset, we aim to identify the optimal multimodal fusion technique, comparing various architectures and strategies.

## Evaluation Strategy

Model performance is evaluated using accuracy, precision, recall, and F1-score, which measure effectiveness in distinguishing troll memes from benign content. We compare image-only, text-only, and multimodal models, analyzing their capabilities in zero-shot and few-shot learning scenarios to test generalizability on unseen troll memes. Additionally, we assess model efficiency and robustness under real-world conditions, aiming to determine the best architecture for troll meme detection and provide insights for future improvements.

## Tools and Frameworks

The project uses Python and deep learning libraries like TensorFlow and PyTorch for model development. Pre-trained models such as BERT and ViT from Hugging Face or PyTorch provide a foundation for faster experimentation and fine-tuning for troll meme detection.

## Challenges and Limitations

Challenges include ensuring model generalization to the diverse and evolving nature of troll memes and addressing potential dataset imbalances, as troll memes may have fewer labeled examples compared to benign memes. We aim to tackle these issues using data augmentation techniques and few-shot learning approaches to improve the model’s robustness and adaptability.
