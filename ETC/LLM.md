# TIL (2024-09-02)

## Day 1: Introduction to Large Language Models (LLM)

### What is an LLM?
- **LLM (Large Language Model)**: LLM은 대규모 데이터셋을 기반으로 학습된 인공지능 언어 모델입니다. 이 모델은 자연어 처리(NLP) 작업을 수행할 수 있으며, 텍스트 생성, 번역, 요약, 질문 답변 등 다양한 작업에 활용됩니다.

### Key Concepts
- **Parameters**: LLM은 수십억 개의 매개변수(parameters)를 가지며, 이 매개변수들은 모델이 학습하는 과정에서 조정됩니다. 매개변수의 수가 많을수록 모델의 성능이 좋아질 가능성이 높습니다.
  
- **Training Data**: LLM은 대규모 텍스트 데이터를 학습하여 언어 패턴과 구조를 이해합니다. 웹사이트, 책, 논문 등의 다양한 출처에서 데이터를 수집합니다.

- **Transformer Architecture**: 대부분의 LLM은 트랜스포머(Transformer) 구조를 기반으로 합니다. 트랜스포머는 인코더와 디코더로 구성되며, 셀프 어텐션(self-attention) 메커니즘을 사용하여 입력 문장 내에서 단어 간의 관계를 이해합니다.

- **Fine-Tuning**: LLM은 특정 작업에 맞게 추가적으로 학습(Fine-Tuning)될 수 있습니다. 이 과정에서 일반적인 언어 모델이 특정 도메인이나 응용 프로그램에 최적화됩니다.

### Popular LLMs
- **GPT (Generative Pre-trained Transformer)**: OpenAI에서 개발한 대표적인 LLM입니다. GPT 시리즈는 GPT-2, GPT-3, GPT-4 등으로 진화해 왔습니다.
  
- **BERT (Bidirectional Encoder Representations from Transformers)**: Google에서 개발한 모델로, 문장의 양방향 컨텍스트를 이해하는 데 강점이 있습니다. 주로 텍스트 분류, 감정 분석 등에 사용됩니다.

- **T5 (Text-To-Text Transfer Transformer)**: Google에서 개발한 모델로, 모든 NLP 작업을 텍스트 생성 문제로 변환합니다. 입력과 출력을 모두 텍스트로 취급하는 것이 특징입니다.

### Real-World Applications
- **Chatbots**: LLM은 고객 지원, 상담 등에서 사용되는 고도화된 챗봇의 핵심 기술입니다.
  
- **Content Generation**: 블로그 포스트, 뉴스 기사, 광고 카피 등 다양한 콘텐츠를 자동으로 생성하는 데 사용됩니다.

- **Translation**: LLM을 이용한 언어 번역 서비스는 기존의 규칙 기반 번역 시스템보다 더 자연스러운 번역을 제공합니다.

### Learning Resources
- [OpenAI GPT-3 Documentation](https://beta.openai.com/docs/)
- [Google Research: BERT](https://github.com/google-research/bert)
- [Hugging Face Transformers Library](https://huggingface.co/transformers/)

### Summary
오늘은 LLM의 기본 개념과 주요 모델에 대해 배웠습니다. 앞으로는 이러한 모델들을 더 깊이 이해하고, 직접 다뤄보는 것을 목표로 합니다.

---

**Commit message**: `Add Day 1: Introduction to LLM`

