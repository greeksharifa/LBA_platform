
## 1단계 과제 목표: 데이터셋 설계 및 확보

---

### 1차년도
- 기술검증 실험을 위한 OOD 정보를 내포하고 OOD 해결을 위한 올바른 정보도 알고 있는 데이터셋 설계
- 기존 멀티모달 시계열 데이터 관련 데이터셋에 다양한 시구간 길이에 기반한 물체, description 등의 메타정보 데이터셋 구축 계획 수립.

### 2차년도
- 멀티모달 시계열 데이터 OOD 정보에 대한 불확실성 자각 및 질문 성장 기술 검증 데이터셋 설계 및 데이터 검수 및 보강 


### 3차년도
- 멀티모달 시계열 데이터 자가 선학습 및 지식 성장 학습을 위한 대규모 데이터셋 구축 및 공개



---


## 1차년도: 데이터셋 설계

### 기술검증 실험을 위한 OOD 정보를 내포하고 OOD 해결을 위한 올바른 정보도 알고 있는 데이터셋 설계

#### 설계 기준

어떤 질문을 할것인가? 어떤 보조질문을 만드는 것이 좋을까?
- 질문 내용 중 OOD label의 후보가 될 수 있는 인물/물체/장소/관계 등을 포함하여야 함
- 보조질문을 명확하게 만들 수 있어야 함
    - 보조질문을 명확하게 만들 수 있으려면 질문 해결을 위한 Reasoning 단계를 논리적으로 표현해야함

#### AGQA-like 데이터셋 설계 기준 수립
- 기존의 또오해영(DramaQA) 데이터셋 annotation을 바탕으로 대답할 수 있는 질문 template을 생성
- 추후, 2차년도 상반기 중 만들어질 한양대 module의 결과인 Video Scene graph를 바탕으로 질문 template을 추가 확장할 수 있음


#### 기존 또오해영 데이터셋의 annotation 정보
```
https://dramaqa.snu.ac.kr/Dataset 참조
- person
    - person id (ex. Haeyoung1)
    - behavior (ex. stand up)
    - emotion (ex. angry)
    - bbox
    - related_objects (특정 사람과 연관되어 있는 물체)
        - 일부의 object만 tagging되어 있음
        - bbox
- object
    - object class (ex. vase)
    - bbox
- place (ex. park)
- QA
    - 질문 template 생성이 목표이므로 QA는 데이터셋 추가 확보에는 사용하기 어려움
```


---

### 기존 멀티모달 시계열 데이터 관련 데이터셋에 다양한 시구간 길이에 기반한 물체, description 등의 메타정보 데이터셋 구축 계획 수립


작성 중
