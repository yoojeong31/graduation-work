# 🎓 Graduation Project: Best Day of Big Data 🌐📊

이 리포지토리는 제가 한양여자대학교 빅데이터과 3학년 재학 중 수행한 **졸업 작품 캡스톤디자인 프로젝트**를 다룹니다.  

해당 프로젝트는 **사회 이슈 발생 시 이해관계자 개입에 따른 소비량 변화를 분석하고 시각화**하는 것을 목표로 진행되었습니다.  

프로젝트는 **BDBD팀**의 일원으로 진행되었으며, 저는 **PM (프로젝트 매니저)** 와 **시각화 구축가** 역할을 맡아 프로젝트의 기획과 데이터 시각화를 주도적으로 담당했습니다.

---

## 📚 프로젝트 개요  

- **프로젝트 제목**: 사회 이슈 발생 시 이해관계자 개입에 따른 소비량 예측 및 시각화
- **목표**:  
  - 이해관계자 패턴과 외부 요인(언론 데이터 등)을 기반으로 소비량 변화 예측.  
  - Tableau를 활용한 데이터 시각화 대시보드 제작.  
- **활용 기술**:  
  - Python (`pandas`, `numpy`, `Prophet`, `scikit-learn`)  
  - Tableau  
  - Google Colab  

---

## 데이터 수집 및 전처리 🛠️

1. **이해관계자 키워드 추출**  
   - `데이터 수집 및 전처리/키워드열_추출_및_단어_분리.ipynb`  
   빅카인즈에서 수집한 뉴스 데이터를 기반으로 이해관계자로 추정되는 키워드를 추출합니다.

2. **키워드 분류 코드화**  
   - 추출된 키워드들을 대분류, 중분류로 나누어 코드화합니다.

3. **뉴스 기사별 이해관계자 추출**  
   - `데이터 수집 및 전처리/뉴스_기사_별_이해관계자_추출.ipynb`  
   각 뉴스 기사에서 이해관계자를 추출하여 기사별로 정리합니다.

4. **이해관계자 코드화**  
   - `데이터 수집 및 전처리/대분류,_언론사_코드_정리.ipynb`  
   정리된 뉴스 기사별 이해관계자 데이터를 코드화하여 분석 준비를 마칩니다.

5. **이해관계자 빈도 계산**  
   - 최종적으로 엑셀에서 이해관계자의 빈도를 계산하여 분석에 사용할 **최종 데이터셋**을 준비합니다.

---

## 데이터 분석 📈

1. **상관분석**  
   - 데이터 변수들 간의 관계를 파악하여 상관관계를 분석합니다.

2. **회귀 분석**  
   - 변수들 간의 인과관계를 검토하고 회귀 분석을 통해 모델을 생성합니다.

3. **시계열 분석**  
   - 시간에 따른 변화 패턴을 분석하여 트렌드를 파악합니다.

4. **성능 평가 및 최적 모델 선정**  
   - 다양한 성능평가 지표를 활용해 가장 예측 성능이 높은 모델을 채택합니다.

---

## 프로젝트 활용 파일 및 링크 🔗

- **데이터 수집 및 전처리 코드**  
  - [`키워드열_추출_및_단어_분리.ipynb`](https://github.com/yoojeong31/graduation-work/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%84%EC%B2%98%EB%A6%AC/%E1%84%82%E1%85%B2%E1%84%89%E1%85%B3_%E1%84%80%E1%85%B5%E1%84%89%E1%85%A1_%E1%84%87%E1%85%A7%E1%86%AF_%E1%84%8B%E1%85%B5%E1%84%92%E1%85%A2%E1%84%80%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A8%E1%84%8C%E1%85%A1_%E1%84%8E%E1%85%AE%E1%84%8E%E1%85%AE%E1%86%AF.ipynb)
  - [`뉴스_기사_별_이해관계자_추출.ipynb`]([https://github.com/yoojeong31/graduation-work/tree/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%84%EC%B2%98%EB%A6%AC/뉴스_기사_별_이해관계자_추출.ipynb](https://github.com/yoojeong31/graduation-work/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%84%EC%B2%98%EB%A6%AC/%E1%84%8F%E1%85%B5%E1%84%8B%E1%85%AF%E1%84%83%E1%85%B3%E1%84%8B%E1%85%A7%E1%86%AF_%E1%84%8E%E1%85%AE%E1%84%8E%E1%85%AE%E1%86%AF_%E1%84%86%E1%85%B5%E1%86%BE_%E1%84%83%E1%85%A1%E1%86%AB%E1%84%8B%E1%85%A5_%E1%84%87%E1%85%AE%E1%86%AB%E1%84%85%E1%85%B5.ipynb))
  - [`대분류,_언론사_코드_정리.ipynb`](https://github.com/yoojeong31/graduation-work/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%88%98%EC%A7%91%20%EB%B0%8F%20%EC%A0%84%EC%B2%98%EB%A6%AC/%E1%84%83%E1%85%A2%E1%84%87%E1%85%AE%E1%86%AB%E1%84%85%E1%85%B2%2C_%E1%84%8B%E1%85%A5%E1%86%AB%E1%84%85%E1%85%A9%E1%86%AB%E1%84%89%E1%85%A1_%E1%84%8F%E1%85%A9%E1%84%83%E1%85%B3_%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%85%E1%85%B5.ipynbb)

- **분석 결과 및 대시보드**  
  - 진행 과정에서 산출된 대시보드와 분석 결과는 HTML 페이지로 제공되며, 아래 링크에서 확인하실 수 있습니다!

---

## 프로젝트 주요 내용 📈

프로젝트 산출물 및 대시보드는 HTML 페이지를 통해 제공되며, GitHub에서 코드와 자료를 직접 확인하실 수 있습니다.

🔗 **[html 링크]([https://github.com/BDBD-hywu](https://bestdayofbigdata22.framer.website/))**  

<!--
**BDBD-hywu/BDBD-hywu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

