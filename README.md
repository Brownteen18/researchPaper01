# researchPaper01
A Local Language NLP Framework for Maithili–Hindi alignment under ultra-low resource conditions, focusing on inclusive AI and transformer-based learning.

Overview:
This project presents a Local Language NLP Framework designed for Maithili–Hindi alignment under ultra-low resource conditions.

The goal is to improve inclusive digital communication by enabling better cross-lingual understanding for regional languages that are often underrepresented in modern NLP systems.

Problem Statement:
Most NLP systems are optimized for high-resource languages, leaving regional languages like Maithili underserved.

Challenges include:
- Limited availability of aligned datasets
- Poor generalization in low-data scenarios
- Lack of inclusive AI solutions

- Objective:
- - Build a structured Maithili–Hindi NLP framework
- Analyze transformer performance in extreme low-resource settings
- Improve cross-lingual alignment and learning stability

- Methodology:
- - Preprocessing (normalization, cleaning, tokenization)
- Transformer-based fine-tuning
- Float32 precision for stability
- Evaluation using Leave-One-Out Cross Validation (LOOCV)

- Dataset:
- - 25 aligned Maithili–Hindi sentence pairs
- Domains: daily communication, education, governance
- Ultra-low resource experimental setup

- Results:
- - Initial Word Error Rate (WER): ~1.0
- Improved WER (LOOCV): ~0.24
- Significant improvement in alignment and prediction quality

- Key Learnings:
- - Preprocessing plays a critical role in low-resource NLP
- Fine-tuning improves stability even with minimal data
- Proper evaluation strategies are essential for realistic performance

- Impact:
- This project contributes toward:
- Inclusive AI development
- Regional language preservation
- Accessible digital communication systems

- Future Work:
- - Expand dataset (1000+ sentence pairs)
- Integrate speech-based models (ASR)
- Optimize for mobile and edge deployment

- Acknowledgement:
- I would like to express my sincere gratitude to Ms. Madhuri Gupta (Assistant Professor, PSIT Kanpur) for her guidance and support throughout this project.

- Research Paper:
- You can read the full research paper here:
  [https://drive.google.com/file/d/1jxv37rr2ik_RGMTfmyuTA1v6smDFkXW9/view?usp=drive_link]
