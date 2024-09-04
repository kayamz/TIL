# TIL (2024-09-04)

## Day 3: Introduction to BERT (Bidirectional Encoder Representations from Transformers)

### What is BERT?
- **BERT (Bidirectional Encoder Representations from Transformers)**: BERT는 Google에서 개발한 사전 학습된 언어 모델로, 텍스트의 양방향 컨텍스트를 이해하는 데 중점을 둔다. 이는 트랜스포머의 인코더(Encoder) 구조를 사용하며, 입력 문장의 양쪽 방향에서 문맥을 고려하여 단어의 의미를 학습한다.

### Key Features of BERT
- **Bidirectional Contextualization**: BERT는 문장의 양방향 컨텍스트를 사용하여 단어를 학습한다. 이는 단어가 문장의 앞과 뒤에서 어떻게 사용되는지를 모두 고려하여 더 정확한 표현을 생성할 수 있게 한다.
  
- **Pre-training and Fine-tuning**: BERT는 대규모 텍스트 데이터로 사전 학습(pre-training)된 후, 특정 작업에 맞게 미세 조정(fine-tuning)된다. 사전 학습 단계에서는 언어 모델링과 다음 문장 예측 작업을 수행하며, 이후 특정 NLP 작업(예: 감정 분석, 질문 답변)에 맞게 미세 조정된다.

- **Masked Language Modeling (MLM)**: BERT는 입력 텍스트의 일부 단어를 마스킹한 후, 이 단어를 예측하는 방식으로 학습된다. 이 방법은 모델이 문장의 양쪽 문맥을 모두 활용하여 단어의 의미를 추론하게 한다.

### How BERT Works
- **Step 1**: 입력 텍스트는 토크나이저에 의해 토큰으로 분할된다. 각 토큰은 임베딩 벡터로 변환되어 BERT 모델의 입력으로 사용된다.
- **Step 2**: BERT는 인코더만으로 구성된 트랜스포머 아키텍처를 사용하여 입력 텍스트의 각 토큰에 대해 양방향 컨텍스트를 학습한다.
- **Step 3**: 사전 학습된 BERT 모델은 특정 작업에 맞게 미세 조정된다. 예를 들어, 질문 답변 시스템에서는 질문과 문맥을 입력받아 정답이 될 가능성이 높은 부분을 출력하도록 학습된다.

### Real-World Applications
- **Question Answering**: BERT는 질문에 대한 정확한 답변을 찾아내는 데 매우 효과적이다. 예를 들어, Google 검색 엔진은 사용자의 질문에 맞는 답변을 제공하기 위해 BERT를 사용한다.
  
- **Sentiment Analysis**: 영화 리뷰나 소셜 미디어 게시글의 감정(긍정, 부정, 중립)을 분석하는 작업에 BERT가 활용된다. BERT의 양방향 학습은 문맥을 고려한 정확한 감정 분석을 가능하게 한다.

- **Text Classification**: 스팸 메일 필터링, 주제 분류 등 다양한 텍스트 분류 작업에서 BERT는 높은 정확도를 보인다.

### Learning Resources
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [BERT Explained: State of the art language model for NLP](https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270)
- [Hugging Face BERT Documentation](https://huggingface.co/transformers/model_doc/bert.html)

### Summary
오늘은 BERT 모델의 기본 개념과 작동 원리, 그리고 실제 활용 사례에 대해 배웠다. BERT는 트랜스포머의 인코더 구조를 활용하여 텍스트의 양방향 컨텍스트를 학습함으로써, 다양한 NLP 작업에서 높은 성능을 발휘한다. 앞으로는 BERT를 직접 활용해보고, 다양한 NLP 작업에 적용하는 것을 목표로 한다.

---

**Commit message**: `Add Day 3: Introduction to BERT`
