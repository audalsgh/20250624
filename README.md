# 1일차 내용요약
### * 앞으로 구글 colab에서 파이썬 코드작성후, Github에 .ipynb 사본파일을 저장해둘것이다.

## 📘 AI 학습 정리
## 1. About GitHub, Markdown, Colab, w3schools
- [GitHub 사용법](#github-사용법)
- [Markdown 문법](#markdown-문법)  
- [Colab 기초](#colab-기초)
- [w3schools 사이트로 파이썬 기초 공부](#w3schools-사이트로-파이썬-기초-공부)

## GitHub 사용법

### ✅ GitHub 계정 만드는 순서 (2025년 기준)

1. **웹 브라우저 열기**
   크롬(Chrome), 엣지(Edge), 사파리(Safari) 중 편한 걸 사용하세요.

2. **GitHub 웹사이트 접속**
   주소창에 아래 주소를 입력하고 Enter 누르세요: https://github.com

3. **회원가입 시작하기**
   화면 오른쪽 위 또는 중간에 있는 Sign up 버튼 클릭

4. **이메일 주소 입력**
   평소 자주 사용하는 이메일을 입력

5. **비밀번호 만들기**
   영어 대문자, 소문자, 숫자, 특수문자를 섞어 안전하게!
   예시: Git1234!hub

6. **사용자 이름(Username) 정하기**
   나만의 고유한 이름을 지어요 (다른 사람이 쓰고 있으면 불가)
   - 예시: jetsunmom, sungsookjang66 등
   - 영어, 숫자, 하이픈(-) 가능 (띄어쓰기 ❌)

### ✅ Repository 만들기 순서

1. **GitHub에 로그인 후 New Repository 클릭**
   ![new](https://github.com/user-attachments/assets/3481a680-f677-403b-be8c-1fe59d5aa7cb)

2. **Repository 이름 입력**
3. **Public/Private 선택**
4. **README.md 파일 생성 체크**
5. **Create repository 버튼 클릭**
   
![create_repository](https://github.com/user-attachments/assets/8c2eb16b-8dfc-465a-88cd-d35770d12df0)

## Markdown 문법

| 기능        | 문법               | 예시                         | 결과                       |
| --------- | ---------------- | -------------------------- | ------------------------ |
| 제목(Title) | `#`, `##`, `###` | `## 내 프로젝트`                | 내 프로젝트                   |
| 굵게        | `**굵게**`         | `**중요**`                   | **중요**                   |
| 기울임       | `*기울임*`          | `*강조*`                     | *강조*                     |
| 목록        | `-`, `*`         | `- 사과` <br> `- 배`          | ● 사과 <br> ● 배            |
| 숫자 목록     | `1.`, `2.`       | `1. 첫째` <br> `2. 둘째`       | 1. 첫째 <br> 2. 둘째         |
| 링크        | `[이름](주소)`       | `[구글](https://google.com)` | [구글](https://google.com) |
| 이미지       | `![이름](이미지주소)`   | `![고양이](cat.jpg)`          | ![고양이](cat.jpg)          |
| 코드블록      | \`\`\`python     | `print("Hello")`           | 코드박스                     |
| 인라인 코드    | \`코드\`           | \`a = 3\`                  | `a = 3`                  |
| 구분선       | `---`            | `---`                      | ―――                      |

1.github에서 보기 좋게 정리하는 구조는 #을 적극이용한다
### 샵 갯수에 따른 폰트 사이즈 변화 3개
#### 샵 갯수에 따른 폰트 사이즈 변화 4개
##### 샵 갯수에 따른 폰트 사이즈 변화 5개

2.글자꾸미기 문법들 ** * ~~ ``
**굵게**
*기울임*
~~취소선~~
`코드처럼`

3.목록 만들기 문법 -,1. 2. 3.

● 순서 없는 목록 만들기엔 대쉬-
- 항목1
- 항목2
- 하위항목

● 순서 있는 목록 만들기엔 1. 2. 3.
1. 첫번째
2. 두번째

4.사진 드래그하여 삽입하기

![image](https://github.com/user-attachments/assets/26d7a201-9823-46b1-9586-810fcaa3291a)

5.인용문 표현하는 문법은 꺽쇠>
> 인용문입니다.
>> 두번 사용시 중첩 인용도 표현가능.

6.여러줄 코드블록은 키보드 물결버튼을 3번 입력해서 묶어주고, 언어이름을 적어주면 코드처럼 보인다
```python
print("안녕하세요")
※ 위 예시에서는 백틱(```)을 사용함. 언어 이름을 쓰면 색이 입혀짐.
```

7.표 만들기 역시 물결버튼 3번으로 묶어줘야 보기좋음.
```
| 이름 | 나이 | 직업 |
|------|----|-------|
| 영희 | 25 | 디자이너 |
| 철수 | 30 | 개발자 |
```

## Colab 기초  
(https://colab.research.google.com/drive/1kjk4TaXF05J5hpyAIl9mtpPz_PA3CV32#scrollTo=xqIeXOJikMM5)

1.런타임 유형 변경 -> T4 GPU

   ![image](https://github.com/user-attachments/assets/30e8abfa-d3a3-4a85-825b-386c18565fcb)

2.파일 -> github에 사본저장
   ![image](https://github.com/user-attachments/assets/1c65bc29-fc70-4cde-baa2-821e154ba52d)
   ![image](https://github.com/user-attachments/assets/f95321fc-3a20-4b8b-aeca-ece22ef900d8)

3.github에서 코드를 확인할수 있다.
   ![image](https://github.com/user-attachments/assets/e6b67e8a-d4e5-412b-bfc3-173e2a9ad6b1)

## w3schools 사이트로 파이썬 기초 공부
([https://www.w3schools.com/python/python_datatypes.asp](https://www.w3schools.com/python/default.asp))

 w3schools 사이트와, Colab을 동시에 열어두고 파이썬 코드를 돌려보며 공부한다.

![image](https://github.com/user-attachments/assets/983dd1cb-e0c5-404e-ae17-96491786a340)


## 2. 강의계획
### 1. About Python3
- [Python basic](./docs/python3.md)

### 2. data structure / data sciencs
- [데이터 구조 개요](./data_structures.md)
- [Pandas](./pandas.md)
- [Numpy](./numpy.md)
- [Matplotlib](./Matplotlib.md)

### 3. Machine Learning
- [Machine Learning Basic](./ml_basic.md)
- [모델 훈련 및 평가](./ml_test.md)

### 4. OpenCV
- [OpenCV Basic](./OpenCV_basic.md)
- [이미지 처리](./image_test.md)

### 5. CNN(Convolution Neural Network
- [CNN_Basic](./CNN_basic.md)
- [CNN_자율주행 관련 코드](./cnn_test.md)

### 6. Ultralytics
- [Ultralytics_Basic](./Ultralytics_basic.md)
- [YOLOv8](./YOLOv8_test.md)
- [YOLOv12](./YOLOv12_test.md)
  
### 7. TensorRT vs PyTorch 
- [PyTorch_Basic](./PyTorch_basic.md)
- [TensorRT](./TensorRT_test.md)
- [YOLOv12](./YOLOv12_test.md)

### 8. TAO Toolkit on RunPod
- [TAO_사용법](.TAO_install.md)
- [TAO_Toolkit](.TAO_Toolkit.md)

### 9. 칼만필터, CARLA, 경로 알고리즘
- [kalman](.kalman.md)
- [CARLA_simulator](.CARLA.md)

### 10. ADAS & (ADAS TensorRT vs PyTorch)
- [adas_basic](.adas_basic.md)
- [TensorRT vs PyTorch 비교](.vs.md)
