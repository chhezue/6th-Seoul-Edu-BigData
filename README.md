## 📖 2024 제6회 서울교육 데이터 분석·활용 아이디어 공모전

### 🚀 프로젝트 소개

**중장년 대상 관심사 기반 평생교육 강좌 추천 챗봇<br>**
> 중장년층을 대상으로 관심사 기반의 평생교육 강좌를 추천하는 챗봇 시스템을 구현한 프로젝트<br>
> 사용자가 관심사 및 해당 관심사의 중요도를 입력 → 이를 분석하여 가장 적합한 평생교육 강좌를 추천

### 🤝 주요 내용

- **주제**: 중장년 대상 관심사 기반 평생교육 강좌 추천 챗봇
- **활용 데이터**: 
  - 평생교육 오프라인/온라인 강좌 정보
  - 네이버 뉴스 및 블로그에서 수집한 중장년 관심사 데이터 (웹 크롤링)
- **활용 기술**:
  - Otk 형태소 분석기를 사용하여 한글 텍스트를 토큰화하고 불용어 제거
  - TfidfVectorizer와 BERT 모델을 활용하여 텍스트 데이터를 벡터화하고 의미를 분석
  - 임베딩 기술
- **모델 로직**: 
  - 사용자의 관심사 2개와 각 관심사의 중요도(가중치)를 입력받아 평생교육 강좌 추천

### 🛠️ 기술 스택
- Python
- scikit-learn
- TensorFlow(BERT)
- Beautiful Soup
