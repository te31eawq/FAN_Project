# FAN_project

이 프로젝트는 선풍기의 강도 설정 및 타이머 기능을 제어하는 시스템입니다. 사용자는 버튼을 통해 선풍기의 동작을 제어하고, 타이머 기능을 사용하여 일정 시간 동안 선풍기를 동작시키거나 정지시킬 수 있습니다. 이 시스템은 다음과 같은 주요 기능을 제공합니다.

## 기능

### 1. **버튼 1: 강도 변경**
- 버튼 1을 누르면 선풍기의 강도가 **약**, **중**, **강**, **OFF** 순으로 변경됩니다. 
- 각 강도 설정에 따라 선풍기의 동작이 조정됩니다.

### 2. **버튼 2: 자동 반복**
- 버튼 2를 누르면 버튼 1의 강도 변경이 자동으로 3초 간격으로 반복됩니다.
- 강도는 **약**, **중**, **강**, **OFF** 순으로 돌아가며, 사용자가 종료할 때까지 계속 반복됩니다.

### 3. **버튼 3: 타이머 설정**
- 버튼 3을 눌러 타이머를 설정할 수 있습니다.
  - 3분, 5분, 7분으로 설정 가능.
- 타이머 설정 후, 버튼 4를 누르면 타이머가 시작됩니다.

### 4. **버튼 4: 타이머 시작**
- 버튼 4를 누르면 설정된 타이머가 시작됩니다.
- 타이머가 작동하는 동안 버튼 1과 버튼 2는 비활성화되어 선풍기의 강도를 변경할 수 없습니다.
- 타이머가 끝나면 선풍기가 자동으로 **OFF** 상태로 돌아갑니다.

## 사용법

1. **선풍기 강도 변경**  
   버튼 1을 눌러 선풍기의 강도를 **약** -> **중** -> **강** -> **OFF** 순으로 변경할 수 있습니다.

2. **자동 반복 모드**  
   버튼 2를 눌러 강도 변경이 3초마다 자동으로 반복되도록 설정합니다. 이를 통해 선풍기를 자동으로 조정할 수 있습니다.

3. **타이머 설정**  
   버튼 3을 눌러 3분, 5분, 7분 중 원하는 시간을 설정합니다. 
   
4. **타이머 시작**  
   버튼 4를 눌러 타이머를 시작합니다. 타이머가 작동하는 동안 버튼 1과 버튼 2는 비활성화됩니다.

5. **타이머 종료 후 선풍기 OFF**  
   타이머가 종료되면 선풍기가 자동으로 **OFF** 상태로 돌아갑니다.


```plaintext
my-project/              # 최상위 프로젝트 디렉토리
├── FAN_project/         # FAN_project 디렉토리 (선풍기 제어 시스템)
│   ├── main.py          # 프로젝트 실행 파일
│   ├── requirements.txt # 필요한 라이브러리 목록
│   └── README.md        # 이 문서
└── 기타 파일들         # 기타 관련 파일들

## 프로젝트 위치

이 프로젝트는 [my-project GitHub 저장소](https://github.com/te31eawq/my-project.git) 내의 `FAN_project` 디렉토리 안에 있습니다. 해당 저장소를 클론하여 사용할 수 있습니다.