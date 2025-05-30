# 🧠 Text Analytics Project

본 프로젝트는 자연어 처리(NLP) 전처리부터 대형언어모델(LLM) 활용까지 다양한 분석 기법과 도구들을 탐구한 기록입니다.  
한국어 텍스트 분석과 LLM 응용을 중심으로 실습하며, 전처리부터 RAG 구조까지의 전체 흐름을 다룹니다.

---

### 🔍 주요 기술 스택

#### RAG (Retrieval-Augmented Generation)
- 문서 검색 기반 LLM 응답 생성 구조 실험
- LangChain 및 FAISS 연동

#### HuggingFace Transformers
- 사전학습 언어모델 기반 임베딩 및 문서 검색 테스트
- `sentence-transformers`, `BAAI/bge-m3` 등 활용

#### NLP 전처리 with NLTK
- 문장 분리: `sent_tokenize`
- 단어 분리: `word_tokenize`
- 불용어 제거
- 어간 추출 (Stemming: `LancasterStemmer`)
- 표제어 추출 (Lemmatization: `WordNetLemmatizer`)
- Bag-of-Words (BOW): `CountVectorizer`, `TfidfVectorizer`
- 희소행렬 표현: `COO`, `CSR` 포맷

#### LLM API 활용
- OpenAI GPT API를 이용한 프롬프트 기반 질의응답 테스트
- GPT-4 모델과의 연동 및 응답 흐름 확인

---

### 🛠️ Text Preprocessing Tools

| 라이브러리 | 설명 |
|------------|------|
| `re.sub()` | 정규표현식 기반 문자열 정제 |
| `PyKoSpacing` | 띄어쓰기 자동 교정 |
| `KiwiPiepy` | 한국어 형태소 분석기 |
| `KoNLPy` | 다양한 한국어 분석기 지원 (`Hannanum`, `Kkma`, `Komoran`, `Okt`) |

---

### ✅ 학습 목표

- 다양한 한국어 전처리 도구 실습 및 비교
- 문서 임베딩 기반 검색 시스템 구성 실습 (FAISS, Chroma 등)
- RAG 파이프라인 설계 이해 및 실험
- OpenAI GPT API를 활용한 질의응답 및 생성 실습

---

### 💬 기타
이 프로젝트는 학습용으로 구성되었으며, 일부 데이터셋 및 API는 개인 실습 범위 내에서 사용되었습니다.



