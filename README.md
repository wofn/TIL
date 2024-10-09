# TIL
Today I Learned - 그날 공부한 내용 정리

## 2024-10-09
### 주제: 코딩 테스트 문제 풀이
#### 2675 문자열 반복 (반복문)
- 문제 설명: 주어진 문자열의 각 문자를 입력된 횟수만큼 반복하여 새로운 문자열을 생성하는 문제
- 접근 방법
  - 테스트 케이스의 개수를 입력
  - 각 테스트 케이스마다, 반복 횟수와 문자열을 입력
  - 문자열의 각 문자를 주어진 반복 횟수만큼 반복하여 새로운 문자열생성
  - 반복된 문자열을 출력

### 프로젝트: 이미지 객체 감지 및 시각화
- 프로젝트 설명
  -OpenCV와 Google Cloud Vision API를 사용하여 이미지에서 객체를 감지하고, 감지된 객체를 이미지 위에 시각적으로 표시한 후, 결과를 HTML 파일로 저장하는 프로젝트
- 구현 방법
  -OpenCV를 통해 이미지 처리 및 시각화를 수행합니다.
  -Google Cloud Vision API를 사용하여 이미지에서 객체를 감지합니다.
  -감지된 객체의 라벨에 따라 고유한 색상을 지정하여 경계 상자를 그립니다.
  -결과 이미지를 파일로 저장하고, 감지된 객체 정보를 포함한 HTML 파일을 생성하여 웹 브라우저에서 결과를 확인할 수 있도록 합니다.

## 2023년 10월 7~8일(SW-AI 융합 스마트 메이커 대회, 1박2일 대회)

### 프로젝트 1: 캘린더 앱과 블루투스 통신
- 앱에서 날짜 값을 블루투스 통신으로 아두이노에 전송하고 LCD에 출력하는 아이디어를 구상했으나, 통신 문제로 포기.

### 프로젝트 2: 오늘의 운세
- 버튼을 누르면 무작위로 운세를 LCD에 출력.
- 버튼을 누르지 않은 상태에서는 인사말 출력.

### 대회 회고
- 밤새워 코딩하면서 결과물을 만들어보려는 첫 경험.
- 노력 대비 결과물이 미흡했지만, 배운 점이 많았음.
- 블루투스 문제로 인해 앱 구현 실패.
- 코드 이해의 중요성 및 기본기에 대한 중요성을 느낌.

## 2024-10-06
### 주제: 조건문, 반복문 복습
- if, else if, else, switch
  - if, else if를 사용하여 조건을 평가하고, else를 사용하여 모든 조건이 거짓일 때의 동작을 정의
  - switch문은 동일한 변수에 여러 값을 비교해야 할 때 유용
- for, while, do-while
  - for문은 반복 횟수가 정해져 있을 때 유용
  - while문은 조건이 참인 동안 반복
  - do-while은 최소 한 번은 실행되어야 할 때 사용

### 주제: 코딩 테스트 문제 풀이
#### 2884 알람 시계(조건문)
- 문제 설명: 현재 설정된 알람 시간에서 45분 일찍 설정하는 문제
- 접근 방법
  - 입력 받은 시간에서 45분 빼는 계산
  - 분이 0보다 작을 경우, 시간을 1시간 감소하고 분에 60을 더하기
  - 시간이 0보다 작아질 경우, 24시로 설정하여 전날로 돌아가기

#### 8393 합 (반복문)
- 문제 설명: 1부터 n까지 자연수를 모두 더하는 문제
- 접근 방법
  - 반복문을 사용하여 1부터 n까지의 수를 순회하며 합을 계산(반복문을 활용한 누적합)






