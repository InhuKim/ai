# 🖥 AI Team
- 김인후
- 서지연
- 심혜주
- 이지희
- 정민수

## 🛒 시각 장애인 마트 쇼핑 서비스
### ✔ 목적
- 시각 장애인의 쇼핑 편의 향상
### 📢 방향
- 제품 이미지 학습 및 쇼핑 경로 안내
### 🕹 수행 방법▪도구
- Object Tracking (객체 탐지 및 추적 방법)
- 딥러닝 기반 실시간 다중 추적 시스템 : YOLO-v3, Deep Sort
- 실험 데이터 : MOT16, MOT challenge benchmark (CCTV 영상처럼 구성)
- 라이브러리 : pytorch, opencv, sklearn
### ⭐ 필수 기능
- 상품명 촬영 시 이미지 인식 (마트 홈페이지 크롤링 데이터로부터 검색 후 가격 정보 안내 & 유사품과 가격 비교)
- 마트에 설치된 카메라로 사용자를 인식, 추적하여 사용자의 위치 정보 생성
- 마트 내 위치 정보를 통해 경로 안내(카트에 담긴 상품들의 특성에 따른 최적 쇼핑 경로 안내)
### 📚 데이터
- [딥러닝 기반 다중 CCTV 영상](https://drive.google.com/drive/folders/1el9kK4wgaiMzEMlfzqeQx6acoq703diP)
- [Real-Time Object Detection on COCO](https://paperswithcode.com/sota/real-time-object-detection-on-coco)
- [유사 이미지 찾기](https://velog.io/@chacha/Kaze-Keypoint-Matching-%EC%9C%A0%EC%82%AC-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%B0%BE%EA%B8%B0)
- [AIHub 롯데정보통신 상품 이미지 소개](https://aihub.or.kr/aidata/34145) 

### 🔍 사례

- 서비스구현 [시각장애인을 위한 편의점 음료 서비스](https://github.com/se-ize/BeYerage)
- 서비스 [설리번+:시각장애인 및 저시력자 등 시각의 보조가 필요한 사용자들에게 스마트폰 카메라를 통해 인식한 정보를 알려주는 서비스 ](https://www.mysullivan.org/)
- 서비스 [LG CNS 상품검색 API 서비스](ai.lgcns.com)
- 논문 [딥러닝 객체 탐지 기술을 사용한 스마트 쇼핑카트의 구현](https://www.koreascience.or.kr/article/JAKO202021853968918.pdf)
- 뉴스기사 [NEC의 상품인식 개발](http://www.aitimes.kr/news/articleView.html?idxno=11439) : 딥러닝 + 특징점 융합
- 논문, 코드 [로고인식 논문, 소스코드](https://m.facebook.com/groups/TensorFlowKR/permalink/501214233552973/)
- 서비스구현 [와들프로젝트:시각장애인을 위해 OCR을 사용하여 온라인 쇼핑 페이지를 읽어주는 서비스 (온라인)](https://www.chosun.com/national/national_general/2021/06/15/B2NNB3S35NFHTEHSRJHUUZIICM/)

## 🙆‍♂️🧏‍♀️ 수어 영상 한글 번역기
### ✔ 목적
- 수어를 모르는 사람과 청각 장애인 간의 원활한 의사소통 
### 📢 방향
- 제품 이미지 학습 및 쇼핑 경로 안내
### 🕹 수행 방법▪도구
- Object Tracking (객체 탐지 및 추적 방법)
- 모델 : 수어 인식 모델(DG-STA, SMKD), 번역기 모델(transformer)
- 실험 데이터 : MOT16, MOT challenge benchmark (CCTV 영상처럼 구성)
- 라이브러리 : pytorch, opencv
### ⭐ 필수 기능
- 이미지 인식 : 수어 영상에서 hand skeleton recognition, 이미지 인식 모델을 통해 한글 단어로 분류
- 수어 - 한글 번역 : 수어 문장 - 한글 문장 쌍을 만든 후 번역 모델로 학습하여 번역기 제작
### 📞 요구 사항
1. 수어 영상 인식 기능
2. 인식한 단어->텍스트로 변환 후 번역기에 전달
3. 어순이 다른 수어를 번역기가 한글 문장으로 번역
### 🔍 사례
- [영상 기반 수어 인식](https://github.com/hthuwal/sign-language-gesture-recognition/blob/master/Final%20Report.pdf)
- [영상 기반 수어 인식 github](https://github.com/hthuwal/sign-language-gesture-recognition)
- [‘수어 영상 인공지능 학습용 데이터’ 구축 사례](https://blog.naver.com/testworks_mktg/222206817110)
- [Real-Time American Sign Language Recognition Using Desk and Wearable Computer Based Video](http://luthuli.cs.uiuc.edu/~daf/courses/Signals%20AI/Papers/HMMs/00735811.pdf)
