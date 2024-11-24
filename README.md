# BDBD: Data Collection and Analysis Guide 📊

이 리포지터리는 **BDBD팀의 졸업 프로젝트**로서, 사회 이슈 발생 시 이해관계자 패턴에 따른 소비량 변화 분석 및 시각화를 목표로 데이터를 수집하고 분석하는 과정을 다룹니다. 이 페이지는 데이터 수집 및 전처리 단계부터 데이터 분석 단계까지의 전반적인 진행 흐름과 사용한 코드 파일을 소개합니다.

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
  - [`키워드열_추출_및_단어_분리.ipynb`](./데이터%20수집%20및%20전처리/키워드열_추출_및_단어_분리.ipynb)
  - [`뉴스_기사_별_이해관계자_추출.ipynb`](./데이터%20수집%20및%20전처리/뉴스_기사_별_이해관계자_추출.ipynb)
  - [`대분류,_언론사_코드_정리.ipynb`](./데이터%20수집%20및%20전처리/대분류,_언론사_코드_정리.ipynb)

- **분석 결과 및 대시보드**  
  - 진행 과정에서 산출된 대시보드와 분석 결과는 HTML 페이지로 제공되며, 메인 프로필 페이지에서 찾아볼 수 있습니다!

---

이 프로젝트에 대한 보다 자세한 내용은 해당 코드 파일을 참조해주세요.

---

## 프로젝트 주요 내용 📈

프로젝트 산출물 및 대시보드는 HTML 페이지를 통해 제공될 예정이며, GitHub에서 코드와 자료를 직접 확인하실 수 있습니다.

🔗 **[html 링크]([https://github.com/BDBD-hywu](https://bestdayofbigdata22.framer.website/))**  

---

## 소통해요! 🤝

해당 프로젝트에 관심이 있으시거나 궁금한 점이 있다면 언제든지 연락 주세요!

- E-mail : bestdayofbigdata22@gmail.com

<!--
**BDBD-hywu/BDBD-hywu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
