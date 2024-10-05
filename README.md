# Video Chatbot for Multimodal YouTube Analysis using Large Vision-Language Models (LVLMs)

This project implements a video chatbot capable of automatic caption generation and Q&A for YouTube videos using state-of-the-art multimodal **Large Vision-Language Models (LVLMs)**. The chatbot enhances video comprehension and interaction by processing text and visual inputs and delivering real-time responses to user queries.

## 🚀 Key Features

- **YouTube Video Analysis**: Automatically generates captions and answers questions based on video content.
- **Multimodal Interaction**: Combines visual and text-based inputs to enhance video understanding and interaction.
- **Model Benchmarking**: Evaluates different LVLMs using standard video understanding metrics.

## 🧠 Models Evaluated

The following **Large Vision-Language Models** (LVLMs) were evaluated in the project:

- **Qwen2-VL**
- **LLaVa-NeXT-Video**
- **mPLUG-Owl3**

### Model Performance Metrics

Models were benchmarked on the **MSR-VTT dataset** using the following metrics:

- **BLEU** (Bilingual Evaluation Understudy)
- **METEOR** (Metric for Evaluation of Translation with Explicit ORdering)
- **ROUGE-L** (Recall-Oriented Understudy for Gisting Evaluation)

## ⚙️ Tech Stack

- **Frameworks**: PyTorch, Transformers
- **Models**: Large Vision-Language Models (LVLMs)
- **Languages**: Python
