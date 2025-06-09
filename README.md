# LLM Study Project

이 프로젝트는 대규모 언어 모델(LLM)의 학습과 활용에 대한 연구 및 실습 내용을 담고 있습니다.

## 프로젝트 구성

### 1. PromptTemplate.ipynb
- LangChain을 활용한 프롬프트 템플릿 구현
- OpenAI API를 사용한 LLM 모델 활용
- 프롬프트 템플릿의 기본 개념과 활용 방법 학습
- 요리 추천 시스템 구현 예제 포함

### 2. Model_Weights_Loaded.ipynb
- 텍스트 토큰화 및 전처리 과정 학습
- 정규표현식을 활용한 기본 토크나이저 구현
- 텍스트 데이터 전처리 기법 학습
- 토큰화된 데이터의 구조와 처리 방법 이해

### 3. Langchain_Project.ipynb
- LangChain 프레임워크를 활용한 텍스트 처리
- Text Splitter를 사용한 텍스트 분할 기법
- CharacterTextSplitter와 RecursiveCharacterTextSplitter 구현
- 토큰 기반 텍스트 분할 및 임베딩 처리

### 4. 02_fullfinetuning1_base_cleaned.ipynb
- LLM 모델의 전체 미세조정(Full Fine-Tuning) 구현
- 카카오 나노 2.1b 베이스 모델 사용
- 데이터셋 준비 및 전처리 과정
- PyTorch를 활용한 모델 학습 구현
- 미세조정된 모델의 성능 평가

## 주요 기능

1. **프롬프트 엔지니어링**
   - 템플릿 기반 프롬프트 생성
   - 시스템 메시지와 사용자 메시지 구조화
   - 다양한 LLM 모델과의 통합

2. **텍스트 처리**
   - 텍스트 분할 및 청크 생성
   - 토큰화 및 임베딩 처리
   - 데이터 전처리 파이프라인 구축

3. **모델 학습**
   - 전체 미세조정 구현
   - 데이터셋 준비 및 처리
   - 모델 학습 및 평가

## 기술 스택

- Python
- PyTorch
- LangChain
- OpenAI API
- Hugging Face Transformers
- tiktoken

## 설치 및 실행

1. 필요한 패키지 설치:
```bash
pip install openai langchain langchain-openai langchain_community
pip install torch transformers
pip install tiktoken
```

2. OpenAI API 키 설정:
```python
import os
os.environ["OPENAI_API_KEY"] = 'your-api-key'
```

## 참고 자료

- [Build a Large Language Model (From Scratch)](https://www.youtube.com/watch?v=yXrGeDNuymY&list=PLPTV0NXA_ZSgsLAr8YCgCwhPIJNNtexWu&index=32)
- [Fine-Tuning of a Korean Local Model](https://www.youtube.com/watch?v=NrDZmSDvXXw)

## 주의사항

- 실제 프로덕션 환경에 적용하기 전에 추가적인 검증이 필요합니다.
- API 키와 같은 민감한 정보 사용에 주의하세요.